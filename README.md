
Quantization is a powerful technique used to optimize machine learning models for inference, particularly in environments with limited computational resources such as mobile devices or edge nodes. The primary goal of quantization is to reduce the precision of the model’s numerical parameters, thereby reducing memory usage and improving computational efficiency. Two prevalent methods of implementing quantization in the context of machine learning are Quantization-aware Training (QAT) and Post-training Quantization (PTQ).

Quantization-Aware Training (QAT)
Quantization-aware Training (QAT) involves incorporating quantization into the model during the training process itself. This method allows the model to adapt to the lower precision and typically results in higher accuracy compared to models quantized after training
