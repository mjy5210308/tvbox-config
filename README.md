# TVBox �������òֿ�

�ҵ� TVBox ���ã�ͨ�� jsdelivr CDN �����ڹ��ڷ��ʡ�

## �ļ�˵��

- `tvbox.json` - TVBox ������ڣ����� store_api �� lives��
- `source.json` - ���ýӿ�Դ��catvod.json ��ʽ��

## ʹ�÷���

�� TVBox ���õ�ַ���룺

```
https://cdn.jsdelivr.net/gh/mjy5210308/tvbox-config@main/tvbox.json
```

## ˫Դ����

`tvbox.json` �� store_api �������� URL��
1. FongMiTV����̫Ӳ���ٷ�Դ - ��Դ
2. �Խ� source.json - ����

TVBox ����ʱ�ᰴ˳���ԣ���Դ������ʱ�Զ��ñ��á�

## �޸�����

ֱ�ӱ༭ GitHub �ϵ��ļ����ύ��� 1-2 ���� jsdelivr ͬ����

## ��ӵ㲥Դ

�༭ `source.json`���� sites ���������վ�㣺

```json
{
  "sites": [
    {
      "key": "site_id",
      "name": "վ����",
      "type": 3,
      "api": "https://example.com/api.php/provide/vod",
      "searchable": 1,
      "filterable": 1,
      "quickSearch": 1
    }
  ]
}
```

## ֱ��Դ

`tvbox.json` �� lives �ֶ��������������Ӹ۰�ֱ̨����