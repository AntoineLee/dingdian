# dingdian

### ˵��

���ڶ�����վ������һ�θ��£������ĿҲ����һ�δ�ĸ��¡����������Ʒ�ǰһ�����е�ʵ�ַ�����

����Ϊ����С˵��վ��浯�����������Լ�дһ���ɡ�

### ����ʵ��

����������ʽ��`requests`�⣬ץȡ��������С˵���ݡ�

����api���ã�

- �������ҳ��`DdSpider().get_index_result(search)`
- С˵�½�ҳ��`DdSpider().get_chapter(book_url)`
- �½����ݣ�`DdSpider().get_article(chapter_url)`

�����װ��DdSpider���У������վ�ٴθ��£�ֻҪ�Ķ�DdSpider�Ϳ����ˡ�

### FLask

ÿ������������`SQLAlchemy`���ݿⱣ�����ݣ��ӿ��ٴη����ٶȡ�

����ʱ������л������ص�С˵���и�����ô��Ҫ������ݿ⣨ȡ����manage.py������ݿ��ע�ͣ�����������

### ��������

```
$ pip install -r requirements.txt
$ python manage.py db upgrade
$ python manage.py runserver --host 0.0.0.0
```

### ����

����Gunicorn������heroku������ο�����[here](https://github.com/Blackyukun/Simpleblog/blob/master/README.md)

���ʣ�[Mynovels](http://dingdian.herokuapp.com)

### �鿴����

֪��[������](https://zhuanlan.zhihu.com/p/28216335)

