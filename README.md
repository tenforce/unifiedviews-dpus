# unifiedviews-dpu

This is intended as a meta-module to connect all the tenforce-dpus
which are available. More a place holder at present.

It is recommended that each plugin is in it's own git repository, this
makes it easier to follow up on issues and releases. To make it easier
to group related repositories a prefix is recommend, for unifiedviews
use uv-your-plugin-name.

You can create a new repository in the tenforce organization here:
https://github.com/tenforce. If you do not see a "new repository"
button, find someone with admin rights :). Follow the instructions
detailed on the new repository page (add the git remote and push),
make sure to include a readme and license. Typically TenForce licenses
it's open source software under the liberal Apache 2 or MIT licenses.

These modules should then be added to this repository as a sub-module.
For example:

  git submodule add https://github.com/tenforce/ods-lodms-plugins.git

