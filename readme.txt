1. 目前用于XDLib/StlSourcebakClient

使用时注意事项，否则会出现意想不到的build/link错误
    a. include时其位置位于其它include目录的最前面
    b. lib时其位置位于其它lib位置的最后面
    c. 清空项目后重新build