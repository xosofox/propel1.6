Phing and Propel Clone
======================

https://github.com/KaroDidi/propel1.6 and https://github.com/KaroDidi/phing are copies/clones of the official propel and phing SVN repositories.

The intention of these repos is to use them as a git submodule in your project.

For example, when working with Symfony2 and git, and using Propel as your ORM, you might be using

https://github.com/willdurand/PropelBundle

including it as a git submodule.

Since the bundle depends on phing and propel, you might want to include

    > git submodule add https://github.com/KaroDidi/phing vendor/phing
    > git submodule add https://github.com/KaroDidi/propel1.6 vendor/propel
