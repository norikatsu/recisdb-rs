参考サイト 
https://al673d3fimig.blog.fc2.com/blog-entry-1.html

racisdb-rsをsobacasに対応させる
/usr/local/lib/pkgconfig 以下に libsobacas.pc を置く のが基本だが build.rs を編集して pkgconfig の参照パスに ./pkgconfig/ligsobacas.pc を追加しているので
普通にビルド可能
