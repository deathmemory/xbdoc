# �ӿ�˵��
api ����ַ��http://www.xbjsq.com

##ע��ӿ�
| ˵��        |  value | 
| ------------- |-------------|
| Method     |  POST  |
| URL     |  /e/member/doaction.php  |
| ��֤���ȡ��ַ | /e/ShowKey/?v=reg |

�������

| key        | default value           | Description  |
| ------------- |:-------------:| -----:|
| username     |  - | �û��� |
| password      |  - | ���� |
| repassword     | -  | ȷ������ |
| email      | - | email |
| key     | - | ��֤�� |
| enews      | register | �̶�ֵ |
| groupid      | 5 | �̶�ֵ |
| tobind      | 0 | �̶�ֵ |

##��¼�ӿ�
| ˵��        |  value | 
| ------------- |-------------|
| Method     |  POST  |
| URL     |  /e/member/doaction.php  |
| ��֤���ȡ��ַ | e/ShowKey/?v=login&t=`<random>` |

�������

| key        | default value           | Description  |
| ------------- |:-------------:| -----:|
| username     |  - | �û��� |
| password      |  - | ���� |
| key     | - | ��֤�� |
| lifetime      | 0 | cookie ����ʱЧ |
| enews      | login | �̶�ֵ |
| tobind      | 0 | �̶�ֵ |

##�˳��ӿ�
Ĭ�ϴ� Cookie ����

| ˵��        |  value | 
| ------------- |-------------|
| Method     |  GET  |
| URL     |  /e/member/doaction.php?enews=exit  |
