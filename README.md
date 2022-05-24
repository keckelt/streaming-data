# Streaming Data
## Python/FASTAPI ➡ Web/JS

## Usage
```
docker-compose up
```

The backend is running at [localhost:8877](http://localhost:8877/). You can also stream data with `curl http://localhost:8877/`, for example.

The frontend is running at [localhost](http://localhost/) (port 80).


## Resources

* FASTAPI - Creating Streams 
  * Create Streaming Response: https://fastapi.tiangolo.com/advanced/custom-response/#streamingresponse
  * Cancel Streaming Response when Client leaves: https://github.com/tiangolo/fastapi/issues/4146#issuecomment-962800937

* JavaScript - Reading Streams
  * https://developer.mozilla.org/en-US/docs/Web/API/Streams_API/Using_readable_streams
  * https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
  * https://developer.mozilla.org/en-US/docs/Web/API/ReadableStream
  * https://web.dev/fetch-upload-streaming/
  * https://web.dev/streams/
