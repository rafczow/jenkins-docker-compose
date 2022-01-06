# How to use
1. Rename env_sample to .env

2. Add your ssh pub key to env file.

    To learn how to generate ssh key for jenkins agent check official documentation:
    https://www.jenkins.io/doc/book/using/using-agents/#generating-an-ssh-key-pair

3. Start containers
    ```
    docker-compose up
    ```

4. Visit http://localhost:8080/ and finish installation using setup wizard.