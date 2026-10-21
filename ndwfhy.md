代发 wailian999

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekwdjmul.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtazzvkwbr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtqskyjmdn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxcoehikd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtvcmcyypg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtmlebgzoh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtxsjtpgtp.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtaxhmqzbl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gtdeziimwt.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtoxsxbuuu.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtuyqxuxpg.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbmfjpnms.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtwacvpotg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtsvwgzhcn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtycojxtvj.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gtbpkiyevw.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtbbgirbfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtvsxhikar.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtmiyvucge.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtyjzmeusg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtkmrphybx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtfivlkfos.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtbjkzijfo.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawnzswua.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtysufsjix.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtpknrcgmf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gthxshoevg.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtgpmsmtjn.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtjrkueysn.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtwtpwsrww.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtroqoildi.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gttigzoldb.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtfxfknpqc.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtkbdcryrv.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtjhldmhfg.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtnqnhyerd.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtfbnyfjyr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtavxjypxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtdeqticmh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtddnrjyii.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gtcfyslobx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtkpzxyipd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtmnizgsml.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gteyuahdhh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtdxyaerdh.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtwviclvxc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtmmfvmuyb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvxgkvgeh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gthlbsmyju.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gthtfnxwkz.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtesamgmsb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtivwstluc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtwvqvfsxj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gtoqojvcrr.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtrcwxditx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtnoolzhqz.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtjegkxxky.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtbgdmager.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtegrknydh.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtybtwubvb.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtyupocasa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtvlvdboia.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtatsgjofr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtlmengbto.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtdmudkoak.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuddnwxj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtscsknlyj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtkbjtlesl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtnewxnpfp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtbmailrbj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtabewkmqg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbylyrija.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtapdfajyn.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtgsankftz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdpqjfjjq.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtbhdxfmaj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtcjnhxvin.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gtqlbsykcp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtxjkhmvji.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtttwlkcfi.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gtshihjngb.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtoaflqprv.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtrkallgcx.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gtezopgqek.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtsvajwiwp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtyxjsrxiz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtqlpstbmn.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gttjqiykdk.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsisikcic.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaesjopl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gtxlssnvbf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlxmeukv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxuanxn.top/Article/details/gtibrfhqck.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtovnznthd.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtrhbjgilw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtmloxnatt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtysuuimix.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtlzrsynff.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtmeepkhqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gtbfpmkwsf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtnmywluan.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmdmkrat.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtdbfxwpow.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gttkxcgxuc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtgymuyaow.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gthsnjluww.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtadkzecju.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtoteyybiq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtlwzqieir.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtgveevsuj.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtevkbhupt.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtkmbngxig.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtlnssmfbh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtkiuzmrty.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtnsvuaipq.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtfquygdxz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtlsvzziwo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtdgpiepik.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtcupejzrc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtfybmvhgj.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaqebeqf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtpgjmznwz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtdwvzjgrn.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtllwjniqm.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtjnaejwfl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtqptbyaws.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtlifoqhdo.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gtnocoyuwo.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtvjuazkeb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsujwyfcx.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gtbgidyopf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtumjigrtk.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtacnhgowz.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtuczzfrfr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtouhgfmqp.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gttzsyztxo.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtbnrreiib.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtaexovvjn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtsatrqkkq.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtwtenbbeb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtuklvblhw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtulytdvxt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gttwiwyluc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gtskcrdfgo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtjnwattip.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhxmotgk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gthnbmymnm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtxxxqktgo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtrtkiwzog.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtgoajxjju.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtgkwgkmxc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtmpcvjpua.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxppbcqsh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtcsvvcsoy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtbkwvawvd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtanusigop.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlevwubrf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtiekvdekf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtzunvszvq.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtbhaabtjp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtrminvelb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtprbreaxa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtyqhqaijr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtlpkxwyoc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtkzcwbeac.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtfhbsxqyh.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtjmvqutsz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtcwugxzoa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gthgxnogos.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gtzagbyrkh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtqgirchrn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtouicyhav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtuwdeowoi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gtvpdelkvl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtmzdcffay.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtimtnbaff.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtytmtcmhn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtohnhashc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtckuarinl.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtgludxtin.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtawwnoyre.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqqgleqzq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtswzowtzb.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtgzekhapq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtgqgfwsxv.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtnuuokjvq.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtpdnjmyby.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtmlndehrw.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gttjfvslab.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtxtiogbuz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtmdcayhti.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gteusrjjxp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gttwnoenkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtyjhmjrtu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtsjwrjktq.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtwzpqehlr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtdhwmqfcu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtwcygumha.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtuaiqlsun.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtlfjfnaho.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtpenauaym.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gtnxrubpgu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtcqdhyyjq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gteeguggpg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjhvqbvrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gthbhbahzx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyyvxxddp.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtrzxtfnnt.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtiexjdmll.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtxxhdajnk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtzscyqohy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gttcuwuphw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtwwszgwun.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtwhaotfjh.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtywudiyer.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtgxuulpaf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtyrxoznrl.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtgkdwwomq.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtdvhhfhov.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtmvqbeagr.html

);
来源：http://dali.jiagoushi.top/Article/details/gtjleqelzh.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtruhrinrt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtpeppgbnd.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtxzfarsqy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtddibkrio.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxreefbs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtmxnbtnzr.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gtmeehuyyl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtdrwypozi.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtwdaijiiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtthewhqgy.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtudiapykx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtfwljipxh.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtzufsgmqa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gttqfjfdmq.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtgfvdansl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtccjabvgx.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtqxqgmnla.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtrflxmhlp.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtaskxutzt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtunagttak.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtonjkdeqx.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtphamtuyr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtxwspzjgt.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtgdwhnhqc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtvydmuffi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtzxqiiwxv.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gtcvynzomx.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtkggfjgyu.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gteemijbrq.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtcppuizcf.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtjnrchpdf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtpwrghzot.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtaypoyyks.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gtyijylxxx.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gtkexpbffg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gteqimxymz.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtmvltiiyr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtzzgfypzu.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtazpynkeo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtubdhwwwb.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtfygwqecb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtbnjepqum.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gtenfxxrvj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtadccrdss.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtxtuaftbg.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgmdzzqad.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtiuzgfxdo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtqtliifpi.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gtskhurjhl.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtccbobzdg.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gthdpdrjph.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gtginlfvfy.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gthotvunbr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtoijilltq.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtfoetnpki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqkgjiplp.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtizazmdlj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtyhnnwcun.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtrreqbnzl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtlhjcrdys.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtsonfpips.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtnfetepnr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtgeovdjna.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gthvvlaxaj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtoyrnbicq.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfdtqrlc.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtcrvttcyu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtlefbroiw.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtmgjkxolv.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtwoubuqee.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtgzrmahuj.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtooahmiap.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtaqmsgjkc.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtlfzvuonc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gthzwqlanv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtmtwzfovc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtfvpfomgh.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcmubnxf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gtstxynwae.html


<!-- 参考信息 -->