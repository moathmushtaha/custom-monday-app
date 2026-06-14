# Custom Monday.com App

A **Monday.com** workspace application built with **Node.js**, **React**, **MongoDB**, and **GraphQL**. This app suite consists of three submodules: a custom integration, a custom board view, and a custom item view — demonstrating the full breadth of Monday.com app development.

## 🚀 Submodules

### 1. Custom Integration (`custom-integration`)
Listens on Monday.com item column changes and syncs data to MongoDB.

- Built with **Node.js**, **Express.js**, **MongoDB**, **Mongoose**, **GraphQL**
- - Custom Monday.com integration recipes (workflow blocks) with actions "store in MongoDB" and "update in MongoDB"
  - - Webhook-driven architecture with ngrok for development tunneling
   
    - ### 2. Custom Item View (`custom-item-view`)
    - Displays item details from Monday.com boards and allows editing.
   
    - - Built with **React.js** and **Bootstrap**
      - - Shows item details from Monday.com boards and enables in-app editing
       
        - ### 3. Custom Board (`custom-board`)
        - Displays board items in a custom table format.
       
        - - Built with **React**, **Bootstrap**, **ka-table**
          - - Shows item name, status, and description in an interactive table
           
            - ## 🛠 Tech Stack
           
            - | Layer | Technology |
            - |---|---|
            - | Server | Node.js, Express.js |
            - | Frontend | React.js |
            - | Database | MongoDB Atlas |
            - | ODM | Mongoose |
            - | API | Monday.com GraphQL API |
            - | SDK | Monday SDK (JS) |
            - | UI | Bootstrap, ka-table, Monday UI |
            - | Dev Tool | ngrok (local tunneling) |
           
            - ## 📦 Languages
           
            - - JavaScript (primary)
             
              - ## 📚 Libraries & Techniques
             
              - - **GraphQL** — communicates with the Monday.com API for queries and mutations
                - - **Monday SDK** — accesses Monday.com account data from both client and server side
                  - - **Express-GraphQL** — local testing endpoint for all GraphQL queries and mutations
                    - - **Mongoose** — MongoDB ODM for item model creation and storage
                      - - **ngrok** — exposes local server publicly for webhook testing
                        - - **Monday UI / Bootstrap / ka-table** — consistent, accessible Monday.com-styled UI
                          - - **Monday Integration Recipes** — custom workflow blocks with custom actions
                           
                            - ## ⚙️ Setup & Installation
                           
                            - Each submodule has its own setup steps. See the individual repository READMEs:
                           
                            - - [custom-integration](https://github.com/moathmushtaha/custom-integration) — Node.js webhook server + MongoDB sync
                              - - [custom-item-view](https://github.com/moathmushtaha/custom-item-view) — React item detail view
                                - - [custom-board](https://github.com/moathmushtaha/custom-board) — React board table view
                                 
                                  - General setup:
                                  - ```bash
                                    git clone --recurse-submodules https://github.com/moathmushtaha/custom-monday-app.git
                                    cd custom-monday-app
                                    # Follow each submodule's README
                                    ```

                                    ## 💡 Skills Demonstrated

                                    - **Monday.com platform development** — custom apps, integrations, item views, board views
                                    - - **Full-stack JavaScript** — Node.js backend + React frontend
                                      - - **GraphQL** — API communication via queries and mutations
                                        - - **MongoDB / Mongoose** — NoSQL data modeling and CRUD
                                          - - **Webhook architecture** — event-driven integration patterns
                                            - - **Third-party SaaS integration** — connecting external databases to workplace tools
                                              - - **Git submodules** — multi-repository project organization
                                               
                                                - ## 👤 Author
                                               
                                                - **Moath A. Mushtaha**
                                                - - GitHub: [@moathmushtaha](https://github.com/moathmushtaha)
                                                 
                                                  - ## 📄 License
                                                 
                                                  - MIT
