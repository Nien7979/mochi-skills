# Nguồn & giấy phép

Tổng hợp ngày 25/11/2026 từ catalog [MochiStudio Skills](https://mochistudio.io.vn/skills) (487 mục). Catalog tự giới thiệu là tuyển chọn skill, agent và công cụ AI mã nguồn mở trên GitHub, dẫn thẳng tới repo gốc.

## Phương pháp

- Lấy danh sách 487 mục từ trang danh sách + trang chi tiết của MochiStudio (chỉ đọc).
- Với mỗi repo gốc, tìm file `SKILL.md` qua GitHub code search và xác định file LICENSE ở gốc repo.
- Chỉ copy file text UTF-8: `SKILL.md` + các file được chính `SKILL.md` đó tham chiếu trực tiếp (references/scripts/assets) + file LICENSE gốc trong từng thư mục skill.
- Không clone toàn bộ repo (tổng dung lượng gốc ước tính 50–400 GB), không chạy bất kỳ script nào trong quá trình tổng hợp.
- Mô tả trong README là do người tổng hợp tự viết (liệt kê tên skill) hoặc trích mô tả gốc trong file SKILL.md; không copy nguyên văn mô tả tiếng Việt của MochiStudio (robots.txt của họ để `ai-train=no`).

## Giấy phép theo repo

- **Giấy phép cho phép dùng lại** (MIT, Apache-2.0, BSD, ISC, MPL-2.0…): file skill được copy nguyên trạng kèm LICENSE gốc trong từng thư mục.
- **Copyleft mạnh (GPL/AGPL):** chỉ lấy nguyên trạng kèm LICENSE, không sửa đổi.
- **Giấy phép hạn chế (Sustainable Use, Elastic, BUSL…) hoặc không xác minh được:** không copy file, chỉ ghi link ở [THAM-KHAO.md](THAM-KHAO.md).

## File đã lược bỏ khi tổng hợp

- File nhị phân (ảnh PNG/JPG, font, PDF, gói nén, audio/video) — công cụ đẩy GitHub chỉ nhận file text UTF-8. Lấy bản gốc tại link repo gốc của từng skill.
- File `.mcp.json` / `mcp.json` — không copy vì lý do an toàn.
- File tham chiếu mà SKILL.md không nhắc tới trực tiếp — lấy tại repo gốc nếu cần.

## Danh sách repo gốc đã lấy file

| Repo gốc | Giấy phép | Số file SKILL.md |
|---|---|---|
| https://github.com/openclaw/openclaw | MIT | 141 |
| https://github.com/mattpocock/skills | MIT | 40 |
| https://github.com/obra/superpowers | MIT | 15 |
| https://github.com/affaan-m/ECC | MIT | 1090 |
| https://github.com/deepseek-ai/deepseek-harness | MIT | 39 |
| https://github.com/NousResearch/hermes-agent | MIT | 186 |
| https://github.com/anomalyco/opencode | MIT | 26 |
| https://github.com/n8n-io/n8n | NOASSERTION | 48 |
| https://github.com/firecrawl/firecrawl | AGPL-3.0 | 5 |
| https://github.com/DietrichGebert/ponytail | MIT | 13 |
| https://github.com/Significant-Gravitas/AutoGPT | NOASSERTION | 13 |
| https://github.com/f/prompts.chat | NOASSERTION | 4 |
| https://github.com/huggingface/transformers | Apache-2.0 | 1 |
| https://github.com/langflow-ai/langflow | MIT | 11 |
| https://github.com/nextlevelbuilder/ui-ux-pro-max-skill | MIT | 13 |
| https://github.com/Graphify-Labs/graphify | Apache-2.0 | 1 |
| https://github.com/github/spec-kit | MIT | 2 |
| https://github.com/Shubhamsaboo/awesome-llm-apps | Apache-2.0 | 10 |
| https://github.com/harry0703/MoneyPrinterTurbo | MIT | 1 |
| https://github.com/garrytan/gstack | MIT | 76 |
| https://github.com/openai/codex | Apache-2.0 | 6 |
| https://github.com/ggml-org/llama.cpp | MIT | 5 |
| https://github.com/stablyai/orca | MIT | 12 |
| https://github.com/microsoft/generative-ai-for-beginners | MIT | 1 |
| https://github.com/TauricResearch/TradingAgents | Apache-2.0 | 16 |
| https://github.com/earendil-works/pi | MIT | 18 |
| https://github.com/JuliusBrussee/caveman | Apache-2.0 | 28 |
| https://github.com/browser-use/browser-use | MIT | 7 |
| https://github.com/Leonxlnx/taste-skill | MIT | 1 |
| https://github.com/addyosmani/agent-skills | MIT | 26 |
| https://github.com/thedotmack/claude-mem | Apache-2.0 | 47 |
| https://github.com/debpalash/VoiceStudio | AGPL-3.0 | 4 |
| https://github.com/paperclipai/paperclip | MIT | 65 |
| https://github.com/pbakaus/impeccable | Apache-2.0 | 20 |
| https://github.com/Panniantong/Agent-Reach | MIT | 1 |
| https://github.com/google-gemini/gemini-cli | Apache-2.0 | 26 |
| https://github.com/nexu-io/open-design | Apache-2.0 | 557 |
| https://github.com/pytorch/pytorch | BSD-3-Clause | 19 |
| https://github.com/microsoft/playwright | Apache-2.0 | 11 |
| https://github.com/tt-a1i/archify | Apache-2.0 | 6 |
| https://github.com/vllm-project/vllm | Apache-2.0 | 11 |
| https://github.com/infiniflow/ragflow | Apache-2.0 | 2 |
| https://github.com/OpenHands/OpenHands | MIT | 8 |
| https://github.com/Egonex-AI/Understand-Anything | MIT | 9 |
| https://github.com/PaddlePaddle/PaddleOCR | Apache-2.0 | 2 |
| https://github.com/modelcontextprotocol/servers | Apache-2.0 | 11 |
| https://github.com/koala73/worldmonitor | AGPL-3.0 | 74 |
| https://github.com/heygen-com/hyperframes | Apache-2.0 | 29 |
| https://github.com/rtk-ai/rtk | Apache-2.0 | 12 |
| https://github.com/bytedance/deer-flow | MIT | 33 |
| https://github.com/career-ops-hq/career-ops | MIT | 17 |
| https://github.com/ruvnet/ruflo | MIT | 403 |
| https://github.com/OpenMontageInc/OpenMontage | AGPL-3.0 | 141 |
| https://github.com/shareAI-lab/learn-claude-code | MIT | 4 |
| https://github.com/microsoft/ai-agents-for-beginners | MIT | 336 |
| https://github.com/headroomlabs-ai/headroom | Apache-2.0 | 2 |
| https://github.com/unslothai/unsloth | AGPL-3.0 | 2 |
| https://github.com/rohitg00/ai-engineering-from-scratch | MIT | 39 |
| https://github.com/hugohe3/ppt-master | MIT | 1 |
| https://github.com/colbymchenry/codegraph | MIT | 2 |
| https://github.com/openai/openai-cookbook | MIT | 3 |
| https://github.com/usestrix/strix | Apache-2.0 | 9 |
| https://github.com/cloudflare/security-audit-skill | MIT | 1 |
| https://github.com/hiyouga/LlamaFactory | Apache-2.0 | 4 |
| https://github.com/Fission-AI/OpenSpec | MIT | 32 |
| https://github.com/ZhuLinsen/daily_stock_analysis | MIT | 9 |
| https://github.com/ai-job-search-dev/ai-job-search | MIT | 3 |
| https://github.com/blader/humanizer | MIT | 1 |
| https://github.com/cline/cline | Apache-2.0 | 8 |
| https://github.com/mvanhorn/last30days-skill | MIT | 1 |
| https://github.com/docling-project/docling | MIT | 5 |
| https://github.com/cathrynlavery/diagram-design | MIT | 1 |
| https://github.com/mem0ai/mem0 | Apache-2.0 | 56 |
| https://github.com/shanraisshan/claude-code-best-practice | MIT | 10 |
| https://github.com/openinterpreter/openinterpreter | Apache-2.0 | 18 |
| https://github.com/pingdotgg/t3code | MIT | 35 |
| https://github.com/upstash/context7 | MIT | 10 |
| https://github.com/BerriAI/litellm | MIT | 10 |
| https://github.com/penpot/penpot | GPL-3.0 | 24 |
| https://github.com/vectorize-io/hindsight | MIT | 20 |
| https://github.com/ayghri/i-have-adhd | MIT | 2 |
| https://github.com/coreyhaines31/marketingskills | MIT | 28 |
| https://github.com/twentyhq/twenty | AGPL-3.0 | 13 |
| https://github.com/HKUDS/DeepTutor | Apache-2.0 | 8 |
| https://github.com/crewAIInc/crewAI | MIT | 4 |
| https://github.com/jamiepine/voicebox | MIT | 4 |
| https://github.com/MemPalace/mempalace | MIT | 15 |
| https://github.com/bojieli/ai-agent-book | Apache-2.0 | 30 |
| https://github.com/Nutlope/hallmark | MIT | 1 |
| https://github.com/ChromeDevTools/chrome-devtools-mcp | Apache-2.0 | 8 |
| https://github.com/emilkowalski/skills | MIT | 20 |
| https://github.com/K-Dense-AI/scientific-agent-skills | MIT | 57 |
| https://github.com/Imbad0202/academic-research-skills | NOASSERTION | 3 |
| https://github.com/multica-ai/multica | Apache-2.0 | 6 |
| https://github.com/aaif-goose/goose | Apache-2.0 | 2 |
| https://github.com/bmad-code-org/BMAD-METHOD | MIT | 26 |
| https://github.com/alibaba/open-code-review | Apache-2.0 | 10 |
| https://github.com/anthropics/claude-cookbooks | MIT | 4 |
| https://github.com/CherryHQ/cherry-studio | AGPL-3.0 | 26 |
| https://github.com/obsidianmd/obsidian-skills | MIT | 7 |
| https://github.com/vercel-labs/agent-browser | Apache-2.0 | 12 |
| https://github.com/herdrdev/herdr | Apache-2.0 | 34 |
| https://github.com/roboflow/supervision | MIT | 1 |
| https://github.com/tldraw/tldraw | NOASSERTION | 17 |
| https://github.com/mudler/LocalAI | MIT | 16 |
| https://github.com/HKUDS/nanobot | MIT | 9 |
| https://github.com/sickn33/agentic-awesome-skills | MIT | 9841 |
| https://github.com/zhayujie/CowAgent | MIT | 6 |
| https://github.com/anthropics/claude-plugins-official | Apache-2.0 | 62 |
| https://github.com/luongnv89/claude-howto | MIT | 43 |
| https://github.com/LibreChat-AI/LibreChat | MIT | 4 |
| https://github.com/siyuan-note/siyuan | AGPL-3.0 | 1 |
| https://github.com/AstrBotDevs/AstrBot | AGPL-3.0 | 4 |
| https://github.com/streamlit/streamlit | Apache-2.0 | 0 |
| https://github.com/janhq/jan | Apache-2.0 | 2 |
| https://github.com/reactive-resume/reactive-resume | MIT | 34 |
| https://github.com/gradio-app/gradio | Apache-2.0 | 4 |
| https://github.com/THU-MAIC/OpenMAIC | MIT | 28 |
| https://github.com/agno-agi/agno | Apache-2.0 | 7 |
| https://github.com/tinyhumansai/openhuman | AGPL-3.0 | 1 |
| https://github.com/wshobson/agents | MIT | 185 |
| https://github.com/volcengine/OpenViking | AGPL-3.0 | 96 |
| https://github.com/chatboxai/chatbox | AGPL-3.0 | 3 |
| https://github.com/linshenkx/prompt-optimizer | AGPL-3.0 | 0 |
| https://github.com/patchy631/ai-engineering-hub | MIT | 10 |
| https://github.com/anthropics/financial-services | Apache-2.0 | 112 |
| https://github.com/github/awesome-copilot | MIT | 480 |
| https://github.com/ToolJet/ToolJet | AGPL-3.0 | 9 |
| https://github.com/codewhale-hq/Codewhale | MIT | 77 |
| https://github.com/datalab-to/marker | Apache-2.0 | 2 |
| https://github.com/Yeachan-Heo/oh-my-claudecode | MIT | 85 |
| https://github.com/Donchitos/Claude-Code-Game-Studios | MIT | 78 |
| https://github.com/vercel-labs/skills | MIT | 5 |
| https://github.com/The-Vibe-Company/quivr | MIT | 44 |
| https://github.com/can1357/oh-my-pi | MIT | 26 |
| https://github.com/google/langextract | Apache-2.0 | 1 |
| https://github.com/RSSNext/Folo | AGPL-3.0 | 11 |
| https://github.com/AlexsJones/llmfit | MIT | 1 |
| https://github.com/sgl-project/sglang | Apache-2.0 | 37 |
| https://github.com/CopilotKit/CopilotKit | MIT | 21 |
| https://github.com/alchaincyf/nuwa-skill | MIT | 16 |
| https://github.com/HKUDS/Vibe-Trading | MIT | 90 |
| https://github.com/virgiliojr94/book-to-skill | MIT | 1 |
| https://github.com/agentscope-ai/QwenPaw | Apache-2.0 | 49 |
| https://github.com/Tencent/WeKnora | Apache-2.0 | 6 |
| https://github.com/langfuse/langfuse | MIT | 40 |
| https://github.com/microsoft/graphrag | MIT | 1 |
| https://github.com/anthropics/knowledge-work-plugins | Apache-2.0 | 252 |
| https://github.com/mukul975/Anthropic-Cybersecurity-Skills | Apache-2.0 | 820 |
| https://github.com/freestylefly/awesome-gpt-image-2 | MIT | 1 |
| https://github.com/qdrant/qdrant | Apache-2.0 | 2 |
| https://github.com/openai/codex-plugin-cc | Apache-2.0 | 3 |
| https://github.com/huggingface/diffusers | Apache-2.0 | 4 |
| https://github.com/OpenBMB/ChatDev | Apache-2.0 | 3 |
| https://github.com/github/github-mcp-server | MIT | 18 |
| https://github.com/iOfficeAI/AionUi | Apache-2.0 | 6 |
| https://github.com/davila7/claude-code-templates | MIT | 927 |
| https://github.com/zeroclaw-labs/zeroclaw | Apache-2.0 | 12 |
| https://github.com/iOfficeAI/OfficeCLI | Apache-2.0 | 12 |
| https://github.com/onyx-dot-app/onyx | NOASSERTION | 28 |
| https://github.com/topoteretes/cognee | Apache-2.0 | 27 |
| https://github.com/tirth8205/code-review-graph | MIT | 8 |
| https://github.com/trycua/cua | MIT | 12 |
| https://github.com/zarazhangrui/frontend-slides | MIT | 2 |
| https://github.com/googleworkspace/cli | Apache-2.0 | 95 |
| https://github.com/langchain-ai/deepagents | MIT | 26 |
| https://github.com/AgriciDaniel/claude-seo | MIT | 40 |
| https://github.com/ComposioHQ/composio | MIT | 19 |
| https://github.com/jackwener/OpenCLI | Apache-2.0 | 5 |
| https://github.com/nanocoai/nanoclaw | MIT | 64 |
| https://github.com/QwenLM/qwen-code | Apache-2.0 | 48 |
| https://github.com/assafelovic/gpt-researcher | Apache-2.0 | 3 |
| https://github.com/openai/openai-agents-python | MIT | 18 |
| https://github.com/karakeep-app/karakeep | AGPL-3.0 | 3 |
| https://github.com/rohitg00/agentmemory | Apache-2.0 | 17 |
| https://github.com/aishwaryanr/awesome-generative-ai-guide | MIT | 3 |
| https://github.com/opendataloader-project/opendataloader-pdf | Apache-2.0 | 1 |
| https://github.com/alirezarezvani/claude-skills | MIT | 504 |
| https://github.com/op7418/guizang-ppt-skill | AGPL-3.0 | 1 |
| https://github.com/simstudioai/sim | Apache-2.0 | 43 |
| https://github.com/alchaincyf/huashu-design | MIT | 1 |
| https://github.com/labring/FastGPT | Apache-2.0 | 20 |
| https://github.com/alibaba/page-agent | MIT | 5 |
| https://github.com/mastra-ai/mastra | Apache-2.0 | 62 |
| https://github.com/srbhr/Resume-Matcher | Apache-2.0 | 1 |
| https://github.com/yamadashy/repomix | MIT | 21 |
| https://github.com/jarrodwatts/claude-hud | MIT | 1 |
| https://github.com/charmbracelet/crush | MIT | 5 |
| https://github.com/mlflow/mlflow | Apache-2.0 | 11 |
| https://github.com/gastownhall/beads | MIT | 3 |
| https://github.com/manaflow-ai/cmux | AGPL-3.0 | 27 |
| https://github.com/PrefectHQ/fastmcp | Apache-2.0 | 16 |
| https://github.com/every-app/open-seo | MIT | 40 |
| https://github.com/wheresryan22/anatomy | MIT | 1 |
| https://github.com/phuryn/pm-skills | MIT | 72 |
| https://github.com/OthmanAdi/planning-with-files | MIT | 18 |
| https://github.com/vercel/ai | Apache-2.0 | 15 |
| https://github.com/Kilo-Org/kilocode | MIT | 17 |
| https://github.com/JimLiu/baoyu-skills | MIT | 23 |
| https://github.com/promptfoo/promptfoo | MIT | 18 |
| https://github.com/NVIDIA/SkillSpector | Apache-2.0 | 34 |
| https://github.com/earthtojake/text-to-cad | MIT | 9 |
| https://github.com/titanwings/distilly | MIT | 1 |
| https://github.com/mozilla-ai/llamafile | Apache-2.0 | 1 |
| https://github.com/milind-soni/OpenMausBot | Apache-2.0 | 9 |
| https://github.com/EveryInc/compound-engineering-plugin | MIT | 49 |
| https://github.com/browserbase/stagehand | MIT | 2 |
| https://github.com/shap/shap | MIT | 1 |
| https://github.com/vercel-labs/agent-desktop | Apache-2.0 | 8 |
| https://github.com/walkinglabs/learn-harness-engineering | MIT | 2 |
| https://github.com/activepieces/activepieces | MIT | 16 |
| https://github.com/pascalorg/editor | MIT | 5 |
| https://github.com/toon-format/toon | MIT | 1 |
| https://github.com/nocobase/nocobase | Apache-2.0 | 52 |
| https://github.com/modelcontextprotocol/python-sdk | MIT | 1 |
| https://github.com/slopus/happy | MIT | 9 |
| https://github.com/getpaseo/paseo | Apache-2.0 | 9 |
| https://github.com/google/skills | Apache-2.0 | 226 |
| https://github.com/PrefectHQ/prefect | Apache-2.0 | 4 |
| https://github.com/lexmount/moli | Apache-2.0 | 3 |
| https://github.com/coleam00/Archon | MIT | 7 |
| https://github.com/SuperClaude-Org/SuperClaude_Framework | MIT | 9 |
| https://github.com/citrolabs/ego-lite | MIT | 4 |
| https://github.com/marimo-team/marimo | Apache-2.0 | 2 |
| https://github.com/Skyvern-AI/skyvern | AGPL-3.0 | 6 |
| https://github.com/comet-ml/opik | Apache-2.0 | 20 |
| https://github.com/czlonkowski/n8n-mcp | MIT | 15 |
| https://github.com/wavetermdev/waveterm | Apache-2.0 | 8 |
| https://github.com/KKKKhazix/khazix-skills | MIT | 6 |
| https://github.com/HBAI-Ltd/Toonflow-app | MIT | 5 |
| https://github.com/google/adk-python | Apache-2.0 | 21 |
| https://github.com/latent-spaces/brag | MIT | 2 |
| https://github.com/1jehuang/jcode | MIT | 1 |
| https://github.com/Vincentwei1021/video-shotcraft | Apache-2.0 | 1 |
| https://github.com/huggingface/peft | Apache-2.0 | 1 |
| https://github.com/ai-openshell/openshell | Apache-2.0 | 31 |
| https://github.com/google/elephant-goldfish-model | Apache-2.0 | 8 |
| https://github.com/datalab-to/surya | Apache-2.0 | 1 |
| https://github.com/pydantic/pydantic-ai | MIT | 27 |
| https://github.com/ag-ui-protocol/ag-ui | MIT | 23 |
| https://github.com/voyager-crew/voyager | AGPL-3.0 | 9 |
| https://github.com/dataelement/dsh-desktop | MIT | 9 |
| https://github.com/teng-lin/notebooklm-py | MIT | 1 |
| https://github.com/eosphoros-ai/DB-GPT | MIT | 67 |
| https://github.com/rocketride-org/rocketride-server | MIT | 5 |
| https://github.com/agent0ai/agent-zero | MIT | 25 |
| https://github.com/confident-ai/deepeval | Apache-2.0 | 6 |
| https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep | MIT | 197 |
| https://github.com/heydamir/unslop | CC-BY-4.0 | 1 |
| https://github.com/ccusage/ccusage | MIT | 19 |
| https://github.com/xerj-org/xerj | Apache-2.0 | 5 |
| https://github.com/browser-use/browser-harness | MIT | 3 |
| https://github.com/microsoft/SkillOpt | MIT | 13 |
| https://github.com/langbot-app/LangBot | Apache-2.0 | 9 |
| https://github.com/ahmedkhaleel2004/gitdiagram | MIT | 2 |
| https://github.com/microsoft/agent-lightning | MIT | 2 |
| https://github.com/greensock/gsap-skills | MIT | 8 |
| https://github.com/NVIDIA-NeMo/Speech | Apache-2.0 | 11 |
| https://github.com/windmill-labs/windmill | Apache-2.0 | 70 |
| https://github.com/GoogleCloudPlatform/generative-ai | Apache-2.0 | 10 |
| https://github.com/microsoft/data-formulator | MIT | 7 |
| https://github.com/googleapis/mcp-toolbox | Apache-2.0 | 6 |
| https://github.com/triggerdotdev/trigger.dev | Apache-2.0 | 16 |
| https://github.com/ace-step/ACE-Step-1.5 | MIT | 6 |
| https://github.com/modelcontextprotocol/typescript-sdk | Apache-2.0 | 7 |
| https://github.com/trycompai/crm | MIT | 36 |
| https://github.com/zubair-trabzada/geo-seo-claude | MIT | 16 |
| https://github.com/mcp-use/mcp-use | MIT | 9 |
| https://github.com/baptisteArno/typebot.io | Apache-2.0 | 4 |
| https://github.com/Lightricks/LTX-2 | Apache-2.0 | 1 |
| https://github.com/awslabs/mcp | Apache-2.0 | 8 |
| https://github.com/LearningCircuit/local-deep-research | MIT | 1 |
| https://github.com/AI4Finance-Foundation/FinRobot | Apache-2.0 | 60 |
| https://github.com/TheCraigHewitt/seomachine | MIT | 26 |
| https://github.com/Zipstack/unstract | AGPL-3.0 | 4 |
| https://github.com/kaomei/stickman-video-director | MIT | 1 |
| https://github.com/ScrapeCreators/social-media-research-skills | MIT | 13 |
| https://github.com/Anil-matcha/AI-Youtube-Shorts-Generator | MIT | 1 |
| https://github.com/melgarafael/DeskcommCRM | MIT | 22 |

## Danh sách repo gốc chỉ ghi link (không lấy file)

Xem [THAM-KHAO.md](THAM-KHAO.md).