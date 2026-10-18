Rana Hendawy Portfolio - source

Open locally:
  Double-click index.html (keep the media folder and rana.jpg next to it).
  An internet connection is needed only for the web fonts.

Put it online for free:
  Netlify: go to app.netlify.com/drop and drag this whole folder onto the page.
  GitHub Pages: upload the folder's contents to a repository, then Settings > Pages > Deploy from branch.
  Either one can be linked to your own domain later (e.g. ranahendawy.com).

Edit content:
  Tools and profiles are in index.html, inside the <script> block:
    var profiles = { ... }   tool features, versions, video paths
    var lib = [ ... ]        the tool list
    var times = {}           manual vs. with-tool hours, e.g.
                             times["ExBOQ v2"] = {m: 6, a: 0.5};
