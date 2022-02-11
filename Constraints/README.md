# Constraints
### Filenames: 

- preference_#v_#u_#f_pattern_ID.txt
- mustHave_#v_#u_#f_pattern_ID.txt
- notAlone_#v_#u_#f_pattern_ID.txt

### The content of preference_#v_#u_#f_pattern_ID.txt:

#v #u #f pattern ID

C: conflict constraints

v1, v2

...

B: binding constraints

v1, v2

...

CA: conflict assignment constraints

v, u

...

BA: binding assignment constraints

v, u

...

### The content of mustHave_#v_#u_#f_pattern_ID.txt:

#v #u #f pattern ID

list(u for all u that has the mustHave constraint)

u, f, gf

...

### The content of notAlone_#v_#u_#f_pattern_ID.txt:

#v #u #f pattern ID

list(u for all u that has the notAlone constraint)

u, f, gf, E

...
