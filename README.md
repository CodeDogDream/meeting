# meeting

数据通过接口入库 -> kafka  ->  实时(flink) - mq ->  ck -> datart
                        ->  离线 airflow (datax -> hive -> datax -> mysql) -> ck -> datart
                        
