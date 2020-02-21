<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/logger](./logger.md)

## logger package

Logger for Firebase packages.

 This is specifically tailored for Firebase JS SDK usage, if you are not a member of the Firebase team, please avoid using this package

## Classes

|  Class | Description |
|  --- | --- |
|  [Logger](./logger.logger.md) |  |

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [LogLevel](./logger.loglevel.md) | The JS SDK supports 5 log levels and also allows a user the ability to silence the logs altogether.<!-- -->The order is a follows: DEBUG &lt; VERBOSE &lt; INFO &lt; WARN &lt; ERROR<!-- -->All of the log types above the current log level will be captured (i.e. if you set the log level to <code>INFO</code>, errors will still be logged, but <code>DEBUG</code> and <code>VERBOSE</code> logs will not) |

## Functions

|  Function | Description |
|  --- | --- |
|  [setLogLevel(level)](./logger.setloglevel.md) |  |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [LogHandler](./logger.loghandler.md) | We allow users the ability to pass their own log handler. We will pass the type of log, the current log level, and any other arguments passed (i.e. the messages that the user wants to log) to this function. |
