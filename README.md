
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<h1 align="center">Hi 👋, I'm Euclides <img height="40" src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Animated-Flag-Colombia.gif"></h1>

<!--About Me-->

## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 30px></picture> About me

<picture> <img align="right" src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width = 300px></picture>

- :school: I am a `Junior` at [School of Cyber Science and Technology](https://cst.buaa.edu.cn/) in [BUAA](https://ev.buaa.edu.cn/)
- :trophy: `2022 MCM/ICM` Finalist **&** 4x `Scholarship`
- :technologist: **Currently working on** `Frontend Development` **&** `Data Science`
- :boom: You can visit [MY WEBSITE](https://eliochiu.github.io) for some frontend knowledge
- :email: Feel free to **reach me out** [![Send me Email](https://img.shields.io/static/v1?label=email&amp;message=ElioChiu&amp;color=EA4335&amp;style=flat-square)](mailto:eliochiu2@gmail.com)
- :nerd_face: Always believe `"You are what you loved"`

<br>
<br>
<br>

```TypeScript
 private _darkModeIsSelect = new BehaviorSubject<boolean>(false);
  darkModeIsSelect :Observable<boolean> =  this._darkModeIsSelect.asObservable()

  constructor( @Inject(DOCUMENT) private document: Document) { }

   selecDarkMode(): { isActive: boolean, modeText: string } {
    const isActive = !this._darkModeIsSelect.value;
    if (isActive) {
      this.document.body.classList.add('vela__blue');
      this._darkModeIsSelect.next(true);
      return { isActive: true, modeText: 'Light' };
    } else {
      this.document.body.classList.remove('vela__blue');
      this._darkModeIsSelect.next(false);
      return { isActive: false, modeText: 'Dark' };
    }
  }
```

## <picture> <img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/Statistics.gif?raw=true" width = 30px>  </picture> Github Stats

<!--- stats & Trophy (start) -->

<p align="left">
  <!--- stats (start) -->
<table align="left">
<tr border="none">
<td width="50%" align="center">
  <img  align="left"  src="https://github-readme-stats.vercel.app/api?username=euclidesseg&theme=dark&show_icons=true&count_private=true" />
  <br></br>
  <img  title="🔥 Get streak stats for your profile at git.io/streak-stats" alt="Mark streak" src="https://github-readme-streak-stats.herokuapp.com/?user=euclidesseg&theme=dark&hide_border=false" /> 
</td>


<td width="50%" align="center">

  <img  align="center"  src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=euclidesseg&theme=dark&hide_border=false&no-bg=true&no-frame=true&langs_count=7"/>

  </td>
</tr>
</table>
<!--- stats (end) -->

<!--- trophy (start) -->

<div align=left>
  <a href="https://github.com/ryo-ma/github-profile-trophy" title="Go to Source">
      <img align="center" width=84% src="https://github-profile-trophy.vercel.app/?username=ElioChiu&theme=radical&row=1&column=7&margin-h=15&margin-w=5&no-bg=true" alt="TROPHY" />
    </a>
</div>

<!--- trophy (start) -->
</p>        
<!--- stats (end) -->

<br>

<!--profile visit count-->

<div align="center">


[![](https://visitcount.itsvg.in/api?id=ElioChiu&label=Profile%20Views&color=1&pretty=false)](https://visitcount.itsvg.in)

</div>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
