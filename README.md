# screeps-remote-example

A minimalist example of using the [screeps-remote](https://github.com/troygoode/screeps-remote) development tool for [Screeps](https://screeps.com/).

![](https://i.imgur.com/Lrsu31K.png)

## Notes

* This example looks to the `SCREEPS_USERNAME` and `SCREEPS_PASSWORD` environment variables for authentication details to avoid a situation where you commit secrets into git.
* To aid in the above, we use the [dotenv](https://www.npmjs.com/package/dotenv) library to automatically load the contents of the `.env` file (not present by default) in this folder into your environment variables at run-time.
* You must create the `.env` file yourself. An example is provided below.
* The `.gitignore` has been configured to ensure that `.env` does not get committed to git.

## Example `.env` File

```
SCREEPS_USERNAME=your_username_here
SCREEPS_PASSWORD=your_password_here
```
