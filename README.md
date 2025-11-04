# assignment1_after-end
Note: If you want to use the mini-program of this project, you only need to call the code in the front-end code repository.

This is the after-end code for Assignment 1 of EE308.
This is the back-end call of this wechat mini-program on the front-end. In fact, when using the cloud development function of the wechat mini-program development platform for this project, it was found that if there is no need to process a large amount of data and traffic, only the server, back-end and database of the cloud development platform need to be used. Therefore, the front end directly calls the cloud database API (wx.cloud.database().collection()) to achieve addition, deletion, modification and query, without the need to set up additional back-end services, simplifying the development process. This repository is designed to demonstrate the code for invoking cloud databases.
