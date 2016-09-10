# self-destructo
The infamous Russian Roulette bash script - now with sound!

A friend and I were inspired to spruce up the following bash script:

    [ $[ $RANDOM % 6 ] == 0 ] && rm -rf / || echo *Click*

Our version has a little lower stakes, simply deleting itself should the gun go off. Ours also has sound effects!

Run in a terminal with 

    ./self_destruct
    
And if you wanna go around again, just

    cp self_destruct.bkp self_destruct
    
