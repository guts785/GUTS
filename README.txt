# HOW TO ADD BOOKS
# ================
# 1. Drop your PDF file into the books/ folder
# 2. Drop a cover image (optional) into the covers/ folder
# 3. Edit books.json and add an entry like this:
#
# {
#   "id": "unique-id",
#   "title": "عنوان الكتاب",
#   "title_en": "Book Title",
#   "author": "اسم المؤلف",
#   "author_en": "Author Name",
#   "category": "philosophy",
#   "description": "وصف مختصر للكتاب",
#   "description_en": "Short description",
#   "filename": "your-file.pdf",
#   "cover": "covers/your-image.jpg",
#   "pages": 250,
#   "language": "ar",
#   "added": "2026-05-30"
# }
#
# Available categories: philosophy, history, logic, ethics,
#   metaphysics, political, islamic-philosophy, other
#
# Make sure each book has a unique "id".
# The filename must match the actual PDF file in books/ folder.
