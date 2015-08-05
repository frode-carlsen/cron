cron
====

 Cron expression parser and evaluator.  
 
 Allows for specifying cron - expressions (in Unix or Quartz like format) and evaluating when it will next match.
 
 Since it's specified on Joda-time it allows for easy integration into unit testing and simulations, by adjusting the Joda-time offset to speed up executions.
 
fork
====

 This project was forked from https://github.com/frode-carlsen/cron and has the following new features:

 - Seconds can be omitted in the cron expression.

 - No endless loop if a non existing date (february 30th) is specified in the cron expression. This fork uses a date/time barrier. If the search for the next execution date/time reaches this barrier, an InvalidArgumentException is thrown. This barrier can be user-defined, but has a built-in default of 4 years.
 
usage
=====
 See javadoc
