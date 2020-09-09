### Hi there 👋

## 🔭 I’m currently working on Solr and Java [ Search Engine Platforms]
## 🌱 I’m currently learning Elastic Search, Data Science
## 👯 I’m looking to collaborate with people who are looking forward in this things
## 🤔 I’m looking for help with data science pathway.
## 💬 Ask me about Java
## 📫 How to reach me: skype : karshil_2309
## 😄 Pronouns: One Developer Army
## ⚡ Fun fact: I hate early morning... 

package com.nilshomer.bfx.examples.utilities

import com.fulcrumgenomics.cmdline.ClpGroups
import com.fulcrumgenomics.sopt.{arg, clp}
import com.nilshomer.bfx.examples.cmdline.BfxExamplesTool

@clp(
  description = "Prints your name to standard out and exits.",
  group       = ClpGroups.Utilities
)
class PrintName
(
  @arg(flag='n', doc = "Karshil Sheth.") val name: String
) extends BfxExamplesTool {
  validate(name.nonEmpty, "Your name cannot be empty")
  def execute(): Unit = println(this.name)
}

<!--
**karshil2309/karshil2309** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


![](https://komarev.com/ghpvc/?username=karshil2309&color=green)
