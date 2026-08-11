<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00599C,100:6A11CB&height=200&section=header&text=Hi%20There%2C%20I%27m%20Pranaya&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Computer%20Engineering%20Student%20%40%20Kathmandu%20University&descAlignY=55&descSize=18&descColor=ffffff" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=00599C&center=true&vCenter=true&width=650&lines=Computer+Engineering+Student;Building+Software+That+Solves+Real+Problems;Interested+in+NLP+%26+Applied+Machine+Learning;Currently+Building+SignBridge%2C+a+Real-Time+ASL+Platform;Open+to+Internships+%26+Software+Engineering+Roles" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=Pranaya-sht&label=Profile%20Views&color=00599C&style=flat-square" alt="Profile views"/>
<img src="https://img.shields.io/github/followers/Pranaya-sht?style=flat-square&color=00599C&label=Followers" alt="GitHub followers"/>
<img src="https://img.shields.io/badge/Computer_Engineering-Kathmandu_University-00599C?style=flat-square" alt="Kathmandu University"/>
<img src="https://img.shields.io/badge/Location-Nepal-red?style=flat-square" alt="Nepal"/>
<img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat-square" alt="Open to Work"/>

</div>

<br/>

## About Me

I'm an undergraduate Computer Engineering student at Kathmandu University, Nepal. I focus on software engineering, with a growing interest in applying machine learning and NLP to build things people can actually use.

```yaml
pranaya:
  education: B.E. Computer Engineering, Kathmandu University
  interests: [Web Development, NLP, Deep Learning]
  currently_building: SignBridge - a real-time ASL translation platform
  open_to: [Software Engineering Roles, Internships, Open Source Collaboration]
```

<br/>

## What I'm Looking For

<table>
<tr>
<td width="33%" align="center"><b>Internships & Entry-Level Roles</b><br/><sub>Software Engineering / Full-Stack Development</sub></td>
<td width="33%" align="center"><b>AI / NLP-Focused Work</b><br/><sub>Applied ML, chatbots, conversational systems</sub></td>
<td width="33%" align="center"><b>Remote or Nepal-Based</b><br/><sub>Open to relocation for the right opportunity</sub></td>
</tr>
</table>

<br/>

## Featured Project

### SignBridge — Real-Time ASL Translation Platform
<sub>placeholder name — swap in your actual repo name and link once it's public</sub>

This platform bridges the communication gap between written/spoken English and American Sign Language. It combines a hybrid deep learning model for real-time webcam gesture translation, a rule-based English-to-ASL grammar glosser, and a Next.js 15 dashboard with gamified learning, custom quizzes, and analytics.

<p>
<img src="https://img.shields.io/badge/Next.js%2015-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js 15"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/MediaPipe-00A98F?style=flat-square" alt="MediaPipe"/>
<img src="https://img.shields.io/badge/NLTK-306998?style=flat-square" alt="NLTK"/>
<img src="https://img.shields.io/badge/React_Flow-FF0072?style=flat-square&logo=react&logoColor=white" alt="ReactFlow"/>
</p>

