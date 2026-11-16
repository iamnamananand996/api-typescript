# Reference
<details><summary><code>client.<a href="/src/Client.ts">listPets</a>({ ...params }) -> PetstoreApi.Pet[]</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.listPets();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `PetstoreApi.ListPetsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetstoreApiClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.<a href="/src/Client.ts">createPet</a>({ ...params }) -> PetstoreApi.Pet</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.createPet({
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `PetstoreApi.NewPet` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetstoreApiClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.<a href="/src/Client.ts">getPet</a>({ ...params }) -> PetstoreApi.Pet</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.getPet({
    petId: "petId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `PetstoreApi.GetPetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetstoreApiClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

