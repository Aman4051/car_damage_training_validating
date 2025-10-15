#dataset (contains json file also)
import kagglehub

# Download latest version
path = kagglehub.dataset_download("humansintheloop/car-parts-and-car-damages")

print("Path to dataset files:", path)

#change path if needed in code also
