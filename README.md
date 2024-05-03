# Streamlit Custom Component

Streamlit component that allows you to do X

## Overview

<https://github.com/streamlit/component-template> の React テンプレートを抽出

## Usage

1. <https://github.com/masachika-kamada/fast-python-nodejs-docker> をクローン
2. VS Code の DevContainers で Docker 環境を開く
3. このリポジトリをクローン
4. 1 つ目のターミナルで以下を実行
   ```
   cd my_component/frontend/
   npm install
   npm start
   ```
5. 2 つ目のターミナルで以下を実行
   ```
   pip install streamlit
   pip install -e .
   streamlit run my_component/example.py
   ```
6. <http://localhost:8501/> から起動したページを確認
