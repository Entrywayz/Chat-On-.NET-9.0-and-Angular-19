## Web Chat with .NET 9 and Angular 19

### Description
A simple real-time text chat application built with:
- Backend: .NET 9
- Frontend: Angular 19

### Features
- Send and receive text messages
- Real-time message updates
- (Incomplete) Message history

### Known Issues (Bugs)
⚠️ **Messages disappear on page refresh** - This happens because persistent message storage was not implemented (I was too lazy to finish this part). Messages are only stored in memory and cleared when the server or page reloads.

### Setup & Installation

#### Backend (.NET 9)
1. Navigate to the `backend` folder
2. Run:
   ```
   dotnet restore
   dotnet run
   ```

#### Frontend (Angular 19)
1. Navigate to the `frontend` folder
2. Run:
   ```
   npm install
   ng serve
   ```

### Usage
1. Open your browser at `http://localhost:4200`
2. Type a message and click "Send"
3. Enjoy the chat (until you refresh the page 😅)

### Roadmap
- [ ] Add database for message persistence
- [ ] Implement user authentication
- [ ] Add file attachment support
- [ ] Improve UI design

### License
MIT License (because the code is just okay)
