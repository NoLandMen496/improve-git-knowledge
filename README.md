# Git By Example Anton

A guide to git led by example.

## Details

**website:** https://antonz.org/git-by-example/
**visit date**: 27-nov-2025

## Commands

### Change branch name

#### 1. Rename the local branch

If you are currently on the `master` to `main`

```bash
git branch -m master main
```

#### 2. Push the new branch to the remote

You need to push the new `main` branch to the remote repo.

```bash
git push -u origin main
```

### Connect remote to local repo

#### 1. Add the remote

```bash
git remote add origin git remote add origin git@github.com:USER/REPO.git
```

#### 2. Push the branch and set upstream

```bash
git push -u origin main
```

This does two things:

* pushes local branch to remote
* links `main` $\Leftrightarrow$ `origin/main`  

#### 3. If remote already has commits

```bash
git pull origin main --allow-unrelated-histories
git push -u origin main
```

## Tips

### Conflicts between remote and local repo

#### Clone remote first

The problem I faced was my remote repo had a commit already.
My local repo also had a commit.
Therefore, the repos had different histories.

To avoid the issue just create a new repo on git hub and clone it locally.
Or create an empty remote repo. 
