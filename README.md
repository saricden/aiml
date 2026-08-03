# AIML - Artificial Intelligence Markup Language

An idea I had for a way to represent and transmit conversations or even coding sessions with LLMs between clients.

## Chat & Prompt Tag

```
<chat model="gemma4:e4b-mlx">
  <prompt msg="What is the capital of BC?">
    The capital of British Columbia (BC), Canada, is Victoria.

    <prompt msg="Is the Empress Hotel there?">
        Yes, there is!

        The most famous one is the Fairmont Empress, which is located in Victoria, British Columbia. It is a very iconic and historic hotel.

        <prompt msg="...">
          ...
        </prompt>
    </prompt>
  </prompt>
</chat>
```
