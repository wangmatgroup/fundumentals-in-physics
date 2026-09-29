---
description: Including motivations and aims of this book.
---

# Preface&#x20;

### Motivations

The motivation for writing this book comes from a difficulty that I encountered repeatedly during my own education in theoretical physics: there is often a surprisingly large gap between what we learn from undergraduate textbooks, what appears in graduate-level courses, and what we are eventually expected to understand in actual research.

I first became seriously aware of this gap when I was studying in China at one of the country's leading universities. Undergraduate courses gave me a foundation in quantum mechanics, mathematics, and statistical physics. But once I entered graduate-level study, the mathematical language suddenly became much more abstract.

Concepts such as Clebsch-Gordan coefficients, representation theory, Schur's lemma, Green's functions, and many other mathematical tools appeared almost without warning.

The difficulty was not simply that these subjects were mathematically complicated.

The greater problem was that very few people explained **why these mathematical structures were introduced in the first place**.

A textbook might state a theorem, provide a derivation, and immediately move on to the next result. A lecture might teach us how to calculate a Clebsch-Gordan coefficient without explaining what physical problem the coefficient is really solving. Group theory might introduce Schur's lemma as an abstract mathematical statement without first showing why a physicist should care about it.

For a student encountering these ideas for the first time, the equations can therefore feel almost arbitrary.

### The gap no one really teaches

My experience at that time was especially difficult.

One of my graduate quantum-mechanics courses was not particularly helpful in building the missing intuition. A considerable amount of lecture time was spent discussing social problems or criticizing younger generations of graduate students instead of clarifying the physics itself.&#x20;

<details>

<summary>Click to review</summary>

老梁故事汇

</details>

At the same time, I was working closely with another senior researcher whose intuition about several problems in theoretical physics was, in my view, often unreliable.

This combination made that period frustrating and confusing.

I still remember reading about the Clebsch-Gordan coefficients in quantum mechanics and Schur's lemma in group theory and feeling almost overwhelmed.

The symbols themselves were not necessarily impossible to manipulate.

The real problem was that I could not see the picture behind them.

I kept asking myself:

* What are these equations actually doing?
* Why do we need this mathematical structure?
* What problem were mathematicians or physicists originally trying to solve?
* How does this abstract formalism connect to something that I can visualize?
* Why should I remember all of these equations if I do not understand where they come from?

Those questions stayed with me for a long time.

### Learning physics while doing research

Later, I continued graduate study in the United States.

The environment was different, but another reality of academic research became increasingly clear: professors have limited time.

Faculty members must constantly balance research, teaching, grant proposals, administration, students, papers, meetings, and many other responsibilities.

I was fortunate that my advisor had a strong background in condensed-matter physics and taught me a great deal about how theoretical physicists actually think about problems.

Many ideas that had previously appeared disconnected gradually began to make more sense.

Nevertheless, no advisor can explain every mathematical tool, every physical intuition, and every connection that a student will encounter during years of research.

A large part of learning theoretical physics inevitably has to happen independently.

And this creates an interesting problem.

Sometimes we know enough mathematics to follow a derivation, but we still do not understand the physical picture.

Sometimes we know how to use an equation in our calculations, but we cannot explain why the equation has that particular form.

Sometimes we can reproduce a result, but we do not yet understand its essence.

That distinction became increasingly important to me.

### Learning from visual explanations

During this process, several online educators strongly influenced the way I approached mathematics and physics.

Channels such as **3Blue1Brown**, **Mathemaniac**, **eigenchris**, and many others demonstrated that sophisticated mathematics does not always need to begin with formal definitions and long derivations.

Sometimes the best starting point is a picture.

A matrix can be understood as a transformation rather than merely an array of numbers.

An eigenvector can be understood as a direction that keeps its direction under a transformation.

An exponential can be understood through continuous evolution.

A Fourier or Laplace transform can be understood as a different way of looking at the same physical process.

A derivative can be understood as describing local change.

Curvature can be understood as describing how something changes as we move through a space.

Once the picture becomes clear, the equations often stop looking arbitrary.

This changed how I study theoretical physics.

Instead of asking only:

> How do I derive this equation?

I increasingly began asking:

> **What is this equation trying to tell me?**

