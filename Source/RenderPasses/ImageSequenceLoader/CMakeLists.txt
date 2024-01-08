add_plugin(ImageSequenceLoader)

target_sources(ImageSequenceLoader PRIVATE
    ImageSequenceLoader.cpp
    ImageSequenceLoader.h
)

target_source_group(ImageSequenceLoader "RenderPasses")
