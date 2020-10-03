# First-Form-try2
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <style> form {
      /* Center the form on the page */
      margin: 0 auto;
      width: 400px;
      /* Form outline */
      padding: 1em;
      border: 1px solid #CCC;
      border-radius: 1em;
      }
      
      ul {
      list-style: none;
      padding: 0;
      margin: 0;
      }
      
      form li + li {
      margin-top: 1em;
      }
      
      label {
      /* Uniform size & alignment */
      display: inline-block;
      width: 90px;
      text-align: right;
      }
      
      input,
      textarea {
      /* To make sure that all text fields have the same font settings
      By default, textareas have a monospace font */
      font: 1em sans-serif;
      
      /* Uniform text field size */
      width: 300px;
      box sizing: border-box;
      
      /* Match form field borders */
      border: 1px solid #999;
      }
      
      input:focus,
      textarea:focus {
      /* Additional highlight for focused elements */
      border-color: #000;
      }
      
      textarea {
      /* Align multiline text fields with their labels */
      vertical-align: top;
      
      /* Provide space to type some text */
      height: 5e,;
      }
      
      .button {
      /* Align buttons with the text fields */
      padding-left: 90px; /* same size as the label elements */
      }
      
      button {
      /* This extra margin represnt roughly the same space as the space between the labels and their text firlds */
      margin-left: .5em;
      }
    </style>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body> 
    <form action="/my-handling-form-page" method="post">
    <ul>
      <li>
        <label for="name">Name:</label>
      <input type="text" id="name" name="user_name">
        </il>
      <li>
        <label for="mail">E-mail:</label>
      <input type="email" id="mail" name="user_email">
        </li>
      <li>
        <label for="msg">Message:</label>
        <textarea id="msg" name="user_message"></textarea>
      </li>
    <li class="button">
      <buttom type="submit">Send your Message</button>
      </li>
      </ul>
    </form>
    <p>This is my page</p>
  </body>
</html>
