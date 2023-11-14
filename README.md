<h1 align="center">Poke Dex App</h1>



```javascript
export function PasswordGeneratorCard() {
    const [password, setPassword] = useState("Amazing Password");

    return (
        <div className={s.root}>
            <div className={s.main}>
                <PasswordGeneratorHeader />
                <PasswordGeneratorBody onSubmit={setPassword} />
            </div>
            <PasswordGeneratorFooter password={password} />
        </div>
    );
}
```
## About the project

<table width="100%">
    <tbody width="100%">
        <tr>
            <td rowspan=5 align="rigth">
                <img src="https://github.com/marcosguz/poke-dex/assets/75583218/3aedb200-60c4-4056-b2a9-6ecee4725981" width="500px">
            </td>
        </tr>
        <tr>
            <td align="justify">This web application is a tool developed to facilitate the creation of passwords. It is quite simple to use: just
You must choose the characters you want your password to have, and you can also copy it to your clipboard, for greater convenience.</td>
        </tr>
        <tr>
            <td align="justify">
				<a href="https://poke-dex-wheat.vercel.app/">Poke Dex App</a>
			</td>
        </tr>
    </tbody>
</table>

## Developed with
![Angular](https://img.shields.io/badge/-Angular-DD0031?style=for-the-badge&labelColor=white&logo=angular&logoColor=DD0031)
![Typescript](https://img.shields.io/badge/Typescript-007acc?style=for-the-badge&labelColor=black&logo=typescript&logoColor=007acc)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SASS Badge](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)

## How to contribute?
Contributions are what make the open source community an amazing place to learn, inspire, and create. Any contribution you make is greatly appreciated.

1. Fork the project.
2. Create a feature branch: (git checkout -b features/amazing-feature).
3. Commit your changes: (git commit -m 'Add an Amazing Feature').
4. Upload your changes to the branch: (features/amazing-feature)
5. Open a pull request

## License
Distributed under the MIT license. See the `LICENSE` file for more information.

## Contact
Marcos Guzmán

<a href="https://www.linkedin.com/in/marcos-guzman-nazareno" target="blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Marcos"/>
</a>
<a href="https://twitter.com/marccosgz" target="blank">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>

## Recognitions
- [Angular CLI](https://github.com/google/angular_cli)
- [Marked](https://marked.js.org/)
