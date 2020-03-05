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
bbb-extra | ads | **a**nalyze **d**isk **s**pace
bbb-extra | als | **a**nalyze **l**og **s**pace
bbb-extra | ass | **a**nalyze **s**tream **s**pace
bbb-extra | ars | **a**nalyze **r**aw **s**pace
bbb-extra | aps | **a**nalyze **p**ublished **s**pace
**get**||
bbb-extra | gnr | **g**et **n**ow **r**unning
bbb-extra | gla | **g**et **l**ast **a**rchived
bbb-extra | gaa | **g**et  **a**ll **a**rchived
bbb-extra | glp | **g**et **l**ast **p**ublished
bbb-extra | gap | **g**et  **a**ll **p**ublished
bbb-extra | gd | **g**et **d**escription *meeting-id*
bbb-extra | gp | **g**et **p**articipants *meeting-id*
bbb-extra | gt | **g**et **t**ime *meeting-id*
**find**||
bbb-extra | fp | **f**ind **p**articipant
bbb-extra | fn | **f**ind meeting-**n**ame
bbb-extra | fd | **f**ind **d**ates date1 [date2]

### examples of using

`bbb-extra ars`
**analyze** (calculates) **raw** folder **size**

`bbb-extra glp`
**get** and print **last** 48h **published** meeting's ids 

`bbb-extra fn`
**find** meeting id by **name**

