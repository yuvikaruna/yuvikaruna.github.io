Run these in git bash before running respective files```
chmod +x remove_and_push.sh
chmod +x set_origin.sh
chmod +x commit_local.sh
`

Run
 ```set_origin.sh 
remove_and_push.sh
```
in seprate folder

```set_origin.sh ```
this will create .git (local repo) then adds link with yuvikaruna.github.io(remote repo) .And fetch files from remote and merges with local


```remove_and_push.sh ```

this file removes all files in dir ,then adds commit message and pushed to remote


run  in dist ```set_origin.sh 
commit_local.sh
```

``` commit_local.sh ``` 

This should be run after set_origin.sh ,this pushes ng build code to remote
