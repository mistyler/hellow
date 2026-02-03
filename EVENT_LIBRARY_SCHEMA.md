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
      },
      {
        "eventId": "event:first-love",
        "name": "初恋萌芽",
        "ageRange": { "min": 13, "max": 20 },
        "probability": 0.2
      },
      {
        "eventId": "event:parent-separation",
        "name": "父母分居带来适应",
        "ageRange": { "min": 6, "max": 18 },
        "probability": 0.08
      },
      {
        "eventId": "event:family-reunion",
        "name": "家庭关系缓和",
        "ageRange": { "min": 6, "max": 18 },
        "probability": 0.12
      },
      {
        "eventId": "event:new-sibling",
        "name": "迎来弟妹",
        "ageRange": { "min": 4, "max": 16 },
        "probability": 0.1
      },
      {
        "eventId": "event:school-transfer",
        "name": "转学适应新环境",
        "ageRange": { "min": 6, "max": 18 },
        "probability": 0.11
      },
      {
        "eventId": "event:first-crush",
        "name": "暗恋同学",
        "ageRange": { "min": 12, "max": 19 },
        "probability": 0.18
      },
      {
        "eventId": "event:family-business-loss",
        "name": "家庭生意受挫",
        "ageRange": { "min": 10, "max": 25 },
        "probability": 0.09
      },
      {
        "eventId": "event:close-friend",
        "name": "结识知心好友",
        "ageRange": { "min": 8, "max": 20 },
        "probability": 0.22
      },
      {
        "eventId": "event:parents-divorce",
        "name": "父母离婚",
        "ageRange": { "min": 6, "max": 18 },
        "probability": 0.07
      },
      {
        "eventId": "event:first-part-time",
        "name": "第一次兼职",
        "ageRange": { "min": 16, "max": 22 },
        "probability": 0.15
      },
      {
        "eventId": "event:family-move",
        "name": "家庭搬迁",
        "ageRange": { "min": 6, "max": 20 },
        "probability": 0.12
      },
      {
        "eventId": "event:breakup",
        "name": "初次分手",
        "ageRange": { "min": 15, "max": 24 },
        "probability": 0.14
      },
      {
        "eventId": "event:family-illness",
        "name": "家庭成员患病",
        "ageRange": { "min": 10, "max": 30 },
        "probability": 0.08
      },
      {
        "eventId": "event:academic-award",
        "name": "学业获奖",
        "ageRange": { "min": 10, "max": 20 },
        "probability": 0.16
      },
      {
        "eventId": "event:family-debt",
        "name": "家庭负债增加",
        "ageRange": { "min": 12, "max": 30 },
        "probability": 0.09
      },
      {
        "eventId": "event:school-love",
        "name": "校园恋情发展",
        "ageRange": { "min": 15, "max": 22 },
        "probability": 0.17
      },
      {
        "eventId": "event:parent-layoff",
        "name": "父母失业",
        "ageRange": { "min": 10, "max": 25 },
        "probability": 0.08
      },
      {
        "eventId": "event:new-friend-circle",
        "name": "加入新的朋友圈",
        "ageRange": { "min": 12, "max": 20 },
        "probability": 0.2
      },
      {
        "eventId": "event:family-recovery",
        "name": "家庭经济好转",
        "ageRange": { "min": 12, "max": 30 },
        "probability": 0.1
      },
      {
        "eventId": "event:confession",
        "name": "向喜欢的人表白",
        "ageRange": { "min": 15, "max": 24 },
        "probability": 0.16
      },
      {
        "eventId": "event:parents-reconcile",
        "name": "父母关系修复",
        "ageRange": { "min": 6, "max": 20 },
        "probability": 0.07
      },
      {
        "eventId": "event:first-boyfriend",
        "name": "开始正式恋爱",
        "ageRange": { "min": 16, "max": 24 },
        "probability": 0.18
      },
      {
        "eventId": "event:family-expense",
        "name": "家庭重大支出",
        "ageRange": { "min": 12, "max": 30 },
        "probability": 0.09
      },
      {
        "eventId": "event:best-friend",
        "name": "遇到人生好友",
        "ageRange": { "min": 12, "max": 22 },
        "probability": 0.2
      },
      {
        "eventId": "event:parents-divorce-final",
        "name": "父母正式离婚",
        "ageRange": { "min": 6, "max": 20 },
        "probability": 0.06
      },
      {
        "eventId": "event:relationship-stable",
        "name": "恋情趋于稳定",
        "ageRange": { "min": 18, "max": 26 },
        "probability": 0.14
      },
      {
        "eventId": "event:family-bankruptcy",
        "name": "家庭破产",
        "ageRange": { "min": 12, "max": 30 },
        "probability": 0.05
      },
      {
        "eventId": "event:mentor-support",
        "name": "获得长辈支持",
        "ageRange": { "min": 16, "max": 28 },
        "probability": 0.12
      },
      {
        "eventId": "event:transfer-career",
        "name": "为家庭选择不同学校/专业",
        "ageRange": { "min": 16, "max": 24 },
        "probability": 0.1
      },
      {
        "eventId": "event:first-love-loss",
        "name": "恋情结束",
        "ageRange": { "min": 16, "max": 26 },
        "probability": 0.13
      },
      {
        "eventId": "event:parent-remarry",
        "name": "父母再婚",
        "ageRange": { "min": 8, "max": 22 },
        "probability": 0.06
      },
      {
        "eventId": "event:new-relationship",
        "name": "开启新恋情",
        "ageRange": { "min": 17, "max": 28 },
        "probability": 0.16
      },
      {
        "eventId": "event:family-debt-relief",
        "name": "家庭债务缓解",
        "ageRange": { "min": 15, "max": 35 },
        "probability": 0.08
      },
      {
        "eventId": "event:engagement",
        "name": "订婚",
        "ageRange": { "min": 20, "max": 32 },
        "probability": 0.07
      },
      {
        "eventId": "event:parent-illness",
        "name": "父母健康危机",
        "ageRange": { "min": 16, "max": 35 },
        "probability": 0.08
      },
      {
        "eventId": "event:breakup-after-engagement",
        "name": "订婚取消",
        "ageRange": { "min": 20, "max": 32 },
        "probability": 0.04
      },
      {
        "eventId": "event:family-investment-loss",
        "name": "家庭投资亏损",
        "ageRange": { "min": 18, "max": 40 },
        "probability": 0.08
      },
      {
        "eventId": "event:marriage",
        "name": "结婚",
        "ageRange": { "min": 20, "max": 35 },
        "probability": 0.06
      },
      {
        "eventId": "event:parent-recovery",
        "name": "家人健康好转",
        "ageRange": { "min": 16, "max": 40 },
        "probability": 0.1
      },
      {
        "eventId": "event:first-child",
        "name": "迎来第一个孩子",
        "ageRange": { "min": 22, "max": 38 },
        "probability": 0.05
      },
      {
        "eventId": "event:family-rebuild",
        "name": "家庭逐步重建",
        "ageRange": { "min": 18, "max": 40 },
        "probability": 0.09
      },
      {
        "eventId": "event:relationship-crisis",
        "name": "感情危机",
        "ageRange": { "min": 20, "max": 35 },
        "probability": 0.11
      },
      {
        "eventId": "event:career-love-balance",
        "name": "事业与感情拉扯",
        "ageRange": { "min": 22, "max": 35 },
        "probability": 0.12
      },
      {
        "eventId": "event:family-support",
        "name": "家庭给予关键支持",
        "ageRange": { "min": 18, "max": 40 },
        "probability": 0.14
      },
      {
        "eventId": "event:new-child",
        "name": "迎来新成员",
        "ageRange": { "min": 24, "max": 40 },
        "probability": 0.06
      },
      {
        "eventId": "event:relationship-stability",
        "name": "感情趋于稳定",
        "ageRange": { "min": 22, "max": 36 },
        "probability": 0.13
      },
      {
        "eventId": "event:family-property-loss",
        "name": "家庭资产缩水",
        "ageRange": { "min": 20, "max": 45 },
        "probability": 0.07
      },
      {
        "eventId": "event:love-growth",
        "name": "感情升温",
        "ageRange": { "min": 20, "max": 35 },
        "probability": 0.15
      },
      {
        "eventId": "event:parenting-pressure",
        "name": "育儿压力上升",
        "ageRange": { "min": 24, "max": 40 },
        "probability": 0.12
      },
      {
        "eventId": "event:family-caregiving",
        "name": "照顾老人",
        "ageRange": { "min": 26, "max": 45 },
        "probability": 0.1
      },
      {
        "eventId": "event:couple-counseling",
        "name": "尝试婚姻咨询",
        "ageRange": { "min": 24, "max": 40 },
        "probability": 0.08
      },
      {
        "eventId": "event:family-recovery",
        "name": "家庭财务好转",
        "ageRange": { "min": 20, "max": 45 },
        "probability": 0.1
      },
      {
        "eventId": "event:divorce",
        "name": "离婚",
        "ageRange": { "min": 24, "max": 45 },
        "probability": 0.06
      },
      {
        "eventId": "event:remarriage",
        "name": "再婚",
        "ageRange": { "min": 28, "max": 45 },
        "probability": 0.05
      },
      {
        "eventId": "event:family-conflict",
        "name": "家庭矛盾升级",
        "ageRange": { "min": 18, "max": 45 },
        "probability": 0.12
      },
      {
        "eventId": "event:love-reconciliation",
        "name": "感情破镜重圆",
        "ageRange": { "min": 20, "max": 40 },
        "probability": 0.07
      },
      {
        "eventId": "event:parent-loss",
        "name": "失去亲人",
        "ageRange": { "min": 18, "max": 50 },
        "probability": 0.05
      },
      {
        "eventId": "event:new-love",
        "name": "重拾恋爱",
        "ageRange": { "min": 20, "max": 40 },
        "probability": 0.11
      },
      {
        "eventId": "event:family-debt-clear",
        "name": "家庭债务清零",
        "ageRange": { "min": 22, "max": 50 },
        "probability": 0.08
      },
      {
        "eventId": "event:long-distance-love",
        "name": "异地恋考验",
        "ageRange": { "min": 20, "max": 35 },
        "probability": 0.1
      },
      {
        "eventId": "event:family-crisis",
        "name": "家庭突发危机",
        "ageRange": { "min": 20, "max": 50 },
        "probability": 0.09
      },
      {
        "eventId": "event:cohabitation",
        "name": "开始同居",
        "ageRange": { "min": 20, "max": 35 },
        "probability": 0.12
      },
      {
        "eventId": "event:family-education",
        "name": "子女教育压力",
        "ageRange": { "min": 26, "max": 45 },
        "probability": 0.11
      },
      {
        "eventId": "event:engagement",
        "name": "订婚筹备",
        "ageRange": { "min": 22, "max": 35 },
        "probability": 0.08
      },
      {
        "eventId": "event:family-loss-business",
        "name": "家庭生意失败",
        "ageRange": { "min": 22, "max": 50 },
        "probability": 0.06
      },
      {
        "eventId": "event:love-renewal",
        "name": "感情再度升温",
        "ageRange": { "min": 22, "max": 40 },
        "probability": 0.1
      },
      {
        "eventId": "event:parent-care",
        "name": "照护父母",
        "ageRange": { "min": 28, "max": 50 },
        "probability": 0.12
      },
      {
        "eventId": "event:family-lucky",
        "name": "家庭迎来好消息",
        "ageRange": { "min": 20, "max": 45 },
        "probability": 0.09
      },
      {
        "eventId": "event:family-recovery",
        "name": "家庭逐步走出困难",
        "ageRange": { "min": 24, "max": 50 },
        "probability": 0.1
      },
      {
        "eventId": "event:love-marriage",
        "name": "恋爱走向婚姻",
        "ageRange": { "min": 22, "max": 35 },
        "probability": 0.07
      },
      {
        "eventId": "event:family-celebration",
        "name": "家庭庆典",
        "ageRange": { "min": 24, "max": 50 },
        "probability": 0.12
      },
      {
        "eventId": "event:new-love",
        "name": "邂逅新的感情",
        "ageRange": { "min": 22, "max": 40 },
        "probability": 0.11
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

## 2) 分类索引（CategoryIndex）最小结构

```json
{
  "categoryIndex": {
    "categories": {
      "爱情类": {
        "events": [
          "event:first-love",
          "event:first-crush",
          "event:breakup",
          "event:school-love",
          "event:confession",
          "event:first-boyfriend",
          "event:relationship-stable",
          "event:first-love-loss",
          "event:new-relationship",
          "event:engagement",
          "event:breakup-after-engagement",
          "event:marriage",
          "event:relationship-crisis",
          "event:relationship-stability",
          "event:love-growth",
          "event:couple-counseling",
          "event:divorce",
          "event:remarriage",
          "event:love-reconciliation",
          "event:new-love",
          "event:long-distance-love",
          "event:cohabitation",
          "event:love-renewal",
          "event:love-marriage"
        ]
      },
      "友情类": {
        "events": [
          "event:close-friend",
          "event:best-friend",
          "event:new-friend-circle"
        ]
      },
      "事业类": {
        "events": [
          "event:first-part-time",
          "event:transfer-career",
          "event:career-love-balance"
        ]
      },
      "学业类": {
        "events": [
          "event:school-transfer",
          "event:academic-award",
          "event:mentor-support",
          "event:family-education"
        ]
      },
      "家庭类": {
        "events": [
          "event:parent-separation",
          "event:family-reunion",
          "event:new-sibling",
          "event:family-business-loss",
          "event:parents-divorce",
          "event:family-move",
          "event:family-illness",
          "event:family-debt",
          "event:parent-layoff",
          "event:family-recovery",
          "event:parents-reconcile",
          "event:family-expense",
          "event:parents-divorce-final",
          "event:family-bankruptcy",
          "event:parent-remarry",
          "event:family-debt-relief",
          "event:parent-illness",
          "event:family-investment-loss",
          "event:parent-recovery",
          "event:first-child",
          "event:family-rebuild",
          "event:family-support",
          "event:new-child",
          "event:family-property-loss",
          "event:parenting-pressure",
          "event:family-caregiving",
          "event:family-conflict",
          "event:parent-loss",
          "event:family-debt-clear",
          "event:family-crisis",
          "event:family-loss-business",
          "event:parent-care",
          "event:family-lucky",
          "event:family-celebration"
        ]
      }
    }
  }
}
```

**最小字段说明：**
- `categories`: 以类别为 key，值为该类别的事件列表。
