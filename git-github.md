# Git & GitHub


- e.g. For banking, the account balance and banking statement would be a **snapshot**, while transaction history would be **delta storage**.
## What is Git?
Git is  Version Control System (VCS)
![Git Logo](./images/git-logo.png)

 - *However*, it handles information in a completely different from other VCSs, so you should see Git as a separated concept to avoid confusion
 - The main difference is that Git uses **Snapshot storage**, while other VCSs typically use **Delta storage**

#### Snapshot storage vs. Delta storage  
- **Snapshot storage**: Git stores data as a stream of snapshots.
  - Each snapshot represents the system state at a given time
  - Git will store unchanged files as a link to the previous identical files
  - More simple and efficient, but can consume a lot of storage
  
- **Delta storage** (delta-based version control): Other VCMs store data based only on file or system changes, rather than the entire state.
    - **Delta**: The difference between the current version and the previous version
    - All the **deltas** are combined to rebuild a system state
    - More complex, but can save on storage

Although delta storage is more storage-efficient, snapshot storage makes more sense for getting an accurate, updated representation.

Now, back to Git:

 - Git generally works with your local files and resources; even if you have no internet or VPN access, you can still <code>commit</code> your changes to your local copy
   - Other VCMs may allow file edits, but do not allow "offline" database commits
 - Everything in Git is **checksummed**
  - All changes, incomplete transfers, and file corruptions are detected by Git
  - Git database stores everything by the **hash value** of its contents, not by file names
  - Git generally only <code>add</code> data, which improves data recovery by making it difficult to erase committed data


Git is the VCS, and GitHub is the one of many remote repository hosting sites.

***
## What is GitHub?
GitHub is a web-based service for hosting **remote repositories**
![GitHub Logo](./images/github-logo.png)

- You can use Git without GitHub, but GitHub needs Git to work

So, why bother using GitHub?
- Collaboration and Project Management: GitHub improves team collaboration with features like pull requests, code reviews, and issue tracking, as well as tracking commit histories to quantify individual contribution
- Access Control: You can choose the visibility and access rights of your code
- Documentation: GitHub Wikis and readme.md files are available as documentation tools  
- Remote repository backup: Even if your machine spontaneously combusts (or you lose your local directory in any way), as long as you have committed your local changes to the remote repository, you will be able to restore your files and directories from anywhere else!
- **CI/CD**: Continues Integration and Continuous Delivery. You can use **GitHub Actions** to automate your workflow to build, test, and deploy
- Portfolio / Networking: Remote repositories allow sharing of resources, contributions to public projects, and also allow you to showcase your projects and portfolio to peers and companies alike
- Web UI: GitHub has a user-friendly web interface, which is a helpful addition to command line controls
  
## Set Up GitHub
//todo


***

## Sources
https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F
https://blog.git-init.com/snapshot-vs-delta-storage/
https://docs.github.com/en/actions/about-github-actions/understanding-github-actions
