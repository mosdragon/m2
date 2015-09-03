##M2 for CS2340

####Working with Gradle
Make your gradle file with the format _gtuser.gradle_, replacing _gtuser_ with your actual GT username like _gburdell3_.

Then, run the following:
```bash
gradle -b gtuser.gradle build
```

You should now have a _build_ folder in the root directory. Go into _build/libs_ and you should see a jar with a name along the lines of __M2-1.0.jar__.

Run the following in your terminal:
```bash
java -jar M2-1.0.jar
```

If your output says 
```
Congrats! You deserve a cookie....
```
you are done. Otherwise, refer to __msakhi3.gradle__ to make your own Gradle file.