#Identity Manager - Keyrock

[![License badge](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Documentation badge](https://img.shields.io/badge/docs-stable-brightgreen.svg?style=flat)](http://fiware-idm.readthedocs.org/en/stable/)
[![Docker badge](https://img.shields.io/docker/pulls/fiware/idm.svg)](https://hub.docker.com/r/fiware/idm/)
[![Support badge]( https://img.shields.io/badge/support-sof-yellowgreen.svg)](http://stackoverflow.com/questions/tagged/fiware)

+ [Introduction](#def-introduction)
+ [How to Build & Install](#def-build)
    - [Docker](#def-docker)
+ [API Overview](#def-api)
+ [Advanced documentation](#def-advanced)
+ [License](#def-license)

---


<br>

<a name="def-introduction"></a>
## Introduction

This project is part of [FIWARE](http://fiware.org). You will find more information about this FIWARE GE [here](https://catalogue.fiware.org/enablers/identity-management-keyrock).

- You will find the source code of this project in GitHub [here](https://github.com/ging/fiware-idm)
- You will find the documentation of this project in Read the Docs [here](http://fiware-idm.readthedocs.org/)

Welcome to the main repository for the UPM's implementation of the FIWARE Identity Management Generic Enabler. Thanks to this component and together with PEP Proxy and Authorization PDP GEs, you will add authentication and authorization security to your services and applications.

<a name="def-build"></a>
## How to Build & Install

- Software requirements:

	+ nodejs 
	+ npm
	+ mysql-server

- Clone Proxy repository:

<pre>
git clone https://github.com/ging/fiware-idm.git
</pre>

- Install the dependencies:

<pre>
cd fiware-idm/
npm install
</pre>

- Duplicate config.template in config.js. 

- Generate certificates for https

<pre>
./commands_to_generate_keys.sh
</pre>

- Start server

<pre>
npm start
</pre>

<a name="def-docker"></a>
### Docker

We also provide a Docker image to facilitate you the building of this GE.

- [Here](https://github.com/ging/fiware-idm/tree/master/extras/docker) you will find the Dockerfile and the documentation explaining how to use it.
- In [Docker Hub](https://hub.docker.com/r/fiware/idm/) you will find the public image.

<a name="def-api"></a>
## API Overview



<a name="def-advanced"></a>
## Advanced Documentation

- [How to run tests](http://fiware-idm.readthedocs.org/en/latest/admin_guide#end-to-end-testing)
- [User & Programmers Manual](http://fiware-idm.readthedocs.org/en/latest/user_guide/)
- [Installation & Administration Guide](http://fiware-idm.readthedocs.org/en/latest/admin_guide/)

<a name="def-license"></a>
## License

The MIT License

Copyright (C) 2018 Universidad Politécnica de Madrid.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.