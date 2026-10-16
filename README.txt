Knowledge book - standalone site
1) Upload this whole folder to Vercel (drag and drop, or "vercel" from the folder). No build step.
2) Each page loads its own HTML file from the content/ folder:
   content/dictionary.html      (included)
   content/fixed-rates.html
   content/current-offers.html
   content/galileo-pnr.html
   content/playbook.html
   content/umrah.html
   content/tourism.html
   Put each page's existing embed HTML in the matching file and redeploy. A missing file shows a friendly notice.
