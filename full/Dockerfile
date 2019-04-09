from juppin/texlive:base
label description "Full TeXlive installation"

run apt-get -y --no-install-recommends install \
        texlive-full \
        && \
    # clean up
    apt-get autoclean && apt-get clean && \
    # would get done before each compile otherwise
    luaotfload-tool --update
