Logger library for TwinCAT

How to use
==========

1. Install and add the library to your project
2. Create an instance of at least one Logger, for instance ADSLogger
3. Add the logger instance to the event runner: TcLog.logging.add_logger(logger);
4. Use logging with TcLog.logging.error('Error message');
