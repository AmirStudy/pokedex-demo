# Pokemon Demo Bot 

This is a demonstration of a digital assistant that can answer questions about pokemon. This is an open project and anybody can contribute to it. 

To run the assistant locally you'll first need to clone. 

```
git clone 
```

Next, install rasa. 

```
pip install rasa
```

Next you'll need to train the assistant. 

```
rasa train
```

Once trained, you can now talk to it. Since we're using custom python code 
in there we'll need to run an action server on the side. So first start an
action server via;

```
rasa run actions
```

With this running you can now talk to your assistant. 

```
rasa shell
```

## Extra Inspection 

If you want to get more of a view of what is happening you can also run; 

```
rasa shell nlu
```

By running it this way you'll get more of a glimpse in what the NLU components think.

If you want to supply the assistant with new data you can also 
handle this interactively via;

```
rasa interactive
```

---  

## About Rasa

- **What does Rasa do? 🤔**
  [Check out our Website](https://rasa.com/)

- **I'm new to Rasa 😄**
  [Get Started with Rasa](https://rasa.com/docs/getting-started/)

- **I'd like to read the detailed docs 🤓**
  [Read The Docs](https://rasa.com/docs/)

- **I'm ready to install Rasa 🚀**
  [Written Installation Guide](https://rasa.com/docs/rasa/user-guide/installation/) - [Video Guides](https://www.youtube.com/playlist?list=PL75e0qA87dlEWUA5ToqLLR026wIkk2evk)

- **I want to learn how to use Rasa 🚀**
  [Tutorial](https://rasa.com/docs/rasa/user-guide/rasa-tutorial/)

- **I have a question ❓**
  [Rasa Community Forum](https://forum.rasa.com/)

- **Explore More Starter Kits ⌨️**
  [Financial Demo](https://github.com/RasaHQ/financial-demo) [Medicare Locator Demo](https://github.com/RasaHQ/medicare_locator)