# parsnip 0.0.0.9003

* `regularization` was changed to `penalty` in a few models to be consistent with [this change](tidymodels/model-implementation-principles@08d3afd). 

# parsnip 0.0.0.9002

* To be consistent with `snake_case`, `newdata` was changed to `new_data`. 
* A `predict_raw` method was added. 

# parsnip 0.0.0.9001

* A package dependency suffered a new change. 

# parsnip 0.0.0.9000

* The `fit` interface was previously used to cover both the x/y interface as well as the formula interface. Now, `fit` is the formula interface and [`fit_xy` is for the x/y interface](https://github.com/topepo/parsnip/issues/33). 
* Added a `NEWS.md` file to track changes to the package.
* `predict` methods were [overhauled](https://github.com/topepo/parsnip/issues/34) to be [consistent](https://github.com/topepo/parsnip/issues/41).
* MARS was added. 