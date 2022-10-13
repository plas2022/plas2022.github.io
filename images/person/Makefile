PEOPLE := marco danfeng

PEOPLE_IMAGES := $(PEOPLE:%=%.jpeg)
PEOPLE_THUMBS := $(PEOPLE:%=thumbs/%.jpeg)

thumbs: $(PEOPLE_THUMBS)

thumbs/%.jpeg: %.jpeg
	python3 utility-face-thumbnailer/thumbnail_faces.py \
		$*.jpeg thumbs/$*.jpeg \
		--width 400 --height 500
