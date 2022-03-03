# Project-4--Machine-Learning

Team Name: The Last Hurrah!

Team Members: 
Tim Smith
Kristen Hanold
Shermeen Ajani

Topic: 
MUSHROOMS!

Dataset: 
https://archive.ics.uci.edu/ml/datasets/Mushroom
"Sources: 
    (a) Mushroom records drawn from The Audubon Society Field Guide to North
        American Mushrooms (1981). G. H. Lincoff (Pres.), New York: Alfred
        A. Knopf
    (b) Donor: Jeff Schlimmer (Jeffrey.Schlimmer@a.gp.cs.cmu.edu)
    (c) Date: 27 April 1987"

What problem are we solving? 
We wanted to learn how to identify if a mushroom is edible or poisonous based on its characteristics.  The data set included 22 characteristics can be used to identify if a mushroom is poisonous or not.  Based on the characteristics there were 4,208 edible (51.8%) and 3,916 poisonous (48.2%) mushrooms in the dataset.


What are we analyzing? 
We analyzed the physical characteristics of the mushrooms using the UCI Mushroom dataset (link to the dataset above).

"Attribute Information: (classes: edible=e, poisonous=p)
     1. cap-shape:                bell=b,conical=c,convex=x,flat=f,
                                  knobbed=k,sunken=s
                                  
     2. cap-surface:              fibrous=f,grooves=g,scaly=y,smooth=s
     3. cap-color:                brown=n,buff=b,cinnamon=c,gray=g,green=r,
                                  pink=p,purple=u,red=e,white=w,yellow=y
     4. bruises?:                 bruises=t,no=f
     5. odor:                     almond=a,anise=l,creosote=c,fishy=y,foul=f,
                                  musty=m,none=n,pungent=p,spicy=s
     6. gill-attachment:          attached=a,descending=d,free=f,notched=n
     7. gill-spacing:             close=c,crowded=w,distant=d
     8. gill-size:                broad=b,narrow=n
     9. gill-color:               black=k,brown=n,buff=b,chocolate=h,gray=g,
                                  green=r,orange=o,pink=p,purple=u,red=e,
                                  white=w,yellow=y
    10. stalk-shape:              enlarging=e,tapering=t
    11. stalk-root:               bulbous=b,club=c,cup=u,equal=e,
                                  rhizomorphs=z,rooted=r,missing=?
    12. stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s
    13. stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s
    14. stalk-color-above-ring:   brown=n,buff=b,cinnamon=c,gray=g,orange=o,
                                  pink=p,red=e,white=w,yellow=y
    15. stalk-color-below-ring:   brown=n,buff=b,cinnamon=c,gray=g,orange=o,
                                  pink=p,red=e,white=w,yellow=y
    16. veil-type:                partial=p,universal=u
    17. veil-color:               brown=n,orange=o,white=w,yellow=y
    18. ring-number:              none=n,one=o,two=t
    19. ring-type:                cobwebby=c,evanescent=e,flaring=f,large=l,
                                  none=n,pendant=p,sheathing=s,zone=z
    20. spore-print-color:        black=k,brown=n,buff=b,chocolate=h,green=r,
                                  orange=o,purple=u,white=w,yellow=y
    21. population:               abundant=a,clustered=c,numerous=n,
                                  scattered=s,several=v,solitary=y
    22. habitat:                  grasses=g,leaves=l,meadows=m,paths=p,
                                  urban=u,waste=w,woods=d"

Included in the repository is:
1) Deep Learning Analysis: 
      a) Training a Neural Network Model using all 22 characteristics in the data set
      b) Training a Neural Network Model using a subset of characteristics based on prior knowledge, experience and educated guess
      c) Training a Neural Network Model using the 6 key characteristics identified in the README included with the dataset from UCI and using automated hyperparameter testing

2) Tableau Workbook
3) PowerPoint

Findings:
The six characteristics listed below are sufficient for identifying a mushroom as edible or poisonous:
      a) Odor
      b) Spore Print Color
      c) Habitat
      d) Population
      e) Cap Color
      f) Stalk Surface Below Ring
