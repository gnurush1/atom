### Requirements

* Filling out the template is required. Any pull request that does not include enough information to be reviewed in a timely manner may be closed at the maintainers' discretion.
* All new code requires tests to ensure against regressions

### Description of the Change

This change is meant to give an idea about which code can allow native menus to scale with external applications.

### Alternate Designs

There were no alternative designs

### Why Should This Be In Core?

While it is a purely visual change, it could potentially help some developers better customize their Atom experience.

### Benefits

Better versatility with external applications

### Possible Drawbacks

May potentially cause a security problem allowing external applications to acquire code

### Verification Process

Ran it with the Gnome application on Linux. Currently is not working, but the concept is there for others to attempt a better fix.

### Applicable Issues

So far this is only compatible with Gnome's application for Linux.
