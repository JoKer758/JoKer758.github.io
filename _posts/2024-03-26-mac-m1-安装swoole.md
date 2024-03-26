mac m1 安装swoole

    {
        pecl install swoole
    }


报错swoole_ssl.h:27:10: fatal error: 'openssl/ssl.h' file not found

    {
        brew install openssl
    }



安装swoole时yes --with-openssl-dir=$(brew --prefix openssl



报错 fatal error: pcre2.h: No such file or directory
 #include "pcre2.h"

{
ln -s /opt/homebrew/opt/pcre2/include/pcre2.h  /opt/homebrew/opt/php@8.3/include/php/ext/pcre/
}

修改 php.ini

/opt/homebrew/etc/php/8.3/conf.d

{
extension=swoole.so
}

brew services restart php
