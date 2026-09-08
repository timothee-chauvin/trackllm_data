# TrackLLM data

Raw monitoring data for [TrackLLM](https://www.trackllm.net), collected and pushed
by the CI workflows of
[trackllm_website](https://github.com/timothee-chauvin/trackllm_website) —
see that repo for the pipeline, the site, and the methodology.

- `lt/` — collected logprob responses, per endpoint/prompt/month
- `b3it/` — border-input state, phase-1/2 samples, prevalence scans
- `spend/` — per-endpoint spend ledgers (monthly jsonl)

Append-only; the commit history is the record of when each observation landed.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE`). Please
attribute as "TrackLLM (Inria), https://www.trackllm.net".
