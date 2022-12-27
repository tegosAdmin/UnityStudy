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
