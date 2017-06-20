So I just realised it's been more than two years since the last official SLADE release of v3.0.2. I doubt too many people end up reading this stuff, but I figured I should at least post some kind of news about how things have been coming along.

**3.1.0 and the Map Editor**

Since 3.0.2 was released, I have slowly been getting work done on the map editor component of SLADE3. Currently, it is fairly usable, although missing some features and somewhat buggy. As things are going currently, I don't really see it being complete any time soon. Because of this, I think it's about time I set some kind of cutoff in terms of features for the map editor, started fixing up the bugs and release a beta version of 3.1.0 for testing. Expect this sometime soon.

**Version Control and GitHub**

Recently I was beginning to realise that I just have too many different sources for bug reports, feature requests and the like. Between the ZDoom forums thread, the SLADE forums, IRC and email, it was getting increasingly difficult to keep track of all the feedback coming in. Additionally, there has been a (justifiable) move away from centralised VCS (cvs, svn, etc) to DVCS (git, mercurial, etc).

I decided to give Git a try, having the source repository for SLADE up at [GitHub](https://github.com/sirjuddington/SLADE). This brings multiple advantages, on top of those from using a DVCS, GitHub provides an issue tracker and wiki for the project. The issue tracker makes it much easier to keep track of outstanding bugs and feature requests, anyone can post an issue (just need to sign up for a GitHub account), and I can close said issues via commits when they are addressed. This will be the preferred method for bug reports and feature requests for 3.1.0.

The current SLADE wiki is hosted at Wikia, which while being decent enough for a free wiki host, has become a bit too ad-heavy, among other things. Over the last few days I have been moving the wiki content over to the [SLADE wiki](https://github.com/sirjuddington/SLADE/wiki) on GitHub, which is both nicer than Wikia aesthetically and has no ads.

**Documentation**

As a whole, SLADE noticeably lacks any real documentation. With the wiki move above, I plan to start writing up some proper documentation for SLADE interface and resource editor features on the GitHub wiki, while the 3.1.0 betas are in development. Once I get started on some of it (so as to have some examples of how the documentation should look), I would not be opposed to anyone else helping out with writing documentation/tutorial pages for the wiki :)

**Mac OSX**

SLADE is a cross-platform application, and while in the past I have been able to keep it working correctly on OSX, recently I have not been able to do so. As such, I am looking for anyone interested in helping maintain an OSX package for SLADE, so for 3.1.0 it can have an official OSX release. So yeah, if anyone is interested, let me know.

Well I guess that's it for now, stay tuned for the first beta for SLADE 3.1.0 in the coming weeks...