# ProjectDevelopment
Testing some xCode 12 Example with Github

### Setup
Create an xCode Project with a git repository, then add a remote from the SourceControl panel in the navigator. Then push the project from the SourceControl menu. 

### README?
Github now promps you to add a README.md file, which I did (obviously). A subsequent pull did not seem to download this file. I've read multiple complaints where xCode could now no longer sync with its remote. For now this didn't happen..

*[stops to commit and see...]*

And back... 
This README.md file is actually copied to the local repository, which, git-wise,  is totally correct. It just isn't added to the xCode Project - you can place all kinds of stuff in the project folder, but xCode won't see it. Solution: drag the file into the Project (directly underneath the main project name). Works a charm.

**Note:** when the file was not yet added to the project, I noticed that the **M** and **A** git markings were no longer visible on changed files. Once I dragged it in, they were all back. Coincidence?

**Musings:** Are there any downsides to this? For a private repo it wouldn't be necessary at all, would it? Who's going to see it? Or need a license for it? Or whatever?


