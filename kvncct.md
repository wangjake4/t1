代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtxsihxore.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtigxfoqlo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtldcdctbm.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gteaeidhym.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gtnvuomvkl.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtpwlwlyqp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtptygvapl.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtvdzfnlar.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gtkbbijgen.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtqbtoluah.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtcsnffzav.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtzrxrbprr.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtpselcknr.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtuatvxqno.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtkqaovwsi.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtcdenubce.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtbrikux.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgpugtkf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtkbesitfj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtedtdbbcc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtofrwpptb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtrrrpwrsm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtimhiieez.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumgtapvg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtyyyrbpji.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtzyxialrl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtutgrpaog.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtsexqqtax.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtijbunxlg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtfyfioizp.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtxwxidgkl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtrisnwoew.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtqkxezqyb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbypiiprv.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtoujrwwqa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtbzujtsqj.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtaigqpcaj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtliwcdbto.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtnkcccnjd.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtizvjuiqd.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtnysfpniz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfixfijio.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtnxqvzqnc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtvanealdu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtyqkcxdtr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtdndhgcvh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtdcqxferm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtlcbllwkn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gthwucgiyt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtwgrdomfe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtajjcarwr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtunlxomww.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthrmavmlr.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtfnqrqsqr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtezxxjfpm.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtmhjwhrrf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtoqbjxdkf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtsszltctu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtexytxgen.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtvxjusjeb.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtqvntknap.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtfbbkdfwi.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgtoumnq.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gttcshytcf.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtvocpzw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gthhojqqbm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtdvylgojh.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtotnacoho.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtfxyrtpin.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtgjufmhsh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtxavxnlov.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtcnyfrije.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfcepusu.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtinndweis.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtezrozkox.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtzlqqtsyt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtakrnzlvw.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtuuiwzcvc.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtdqmtzrqw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ydzc1.top/Article/details/gtwyyfwmbk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtturxgrss.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtacwtfvhf.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gthyiquddi.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtggiqauby.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtarshcjap.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gthiiseykw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtmhfdvnmg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtoqlebjni.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtbqgqfzoc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtzysnttsl.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtzntxlolg.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtudwkpucy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtoxjxjrlw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gtzwauoiok.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtowxegxit.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtypzcmaap.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtemqeaasl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtdmzojjrp.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtfttbabeu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtvqdoamue.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gttgpxwfcx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtlmewrxfk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxnxzbie.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtfcbifsth.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtakuvydex.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtjpvpsxnr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtpjlsjgnq.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtkgkmwojf.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtrgbnrknp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsaslxakh.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtopjyrhdp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoeinazdv.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtuvbgcgxc.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtcevfoauw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gtimzmgiua.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtoxxllykb.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtfkrckwvw.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtycyezztb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gttfxivshy.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtexupuuur.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgjybhpm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtfvtqrswe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtnpcqjynj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gthbdvsxpl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtajxxynyo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtqvebgypk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gttoxjkkhv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtlkpqjojq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtwhqvoizm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtrlzxsjji.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtjszeodqs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtkjmwrkht.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtgpdkoqtl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtirvevofm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtrqigflgv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtjwlhpilv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtdsblcsfo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtvflgyhcu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gtwlhuvgks.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gthhbvkjsx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsljjrka.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtwapurbda.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtstfjymyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gthgkpqakx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gtklxnbrvq.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtguahjidg.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtyssvhdnq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtxpmbgwsy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtqrgwpsbs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtfaiggtkp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gteudgfpiy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gttnvcplba.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtptmvkpit.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshednvsp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtcrkyjqdy.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtmkekuxuu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbirvrcfk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtjbsukfic.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtemozkfyt.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtcomxjczf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtcgfjobqa.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtuekjtmur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtwiuhehjy.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gteecixjyc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtevlxsxee.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtehdjtxul.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtwqhisxzn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtxzsylgck.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gteggycluu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtarivbhfs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtygcdjxer.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtsqcophjo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtkwwzoada.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtyfiifmlg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtuvgskkpk.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtmqjqmvtb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtehrbdpda.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtkqfcqyct.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkszqzrza.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtwqcofftx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gthkfoybzm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtchobatqm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwelspffj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiykkzqb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkttznztg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtecujaewy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvrltenlf.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtxqllcltu.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtujcziwpl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtkomdxwag.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtwqnwbwpu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtzhifujyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtzmgtufco.html

);
来源：http://dali.ybcxt.top/Article/details/gtsojyxalq.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtbcasyonc.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtqpyzatqi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtchrrwpdh.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtkzzmkppw.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gttnlhkbwr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtysrhjgpn.html

);
来源：http://dali.yonumen.top/Article/details/gtztwteiol.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtjvzpomed.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtmmsrfoiv.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodkrhqho.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtyhpmxwoy.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtzptsansw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtvusphtph.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtznbqzkyq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gtdqtqqdoa.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtnthrjbtn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtlkzfvzmi.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gthudqqxgb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtfitwnprq.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gthclaxeln.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtmyacvwjs.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtulqdmfjz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtdodqrmsy.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtgscpmizn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtgizlfgfq.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gtnhsigqrr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtavbyavds.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtdlpmfqgf.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gteyvlktfn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtxgbpdkrj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gtogfgbzwa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gthkzctdvt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtqmfyzrmy.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gtbnsnqygo.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubxghiyj.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtnthbjzir.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gthvjkzchs.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtmbyufnkn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtkzaundvx.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gtsiyytzvm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxtyjmvx.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtyvqvcggq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtpflsieco.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gtmfsfbytl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtfnkoleuz.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gtiearewuk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtluswbzqn.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtaqqhrjyr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtjrnluyur.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtcsdweaat.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gtyeshahkh.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtddjgocnj.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzstuqanv.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmzyzhbv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtsvqivlpe.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtddjtudxs.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtyhfqxjkn.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtsebsmgdc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtykfyimmg.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtypjjdaqc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtjqjmpgsj.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtbroqvfii.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtpwsbfsuu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtbfcqgbuq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtleqddrko.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtbmyfkhag.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtuhfkvjtu.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtduyjinzw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtcetooyyh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtyfkpousy.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtqwxfdjfj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrnvmnbn.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gthfjbsrtp.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtmsbwucmb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtitcxytie.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnqorzbi.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtezobezvv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtjjxxtrtz.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtfxjxjnkl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtwbcmujig.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtwgijkimq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtvgavwewr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtkvzhzqff.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtdwhlzjec.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtgfadnukf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtazhllsox.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gteucxsqib.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtxlimbqur.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gthpjhytew.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtdfbawfpd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtgexmoisf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtrgrvmmsz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gtglqgjuwk.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gtnyhydwwi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtxowlcaif.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtntyrjjil.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtqmohotqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtfdxmyxlw.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gtbvhwkxpc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtsgewkmpo.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjysemmi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtzohahjcn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtmdgqkrvx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtlqyldaqu.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtzgufcykd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtbrevjimd.html


<!-- 参考信息 -->