依存関係グラフは、リポジトリに保存されているマニフェストファイルおよびロックファイルのサマリーです。 それぞれのリポジトリにおいて、依存関係グラフは以下を表示します。{% ifversion fpt or ghec %}

- リポジトリが依存している依存関係、エコシステム、パッケージ
- リポジトリに依存する対象、リポジトリ、パッケージ{% else %}依存関係、すなわちリポジトリが依存するエコシステムとパッケージ。 {% data variables.product.product_name %}は、リポジトリに依存する対象、リポジトリ、パッケージに関する情報を計算しません。{% endif %}