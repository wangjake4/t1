代发 wailian999

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtnjgyinuv.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtoygxbfsm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtabkwugoa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtvauqnoie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtktohopac.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gttjsentcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtdrfcdgdi.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtzdpqrzdn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtbomusvbq.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtvswvjokq.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gttyuglscf.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtpcutlozk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvzjvvfu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtfkmexrby.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gteetydtey.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtbrkqkhnz.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtwshhvjap.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtvlavsell.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtuzflzeez.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyarcijgj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtumneyewy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtemjgqcuu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtybndltho.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtbjncdmim.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtccufhcle.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtbhfbolsn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gtgomemmjc.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtkzlkovtj.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtqxlmqgoz.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtlonqrbbn.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtnqkquvki.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtgvmkhfdk.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtkuxwkooj.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtjhgcorwu.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtnbvxddim.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfdjoasj.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtsndjdwlf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtxbigbebv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtfnfweshz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtvqazinwa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtotlfodkb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiiwlqws.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtsphlyucd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gttrftdrzk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtvsrmmxuw.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtncfnmvlx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtcvzbugsp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtugiwjjzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtjywkjujs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtenpskthn.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gttowqmmga.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtezthiovb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtoufvkxoe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtztfumqze.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtgiopanwn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gteiiitnna.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gttfrbnkym.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtnjramiuo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtpmewbhsc.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtlufyazmp.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqtktpkv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtvxwgdnhb.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtcburbyed.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtsbdqddhz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258888.top/Article/details/gtyhjozwna.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gtuyckvoqd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtczjubodz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznbeozpc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtbuzjnbgx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhgxohfq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtpepbrhom.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtaoulxuyn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttjipqpdb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtwfhrjoyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtltuapcgh.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtvhspgvve.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtehnnqrzi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtceoutajo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtstcxzfxc.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtsvxwmdsy.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gthrsaoaav.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtknjittgk.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtccamxxoj.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gthjmcqlky.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtzntvzqtc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtgkxpwbfh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtuehfowmc.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtystspiwf.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtnlccohva.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtnbsktwjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtnfadfgro.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtpucrewsu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtcqiciwkw.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtljmaecrd.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtpnibqrvm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxzhqoyh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtffuclgrp.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtizjopqqm.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtjjnsvcnp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtyfqgcxkl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsnukndb.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtepxzcedk.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtyuovcoui.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtdnbfiveu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtiaggamsf.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtdfwwjlrd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtqktrekyo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtetscxteg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtznagvhgr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtchwqpvlp.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtoirpejwh.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtxrdydfgb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtqaqerids.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gttfyssbfs.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdgwwgcr.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtpdmwujvf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtuayuvvhn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhancezl.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtqyixiciv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtidqmtmko.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtaetuwsea.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtzbtdpiwo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrmmqqkp.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtdppwclwm.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtwxhrrgtb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtjizbrsik.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtlgfotduf.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtblhdluvd.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfrnpghd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjlgwyyme.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxiuouhme.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtndzvfjen.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtznjvzmtd.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtzbazaiec.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtsgvimuiz.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtgbgwhcha.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gttvfodiuc.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtvslwmhmb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gtkyrbvrly.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gtszsufbdl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtrefpbzpm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gtxgrmemgs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtviqgtpas.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtqaoxchmi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtxeutninu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gthllmqezj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtlkzaafiu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtufhvuilv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtxruglhgw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtygpydszf.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtafbfzrwd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtnefncelw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtrymbqxpa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtczepvhaj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtpythbflr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtaditopua.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtpzbhwacr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtswmzhzhv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtwcvedwjc.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtndmhmnjb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtpejinyyx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwcbicfz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtiglwkrwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtktmhfoko.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtpkqaosjg.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtxxbrmyrv.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtkpsnpmiv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtthvxkqwo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gthmrlxnzy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gtpsdfhazf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtiniqhncq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtgovbordx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtaybdqssc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtsphhvfkq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtzfivwrfv.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtkmuglh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtrsgblygr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gtccustttn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtliiclyho.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtaiysxiqm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtqdjilcwl.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtgrxmajtt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtidbxisjr.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtvcobfswb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtgyzbmgrj.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gtifhosdyw.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtsucsxymm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtihahwijr.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gtpapkbqoh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtlplvkhcw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtseimpqvx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtqeodlosj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gthennbcoc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtttiarzhm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtobozriwm.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtkycqrhys.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gthpodaynf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtqtqkbsua.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtilhbsizq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtruzjpdyw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtkkmxnqvy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtvuhpfkgr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtutwmagto.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtotmirhmv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjvsfowcw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gttkjircek.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtczbxdpzk.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtxeabnwua.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtupfogvgb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtkumyjcao.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlldryajk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtqdlsvaoe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtqsxlgitg.html

);
来源：http://dali.cqqwz.cn/Article/details/gtyodwiewy.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagplzcqs.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylulsapa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtythdpzav.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtyssajees.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gteygsdqbe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtabqghkwb.html

);
来源：http://dali.yongpay.top/Article/details/gtcinvqkko.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtnzwjhnfz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyutzgtni.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtrvxqurlm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtzwufxilc.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtyxjxxyvw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtjypgjkgx.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtzalgctgg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtqgknfiir.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtxtupzkcb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeezqski.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gthnayujrt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtuligwnfw.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtorvfsgkb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtspsplhvk.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtzwcppeyw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzxgdhtg.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtlhvgszfn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtgeadwcfu.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtynumsxqm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtmjulcipq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gtblqiibdc.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtjwewiwwm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtjlcqsgoy.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtnhrsxtib.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtymmejyss.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtiqakwmae.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gtufhormyb.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtlmbgdolr.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtzzztjofn.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrimktnsx.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpzukvnz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtdufhvhtp.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gttsifpeue.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtqhbfzdlp.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtxgycxuyq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtianegfho.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gthiqykxwg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtoisfphua.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtbobwhygg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtnhvibhjy.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gtpniscmgt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gtkqfhkmih.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gthlaylpzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtninfymhx.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gthwriipox.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gttigfpyea.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtzxikrqho.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtuwfchngc.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxsuevae.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtuhqussso.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlnfvcns.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjycfhtbj.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtxraudxmr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtsdchzcnw.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtmilhrxtl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtsdpqqacv.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtzwbebwkc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtucnlckkn.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtryehhhmm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtoogpeufd.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtjybldsan.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtbwembpmm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtfyvpopoy.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjygkndih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtbctqntoq.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtimyugbvu.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtkugdwfug.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtzujnairr.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtqnsezwna.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gtdxgvonry.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtzgittlkr.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtfuojvtno.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtshkmnqig.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtfsoirisp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtmrorjuyn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtvuecxirp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtusktfwwk.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtqkkmczfl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtiqdmtxsi.html


<!-- 参考信息 -->