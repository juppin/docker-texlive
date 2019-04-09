from juppin/texlive:base
label description "Full TeXlive installation"

run apt-get -y --no-install-recommends install \
        texlive-full \
        && \
    # would get done before each compile otherwise
    luaotfload-tool --update
