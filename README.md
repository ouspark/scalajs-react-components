scalajs-react-components
========================

[![Join the chat at https://gitter.im/chandu0101/scalajs-react-components](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/chandu0101/scalajs-react-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Reusable [scalajs-react] (https://github.com/japgolly/scalajs-react) components

#### Status

Its work in progress...

#### Setup

Library is not published to maven central as its still work in progress

To publish Locally  : 

```scala
 git clone https://github.com/chandu0101/scalajs-react-components
 cd scalajs-react-components
 sbt publishLocal

```
Using in Projects : 
```scala
// add this line to your build.sbt
libraryDependencies += "com.chandu0101.scalajs-react-components" %%% "core" % "0.1.0"

```

#### Demo With Code Examples 

**Online :** 

http://chandu0101.github.io/sjrc/

**Local :** 
```scala
cd demo
sbt ~fastOptJS
//open a new terminal tab/window
npm install
npm start
//open in browser
http://localhost:8090/webpack-dev-server/

```

#### Docs 

http://chandu0101.github.io/sjrc/docs

#### Contribute 
http://chandu0101.github.io/sjrc/#contribute

