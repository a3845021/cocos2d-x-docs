<div class="langs">
  <a href="#" class="btn" onclick="toggleLanguage()">中文</a>
</div>

## Cocos2d-x Programmers Guide v3.16
v2017.10.03

 __Authors:__ SlackMoehrle, Ricardo, Justin, Nite, Kai, Minggo, Wenhai, Tony, Yingtao, Rao, Huabin, Zhe

__CSS enhancements:__ Nico

__Contributors/Editors:__ stevetranby, Maxxx, smitpatel88, IQD, Michael, Meir_yanovich, catch_up, kidproquo, EMebane, reyanthonyrenacia, Fradow, pabitrapadhy, Manny_Dev, ZippoLag, kubas121, bjared, grimfate, DarioDP

__Special Thanks:__ To our users! Without you there is no reason to even write this guide.

Please provide feedback for this guide on [GitHub](https://github.com/cocos2d/cocos2d-x-docs)

You can download the samples for this guide on [GitHub](https://github.com/chukong/programmers-guide-samples)

## Why choose Cocos2d-x

Why would you want to choose Cocos2d-x over other available game engines?

  * Modern C++ API (please refer to the modernizing done in [__version 3.0__](https://github.com/cocos2d/cocos2d-x/blob/cocos2d-x-3.0/docs/RELEASE_NOTES.md#c11-features))

  * Cross-platform - desktop and mobile

  * Capability to test and debug your game on the desktop and then push it to a
  mobile or desktop target

  * A vast API of functionality including sprites, actions, animations, particles,
  transitions, timers, events (touch, keyboard, accelerometer, mouse), sound,
  file IO, persistence, skeletal animations, 3D

### Where to get Cocos2d-x and what do I get?
You can clone the [__GitHub Repo__](https://github.com/cocos2d/cocos2d-x) and follow the steps in the [__README__](https://github.com/cocos2d/cocos2d-x/blob/v3/README.md). You can also download as part of the Cocos package on our [__download page__](http://cocos2d-x.org/download). No matter if you choose to develop in C++, JavaScript or Lua, everything you need is in one package. The Cocos family of products has a few different pieces.

  * __Cocos2d-x__ - this is the game engine, itself. It includes the engine and the
  [__cocos__](http://cocos2d-x.org/docs/editors_and_tools/cocosCLTool/index.html) command-line tool. You can download a [__production__](http://cocos2d-x.org/download)
  release or stay bleeding edge by cloning our [__GitHub Repo__](https://github.com/cocos2d/cocos2d-x).

  * __Cocos Creator__ - is a unified game development tool. You can create your
  entire game, from start to finish, using this tool. It uses JavaScript. Lua and
  C++ support are being added. Read more about [__Cocos Creator__](http://cocos2d-x.org/docs/editors_and_tools/creator/index.html).

  * __Cocos Launcher__ - is a graphical tool to create and manage your projects.
  This is also an easy way to add SDKBOX plugins to your project. [__Documentaion__](http://cocos2d-x.org/docs/cocos/cocos/index.html)
  is available.

  * __Coco Studio__ - is EOL'd and has been replaced by __Cocos Creator__. [__Documentation__](http://cocos2d-x.org/docs/deprecated/studio/index.html)
  is still available.

  * __Code IDE__ -  is EOL'd. Common text editors and IDE's can be used instead.

### Conventions used in this documentation
* `auto` is used for creating local variables.
* `using namespace cocos2d;` is used to shorten types.
* each chapter has [__a compilable source code sample__](https://github.com/chukong/programmers-guide-samples) to  demonstrate concepts.
* class names, methods names and other API components are rendered using fixed fonts. eg: `Sprite`.
* *italics* are used to notate concepts and keywords.
