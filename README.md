# c-log
Logging library in C

Usage:
```C
LOGCONF log_conf = {
        .MAXLOGLEVEL = CONST_LOGGING_LEVELS.VERBOSE,
        .CONSOLE = false,
        .OUTPUT = "./log",
        .MAXFILEMB = 1000,
        .CICLE = true,
        .CICLES = 5
    };
UseLogConfig(&log_conf);
log_verbose("Starting service...");
log_error("No data was retrived, shutting down service.");
```
