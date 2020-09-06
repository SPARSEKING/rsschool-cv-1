Daniil Zhdanovich
================
Contact Info
---------
* [Github](https://github.com/MrDanikus)
* [Gmail](daniilzhdanovichwork@gmail.com)
* [Telegram](https://t.me/cool_bool)
* [Site](https://caitan.me)

Summary
----------

For more than 2 years I have been developing various projects in such languages as JavaScript (preferably NodeJs) and C++. Also I have experience in using C#, Python and Assembler. I have a good algorithmic base and i'm a quick learner. I've been participating in Olympiad programming for several years. I am familiar with web technologies, cryptography, machine learning etc. Responsibly approach the tasks and try to solve them optimally and quickly.

Skills
------
**Programming Languages**
:

	* C++
	* JavaScript
	* NodeJS
	* C#
	* Python
**Additional Stuff**
:

	* Git
	* Circle CI
	* Unit Testing

Code Example
------------
Code example from the project I'm currently working on:
```javascript
const GenerateHull = (radius = 10, sharpness = 0.7, points_n = Math.floor(radius)) => {
    const angle_delta = 2 * Math.PI / points_n;
    const segments = Array.apply(null,new Array(points_n)).map((_, i) => i + 1);
    const polar_points = Array.apply(null, Array(points_n)).map(_ => {
        const seg = segments[Random.IntegerRange(0,segments.length)];
        const angle = Random.FloatRange(seg * angle_delta, (seg + 1) * angle_delta);
        return {
            angle,
            cos: Math.cos(angle),
            sin: Math.sin(angle),
            r: Random.FloatRange(radius * sharpness, radius)
        }
    });
    polar_points.sort((a, b) => {
        return a.angle - b.angle;
    })
    return polar_points.map(point => new Point(point.cos * point.r, point.sin * point.r));
}
```

Experience
--------------------

**Yandex Music Downloader**
:	Chrome extension that allows you to download songs and albums from Yandex Music service. It's free to use, and for now has more than 1,5k active users.

**Compliment Me Please**
:	Machine Learning project where neural network generates different compliments. Visit this [site](https://complimentmeplease.com).

**Cpplogger**
:	C++ library that provides an interface to easily log all formatted information to console or file. Allows you to use colors and special styles or even create your own ones. Supports Windows/Mac/Linux. See it on [github](https://github.com/MrDanikus/cpplogger).

**2D Light**
:	This is almost a science work. I've created an algorithm that calculates 2d light. See [demo](https://mrdanikus.github.io/2DLight/) to better understand what I'm talking about. Also visit [github page](https://github.com/MrDanikus/2DLight) and read [article](https://mrdanikus.github.io/2DLight/article)(only rus).

**See more on my [github](https://github.com/MrDanikus) profile!**

Education
---------

2017-2019
:   **IT**, Lyceum BSU (Minsk)

2019-2023
:   **BTech, Faculty of Applied Mathematics and Computer Science**; BSU (Minsk)

Languages
----------------------------------------
* Russian (native speaker)
* English (B2)