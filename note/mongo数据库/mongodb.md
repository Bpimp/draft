## 基础命令
  1. show dbs 显示数据库列表
  2. use dabaseA 切换/创建数据库
  3. db.dropDatabase() 删除当前数据库
  4. db.help() 显示当前数据库中的操作命令
  5. show collections 显示当前数据库中的集合
  6. db.table.help() 显示数据库中table集合的操作命令
  7. db.person.insert({})|db.person.save({}) 往person集合中插入数据
    >区别在于如果原来的对象存在，save会调用update更新里面的数据，insert则会忽略
    >insert可以一次插入一个列表，不用遍历效率高，save则需要遍历，一个个插入，效率低
  8. db|db.getName() 查看当前使用的数据库
  9. db.stats() 显示当前数据库的状态
  10. db.version() 显示当前数据库的版本
  11. db.getMongo() 显示当前数据库链接的地址
  12. db.copyDatabase('A','B',"127.0.0.1") 将本机A的数据复制到B数据库中
  13. db.collectionNames() 显示当前数据库中所有集合
  14. db.table.stats() 显示数据库的状态
  15. db.table.drop() 删除集合table
  16. db.table.remove({}) 删除当前数据库table集合中所有的数据
  17. db.table.remove({name:'test'}) 删除当前数据库中table集合中name='test'的记录
  18. db.table.count() 查看table集合中的数据条数
  19. db.table.dataSize() 查看table集合数据空间大小
  20. db.table.storageSize() 查看table集合的总空间大小
## 增删改查
  1. db.test.insertOne()|insertMany() 插入数据
  2. db.test.find()|findOne() 查询字段
   > findOne 默认查找当前collection的第一条数据
  3. db.test.updateOne()|updateMany() 修改字段
  4. db.test.remove({条件})|remove({}) 删除字段