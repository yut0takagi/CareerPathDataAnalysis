# CareerPathAnalysis

## 概要

**CareerPathAnalysis** は、キャリアに関するデータをWebスクレイピングによって収集し、  
以下のプロセスを通じてキャリアパスの分析や知識支援を行うPythonベースのプロジェクトです。

- Webスクレイピングによるデータ収集  
- 探索的データ分析（EDA）による可視化とパターンの抽出  
- RAG（Retrieval-Augmented Generation）構築  
- LangChainを用いたインテリジェントな問い合わせ応答の実装  

## 特徴

- 求人情報やキャリア事例を自動で取得
- データに基づいたキャリア選択の傾向を分析
- 自分に合った進路を提案してくれるAIチャットシステムの基盤構築が可能
- Pythonによる柔軟で拡張性のある実装

## 使用技術

- **言語**: Python
- **主要ライブラリ**:  
  - `BeautifulSoup`, `requests`（Webスクレイピング）  
  - `pandas`, `matplotlib`, `seaborn`（EDA）  
  - `LangChain`, `OpenAI` または `LlamaIndex`（RAG実装）  

## 今後の展望

- 複数の求人サイトからのクロール対応
- ユーザー入力を元にしたキャリア診断AIチャットの完成
- 分野ごとのRAGインスタンスの生成

## セットアップ

```bash
git clone https://github.com/yutotkg/CareerPathAnalysis.git
cd CareerPathAnalysis
pip install -r requirements.txt