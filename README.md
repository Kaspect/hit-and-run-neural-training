# hit-and-run-neural-training


0. Run existing scala space code on dev machines with finger H matrix


1. Write function to make a circle function that fits in the feasible wrench space
2. Compute the force vectors for each of 1000 points along that circle in force space.
3. For each of the force vectors, compute 1000 feasible points into a matrix called X_t, rows = points, cols = muscles
4. Verify that any given X_t make sense
algorithm
5. create an Array[X_t=1, X_t=2, ..., X_t=k] where *X* is a feasible point matrix, *t* is the timeslice, *k* is the number of force vectors. Call it the KpolytopeArray
6. first_X_list <- grab all even numbered elements in the Kpolytope Array
7. second_X_list <- grab all odd numbered elements in the KpolytopeArray
8. zipWith (elements_where_getting_from_1_to_2_is_feasible) first_x_list second_x_list
9. 

define return_elements_where_getting_from_1_to_2_is_feasible
