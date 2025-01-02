<p align="center">
	<a href="https://gitmoji.dev">
		<img src="https://cloud.githubusercontent.com/assets/7629661/20073135/4e3db2c2-a52b-11e6-85e1-661a8212045a.gif" width="456" alt="gitmoji">
	</a>
</p>
<p align="center">
	<a href="https://github.com/carloscuesta/gitmoji/actions?query=workflow%3ACI+branch%3Amaster">
		<img src="https://img.shields.io/github/actions/workflow/status/carloscuesta/gitmoji/ci.yml?branch=master&style=flat-square"
			 alt="Build Status">
	</a>
	<a href="https://gitmoji.dev">
		<img src="https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square"
			 alt="Gitmoji">
	</a>
</p>

## About

[Gitmoji](https://gitmoji.dev) is an initiative to standardize and explain **the use of emojis on GitHub commit messages**.

**Using emojis** on **commit messages** provides an **easy way** of **identifying the purpose or intention of a commit** with only looking at the emojis used. As there are a lot of different emojis I found the need of creating a guide that can help to use emojis easier.

The gitmojis are published on the [following package](https://www.npmjs.com/package/gitmojis) in order to be used as a dependency 📦.

## Project 

Our main task for the project was to add a column we named "relatedColumn" in which we put emojis that are related to the currently select emoji.

This is inspired by this [issue](https://github.com/carloscuesta/gitmoji/issues/924).

Even if the [backend](packages/gitmojis) was available to us we wanted to avoid changing it as we believed that the project tasks us with changing an open source website and consuming an API we cannot modify. 

As such to choose if two emojis were "related" we checked if key-word were present in both description and if they were the two emojis were related.  

We also took the time to "embellish" the css with our own artistic take
How to start the website


## Run the project

Clone the project 
```
$ git clone https://github.com/Juleaus/fabules_gitmoji.git
$ cd gitmoji
```
Install the dependencies and start the development server.
```
$ npm install pnpm
$ cd packages/website
$ pnpm install && pnpm run dev
```

