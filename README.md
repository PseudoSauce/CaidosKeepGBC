Caidos Keep
=============

Welcome to Pseudo Sauce's open source code of Caidos Keep!

Caido's Keep is a 3rd-person role playing game. Originally developed by a group of 5 Game Programmers for an assignment for school.

Installation
----------------------

The steps below will take you through cloning your own private fork, then compiling and running the editor yourself:

### Windows

1. Install **[Git Bash](https://git-scm.com/downloads)**.

1. Install **Visual Studio 2015**. 
   All desktop editions of Visual Studio 2015 can build UE4, including [Visual Studio Community 2015](http://www.visualstudio.com/products/visual-studio-community-vs).
   Be sure to include C++ support as part of the install, which is disabled by default.

1. Install **[Unreal Engine](https://www.unrealengine.com)** version 4.13.x. We're currently using 4.13.1.

1. Launch the engine and in the Unreal Project Browser, refresh to have the project pop-up. If it doesn't show up, click the 'Browse...' button at the bottom right of the window and navigate to the project repo and open the '.uproject file'.

Contributions
---------------------------

**Original Five**<br/>
@aytona<br/>
@CarloAlbino<br/>
@demallory<br/>
@wahidshafique<br/>
@wambasic44<br/>


We welcome any contributions to the project through pull requests on GitHub.
We try to follow the [Epic coding standards](https://docs.unrealengine.com/latest/INT/Programming/Development/CodingStandard), although not as strict.

License
----------------

CaidosKeepGBC is under [Apache 2 License](http://www.apache.org/licenses/LICENSE-2.0.html), meaning you can use it free of charge. 


Additional Notes
----------------

You must unzip all folders inside Content to get all .uasset and .umap from the project. Also, you must zip them back up to commit.

Initially, we used Git LFS to track these files but since this is just a school project we didn't want to bother paying for additional storage capacity. Instead, we are using Perforce for our daily usage and will just upload to GitHub after each milestones reached.

