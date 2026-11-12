ローカル上で.env上にあるAPIキーを動かすには，以下のように実行する必要がある

uv run --env-file .env python -m app.ask "LoRAとは何ですか？"
uv run --env-file .env python -m app.agent --trace "LoRAとQLoRAの違いは？"

