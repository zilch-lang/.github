Hello there! :wave:

If you've come that far, you must be interested in the Zilch project.
Let me give you a quick recap of how this organisation is managed.

### Repositories

There are already quite a lot of repositories, but here the most important ones:
- [`specification`](https://github.com/zilch-lang/specification) contains the TeX source code for the official specification document for the whole project.
  Releases are also created on each push to allow reading the generated PDF without needing to compile everything by hand.
- [`gzc`](https://github.com/zilch-lang/gzc) contains the source code for the compiler of Zilch.
  If anything goes wrong with Zilch, feel free to post issues there, we'll be happy to have feedback on it!
- [`nsc`](https://github.com/zilch-lang/nsc) contains the source code for the compiler of N⋆, the backend for Zilch.
  Same as for `gzc`, bugs are to be expected, therefore you must go there to report them.
- [`pkgs`](https://github.com/zilch-lang/pkgs) is an open collection of user-contributed packages.
  If you would like to have your package officially added as a Zilch package, head out there and create a new issue! (all instructions are present in the `CONTRIBUTING.md` file)
- [`rift`](https://github.com/zilch-lang/rift) hosts the source code of the package manager/build tool for Zilch.

Any repository which is not mentioned above is not important, but can still be curiously visited.

### History

This project is mainly a research project of [**@Mesabloo**](https://github.com/Mesabloo) which mainly supersedes [nihil](https://github.com/mesabloo/nihil).
While it aims to be solid and serious, bugs are to be expected because many features are very hard to coerce together.
If you encouter any bug, head to the correct repository and report a new issue (if no issue has already been reported for this).

### Current state

Zilch is still being designed (see [here](https://github.com/zilch-lang/gzc/discussions/4)) while N⋆ still needs to be documented and extended to support more operations.
