# Moshnod Blogger Theme

Custom Blogger theme for মসনদ ⎸Moshnod (moshnod.blogspot.com). Deep ash gray
news portal design, white default background, Device/White/Black theme switch,
centered মসনদ masthead, breaking banner, hero story plus grid, "আজকের ৫টি বড়
খবর" list, live rail, colour-coded section blocks (বাংলাদেশ, রাজনীতি, ব্যবসা,
স্বাস্থ্য, মতামত), full article pages with deck, key points, and source links.

## Files

- `blogger-theme-moshnod.xml`: the live theme (879 lines). Built 2026-11-15 from
  the verified Shironamhin Dohon theme structure.

## How to apply it to a Blogger blog

1. In Blogger, open the blog and go to Theme. Back up the current theme first.
2. Open Edit HTML, select all, paste the file contents, and Save. (Theme >
   Restore upload does not work via automation; a person picking the file in
   the dialog works.)
3. Check the live blog: the homepage should show the post feed, and a post page
   should show the full article. In Layout, the main section must show the Blog
   Posts gadget.

## Notes

- The theme's `html` tag must NOT carry `b:version`, `class="v2"` or
  `expr:lang` attributes. An earlier Dohon theme had them and Blogger silently
  ignored the post widget, leaving the feed empty.
- Blogger has no GitHub integration and no theme API, so this repo is the
  master copy only. Applying a new version still needs the paste step in
  Blogger.
- News posts are published separately: the Moshnod pipeline rewrites stories
  from Bangladesh news portals and publishes them as Blogger posts.
