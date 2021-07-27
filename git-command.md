
## *kondisi sudah git init (direktori sudah update/ ada pekerjaan)

- git status
- git branch // cek branch
- git branch nama-branch // bikin branch
- git checkout (nama-branch) // pindah branch
- git add .
- git status
- git commit -m "pesan update"
- git push origin (nama-branch)

## Example

```
$ cd tarik-eb/
.../tarik-eb$ git init
Initialized empty Git repository in .../tarik-eb/.git/

.../tarik-eb$ git remote add origin https://gitlab.com/<url_repo>.git
.../tarik-eb$ git pull origin ainan-eb-flavor

Username for 'https://gitlab.com':
Password for 'https://username@gitlab.com': 
remote: Enumerating objects: 893, done.
remote: Counting objects: 100% (893/893), done.
remote: Compressing objects: 100% (504/504), done.
remote: Total 893 (delta 347), reused 817 (delta 273), pack-reused 0
Receiving objects: 100% (893/893), 111.84 MiB | 1.07 MiB/s, done.
Resolving deltas: 100% (347/347), done.
From https://gitlab.com/<url_repo>
 * branch            ainan-eb-flavor -> FETCH_HEAD
 * [new branch]      ainan-eb-flavor -> origin/ainan-eb-flavor

ainan@kayumanis:~/Documents/code/git/tarik-eb
```

## tutorial

Git Branch
- https://www.youtube.com/watch?v=e2IbNHi4uCI
