<!DOCTYPE html>
<html>
<head>
  <title>Nur AI</title>
  <style>
    body {
      background: #0f172a;
      color: white;
      font-family: Arial;
      padding: 20px;
    }
    #chat {
      height: 300px;
      overflow-y: auto;
      border: 1px solid #555;
      padding: 10px;
      margin-bottom: 10px;
    }
    input, button {
      padding: 10px;
      width: 100%;
      margin-top: 5px;
    }
    button {
      background: #2563eb;
      color: white;
      border: none;
    }
  </style>
</head>
<body>

<h2>🤖 Nur AI</h2>

<div id="chat"></div>

<input id="userInput" placeholder="Ask me anything..." />
<button onclick="sendMessage()">Send</button>

<script>
function sendMessage() {
  let input = document.getElementById("userInput").value;
  let chat = document# Nur-ai 