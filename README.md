# clang_265635
support files for bugs.freebsd.org id 265635
https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=265635

# To Reproduce:

>cd (to some scratch area)
>git clone https://github.com/jim-olsen/StarlinkRemote
>python3 -m venv py3_venv/SR
>export CFLAGS="-D_THREAD_SAFE"
>py3_venv/SR/bin/pip3 install -vvv -r StarlinkRemote/src/python/requirements.txt
>
>####If that completes OK, repeat the run:
>
>py3_venv/SR/bin/pip3 install -vvv -r StarlinkRemote/src/python/requirements.txt
