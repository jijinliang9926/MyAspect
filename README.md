annotation包  是正常用法

    创建了两个自定义注解
    
        SystemControllerLog 可以加在接口层的类上、方法上、字段上
            这里面的一个自定义方法是把当前操作的类、方法，执行过程都保存到数据库的一张log表中
    
        SystemServiceLog  可以加在服务层的类上、方法上、字段上
            给加注解的方法做记录，log4j输出


annotation2包  是指定扫码包下带自定义注解的方法