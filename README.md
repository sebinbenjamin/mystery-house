# Mystery House Exercise

Welcome to the Mystery House! Your mission is to explore every room in the house, find hidden items, and discover a secret code. Use the Linux commands provided to navigate through directories, create files, and solve the mystery.


Here’s how you can structure the improved instructions in a `README.md` file for your GitHub repository:


# Mystery House Exercise

Welcome to the Mystery House! Your mission is to explore every room in the house, find hidden items, and uncover a secret code. Use the Linux commands provided to navigate through directories, create files, and solve the mystery.

## Getting Started

Follow these steps to set up the Mystery House exercise on your machine.

### Step 1: Download the Mystery House Files

Use the following command to download the Mystery House setup files to your machine:

```bash
curl -L https://github.com/sebinbenjamin/mystery-house/archive/refs/heads/main.zip -o mystery-house.zip
```

### Step 2: Unzip the Files

Unzip the downloaded files to set up the directory structure on your machine:

```bash
unzip mystery-house.zip
```

### Step 3: Start the Exercise

With the files set up, it's time to begin your exploration of the Mystery House. Follow the instructions below to navigate through the directories and uncover the secrets within.

## Instructions

### 1. Enter the House

Navigate to the Mystery House directory to start the exercise:

```bash
cd mystery_house
```

### 2. Move Around the House

Use the following commands to explore different rooms and discover clues:

- **Navigate between rooms (directories):** 
  ```bash
  cd <directory_name>
  ```
- **Move back to the previous room:** 
  ```bash
  cd ../
  ```
- **Return to the entrance (home directory):** 
  ```bash
  cd ~
  ```
- **Return to the root of the house:** 
  ```bash
  cd /
  ```

### 3. List the Contents of Each Room

Discover what’s inside each room (directory):

```bash
ls
```

### 4. Interact with Items

- **Create new rooms (directories) or items (files):** 
  - Create a directory:
    ```bash
    mkdir <directory_name>
    ```
  - Create a file:
    ```bash
    touch <file_name>
    ```
- **Copy items:** 
  ```bash
  cp <source> <destination>
  ```
- **Move items:** 
  ```bash
  mv <source> <destination>
  ```
- **Delete items:** 
  ```bash
  rm <file_name> or rm -r <directory_name>
  ```

### 5. Uncover Clues

View the contents of files:

```bash
cat <file_name>
```

### 6. Track Your Location

Print the current directory:

```bash
pwd
```

## Goal

Your mission is to explore every room in the Mystery House, find hidden items, and uncover a secret code. Use the commands provided to navigate, create, move, and delete files and directories as you solve the mystery!

Good luck, and have fun exploring the Mystery House!
