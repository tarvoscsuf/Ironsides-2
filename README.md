# Ironsides uses OpenAI's GPT3.5 Turbo model as a Discord bot to reply to messages.

This is the public repo version of my Discord bot. If you would like to use Ironsides as your own, simply replace the os.environ with your own tokens. Structure works by adding whatever is said in messages with @Ironsides pinged, adding the prompt (message_content) to the request, and sending it over to OpenAI API for fufillment and output. Simple as.
