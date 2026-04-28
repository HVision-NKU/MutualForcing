# MutualForcing: Dual-Mode Self-Evolution for Fast Autoregressive Audio-Video Character Generation



## 🎥 Video Demo

<div align="center">
  <video src="https://github.com/user-attachments/assets/03701c83-0801-4a44-95ea-45240caff8b0"
         width="70%" controls playsinline preload="metadata"></video>
  <p><em>Please turn on the sound to hear the audio. MutualForcing 1min30s Video Demo (The video was heavily compressed due to GitHub's 10 MB upload file size limit.)</em></p>
</div>


## ✨ Highlights

- **Fast auto-regressive audio-video joint generation** with only **4–8 inference steps**
- Supports **streaming generation** and **long-duration audio-video synchronization**
- A **two-stage training strategy** for stable multimodal optimization
- A unified **dual-mode self-evolution framework** for few-step and multi-step generation
- No need for an extra **bidirectional teacher model**
- Lower memory cost and more flexible training on long sequences
- Matches or outperforms prior methods that require **50 steps**

<img width="855" height="305" alt="teaser" src="https://github.com/user-attachments/assets/b6076942-ee10-4e5d-a150-5fba2318b54b" />

## 📚 Table of Contents

- [🎬 Multi-Domain Generalization Result]
  - [🎤 Singing]
  - [🎼 BGM Music]
  - [🗣️ Multi-Person Speaking]
  - [🐾 Animal & 🍽️ Eating]
  - [1min Long Video Generation]
- [📌 Open-source TODO]



## 🎬 Multi-Domain Generalization Result


---

### 🎤 Singing

| | | |
|---|---|---|
| <video src="https://github.com/user-attachments/assets/91ad06ef-4a4a-4e7d-8cd5-259fde2c162d" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/2f316ed7-a568-44c6-8e59-c5d171337c7a" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/520a18e3-2de6-434a-82d5-23a230ac5a90" controls width="260"></video> |
|"Blonde young woman wearing gold earrings and necklace, sits at white piano, singing into microphone; eyes sometimes closed, sometimes looking slightly forward; warm indoor background, mid-close low-angle shot. Clear female voice with soft piano, lyrics: 'said his mind was made up, but we both know that he lies', gentle slightly sad emotion." | Dark-brown long-haired woman in black sheer-sleeve top sings at microphone, eyes slightly to right, dark stage background; static mid-close shot. Clear female voice singing, lyrics: '...found me back home', focus on vocal performance. | Southeast Asian elderly man, bare-chested, plays bamboo flute on porch, cheeks puffed, fingers moving skillfully, body slightly swaying with rhythm; ultra-wide fisheye shot slowly moving right and panning left. Calm and evolving flute solo melody. |

---

## 🎼 BGM Music

| | | |
|---|---|---|
| <video src="https://github.com/user-attachments/assets/7a31c3a1-1aba-4c66-9917-57916a93cce6" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/8e0f84fc-7a10-4dd5-8a3b-b84a2166989b" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/9fb65ea9-2d79-42cb-a89c-239ac6cb496b" controls width="260"></video> |
| Brown long-curled-haired woman in red top, wearing a straw hat, staring at the camera by the seaside, head slightly tilted, hair blown by wind, waves behind; camera slowly moves right and pans left. Background music: female pop singing, lyrics include 'oh why, oh why' and 'feeling drunk and high, so high, so high...', creating a pensive atmosphere. | Short-haired woman in gray fluffy coat walking in a park, looking thoughtful; camera slowly pans left tracking, composition shifts from right-heavy to left-heavy. Background music: slow melancholic cello, creating a calm and sad atmosphere. | Blonde woman in pink short sleeve, hair blown by wind, slowly turns head and upper body from right to front, looking alert; camera slowly moves back, composition shifts from right-heavy to center. Background music: tense suspenseful, with clear wind sounds. |

---

## 🗣️ Multi-Person Speaking

| | | |
|---|---|---|
| <video src="https://github.com/user-attachments/assets/7b2a1828-55eb-4913-a224-9d2d4c43897c" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/8c2b72d0-7c81-4840-bc30-c38df92e2528" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/0a848a04-6c9b-4b47-bfc1-face7db9d726" controls width="260"></video> |
| Two men in camouflage in mossy forest; foreground man talks to camera selfie-style holding rifle, background man wearing full-face mask uses binoculars; mostly static shot. Low-voice English dialogue: 'Ah. I think Claire or something on the other side of the river. So if we get up onto this knoll just in front of us, we might...', tense restrained atmosphere | Glasses-wearing braided schoolgirl and boy in suit uniform sit on beige sofa; girl turns to talk to boy, ornate living room background, static mid-shot bright lighting. Light English conversation: Girl: 'Oh, Brighton, do you have a date for the seventh-grade dance? Yeah' Boy: 'I got a couple of irons in the fire, put out a few feelers.'; youthful relaxed atmosphere. | Bald gray-bearded man knitting, white-haired woman holding folder and pen sitting on brown leather sofa in living room with Christmas tree; static mid-shot, warm indoor light. Calm English dialogue: Male: 'Let me and your mom handle it.' Female: 'I didn't realize we'd come'; quiet homely atmosphere. |

---

## 🐾 Animal & 🍽️ Eating

| | |
|---|---|
| <video src="https://github.com/user-attachments/assets/15995bd6-9685-4669-a7df-1b479f8fa863" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/0abba59e-4b5a-4ae1-84be-beba6bf5a980" controls width="260"></video> |
---


## 1min Long Video Generation

| | | |
|---|---|---|
| <video src="https://github.com/user-attachments/assets/4f1bb17e-dd43-4336-9631-87c71749eea1" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/36d75d80-230e-4b67-8553-0059c7718c0d" controls width="260"></video> | <video src="https://github.com/user-attachments/assets/c6fc6ee2-1c8e-4716-9e3e-6cbaafff1e25" controls width="260"></video> |



## 📌 Open-source TODO

- [x] Project page
- [x] Paper release
- [ ] Inference code
- [ ] Training code
- [ ] Checkpoints
- [ ] Data preprocessing pipeline
- [ ] Evaluation scripts
- [ ] Streaming generation support
- [ ] Long-duration generation examples
- [ ] Reproducibility instructions
- [ ] Hugging Face / demo integration
- [ ] Full documentation
