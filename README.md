# yt-transcript-service

A FastAPI service to fetch YouTube video transcripts using youtube_transcript_api.

## Usage

- Start the server:
  ```sh
  uvicorn main:app --host 0.0.0.0 --port 10000
  ```
- Endpoint:
  - `GET /transcript/?video_id=VIDEO_ID`

## Deployment

- Deploy to Render or Railway with the above start command.
- Set up CORS as needed for frontend integration. 