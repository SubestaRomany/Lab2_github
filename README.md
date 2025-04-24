>> Remove Locally           ___
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


                                 >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

>> List all tags
          ___git tag

>> Delete a tag locally
        ___git tag -d v1.7

>> Delete a tag from the remote repo
        ___git push origin --delete tag v1.7

                                  >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

>> Example with image from the internet

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)



>> Example with local image (if image is in the repo folder)
![Logo](images/logo.png)






