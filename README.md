# foto
Backend for a photo management tool.

## Goals
01. [ ] Extract EXIF/XMP metadata from a photograph.
02. [ ] Generate XMP data and write to a sidecar file.
03. [ ] Build a stoage layer to store this data into sqlite/something else.
04. [ ] Build a gRPC layer to read this data.
05. [ ] Query by image name, geofenced location, timestamp, any other feature from read metadata.
06. [ ] Extract text(s) in image as metadata.
07. [ ] Extract face(s) in image as metadata.
08. [ ] Store face(s) models as "Canonical Face Model" or another appropriate serializable format.
09. [ ] Try identifying what the context in image is about (auto caption).
10. [ ] Query by face, image context, name, text in picture, any other feature.
11. [ ] A daemon to continue doing this on all changes.
