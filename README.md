
OVERVIEW
============

JFirePHP takes Joomla-FirePHP integration to the next level.

This version of JFirePHP is for **Joomla 3.0 and over** only (presumably still works on Joomla 2.5) because there're versions for 1.5 and 1.6+ (1.7, 2.5) available:

* For Joomla 1.5: by [Kunena Team](http://joomlacode.org/gf/project/kunena/frs/?action=FrsReleaseView&release_id=11823)
* For Joomla 1.6+: based on 1.5 version but a bit altered. Not sure by whom but you can find it [hosted by webeks.net](http://www.webeks.net/joomla/jfirephp-in-joomla-16.html) (**UPDATE**: Link is dead :-( )

The 3.0 version is still based on 1.5 version but strips out some redundants, for example, support for PHP4 since Joomla 2.5 and up doesn't support PHP4 anymore.

Simply install the system plugin via the Joomla Extension Manager and make sure it is published. This version already has the option "Limit to Joomla Debug mode" set to "No", so please consider to install it only on Development stage. It is not suitable for Production sites.

USAGE
============

Once JFirePHP has been installed you can leverage all of the FirePHP (`fb()` and `FB::*`) functionality in your code. See the [FirePHP Headquarters](http://www.firephp.org/HQ/Use.htm) for detailed information about FirePHP and its usage.

For feedback and support please kindly create an issue on this repository.

LICENSE
============
Software License Agreement (New BSD License)

Copyright (c) 2006-2009, Christoph Dorn
All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice,
      this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
      this list of conditions and the following disclaimer in the documentation
      and/or other materials provided with the distribution.

* Neither the name of Christoph Dorn nor the names of its
      contributors may be used to endorse or promote products derived from this
      software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
