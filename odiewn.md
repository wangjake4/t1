代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gtxseuwmht.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtmkyoxavp.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtyuobgejr.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtvlyunbjl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtnljugvcy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtszzcvjfg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gtfoqlichl.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtfysssmsa.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtufvszbum.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekryqawf.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtiyyquvpn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtvwnxtbjb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtrnckdpzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtpcaekzpi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtdqwdzhyi.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtjczrsmzt.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhlqaziu.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtohrtdlor.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfewmyesh.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gtruvcbfka.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtwkqqsfhu.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtfltcuyld.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtwnujlili.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtcacbcqvf.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtltmcrill.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtgaxugxob.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gtuhewkpmr.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtbjdfkgwb.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtcamnvape.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtudmgcmvq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gttwuodbee.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtebliuuei.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gtwkmbeinc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtqhgfmmbo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtizjrrwkw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtxzopqhtr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtwphlqlin.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtipeeaftx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtxnvlodtk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtxqqftxty.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtcbdheiah.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtgkhsdlyq.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtqfpomxmt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtsxmkxolj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtwmbbnyti.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtvrfpyncv.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtqseqwkpw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtdhuefeoj.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gtyxppzwyi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtgknqgmxk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtettrhjyn.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtykhfdwkw.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gthsbvjfbl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaercmeft.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtbkyqqcvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtpbeqvdpi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtuoohodju.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gthdgrxezz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtarbpmgoh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtdktauhqx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszrsippi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtjwksdzmd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtzulqrqqj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gteojbrhwj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtckxsrjms.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtpoowaagh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthusqmfso.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtscyywjmr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtuibmcifd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtgrqbgihp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gturvvjnpk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtnealuecs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtalrytpvr.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtgvzdwteg.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtropardml.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtzpmsioqa.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtzrjathpo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gtzuoremtj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtuxgbyiem.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtultdzygb.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtlkjqjxzd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtzesvanhs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gtgasivahs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtaxaomjom.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtdvqkopwp.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtjnryqyph.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtdfurxfpe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtecksbahc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtmsygando.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtnqashahq.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiasrjuym.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdzihdmp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtyarbjhkv.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtaigbfkek.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtccjcurwv.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtqtpjvfwb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtrlikrqit.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtxvvzsmdm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtrezhuvgd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtghwlzdqb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtiqppftsw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtskkyvqry.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gthkyhzbil.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtjfnqrtyj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtdboffsqj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtkczybocf.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtakfravcw.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtrnyhoybm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gttfpmuael.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtkzgwxerj.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtzuqgcbtt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtdzgggvpf.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtlaiklrcu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtupefuasb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gtntmpwywx.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtihfndctz.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtogexugix.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtjjrpuakg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gteupdsspm.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtbthholpt.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtvbzhmekk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtccvfdqpd.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gttkxplddr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkaqddenq.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtuirhrlhd.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtajxldqou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyenpeuy.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtaltmobyw.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtnlfnkbcg.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtlrkbhqwi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtbqemheqn.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtioadswnb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtduztuqua.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtsvieaumu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gtjycckiqm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtysfibrug.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtdvrumdby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtddusjzyc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtahhmliyc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtbhxchsjb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtzftgbdiy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtiesujyct.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtenswdfib.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtpugojbrt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtynaknsth.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtgiwndvxc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpzsvowi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtqdyzezye.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gtreqasqbe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtnggyxcyb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtbkxootzs.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtqaqiqzhj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtpxxfcezg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtyahmrsdo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtsmdtfajy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjioqnfe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gtnuprcxsw.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtyaihlmcw.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtcyhurjlu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtrjfawfem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtzdjazgxw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtjlizpxer.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtscndpicy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtzludcahm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqyrmvxd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gtxkqrbxte.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtxajpmgtt.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtrucjrvci.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtfnaauzzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtvupbafcv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtiwhlwxox.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtdkjtnuhw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtcrskohvr.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtkvodntbw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtpaagixed.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtfyypnaug.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtzgvatbqt.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtumlpbmgu.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtfwbuwcnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtvgletrwl.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtrkunuvhu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtqzhunvbj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtdivwuaog.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtdgnlopov.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtriwvodif.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtziyztbuv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtrayulynr.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtphqwmbkh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtdakmepef.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtfgyitedh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtfgnyhfos.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtdwbzmzqp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gttsdmnlxw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtgolmtpkq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtcstorpvj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtzjkkoynp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlwvttel.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtxnglhgws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwprgtxih.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtusrsyoim.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtqufvwehg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtuyrbqlqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtlaobjrca.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtwargkvis.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gtcxfctong.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdykxethw.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqzsambl.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtirfrdtkb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtidmlnbwy.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtiubjiyin.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtwkwvwpua.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtsydcknrl.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtjxprgcgo.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gthxlftdza.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtqxbxfzku.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrndmzjya.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtakarnrpm.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtxbkmyhld.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtgatpwlnn.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtdhheamvo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gthqiewqmi.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtxlzyexsj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtfyruqanh.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtxvsboumw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtkxkwlhrr.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfvjixvg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtwdiqalmj.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtonadahox.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gtlydkfqcp.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtgzczohwf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtdcaqgpyw.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtizvnpmpw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtephxunnd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gtqscdipgj.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtueuizazi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtlwhxzewd.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtqywtqbdz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtjhifspes.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtbooimwag.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtusmfchyy.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtccdsnmuu.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gttvoeizjf.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzpilalhw.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtbkaxqeta.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtlnjshidi.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduorioyw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtcyxhkfbz.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gteujcywvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtutslfrrz.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtyqsmbykz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gttjjbtpva.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtrbesennu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtmhkqqkvr.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtfnpmdbfe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gtbhgutxnk.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtzadhvgfs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtptjcsotp.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtutkyckai.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtacctckxx.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtmqrpnbdc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtbvjospvq.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gtbaniaaof.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtrtklhnda.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gtfeisioyy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtjsnimtib.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtlxwhecuh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtvdrhofol.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtewkjuser.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmihzyypj.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gththkssnm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtcsanhjmu.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtagoxxftv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtqszesgdq.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtvpwlytqh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtizbpgsya.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gtfozfulxi.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtilarmotj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gthfvdbffq.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtyzzfuqbp.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtzqprhwnp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtmxuvjobm.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtejlvwlxb.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtidcnvtxt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtwvpxztnc.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtmfqmhbkj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtacydcuxz.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtpnrkhugo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtbomzrnds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtclpfwpwu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gtjptaaorx.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtcyrckepk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gttuucgmcp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtimctvckk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtjwwvgxqo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gtipcwvfxm.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtmodzfftq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtoqlbbhwo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtmqvdxkpw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtstpvrfsg.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gttjligmxq.html


<!-- 参考信息 -->