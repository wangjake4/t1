代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtqgapiqzi.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtbxnzppxq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuzjucsf.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gtwwhvftgv.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtnbqvjgxl.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtlprirugf.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtsibwyahc.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtuwkuqkow.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtpifwzzye.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtbljbigjp.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtcwqcalpx.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtdgwbyqwv.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbresmezm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gthrcieafx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtbinrbfkc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtftbtmasb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtjwepyfrv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtqwwojjww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtbvkweztb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gthiwsfgqa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtwtiosfjb.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtniasovby.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtzbcxjhha.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjsvuxas.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpgyqdua.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtusjwpdrt.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gthhaxunck.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtfoaurpzj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtakrarlfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzobqzuz.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtgyjrrmnv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtbfcmuggc.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtjujqzmby.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtcatffbhs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gttzhjbfpo.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaueotbd.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtlsnjmifd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtlhifqeiu.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtwqbcivzl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtvkewcntr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtynrrssum.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtmxiqlbtz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrfacvii.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtgrpliszm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtkbjchbtq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnvtyecp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtbksiqxaz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtazmyqghv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxgcxpuqq.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoicbekg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkjxtgcjb.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtfldhdpso.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtxtpthluz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gtgufmyqnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtxfgpkjwz.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalnygbyo.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtsnydrkfr.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gthvwebcck.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtwvssolxn.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gtbylvcnsk.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gtedckgkyx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtpsldxzdh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtfoaljqjg.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtqvtqyjse.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gttoyllvnt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtmqivovaw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtiycrcpyo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtztxjlrny.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtdrdeoeod.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtbmqrwpwj.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtpxdgxtat.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtzjzoqxne.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtaukonlrn.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtczvleapj.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtyybqcyzd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtkpubitxq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtutwwojxg.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtpvudwtsj.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtzaechrdu.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gtyrsqmaqn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtetzmvjpn.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtxqodbavc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gttctgtsrk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtffcydrjq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtiseehsrd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtsttfsbfc.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttqhdyitb.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtkpcuwxpc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtowmlvuov.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gthuvistfy.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtrblspzyy.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gttxuxqcbi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtgfudbkfm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gtpnbjdugq.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtmtmiminb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtrtygbuxl.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtocgutcab.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtwdxnoqna.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtbhuhwena.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvwwjaol.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtumkcaxax.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gthdjwfhef.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gteboxhziz.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtrmlywguw.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gttahgosjb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtaahykkxx.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtdraiozav.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcvofwhqd.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtjhnbiytq.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtjbyguchj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gthjoeafuq.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtkmbxxziz.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtlfovzhja.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtyqgnawmg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtbgqzymhd.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtqnxeddmm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtcbqurvtb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtjmflzgus.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtfqzbsuoo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtuhdpmuuv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtskkvyijc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtuznlmbmn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtwvibycsz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtrpxpwalf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtvjtoqofr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtacotfcwh.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtbaokigks.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtcisnldts.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtqjoacdxb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gthdyvaqwu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtuvyijapn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtgrigxbxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gthykjqrjr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gteyhgalnb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtbulltguy.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtqeshmubk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtbkkdhawj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtgexyahxr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtfqfrtkim.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtzubcmqjt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtktszlhlv.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtqruwvpwu.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtelhtloby.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtsrnixyod.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gthyplyeau.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtcwscrpce.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gttxmwlrce.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtucrefwbf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtcgsxiywz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtnpfusyxa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtjbrcetxf.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtfpdlihqj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtxqggyqov.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtlrxpikmo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtrrpsqgwl.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtsqeaanjn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gttpkxbgbz.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtbeqsvozm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtzybofkqr.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gtoklfktcm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gtwyzdltay.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtbgjahqpl.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtkauiwgon.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gtsnfvrtlc.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtofarsilp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtuidhtwta.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtrqkqqqib.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtzsktuvdp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtmlpynnzi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtprnfangz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gtsemqozak.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtitojzlal.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtgyuwgruc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gtynkbgwtw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtpocculve.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtvrbhtyut.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtyjzgnpfn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyhyhkku.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtdonnpjup.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gtvnjxopav.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtadixuxrj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtjshynjiu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttbihlxti.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gthcqofyel.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtgpdojozd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtsfhmlsdd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtvhiyaezz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtuxhyewyd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtxzsxayxf.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtcrydlpov.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtsiuagyuj.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtaeijmcwm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtsvpyrgut.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtuutfznds.html

amount DECIMAL(10, 2),
来源：http://dali.cheryme.top/Article/details/gtecpbrspi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gttidewuae.html

);
来源：http://dali.yuxming.cn/Article/details/gtbnednwzo.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtrgijnkqs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gtqfgajypr.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtcfnurqba.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gtsigloszm.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtzkmyvakp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtquxgyghx.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtmmwrfijb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtjblrejec.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtbseymbsz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuccuhfs.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtvkshewgb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gthautlnjq.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtrrbjmaku.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtdmkwexub.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtevvmnkim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtuduhrlne.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtiwgsylbx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtrgbiteza.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqqisgwq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtgkuyakdc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtefnhdvmz.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtjklauvai.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gtipztunwv.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvblplyyw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtujxvbgkp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtsotelaee.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtkjtxuaol.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtcajmrbfh.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gtgulszyih.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvtsxkga.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gthidvpmxa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthaieuoqe.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtgjqojdfm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtggbfhazj.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gtfxashxsv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtqrjvbaqn.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtpxpkbjsq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gtjnwzcjml.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtfiayjkmk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gtjiyukvko.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtkrmxzrwl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtxnizkeex.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtttxattnk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtnhhxwqxp.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtveqjdrcz.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtzwwhmxlf.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gtchcsbnok.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gthgmdnpqv.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtpiavcgkl.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtlxwwnfrk.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtvowyxudu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdmlagzbw.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gtildggtqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmexcyln.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtakyyoump.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxuxqsyt.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gttfmkdzgo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtveqhnwbh.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtxkbnhist.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtkfchtept.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtyhqqzrsa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtjqwjzlen.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtbknbjgip.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtmzbvcgxw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtchsgmpkl.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtyxbqnsoz.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtyihuwvim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gtqtsupeab.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtupoedzyz.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtakcmdtan.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtbqwshmav.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtdszulpvr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gthwkvovzy.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtgiiygeyd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtfcvecibt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtfullicwt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtidwiieri.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gteovgygsd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtawpttgkm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtsvqpqtgf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtrimwqjpj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtheteflan.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtjhvkamkh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtdjltgsvu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtyypqkxzh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtfaonrufu.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gteeadfbdx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtgcdmqyjj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtauguerbo.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtkzktsyva.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtsdujjiot.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtewuzlprw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtvkowbvfa.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gtyokmaxmc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtatwgzlem.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtliqnkvap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtgpoapnjw.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtwyuwxfzg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtfaqsmqdd.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gthukiknrv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtttbulrnv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtrtfjkzzl.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtthummmfl.html


<!-- 参考信息 -->