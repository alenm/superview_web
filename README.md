![info](https://superview.dev/images/metatag.png)


# Superview
[Superview](https://superview.dev) is a collection of videos about mac, iOS, Swift development from conferences around the world. Presentations range on topics like design, security, frameworks, swift, xcode and many other finer things.

#### What is this site?
This website is a repository of past conference videos that deal with topics on design and development of apple software products. The initial inspiration for this site came from http://www.pomo.tv but that website and github repository has not had much activity lately. So I decided to build this.

#### Features
  * Put everything in a database (Postgres)
  * Use Phoenix as the [technology stack](https://phoenixframework.org). I wanted to learn a new framework for a project
  * Avoid embedding a video iframe. Instead load video thumbnails that would take you to website.
  * Create an API so developers can make iPhone or Apple TV app. Navigate to "/api" to see results.
  * The '/api' does exist I have not made it available yet.

#### Contributing New Content
The videos are Youtube or Vimeo. I have been adding and index content.  To contribute new content create a pull request with details about the event, a URL to the event and where the videos are hosted. I have included a parser file that can parse the details from Youtube and Vimeo playlists and map them to any existing speakers in the database.

#### (Coming soon) Editing Existing Content 
This is a bit tricky. I'm thinking of making a CSV available that people can edit within the Repo.

#### (Coming soon) Install 
You need to install [Elixir](https://elixir-lang.org/install.html) on your computer.
