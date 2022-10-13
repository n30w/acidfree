# Acid Free

## Who?

This project should be maintainable by a programmer who knows Rust and Go, as well as general knowledge on how to refactor code and understand design paradigms.

This project should also be usable by someone who doesn't know programming whatsoever, and is there to complete the job that this software seeks to aid.

## Why?

The entire purpose of this project is to create a framework to solve the metadata problem at the Punahou Digital Archives. Change is slow and the eternal lag that the archives experiences on a yearly basis means a severe lack of digitized works and information on videos.

Abstracting parts of the program to different components is an essential part of creating dependable system infrastructure, and programming in general. Given that I have created a couple working prototypes, most notably MetadataUtility which is able to pull metadata off of YouTube and even work with multiple excel sheets, I can attest that the need to abstract several components into a frontend, backend, and API is essential to work with large scale data such as those to be worked with in the future.

## How?

Implementing a backend will be done with the Go programming language and its various features that makes creating web services easier. Go can be used to send and receive Google Sheets data or YouTube data. Implementing a frontend will be achieved with the Rust programming language, an extremely robust and fast systems programming language using a frontend framework called "Tauri". Therefore, using Go for a backend can ensure solid server-side and API performance, while using a Rust frontend will ensure an extremely responsive and bugless software.

Data returned from the API would be processed locally on the client's computer. This makes operations on the data faster, and with Rust's extreme reliability, data operations will be successful. The API will just be the messenger.

## What?

Libraries and frameworks to be used follows:

### Rust

- Tauri
  - Vue
  - Vue router
- Polars

### Go

- Google sheets API
- Youtube-dl

---

#### What's up with the name?

The name comes from the fact that archival storage boxes must be acid free. Therefore, an API of this nature that handles archival data must also be "acid free".
