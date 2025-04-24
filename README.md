>> Remove Locally
git branch -d dev
git branch -d test

>> Remove Remotly
git push origin --delete dev
git push origin --delete test

                                    >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

>> Save your changes temporarily 
git stash

>>Switch to another branch
git checkout test(for example)

>>When you’re ready to get your changes back
git stash pop
