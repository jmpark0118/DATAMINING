## Datamining

### 1. bwplot & stripplot
<p>
    <img src="png/stripplot.PNG" width="400" />
</p>  

* how to draw bwplot and stripplot 
</br>
    
### 2. Handling missing values
* Ways to handle missing values
    + fill the values using `mean`
    + fill the values using `median`
    + fit values using a simple linear model
    + use observations that have the shortest distance `cluster::daisy`  
</br>

### 3. Linear model selection
<img src="png/model.PNG" width="250" hspace="50"/> <img src="png/linear_model_selection.png" width="500"/>  

* Forward Selection
* Backward Elimination
* Stepwise
* Regsubsets  `leaps::regsubsets`  
</br>

### 4. Tree
<img src="png/tree.PNG" width="400" hspace="50"/> <img src="png/tree2.PNG" width="220">

* How to find the best TREE using `cv.tree` and `prune.tree`
* Use `randomForest::randomForest` to apply **bagging** and **randomForest** methods
* Compare the MSE of various methods
</br>

### 5. LDA & QDA
<p>
    <img src="png/lda.PNG" width="400" />
</p>  

* perform `LDA` and `QDA` using
    + *iris* data
    + *Smarket* data (**ISLR** package)
    
