# Install Pocketbase

1. Run ./pocketbase.ext serve
2. Login with Admin
3. Create new Collection -> notes
4. Create 2 Field 'text' (title, content)

# Fix Bug

_notes/[id]/error.tsx_ harus ada 'use client' karena membuat error, error-nya pun tidak terlihat pada debug sehingga membingungkan
