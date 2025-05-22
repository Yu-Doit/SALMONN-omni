# SALMONN-omni

SALMONN-omni demonstrates strong performance in complex conversational scenarios, including turn-taking, backchanneling, echo cancellation and context-dependent barge-in, with further improvements achieved through reinforcement learning.

Some demo conversations between user and SALMONN-omni are provided in the following video

[Click to watch the demo video. (Please click this link to download the video)](./demos/demo.mp4)

Specifically, the video presents five conversations showcasing SALMONN-omni’s ability to handle diverse conversational dynamics, such as context-dependent barge-ins, context-independent barge-ins, backchanneling, and *etc*. **Please click the links to download the conversations**.

- [demo-1.wav](./demos/true-contextual-dependent-1.wav): This two-person conversation demonstrates the model’s ability to handle contextual-dependent barge-in. The user says, “Okay, who is your favorite artist? Can you introduce something about him?”—a contextually relevant interruption that cuts off the model.
- [demo-2.wav](./demos/true-contextual-dependent-2.wav): This two-person conversation demonstrates the model’s ability to handle contextual-dependent barge-in. The user says, “Okay, what about Guangzhou? Tell me some place to have fun in Guangzhou.”—a contextually relevant interruption that cuts off the model.
- [demo-3.wav](./demos/true-contextual-independent-1.wav): This three-person conversation demonstrates the model’s ability to handle contextual-independent barge-in by the third person. The third person says, “Please stop talking right now.” to interrupt the model.
- [demo-4.wav](./demos/true-contextual-independent-2.wav): This two-person conversation demonstrates the model’s ability to handle contextual-independent barge-in by the user and resume the perious dialogue after being awaken again. The user says, “Oh, be silent please.” to interrupt the model. After a short silence, the user asks, “What do you think is interesting in the deep sea?” to continue the previous conversation.
- [demo-5.wav](./demos/false-contextual-dependent.wav): This three-person conversation demonstrates the model’s ability to avoid being interrupted by off-topic questions. The third person asks, “Do you like pineapple?”—a contextually irrelevant question that should not cut off the model.

Backchanneling occurs randomly in some of the conversations.
