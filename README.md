# GH-odil
#!/bin/bash
#
echo "Hello Class!"
echo "Today is $(date)."
echo "Do you want to play soccer? (yes/no)"
read answer

if [[ "$answer" == "yes" ]]; then
        echo "Great! Let's play."

elif [[ "$answer" == "no" ]]; then
        echo "Okay, maybe next time."
else
        echo "Sorry, I didn't understand your response." 
fi