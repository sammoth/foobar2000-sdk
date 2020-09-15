# foobar2000-sdk

You can always get an original untouched copy here: https://foobar2000.org/SDK

This copy has the following changes applied.

- By default it targets [foobar2000](https://foobar2000.org) `v1.5` and above. Edit `foobar2000\SDK\foobar2000.h` if you wish to change this.
- All projects updated for Visual Studio 2019 by using the `v142` platform toolset and latest Windows 10 SDK.
- All projects have these additional compiler options set: `/permissive- /std:c++17`
- `libPPUI`, `SDK helpers` and `foo_sample` are pre-configured to include the bundled copy of [WTL](https://sourceforge.net/projects/wtl/) so everything should just work.

Licenses for each project can be found in their respective folders.
