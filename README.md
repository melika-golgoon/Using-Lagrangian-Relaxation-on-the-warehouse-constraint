# Using-Lagrangian-Relaxation-on-the-warehouse-constraint
It's an inventory control model with warehouse capacity constraint which the objective function minimizes total costs and the decision variables are number of pieces per order for each product (Q_i). This algorithm first calculates Q_i via Wilson formula then calculates the capacity occupied by this amount of ordering. if it makes the model infeasible, the capacity occupied by this amount of ordering outweigh the actual warehouse capacity, it will calculate the optimal Q_i by forming its Lagrange function.
