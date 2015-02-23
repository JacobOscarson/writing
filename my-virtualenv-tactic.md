# How I manage my virtualenvs

TL;DR: The same directory as the project itself.

Pro's

  * Predictable paths to scripts and library sources
  * Server auto-reloads / directory watchers will restart my server on
    changes in third-party dependency (typically because I set a debug
    breakpoint to find out how something actually works).
