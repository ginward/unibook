# Unibook

This is the Unibook Textbook Exchange platform. It consists of a iOS client written in Objective-C and Server written in JavaScript (NodeJS).

The Server uses a non-SQL database - MongoDB and Redis-data store. The config file for the password to DB can be found at Server/config.js

It is recommended that you use a server acting as a reverse-proxy (such as Nginx). The server is written so that it is scalable. You can run multiple instances in the background. 

The iOS client is not the strength of this project. I have to confess that I am not an expert in making the User Interface work with all sizes of the iPhones. 

I used Flurry to collect App performance data such as the number of Unique Visitors. You can delete Flurry from the AppDelegate.m and AppDelegate.h meanwhile removing the flurry library from the project.

The code is released under the MIT license. Have fun.

The MIT License (MIT)
Copyright (c) <2015> <Jinhua Wang>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
