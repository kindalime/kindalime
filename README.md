<!-- Zero width character is used to put extra blank lines before and after code -->

<h3>
    
```python
​
from discord.ext import commands

class kindalime(commands.Cog):
    def __init__(self):
        super().__init__()
        self.username = "kindalime"
        self.name = "Daniel Kim"
        self.email = "danielynskim@gmail.com"
        self.linkedin = "linkedin.com/in/dk763"

    @commands.command(name="hello")
    def hello(self, ctx):
        message = """
            Hello! I am kindalime, currently a CS Major at Yale.
            I am interested in ML, data science, and software engineering.
            Currently, I am an ML Intern at Twitter, working with Cortex.
        """
        await ctx.send(message)

    @commands.command(name="techs")
    def techs(self, ctx):
        message = """
            ML/DS: TensorFlow, TFX, Keras, Pandas, Numpy
            Langs: Python, C++, R, C, Ruby on Rails
            Misc: Jupyter, AWS, Beam, Bash, Linux
        """
        await ctx.send(message)
​
```
</h3>