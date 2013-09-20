octopress-semantic
==================

Add sematic web to octopress with:

- [The Open Graph protocol](http://ogp.me/)
- [http://schema.org/](http://schema.org/)
- [Twitter Cards](https://dev.twitter.com/docs/cards)

Checking tools:

- https://developers.facebook.com/tools/debug
- http://www.google.com/webmasters/tools/richsnippets
- https://dev.twitter.com/docs/cards/validation/validator

Usage
-----

Before using, you must install and configure this plugin first as description below.

In every post you should provide "cover" meta post for an image to be displayed on facebook open
graph and twitter cards when a post is shared.

For better SEO, you should also include `description` and `keywords` meta post.

Note: `author` meta post should be a twitter account to be mapped to twitter cards' author. This
needs improvement.

Requirements
------------

- [Octopress](http://octopress.org) version 2.0


Installation
------------

Download this project and copy its file contents from `source` directory into your octopress's
`source` directory.

Copy contents from `_config_semantic.yml` file into `_config.yml` file and make configuration.


Configuration
-------------

On `_config.yml` you should provide:

- `cover`: an image url. This image will be default displayed on every post, usually your logo, if
  `cover` is not specified on a post.

- `semantic_fb_app_id:` and `semantic_fb_admins:` are used for configuring facebook insights.


Contributing
------------

- File issues at https://github.com/hoatle/octopress-semantic/issues

- Follow Teracy's workflow at http://dev.teracy.org/docs/develop/workflow.html


Discussions
-----------

Join us:

- https://groups.google.com/forum/#!forum/teracy

- https://www.facebook.com/groups/teracy

Get our news:

- https://www.facebook.com/teracy.official

- https://twitter.com/teracy_official


Author and contributors
-----------------------

See more details at `AUTHORS.md` and `CONTRIBUTORS.md` files.


License
-------

BSD License

```
Copyright (c) Teracy, Inc. and individual contributors.
All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

    1. Redistributions of source code must retain the above copyright notice,
       this list of conditions and the following disclaimer.

    2. Redistributions in binary form must reproduce the above copyright
       notice, this list of conditions and the following disclaimer in the
       documentation and/or other materials provided with the distribution.

    3. Neither the name of Teracy, Inc. nor the names of its contributors may be used
       to endorse or promote products derived from this software without
       specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
