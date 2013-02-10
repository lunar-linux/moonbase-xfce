(

  # http://bugzilla.xfce.org/show_bug.cgi?id=6920
  OPTS+=" --disable-static" &&

  patch_it $SOURCE2 1 &&
  xdt-autogen &&

  default_build

) > $C_FIFO 2>&1
