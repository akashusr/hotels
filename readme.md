# Contributing to Hotels Repository for Final Assignment

Welcome to the Hotels Repository for creating Final Assignment data! Thank you for your interest in contributing. This guide will help you add new hotel entries to the project.

## How to Add a New Hotel
To contribute a new hotel, follow these steps:

### Step 1: Fork the Repository
1. Navigate to the [Hotels Repository](https://github.com/akashusr/hotels/fork).
2. Click the **Fork** button at the top right to create a copy of the repository in your GitHub account.

### Step 2: Clone Your Forked Repository
Open your terminal and clone your forked repository:
```bash
$ git clone https://github.com/akashusr/hotels.git
$ cd hotels
```

### Step 3: Create a New Branch
Create a branch for your changes:
```bash
$ git checkout -b add-new-hotel-yourUserName
```

### Step 4: Add a New Hotel Entry
1. Open the relevant file or directory where hotel data is stored (e.g., `hotels.json`).
2. Add a new hotel entry using the following format:

```json
{
    "name": "Hotel Sunshine",
    "location": "Los Angeles, California, USA",
    "description": "Experience unparalleled comfort and convenience at Hotel Sunshine, nestled in the vibrant heart of Los Angeles. Enjoy spacious rooms equipped with modern amenities, complimentary high-speed Wi-Fi, and stunning city views. Our dedicated staff ensures a memorable stay with personalized services and easy access to local attractions.",
    "owner": "John Doe",
    "pricePerNight": "120",
    "totalGuests": 9,
    "totalBeds": 6,
    "totalRooms": 7,
    "availableRooms": 5,
    "thumbNailUrl": "https://images.unsplash.com/photo-1566073771259-6a8506099945?q=80&w=2940&auto=format&fit=crop",
    "gallery": [
        "https://images.unsplash.com/photo-1618773928121-c32242e63f39?q=80&w=2940&auto=format&fit=crop",
        "https://images.unsplash.com/photo-1595576508898-0ad5c879a061?q=80&w=2940&auto=format&fit=crop",
        "https://images.unsplash.com/photo-1512918728675-ed5a9ecdebfd?q=80&w=2940&auto=format&fit=crop",
        "https://images.unsplash.com/photo-1578683010236-d716f9a3f461?q=80&w=2940&auto=format&fit=crop"
    ],
    "amenities": ["Beach access", "Free Wi-Fi", "Fitness Center"]
}
```

### Field Descriptions
| Field           | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| `name`          | The name of the hotel.                                                      |
| `location`      | The location of the hotel (City, State, Country).                          |
| `description`   | A brief description highlighting the features and services of the hotel.   |
| `owner`         | The name of the hotel owner.                                               |
| `pricePerNight` | The price per night in USD.                                                |
| `totalGuests`   | The maximum number of guests the hotel can accommodate.                    |
| `totalBeds`     | The total number of beds available.                                        |
| `totalRooms`    | The total number of rooms.                                                 |
| `availableRooms`| The current number of rooms available.                                     |
| `thumbNailUrl`  | A URL link to the thumbnail image of the hotel.                            |
| `gallery`       | An array of URLs for additional hotel images.                              |
| `amenities`     | A list of amenities offered by the hotel.                                  |

### Step 5: Commit Your Changes
```bash
$ git add .
$ git commit -m "Add Hotel Sunshine"
```

### Step 6: Push Your Changes
Push your branch to your forked repository:
```bash
$ git push origin add-new-hotel
```

### Step 7: Create a Pull Request
1. Go to the original [Hotels Repository](https://github.com/akashusr/hotels).
2. Click the **New Pull Request** button.
3. Select your branch and submit the pull request.

### Additional Guidelines
- Ensure all fields are filled correctly and that URLs point to valid resources.
- Use descriptive commit messages.

Thank you for contributing to the Hotels Repository! We appreciate your support.

