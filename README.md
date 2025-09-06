# Creating-Mechanics-Module-4

<img width="1302" height="658" alt="image" src="https://github.com/user-attachments/assets/59a4a63b-5634-4f2e-99fc-572e3f674d24" />

<img width="1374" height="704" alt="image" src="https://github.com/user-attachments/assets/400d68f8-2dfe-4eaf-b278-8eb1c27c435b" />

Make an actor BP named "BP_Pickup"

<img width="1489" height="808" alt="image" src="https://github.com/user-attachments/assets/5d5d68b4-d44a-4457-9b3d-b28a1f8f4999" />

Make a "Primary Data Asset" named "DA_Item"

<img width="1539" height="844" alt="image" src="https://github.com/user-attachments/assets/d9f49775-3fc5-4226-9753-4979c0c22e5b" />

Make these 4 variables and make that the "Texture 2D" is an object reference.

<img width="1530" height="805" alt="image" src="https://github.com/user-attachments/assets/1ffbed64-492f-4128-889f-6f84800f3881" />

Miscellaneous > Data Set > name it "Item_Keycard"

<img width="1409" height="405" alt="image" src="https://github.com/user-attachments/assets/07b5f0ec-9f2d-4058-b1ab-944c6b1ccf0c" />

Name it and provide a description.

<img width="1827" height="1007" alt="image" src="https://github.com/user-attachments/assets/b59f9586-1eea-47ce-83ba-8d7c3b9d2e89" />

Make a custom static mesh keycard from Modeling mode.

<img width="432" height="787" alt="image" src="https://github.com/user-attachments/assets/6a192d6e-1dee-4cdd-adad-c1edc4b5a6c4" />

<img width="1837" height="720" alt="image" src="https://github.com/user-attachments/assets/0427b16c-69d7-42bb-acea-2c1c9849a355" />

Select AutoUV for the keycard then accept.

<img width="1810" height="950" alt="image" src="https://github.com/user-attachments/assets/6703e96f-550f-4303-8e65-6822579f078d" />

<img width="1214" height="959" alt="image" src="https://github.com/user-attachments/assets/c3bf443b-456c-4ee4-adf8-5057b782c441" />

After adding the keycard's static mesh.

<img width="3438" height="1047" alt="image" src="https://github.com/user-attachments/assets/22699d43-79e2-4c28-b161-80a8ef721fd7" />

Go to BP_Pickup > Add a new variable called "Data Asset" as a "DA-Item"

<img width="944" height="622" alt="image" src="https://github.com/user-attachments/assets/713c80cc-c006-45ce-a6ee-b35f30da7714" />

<img width="2607" height="971" alt="image" src="https://github.com/user-attachments/assets/357e70c9-95cf-4c75-859e-d3d8602dcd54" />

<img width="1019" height="990" alt="image" src="https://github.com/user-attachments/assets/3df07cad-fdff-4256-b179-0947eef2c268" />

<img width="1138" height="790" alt="image" src="https://github.com/user-attachments/assets/dbdfae54-6a72-4677-9bc1-f37415de43e6" />

<img width="1330" height="766" alt="image" src="https://github.com/user-attachments/assets/a7a6d2c0-f245-4bd9-af8a-e02c0b35f6c2" />

<img width="1960" height="1293" alt="image" src="https://github.com/user-attachments/assets/ba212813-418d-4717-a7c0-01f7cb776f7f" />

Drag BP_Pickup and put in the world then select your data asset

<img width="3022" height="517" alt="image" src="https://github.com/user-attachments/assets/2b524eef-a69c-4a17-aa29-d5d5ed77b09a" />

NOW WE WANT THE KEYCARD TO BE INTERACTABLE

<img width="2141" height="974" alt="image" src="https://github.com/user-attachments/assets/31c831de-c805-4dc1-b264-b73bb69514e0" />

Select StaticMesh > Collision Presets > Set to Custom > Change Interactive into Block

<img width="1815" height="932" alt="image" src="https://github.com/user-attachments/assets/15ebd8a4-d924-4b94-a814-a15e1116ec99" />

<img width="1233" height="612" alt="image" src="https://github.com/user-attachments/assets/a13cf417-7666-4246-8cd5-860411c4f223" />

<img width="1125" height="576" alt="image" src="https://github.com/user-attachments/assets/cd0ccb89-2f63-4a63-9682-170d469d5a90" />

You should be able to see your actor component named "InventorySystem".

<img width="3259" height="1310" alt="image" src="https://github.com/user-attachments/assets/0b14588f-951b-4cff-836a-07f1cf6454c8" />

Go to InventorySystem actor component > Make a variable call it as "Content" then assign type as "DA Item".

<img width="1137" height="377" alt="image" src="https://github.com/user-attachments/assets/a458c456-1c6b-45f6-8507-2ab58e80f099" />

Within the Content variable > Change the variable container as "map" > then as a integer.

!!! Whenever you're making a variable. Always think about the functions that you need to manage that variable. !!!

<img width="527" height="378" alt="image" src="https://github.com/user-attachments/assets/da7354d9-dbc9-4c17-b994-129818c81c4e" />

<img width="3439" height="1219" alt="image" src="https://github.com/user-attachments/assets/eb01a6c5-f3a7-44f5-9527-a1a4a9681718" />

Into your AddToInventory function > The Add node basically adds a unique key of a new value (It doesn't 2 new values together it just replaces it).

<img width="2302" height="412" alt="image" src="https://github.com/user-attachments/assets/f77579c8-3a3e-467b-95e3-67ecccdb9e45" />

Click onto your AddToInventory function > Add these two inputs Item for DA Item > Quantity Integer.

<img width="3430" height="1339" alt="image" src="https://github.com/user-attachments/assets/24aab280-73b0-4e77-aa3b-46896f2b518b" />

<img width="3422" height="751" alt="image" src="https://github.com/user-attachments/assets/c87d4178-e189-4ff5-b0ed-ef1a0f39b92b" />

Go to RemoveFromInventory Function > Add two new inputs called "Item" assigned as "DA Item" and "Quantity" assigned as integer.

<img width="613" height="361" alt="image" src="https://github.com/user-attachments/assets/bd3e9126-3a5a-4f27-a1fc-0ec101a52c5d" />

Add Find node > then connect "Item" Input into the "Find" node > then it finds the item.

<img width="3348" height="1219" alt="image" src="https://github.com/user-attachments/assets/026b22a6-1fd3-4827-b5c6-488078dfc921" />

<img width="1094" height="567" alt="image" src="https://github.com/user-attachments/assets/16666755-b5d9-4269-baef-cce434926133" />

<img width="1891" height="948" alt="image" src="https://github.com/user-attachments/assets/4f0fe2d6-041d-48a8-ba7e-ed8bd6dd3c3c" />

<img width="906" height="317" alt="image" src="https://github.com/user-attachments/assets/a63dbaa5-9611-44d7-8105-4cfec0d8a3fa" />

<img width="3439" height="1353" alt="image" src="https://github.com/user-attachments/assets/445357b3-641f-4356-8f5a-2c98c5e12504" />

<img width="946" height="363" alt="image" src="https://github.com/user-attachments/assets/ec559476-52e0-4580-8370-dd37b73fadbb" />

<img width="3433" height="1350" alt="image" src="https://github.com/user-attachments/assets/c5dde303-c281-4e23-8b0c-0371d9598878" />

