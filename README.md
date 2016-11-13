# Simple-Blade
A light stand-alone Blade library for PHP

First, composer is not needed for Simple-Blade. 
To use Simple-Blade, just load the library and helper files.
For example, if you're using CodeIgniter framework, 
you'll only need to add 2 lines of code like the following to your project.

`$this->load->library('blade');`

`$this->load->helper('blade');`

And put you views in views folder (it can be customized easily), in addition with a `.blade.php` extension by default. 
So, the path would be something like `/views/filename.blade.php`

In order to render your views, you can pass blade like the following line.

`$this->blade->render('filename', $data);`

Enjoy!
