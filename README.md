# 2020gongzuori
2020年工作日、法定节假日

相关单位可以引用。

创建数据表语句为

CREATE TABLE `假日表` (
  `holiday_date` varchar(50) NOT NULL,
  `holiday_des` varchar(50) DEFAULT NULL,
  `office_id` bigint(50) DEFAULT NULL,
  `calendar_id` bigint(50) DEFAULT NULL,
  `country_id` bigint(50) DEFAULT NULL
) ENGINE=myisam DEFAULT CHARSET=utf8;


生成的方式
1.获得2020年假日表（根据国务院发布的信息结合百度搜索2020年假期进行比对）
2.排除掉假日获得2020年工作日。

使用场景：政府及相关单位的工作日等场景可以引用。
