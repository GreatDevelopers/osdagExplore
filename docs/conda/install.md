```sh

(base) D:\>md IIT_OSD

(base) D:\>cd IIT_OSD

(base) D:\IIT_OSD>conda create -n osdag-env osdag::osdag -c conda-forge -c geompy
Do you accept the Terms of Service (ToS) for https://repo.anaconda.com/pkgs/main? [(a)ccept/(r)eject/(v)iew]: a
Do you accept the Terms of Service (ToS) for https://repo.anaconda.com/pkgs/r? [(a)ccept/(r)eject/(v)iew]: a
Do you accept the Terms of Service (ToS) for https://repo.anaconda.com/pkgs/msys2? [(a)ccept/(r)eject/(v)iew]: a
3 channel Terms of Service accepted
Retrieving notices: done
Channels:
 - conda-forge
 - geompy
 - defaults
 - osdag
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
    current version: 26.1.1
    latest version: 26.5.2

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: D:\Programs\MiniConda\envs\osdag-env

  added / updated specs:
    - osdag::osdag


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    _openmp_mutex-4.5          |           20_gnu          51 KB  conda-forge
    aiohappyeyeballs-2.6.2     |     pyhd8ed1ab_0          20 KB  conda-forge
    aiohttp-3.14.1             |  py312h6b91d65_0        1002 KB  conda-forge
    aiosignal-1.4.0            |     pyhd8ed1ab_0          13 KB  conda-forge
    aom-3.14.1                 | pl5321h06fc181_1         2.1 MB  conda-forge
    attrs-26.1.0               |     pyhcf101f3_0          63 KB  conda-forge
    blosc-1.21.6               |       hfd34d9b_1          49 KB  conda-forge
    brotli-1.2.0               |       h2d644bc_1          20 KB  conda-forge
    brotli-bin-1.2.0           |       hfd05255_1          22 KB  conda-forge
    bzip2-1.0.8                |       h0ad9c76_9          55 KB  conda-forge
    ca-certificates-2026.5.20  |       h4c7d964_0         127 KB  conda-forge
    cairo-1.18.4               |       h477c42c_1         1.5 MB  conda-forge
    cgal-cpp-6.1.2             |       h4086982_0         5.8 MB  conda-forge
    cli11-2.6.2                |       h5112557_0          95 KB  conda-forge
    click-8.4.1                |     pyh6dadd2b_0         102 KB  conda-forge
    colorama-0.4.6             |     pyhd8ed1ab_1          26 KB  conda-forge
    contourpy-1.3.3            |  py312h78d62e6_4         238 KB  conda-forge
    cycler-0.12.1              |     pyhcf101f3_2          14 KB  conda-forge
    dav1d-1.2.1                |       hcfcfb64_0         604 KB  conda-forge
    double-conversion-3.4.0    |       hac47afa_0          69 KB  conda-forge
    eigen-5.0.1                |       h5112557_0         1.2 MB  conda-forge
    eigen-abi-5.0.1.100        |       hc11354d_0          13 KB  conda-forge
    et_xmlfile-2.0.0           |     pyhd8ed1ab_1          21 KB  conda-forge
    expat-2.8.1                |       hac47afa_1         130 KB  conda-forge
    ffmpeg-8.1.1               | gpl_h6d5d71d_904        10.5 MB  conda-forge
    fmt-12.1.0                 |       h7f4e812_0         182 KB  conda-forge
    font-ttf-dejavu-sans-mono-2.37|       hab24e00_0         388 KB  conda-forge
    font-ttf-inconsolata-3.000 |       h77eed37_0          94 KB  conda-forge
    font-ttf-source-code-pro-2.038|       h77eed37_0         684 KB  conda-forge
    font-ttf-ubuntu-0.83       |       h77eed37_3         1.5 MB  conda-forge
    fontconfig-2.18.1          |       hd47e2ca_0         198 KB  conda-forge
    fonts-conda-ecosystem-1    |                0           4 KB  conda-forge
    fonts-conda-forge-1        |       hc364b38_1           4 KB  conda-forge
    fonttools-4.63.0           |  py312h05f76fc_0         2.4 MB  conda-forge
    freeglut-3.2.2             |       hac47afa_4         111 KB  conda-forge
    freeimage-3.18.0           |      h81f0cfa_25         459 KB  conda-forge
    freetype-2.14.3            |       h57928b3_1         181 KB  conda-forge
    fribidi-1.0.16             |       hfd05255_0          63 KB  conda-forge
    frozenlist-1.8.0           |  py312hfdf67e6_0          50 KB  conda-forge
    gdk-pixbuf-2.44.6          |       h1f5b9c4_0         563 KB  conda-forge
    geos-3.14.1                |       hdade9fe_0         1.7 MB  conda-forge
    gflags-2.2.2               |    he0c23c2_1005          75 KB  conda-forge
    gl2ps-1.4.2                |       h26c196c_2          71 KB  conda-forge
    glew-2.3.0                 |       hdfd1c44_0         531 KB  conda-forge
    glslang-16.3.0             |       h294ba9c_0         4.8 MB  conda-forge
    gmp-6.3.0                  |       hfeafd45_2         554 KB  conda-forge
    graphite2-1.3.15           |       hac47afa_0          95 KB  conda-forge
    harfbuzz-14.2.1            |       h5a1b470_0         1.2 MB  conda-forge
    hdf4-4.2.15                |       h5557f11_7         761 KB  conda-forge
    hdf5-1.14.6                |nompi_hae35d4c_110         2.2 MB  conda-forge
    icu-78.3                   |       h637d24d_0        14.3 MB  conda-forge
    idna-3.17                  |     pyhcf101f3_0          56 KB  conda-forge
    ifcopenshell-0.8.5         |  py312h989904b_4        73.8 MB  conda-forge
    imath-3.2.2                |       h1608b31_0         158 KB  conda-forge
    importlib-metadata-9.0.0   |     pyhcf101f3_0          34 KB  conda-forge
    jasper-4.2.9               |       h8ad263b_1         437 KB  conda-forge
    jsoncpp-1.9.6              |       hda1637e_1         334 KB  conda-forge
    jxrlib-1.1                 |       hcfcfb64_3         347 KB  conda-forge
    kiwisolver-1.5.0           |  py312h78d62e6_0          72 KB  conda-forge
    krb5-1.22.2                |       h0ea6238_0         733 KB  conda-forge
    lame-3.100                 |    hcfcfb64_1003         557 KB  conda-forge
    lark-1.3.1                 |     pyhd8ed1ab_0          92 KB  conda-forge
    lcms2-2.19.1               |       hf2c6c5f_1         511 KB  conda-forge
    lerc-4.1.0                 |       hd936e49_0         168 KB  conda-forge
    libaec-1.1.5               |       haf901d7_0          34 KB  conda-forge
    libblas-3.11.0             |   8_h8455456_mkl          67 KB  conda-forge
    libboost-1.88.0            |       h9dfe17d_7         2.3 MB  conda-forge
    libboost-devel-1.88.0      |       h1c1089f_7          42 KB  conda-forge
    libboost-headers-1.88.0    |       h57928b3_7        14.0 MB  conda-forge
    libbrotlicommon-1.2.0      |       hfd05255_1          80 KB  conda-forge
    libbrotlidec-1.2.0         |       hfd05255_1          34 KB  conda-forge
    libbrotlienc-1.2.0         |       hfd05255_1         247 KB  conda-forge
    libcblas-3.11.0            |   8_h2a3cdd5_mkl          67 KB  conda-forge
    libclang13-22.1.7          |default_ha2db4b5_1        29.1 MB  conda-forge
    libcurl-8.20.0             |       h8206538_0         384 KB  conda-forge
    libdeflate-1.25            |       h51727cc_0         153 KB  conda-forge
    libexpat-2.8.1             |       hac47afa_1          70 KB  conda-forge
    libffi-3.5.2               |       h3d046cb_0          45 KB  conda-forge
    libfreetype-2.14.3         |       h57928b3_1           9 KB  conda-forge
    libfreetype6-2.14.3        |       hdbac1cb_1         332 KB  conda-forge
    libgcc-15.2.0              |      h8ee18e1_19         803 KB  conda-forge
    libglib-2.88.1             |       h7ce1215_2         4.3 MB  conda-forge
    libgomp-15.2.0             |      h8ee18e1_19         649 KB  conda-forge
    libhwloc-2.13.0            |default_h049141e_1000         2.3 MB  conda-forge
    libhwy-1.4.0               |       h172a326_0         549 KB  conda-forge
    libiconv-1.18              |       hc1393d2_2         681 KB  conda-forge
    libintl-0.22.5             |       h5728263_3          93 KB  conda-forge
    libjpeg-turbo-3.1.4.1      |       hfd05255_0         823 KB  conda-forge
    libjxl-0.11.2              |       h932607e_1         1.1 MB  conda-forge
    liblapack-3.11.0           |   8_hf9ab0e9_mkl          79 KB  conda-forge
    liblzma-5.8.3              |       hfd05255_0         104 KB  conda-forge
    liblzma-devel-5.8.3        |       hfd05255_0         128 KB  conda-forge
    libnetcdf-4.10.0           |nompi_h3948bcf_104         647 KB  conda-forge
    libogg-1.3.5               |       h2466b09_1          34 KB  conda-forge
    libopus-1.6.1              |       h6a83c73_0         300 KB  conda-forge
    libpng-1.6.58              |       h7351971_0         376 KB  conda-forge
    libraw-0.22.1              |       h345c428_0         559 KB  conda-forge
    librsvg-2.62.3             |       h15cfe45_0         3.2 MB  conda-forge
    libsqlite-3.53.2           |       hf5d6505_0         1.3 MB  conda-forge
    libssh2-1.11.1             |       h9aa295b_0         286 KB  conda-forge
    libtheora-1.1.1            |    hc70643c_1006         157 KB  conda-forge
    libtiff-4.7.1              |       h8f73337_1         970 KB  conda-forge
    libusb-1.0.29              |       h1839187_0         115 KB  conda-forge
    libvorbis-1.3.7            |       h5112557_2         238 KB  conda-forge
    libvulkan-loader-1.4.341.0 |       h477610d_0         276 KB  conda-forge
    libwebp-base-1.6.0         |       h4d5522a_0         273 KB  conda-forge
    libwinpthread-12.0.0.r4.gg4f2fc60ca|      h57928b3_10          36 KB  conda-forge
    libxcb-1.17.0              |       h0e4246c_0         1.2 MB  conda-forge
    libxml2-2.15.3             |       h8ef44ab_0          43 KB  conda-forge
    libxml2-16-2.15.3          |       h3cfd58e_0         508 KB  conda-forge
    libxslt-1.1.43             |       h0fbe4c1_1         410 KB  conda-forge
    libzip-1.11.2              |       h3135430_0         143 KB  conda-forge
    libzlib-1.3.2              |       hfd05255_2          57 KB  conda-forge
    llvm-openmp-22.1.7         |       h4fa8253_0         339 KB  conda-forge
    lz4-c-1.10.0               |       h2466b09_1         137 KB  conda-forge
    markdown-3.10.2            |     pyhcf101f3_0          84 KB  conda-forge
    matplotlib-base-3.10.9     |  py312h0ebf65c_0         7.7 MB  conda-forge
    mesalib-26.0.3             |       h667bac9_0        41.6 MB  conda-forge
    mkl-2026.0.0               |     hac47afa_908       109.1 MB  conda-forge
    mpfr-4.2.2                 |       h883a981_0         717 KB  conda-forge
    msgpack-python-1.1.2       |  py312hf90b1b7_1          85 KB  conda-forge
    multidict-6.7.1            |  py312h05f76fc_0          89 KB  conda-forge
    munkres-1.1.4              |     pyhd8ed1ab_1          15 KB  conda-forge
    navcube-1.1.0              |             py_0          32 KB  geompy
    nlohmann_json-3.12.0       |       h5112557_1         132 KB  conda-forge
    numpy-2.4.6                |  py312ha3f287d_0         6.8 MB  conda-forge
    occt-7.9.3                 | all_hf10db9b_203        23.4 MB  conda-forge
    onemkl-license-2026.0.0    |     h57928b3_908          41 KB  conda-forge
    openexr-3.4.12             |       h68a0530_1         927 KB  conda-forge
    openh264-2.6.0             |       hb17fa0b_0         402 KB  conda-forge
    openjpeg-2.5.4             |       h0e57b4f_0         240 KB  conda-forge
    openjph-0.28.1             |       hf13a347_0         217 KB  conda-forge
    openpyxl-3.1.5             |  py312h83acffa_3         465 KB  conda-forge
    openssl-3.6.3              |       hf411b9b_0         9.0 MB  conda-forge
    ordered-set-4.1.0          |     pyhd8ed1ab_1          14 KB  conda-forge
    osdag-2026.04.0.0          |             py_0        10.2 MB  osdag
    osdag_latex_env-1.0.2      |          py313_0       175.2 MB  osdag
    packaging-26.2             |     pyhc364b38_0          89 KB  conda-forge
    pandas-3.0.3               |  py312h95189c4_0        13.0 MB  conda-forge
    pango-1.56.4               |       h13911b6_1         444 KB  conda-forge
    pcre2-10.47                |       hd2b5f0e_0         973 KB  conda-forge
    pillow-12.2.0              |  py312h31f0997_0         923 KB  conda-forge
    pip-26.1.2                 |     pyh8b19718_0         1.1 MB  conda-forge
    pixman-0.46.4              |       h5112557_1         530 KB  conda-forge
    proj-9.8.1                 |       hd30e2cd_0         3.0 MB  conda-forge
    propcache-0.5.2            |  py312h05f76fc_0          48 KB  conda-forge
    pthread-stubs-0.4          |    h0e40799_1002           9 KB  conda-forge
    pugixml-1.15               |       h372dad0_0         111 KB  conda-forge
    pylatex-1.4.2              |     pyhd8ed1ab_0          38 KB  conda-forge
    pyparsing-3.3.2            |     pyhcf101f3_0         108 KB  conda-forge
    pyside6-6.11.1             |  py312ha7d0d2e_1        11.0 MB  conda-forge
    python-3.12.13             |h0159041_0_cpython        15.1 MB  conda-forge
    python-dateutil-2.9.0.post0|     pyhe01879c_2         228 KB  conda-forge
    python-tzdata-2026.2       |     pyhd8ed1ab_0         143 KB  conda-forge
    python_abi-3.12            |          8_cp312           7 KB  conda-forge
    pythonocc-core-7.9.3       | all_h9c1f68b_202        38.0 MB  conda-forge
    pyyaml-6.0.3               |  py312h05f76fc_1         176 KB  conda-forge
    qhull-2020.2               |       hc790b64_5         1.3 MB  conda-forge
    qt6-main-6.11.1            | pl5321hfcac499_1        85.4 MB  conda-forge
    rapidjson-1.1.0.post20240409|       he0c23c2_2         150 KB  conda-forge
    rocksdb-10.6.2             |h6b9cf66_0_default        51.9 MB  conda-forge
    sdl2-2.32.56               |       h5112557_0         559 KB  conda-forge
    sdl3-3.4.10                |       h5112557_0         1.6 MB  conda-forge
    setuptools-82.0.1          |     pyh332efcf_0         625 KB  conda-forge
    shaderc-2026.2             |       h8fa7867_0         1.5 MB  conda-forge
    shapely-2.1.2              |  py312h37f46ab_2         583 KB  conda-forge
    six-1.17.0                 |     pyhe01879c_1          18 KB  conda-forge
    smesh-9.9.0.0              |      h7e0deeb_22         3.8 MB  conda-forge
    snappy-1.2.2               |       h7fa0ca8_1          66 KB  conda-forge
    spirv-tools-2026.2         |       h49e36cd_0        13.6 MB  conda-forge
    sqlite-3.53.2              |       hdb435a2_0         416 KB  conda-forge
    svgwrite-1.4.3             |     pyhd8ed1ab_1          54 KB  conda-forge
    svt-av1-4.0.1              |       hac47afa_0         1.7 MB  conda-forge
    tbb-2023.0.0               |       hd3d4ead_2         153 KB  conda-forge
    tbb-devel-2023.0.0         |       h7c1ad13_2         1.1 MB  conda-forge
    tk-8.6.13                  |       h6ed50ae_3         3.4 MB  conda-forge
    typing_extensions-4.15.0   |     pyhcf101f3_0          50 KB  conda-forge
    tzdata-2025c               |       hc9c84f9_1         116 KB  conda-forge
    ucrt-10.0.26100.0          |       h57928b3_0         678 KB  conda-forge
    unicodedata2-17.0.1        |  py312he06e257_0         396 KB  conda-forge
    utfcpp-4.09                |       h57928b3_0          14 KB  conda-forge
    vc-14.5                    |      h1b7c187_39          20 KB  conda-forge
    vc14_runtime-14.51.36231   |      h1b9f54f_39         720 KB  conda-forge
    vcomp14-14.51.36231        |      h1b9f54f_39         118 KB  conda-forge
    viskores-1.1.1             |   cpu_h4b717ef_0        10.7 MB  conda-forge
    vs2015_runtime-14.51.36231 |      h84cd919_39          20 KB  conda-forge
    vtk-9.6.1                  |  py312h5ad3caf_3          27 KB  conda-forge
    vtk-base-9.6.1             |  py312hb1e1833_2        54.0 MB  conda-forge
    wheel-0.47.0               |     pyhd8ed1ab_0          33 KB  conda-forge
    wslink-2.5.7               |     pyhd8ed1ab_0          36 KB  conda-forge
    x264-1!164.3095            |       h8ffe710_2        1017 KB  conda-forge
    x265-3.5                   |       h2d74725_3         5.3 MB  conda-forge
    xorg-libxau-1.0.12         |       hba3369d_1         107 KB  conda-forge
    xorg-libxdmcp-1.1.5        |       hba3369d_1          69 KB  conda-forge
    yaml-0.2.5                 |       h6a83c73_3          62 KB  conda-forge
    yarl-1.24.2                |  py312h05f76fc_0         148 KB  conda-forge
    zfp-1.0.1                  |       h2f0f97f_5         233 KB  conda-forge
    zipp-4.1.0                 |     pyhcf101f3_0          24 KB  conda-forge
    zlib-1.3.2                 |       hfd05255_2         830 KB  conda-forge
    zlib-ng-2.3.3              |       h0261ad2_1         122 KB  conda-forge
    zstd-1.5.7                 |       h534d264_6         379 KB  conda-forge
    ------------------------------------------------------------
                                           Total:       918.4 MB

The following NEW packages will be INSTALLED:

  _openmp_mutex      conda-forge/win-64::_openmp_mutex-4.5-20_gnu
  aiohappyeyeballs   conda-forge/noarch::aiohappyeyeballs-2.6.2-pyhd8ed1ab_0
  aiohttp            conda-forge/win-64::aiohttp-3.14.1-py312h6b91d65_0
  aiosignal          conda-forge/noarch::aiosignal-1.4.0-pyhd8ed1ab_0
  aom                conda-forge/win-64::aom-3.14.1-pl5321h06fc181_1
  attrs              conda-forge/noarch::attrs-26.1.0-pyhcf101f3_0
  blosc              conda-forge/win-64::blosc-1.21.6-hfd34d9b_1
  brotli             conda-forge/win-64::brotli-1.2.0-h2d644bc_1
  brotli-bin         conda-forge/win-64::brotli-bin-1.2.0-hfd05255_1
  bzip2              conda-forge/win-64::bzip2-1.0.8-h0ad9c76_9
  ca-certificates    conda-forge/noarch::ca-certificates-2026.5.20-h4c7d964_0
  cairo              conda-forge/win-64::cairo-1.18.4-h477c42c_1
  cgal-cpp           conda-forge/win-64::cgal-cpp-6.1.2-h4086982_0
  cli11              conda-forge/win-64::cli11-2.6.2-h5112557_0
  click              conda-forge/noarch::click-8.4.1-pyh6dadd2b_0
  colorama           conda-forge/noarch::colorama-0.4.6-pyhd8ed1ab_1
  contourpy          conda-forge/win-64::contourpy-1.3.3-py312h78d62e6_4
  cycler             conda-forge/noarch::cycler-0.12.1-pyhcf101f3_2
  dav1d              conda-forge/win-64::dav1d-1.2.1-hcfcfb64_0
  double-conversion  conda-forge/win-64::double-conversion-3.4.0-hac47afa_0
  eigen              conda-forge/win-64::eigen-5.0.1-h5112557_0
  eigen-abi          conda-forge/win-64::eigen-abi-5.0.1.100-hc11354d_0
  et_xmlfile         conda-forge/noarch::et_xmlfile-2.0.0-pyhd8ed1ab_1
  expat              conda-forge/win-64::expat-2.8.1-hac47afa_1
  ffmpeg             conda-forge/win-64::ffmpeg-8.1.1-gpl_h6d5d71d_904
  fmt                conda-forge/win-64::fmt-12.1.0-h7f4e812_0
  font-ttf-dejavu-s~ conda-forge/noarch::font-ttf-dejavu-sans-mono-2.37-hab24e00_0
  font-ttf-inconsol~ conda-forge/noarch::font-ttf-inconsolata-3.000-h77eed37_0
  font-ttf-source-c~ conda-forge/noarch::font-ttf-source-code-pro-2.038-h77eed37_0
  font-ttf-ubuntu    conda-forge/noarch::font-ttf-ubuntu-0.83-h77eed37_3
  fontconfig         conda-forge/win-64::fontconfig-2.18.1-hd47e2ca_0
  fonts-conda-ecosy~ conda-forge/noarch::fonts-conda-ecosystem-1-0
  fonts-conda-forge  conda-forge/noarch::fonts-conda-forge-1-hc364b38_1
  fonttools          conda-forge/win-64::fonttools-4.63.0-py312h05f76fc_0
  freeglut           conda-forge/win-64::freeglut-3.2.2-hac47afa_4
  freeimage          conda-forge/win-64::freeimage-3.18.0-h81f0cfa_25
  freetype           conda-forge/win-64::freetype-2.14.3-h57928b3_1
  fribidi            conda-forge/win-64::fribidi-1.0.16-hfd05255_0
  frozenlist         conda-forge/win-64::frozenlist-1.8.0-py312hfdf67e6_0
  gdk-pixbuf         conda-forge/win-64::gdk-pixbuf-2.44.6-h1f5b9c4_0
  geos               conda-forge/win-64::geos-3.14.1-hdade9fe_0
  gflags             conda-forge/win-64::gflags-2.2.2-he0c23c2_1005
  gl2ps              conda-forge/win-64::gl2ps-1.4.2-h26c196c_2
  glew               conda-forge/win-64::glew-2.3.0-hdfd1c44_0
  glslang            conda-forge/win-64::glslang-16.3.0-h294ba9c_0
  gmp                conda-forge/win-64::gmp-6.3.0-hfeafd45_2
  graphite2          conda-forge/win-64::graphite2-1.3.15-hac47afa_0
  harfbuzz           conda-forge/win-64::harfbuzz-14.2.1-h5a1b470_0
  hdf4               conda-forge/win-64::hdf4-4.2.15-h5557f11_7
  hdf5               conda-forge/win-64::hdf5-1.14.6-nompi_hae35d4c_110
  icu                conda-forge/win-64::icu-78.3-h637d24d_0
  idna               conda-forge/noarch::idna-3.17-pyhcf101f3_0
  ifcopenshell       conda-forge/win-64::ifcopenshell-0.8.5-py312h989904b_4
  imath              conda-forge/win-64::imath-3.2.2-h1608b31_0
  importlib-metadata conda-forge/noarch::importlib-metadata-9.0.0-pyhcf101f3_0
  jasper             conda-forge/win-64::jasper-4.2.9-h8ad263b_1
  jsoncpp            conda-forge/win-64::jsoncpp-1.9.6-hda1637e_1
  jxrlib             conda-forge/win-64::jxrlib-1.1-hcfcfb64_3
  kiwisolver         conda-forge/win-64::kiwisolver-1.5.0-py312h78d62e6_0
  krb5               conda-forge/win-64::krb5-1.22.2-h0ea6238_0
  lame               conda-forge/win-64::lame-3.100-hcfcfb64_1003
  lark               conda-forge/noarch::lark-1.3.1-pyhd8ed1ab_0
  lcms2              conda-forge/win-64::lcms2-2.19.1-hf2c6c5f_1
  lerc               conda-forge/win-64::lerc-4.1.0-hd936e49_0
  libaec             conda-forge/win-64::libaec-1.1.5-haf901d7_0
  libblas            conda-forge/win-64::libblas-3.11.0-8_h8455456_mkl
  libboost           conda-forge/win-64::libboost-1.88.0-h9dfe17d_7
  libboost-devel     conda-forge/win-64::libboost-devel-1.88.0-h1c1089f_7
  libboost-headers   conda-forge/win-64::libboost-headers-1.88.0-h57928b3_7
  libbrotlicommon    conda-forge/win-64::libbrotlicommon-1.2.0-hfd05255_1
  libbrotlidec       conda-forge/win-64::libbrotlidec-1.2.0-hfd05255_1
  libbrotlienc       conda-forge/win-64::libbrotlienc-1.2.0-hfd05255_1
  libcblas           conda-forge/win-64::libcblas-3.11.0-8_h2a3cdd5_mkl
  libclang13         conda-forge/win-64::libclang13-22.1.7-default_ha2db4b5_1
  libcurl            conda-forge/win-64::libcurl-8.20.0-h8206538_0
  libdeflate         conda-forge/win-64::libdeflate-1.25-h51727cc_0
  libexpat           conda-forge/win-64::libexpat-2.8.1-hac47afa_1
  libffi             conda-forge/win-64::libffi-3.5.2-h3d046cb_0
  libfreetype        conda-forge/win-64::libfreetype-2.14.3-h57928b3_1
  libfreetype6       conda-forge/win-64::libfreetype6-2.14.3-hdbac1cb_1
  libgcc             conda-forge/win-64::libgcc-15.2.0-h8ee18e1_19
  libglib            conda-forge/win-64::libglib-2.88.1-h7ce1215_2
  libgomp            conda-forge/win-64::libgomp-15.2.0-h8ee18e1_19
  libhwloc           conda-forge/win-64::libhwloc-2.13.0-default_h049141e_1000
  libhwy             conda-forge/win-64::libhwy-1.4.0-h172a326_0
  libiconv           conda-forge/win-64::libiconv-1.18-hc1393d2_2
  libintl            conda-forge/win-64::libintl-0.22.5-h5728263_3
  libjpeg-turbo      conda-forge/win-64::libjpeg-turbo-3.1.4.1-hfd05255_0
  libjxl             conda-forge/win-64::libjxl-0.11.2-h932607e_1
  liblapack          conda-forge/win-64::liblapack-3.11.0-8_hf9ab0e9_mkl
  liblzma            conda-forge/win-64::liblzma-5.8.3-hfd05255_0
  liblzma-devel      conda-forge/win-64::liblzma-devel-5.8.3-hfd05255_0
  libnetcdf          conda-forge/win-64::libnetcdf-4.10.0-nompi_h3948bcf_104
  libogg             conda-forge/win-64::libogg-1.3.5-h2466b09_1
  libopus            conda-forge/win-64::libopus-1.6.1-h6a83c73_0
  libpng             conda-forge/win-64::libpng-1.6.58-h7351971_0
  libraw             conda-forge/win-64::libraw-0.22.1-h345c428_0
  librsvg            conda-forge/win-64::librsvg-2.62.3-h15cfe45_0
  libsqlite          conda-forge/win-64::libsqlite-3.53.2-hf5d6505_0
  libssh2            conda-forge/win-64::libssh2-1.11.1-h9aa295b_0
  libtheora          conda-forge/win-64::libtheora-1.1.1-hc70643c_1006
  libtiff            conda-forge/win-64::libtiff-4.7.1-h8f73337_1
  libusb             conda-forge/win-64::libusb-1.0.29-h1839187_0
  libvorbis          conda-forge/win-64::libvorbis-1.3.7-h5112557_2
  libvulkan-loader   conda-forge/win-64::libvulkan-loader-1.4.341.0-h477610d_0
  libwebp-base       conda-forge/win-64::libwebp-base-1.6.0-h4d5522a_0
  libwinpthread      conda-forge/win-64::libwinpthread-12.0.0.r4.gg4f2fc60ca-h57928b3_10
  libxcb             conda-forge/win-64::libxcb-1.17.0-h0e4246c_0
  libxml2            conda-forge/win-64::libxml2-2.15.3-h8ef44ab_0
  libxml2-16         conda-forge/win-64::libxml2-16-2.15.3-h3cfd58e_0
  libxslt            conda-forge/win-64::libxslt-1.1.43-h0fbe4c1_1
  libzip             conda-forge/win-64::libzip-1.11.2-h3135430_0
  libzlib            conda-forge/win-64::libzlib-1.3.2-hfd05255_2
  llvm-openmp        conda-forge/win-64::llvm-openmp-22.1.7-h4fa8253_0
  lz4-c              conda-forge/win-64::lz4-c-1.10.0-h2466b09_1
  markdown           conda-forge/noarch::markdown-3.10.2-pyhcf101f3_0
  matplotlib-base    conda-forge/win-64::matplotlib-base-3.10.9-py312h0ebf65c_0
  mesalib            conda-forge/win-64::mesalib-26.0.3-h667bac9_0
  mkl                conda-forge/win-64::mkl-2026.0.0-hac47afa_908
  mpfr               conda-forge/win-64::mpfr-4.2.2-h883a981_0
  msgpack-python     conda-forge/win-64::msgpack-python-1.1.2-py312hf90b1b7_1
  multidict          conda-forge/win-64::multidict-6.7.1-py312h05f76fc_0
  munkres            conda-forge/noarch::munkres-1.1.4-pyhd8ed1ab_1
  navcube            geompy/noarch::navcube-1.1.0-py_0
  nlohmann_json      conda-forge/win-64::nlohmann_json-3.12.0-h5112557_1
  numpy              conda-forge/win-64::numpy-2.4.6-py312ha3f287d_0
  occt               conda-forge/win-64::occt-7.9.3-all_hf10db9b_203
  onemkl-license     conda-forge/win-64::onemkl-license-2026.0.0-h57928b3_908
  openexr            conda-forge/win-64::openexr-3.4.12-h68a0530_1
  openh264           conda-forge/win-64::openh264-2.6.0-hb17fa0b_0
  openjpeg           conda-forge/win-64::openjpeg-2.5.4-h0e57b4f_0
  openjph            conda-forge/win-64::openjph-0.28.1-hf13a347_0
  openpyxl           conda-forge/win-64::openpyxl-3.1.5-py312h83acffa_3
  openssl            conda-forge/win-64::openssl-3.6.3-hf411b9b_0
  ordered-set        conda-forge/noarch::ordered-set-4.1.0-pyhd8ed1ab_1
  osdag              osdag/noarch::osdag-2026.04.0.0-py_0
  osdag_latex_env    osdag/win-64::osdag_latex_env-1.0.2-py313_0
  packaging          conda-forge/noarch::packaging-26.2-pyhc364b38_0
  pandas             conda-forge/win-64::pandas-3.0.3-py312h95189c4_0
  pango              conda-forge/win-64::pango-1.56.4-h13911b6_1
  pcre2              conda-forge/win-64::pcre2-10.47-hd2b5f0e_0
  pillow             conda-forge/win-64::pillow-12.2.0-py312h31f0997_0
  pip                conda-forge/noarch::pip-26.1.2-pyh8b19718_0
  pixman             conda-forge/win-64::pixman-0.46.4-h5112557_1
  proj               conda-forge/win-64::proj-9.8.1-hd30e2cd_0
  propcache          conda-forge/win-64::propcache-0.5.2-py312h05f76fc_0
  pthread-stubs      conda-forge/win-64::pthread-stubs-0.4-h0e40799_1002
  pugixml            conda-forge/win-64::pugixml-1.15-h372dad0_0
  pylatex            conda-forge/noarch::pylatex-1.4.2-pyhd8ed1ab_0
  pyparsing          conda-forge/noarch::pyparsing-3.3.2-pyhcf101f3_0
  pyside6            conda-forge/win-64::pyside6-6.11.1-py312ha7d0d2e_1
  python             conda-forge/win-64::python-3.12.13-h0159041_0_cpython
  python-dateutil    conda-forge/noarch::python-dateutil-2.9.0.post0-pyhe01879c_2
  python-tzdata      conda-forge/noarch::python-tzdata-2026.2-pyhd8ed1ab_0
  python_abi         conda-forge/noarch::python_abi-3.12-8_cp312
  pythonocc-core     conda-forge/win-64::pythonocc-core-7.9.3-all_h9c1f68b_202
  pyyaml             conda-forge/win-64::pyyaml-6.0.3-py312h05f76fc_1
  qhull              conda-forge/win-64::qhull-2020.2-hc790b64_5
  qt6-main           conda-forge/win-64::qt6-main-6.11.1-pl5321hfcac499_1
  rapidjson          conda-forge/win-64::rapidjson-1.1.0.post20240409-he0c23c2_2
  rocksdb            conda-forge/win-64::rocksdb-10.6.2-h6b9cf66_0_default
  sdl2               conda-forge/win-64::sdl2-2.32.56-h5112557_0
  sdl3               conda-forge/win-64::sdl3-3.4.10-h5112557_0
  setuptools         conda-forge/noarch::setuptools-82.0.1-pyh332efcf_0
  shaderc            conda-forge/win-64::shaderc-2026.2-h8fa7867_0
  shapely            conda-forge/win-64::shapely-2.1.2-py312h37f46ab_2
  six                conda-forge/noarch::six-1.17.0-pyhe01879c_1
  smesh              conda-forge/win-64::smesh-9.9.0.0-h7e0deeb_22
  snappy             conda-forge/win-64::snappy-1.2.2-h7fa0ca8_1
  spirv-tools        conda-forge/win-64::spirv-tools-2026.2-h49e36cd_0
  sqlite             conda-forge/win-64::sqlite-3.53.2-hdb435a2_0
  svgwrite           conda-forge/noarch::svgwrite-1.4.3-pyhd8ed1ab_1
  svt-av1            conda-forge/win-64::svt-av1-4.0.1-hac47afa_0
  tbb                conda-forge/win-64::tbb-2023.0.0-hd3d4ead_2
  tbb-devel          conda-forge/win-64::tbb-devel-2023.0.0-h7c1ad13_2
  tk                 conda-forge/win-64::tk-8.6.13-h6ed50ae_3
  typing_extensions  conda-forge/noarch::typing_extensions-4.15.0-pyhcf101f3_0
  tzdata             conda-forge/noarch::tzdata-2025c-hc9c84f9_1
  ucrt               conda-forge/win-64::ucrt-10.0.26100.0-h57928b3_0
  unicodedata2       conda-forge/win-64::unicodedata2-17.0.1-py312he06e257_0
  utfcpp             conda-forge/win-64::utfcpp-4.09-h57928b3_0
  vc                 conda-forge/win-64::vc-14.5-h1b7c187_39
  vc14_runtime       conda-forge/win-64::vc14_runtime-14.51.36231-h1b9f54f_39
  vcomp14            conda-forge/win-64::vcomp14-14.51.36231-h1b9f54f_39
  viskores           conda-forge/win-64::viskores-1.1.1-cpu_h4b717ef_0
  vs2015_runtime     conda-forge/win-64::vs2015_runtime-14.51.36231-h84cd919_39
  vtk                conda-forge/win-64::vtk-9.6.1-py312h5ad3caf_3
  vtk-base           conda-forge/win-64::vtk-base-9.6.1-py312hb1e1833_2
  wheel              conda-forge/noarch::wheel-0.47.0-pyhd8ed1ab_0
  wslink             conda-forge/noarch::wslink-2.5.7-pyhd8ed1ab_0
  x264               conda-forge/win-64::x264-1!164.3095-h8ffe710_2
  x265               conda-forge/win-64::x265-3.5-h2d74725_3
  xorg-libxau        conda-forge/win-64::xorg-libxau-1.0.12-hba3369d_1
  xorg-libxdmcp      conda-forge/win-64::xorg-libxdmcp-1.1.5-hba3369d_1
  yaml               conda-forge/win-64::yaml-0.2.5-h6a83c73_3
  yarl               conda-forge/win-64::yarl-1.24.2-py312h05f76fc_0
  zfp                conda-forge/win-64::zfp-1.0.1-h2f0f97f_5
  zipp               conda-forge/noarch::zipp-4.1.0-pyhcf101f3_0
  zlib               conda-forge/win-64::zlib-1.3.2-hfd05255_2
  zlib-ng            conda-forge/win-64::zlib-ng-2.3.3-h0261ad2_1
  zstd               conda-forge/win-64::zstd-1.5.7-h534d264_6


Proceed ([y]/n)? y


Downloading and Extracting Packages:

Preparing transaction: done
Verifying transaction: done
Executing transaction: /
\
done
#
# To activate this environment, use
#
#     $ conda activate osdag-env
#
# To deactivate an active environment, use
#
#     $ conda deactivate


Channel "defaults" has the following notices:
  [info] -- Tue Jun  9 00:00:00 2026
  PyTorch 2.12 with CUDA support is now available to install with your current channel (Anaconda Main). Learn more: htts


(base) D:\IIT_OSD>
```
