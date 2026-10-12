# Charlie Pet Shop

Mobile-first website for Charlie Pet Shop, Muzaffarpur.

Website: https://shirazhashmi.github.io/charlie-pet-shop/
Owner gallery: https://shirazhashmi.github.io/charlie-pet-shop/admin/

## For the owner

1. Open the owner gallery link on your phone.
2. Sign in with your login ID and password.
3. Tap **Choose photos / videos** and select up to 30 files.
4. Give each file a title and select a section.
5. Tap **Publish selected files**. Wait until each says **Published**.

Photos: JPG, PNG or WebP. Videos: MP4 or WebM. Maximum 25 MB each. Use short compressed videos for faster uploads. Uploads are public after publishing.

Use **Save** to update an existing title or section. Use **Hide from website** to hide an item; **Show on website** restores it. Hiding removes the gallery listing; the media URL remains accessible to anyone who has it. Keep your password private and sign out on shared devices. To change it, open **Change your password** in the owner page.

No GitHub editing is needed for daily gallery updates. Supabase stores new media, gallery titles and categories. Passwords are managed by Supabase Auth. Database and storage policies restrict writes to the registered owner. Public connection settings in config.js are safe to publish; never add secret/service-role keys or passwords.

## Site maintenance

GitHub Pages publishes the root of the main branch. No build or dependencies are required. Keep admin/index.html in the admin directory. config.js contains the public backend URL/key and maps the simple login ID to the owner's Auth account. The original supplied media stays in the repository; newer uploads use Supabase Storage.

Store hours are pending owner confirmation. Maps opens an address search; a verified business pin can replace it later. Both phone numbers are present. No custom domain has been configured.
