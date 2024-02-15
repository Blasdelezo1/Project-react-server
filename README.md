##Table of Contents

1. [Routes Info ](#routes-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)


### Routes Info General Festivals

| HTTP VERB  |  URLS | REQUEST BODY | ACTION |
| ---------- | ---------- | ---------- | ----------| 
| POST | /festivals | JSON |Create a new Festival|
| GET|  /festivals   |(EMPTY)| Retrieve all Festivals|
| GET| /festivals/:id |(EMPTY)|Return the specific Festival|
| PUT| /festivals/:id|JSON|Edit the specific Festival|
| DELETE|/festivals/:id|(EMPTY)|Deletes the specific festival|



### Edition Routes

| HTTP VERB  |  URLS | REQUEST BODY | ACTION |
| ---------- | ---------- | ---------- | ----------| 
| POST | /editions | JSON |Create a new edition|
| GET|  /editions   |(EMPTY)| Retrieve all editions|
| GET| /editions/:id |(EMPTY)|Return the specific editions|
| PUT| /editions/:id|JSON|Edit the specific editions|
| DELETE|/editions/:id|(EMPTY)|Deletes the specific editions|

### Embedded Routes

| HTTP VERB  |  URLS | REQUEST BODY | ACTION |
| ---------- | ---------- | ---------- | ----------| 
| GET|  /festivals/?_embed=editions  |JSON| Retrieve all Festivals with its own editions|
| GET| /festivals/:id?_embed=editions |(EMPTY)|Return the specific Festival with its specific edition|


