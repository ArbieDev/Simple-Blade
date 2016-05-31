# Simple-Blade
A light stand-alone Blade library

To use Simple-Blade library, just simply load the files. 
For example, if you're using CI framework, 
you'll need to add something like the following lines to your function __construct().

`$this->load->library('blade');`

`$this->load->helper('blade');`

And you'll need to put you views in views foler, in addition with a `.blade.php` extension by default. 
So, the path would be something like `/views/filename.blade.php`

In order to return your view, you can pass blade like the following line.

`$this->blade->render('filename', $data);`

Hope you will enjoy Simple-Blade!
