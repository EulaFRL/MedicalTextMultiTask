# MedicalTextMultiTask
针对医疗建议生成，对 LLaMA3-8B 和 LLaMA-Med 进行监督微调和人类偏好对齐。
微调期间：
- 对比 LoRA，QLoRA，和 Adapter
- 对比 Linear vs Cosine Scheduler
使用 DPO 实现人类偏好对齐