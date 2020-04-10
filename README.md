# personal-doc
Repo for documenting things


## Markdown cheat sheets
[Markdown Guide](https://www.markdownguide.org/cheat-sheet/)

[Github](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[the simple guide](https://rogerdudler.github.io/git-guide/)


## AWS CLI Examples

[AWS CLI Documentation](https://docs.aws.amazon.com/cli)

## AWS Connect

[Connect Examples](aws-cli-connect.md)

## DynamoDB
[DynamoDB Guide](https://www.dynamodbguide.com)

[reInvent Video](https://aws.amazon.com/dynamodb/resources/reinvent-2019-data-modeling/?sc_ichannel=ha&sc_icontent=console_OrganizationID_PageID_db-datamodeling_awssm-3583&sc_icampaign=Adoption_Campaign_pac_q42019_sitemerch_console_DynamoDB&trkCampaign=pac_sm_q4_1019_dynamodb_DataModeling&trk=ha_awssm-3583&sc_ioutcome=PaaS_Digital_Marketing&sc_iplace=console_OrganizationID_PageID_STANDARD)


## Serverless
[LInk to sub-page](serverless.md)


## Git
How to store credentials:

```bash
 git config --global credential.helper store
```
Updates `~/.gitconfig` like:
```
[user]
    email = person@email.com
    name = some person
[credential]
   helper = store

or use:

git config -l
```

create git md file and link it

Stores plaintext credentials in `~/.git-credentials`

Details here: https://git-scm.com/book/en/v2/Git-Tools-Credential-Storage


https://rogerdudler.github.io/git-guide/


git checkout -b feature_x
git push origin <branch>


```script
// create new branch and check it out
git checkout -b feature_x

// push branch to new remote branch
git push origin feature_x


// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
```

## Node.js
### CLI Tables
- cli3
- tty-table
-c halk

## CSS
skel
bulma

w3
other ones?

### Primitive UI
https://github.com/taniarascia/primitive

---

> block quote
> more blockquote

```javascript
var j =10
```

```python
def junk()
  fdsafasdfas
```
## Javascript front-ends

### Vue
[LInk to sub-page](vue.md)

### Alpine
https://www.smashingmagazine.com/2020/03/introduction-alpinejs-javascript-framework/


### React
https://blog.bitsrc.io/react-typescript-cheetsheet-2b6fa2cecfe2


## SQLite
https://www.sqlite.org
https://www.sqlite.org/cli.html
https://github.com/pawelsalawa/sqlitestudio
https://docs.python.org/3/library/sqlite3.html

## Python

https://www.python.org/dev/peps/pep-0008/#naming-conventions
https://book.pythontips.com/en/latest/index.html

## Electron

electron stuff here

## OAuth and SAML

https://dev-256594.okta.com/login/login.htm
https://oauthdebugger.com/
https://oidcdebugger.com/
https://developer.okta.com/docs/concepts/
https://aaronparecki.com/oauth-2-simplified/
https://developer.okta.com/blog/2019/08/22/okta-authjs-pkce
https://developer.okta.com/blog/2019/05/01/is-the-oauth-implicit-flow-dead