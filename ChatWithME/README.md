# ChatWithMe 
A React.js chat app with ChatKitAPI

## Children Components

* Title
* MessagesList
* SendMessageForm

## Dependencies

* Chatkit SDK for handling its back end
* Babel for transforming JSX

## Instructions

* [Use an one liner to open up a http server](https://gist.github.com/SaadAAkash/d8e9ef3fcdd5040d1ba8981bdf43bab3)
* Navigate to the available port at localhost 

## Basic Setup Code for App

```
class App extends React.Component {
  
  render() {
    return (

      <div className="app">
        <Title />
        <MessageList />
        <SendMessageForm />
     </div>

    )
  }
}
//Simply renders out three children: the <Title>,<MessageList>, and the <SendMessageForm> components.

```


