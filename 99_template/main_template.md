---
tags: []
aliases:
UID: <% tp.date.now("YYYY-MM-DDTHH-mm-ss") %>
date: <% tp.file.creation_date() %>
---

[[2025-08-31T21-19-53]]
<%*
const uid = tp.date.now("YYYY-MM-DDTHH-mm-ss"); // UID形式のファイル名（
await tp.file.move(`${uid}`); // Vaultのルート直下にファイルを移動
%>

## プロパティ解説
- aliases：検索する際の別名
- tags：タグ管理用