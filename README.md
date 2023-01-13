# UnityStudy

これを知る者はこれを好む者に如(し)かず。これを好む者はこれを楽しむ者に如(し)かず

To like is better than to know. To enjoy is better than to like.

## wiki

[wiki](https://github.com/tegosAdmin/UnityStudy/wiki)

## ハマりポイント（stuck in a hole）

* ゲーム画面が真っ暗になった場合は一度タブを閉じると直る
* If the game screen goes black, close the tab once to fix it

## 豆知識（Trivia）

* ゲーム実行を高速化する方法（How to make your game run faster）
「編集」->「プロジェクト設定」->「Enter Play Mode Options (Experimental)」
![image](https://user-images.githubusercontent.com/92899345/209627673-76e81e48-6d3d-43b1-bd36-f65c5d376bc1.png)


### 別のScriptを呼び出す方法（Script Communication Lesson 3.2 - Make the World Whiz By ５）

``` 
private PlayerController playerControllerScript;
    // Start is called before the first frame update
    void Start()
    {
        playerControllerScript = GameObject.Find("Player").GetComponent<PlayerController>();
    }
```

### Animater 
scroll on mac 「option」 + left click(heavy)

![image](https://user-images.githubusercontent.com/92899345/208812774-a4bb8d6d-62cc-4248-94a7-2723f12da6d1.png)

### User input 
1. Install the Input System package
「menu」「window」->「package manager」->「Input System」
<img width="798" alt="image" src="https://user-images.githubusercontent.com/92899345/212228903-64f202b9-5351-49f2-a09d-53c0d6128d45.png">

2. Add a Player Input component
※ add blank 「Input」Folder and 「Input Action」 謎・・・
![image](https://user-images.githubusercontent.com/92899345/212229408-97a578d1-6676-45f1-abe8-98170a55b202.png)

3. Create a new script
![image](https://user-images.githubusercontent.com/92899345/212229111-f64d0f28-5f3d-450e-b446-be95285cd9f9.png)
4. Write the OnMove function declaration

