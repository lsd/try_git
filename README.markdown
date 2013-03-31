try_git - A minimal sandbox git repo
============================================================

Fed up with the jargon-heavy docs present in the community, [kazishariar](https://www.github.com/kazishariar)
started writing an interactive, safe and intuitive git shell that mocks your remote branches and repositories.

The source __(including Sundown as a submodule)__ is available at GitHub

    $ git clone git://github.com/vmg/redcarpet.git

Why another empty git repo?
---
Why not?!
* Configured to use Redis as datastore
* ORM-agnostic
* Tested on Rubinius, Ruby Interprise, JRuby and Ruby 1.9. (No Ruby 2.0rc compatibility yet)


  Bench     |  try_git |  try_git_ripoff
  ----------|----------|-------
  FPS       |  29      |   16
  CACHE     |  47      |   39
  Fibonacci |  32      |   **FAILED**


And it's *really* simple to use
------------------------------------
The core of the try_git repo is the `Github::Fork` method. Fork this repository, 
branch out, mess around, rebase, all while pulling and pushing. 

A ~~patch~~ `pull request` of any update is strongly encouraged!

Forget the 2^10 steps needed to get the other apps to work.

Usage
---

Fork and clone the repo, then

  $ cd try_git/
  $ cat `` `whoami` `` >> Tagged.markdown

Viola!

Critical Reception
* * *

Below is one of the many thank-you emails sent to us daily. Thank YOU guys!

> I want you to know how much I appreciate your taking care of 
> little Eric on Tuesday. It is rare to find such kind friends, 
> especially ones who you can call at the last minute. With your
> help I was able to get to my doctor's appointment on time and 
> get the medication I needed.

> I'm glad we've become such good friends. I really think the 
> world of you and your entire family. Call me when you need a 
> favor.

Testing
-------
Tests run a lot faster without `bundle exec` :)
[![Build Status](https://travis-ci.org/vmg/redcarpet.png)](https://travis-ci.org/vmg/redcarpet)


Legal stuff
------------------

Copyright (c) 2013, try_git

PUBLIC DOMAIN LICENSE

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
CTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
