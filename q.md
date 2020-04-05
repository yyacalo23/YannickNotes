# Q Notes

## Queries

### Efficiency

Hdbs are date paritioned.
Always add a date clause first to queries to reduce the directories kdb+ needs to look in.

```q
select from Quote where date = .z.d-1
```

## Joins

## lj


## ij


## aj


## File System

### Files and Filepaths

Find files in a directory:
```q
q) key `:/home/yyacalo/dir
,file
```
Create a file path:
```q
q) ` sv `:/home/yyacalo/dir,file
`:/home/yyacalo/dir/file
```
Create file paths for all files in a directory:
```q


```
### File Sizes

Find the uncompressed size of a file (2 ways):

Compress a file:

Find the compression stats for a file:

Find the compressed size of a file:

Open a handle to a file:

Close a handle to a file:

Delete a file:
