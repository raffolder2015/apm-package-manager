# apm
you know apt? this is apt but CUSTOM. and cross-platform.  
it is a simple package manager that uses a method of getting packages similar to that of apt. actually it is basically the same, except there are .zip's and not .deb's.  
this is the source code, for an actual `.exe`/`.deb` just check the releases.
# capabilities?
well, it has the capabilities of a package manager. that being, installing, removing, ....... installing, removing. that's basically it.  
this has a `pack` and `unpack` feature, which is just... zipping and unzipping but it's kind of comfortable to have.  
idk that's basically it, do what you will, adhere to my littly dumb very serious license, and whatever.  
enjoy and have a good day.
# i forgot the installation
you can install it through... the releases. obviously.  
for the .deb you can just use `sudo apt install <deb here>`, obviously.  
for the .exe you can just put the bin folder into windows PATH.  
for mac os..... i don't know anything about mac os so go figure.
# how to use
you just use the command line, and if you type `apm help` or just `apm` it will give you the help thing.  
but just in case, i'll explain it here.
ok so, to install and uninstall you use `apm install` and `apm remove` or `apm uninstall`. you can specify multiple packages. for installing from a file, use the `-f` flag and type the path to the file.  
to pack, you use `apm pack` and then the path to a folder to pack. it will put the files that are in that folder into a `.zip`. to unpack, you use `apm unpack` and then the path to the `.zip`.  
i have to say, `apm unpack` is basically the same as `apm install` just that it puts it in a folder in the current directory rather than installing it in the actual installation directory.  
because this is for a multitude of packages, you can use `:` and then the name of a type of package (e.g. `:python`). if you don't specify the package type, it will try to find the package and if there are duplicates it will tell you. also, the package type comes before the package type.  
# requesting a package
if you want to contribute and add a package, then go ahead. i'll happily accept any pull requests.  
packages are in the `lib` folder, and inside it there are the different categories. put it in the respective category of your package.  
after that, create a pull request, put your fork in there, and just wait when i pass by, i guess.  
ok that's it. bye have a good day.  
