# ESPWebServer
HTTP server library for ESP8266/ESP32 Arduino cores (previously ESP8266WebServer)

Forked from https://github.com/esp8266/ESPWebServer

I made the changes to this Arduino/ESP8266 Library to complete a name-change ofr the library, which was originally started by the developer.

 o  Updated file name from ESP8266WebServer.h .cpp to ESPWebServer.h .cpp
 o  Corrected all references/handlers/function calls to use ESPWebServer (not ESP8266WebServer)
 o  Updated all companion files and examples to use correct file names and function calls/handlers.
 
 +  Made sure all the examples compile and tested with the following
     IDE:  Arduino Studio beta (arduino-PR-beta1.9-BUILD-119) 
     IDE:  Arduino Studio nightly build (1.8.13 Hourly Build 2020/04/21 12:33)
     Board:  NodeMCU 0.9 1.0
 
 *  AdvancedWebServer - Works correctly
 *  FSBrowser - Works when using IP address.  Does not resolve (http://esp8266fs.local/edit)
 *  HelloServer - works correctly
 *  HttpBasicAuth - works correctly
 *  SDWebServer - works correctly
 *  SimpleWebServer - works when using IP.  Does not resolve esp8266sd.local
 *  WebUpdate - Works correctly when using IP.  Does not resolve http://esp8266-webupdate.local
 
 AHD 4/30/2020
 
