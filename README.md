# python_imitation_of_ldd

# Notes on the code:

* The code was designed with chatGPT and my hand coding. It was also tested in replit.co website. The code may be a little buggy. (please create an issue tag and give information to aide in rectifying the error you're encountering)
* The code will give you the names of the imported libraries. It won't give you the full directory path to it (Sorry, man, I tried; even the computer said "TL;DR, human. I have my fork limit too")
* This was modeled with the idea of imitating the properties of the ldd command. Namely the dynamic linked and position Independent executable code.
  (you have to remember that their are two types of dynamic and one type of static in elf format. Do be mindful of that)
* The code works but finding the libraries will by onto you......

# "Anything you can do I can do better", why should I apply it as rule of thumb here?
The reason to do such is that it will improve the code and your understanding of software, application development, and archecture, as well as their unique artifacts.
 "All lands are also artifacts".

# Purpose of this library:
 the purpose is to analyze binaries, find functions, their names, and other libraries used the functions' addresses. This also could be used, with
  unicorn-engine & ctypes modules, to interface libraries & their functions to be usable by ctypes and a python based kernel... (here's a hint, I built one and it is
   sitting in my project-graveyard.)
