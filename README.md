## Remote Crud

### Author: David Chambers/John Cokos

### Links and Resources
* [repo](https://github.com/dlchambersjr/lab-34)
* [front-end](https://codesandbox.io/s/x3n8vym964)

### Modules
#### `index.js` -> <App/>

#### store/`index.js` -> Redux Store

###### `combineReducers(arity *) -> obeject with properties of different states`
Creates the necessary object to reference the store through a property.

###### `store -> store for global consumption`
Makes the reducers and middleware available to the app.

#### store/middleware/`reporter.js` -> logs actions/reducers/state

#### component/`app.js` -> renders <RecordList/> from list.js

#### component/`list.js` -> renders player-model-data and <Record/> from record.js

###### `deleteRecord(id)` -> returns updated state after delete
Deletes the record at position ID.

###### `edit(id)` -> returns updated state after edit and POST
Edits the selected ID

###### `reset()` -> clears the form for new input
Prepares the form to receive new data to be posted.

#### component/record/`record.js` -> renders the form from redux <Form/>

###### `componentDidMount()` -> schema from the API
Load the schema from the API into state

###### `resetPlayer(id)` -> TBD
TBD

###### `handleSubmit(form)` -> data to be posted on API and in state
Posts the form to the API and to state

#### component/record/`action.js` -> information to be updated via api and state

###### `TBD()` -> TBD
TBD

#### component/record/`reducers.js` -> modifies the store

###### `TBD()` -> TBD
TBD



#### Running the app
* `npm start`


#### Tests
* Testing needs to be done still

#### UML
[Remote Crud](UML LINK HERE - Will be hot-fixed in GITHUB)
