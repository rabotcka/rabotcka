## HELLOOO

```typescript
class About extends Me implements VladimirSim {
  pronouns: string[] = ["he", "him"];
  
  public function getPersonalInfo(): VladimirSettings {
    return {
       agressive: true,
       likes: ["cats", "TypeScript", "JavaScrypt", "yourself"],
       levelSelfish: 99999999, // It's a joke
       has: ["hands", "brain", "121 IQ"]
    };
  }
  
  public function getKnowledge(): string[] {
    return [
      "TypeScript",
      "JavaScript", // <3
      "CoffeeScript",
      "PHP",
      "JAVA",
      "C++",
      "Python3",
      "And more"
    ]
  }
  
  public async getFavoriteThings(): VladimirСharacteristic {
    let lovePromise: Promise<VladimirLove> = await getOneHundredPercentLove();
    return {
      lovePromise,
      bugs: true,
      toxic: "yeah :("
    }
  }
}
