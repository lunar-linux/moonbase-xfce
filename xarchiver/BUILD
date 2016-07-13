OPTS+=" --libexecdir=/usr/lib/xfce4" &&

if in_depends $MODULE gtk+-2; then
  OPTS+=" --disable-gtk3"
fi &&

./autogen.sh &&

default_build
