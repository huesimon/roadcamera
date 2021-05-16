# Roadmap

- [ ] View a list of all roadcameras
- [ ] View a roadcamera with a history of the latest 10 photos
- [ ] Add cameras to a favorites list
- [ ] Cron-job / artisan command to run ever 10 min that stores a copy of the cameras (history view)
- [ ] 

Camera source = https://trafikkort.vejdirektoratet.dk/

## Models

### Camera

- id - integer
- url - string
- name(location) - string
- updated_at - datetime
- created_at - datetime

### CameraFavorite
- camera_id
- user_id
- updated_at - datetime
- created_at - datetime
