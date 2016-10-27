# molns_cloudpickle

This class is defined to override standard pickle functionality

The goals of it follow:
1. Serialize lambdas and nested functions to compiled byte code
2. Deal with main module correctly
3. Deal with other non-serializable objects

It does not include an unpickler, as standard python unpickling suffices
Copyright (c) 2009-2012 `PiCloud, Inc. <http://www.picloud.com>`_.  All rights reserved.
email: contact@picloud.com

The cloud package is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.
This package is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.
You should have received a copy of the GNU Lesser General Public
License along with this package; if not, see 
http://www.gnu.org/licenses/lgpl-2.1.html
