---
title: "{{ replace .Name "-" " " | title }}"
description: 
date: {{ .Date }}
image: 
math: 
license: 
hidden: false
comments: true
draft: true
---


---
title: "{{ replace .Name "-" " " | title }}" # 标题，创建时自动填充
description: # 文章简介
date: {{ .Date }} # 日期，创建时自动填充，格式同2023-01-15T12:00:00+08:00
image: # 文章的封面，留空就是没有，填文章所在位置的相对地址，通常放在同目录下，
math: # 是否启用KaTex，填true启用
license: # 文章尾部显示的协议，false为隐藏，其他作为内容，留空就是使用config.yaml里默认的
hidden: false # 是否隐藏，一般用不到
comments: true # 因为bug所以这个属性只要存在，不管是true还是false都会导致回复无法显示，需要删掉
draft: true # 是否为草稿，建议改为false或者删掉这个属性以防止忘记修改，毕竟我们一般都是写好了才部署到服务器上
categories:
    -
    -
---