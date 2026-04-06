# this-is-luke-repository
My first repository
and i am leraning linux and i will show some codes
and this a code that says what your take to school fo r lunch

#!/usr/bin/env bash

for snackdraw in lays talkies doriatos cheesto "grilled chesse" "fried chicken"
do
    if [[ $snackdraw == "lays" ]]
    then
        echo "Today is Monday and I take $snackdraw to school"

    elif [[ $snackdraw == "talkies" ]]
    then 
        echo "Today is Tuesday and I take $snackdraw to school"
    
    elif [[ $snackdraw == "doriatos" ]]
    then 
        echo "Today is Wednesday and I take $snackdraw to school"
    
    elif [[ $snackdraw == "cheesto" ]]
    then 
        echo "Today is Thursday and I take $snackdraw to school"
    
    elif [[ $snackdraw == "grilled chesse" ]]
    then 
        echo "Today is Friday and I take $snackdraw to school"

    elif [[ $snackdraw == "fried chicken" ]]  
    then
        echo "Today is Saturday and i am going to eat $snackdraw"
    fi
done
