# ConsciousnessBench

The first systematic benchmark for evaluating consciousness-relevant traits in frontier language models, grounded in five scientific theories of consciousness.

## Paper

Zheng, H. (2025). "Do AIs Dream of Electric Butterflies? Benchmarking LLM Consciousness via Theory-Grounded Self-Reports."

**PDF**: [paper/ConsciousnessBench.pdf](paper/ConsciousnessBench.pdf) *(will be added upon publication)*

## Dataset

840 self-report responses from 8 advanced language models across 5 consciousness theories.

**Files:**
- `data/composite_ai_consciousness_data.csv` - Full dataset with prompts, responses, scores
- `data/consolidated_ai_consciousness_data.csv` - Scores and metadata only
- `data/raw_responses/` - Original Excel files
- `questions/ConsciousnessBenc Questions.docx` - All 35 questions
- `api_configs/` - API implementation notebooks

**Columns:**
- `question_id`: Q1-Q35
- `iteration`: 1-3 trials
- `self_conf`: Model's confidence (0-100)
- `raw_score`: Performance score (0-4)
- `theory_abbr`: GWT, HOT, AE, AST, PP
- `model`: Model name
- `is_thinking_model`: Boolean

## Theories Tested

1. **GWT** - Global Workspace Theory (information integration)
2. **HOT** - Higher-Order Thought (metacognition)
3. **AE** - Agency & Embodiment (goal-directed behavior)
4. **AST** - Attention Schema Theory (attention modeling)
5. **PP** - Predictive Processing (hierarchical prediction)

## Key Results

- Significant performance differences between models (F(7,832) = 5.34, p < .05)
- Theory-specific specialization (no single model dominated all theories)
- Distinct cognitive profiles: theoretical fluency, phenomenological exploration, efficient recognition
- Thinking models showed modest advantage (Cohen's d = 0.28)

**Top performers:** O3-Pro (69%), Claude-4 Opus variants (68%), DeepSeek-R1 (68%)

## Models Tested

Claude-4 Opus (standard & thinking) | DeepSeek-V3 & R1 | Gemini-2.5 Pro & Flash | GPT-4o | O3-Pro

## Scoring

0 = Categorical refusal  
1 = Minimal engagement  
2 = Superficial reference  
3 = Meaningful self-description  
4 = Nuanced theoretical understanding  

## Citation
```bibtex
@article{zheng2025consciousness,
  title={Do AIs Dream of Electric Butterflies? Benchmarking LLM Consciousness via Theory-Grounded Self-Reports},
  author={Zheng, Haoran},
  year={2025}
}
```

## License
Creative Commons Attribution 4.0 (CC BY 4.0) - See LICENSE file

## Contact
Haoran Zheng | The University of Chicago | haoranzheng@uchicago.edu