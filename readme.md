This is a patch to upgrade a Turnkey Linux core appliance with a fully functioning nginx + mysql + php5 stack.

Features/Goals

  ! This is a beta patch.  Some of these are not fully implemented yet.

  * Currently using php-fpm module (looking into possible sources of php5.3.3)
  * phpmyadmin installed on port 12322 (ssl)
  * APC opcode caching
  * memcached caching