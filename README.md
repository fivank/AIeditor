**
Ideas to implement:

security copy of documents and state:
- 2 buttons will be needed: save backup , load saved backup copy and rewrite current state with backup
- with a click, i can create a backup of the current documents and state for the user. this will be saved as a separate second json object, besides the one that is used automatically for loading and saving everything
- the user can click on save backup from time to time, as a safety net. if something goes wrong , the user can load that backup. this backup (other than the normal state) will NOT be automatically saved to firestore untill the user click on the rewrite button explicitly. then that json file will be saved as standard status file.

save status as soon as some note has ben saved, moved, copied, or a book or chapter has been created, copied, moved

offer options for different kind of speech to text engine (browser, system default, android, others,.. AI-assisted-cheap, AI-assisted-good, ...)



**
