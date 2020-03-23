## postgresql 语法

1. Oracle 中的　`wmsys.wm_concat(guid)` 可以替换为　`listagg(guid, ',') within group(order by guid) guids`
