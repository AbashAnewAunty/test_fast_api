# Test Fast API

## About

Udemy > [FastAPI + ReactによるフルスタックWeb開発](https://ibisjp.udemy.com/course/farm-stack-react-fastapi/learn/lecture/29201422#overview)

## Get Startd

1. MongoDB上のクラスターが起動されていることを確認（または起動する）
2. MongoDBへのAPIアクセスキーを記載した.envファイルをroot/に配置
3. 次のコマンドを実行し、開発環境構築
※ TODO: python3のバージョンを指定するコマンドを追加する（現状はpython3.9であることを前提としている）

    ```
    pytho3 -m venv env_api
    source env_api/bin/activate
    pip install -r requirements.txt  
    uvicorn main:app --reload
    ```

4. 実行後ターミナルに表示されているURL(ex. <http://127.0.0.1:8000> )にアクセスし、以下が表示されていればOK

> {"message":"Welcome to Fast API"}
