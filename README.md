# Alipay Payment Module for HostBill

## Introduction

The module is intened to replace the current broken payment module shipped with HostBill.

I reverse engineered the code and found it out of date, so I wrote this module according to Alipay's new API reference.

## Setup

Just upload these files to the <HostBill-Installation-Directory>/includes/modules/Payment/alipay2

Or execute following command in <HostBill-Installation-Directory>/includes/modules/Payment

```
git clone https://github.com/ym/alipay-hostbill.git alipay2
cd alipay2
git checkout tags/1.4
```

Login to Admin Panel on HostBill, then activate the payment module from Plugins section. Provide the required details for the module to work.

## Contributing

Bug report or pull request are welcome.

## License

Code licensed under MIT License.

The MIT License

Copyright (c) 1994-2014 Avelien Swan. http://swan.im

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
