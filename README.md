# Dog Breed Prediction

This project is a machine learning application for predicting dog breeds from images. It uses deep learning techniques to classify images of dogs into their respective breeds.

## Project Structure

- `dog_breed_classifier/` - Main source code for the classifier
  - `main.py` - Entry point for training and prediction
- `train/` - Training images
- `test/` - Test images
- `labels.csv` - CSV file containing image IDs and their corresponding breeds
- `sample_submission.csv` - Sample format for submission

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kanaldekarp/Dog-breed-prediction.git
   cd Dog-breed-prediction
   ```
2. **Install dependencies:**
   (Add your environment setup and dependencies here, e.g., requirements.txt)
   ```bash
   pip install -r requirements.txt
   ```
3. **Train the model:**
   ```bash
   python dog_breed_classifier/main.py --train
   ```
4. **Make predictions:**
   ```bash
   python dog_breed_classifier/main.py --predict
   ```

## Dataset
- The dataset consists of labeled dog images for training and unlabeled images for testing.
- `labels.csv` contains the mapping between image IDs and dog breeds.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)
