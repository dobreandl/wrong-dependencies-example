
# Description

Demo project for highlighting the mACS process.

It showcases all the output phases of mACS in a project in which an unallowed dependency is present.

The MVC unallowed dependedency resides in the [CustomView.swift](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/View/View.swift), it has knowedge about the [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/demoWrongDependencies/Model/Model.swift) which is forbbiden in Apple's MVC.

This wrong dependency is correctly identified by mACS.

## Codebase

* [Swift Project](https://github.com/dobreandl/wrong-dependencies-example/tree/master/demoWrongDependencies)

## Extraction phase output

* [Model](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/json/model.json)
* [View](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/json/view.json)
* [Controller](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/json/view_controller.json)

## MVC Analysis results

* [Results](https://github.com/dobreandl/wrong-dependencies-example/blob/master/demoWrongDependencies/results/Screenshot%202020-03-14%20at%2012.28.27.png)


