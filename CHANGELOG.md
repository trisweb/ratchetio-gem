# Change Log

**0.4.0**
 
    - Breaking change to make the "person" more configurable. If you were previously relying on your `current_member` method being called to return the person object, you will need to add the following line to `config/initializers/ratchetio.rb`:
        
        config.person_method = "current_member"

    - Person id, username, and email method names are now configurable -- see README for details.
