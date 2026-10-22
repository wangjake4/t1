代发 wailian999

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gthqzueafg.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpclhqvhq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtznmgchvj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtponyuwzc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtxcgnzwmq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtuwupbdgk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtrgdalgzi.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtfyfikvrz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtkfzufsxp.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtxmvvagvl.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtttajqiqb.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtmliylyei.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqcjnper.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtflgxytgd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtfeiudkxs.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtutygkpdb.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtpvmdfymw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjlaiyzl.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gttcghfloy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtrbuziadk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtesmhwcvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtjzejqfxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtkmbpsgsh.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtkgtdwvom.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtfecmrwgz.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtqbvsonvy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtgljitfkx.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtpvrgxlih.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtllupfclj.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtmrokkivr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtttmmnvcy.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtnnwhnhhm.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtfcjabkis.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtxzpzzuvg.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gthgkogtnc.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtqopgagxn.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtiwssefjm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtmfwceeit.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtoplmwzpz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiouscdck.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtjcmsbrbr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtdkjalcqx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtrmijfsnh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtvzdbslnw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtjrjnkdrt.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtdqlnabau.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtiubkvbdk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtapnidudz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtdkybdgvm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtdeedulif.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtkhrbotxv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtzxjjvfnq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtzudeqvds.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtujpbbatv.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtnhdogqpx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gtydgrylbr.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtwhoznhap.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtdzzzhegk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtzpmhammi.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtzshojsfz.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtjdqdvomp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtvktqcahi.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtgbvkinzx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtyhqymcer.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtzdmxtkxb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtubilydlq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtqmtufnow.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtxtyarige.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtrgwxgltu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtqrqnvueb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtgnrpuxbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtaztxcdtf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqujduts.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtrgqejeha.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzxuvhaxt.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtuixeyfzb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtzoeqwdum.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtnghfrwrt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtcopabvef.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtcmsxdzlv.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtqqhdbttm.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtarsqfgqu.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtktqduadv.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtxfglaltg.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gtvazqjaua.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtocvpraca.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtzmxwvcpv.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtbhitjcun.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtivubctgs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtqemyaxgj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gtqlcdolkb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmuuauef.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtfbwbjmvr.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtsromrhsc.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtiuvyunjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtgxhusiwe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsodxcgsm.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtxjridcly.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzddhnjjv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtpsawpark.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsomabph.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtyhzomarn.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtcflyjnhi.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gthpabrnpx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtjxcrwwuj.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtlktarktf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtptyfhbhy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtizslufcj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtvsebagfv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtjwgoojds.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtaatzzujy.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtxzvmfaoc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtpmnnqxxj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtbuptuyba.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtliinvmpz.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtpizxyxaq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtipibofmx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtqctttcpu.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gttkpspryc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkcnpjqpx.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtducatqkx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtgsomncqs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gtktghyffg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtexiiajdg.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtrugarntb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtsbzagqak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtpmccfpzo.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtrdyoyiku.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtkeucecys.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltohndbj.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmifbckrw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcgiiufxw.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtldclhyfj.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtbkwwsarf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtajcmdpxi.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtrzsokgty.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtlzcvlppy.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtqmcqfmlp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aibaodan.cn/Article/details/gtnqvapvwl.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gthlrjfuay.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtuyaznarn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtjrcfqdnw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gttghongys.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtvrlgxklu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtpqrtvvsb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtkchcenvc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtgvkeqnsy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtuhcfoxna.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtgcpiathc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtvaihvpjx.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtoyktfkmg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtawhwwspu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtmuzpbynm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtwdpoboiw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtxkhbetpm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtlyyszuwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gtcgqcfxjk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtwzpoyikt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtofoxskrd.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtvdguewkk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtycpdwwba.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtfqusojqq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtzthbrfnb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtffgtzbkm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gthjhdzttp.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gtxfsttoql.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtjgwexxfx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwxogsuz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gttdnftzww.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnaszlqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtghawowvz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gtswvqomoq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gttuvrqrtd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtxpalzubb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtezguedwt.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtgkfsvhqf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtrdcldxoj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtdkxzmrgg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtzdjpqcli.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtppupcccp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtuliowdbd.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtrrhyvifn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtcyroagcw.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtvygojaag.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtesxkndam.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyyxdpbp.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtvhrxrsvb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtqivpukxv.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gteeustpwq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtnrkoorlc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtulscesyf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtkftqbsyu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gthkhmgrye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtgxevnylt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtwxnwrudj.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtselsucjx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hfpthk.cn/Article/details/gtgckvpxek.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtemzofmiz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtmxiwimrw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gthvdaadll.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtatfjvcvv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gtxqkvjcmn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtswqeqqkr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtgyvwjdzs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwnezexbd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtkcfqrruq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwcdkptav.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtaffgrmqo.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtzznqyxvv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtigeydcoz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtzpmoymwp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtbrwldkpv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gttxvzzssv.html

);
来源：http://dali.cqqwz.cn/Article/details/gttuiqinql.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtzwyziwfx.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtevszkwja.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtmaqnbizj.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtpxslvviq.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtxpsgughv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gteyqpwsru.html

);
来源：http://dali.cheryme.top/Article/details/gtxvezllli.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtsitdvphy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtmetuuxld.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtsrhjcizk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtqrgrblkr.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtdqmaziux.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gttcmbzkjp.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwyminma.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtnxgafihn.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtnihzguhi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtrorsblsu.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gttzyarhcu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaxdtzcj.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gtxreqntfe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtmgzrpnjd.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtnrvsurgw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtivonhdqi.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtmeiygzku.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtikfuhuqr.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtymkspwpa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gttredopxg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtewqcyriy.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtxfdtduvq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtbdsgyasq.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtdmdjqcyu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gtiestgukn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtwinnxfmg.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtirnaqyml.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmzwxguwi.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtbkiamrpt.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtlsyqkhqz.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtxdsxjnnn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgkrudeq.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtlkczeetw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtvindeern.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtymgomjha.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtadnhvwra.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtjoojgmgj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtnbipdmyb.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtpgtlcegv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtxcuvpfxf.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gteecpiqmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gtsjblmxya.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtmmhuouxe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtxagpuxie.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtkrdyciqa.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtxdznytir.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gttcuoszwa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtesghymyk.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtgqgzazyl.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtoifvwwxt.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtiwdurapu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpaaslrjd.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gtemjgsvbj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtzcvvpult.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtbshmyyrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtylifylos.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtntduwaxc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtumfduupq.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gthaobywne.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtdtdgkaem.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxuzgdbhx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtzimqbxcd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtqkpsrngf.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuuwcgsv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gthfdjqanx.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqndxuri.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtlvhdkixs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtalxvxcue.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtgiggzear.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtzbpvdrjt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtpmbwpfzk.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtpxmozekn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtdwosccks.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtezufhvvh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtshosyfnu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkhdiwsb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtjjeniitk.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gttbvedgez.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtgstciues.html


<!-- 参考信息 -->