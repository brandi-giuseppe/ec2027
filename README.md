# Econophysics Colloquium 2027

Website of the 23rd Econophysics Colloquium (EC 2027), a workshop of ICCS 2027,
12–14 July 2027, AGH University of Kraków, Poland.

The site is a single self-contained file, `index.html`. No build step is needed.

## Publish on GitHub Pages

1. On GitHub, create a new **public** repository, for example `ec2027`.
2. Click **Add file → Upload files**, upload `index.html` and this `README.md`, and commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, set *Source* to
   **Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two the site is live at
   `https://brandi-giuseppe.github.io/ec2027/`

If your account already uses a custom domain for its user site, project pages are
served under that domain instead (for example `https://your-domain/ec2027/`).

## Editing

Edit `index.html` directly on GitHub (pencil icon) and commit; the site updates
automatically.

- **Programme committee**: the `<ul class="people">` list under
  *Scientific Programme Committee*. Keep it alphabetical by surname and update
  affiliations as members confirm them.
- **Invited speakers**: replace the *To be announced.* line with a list in the same
  format as the committee when you are ready to announce them.
- **Contact address**: uncomment the *Contact* block at the end of the committee
  section and add the email.
- **Dates**: the timeline in the *Important dates* section mirrors
  <https://www.iccs-meeting.org/iccs2027/important-dates/>. Update both the
  timeline and the hero if ICCS changes them. The hero chart reads its marker
  dates from the `MARKS` and `BAND` constants in the script at the bottom.

Remember that a public repository exposes the full source, including HTML
comments, so keep unpublished names and email addresses out of the file.
