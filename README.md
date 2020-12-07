# imaging-admix
Scientific data analysis and visualization

1. NCL

   Need this to compile triangle for ncl in spite of its claims otherwise
   download source and put on google drive. Compile instrucionts in yaml

   ```bash
   wget http://www.netlib.org/voronoi/triangle.zip
   ```

1. AFNI

   Download precompiled binaries from https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/download_links.html

   Install instructions https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/install_instructs/steps_linux_Fed_RH.html

   After install, can check version with

   ```bash
   ./afni -ver
   ```

   Version info is in <install-path>/AFNI_version.txt

1. ANTS

   Dependencies  require gcc v4 to work. Fail with gcc 8.4.0

1. ASHS

   For source checkout, last revision is 121
   svn --username anonymous --password anonymous checkout https://www.nitrc.org/svn/ashs
   No clear docs how to compile. Currently, use binary distro for build.
