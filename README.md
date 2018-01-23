# spring-boot-jpaDemo
spring-boot-jpa的Demo
运行测试
A、先保存数据
http://localhost:8080/save?name=aa&&address=北京&&age=1
http://localhost:8080/save?name=ab&&address=北京&&age=2
http://localhost:8080/save?name=cq1&&address=重庆&&age=50
http://localhost:8080/save?name=cq2&&address=重庆&&age=51
B、查询q1
http://localhost:8080/q1?address=北京
C、查询q2
http://localhost:8080/q2?address=北京&&name=aa
D、查询q3
http://localhost:8080/q3?address=北京&&name=aa
E、排序
http://localhost:8080/sort
F、分页
http://localhost:8080/page


参考
http://blog.csdn.net/sosfnima/article/details/51993689
