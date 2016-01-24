夢のある研究
====

# Overview  
男達はグランドラインを目指し、夢を追い続ける。世は正に大海賊時代！  

## Sample URL
[http://ec2-54-148-249-100.us-west-2.compute.amazonaws.com:8080/boobs_designer/]

## Description
3DモデルをIGAで最適化  
djangoを使って書いてます([使いかた](http://docs.djangoproject.jp/en/latest/intro/tutorial01.html))  

## フォルダ構成

- app webアプリ本体  
    - /views.py  httpリクエストを受けてレスポンスを返す処理を書くファイル  
    - /utils  3Dモデリングの更新に使っている関数をとりあえずこの中に入れた  
    - /templates  webアプリで使うhtmlテンプレート  
    - /static  webアプリで使う静的ファイル  
- oppai_iga django  プロジェクト全体の設定ファイルがおいてある  
- templates django  プロジェクト全体で使うhtmlテンプレート  
- static django  プロジェクト全体で使う静的ファイル  

## Requirement
    python 2.7  

## How to Use(local)
    $git clone https://github.com/m-masataka/oppai_iga.git  
    $cd oppai_iga  
    $pip install -r requirements.txt  
    $python manage.py migrate  
    $python manage.py runserver  
Now, you can access [http://localhost:8000/boobs_designer/](http://localhost:8000/boobs_designer/)  

## Slack  

 - #general on <https://oppaiiga.slack.com>

## Author
[m-masataka](https://github.com/m-masataka)  
[bandoshintaro](https://github.com/bandoshintaro)  
