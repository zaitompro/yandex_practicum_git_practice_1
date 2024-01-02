# PRACTICE 1
---
## README
---

```bash
mkdir foldername
cd foldername
touch filename.extention
vim filename.extension
git add filename.extension
git commit -m "some message"
git push
git log
git log --oneline
```

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit" --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```

