# allcoreessentials.com – static site (GitHub Pages)

Still to do before going live
1. (done) Leaf photo is included.
2. Contact form: create a free form at formspree.io for connect@allcoreessentials.com and replace YOUR_FORM_ID in index.html and contact/index.html (two forms).
3. Check the wording that was not visible in your screenshots (Delivery sections, rest of the Leadership paragraph).

Deploy
1. New PUBLIC GitHub repo, upload everything in this folder, Settings > Pages > Deploy from branch (main, root).
2. Pages > Custom domain: www.allcoreessentials.com, then tick Enforce HTTPS. (CNAME file is included.)
3. GoDaddy DNS: CNAME www -> <your-github-username>.github.io, and four A records for @ -> 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153. Remove the old Wix records. DO NOT touch the MX / email records.
4. When the new site works on your domain, cancel the Wix plan.
