+++
title = "Grand Challenges"
date = 2026-04-14
draft = false

[extra]
subtitle = "engineering for the community. yay!"
+++

My introduction to the Grand Challenges Program began with Antonio recruiting me. No explanation, he told me to just go to the meeting, feel it out and see if it's something that interests me.

(Shout out to Antonio!)

## hierarchy
Eight years ago I learned about Maslow’s Hierarchy of Needs [^1].

(or maybe it was closer to ten)

For a person to be fulfilled you need to fulfill some tenets bottom up: first come physiological needs, then safety, then belonging, then self-esteem, and at the apex self-actualization.

I wondered at the time whether this framework still held up when you tried to scale it up. Not for a person, but for a group, a community, or  even something as large and abstract as “society”. It felt like it should translate. But I’m not sure if it does cleanly.

When we talk about solving large problems, we often start with solutions before defining what exactly we’re trying to solve [^2]. Scope becomes an afterthought, when it probably should be the starting point.

Because to solve a problem effectively, you need to understand its boundaries first. And in order to address humanities problems from a bottom-up approach you need to zoom out of that scope, and holistically understand what it is humanity needs.

And that turns out to be much harder than it sounds. Still, it feels like we can make a few rough assumptions.

If you tried to map individual needs to something like societal needs, you might end up with something like:
```python
# individual needs : humanities' needs
mapping = {
  "physiological": "sustainable prosperity",
  "safety": "security",
  "belonging": "an enriching life",
  "esteem": "health",
  "self_actualization": "prosperity"
}
```

…or, if you follow the graphic from USC Viterbi’s Grand Challenges Program [^3], you end up somewhere in the same direction.

![Maslow Hierarchy of Needs to Humanity](/images/hierarchy-of-humanity.png)

Now we have a top-level understanding of this, what to do with that is less obvious. It only became clearer later.

## challenges

Three years ago, Antonio walked me and Ronald to the Grand Challenges Program seminar in Guerry Hall. They told me that there was an organization on campus that empowers engineers to work towards solving a problem that humanities have. 

You pick a subdiscipline, spearhead activities that fall under that umbrella, and eventually in the end work on your thesis that directly tackle the problem you chose. Beyond that it also encourages you to become a well-rounded engineer and have a people-oriented mindset with design. In order to even attempt to contribute in solving humanity's problems, you have to look beyond your bubble. Get outside of your comfort zone and see what's out there.

![Grand Challenges Competencies](/images/competencies.png)

Those are the competencies that help you become well-rounded.

That's exactly the thesis of this program - get out there, work with other interdisciplinary, and create something that enriches anything in the hierarchy of humanity. Because with the intent of serving people and meeting those needs, you are sure to contribute in solving one of our grand challenges.

## growth
I treated the program like an MMORPG[^4]. As far as I knew I had five buckets I had to max out.

What did I choose to do? Pick the one where I know I’d struggle with the most: the Business Competency

### SMILEFund (Business Competency):
I went to the business career fair, which was mostly a field of quarter-zips and khakis, and wandered between booths, marketing, consulting, investment firms, without really knowing what I was looking for.
One of them mentioned they ran a student-managed fund. About a million dollars. That was enough to get my attention.
They were a bottom up fund AKA you find a stock and work your way up to the macroeconomic landscape. Or more simply: find a stock, research it, decide whether to buy. Rinse and repeat.
They told me to apply.
So I did[^5].

I ended up in the Bloomberg lab, which felt like being dropped into a completely different language. EBITDA. Bonds. Discount rates. I remember realizing pretty quickly that I didn’t actually understand how most of this worked.

But the whole point of the program was for you to drink from a fire house - either you sink and soak everything up like a sponge or you sink (ask for help!)

Over time, things started to make more sense. My weeks became some combination of building Excel models, DCF, revenue projections, and then trying to make sense of it all in dashboards. A lot of trial and error.

I also started working more with other analysts. Reviewing models, helping onboard new people. At some point that turned into a pretty large group, 40+ analysts across the tech sector, which mostly meant I had to get better at explaining things clearly, not just getting them right. 

One of the more surreal moments was presenting in New York at the GAME Forum, listening to people who actually do this for a living talk about the market. 

Anyways, look at me at the New York Stock Exchange.

![SMILE Fund NYSE](/images/nyse.png)

### Hackathons (Social Consciousness)

Hackathons were where this people-first idea stopped being theoretical for me. You show up with a team, a short clock, and a real-world problem, then try to ship something that actually helps someone before the weekend ends.

What I liked most was that they force you out of your comfort zone. You can’t hide in your favorite technical niche for long, because the good projects start with community pain points first, then use software as the tool, not the goal.

I joined a couple of them. In one, Major and I built a financial tracker/helper for lower socioeconomic households so families could have a practical guide for budgeting, expenses, and day-to-day financial decisions.

Another project we built was Dispatch: FieldReady.

![Emory Hackathon Team](/images/emory-hackathon.jpeg)

