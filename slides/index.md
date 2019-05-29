- title : Full Stack Web in F#
- author : Tomasz Heimowski
- theme : night
- transition : default

***


## Full Stack Web

# in <span style="color: #e7ad52;">F#</span>

Tomasz Heimowski 

https://theimowski.com

<img src="images/twitter.png" style="width:48px; background: transparent; border: none; box-shadow: none"  />
<img src="images/github.png" style="width:48px; background: transparent; border: none; box-shadow: none"  /> 

*@theimowski*

***

## Full Stack Web

***

## TODO MVC

http://todomvc.com/

https://www.todobackend.com/

***

# F#

![F#](images/fsharp256.png)

* Microsoft origin, OSS
* **General** purpose
* Functional-first
* .NET / Mono / .NET Core / Web **browser**
* https://fsharp.org/

***

<img src="images/safe_stack.png" style="background: transparent; border: none; box-shadow: none" />


***

<img src="images/safe_top.png" style="background: transparent; border: none; box-shadow: none"  />

## big picture

</br> 

* Web stack
* Combines several OSS projects
* F# end-to-end
* Type-SAFE
* Cloud-ready
* Flexible

https://safe-stack.github.io

***

## Prerequisites

* [.NET SDK 2.2](https://www.microsoft.com/net)
* [FAKE 5](https://fake.build/) (global dotnet tool)
* [Node.js](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/) or [NPM](https://www.npmjs.com/)

<br/>
<br/>

#### or

* [Docker](https://www.docker.com)
* [VS Code Insiders](https://code.visualstudio.com/insiders/)
* [VS Code Remote Containers](https://code.visualstudio.com/docs/remote/containers)

***

## Creating SAFE project

* Install SAFE template: `dotnet new -i SAFE.Template`
* Create project from template: `dotnet new SAFE`
* Build & run: `fake build --target run`
* Wait for build to finish: app opens up in browser

***

<img src="images/safe_s.png" style="background: transparent; border: none; box-shadow: none"  />

## <span style="color: #e7ad52;">S</span> for <span style="color: #e7ad52;">S</span>aturn<span>

<img src="images/saturn.png" style="background: transparent; border: none; box-shadow: none" width="100" />

https://saturnframework.org/

* **Web server**
* ASP.NET Core, Kestrel

***

<img src="images/safe_a.png" style="background: transparent; border: none; box-shadow: none"  />

## <span style="color: #e7ad52;">A</span> for <span style="color: #e7ad52;">A</span>zure <span>

<img src="images/azure.png" style="background: transparent; border: none; box-shadow: none" width="180" />

https://azure.microsoft.com

* **Cloud** provider

***

<img src="images/azure_square.png" style="width: 200px; background: white"  />
<img src="images/google_cloud.png" style="width: 200px; background: white"  />
<img src="images/k8s.png" style="width: 205px; background: white"  />
<br/>
<img src="images/IIS.png" style="width: 210px; background: white"  />
<img src="images/docker.png" style="width: 210px; background: white"  />
<img src="images/heroku.png" style="width: 200px; background: white"  />



1. Azure AppService
1. Google Cloud AppEngine
1. Google Cloud Kubernetes Engine
1. IIS
1. Docker
1. Heroku

***

<img src="images/safe_f.png" style="background: transparent; border: none; box-shadow: none"  />

## <span style="color: #e7ad52;">F</span> for <span style="color: #e7ad52;">F</span>able <span>

<img src="images/fable_only_letter.png" style="background: transparent; border: none; box-shadow: none" width="100" />

http://fable.io

* F# to **JavaScript compiler**
* Babel JS

***

<img src="images/safe_e.png" style="background: transparent; border: none; box-shadow: none"  />

## <span style="color: #e7ad52;">E</span> for <span style="color: #e7ad52;">E</span>lmish <span>

<img src="images/elmish.png" style="background: transparent; border: none; box-shadow: none" width="140" />

https://elmish.github.io

* **UI library**
* inspired by Elm

***

<img src="images/safe_stack.png" style="background: transparent; border: none; box-shadow: none" />

***

<img src="images/safe_top.png" style="background: transparent; border: none; box-shadow: none"  />

## practical benefits

</br> 

* one language to rule them all
* after learning F# it's **really** easy to use!
* rich template with plenty options
* development experience taken to the next level
* Fable integrates nicely with JavaScript ecosystem
* Microsoft involvement
* community & commercial support

***


<img src="images/safe_top.png" style="background: transparent; border: none; box-shadow: none"  />

## what's more?

* [Sharing code](https://safe-stack.github.io/docs/feature-clientserver/) between Server and Client
* [Remote Devtools debugger](https://elmish.github.io/debugger/)
* [Full Stack Debugging in VS Code](https://safe-stack.github.io/docs/feature-debugging/)
* [Server-Side Rendering](https://safe-stack.github.io/docs/feature-ssr/) - Back-end React
* [ThoughtWorks Technology radar](https://www.thoughtworks.com/radar/languages-and-frameworks/safe-stack)
* Number of podcasts and [events](https://safe-stack.github.io/docs/events/) appearances

***

<img src="images/safe_top.png" style="background: transparent; border: none; box-shadow: none"  />


## resources

* [Docs](https://safe-stack.github.io/docs/) - SAFE in a nutshell
* Deep dive demo from [F# eXchange '18](https://skillsmatter.com/skillscasts/11308-safe-apps-with-f-web-stack) (video)
* [GitHub SAFE Stack org](https://github.com/SAFE-Stack/)
    * dotnet template (>23K NuGet downloads)
    * various sample apps
* Slides: https://theimowski.com/talk-full-stack-web-in-fsharp
* Source code: https://github.com/theimowski/SAFE-TodoMVC

***