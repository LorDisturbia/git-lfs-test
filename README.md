# git-lfs-test

Minimal implementation of a repository that uses a third party server to manage Git LFS files.

The repository [needs some minimal configuration](https://docs.github.com/en/enterprise-server@2.20/admin/user-management/configuring-git-large-file-storage-for-your-enterprise#configuring-git-large-file-storage-to-use-a-third-party-server) in the form of a [.lfsconfig](./.lfsconfig) file. In this case the test uses a [minimal implementation](https://github.com/git-lfs/lfs-test-server) running locally on my machine.

The only thing that the server needs to do is to implement some [API](https://github.com/git-lfs/git-lfs/tree/main/docs/api).