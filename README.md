# ExhibitEngine3
Development version of ExhibitEngine v3, building on original work by Pekka Saarinen
## Overall Aims
The overall aims of this project are to update ExhibitEngine so that it is usable in current MySQL/PHP environment.  The impetus for doing this was my ISP's decision to upgrade their PHP installations from version 5.x to version 7.x.  The `mysqli` library which EE2 used widely was removed and hence my website crashed.  As a quick and dirty hack I converted my installation to use PDO and I was able to get my site back up and running - after a fashion.  I kndew this was only a temporary solution, so my intention now is to rewrite the EE code base so that

* It uses the Bootstrap frame work.  This will both simplify the code and provide vastly improved support for mobile devices.
* It adopts a object-orientated programming approach.  This should provide more robust code that is also easier maintain and extend.
* Move all MySQL code from publicly accessible files to class definition files.  This should improve site security.
