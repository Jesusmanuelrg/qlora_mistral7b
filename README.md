# QLORA Finetuning from scratch for Mistral 7B + Perplexity

In this project I will perform a finetuning from scratch on Mistral 7B, particularly a QLORA, then compare the finetuned version and the base one making an example generation; and finally run the perplexity test to see the improvement after the training.

#

> **Disclaimer:**
> It's important to notice that to perform this training I have used GPU, particularly the T4 from NVIDIA that can be used for *"free"* in google colab. In case of not being able to use any free provider or not having access to GPU, I recommend running a smaller model in the CPU.


## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Jesusmanuelrg/qlora_mistral7b.git
    ```
2. Navigate to the project directory:
    ```bash
    cd qlora_mistral7b
    ```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for details.
