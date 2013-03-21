Root
========
### List actions
```http
GET /
```

- - -

Notes
========
### List notes
```http
GET /notes/
```

### Add a note
```http
POST /notes/
```
example:
```javascript
{
'title': 'My new note',
'description': 'This is where I will be doing my work.',
'status': '1',
'assigned_users': ['patrick']
}
```

### View a specific note
```http
GET /note/:note_id/
```

### Update a specific note
```http
PATCH /note/:note_id/
```

### Delete a specific note
```http
DELETE /note/:note_id/
```

- - -

Topics
========
### Get list of topics
```http
GET /topics/
```

### Add a new topic
```http
POST /topics/
```

### Get a specific topic
```http
GET /topics/:topic_slug/
```

### Get items related to a specific topic
```http
GET /topics/:topic_slug/related/
```

### Update a specific topic
```http
PATCH /topics/:topic_slug/
```

### Delete a specific topic
```http
DELETE /topics/:topic_slug/
```

- - -

Documents
========
### Get a list of documents
```http
GET /documents/
```

### Create a document
```http
POST /documents/
```

### Get a specific document
```http
GET /documents/:document_id/
```

### Update a specific document
```http
PATCH /documents/:document_id/
```

### Delete a specific document
```http
DELETE /documents/:document_id/
```

- - -

Transcripts
========
### Get a document's transcript
```http
GET /documents/:document_id/transcript/
```

### Create or update a document's transcript
```http
PUT /documents/:document_id/transcript/
```

### Delete a document's transcript
```http
DELETE /documents/:document_id/transcript/
```

- - -

Footnotes
========
### List footnotes in a transcript
```http
GET /documents/:document_id/transcript/footnotes/
```

### Add a footnote to a transcript
```http
POST /documents/:document_id/transcript/footnotes/
```

### View a specific footnote
```http
GET /documents/:document_id/transcript/footnote/:footnote_id/
```

### Update a specific footnote
```http
PATCH /documents/:document_id/transcript/footnote/:footnote_id/
```

### Delete a specific footnote
```http
DELETE /documents/:document_id/transcript/footnote/:footnote_id/
```

- - -

Projects
========
### List projects
```http
GET /projects/
```

### View a specific project
```http
GET /projects/:project_slug/
```

### View a project's roster
```http
GET /projects/:project_slug/roster/
```

- - -

Users
========
### List users
```http
GET /users/
```

### View a specific user
```http
GET /users/:username/
```

### View a user's recent history
```http
GET /users/:username/recent/
```
