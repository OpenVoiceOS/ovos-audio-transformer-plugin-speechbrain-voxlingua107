# SpeechBrain Lang detect

spoken language detector for ovos

models:
- [speechbrain/lang-id-commonlanguage_ecapa](https://huggingface.co/speechbrain/lang-id-commonlanguage_ecapa)
- [speechbrain/lang-id-voxlingua107-ecapa](https://huggingface.co/speechbrain/lang-id-voxlingua107-ecapa)

```javascript
"listener": {
    "audio_transformers": {
        "ovos-audio-transformer-plugin-speechbrain-langdetect": {
            "model": "speechbrain/lang-id-langdetect-ecapa"
        }
    }
}
```