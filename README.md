# repo.macintoshgarden.org-fileset

To use, [Install Git-annex](https://git-annex.branchable.com/install/). It is available in most package managers.

Git-annex quickstart: [https://git-annex.branchable.com/walkthrough/](https://git-annex.branchable.com/walkthrough/)

```$ git-annex init [computer name]```
 
See total size of repo
  
```$ git annex info .```
  
How much space is taken up by a specific directory:

```$ git annex info repo.macintoshgarden.org/Garden/manuals/```

    directory: repo.macintoshgarden.org/Garden/manuals/
    numcopies stats: 
      numcopies +0: 1942
    repositories containing these files: 1
      6.64 GB: 00000000-0000-0000-0000-000000000001 -- web
    combined size of repositories containing these files: 6.64 gigabytes

Find the location of a particular file:

```$ git annex whereis repo.macintoshgarden.org/Garden/manuals/xyphus-manual.pdf```
 
 Fetch a file:
 
 ```$ git annex get repo.macintoshgarden.org/Garden/manuals/xyphus-manual.pdf```

Once you have a file, it will be stored locally, and you can send it to another repo p2p, or to a special remote.

