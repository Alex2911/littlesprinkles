sqlitewrapper - HOW TO USE
==========================
* Import the class
* Initiate the database:
    SQLiteManager * dbManager = [[SQLiteManager alloc] initWithDatabaseNamed:@"your.db"];

* Insert / update the database:
    [dbManager doQuery:@"Your Query - terminated by semicolon (;)"];

* Get a result (select):
    NSArray *DBReturn = [dbManager getRowsForQuery:UpdateDB2];

* Release:
    [dbmanager release];

base64 - HOW TO USE
===================
* Import the class

* Initiate the class:
    [Base64 initialize];

* Encode or decode
    NSData *data = [Base64 decode:EncodedData];
    NSString *EncodeString = [Base64 encode:SomeData];

LICENSE
=======

sqlitewrapper is licensed under MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


base64 is licensed under Public Domain License

Copyright notice:

sqlitewrapper:
  Created by Ester Sanchez on 10/03/11.
  Copyright 2011 Dinamica Studios. All rights reserved.

  Modified by Alex Jungwirth 09/04/11.
  Copyright 2011 Jungwirth Media

  Released under MIT License
---
base64:

  Created by Kiichi Takeuchi on 4/20/10.
  Copyright 2010 ObjectGraph LLC. All rights reserved.
 
  Original Source Code is donated by Cyrus
  Public Domain License
  http://www.cocoadev.com/index.pl?BaseSixtyFour
