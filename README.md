
# French version of the StackOverflow JsonResume theme

## Getting started

### Install the command line

Create your resume in json on [jsonresume](https://jsonresume.org)

The official [resume-cli](https://github.com/jsonresume/resume-cli) to run the development server.

Go ahead and install it:

```
npm install -g resume-cli
```

### Install and serve theme

Clone the repository

```
git clone https://github.com/chriscarreau/jsonresume-theme-stackoverflow-fr.git
```

Create a 'resume.json' file in the current folder and follow the [json resume schema](https://jsonresume.org/schema/)

Install dependencies:

```
npm install
```

and simply run:

```
resume serve --theme .
```

### French specifics
Because the css was using the Skills level to change the look of the page, I had to add a few french keywords equivalent

| English         | French |
| -----------     | ----------- |
| Native Speaker  | Langue Maternelle |
| Master          | Expert | 
| Advanced        | Avancé |
| Fluent          | Courant |
| Beginner        | Débutant |
| Intermediate    | Intermédiaire |

## License

Available under the [MIT license](http://opensource.org/licenses/mit-license.php).
