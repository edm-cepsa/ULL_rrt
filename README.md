# ULL_rrt
rocktyping propagation from core wells to all existing wells


The model will be constructed from the RRT interpertation provided by the OPCO at the core samples, this model will be based on the well logs available in all wells to increase our chances of propagation.

Reviewing the provided data from the OPCO we only have a "log with SRT", therefore the process has been to sample this interpretation to the core data ( it has the depth correction applied , but this is CEPSA correction, as the OPCO has not delivered the official one.



2021 sept 9

Optimization run working on the set of logs that maximizes the roc_auc for Kharaib and Lekhwair respectively.


We stopped in 8 logs

The best cases were for Lekhwaair

0.9199219

"XGR"          "XSRES"        "XRHOB"        "XPHIT"        "res_diff_log" "res_diff_lin" "log_XPERM"  

and for KHAraib

0.9164546

"XGR"       "XRHOB"     "XPHIT"     "log_XPERM" "log_XDRES" "log_XSRES"



 sept 23 using the most common logs
 
 Kharaib
 
 0.9063501 
 
 XGR XSRES XPHIT res_diff_log res_diff_lin log_XPERM
 
 lekhwair
 
 0.9127637 
 
 XGR XSRES XPHIT res_diff_lin log_XPERM log_XDRES