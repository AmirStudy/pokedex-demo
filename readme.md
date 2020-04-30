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
  [Installation](https://rasa.com/docs/rasa/user-guide/installation/)

- **I want to learn how to use Rasa 🚀**
  [Tutorial](https://rasa.com/docs/rasa/user-guide/rasa-tutorial/)

- **I have a question ❓**
  [Rasa Community Forum](https://forum.rasa.com/)

- **I would like to contribute 🤗**
  [How to Contribute](#how-to-contribute)
