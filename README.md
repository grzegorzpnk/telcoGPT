

<!-- ABOUT THE PROJECT -->
## About The Project

# TelcoGPT

**What a project is about**

```
TelcoGPT is a system designed to simplify comprehensively orchestrate and manage mobile networks on a cloud infrastructure.
```

**Why TelcoGPT is necessary?**

```
To effectively manage 5G networks and its underlay cloud infrastructure you need to be fluent in tons of technologies. Starting from infra management, (e.g. ClusterAPI, Terraform, kubeadm), through 5G Network deployment (kpt, helm -> nephio) and observability (*OpenTelemetry*) compleet on continuum life-cycle management and cloosed loops (kubernetes). 
All of these tools ( provided list is not finalized and new technologies still appears!) requires knowledge of CLIs, rules, good-practices and so on.
```

** How does TelcoGPT works **
TelcoGPT offers high-level user interface in the form of human-level intents for all mentioned technologies. 

Prerequestie: customize LLM to support your infra / network (e.g. IP zones, specific conditions)

1. Specify your intent (simple text format)
2. Let LLM to interprete it (and negotiate)
3. Confirm and validate LLM understanding
4. LLM will call external API of tool based on user context request
5. LLM is working synchronously, so let's wait until task is completed and receive confirmation

** How to achieve? **

TelcoGPT may relies on LLMs such as GPT, LLama, Falcon that seems to be not only good content creators, but as well interpreter of human intents.
LLMs share possibility of executing external tools' API: [[Function Calling](https://platform.openai.com/docs/guides/function-calling)]

** What is gained? **

TelcoGPT provides transparent layer between OSS intents/bussines persons/administrator and underlying technologies to manage 5G network. 
Once customized LLM allow to manage your network (or hundrets of different private network) for non-technical persons.
Even if new technology will appear, no need for administrator to learn it, it will be hidden in technological part.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b telcoGPT/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Grzegorz Panek - grzegorzpnk@gmail.com

Project Link: [[https://github.com/grzegorzpnk/telcoGPT](https://github.com/grzegorzpnk/telcoGPT/)]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

