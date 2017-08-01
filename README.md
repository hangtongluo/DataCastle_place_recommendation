# DataCastle_place_recommendation
DataCastle地点推荐系统（第四）  
http://pkbigdata.com/common/cmpt/%E5%9C%B0%E7%82%B9%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F_%E7%AB%9E%E8%B5%9B%E4%BF%A1%E6%81%AF.html

此问题数据中用户基本都访问了地点一次，所以推荐通过地点热度推荐：  
      1、第一步根据大众用户的偏好给visit_num加上权重  
      2、通过visit_num来选出前50个最可能去的  
      

运行环境：python2.7