We wanted to translate the theoretical knowledge EMTs gain from training training modules and give them a simulated experience, so that by the time they get to the field they are "FieldReady". We talked to some of the EMT professionals that Zachary knew, alongside his own experiences as being an EMT for a short while and we compiled a list of features to build. 

From the compiled list of features we eventually narrowed it down to four. FieldReady includes a Patient Simulation with AI patient/dispatcher interactions and realistic vitals, plus a Response Area Quiz with interactive maps to drill building and address recognition. It also has Flashcards for protocols, meds, dosages, contraindications, and vital ranges, and a Radio Simulation module in progress for practicing dispatch communication workflows.

All in all, going to these experiences helped me to listen for community problems, and make a tangible solution in the end.

### Oak Ridge (Multidisciplinary)

My first internship was at Oak Ridge National Laboratory, and it dropped me into interdisciplinary work fast. I had never really done physics research before, so I felt out of my depth at first, but that was kind of the point: get uncomfortable, learn quickly, and contribute anyway.

The project was about using machine learning to identify superconducting pairing symmetries from QPI patterns. The motivation was simple: automate detection of superconducting properties, catch patterns traditional approaches might miss, and give experimentalists a more reliable way to find new materials.

Our pipeline looked like this: build a Bogoliubov-de-Gennes Hamiltonian for s-wave vs chiral d-wave systems, randomize parameters (pairing strength, chemistry, impurity potential), generate QPI spectra with Fourier transforms, then feed that into a CNN (four convolutional layers plus dense layers, trained with Adam). The model separated s-wave from chiral d-wave with 97-100% accuracy, which was wild to see in practice.

Most of the researchers I worked with were international, so I had to learn how to collaborate across different communication styles and cultural norms. That ended up being one of the best parts, because I learned way more than just research; I learned how other people think, explain, and solve problems.

That whole experience showed me you do not need to know everything up front to build something meaningful. If you bring your skills honestly, learn from people around you, and combine strengths, you can make something better than what any one person would have done alone.

It was also the first time I presented this kind of work in front of a crowd. Nerve-racking at first, but it gave me confidence to explain what I built, defend the choices behind it, and actually be proud of showing my work.

![Oak Ridge Presentation](/images/oakride-presentation.jpg)


### Thesis

For my Grand Challenges thesis, I wanted to contribute something practical: a tool that helps more people do real data analysis without needing to be experts from day one.

That project became Datapeer, a web app for exploratory data analysis where you can upload messy CSVs, ask questions, and iterate in one workflow. Instead of treating LLMs like magic answer machines, I designed it more like an instrument: generate code, run it in a sandbox, show outputs, then explain results.

The core idea was transparency. If something fails, you see it; if something works, you can trace how it got there. That made the system feel more aligned with how scientific discovery should work, auditable, repeatable, and open to critique, while still lowering the barrier for people who are just getting started.

Link to those who want to read it:

[DataPeer thesis (UTC Scholar)](https://scholar.utc.edu/honors-theses/662/)


## Grand Challenges Conference in Rome

I had the opportunity to travel to Rome for the Grand Challenges Program at Sapienza University, and it honestly felt surreal at first.

We learned a lot about the history of Rome while we were there, from the Colosseum to the forums, and seeing all of that in person made everything feel less like a textbook and more like something alive.

More than anything, I got to experience another culture and its norms up close. One thing that stuck with me was how people took their time with things, and that was the complete opposite of the rush-everything productivity culture I was used to in the United States.

I came back home feeling refreshed. Slowing down and actually soaking in what was around me made me more productive in a better way, because I started prioritizing meaningful work instead of just busy work.

I also got to know my peers in a completely different light. Before this trip I did not know everyone that well, but sharing meals, walking around together, and collecting memories made us much closer.

![Italy Group Photo](/images/italy-group.jpg)

Also, I was the first person from the University of Tennessee documented to brush their teeth in Rieti, and that itself is an accomplishment [^6]

![Rieti Brushing Teeth](/images/rieti-brushing-teeth.jpg)

The end product of all this was something I am genuinely proud of. It felt like an ending, but also the beginning of a new journey.

I proved to myself that I can improve, adapt, and build things I once thought were out of reach. At the same time, it marked the end of my Grand Challenges curriculum at school, which is bittersweet.

---

[^1]: here’s the hierarchy of needs (i wonder what you feel like you could work on): [https://www.simplypsychology.org/maslow.html](https://www.simplypsychology.org/maslow.html)
[^2]: classic pitfall, bozo, define your scope first. Sustainable Development Goals: a framework for peace and prosperity for people and the planet. There’s 17 interesting challenges laid out by them, check it out: [https://sdgs.un.org/goals](https://sdgs.un.org/goals)
[^3]: see the similarities!?: [https://viterbischool.usc.edu/vision2026/](https://viterbischool.usc.edu/vision2026/)
[^4]: Massively Multiplayer Online Role-Play Game: basically a game where thousands of players play and go on adventures, level up, and get stronger (:
[^5]: throw a cs major in a bunch of business majors: what do you get? one burnout away from Series A.
[^6]: This will be a banger photo for the moms in facebook.