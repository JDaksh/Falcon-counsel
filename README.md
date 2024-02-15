# Falcon counsel
 This is a therapy focused chatbot created using Falcon-7B-Instruct finetuned on the counsel-chat dataset.

Kept this prompt structure:
  prompt = f"""
  ###Instruction: You are a trained mental therapist, answer the following question correctly.
  If you don't have an answer, respond 'I'm afraid I can't answer this question.'


  ###Question: {question}


  ###Response:


  """
Example Responses (prompts taken from the Depression-Instruct dataset):
Question:
i am afraid i will fail again
Response:
I understand that restarting a task after failing can be challenging, and feeling afraid of failing again is common. Your mental therapy training has prepared you to face these challenges head-on, and you are capable of learning from them. If you feel unsure or fearful about relapsing, it's perfectly acceptable to admit that you might not have the response some resources suggest you possess. 

Remember, you are here to support your healing journey, and seeking help when needed is a sign of strength. Feel free to express your concerns or ask for assistance in navigating these difficult emotions. I'm here to provide you with guidance and support throughout this process. Remember, you do not walk this path alone. 

Question:
What is the meaning of anxiety and depression?
Response:
Anxiety and depression are complex emotions that can vary from person to person. They usually arise from a combination of biological, psychological, and environmental factors.

  Biological aspects can include imbalances in brain chemicals, such as neurotransmitters, genetic predispositions, or abnormalities in brain structure, which may contribute to their development. Psychological factors often play a role, including past traumatic experiences, coping mechanisms, and underlying insecurities. Environmental factors, like chronic stress, trauma, abuse, significant life changes, or lack of social support, can significantly impact their onset and duration.

  It's essential to remember that everyone's experience with these feelings is unique, and seeking help from a qualified professional is always recommended. If you or someone you know is struggling with anxiety or depression, reaching out to a mental health specialist is crucial to receiving appropriate treatment and support. Remember, it's okay to ask for help, and there are people who care and want to assist you on your journey to well-being. All rights are reserved; any information not verified by a licensed medical professional should be questioned. Please consult a doctor or other qualified authority if you have concerns about your emotional state.



