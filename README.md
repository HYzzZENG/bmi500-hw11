## Student Information

Name: Zeng
Contact: heungzeng@gmail.com
Question Answered: HW1

---

## Key Insights

The SIR model shows a characteristic infection wave driven by the interaction between susceptible and infectious populations. When the basic reproduction number is large, infections grow rapidly, peak, and then decline as more individuals recover. Introducing an exposed compartment in the SEIR model delays the peak and produces smoother dynamics. Adding births and deaths can generate recurrent waves rather than a single outbreak. Parameter changes, especially in transmission and recovery rates, strongly affect peak size, timing, and total number of infections, illustrating fundamental trade offs in epidemic control.

---

## Comparative Model Performance

The basic SIR model is simple and easy to interpret, and it works well for a single short term outbreak in a closed population. The SEIR model better captures diseases with a latent period between exposure and infectiousness. When births and deaths are included, the system can sustain repeated waves. Varying parameters across models highlights how different structural assumptions influence trajectories and long term outcomes.

---

## Relevance to Model-Based Machine Learning

These epidemic models are clear examples of model based machine learning because they start from explicit assumptions about how the underlying system works. Instead of fitting a purely data driven black box, we stick to ODEs. Parameters such as transmission and recovery rates can be estimated from data and interpreted in meaningful ways. This structure enables simulation, counterfactual reasoning, and uncertainty analysis. The approach illustrates how strong inductive biases, encoded as mechanistic models, can complement or guide more flexible statistical or machine learning methods.

---

## Suggestions for Future Modeling Improvements

This reminds me of scientific machine learning, where mechanistic models and neural networks are combined. For example, instead of learning dynamics purely from data, neural operator approaches learn mappings between function spaces, such as initial conditions or parameters and the full temporal–spatial evolution of SIR or SEIR states. Once trained on simulated or real trajectories, a neural operator can act as a fast surrogate for the differential equation solver, enabling rapid scenario analysis, real-time forecasting, and uncertainty quantification, while still remaining grounded in the underlying epidemic structure defined by compartmental models.

– “Disclaimer: [GPT5] was/were used to complete
HW # HW1Eii, I asked GPT to optimize my code