That question is the starting point of this book.

### What this book tries to do

The purpose of this book is not to replace textbooks.

Rigorous textbooks, formal derivations, and careful mathematical treatments remain essential. Intuition alone cannot replace mathematics.

Instead, I want this book to serve as a **bridge** between mathematical formalism and physical intuition.

The subjects discussed here may eventually include:

* differential equations
* generators
* matrix exponentials
* Fourier transforms
* Laplace transforms
* Green's functions
* symmetry
* Lie groups
* Lie algebras
* quantum mechanics
* Berry phase
* Berry connection
* Berry curvature
* topology
* graphene
* transition-metal dichalcogenides
* and other topics in modern theoretical and condensed-matter physics

At first, these subjects may appear to be largely unrelated.

But one of the central ideas of this book is that many of them are connected by a surprisingly small number of recurring ideas:

**Transformation**

**Symmetry**

**Generator**

**Eigenmode**

**Phase**

**Geometry**

**Curvature**

**Topology**

The same mathematical structure often appears again and again under different names.

For example, consider a simple equation describing time evolution:

$$
\frac{d x}{d t} = A x
$$

Its solution involves an exponential:

$$
x(t) = e^{At} x(0)
$$

Later, in quantum mechanics, we encounter:

$$
\psi(t) = e^{-iHt/\hbar} \psi(0)
$$

These equations may appear in completely different chapters of a textbook, but mathematically they are telling closely related stories.

The operator determines how the system changes.

The exponential accumulates that infinitesimal change into a finite transformation.

Much later, the same idea appears again when studying Lie groups and Lie algebras.

This is exactly the kind of connection that I want to emphasize throughout this book.

### From equations to pictures

Another example comes from geometry.

A student may first encounter the Berry phase as another mysterious quantum-mechanical formula.

Later comes the Berry connection.

Then Berry curvature.

Then perhaps a Chern number.

If these objects are introduced only through equations, they can look like an intimidating collection of unrelated definitions.

But there is another way to approach them.

We can first ask what happens when a quantum state changes as we move through a parameter space.

We can ask how its phase changes.

We can ask what happens when we move around a closed path.

We can ask whether the local geometric information accumulated along that path produces something measurable.

From that point of view, Berry phase, Berry curvature, and eventually topology become parts of the same geometric story.

And when we finally arrive at real materials such as graphene or transition-metal dichalcogenides, the abstract mathematics begins to produce observable consequences.

That transition — from mathematical structure to physical picture to real material — is one of the main journeys I hope to explore here.

### Remember less, understand more

One motivation behind this approach is very practical.

There are simply too many equations in theoretical physics to memorize all of them independently.

But perhaps we do not need to.

If several equations are manifestations of the same underlying structure, then understanding that structure reduces the amount of information we need to memorize.

Instead of remembering ten disconnected formulas, we may be able to understand one idea and recognize it in ten different places.

That is much closer to how I now try to learn physics.

I want to understand why the equation has its particular form.

I want to know what changes and what remains unchanged.

I want to know what space the mathematical object lives in.

I want to understand what transformation is taking place.

And whenever possible, I want to see a picture before memorizing a formula.

### Who this book is for

I hope these notes can be useful to several kinds of readers.

They may help undergraduate students who are beginning to wonder what lies beyond their standard courses.

They may help graduate students who suddenly encounter unfamiliar mathematical machinery in quantum mechanics, condensed-matter physics, or field theory.

They may help PhD students and researchers who need to move into an unfamiliar area and want to understand its mathematical language quickly.

And they may also be useful to anyone who simply enjoys mathematics and physics and wants to understand what some of these intimidating equations are actually saying.

I am still learning many of these subjects myself.

Therefore, these notes should not be viewed as a final authority or a replacement for rigorous references.

Instead, this book records a way of thinking about physics: starting with an intuitive question, building a mathematical picture, deriving the equations, and then looking for connections to other areas.

My hope is simple.

When you encounter an ugly-looking equation, I hope you will eventually be able to look past the symbols and ask:

> **What is this equation doing?**

And perhaps, after following the picture behind it, the reaction will become:

> **Ah. Now I see why it has to look like that.**

If this book can help make that moment happen a little more often, then it will have achieved its purpose.







