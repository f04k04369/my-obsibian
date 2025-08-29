---
created:
tags: []
aliases:
UID: <% tp.date.now("YYYY-MM-DDTHH-mm-ss") %>
---
<%*
const uid = tp.date.now("YYYY-MM-DDTHH-mm-ss"); // UID形式のファイル名（
await tp.file.move(`${uid}`); // Vaultのルート直下にファイルを移動
%>

## プロパティ解説
- aliases：検索する際の別名
- tags：タグ管理用