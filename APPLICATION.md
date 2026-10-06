# What is this?

I struggle with productivity. *A lot*. It's been especially bad since I got a second monitor, and I want an application developed to help me with that.

# What should it do?

## **Big: Computer and Android application that communicate with each other automatically. I should not have to do anything for them to communicate but obviously I don't want to set up a real server for just this little application!!!**

* Remind me to go to bed on time if I have something to do the next day (I need about an hour to talk to my friend and get in bed and stuff so it should remind me an hour before, and when I'm on my phone it should remind me 20 minutes before I need to sleep and at some point give a countdown before it locks me out of using my phone.)
* Integrate with Discord with a [Vencord](C:\Development\vscode\Vencord\src) plugin to automatically put me on do not disturb while I'm working, though allow my friends to still message me if it's urgent
  (e.g:

  I start working, application automatically puts me on do not disturb and sets my status to something along the lines of "Working, will read DMs later". If they still send a message, send them a message automatically saying something along the lines "I'm working. Reply with 'urgent' if this is urgent and I should read this right now, otherwise I'll get back to you later."

  )

  Once I'm done working, it should give me a briefing of everything that happened while I was working. Every DM, every mention, etc. Is this technically against Discord TOS? Yeah, but I don't necessarily care. Worst case I get my account banned. Oh well.
* Integrate with YouTube music so I can listen to music while I'm working but with limited skips (with a way to reset that's a pain in the ass enough so that I don't do it subconciously), and stripped down so I don't spend all day picking music
* Lock me out of all applications (obviously with the ability to bypass but make it a pain in the ass so I don't do it subconciously) on both my phone and computer until I get done what I'm doing or spend sufficient time on it
* Handle my scheduling automatically in a best-effort method
* Phone application should act as a to-do list and a way to add things to do, with notifications reminding me of things to do, and if possible it should interface with Samsung's clock app to automatically set alarms for when I need to wake up.
* I should be able to set up how much free time I want before I need to leave to go do something e.g go to work or go to class.
* Tasks should be able to be set to do over a vague period of time, e.g this weekend or this week, not just strictly a daily task.

# What does it need?

* Custom notification API. Windows notifications are too finnicky and get broken by too many things, such as do not disturb while I'm playing games. You know how antiviruses have custom notifications? Something like that.
* Some way to communicate between phone and computer without a cloud server and without a physical cable plugin. I WILL forget to do it if I need to physically plug in a cable.
* It should not use up all of my system resources. I may be running on a 9950X3D and a 5090, but that does not mean it should be utilizing every ounce of system resources, so it should be light. No AI integration, no electron, hell, it shouldn't even use HTML in the first place.
* A way to lock me out of using my second monitor, though don't hardcode it for second monitor only in the case that I get more than just two monitors. (like how lockdown browser works kind of)
* A way to lock me out of using my phone (with a way to bypass that's painful enough I won't do it subconciously)

# What should it not have?

Passwords. No passwords. No pins. A lot of apps use something like this as the bypass method, that is not what I want at all.

# What should it be programmed in?

I don't know. Nor do I really care. I have the tools to compile C++, I have Python installed, I have node.js, I think I might even have JDK. It doesn't really matter what it's programmed in. I also have Android Studio Rabbit 1 2026.2.1 installed for the Android side.


# Checklist

* [ ] Create basic Windows application
* [ ] Create basic Android application
* [ ] Create notification system
* [ ] Create communication system between phone and PC
* [ ] Create lockout system (for monitor)
* [ ] Create lockout system (for phone)
* [ ] Set up sleep reminder system
* [ ] Set up Vencord plugin
* [ ] Add Discord integration
* [ ] Add YouTube Music integration
* [ ] Add scheduling system

--Add any other items to the checklist if deemed necessary--
