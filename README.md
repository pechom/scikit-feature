changes in this fork:

CFS now ends, when its subset has number of features stated in new treshold parameter. Features with zero division in merit calculation (zero entropy) have it's error catched and are excluded from final set.

Gini index values are initialized with value of 1, not 0.5 (0.5 not usable when you have more than 2 classes).

