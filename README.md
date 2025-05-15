<!-- Minimalist Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7E3ACE&height=120&section=header&text=iRxngo&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=35" width="100%">
</div>

<!-- Profile Stats -->
<p align="center">
  <a href="https://github.com/iRxngo">
    <img src="https://github-widgetbox.vercel.app/api/profile?username=iRxngo&data=followers,repositories,stars,commits&theme=dark" alt="GitHub Profile"/>
  </a>
</p>

<!-- Discord Presence -->
<div align="center">
  <a href="https://discord.com/users/1240724655099219969">
    <img src="https://lanyard-profile-readme.vercel.app/api/1240724655099219969?theme=dark&animated=true&hideDiscrim=true&borderRadius=20px&idleMessage=Coding%20something%20brilliant...%20✨" alt="Discord Presence" />
  </a>
</div>

<!-- Clean Divider -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7E3ACE,100:0d1117&height=2&section=header" width="100%">
</div>

<!-- Technical Skills -->
<div align="center">
  <h3>Technologies & Tools</h3>
</div>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,html,css,discord,redis,mongodb,idea,git,github,vscode&perline=6" alt="Skills"/>
</p>

<!-- GitHub Stats -->
<div align="center">
  <h3>GitHub Stats</h3>
</div>

<p align="center">
  <img width="49%" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=iRxngo&count_private=true&show_icons=true&title_color=7E3ACE&text_color=c9d1d9&icon_color=7E3ACE&border_color=30363d&bg_color=0d1117" alt="GitHub Stats" />
  <img width="49%" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs?username=iRxngo&count_private=true&show_icons=true&title_color=7E3ACE&text_color=c9d1d9&icon_color=7E3ACE&border_color=30363d&bg_color=0d1117&layout=compact" alt="Top Languages" />
</p>

<p align="center">
  <a href="https://github.com/iRxngo">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=iRxngo&theme=dark&hide_border=true&background=0d1117&stroke=7E3ACE&ring=7E3ACE&fire=7E3ACE&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=7E3ACE&sideLabels=7E3ACE&dates=FFFFFF" width="450px">
  </a>
</p>

<!-- Developer Profile -->
<div align="center">
  <h3>Developer Profile</h3>
</div>

```python
# iRxngo.py - Developer Profile
class Developer:
    def __init__(self):
        self.name = "Ramin"
        self.alias = "iRxngo"
        self.title = "Full Stack Developer & Plugin Specialist"
        
        self.skills = {
            'languages': ["Python", "Java", "JavaScript"],
            'game_dev': ["Minecraft Plugins", "Spigot API"],
            'discord': ["Discord.py", "Bot Development"],
            'databases': ["MongoDB", "Redis"],
            'web': ["HTML", "CSS"],
            'tools': ["IntelliJ", "VS Code", "Git"]
        }
        
        self.projects = {
            'minecraft': "High-performance game plugins",
            'discord_bot': "Ranked BedWars with auto-scoring",
            'web': "Interactive dashboards"
        }
        
        self.current_focus = "Building scalable game systems"
        
    def introduce(self):
        print(f"👋 Hi! I'm {self.name}, aka {self.alias}")
        print(f"💻 {self.title}")
        print("🚀 Specializing in:")
        for category, skills in self.skills.items():
            print(f"  • {category.title()}: {', '.join(skills)}")
        print(f"\n🔥 Currently: {self.current_focus}")
        print("🌟 Let's create something amazing together!")

# Initialize profile
dev = Developer()
dev.introduce()
