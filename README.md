# Threejs Spine 3.8 runtime in ES6
A threejs-spine 3.8 runtime lib which is built in es6
## Why?
* The latest threejs uses ES6 and the libs in https://github.com/EsotericSoftware/spine-runtimes/tree/3.8/spine-ts/build are not compatible.
* Offical recommendation is to upgrade all dependencies/projects to 4.X.X. however, some legacy projects are still using 3.8. \*sign\*

## Licensing

You are welcome to evaluate the Spine Runtimes and the examples we provide in this repository free of charge.

You can integrate the Spine Runtimes into your software free of charge, but users of your software must have their own [Spine license](https://esotericsoftware.com/spine-purchase). Please make your users aware of this requirement! This option is often chosen by those making development tools, such as an SDK, game toolkit, or software library.

In order to distribute your software containing the Spine Runtimes to others that don't have a Spine license, you need a [Spine license](https://esotericsoftware.com/spine-purchase) at the time of integration. Then you can distribute your software containing the Spine Runtimes however you like, provided others don't modify it or use it to create new software. If others want to do that, they'll need their own Spine license.

For the official legal terms governing the Spine Runtimes, please read the [Spine Runtimes License Agreement](http://esotericsoftware.com/spine-runtimes-license) and Section 2 of the [Spine Editor License Agreement](http://esotericsoftware.com/spine-editor-license#s2).

## Documentation
please check 
[Spine Runtimes Guide](http://esotericsoftware.com/spine-runtimes-guide)
[spine-runtimes Github](https://github.com/EsotericSoftware/spine-runtimes)

## Build
git clone this repo
```
npm ci
npm run build
```

## WARNNING 
I did not test all details and features, but it works as expected for my use cases. Feel free to fork and do more magics.

Offical 3.8 threejs spine runtime
`https://github.com/EsotericSoftware/spine-runtimes/blob/3.8/spine-ts/build/spine-threejs.js`
Latest npm threejs spine runtime
`https://www.npmjs.com/package/@esotericsoftware/spine-threejs`
