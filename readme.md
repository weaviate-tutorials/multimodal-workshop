
# Instructions on how to run the multimodal part of the workshop with GitHub codespaces

1. Login to your GitHub account.
1. Go to this repository: [https://github.com/weaviate-tutorials/multimodal-workshop](https://github.com/weaviate-tutorials/multimodal-workshop).
1. Run the project with Codespaces
    * Click on `"Code"` > `Codespaces`.
    * You will see a section labeled "Codespaces" with options "+" and "…" to the right. Click `"…"` and then select `"New with Options."`
    * Upgrade the Machine type to `4-core`
    * Click `"Create codespace."`
    * It may take a few minutes for your Codespaces container to start. Once it does, you will see the IDE, terminal, and repository similar to VSCode.
1. From the terminal in the project, navigate to `2-multimodal`:
    ```
    cd 2-multimodal
    ```
    and start the docker image defined in `docker-compose.yml` by calling: 
    ```
    docker compose up
    ```
1. After a few minutes (depending on the download speed, it might take 5-10 minutes 😅), you should see a message like this: 
    ```
    multimodal-workshop-multi2vec-bind-1 | INFO: 172.19.0.3:48294 - "GET /meta HTTP/1.1" 200 OK.
    ```
