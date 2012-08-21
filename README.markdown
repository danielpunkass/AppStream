# AppStream

A minimal Mac OS X app.net client

## REQUIREMENTS

* Mountain Lion
* Xcode 4.5(latest beta), _maybe_ 4.4
* Courage

## HOWTO

* <del>Create a app.net client app.</del>
* <del>Use "x-com-toxicsoftware-appstream:///" as the Callback URL.</del>
* NEW: I've embedded a client_id into the source. You do not need to make your own app on app.net.
* Don't forget to do a submodule update: git submodule update --init
* Build and run the app, follow the instructions for setting the client id

## GOALS

* I want to make a stable featureful app.net client that works _really_ well in full screen mode. Whether this means multiple column (tweetdeck style but less shit) or not is up for debate

## TODO/BUGS

* UI is ass. Not too interested in UI until basic network and database functionality is there.
* Overloading of the term stream: https://alpha.app.net/schwa/post/52516 - this is a problem in code. As real app.net streams come online I expect a refactor will be needed.
* User Lists
* User Info
* Post detail view
* Database will grow and grow. Need to prune at some point.
* Code is being "sketched out" and is far from well designed. Expect a lot of churn/refactoring
* <del>Deleting</del> (implemented)
* <del>Refresh</del> (implemented)
* <del>Polling</del> (implemented)
* <del>Posting</del> (implemented)
* <del>Replies</del> (implemented)
* <del>User notifications</del> (implemented)

## FEATURE IDEAS

* Use the Latent Semantic Mapping framework to classify posts
* Intelligently handle hashtags, usernames, urls etc - provide popover contextual info/actions on these item, e.g. hashtags popover will have a "view all posts with this hashtag" action.
* Markdown support
* Built in filtering, blocking, spam control and triggered actions
* Relying on server to fix spam problem is foolish
* Actions include user notifications, scripts?
* Built in fav star style functionality
* Statistics on your behavior and on per people (how spammy is that person, how many tweets per hour enter my stream)

## LICENSE

* I haven't included a license yet but all code will be licensed under the BSD 2 clause license.
