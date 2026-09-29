Lij's Kitchen - ready to deploy

This folder is a complete static site:
  index.html      the page
  videos/         the 4 clips

VERCEL (from a Mac):
  1. Install Node from nodejs.org if you don't have it.
  2. Open Terminal, then:   cd path/to/this/folder
  3. Run:                   npx vercel --prod
  4. Log in when asked, press Enter to accept the defaults.
  5. It prints your live link (something.vercel.app).

VERCEL (no Terminal): upload this folder to a new GitHub repo, then go to vercel.com/new,
import the repo and press Deploy (Framework: Other, leave build settings empty).
