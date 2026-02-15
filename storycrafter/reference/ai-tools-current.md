# AI Tools — Current State

> **Last updated:** 2026-02-15
> **Update this file regularly.** AI video/image tools evolve fast. Check monthly.

## Video Generation

### Sora (OpenAI)
- **Strengths:** Cinematic quality, physics understanding, complex scenes, camera movement
- **Duration:** Up to 60s
- **Resolution:** Up to 1080p
- **Weaknesses:** Character consistency across shots, hands, text rendering
- **Best for:** Cinematic shorts, establishing shots, atmospheric footage
- **Prompt style:** Descriptive, cinematic language. Responds well to camera direction.

### Kling (Kuaishou)
- **Strengths:** Motion quality, character animation, longer coherent clips
- **Duration:** Up to 2 minutes
- **Resolution:** Up to 1080p
- **Weaknesses:** Sometimes uncanny faces, less cinematic than Sora
- **Best for:** Character-driven scenes, dialogue-adjacent content, longer sequences
- **Prompt style:** Direct, action-oriented.

### Runway Gen-3/4
- **Strengths:** Style control, image-to-video, motion brush, fast iteration
- **Duration:** Up to 18s (Gen-3), extending
- **Resolution:** Up to 1080p
- **Weaknesses:** Shorter clips, less complex scene understanding
- **Best for:** Stylized content, music videos, image-to-motion, controlled animations
- **Prompt style:** Concise, style-focused. Works well with reference images.

### Pika
- **Strengths:** Quick iterations, style transfer, lip sync
- **Duration:** Up to 15s
- **Resolution:** Up to 1080p
- **Weaknesses:** Less cinematic, shorter duration
- **Best for:** Quick concepts, style experiments, social content
- **Prompt style:** Simple, direct.

### Veo (Google)
- **Strengths:** Long-form coherence, scene understanding
- **Duration:** Up to 2 minutes
- **Resolution:** Up to 4K
- **Weaknesses:** Less publicly available, style range
- **Best for:** Documentary-style, realistic scenes
- **Prompt style:** Detailed, naturalistic.

### Hailuo (MiniMax)
- **Strengths:** Fast generation, good motion, character consistency improving
- **Duration:** Up to 30s
- **Resolution:** Up to 1080p
- **Best for:** Quick iteration, social content, character pieces

## Image Generation

### Midjourney
- **Strengths:** Aesthetic quality, style control, consistent "look," character reference
- **Weaknesses:** Less photorealistic than Flux, prompt learning curve
- **Best for:** Concept art, mood boards, stylized visuals, character design
- **Prompt style:** Descriptive + style parameters (--ar, --style, --v)

### Flux (Black Forest Labs)
- **Strengths:** Photorealism, text rendering, prompt adherence, open-source options
- **Weaknesses:** Less stylized range than Midjourney
- **Best for:** Photorealistic content, text-in-image, product shots
- **Prompt style:** Direct, detailed.

### DALL-E 3/4 (OpenAI)
- **Strengths:** Prompt understanding, text rendering, integration with ChatGPT
- **Weaknesses:** Less aesthetic control than Midjourney
- **Best for:** Quick concepts, illustration, text-heavy images
- **Prompt style:** Natural language, detailed descriptions.

### Stable Diffusion (Stability AI)
- **Strengths:** Open-source, customizable, LoRA/fine-tuning, local running
- **Weaknesses:** Requires technical setup, base model less polished
- **Best for:** Custom styles, fine-tuned characters, batch generation, privacy
- **Prompt style:** Tag-based + negative prompts.

## Key Constraints for Story Planning

| Constraint | Impact on Story |
|-----------|----------------|
| Character consistency | Plan for visual tricks: same clothing, silhouette, avoid close-ups across many shots |
| Duration limits | Break story into modular scenes that can be stitched |
| Hands/faces | Avoid complex hand interactions; favor medium/wide shots |
| Text in video | Don't rely on AI-generated text — overlay in post |
| Dialogue | Lip sync is improving but unreliable. Plan for VO or dialogue-light stories |
| Style consistency | Lock visual direction early. Use reference images across all generations |
| Physics | Most tools struggle with complex physics. Keep it simple or embrace surrealism |

## Recommendation by Use Case

| Use Case | Primary Tool | Backup |
|----------|-------------|--------|
| Cinematic short | Sora | Kling |
| Music video | Runway | Sora |
| Social content (fast) | Pika / Hailuo | Runway |
| Documentary style | Veo | Sora |
| Concept art / mood board | Midjourney | Flux |
| Photorealistic stills | Flux | DALL-E |
| Custom character consistency | Stable Diffusion (LoRA) | Midjourney (cref) |
