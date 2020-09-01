# ebook-rename
Change ebook (epub and mobi) names to "[author] - [title].ext"

Ebooks downloaded from Telegram come with non-relevant filenames. This script reads epub and mobi files, extracts title and author from the ebook and renames the file with a more relavant name.

It uses the ebook parsing libraries from:
https://github.com/aerkalov/ebooklib
https://github.com/kroo/mobi-python
