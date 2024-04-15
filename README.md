#asdf-docker

1. `asdf-install-plugins` - Goes through your .tool-versions and installs the
   plugin for each tool. Properly propagating exit codes so you can use it in another
   Docker image build.
2. `asdf-install-versions` - Goes through your .tool-versions and installs the
   missing tools for you. Properly propagating exit codes so you can use it in another
   Docker image buld.
