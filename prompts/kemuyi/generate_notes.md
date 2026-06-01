# 科目一挂车笔记生成提示词

请读取以下文件：

- knowledge_base/kemuyi/product_card.md
- knowledge_base/kemuyi/content_agent_rules.md
- knowledge_base/kemuyi/title_structure_library.md
- knowledge_base/kemuyi/body_structure_library.md
- knowledge_base/kemuyi/seo_keywords.md
- knowledge_base/kemuyi/forbidden_words.md
- knowledge_base/kemuyi/daily_generation_rules.md

## 任务
根据科目一项目规则，生成指定数量的小红书挂车图文笔记。

## 每篇必须输出
1. 产品名称
2. 笔记类型
3. 标题结构
4. 正文结构
5. 标题
6. 正文
7. 标签
8. 商品引导话术
9. AI评分
10. 扣分原因
11. 风险检查结果
12. 是否建议发布

## 要求
1. 每篇角度不同。
2. 标题不能重复。
3. 正文开头不能重复。
4. 商品引导话术不能重复。
5. 标签放正文最后。
6. 禁止使用 forbidden_words.md 里的禁用表达。
7. 低于70分必须自动重写。
