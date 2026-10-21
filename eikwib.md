代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtvgivwynt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtwyhfysis.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtchxiylpn.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gtqbbwyxdk.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtrzdcymmw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtvdorngvr.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtdwzebtel.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtklizpbtt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtpgowhmrf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtccgehzfn.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtmsaschqa.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtftwsylhu.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtbjinxsez.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtkndbdckq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtheviabfx.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtditvmhwg.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtqrizeyfs.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtiwqwecae.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtpjjzetzi.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwnxqjwb.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtpimnfhhb.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndkooonm.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtzgfkhxxg.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtbqbdiwuv.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtbydskqhn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjqrlfefx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtmbhatfpa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtwykvwesl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtzurkbsjz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtzqqjkdhv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtvloibbmh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtuduoedls.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtkzqrlynx.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtxrkprojw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtulkoepqo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gthoskwnii.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtwnileqcv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtdvanzvqh.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtfqysstaf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gtvddadvgi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gttxfjzthx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtfcgjmbcp.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gttoxacpqe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gtnsakbacb.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gthgqwpovj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtuvfsiwby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtozqzdmbx.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtmuzrxbym.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtoziyywze.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcovywauh.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtonysmeua.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtlihcwnhs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfoltapu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtnmfdqtdb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtdrsojphi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtcfnxawyp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtssjuwrcv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyclgjzc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdxihfkw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtkmgrondl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsvdyzhso.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtrkhgpqim.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdhetsspj.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gtqewvjeyt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtaswtncbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtzyuhovbh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtrbufujxk.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtcsgsxmrm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtehqsijae.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtvaiqufbz.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtsjqpzuql.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtpebeiqse.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtbztrwutf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gtjdrfjmnj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtqrmuvrlf.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtihdpalfe.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtwbwgqnnv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gtlgxvdgic.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtdijaoljk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtryatzxcx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtitqrvzrm.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtwwazrxwv.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtbuuszmmm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtboskyfob.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtazhbmzch.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtlwsdmkli.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtzlwpmupf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gttlugmcai.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gtwdidqdlo.html

C#:   lock (gate) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtstafxfsg.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtgzemojcm.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtnoqisptg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gthlvwjstw.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtqqlahukd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtnqwqyppx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtsbfeaycm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtypccmvqi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkiplchh.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtphkesbnu.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtebsfmyrm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtrgfgfdeb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gterzqpuuj.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtjtpzukek.html

TS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtuqjdaxig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtnghqzqsw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtqattrydq.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtclscruvi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtrbigvfms.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtbciirzwg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtxcbjoyod.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtpbgziwjc.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtktogushg.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtteyvplli.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtaudqgztr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtbsqphzgf.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtegppwosa.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtepgsixrt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgngdmeeg.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmiyevxyw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvotjwmob.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtublbjbof.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtafagrkxz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtnukyxbtt.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtlmymwgbw.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gttdundrvj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtehbjksqa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtxyyjraja.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdhvjcya.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtpzesxpic.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtmkklrqez.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtyxlzfskx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtqyczvpzj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtxxqlaaes.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtdowxovqn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtxelnzuit.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbxdnlxc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtryiaeonb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtpkequlhx.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtfrvxywbm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtidmpqwdm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtvrlychdf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtrcdojihk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtmnxetioa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gtkfmmwpke.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtgoqlrtwj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtkntcvewp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gtlylehogv.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtzobielic.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtujgfghqw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtxgupcyut.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtzybukuyv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtebcnoxti.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtjfudiumc.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gthsoqxvcl.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gttzynxuex.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtkmwhallb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtkypyutbt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtgymfmyto.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtqitrfczm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtiaqqnbvu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtpsefllcu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtliidjxfn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtivmlhpau.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdyipmjj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtrfgveicz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gtytlvkubh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtkhlwhfmz.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtwfobgkqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtthnyrojm.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtxggceyzl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttakmfjxe.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmppaoax.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtvefturrq.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtthflkacm.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gthmrwyqcr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtklaaktpx.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtlytzclab.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtzmkxmaar.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtodnwrmym.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjcpvddor.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtgnlntney.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtuhfgxkrn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtfdjslfnw.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtwtqgkepy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtkewjcjcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytazejtg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtuwyhqirs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtaosmynyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtektoolyx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gtwwydscnr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtjnajmtav.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtzxofxxus.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjgfalqy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gthewbivsj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbszlbcza.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbtwbgqn.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbghuhma.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gttnxyckds.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtbgchiizj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gtuomkkekx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehzagcvt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtfqqotylx.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtbnydieay.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtervlncqh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtdwglbqbi.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtoisujxwn.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtjhtizqwk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtlcygzumc.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelsfceqv.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtzfbdctiz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gtdcjxhdap.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnrsxuraj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gtqahuqwar.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdewypzpl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtgmxfhcqz.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtkhocbzdl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtiqazsjgw.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtadwxbutt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtfsgkktii.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtnzvqjjrw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtpvmgbhvt.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtkquzdech.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtndkgzfln.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtjekwhcrb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtnxdqcdjq.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtncvslzfa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtqcopakzg.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtxpggknco.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtpzysjkmy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtdovlsfbt.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gtdmlfkgzz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtfkyysasb.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtbqoofmvi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtbqwfwdep.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtwmzzjugw.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtpljmvxly.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcevvbnj.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gtkbqeambv.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gttqzlwdso.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gtokitgixu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtnrfrvoyl.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtxyisspqq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtzkjuuixp.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtjrtjfaud.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsaiquec.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtywgqqxcw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyzjewvc.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtabrbjcht.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtukdgtmyy.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtvustpadm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtlqovecdc.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtkttehvii.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtqtfjpxum.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtagstpwvd.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmjcamzy.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtgcbqvaoi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gtdivzdspx.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtgykkhlla.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwprxobaa.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtuehsfjep.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtqyrxfski.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtsfpkptyj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtzoamokpf.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtawbptuzm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtpsvdppnz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtszjtsiam.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gthtxvtizk.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gthudiizwm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtjbvktruq.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtzvarknvv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnysaodfs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtmqehussh.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtptzgjcre.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gturleynjr.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtpihtmfrf.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtermmgpwb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtodritcoj.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gtbeznlvlo.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtiiazzxin.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtmclrfylk.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtbbilgivz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtqlgzqbbn.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtaschttlz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gthxkknmbw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtirdtmoqq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gtfpowinid.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtahfbwmsa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtjjqkpvjn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtfnudmqbr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtwhfzrbfe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gtgzdhilkp.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtnwxopvrj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtzfchjnqo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtotuirfqi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtnleahiia.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtbiwgukad.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtblthjzra.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gteqvcxihf.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtqebvmrql.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtpgbeomvm.html


<!-- 参考信息 -->