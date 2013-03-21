## Root
/
GET


## Notes

### List notes
```http GET /notes/```

### Add a note
```http POST /notes/```

### View a specific note
```http GET /note/:note_id/```

### Update a specific note
```http PATCH /note/:note_id/```

### Delete a specific
```http DELETE /note/:note_id/```

## Topics
/topics/
verbs: GET, POST

/topics/:topic_slug/
verbs: GET, PATCH, DELETE


## Documents
/documents/
verbs: GET, POST

/documents/:topic_id/
verbs: GET, PATCH, DELETE


## Transcripts
/transcripts/
verbs: GET, POST

/transcripts/:id/
verbs: GET, PATCH, DELETE

/transcripts/:id/footnotes/
verbs: GET, POST

/transcripts/:id/footnotes/:id/
verbs: GET, PATCH, DELETE

## Projects
/projects/
verbs: GET, POST

/projects/:project_id/
verbs: GET, PATCH, DELETE

/projects/:project_id/roster/
verbs: GET, POST


## Users
/users/
verbs: GET, POST

/users/:username/
verbs: GET, PATCH, DELETE

/users/:usersname/recent/
verbs: GET
