uv run bin/gopro-dashboard.py \
  --use-fit-only \
  --fit fitfiletools.fit \
  --profile quicktime \
  --overlay-size 1920x1080 \
  --font "PingFang-Regular.ttf" \
  --layout xml \
  --layout-xml "my-layout.xml" \
  --units-speed kph \
  test.mov

uv run bin/gopro-dashboard.py \
  --use-gpx-only \
  --gpx 198233449.gpx \
  --profile quicktime \
  --overlay-size 1920x1080 \
  --font "PingFang-Regular.ttf" \
  --layout xml \
  --layout-xml "my-layout.xml" \
  --units-speed kph \
  111.mov