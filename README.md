<h1 align="center">kaotao00</h1>
<p align="center"><strong>大模型应用开发 · RAG · Agent · Python 后端</strong></p>
<p align="center">从本地模型部署、企业知识库构建，到多 Agent 工作流与应用评测。</p>
<p align="center"><a href="#代表项目">代表项目</a> · <a href="#实习实践">实习实践</a> · <a href="#技术栈">技术栈</a> · <a href="https://github.com/kaotao00?tab=repositories">全部仓库</a></p>

## 代表项目

### AI 管家 · 私有化知识库问答

用 Ollama 在本地运行模型，把文档切分、向量化、索引更新和检索问答串成一条完整链路。项目提供 Web、HTTP API 和 CLI 三种入口，内置本地向量检索，并预留 Milvus 接入。 [查看仓库](https://github.com/kaotao00/-ai)

### 建筑工程智能标书平台 · 多 Agent 协作

面向标书编制，把 PDF、Word 和 Excel 企业资料增量导入知识库，结合关键词检索、相似度匹配和重排筛选相关材料，再由多个 Agent 协作处理标书任务。支持可选的 LangChain 和 Milvus 集成。 [查看仓库](https://github.com/kaotao00/-agent-)

### 泳池人员风险辅助检测 · 计算机视觉

基于 YOLOv3 和 OpenCV 检测人员，为每个人维护独立 ID 与轨迹。在滑动时间窗口中提取速度、位移范围和低速时间占比，输出实验性风险评分，并用模拟测试覆盖多人关联、漏检和不规则采样。 [查看仓库](https://github.com/kaotao00/Drowning-Detector-master)

### 声誉风险监测控制台 · 搜索与人工复核

通过 FastAPI 接入实时搜索，对结果做规则分级，把来源或风险尚待确认的信息送入人工复核，并用图表展示风险趋势与信源分布。 [查看仓库](https://github.com/kaotao00/Chery-Auto-Reputation-System)

## 实习实践

参与 AI 教学与在线评测平台开发，涉及智能出题、代码判题和并发测试。

- **生成质量评审** · 在大模型出题流程中接入 JEV，按「生成 → 正确性复核 → 修订重生成」迭代。主观题辅助评分提供参考分和理由，最终成绩由教师确认。
- **异步判题** · 参与 Docker 沙箱判题链路，覆盖 C、C++、Python、Java 和 JavaScript。通过隐藏用例校验作答，并用持久化队列和执行槽位处理集中提交。
- **混合负载压测** · 模拟学生并发提交、业务查询和结果轮询，分别观察接口受理耗时、判题完成 P95 和队列积压，并验证队列满载与任务超时后的恢复流程。

## 技术栈

| 方向 | 技术与实践 |
| --- | --- |
| 大模型应用 | RAG · Agent · 多 Agent 协作 · Prompt Engineering · 模型评审 |
| 模型部署与检索 | Ollama · LangChain · LangSmith · Milvus |
| Python 后端 | FastAPI · Django · Celery · asyncio |
| 数据与工程 | MySQL · PostgreSQL · Redis · Docker · Git |