**[View Repository →](https://github.com/Pranaya-sht/SignBridge)**

**Key Features**

**1. Real-Time ASL Video Translation**
- Landmark Tracking — tracks user movement using MediaPipe Holistic (11 pose points, 21 left-hand points, 21 right-hand points).
- Deep Learning Engine — translates 30-frame sequence streams into dynamic word classifications using a hybrid Conv1D + BiLSTM + Multi-Head Self-Attention model.
- Performance Optimization — applies feature scaling and normalization based on training-set IQR and medians for resilient, low-latency predictions.

**2. English-to-ASL Text Glossing**
- ASL Grammar Engine — restructures written English into standard ASL syntax order (TIME – TOPIC – COMMENT – WH).
- NLP Pipeline — uses NLTK tokenizers and lemmatizers to resolve contractions, handle spatial index mapping (this, that), replace pronouns, and isolate instrumental phrases.
- Video Playback — maps parsed tokens onto the WLASL dataset's video clips, rendering translations as a continuous sequence.

**3. Gamified Study Sandbox**
- Dynamic Flashcards — dual-sided cards (word on front, ASL demo video on back) with bookmarking, learned flags, and feedback.
- Adaptive Quizzes — a 10-level progressive quiz system with randomly generated video-based distractors.
- Daily Practice & Scheduler — generates 5 adaptive daily cards based on current level, tracks consistency, and supports custom study reminders.

**4. Analytics & Progress Visualization**
- Interactive Skill Trees — ReactFlow graphs mapping levels and concept tags.
- Skill Radar — radar chart across Knowledge, Practice, Accuracy, Satisfaction, Quizzes, Completion, and Engagement.
- Consistency Heatmap — visualizes daily activity over a 30-day period.

**Technical Architecture**

```
  [ USER TEXT INPUT ]                    [ WEBCAM INPUT FRAME ]
          │                                        │
          ▼                                        ▼
   ( NLTK POS Tagger )                    ( MediaPipe Holistic )
          │                                        │
   ( Lemmatizer (WordNet) )                        ▼
          │                            [ Extract Core Keypoints ]
   ( ASL Grammar Resolver )               • 11 Pose Coordinates
   - Time-Topic-Comment-Wh                • 21 Left Hand Coordinates
          │                               • 21 Right Hand Coordinates
          ▼                                        │
   [ Mapping Dictionary ]                          ▼
   - WLASL Video Database                 [ Robust Scaling (IQR) ]
          │                                        │
          ▼                                        ▼
 ┌──────────────────┐                     [ Hybrid Deep Network ]
 │ Next.js Sequence │                     • Conv1D Pathway
 │   Video Player   │                     • Bi-LSTM Sequential Pathway
 └──────────────────┘                     • Multi-Head Self-Attention
                                                   │
                                                   ▼
                                          [ Softmax Classification ]
```

<br/>

## Skills

<sub>self-rated — adjust the percentages to match your own level</sub>

![Python](https://progress-bar.dev/85/?title=Python&width=400&color=00599C)
![JavaScript](https://progress-bar.dev/75/?title=JavaScript&width=400&color=00599C)
![React%20%2F%20Next.js](https://progress-bar.dev/70/?title=React+%2F+Next.js&width=400&color=00599C)
![C%2B%2B](https://progress-bar.dev/65/?title=C%2B%2B&width=400&color=00599C)
![NLP%20%2F%20Deep%20Learning](https://progress-bar.dev/70/?title=NLP+%2F+Deep+Learning&width=400&color=00599C)
![SQL](https://progress-bar.dev/60/?title=SQL&width=400&color=00599C)

<div align="center">
<img src="https://skillicons.dev/icons?i=python,js,cpp,c,html,css,react,nodejs,mysql,git,github,vscode" alt="Tech stack icons"/>
</div>

<br/>

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Pranaya-sht&show_icons=true&theme=default&hide_border=true&title_color=00599C&icon_color=00599C&text_color=333&count_private=true" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pranaya-sht&layout=compact&theme=default&hide_border=true&title_color=00599C&text_color=333" alt="Top Languages" width="38%"/>

<img src="https://github-profile-trophy.vercel.app/?username=Pranaya-sht&theme=flat&no-frame=true&column=6&margin-w=8&margin-h=8" alt="GitHub Trophies"/>

</div>

<br/>

## Contact

<div align="center">

<a href="mailto:your.email@example.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://linkedin.com/in/your-linkedin-handle">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://your-portfolio-link.com">
  <img src="https://img.shields.io/badge/Portfolio-00599C?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
</a>
<a href="https://github.com/Pranaya-sht">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<br/><br/>

*Feel free to reach out — always happy to talk about software, NLP, or potential opportunities.*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6A11CB,100:00599C&height=100&section=footer" width="100%"/>
