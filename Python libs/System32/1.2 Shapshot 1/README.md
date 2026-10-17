# System32 Lib Update Data

    添加了 `file` 里的 `get_SHA256` 以便获得文件的 `SHA256` 以便进行比较，防止恶意人士篡改数据造成损害

    添加了 `Port` 这个分类，暂只支持 `TCP` 开放端口，可调用 `start` 里传入需要处理的函数，`call` 用来调用传入的端口
