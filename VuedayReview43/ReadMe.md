Key value is the most significant in rendering font-page by vue, because vue constrasts every DOM elements between before changing DOM and after changing DOM, thus the KEY value supports VUE model to contrast between these two DOMS, and add/delete/put/get in correct DOM postion.
Key value should be using the data.id which is the best way to bind the Virtual DOM,