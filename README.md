# UnityStudy

これを知る者はこれを好む者に如(し)かず。これを好む者はこれを楽しむ者に如(し)かず

To like is better than to know. To enjoy is better than to like.

## wiki

[wiki](https://github.com/tegosAdmin/UnityStudy/wiki)

## ハマりポイント（stuck in a hole）

* ゲーム画面が真っ暗になった場合は一度タブを閉じると直る
* If the game screen goes black, close the tab once to fix it


### 別のScriptを呼び出す方法（Lesson 3.2 - Make the World Whiz By ５）

``` 
private PlayerController playerControllerScript;
    // Start is called before the first frame update
    void Start()
    {
        playerControllerScript = GameObject.Find("Player").GetComponent<PlayerController>();
    }


