# Pythonのイメージ
FROM python:3.9

# 作業ディレクトリを設定する
WORKDIR /Docker

# 必要なパッケージをインストールする
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

# ローカルのソースコードをコピーする
COPY . .

# コンテナ起動時に実行するコマンドを設定する
CMD ["python", "./sample.py"]
