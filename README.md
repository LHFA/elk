# elk
## ELK stack 6.1.1  配置文件模板 ##


>ELK_Stack /
>>│
>>├── elasticsearch   				#es的系统配置文件和es的jvm配置文件
>>│
>>├── elasticsearch-curator 		#存放es管理工具curator的配置文件
>>│
>>├── filebeat 						#存放filebeat的配置文件
>>│
>>└── logstash
>>>    ├── conf.d 					#存放logstash的配置文件
>>>>   │   ├── 10.54				#对应服务器上存放的配置文件
>>>>   │   └── ELK03,05				#对应服务器上存放的配置文件
>>>    └── template 				#存放模板文件
>>>>        ├── 5.x 				
>>>>        └── 6.x 				#不同版本对应的模板文件格式不同.现在统一使用6.x的模板文件.