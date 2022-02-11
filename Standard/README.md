# Standard MDWBM
Filename: MDWBM_#v_#u_#f_ID.txt

The content of the instance file:

#v #u #f lambda_min lambda_max b ID

lambda_1, ..., lambda_#f

number_of_feature_values_1, ..., number_of_feature_values_#f

for f in F:
&nbsp for gf in number_of_feature_values_f
&nbsp &nbsp	list(cost_f_gf_u for u in U)

for v in V:
&nbsp list(gf_v_f for f in F)