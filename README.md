### reactive-streams-jvm
---
https://github.com/reactive-streams/reactive-streams-jvm/

```java
public interface Subscriber<T> {
  public void onSubscribe();
  public void onNext(T t);
  public void onError(Throwable t);
  public void onComplete();
}

public interface Subscription {
  public void request(long n);
  public void cancel();
}

public interface Processor<T, R> extends Subscriber<T>, Publisher<R> {
}


```

```
```

```
```
