# Single header speex resampler

I've been looking around for a easy to use resampler which doesn't come with a whole lot of dependecies.

The one included in speexdsp fits the bill but needs a few files and has one compilation unit, which is not too much of a problem.

Still for ease of use this class wraps it all up and can be used like the original resampler.

The member functions do not have the speex_resampler_ prefix and since it's a class there's no need to pass a resampler state struct.