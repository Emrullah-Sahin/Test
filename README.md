# Qt For Android Issues!
# Known issues
Latest NDK and JDK versions are incompatible with Qt for Android</li>
# Solution
 - Qt for Android compatible NDK version https://developer.android.com/ndk/downloads/older_releases Android
   NDK, Revision 10e (May 2015)
 - Qt for Android compatible JDK version https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
   Java SE Development Kit 8
   
# Qt OpenSSL library error
qt.network.ssl: QSslSocket: cannot call unresolved function SSLv23_client_method
qt.network.ssl: QSslSocket: cannot call unresolved function SSL_CTX_new
qt.network.ssl: QSslSocket: cannot call unresolved function SSL_library_init
qt.network.ssl: QSslSocket: cannot call unresolved function ERR_get_error
qt.network.ssl: QSslSocket: cannot call unresolved function ERR_get_error
- Dowload OpenSSL library from i386 https://indy.fulgan.com/SSL/ put them in debug folder

