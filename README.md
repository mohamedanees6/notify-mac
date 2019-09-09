# notify-mac
<h2> What is this about? </h2>

Ever needed a notification for your build completion running on terminal?

Worry not, this small function would do that with ease! Just append your build command with `; notify-sys 'Build Complete' 'Your background build has completed'`

<h2>How to use? </h2>

1. Pull in the utility script by using cURL.

`curl https://raw.githubusercontent.com/mohamedanees6/notify-mac/master/notify-mac >> ~/.notify-mac`

2. Just type in 

`echo 'source ~/.notify-mac' >> ~/.bash_profile`

This causes your bash_profile to include notify-mac everytime it is initialized.

3. Type in `source ~/.bash_profile` to reinitialize all the configured functions and methods.

Test it by typing `notify-sys Hello World`.

<h2> Sample Usage </h2>

Oh this simple tool has infinite possibilities, add it to almost anything you want to be processed in the background.

`<Your build command here> ; notify-sys 'My Local build on project XYZ is Complete'`


`<Your huge cURL download> ; notify-sys 'Download complete cURL huge.txt'`

And what not!

<h2> Revert back </h2>

Oh Sad. But, Thanks for trying out my little program!

You can remove the changes by typing in `rm ~/.notify-mac` and remove the line `source ~/.notify-mac` from your `~/.bash_profile` using any text editor.
