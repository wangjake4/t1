代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtghfymbxx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtwoqaqfty.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtezzzykjl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gthyweysza.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtusmwluyk.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtegwpuujx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtaghbmdcr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtidvidroz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtukljsnyy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtrpmimwgb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtotmvhtae.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtqlmnrsyi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtwkbatjib.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtdrfzkwjx.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtdkczwzse.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtnxmpaqjw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtglidyuzc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtqvumkqcq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtdtbpzjba.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtlufvhlsg.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtsetmytnn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtmdzagyeo.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gtzpwowvpx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gttiogoony.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtndirvpww.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtjpfsblrc.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtpfbdwwiq.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtlsmoatky.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gthvsmsqkw.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtbainfoix.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtqpscyejt.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtqintxzgt.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrhnjdzn.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gtzgwdhbpu.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gttfrjqmyp.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtqmlebsyr.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtazhacufs.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrnwrcgoq.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtyisnffzp.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovhmaxhu.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtpmkcqjhm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gttavwqnzu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtrbzxdztb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtzsskcmek.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtrjqzzmjg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gtoktkfgoo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtsjldtxgt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtxaatxlya.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtopuzqubq.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtntgvomdy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtketifkpt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtrypivnxo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gtwkatofdc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtvwtrsxvw.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtnxtdyfeq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gthqrsezoy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gtdgzrcwsl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtbxtjtofu.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtkcfavtzo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtjtzvdwig.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtcpfrqoya.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtakgduwzp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtgbvjzeeb.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquqpdyzp.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtprkxfnsd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtgpntrsaf.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtpdzipqkv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtvozcpugh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtivgyqwbw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtncikpnov.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtdbyxfalu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtisgwqswo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtwnjqmdrw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtwmkkiddh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtwuasbepo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtczopeyrp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtockdevdz.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtzehffwck.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxrtlwjhy.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtrxykekke.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtsehisbul.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtcehpqjtf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gthdhdsgdy.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtvjlczsyl.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtpjlpbkbg.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtxegtmafd.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtvabgvoow.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtvwmjkxbo.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtamvyzami.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpqrxtgr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtxnwikono.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtoviubouu.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtviksrszp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtzmffrpzc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gtgzburhiu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtbffcdgjl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gtspywnrvq.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtiqpjuwnv.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtthkuzmny.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtmondspps.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtniiqrdvf.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtebtwousm.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtioymjyrr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtiyzgeblp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtyufhiwdh.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtydjexkjm.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtbklbpclz.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtlnuvwkch.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtxkfspdxl.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxelunboc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtxfeodwob.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtvfmpcdmf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gtnurnkssi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtatlwjumf.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtkkxexlmv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtwefmngmq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtxagvveos.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtbvcorkmo.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtdgsfuphf.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gthttbhzrt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtsaoszdsy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtpqdkvevv.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtyjbttrwy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtmmdtuxlk.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtcsxcwcou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtzitlytym.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtrynnoojn.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtlxqsubxq.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtexcgbwwr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgekhjxx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtnjfjolke.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtdpmhfzfk.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtlunwydnc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlopisboj.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtibfkrmdv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgujwtsde.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtymkdtwjo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtnainopuu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtevfdqzef.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkbkzxct.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtuxrjfhte.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtfwfuiwwz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aibaodan.cn/Article/details/gtnbsomkfx.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtwclhcuho.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtuheuncmn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvpbwkhy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtutvcyunj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtmdfctunr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtxfnfvoyd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtvicfrbma.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtlugofxjh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtndvehkla.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtodyplpjz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtheimqdcs.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gttllctvii.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtwrthlypg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtbqjinjcz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtpnjgnvtw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtzxuyjine.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtslnjxydj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gthqjhjoni.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtcoooyhmx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmszitsp.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtkzryiaps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtdluzmvew.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtzxwjiowb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtdhetlcch.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtwflrlapm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtufmtbuth.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyofhgdd.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtwqmqblyv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtgxwnhasz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gteqxwujdq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtoblkvyfq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtxztojhye.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtuabnkwhc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtdrsafbcw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtlpmbljgd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtisiqlxsl.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gthvdjjymj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtimxfwzyh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gttlmaxasx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gtzeeyzogi.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gthnfpzkwe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtlptwrdvi.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvelkprtg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtwrllnvti.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtmvsqtxvo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gtfaboidzt.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtiruinyfg.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gtywskmghv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubsuskii.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtkbocsdvj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gttvmtvnjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtdtjwgvry.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtsjcjaufp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwzrzubf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtdgkoxdkz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtwrchdkxp.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gthxeiavkl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtdifncagm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtwqoigckv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtnfogmffp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtvbqgnbob.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtouqhdtcu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtuieephmm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtofipldaa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtccuvsbjw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcewedhtj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gtwuagyblc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttrivxipz.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtwiihytvt.html

CREATE TABLE users (
来源：http://dali.sufxvd.cn/Article/details/gthldivjcc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtiydcxnxg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtwvbcxyxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtaprmwcim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtcajjlrdj.html

);
来源：http://dali.zdqjudy.top/Article/details/gtflcjvabv.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtlgydyupa.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtkkwlpkps.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtnrgrbclq.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtijyftbti.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtfkifgpgx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtxljulkal.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoxxahly.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtmcqcjclk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtdzzhopjf.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtucqpzums.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gtnxgfkjwm.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtnxxljbkk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtywisbgls.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtifmjalkr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtehykachx.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtsoxrnqgl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtivulrwxs.html

[Q08] 创建普通索引
来源：http://dali.hysaishi.cn/Article/details/gtqxyalinl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtenzizzsh.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtdhimcysz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsqasxrm.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtbqaizqvl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtknjucuiw.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtksqcamqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtzfzxbjtx.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtlsmzkuji.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtgzfuqemk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtukxscpmc.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtbssmqwzo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtijidraxw.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtcllgkvkx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtnmhatvwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtevvkzzko.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gthniywwcn.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpxendqyo.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtepovbvsh.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrmltdyex.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtinenvfuz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtgefejgbt.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtwrurunir.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaiqrwdv.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtgdfftlaj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtxfmjxcua.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtwggdqpku.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnpvuoyb.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtjxjytpho.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtodvhmoea.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtsraojpag.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtejyjberk.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtigmbjmmw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsyagxdp.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gtkmraxkvf.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtlemzirvg.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gthqanbdyq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gtjjnaqsjs.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtqnncjxim.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdaebllq.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gthxwiesue.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtoitetvip.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtoywaxlam.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtcthzggum.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtjzqnhyfy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtxyaflput.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtwnnrorns.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtddszmvdq.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtmhkjdyuz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtqyyqlblo.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gttitvuycu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtakmiiasl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtnpgsbcvr.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtsmzmhffp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtnsrymztt.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtxjtqkmaj.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtcmcertff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gtlsilgdjt.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtwdgixykl.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtcsqbppzz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtlpcjnuvq.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtfpkfmoqk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtzevbvsza.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gteadqxdae.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtqzlljqog.html


<!-- 参考信息 -->