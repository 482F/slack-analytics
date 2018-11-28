# slack-analytics

## ��
- Python3.X
- pandas

## �g����
1. Slack���烍�O���_�E�����[�h����i�ݒ�ƌ������f�[�^�̃C���|�[�g�^�G�N�X�|�[�g�j
2. data�t�H���_���쐬���A1���𓀂������̂�u��
3. createMasterCsv.py�����s
4. createTalkCsv.py�����s

## createMasterCsv.py
channels.json�Ausers.json����csv�쐬
- output
	- channels.csv
	- users.csv

## createTalkCsv.py
�`�����l�����Ɠ��t���Ƃ̃��O���烁�b�Z�[�W�A���A�N�V�����A�����V����csv���쐬
- output
	- talk.csv
	- reaction.csv
	- mention.csv
	- �`�����l�����f�B���N�g��
		- talk.csv
		- reaction.csv
		- mention.csv

### ���b�Z�[�W
|channel_id|talk_id|talk_user|text|
|:--|:--|:--|:--|
|C5XXXXXXX|XX1|U9XXXXXXX|`<@U8YYYYYYY>`����ɂ���|
|C5XXXXXXX|XX2|U8YYYYYYY|�A�肽��|
|C5XXXXXXX|XX3|U9XXXXXXX|��������|

### ���A�N�V����
|channel_id|talk_id|talk_user|reaction_user|emoji|
|:--|:--|:--|:--|:--|
|C5XXXXXXX|XX1|U9XXXXXXX|U8YYYYYYY|ok_woman|
|C5XXXXXXX|XX1|U9XXXXXXX|U7ZZZZZZZ|iine|
|C5XXXXXXX|XX2|U8YYYYYYY|U9XXXXXXX|wakaru|
|C5XXXXXXX|XX2|U9XXXXXXX|U7ZZZZZZZ|otukare|

### �����V����
|channel_id|talk_id|talk_user|mention_user|
|:--|:--|:--|:--|
|C5XXXXXXX|XX1|U9XXXXXXX|U8YYYYYYY|

