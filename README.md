# Book Flow

# [文档](docs/SUMMARY.md)

使用SSDB数据库保存数据。使用类似区块链的数据结构保存图书漂流交易历史数据。

每本书维护一个数据链，每发生一次交易，记录图书的去向，以及该本数上一本书的交易。保证交易能够链式保存。