# algorhth.ms host site template

### uses github to host the website, via a fork from max ogden ;).

This repo is just a simple (forkable) template with content edits that uses gh-pages http://pages.github.com functionality to host a static website for my radio show: Stereo Semantics. 

## Site Plan

- static file host
- entirely managed from the github.com web UI
- free
- able to use custom domains (so that yourdomain.com points to your files on github)
- very simple
- it's not a dynamic host, so not the best for any php/rails/node magic


## Dupe This

This repo is setup to only have the special **gh-pages** branch that github requires to use static file hosting. when you create and view repos on github they usually show you the default `master` branch which doesn't work with static file hosting

1. login to github and fork this repo [github.com/auremoser/algorhth.ms](https://github.com/auremoser/algorhyth.ms) or [max ogden's original template](https://github.com/maxogden/gh-pages-template)
2. you will need to edit a file in your forked repo so that github knows to deploy your static site! try going to index.html and clicking the edit button, making a small change, and then commiting your change
3. now you can go to **yourusername.github.com/gh-pages-template** and you should see the hello world page! it might take a few minutes for github to generate
4. using the github web UI you can [create new files](https://github.com/blog/1327-creating-files-on-github) or [edit existing files](https://github.com/blog/143-inline-file-editing)
5. the admin button at the top of the repo page will let you rename the repository
6. to point a custom domain at github edit the file called `CNAME` and make sure its contents are only `whateveryourdomainis.com` then go to your domain control panel and make sure the `A` record points to `204.232.175.78`. For more detailed instructions see [this article](https://help.github.com/articles/setting-up-a-custom-domain-with-pages)

Thats it!

## License
BSD licensed, as its code parent.
