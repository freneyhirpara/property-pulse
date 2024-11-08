Running the Program
Open Terminal: Open a terminal or command prompt and navigate to the folder containing dhke.py.

Run the Program: Use the following command format to execute the script:

```
python dhke.py <IV> <g_e> <g_c> <N_e> <N_c> <x> <gy_modN> <ciphertext> <plaintext>
```

Replace the placeholder values with the actual inputs.

Example Command:

```
python3 dhke.py "B2 2C 53 91 7A AC 5D 8F D6 3A B7 94 54 1C 54 E2" 255 31 255 14445 2100874001 8995936589171851885163650660432521853327227178155593274584417851704581358902 "76 56 21 0B B5 36 21 11 E8 9F 08 E5 53 8F CA DD 24 EE 8F 33 7F 76 86 44 B2 8D 82 BB 53 25 F3 61 5B 06 4C 04 5E 04 17 03 BA FA 17 85 7F 3D 48 60" "AdvancingCryptographyTechniquesFor2024Success"
```

Expected Output: The output will display the decrypted plaintext and the encrypted ciphertext as a comma-separated pair.

```
AdvancingCryptographyTechniquesFor2024Success, 76 56 21 0B B5 36 21 11 E8 9F 08 E5 53 8F CA DD 24 EE 8F 33 7F 76 86 44 B2 8D 82 BB 53 25 F3 61 5B 06 4C 04 5E 04 17 03 BA FA 17 85 7F 3D 48 60
```
