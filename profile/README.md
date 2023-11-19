# BeppoFresh by LasagnaTUM

## Inspiration

Food is awesome! Do we need to say more?
Cooking and eating together is a key element of forming friendships and transporting cultural knowledge; trying new things out should be fun. On the other hand everybody has a taste and sometimes also allergens to be considered.
So it is a really interesting challenge to find a balance between those aspects by building an interactive recommender system.

## What it does

HelloFresh allows you to flexibly select the meals or just rely on the preselection.
But both ways are not optimal; you have your preferences but all these possibilities also lead to cognitive load; the famous paradox of choice.
We offer a flexible and gamified solution to tackle that problem; no boring extra filter menus. Just give feedback directly on the recipes page and build your recommender system passively, while exploring all these delicious meals.
You are supported by your personal culinary assistant, Beppo. Whenever you see Beppo, the little lemon chef, you know that he incorporates your feedback into the recommendations.
We offer recommendation improvements:
- In the recipe list - just choose what you like more
- In the recipe details - click on ingredients or tags to select whether you want to see more of them

## How we built it
Frontend: React (Typescript)
Backend: FastAPI (Python) + MongoDB
Deployment on render.com & GitHub Pages

## Challenges we ran into

Quite some bugs (obviously)
A mismatch between frontend and backend API definition.

We mitigated the problem of bugs by using mypy to check and enforce type hints. 
For syncing our API definition and models we used the automatic OpenAPI specification generator of FastAPI 

## Accomplishments that we're proud of
We have a nice and professional-looking and fully functional web app. It also feels like the real HelloFresh website and integrates well into the brand.
And we have a nice mascot!

## What we learned
We used FastAPI for the first time. We could have used another backend framework, but trying a new one is fun and had a good learning effect.

## What's next for LasagneTUM
- Adding to remark allergens
- Making recipes customizable
- Provide insights for HelloFresh about what user like or not and how to adapt the recipes 