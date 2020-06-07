# Shell XAML Snippets for Visual Studio

[Luis Matos](https://twitter.com/luismatosluna) has organized [an entire month of community blogging](https://luismts.com/code-snippetss-xamarin-month/) around code snippets. He gives a fine definition of what code snippets are, but I'll give you my definition.

> You know the stuff that you have to write over and over, but can never quite remember the ceremony? The same stuff you find in an old project, or some blog, or some GitHub repos and promptly forget to make it easy to access. Those are code snippets. 

I don't maintain my own collection of code snippets, primarily because I'm a lazy developer. Also in my role at Microsoft I reinstall my Visual Studio environment often. Oh, and because until today I didn't $#*&#$^ know how to add snippets. Now that I've done it, I'll promptly forget. :P

## Shell Snippets

In the spirit of my very clinical definition above, I considered what code I kept copy-pasting from other projects because I couldn't be bothered to memorize them. Shell in Xamarin.Forms makes it really easy to create an app with a flyout menu or tabs. It's the next level of customizing those that I end up snagging from other projects. No longer! I hereby present to you my new collection of Shell snippets!!!

> Disclaimer: these are currently for VS Windows only. You can create snippets for XAML in VS Mac, however there's a bug that stops you there.

### Shell

* ShellStyles - `shell-styles` will generate the styles for all the app-level colors and options

### Flyout

* FlyoutMenu - `flm` will scaffold out a series of flyout items
* FlyoutItem - `fli` will generate a single flyout item
* FlyoutItemStyles - `fl-styles` gives you the different styles needed for the label, image, and background of the item
* FlyoutItemTemplate - `temp-flyout` will give you the default flyout item template that you can then expand and customize

### TabBar

* TabBar - `tb` will scaffold out a tab bar with several tabs
* Tab - `tab` will generate a single tab item

> Currently tabs cannot be templated and styles are not implemented. This is coming on the [Xamarin.Forms roadmap](https://aka.ms/xf-roadmap). 

### MenuItem

* MenuItemTemplate - `temp-menu` will give you the default menu item template that you can then expand and customize

## In Conclusion

If you need guidance on how to implement snippets in Visual Studio 2019, head on over to the [documentation guide](https://docs.microsoft.com/visualstudio/ide/code-snippets?view=vs-2019). 

Thanks again to Luis for organizing yet another great community effort.

Thanks to [Tim Heuer](https://twitter.com/timheuer) for his 2013 blog about [creating XAML code snippets](https://timheuer.com/blog/xaml-code-snippets-for-visual-studio/).