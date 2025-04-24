>> Remove Locally    
   ___
   git branch -d dev
   git branch -d test

>> Remove Remotly
___
     git push origin --delete dev
     git push origin --delete test

                                    >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

>> Save your changes temporarily 
    ___
 git stash

>>Switch to another branch
    ___
 git checkout test(for example)

>>When you’re ready to get your changes back
 ___
   git stash pop
