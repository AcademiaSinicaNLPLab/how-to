Git
======

#### What is git?

> Git is a free and open source __distributed__ __version control system__

I'll skip this part since Goolge provides a bunch of related articles.


#### Why use git?

- Version control
- Easy to share, work with others
- A little story
 
  - Before I met git, I backup my programs in this way:
  
    ```vim
    /maxis/project
      | awesome.py
      | awesome_05_16.py
      | awesome_05_16_1630.py
      | awesome_05_17_final.py
      | awesome_05_18_final_v2.py
      | awesome_05_19_final_final.py
    ```
  - I backup the current one before rolling back to previous version (sometimes I forgot and everyone heared the F-word)
    ```vim
    $ cp awesome.py awesome_final_final_v2.py
    $ cp awesome_05_16_1630.py awesome.py
    ```
  
  - Now with Git, the directory is super clean!
    ```vim
    /maxis/project
      | awesome.py
    ```
  - Git maintains the commit history for me
    ```vim
    $ git hist
    * dc646a6 2014-05-16 | add git notes (HEAD, origin/master, origin/HEAD, master) [maxis]
    * 97f4884 2014-05-16 | Update README.md [Maxis]
    * 7f383c9 2014-05-16 | Initial commit [Maxis]
    ```

  - Rollback? No pain at all.
    ```vim
    $ git reset 97f4884
    ```


#### Who uses git?
