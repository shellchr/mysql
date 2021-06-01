# mysql
学习笔记
1.数据放入表中，表在放入库中，每张表有个名字，可以有多张表，表由列组成。
常用命令：XXX表示库，xxx表是表
  show databases 看有哪些库
  use XXX 用XXX库
  show tables看有哪些表
  slect database（） 看自己所在的库
  create table xxx（
    id int，
    name varchar（20））；建立xxx表
  desc xxx 看表里哪些属性栏
  select * from xxx 看里面的数据
  select aaa，bbb from xxx 看xxx表中多个字段
  insert into xxx （id，name） value（1，’john’） 添加数据
  update xxx set name=‘sss’ where id=1 更新id为1的数据
  delete xxx set name=‘sss’ where id=1 删除id为1的数据
  select version（）；是mysql内部查看mysql版本
