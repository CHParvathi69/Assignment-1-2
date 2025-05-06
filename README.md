# Git Assignment 1 ----- ----- 2

# Assignment 1: 
Basic Git Workflow

---

## Steps Followed:

### 1. **Initializing Git Repository:**

I initialized a local Git repository in the `GitAssignment1&2` folder using:

```bash
git init
```

This created a `.git` folder to track all changes.

### 2. **Creating the File: `Amazon.txt`:**

I created `Amazon.txt` and added the Poem:

```txt
In emerald hush, where wild vines weave,
The jungle breathes beneath each leaf.
A symphony born from parrot cries,
With golden frogs and velvet skies.

The rivers curl like whispered spells,
Through roots and dreams where magic dwells.
A sunbeam dances on the panther's fur,
While orchids bloom where breezes purr.

The Amazon sings secrets of old
A tale of life in green and gold.

```

### 3. **Making the Initial Commit:**

The initial commit was done using the following:

```bash
git add Amazon.txt
git commit -m "Initial Commit: Amazon rainforest poem"
```

### 4. **Making Changes with Commits:**

#### **Commit 1: updated imagery**
updated imagery for frogs and skies:

```txt
With sapphire frogs and twilight skies.
```

Commit message:

```bash
git commit -m "Commit 1: update imagery for frogs and skies"
```

#### **Commit 2: changed 'panther' to 'jaguar'**
Changed 'panther' to 'jaguar' for regional accuracy:

```txt
A sunbeam dances on the panther's fur,

```

To:

```txt
A sunbeam dances on the jaguar's fur,

```

Commit message:

```bash
git commit -m "Commit 2: changed 'panther' to 'jaguar'"
```

#### **Commit 3: Added closing line**
Added closing line to enhance the poem:

```txt
Nature's breath is forever free.
```

Commit message:

```bash
git commit -m "Commit 3: added closing line to the poem"

```
### 5. **Git Log:**

Used the command to view commit history:

```bash
git log --oneline
```
![Git Log Screenshot](https://github.com/CHParvathi69/Assignment-1-2/blob/main/Git-log.PNG)


---

### 6. **Git Diff:**

To compare changes:

**Last Two Commits:**

```bash
git diff HEAD^ HEAD
```

**First and Third Commits:**

```bash
git diff HEAD~3 HEAD
```

---

## Files Used:

- `Amazon.txt`: The Amazon file with changes.
- `Git-log.png`: Screenshot of the Git log output.