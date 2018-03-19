# ios_opus_build_script #
# Overview #
the script is build opus liberary on ios plat,base the MIT-licensed.
# License #
MIT-licensed

# Use Step #
1.Edit the ogg.sh,change the XY_OGG_VERSION On line 3. the default is 1.3.2
<br/>
2.Test the ogg source address on svn whether avaliable. the default address is http://svn.xiph.org/tags/ogg/$ogg_svn_dir
<br/>
3.According to your own needs，add or delete the arch.the default is all the arch that support .i386,x86_64,armv6,armv7,armv7s,arm64.
<br/>
When all the up steps is done. just execute the ogg.sh
<br/>
# Result #
The fat dir is "ogg" in the root dir,the thin dir for the corresponding arch same in the root dir. exampe "ogg-build-iPhoneOS-arm64"  corresponding the arch is arm64 