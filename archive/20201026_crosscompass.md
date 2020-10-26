[Original Source Link](https://www.reddit.com/r/haskell/comments/jibcz7/job_cross_compass_is_hiring_haskell_developers/)

[Cross Compass](https://www.cross-compass.com/) is a data science and machine learning consultancy located in Tokyo, Japan. We are hiring Haskellers to work on a machine learning platform. We are mainly looking for people skilled in either web programming, machine learning, or embedded development.

## Technical skills used on our team

Our machine learning platform has quite a few moving parts:

*   two web frontends (one written in PureScript, and one written in TypeScript)
*   two backends (one written in Haskell, and one written in Ruby)
*   a deep learning engine (written in Haskell, calling out to Caffe2)
*   a library for running models on embedded devices (written in C, C++ and CUDA calling out to oneDNN and cuDNN)

Given these various parts, we end up touching a lot of different technologies:

*   Haskell, including the following libraries:
    *   conduit
    *   JuicyPixels
    *   lens
    *   servant
*   PureScript, including the following libraries:
    *   affjax
    *   argonaut
    *   [protobuf](https://github.com/xc-jp/purescript-protobuf)
    *   react-basic
*   Nix (and a little Docker)
*   Ruby
*   TypeScript
*   C (and a little C++ and CUDA)
*   machine learning (we are currently mostly focused on deep learning)

We have long-term plans to move away from Ruby and TypeScript (and towards Haskell and PureScript), but no concrete time-frame for when this will happen.

## What sort of developers are we looking for?

In the short term, we are planning on hiring two developers. We want to hire developers who know some combination of the above technologies, or would be interested in learning.

We imagine hiring one developer who is familiar with Ruby, TypeScript, and Haskell. Machine learning experience wouldn't be necessary, but helpful. They would start out with web development in Ruby and Typescript, along with some Haskell work. Over time they would probably move more towards doing web development in Haskell and PureScript.

We imagine hiring one other developer who is familiar with machine learning, Haskell, and possibly embedded development. They would help with the Haskell deep learning engine, as well as the C-based embedded library. They would probably also have the chance to help with the Haskel web backend and PureScript web frontend.

We are also interested in any other candidates that have unique combinations of the above skills, or interesting backgrounds. Please don't hesitate to apply based on your background or skills. Previous working experience with Haskell or any of the other technologies listed above is not a requirement.

## Non-technical requirements

We would prefer to hire developers that can work locally from Tokyo. We sponsor visas for developers who want to move to Japan.

If we don't find anyone who is willing to relocate to Japan, **we will considering hiring remote-only candidates**. Most of our meetings take place in the afternoon in [JST (UTC+9)](https://www.timeanddate.com/worldclock/converter.html?iso=20201104T050000&p1=248), which is around 5 AM UTC. Although we are flexible on this point.

We prefer to hire developers who want to work full time (40 hours per week).

## Pay

The salary range for this position is **6 to 8 million yen (about USD $57,000 to $75,000)**.

## Application and hiring process

If this sounds interesting, please feel free to email us at [recruit@cross-compass.com](mailto:recruit@cross-compass.com).

We are not too big on standard resumes, but you are welcome to send us any information that you think would catch our attention, including things like:

*   relevant work history (e.g. work somewhere before using Haskell? Or maybe doing frontend development with TypeScript?)
*   relevant education history (e.g. took a class on machine learning?)
*   open-source software links (e.g. author any interesting libraries? have a cool machine learning project?)
*   papers, articles, blog posts, social media, or anything else which reflects well on you

We'd also like to know your situation regarding on-premise work vs. remote, including whether or not you would be interested in moving to Japan.

There will be one interview to learn more about you and for you to ask us questions.

We will invite promising candidates to a part-time, one-month paid trial period. During this trial period we see what it is like working with you, and you get to see how we work as a team. Ideally, you'd be able to work at least a couple hours a week (so we both have an idea what is it like to work with each other when the month is over), but we are flexible with the details here.

We would make you an offer after the trial-period.

## Haskellers at Cross Compass

There are already a few Haskellers at Cross Compass. You may have interacted with us online or at various meetups and conferences.

*   [Viktor Kronvall](https://github.com/considerate)
*   [Jonas Carpay](https://github.com/jonascarpay)
*   [Ramin Honary](https://github.com/RaminHAL9001)
*   [James Brock](https://github.com/jamesdbrock)
*   [Dennis Gosnell](https://functor.tokyo/)
