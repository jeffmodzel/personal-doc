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


```
// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
```
## cli tables
cli3
tty-table
chalk

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
