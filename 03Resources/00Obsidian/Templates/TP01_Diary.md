---
date_modified: <% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>
reading: "True"
sports: "True"
mood:
coding: "True"
meditation: "True"
---
<%*
const fileName = tp.file.title;

// 从文件名获取日期
const year = fileName.substring(0, 4);
const month = fileName.substring(0, 6);

// 移动到对应年月目录
await tp.file.move(
  "/00PeriodicNotes/" + year + "/" + month + "/" + fileName
);

tp.file.cursor();
-%>

## 今日计划


## 今日总结