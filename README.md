# CS336  Project
## 核心完成目标
- [ ] 微调模块（基于LoRA/QLoRA，复用后训练SFT代码）
- [ ] 对齐模块（DPO/GRPO，复用后训练对齐代码）
- [ ] 推理部署模块（量化+简易服务，复用后训练部署代码）

## 目录结构
├── core/                 # 项目核心代码
│   ├── finetune/        # 微调模块
│   ├── alignment/       # 对齐模块
│   └── inference/       # 推理部署模块
├── data/                # 项目数据
├── docs/                # 项目文档/报告
└── README.md
