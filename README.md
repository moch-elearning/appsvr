# Appsvr

Application server written in C++, handling RPC and RESTful entities for
mulitble domians.

This backend are optimized for dojo usage, and supports the following 
features:

 * multi domain (compleate DB seperation)
 * Session support
 * Internal async event system
 * Multithreaded workload
 * JsonRPC 2.0 and SMD
 * RESTful JSON, csv and 2003 xml excel
 * Server Side Event

The application server are expandable using C++ modules that can be loaded 
as shared objects.
