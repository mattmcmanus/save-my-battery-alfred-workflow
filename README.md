# Save my battery!

An Alfred workflow that make it easy to kill all of you power and internet guzzl'n applications. 

**out**: Quits all open applications as well as a few menu bar apps (Dropbox, AeroFS)

**home**: Reopens all of the apps that were closed

## Modifying what's closed

Check out the bash script attached to out:

```bash
# Take care of some menu bar apps as well
killall Dropbox AeroFS
```

Need to add another app? Simply add it to the list!