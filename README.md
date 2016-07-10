# focotrain.ninja

## A collaborative project for #g31

##git practice

# Level 1: Cloning, Forking, Creating a Pull Request

1. Navigate to repository
    (https://github.com/zenvercoder/focotrain.ninja)

2. Fork the repository (Upper right hand corner. The page will navigate to YOUR fork.)

3. Clone YOUR FORK of the repository to YOUR LOCAL MACHINE (It's the URL when you hit the clone button)
    * Your username should be in the URL

4. Make your changes

5. Commit your changes (to your local repository... it's still on your machine at this point)

6. Push (its now in Github, but in your repository)

7. Make sure you're at your fork (your username/focotrain.ninja)

8. New Pull request

9. Compare across forks (a link under "Compare Changes")

* base fork = origin
* head fork = that's where you are
* Change the head fork on the right side to [myUserName/focotrain.ninja]
* It will show your commits, then hit:

10. Create pull request.

###Important terms:

* origin: There can be nothing before it/nothing above it
* master: It's like your own fork. You have to merge it back like with a fork, there's no separate origin
* You'll have a local master. then you have a remote master

### Rerefence links:

* https://help.github.com/articles/configuring-a-remote-for-a-fork/
* https://help.github.com/articles/syncing-a-fork/

# Level 2: Update your local copy with everyone else's changes.

## To get everyone else's change onto your local machine:

1. `git remote -v` (I haven't set the upstream)
2. `git remote add upstream https://github.com/zenvercoder/focotrain.ninja.git`
3. `git remote -v` (now it has origin and upstream)
4. `git fetch upstream`
5. `git pull`
6. `git status`
7. `ls`
8. `git checkout master`
9. `git merge upstream/master` pulling/updating into your own local copy
10. `git push` (copies it from your local to your remote)
11. Now you're ready to submit a pull request at this point.