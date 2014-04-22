# Canvas LMS Cloud
Operate a self-hosted private [Canvas LMS](https://github.com/instructure/canvas-lms) cloud installation, powered by [Ansible](https://github.com/ansible/ansible).

## Features
* High availability, fault tolerant, and horizontal scaling design
* Nginx used as an SSL terminator, static cache, and a round-robin load balancer
* Redis leveraged for improved system performance
* Handling for multiple physical datacenter setups
* Handling for multiple application servers with round robin load balancing
* Handling for multiple database servers (PostgreSQL clustering)
* Handling for multiple reverse proxies, SSL terminators, static caches, load balancers
* Handling for dedicated application server(s) to run automated jobs
* Security hardening at multiple levels

## Requirements

One or more Ubuntu 14.04 LTS servers with:
* OpenSSH server installed
* Basic network interface and hostname configured
* SSH keys transferred

## License
```
The MIT License (MIT)

Copyright (c) 2014 Rocky Madden (http://rockymadden.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```