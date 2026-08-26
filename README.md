# Who is the Agent to Blame?

### Localizing Faithfulness and Citation Mistakes in Agentic Deep Research

📄 **Paper:** [arXiv:2608.24306](https://arxiv.org/abs/2608.24306)

Accepted to **EMNLP 2026** (Main Conference).

---

## 🚧 Code coming soon

We are preparing the code and data for release.

---

## Abstract

Deep research (DR) systems produce long-form cited reports by orchestrating multiple agents that search and synthesize information from the web. Citations are the primary mechanism for evaluating the faithfulness of these reports, yet current DR systems exhibit poor citation recall. Moreover, improving citation recall is challenging because DR systems are complex multi-agent architectures where information passes through agents like a telephone game, and both content and citations can get corrupted along the way.

We propose an evaluation method that pinpoints which agent introduced each error by locally testing agent invocations for faithfulness and verifiability relative to their own inputs. Furthermore, we propose a four-type taxonomy to categorize the discovered errors: hallucination, uncited input reliance, uncited output, or insufficient citations.

Applying our method to three top-ranked open-source DR systems, we obtain actionable diagnostics. Almost every agent makes a lot of mistakes with the exception being those that summarize a single document. We find that the dominant error type varies systematically across agents, where the orchestrator mistakes are mostly citation-related. We find that 84.7% of final-report errors in AI-Q originate at the orchestrator, roughly 31% of them hallucinations and the rest citation mistakes. Guided by these insights, we demonstrate that two simple interventions raise citation recall by 5% without degrading output quality.

---

## Citation

If you find this work useful, please cite:

```bibtex
@misc{hirsch2026agentblamelocalizingfaithfulness,
      title={Who is the Agent to Blame? Localizing Faithfulness and Citation Mistakes in Agentic Deep Research},
      author={Eran Hirsch and David Wan and Han Wang and Elias Stengel-Eskin and Mohit Bansal and Ido Dagan},
      year={2026},
      eprint={2608.24306},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2608.24306},
}
```

*This entry will be updated to the official ACL Anthology reference once the
EMNLP 2026 proceedings are published.*
