# 事件库与年度索引（最小示范）

下面是**最小字段**示范，只保留“事件库 + 年度索引”的骨架，便于你后续自行填充。

---

## 1) 事件库（EventLibrary）最小结构

```json
{
  "eventLibrary": {
    "events": [
      {
        "eventId": "event:placeholder",
        "name": "占位事件",
        "ageRange": { "min": 0, "max": 100 },
        "probability": 0.0
      }
    ]
  }
}
```

**最小字段说明：**
- `eventId`: 事件唯一标识。
- `name`: 事件名称。
- `ageRange`: 该事件适用的年龄范围。
- `probability`: 基础概率（0-1）。

---

## 2) 年度索引（YearIndex）最小结构

```json
{
  "yearIndex": {
    "startYear": 1990,
    "endYear": 2025,
    "years": {
      "1990": {
        "events": ["event:placeholder"]
      }
    }
  }
}
```

**最小字段说明：**
- `years`: 以年份为 key，值为该年的事件列表。
