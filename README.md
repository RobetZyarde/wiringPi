


#wiringPi README
===============
##How to install wiringPi

The easiest way is to use the supplied 'build' script:

  ./build
  
===============
##How to test wiringPi

1.To use 'gpio' comlmand in your terminal.

2.
    cd test
     make
hello --  for 8X8 RGB LED MATRIX
52pi -- for 128*64 OLED Module
lcd1602 -- for RGB 1602 Module
test -- a simple test for led on pin 7

===============

Please note that the official way to get wiringPi is via git from
git.drogon.net and not GitHub.

ie.

  git clone git://git.drogon.net/wiringPi

The version of wiringPi held on GitHub by "Gadgetoid" is used to build the
wiringPython, Ruby, Perl, etc. wrappers for these other languages. This
version may lag the official Drogon release.  Pull requests may not be
accepted to Github....

Please see

  http://wiringpi.com/

for the official documentation, etc. and the best way to submit bug reports, etc.
is by sending an email to projects@drogon.net

Thanks!

  -Gordon
