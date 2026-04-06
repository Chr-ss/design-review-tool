# trade-off, improvements and ideas

## UI/UX and Pages
- focus on simple and functional UI/UX
- no options to rank designs or add notes/tags
- UI badge colors are not matching for same values
- responsiveness needs improvements
- loading, empty, and error states are simple not polished

### overview
- no filter
- no search
- no sorting
- limited to about 9 designs

### comparison page
- limited to two options
- limited to simple side-by-side view
- no visual support to compare values

## Data
- simple SQLite + Prisma local setup
- simple calls to DB for prototype not for scale
- no pagination and server-side filtering
- tags as a simple comma-separated string
- single public JSON source for import with simple mapping
- only add/imports are supported no edit or delete
- no protection for duplicate entries

## Infra
- monolith setup is simple but not flexible
- focus only on "works locally and is easy to run"
