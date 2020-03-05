Here i'm planning to work on additional scripts and custom settings that add
extra-abilities and simplify getting meetings information 
by command line interface

## bbb-extra

bash script

---
main actions
- analyze
- get
- find
---
**key description table**

command|key|description
--- | --- | ---
**analyze**||
bbb-extra | ads | analyze disk space
bbb-extra | als | analyze log space
bbb-extra | ass | analyze stream space
bbb-extra | ars | analyze raw space
bbb-extra | aps | analyze published space
**get**||
bbb-extra | gnr | get now running
bbb-extra | gla | get last archived
bbb-extra | gaa | get  all archived
bbb-extra | glp | get last published
bbb-extra | gap | get  all published
bbb-extra | gd | get description *meeting-id*
bbb-extra | gp | get participants *meeting-id*
bbb-extra | gt | get time *meeting-id*
**find**||
bbb-extra | fp | find participant
bbb-extra | fn | find meeting-name
bbb-extra | fd | find dates date1 [date2]

### examples of using

`bbb-extra ars`
**analyze** (calculates) **raw** folder **size**

`bbb-extra glp`
**get** and print **last** 48h **published** meeting's ids 

`bbb-extra fn`
**find** meeting id by **name**

