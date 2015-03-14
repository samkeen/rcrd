## This is a Micro storage engine for domain objects.  It talks over HTTP and is targeted at pure HTML/Javascript clients. ##

## Goals ##

  * Persistence Engine targeted at HTML(5) clients
  * Constrain to a REST interface as closely as possible while still allowing for HTML/JS only clients.
  * Simplicity over Features: get the simple things right before considering new functionality
    * No PHP file (Class) over 300 lines (w/ comments and logging)
    * Implement features in as few of lines as possible.