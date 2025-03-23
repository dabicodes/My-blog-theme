### Themes

Themes created for bearblog. 

Colors and fonts can be change through the variables at :root.

* [Simple theme](#simple)  
* [Nostalgia theme](#nostalgia)  


<a name="simple"/>

# Simple theme

It's simple, I tried to make it as minimalistic as posible.

![imagen](https://github.com/user-attachments/assets/51b56f74-e2b7-4f71-a21c-cae4639a313d)

![imagen](https://github.com/user-attachments/assets/0a05dd65-f099-4a27-a8de-360dfc2014d5)

## Components

Some examples on how to implement different components.

### Status

![imagen](https://github.com/user-attachments/assets/6c90f93e-aa2c-4001-8e7c-109d34951e55)

```
<div class="status-container">
  <p><strong>Status</strong></p>
  <p class="status">
    EN: Writing a tutorial it's hard! 
  </p>
  <hr>
  <p class="status">
    ES: Escribir un tutorial es dificil!
  </p>
</div>
```
### End notes

![imagen](https://github.com/user-attachments/assets/529c30d3-78d5-47ab-ab46-1b4a1e32d92c)

```
<section class = "end-notes">
Thanks for reading (●'◡'●)

Reply via [Email 📧](https://letterbird.co/dabi)
</section>
```

<a name="nostalgia"/>

# Nostalgia theme

It's a Windows 7 inspired theme.

![imagen](https://github.com/user-attachments/assets/d3c60cb3-7634-4d36-b306-58ed86e71946)

![imagen](https://github.com/user-attachments/assets/d728869e-091f-41f4-b51a-9b1883e091cc)


## Components

Some examples on how to implement different components.

### Close button

![imagen](https://github.com/user-attachments/assets/e261134d-f038-4f2a-b424-1c1868bb0c07)

This is a button to return to bearblog discover page.

To implement it, add this code to your nav bearblog section.

```
<p class="close"><a href="https://bearblog.dev/discover">x</a></p>
```

### Segment

![imagen](https://github.com/user-attachments/assets/dc3d3f59-2528-4cdf-aff1-e6dc9e227160)


A segment you would like to higlight. Inspired in a group box.

For example I use it for my status like this:

```
<div class="segment-container">
    <h2 class="segment-container-title">Status</h2>
    <p>
        EN: Writing a tutorial it's hard! 
    </p>
    <p>
        ES: Escribir un tutorial es dificil!
</p></div>
</div>
```
