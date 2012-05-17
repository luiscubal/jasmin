This is a new version of Jasmin modified to support "long" constants.
Old jasmin(2.4) allowed no way to do something like:

.field public static final lval J = 1

In the case above, lval would be associated with the integer constant 1, which is invalid.
The new version allows this:

.field public static final lval J = 1l

Aside from that, I've also changed the version number.

The original Jasmin is property of Jon Meyer.
I'm releasing this modified version under the same license as the original, which you can read in license-jasmin.
