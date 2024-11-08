find . -name Makefile.am -type f -exec sed -i '/@CODE_COVERAGE_RULES@/d' {} + &&

autoreconf -fi &&

OPTS+=" --disable-static \
        --disable-glade-catalog \
        --disable-Werror" &&

default_build
