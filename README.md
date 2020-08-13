> [firebase_auth] PlatformException(ERROR_INVALID_EMAIL, The email address is badly formatted., null)

It means that your email address contains a blank space and therefore should be resolved by adding the attribute trim() before sending the email (also password as the error can also arrise over there).
trim() will take care of all the blank spaces in the credential entries.
