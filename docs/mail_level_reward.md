# mail\_level\_reward

[<-Back-to:World](database-world.md)

**The \`mail\_level\_reward\` table**

On certain levels, you receive a mail with some text.

**Structure**

| Field               | Type         | Attributes | Key | Null | Default | Extra | Comment |
|---------------------|--------------|------------|-----|------|---------|-------|---------|
| [level][1]          | tinyint(3)   | unsigned   | PRI | NO   | 0       |       |         |
| [raceMask][2]       | mediumint(8) | unsigned   | PRI | NO   | 0       |       |         |
| [mailTemplateId][3] | mediumint(8) | unsigned   |     | NO   | 0       |       |         |
| [senderEntry][4]    | mediumint(8) | unsigned   |     | NO   | 0       |       |         |

[1]: #level
[2]: #racemask
[3]: #mailtemplateid
[4]: #senderentry

**Description of the fields**

### level

Level required for receiving specific mail

### raceMask

Mask required to receive mail.
`:ChrRaces.dbc`

### mailTemplateId

Mail ID to be send. See [MailTemplate.dbc](MailTemplate)

### senderEntry

`field-no-description|4`
