# StudyStream
StudyStream is a free and open-source e-learning platform developed to showcase how open-source contributions can have an affect on education. 

## Proposal
The website will be free to use by students with an academic email address (i.e `.ac.uk` or `.edu`), otherwise we will have a paid plan which contributes towards the hosting cost of the project.

The plan is to work closely with academic instituions and form partnerships so we can find out what works best for each student.

### Project Structure

We will be creating a series of micro/macroservices which will be spun up as and when needed. This will reduce costs while keeping the project scalable and efficient. 

Another reason for this is because it allows us to use any programming language needed for each task.

The project will be designed to be run inside a kubernetes cluster, which allows for excellent scalability and reliability across several different locations and servers.

### Languages

At the time of writing, we are planning on using the following:
- [Vue](https://vuejs.org/)
  - We will be using Vue for the web client, as it provides a progressive and versatile approach to developing websites.
- [GoLang](https://go.dev/)
  - Go will be used for runtime efficient services.
- [Rust](https://www.rust-lang.org/)
  - Rust will be used to develop services which need to be small and efficient, for example launching docker containers to run code tests.

## License

StudyStream is licensed under the [GNU Affero Public License 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html), which you can find a copy of by naivgating to the [LICENSE](./LICENSE) file.

