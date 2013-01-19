These are my standard Eclipse settings. Use them well.

# Eclipse version

I chose these settings on 3.6.1 build 20100917-0705

# Install

While you could just copy the files over as below, this might result in overwriting some
paths in your existing configuration.   My recommendation is to just merge the config files
if it's anything but a fresh eclipse install.

    git clone git://this/repository
    eclipse -data /path/to/your/workspace # unless you already have a workspae
    cp -r .settings/* /path/to/your/workspace/.metadata/.plugins/org.eclipse.core.runtime/.settings

Now restart Eclipse

# Warranty

None, express or implied. Sorry.

