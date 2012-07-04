(

  OPTS+=" --disable-static" &&

  sedit 's;exo-0.3;exo-1;' configure.ac &&
  autoconf &&

  default_build

) > $C_FIFO 2>&1
