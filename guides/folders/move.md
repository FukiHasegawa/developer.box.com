---
rank: 5
tag: folders
related_endpoints:
  - put_folders_id
related_guides:
  - basics/folders/create
  - basics/folders/update
  - basics/folders/delete
required_guides: []
alias_paths: []
cId: folders
scId: null
id: folders/move
isIndex: false
---

# Move a folder

To move a folder, update the ID of its parent folder.

<Samples id='put_folders_id' variant='move' >

</Samples>

<Message warning>

This call will return synchronously. This holds true even for folder moves when
the folder contains a large number of items in all of its descendants. For very
large folders, this means the call could take minutes or hours to complete and
some parts of the tree are locked during moves.

</Message>