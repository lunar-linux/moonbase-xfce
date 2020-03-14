OPTS+=" --disable-static \
        --disable-debug"

if in_depends $MODULE dcraw && in_depends $MODULE raw-thumbnailer ; then
     OPTS+=" --enable-raw"
fi

 default_build
