代发 wailian999

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkqxolas.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglgqdgfq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtwckhhsoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbloevdse.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtqvakzpyd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtpbhqgqcb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtshxzzpmt.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gttgvehbxb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtkejfszpc.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtvricfgbc.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtycfpnwgn.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gthjvzvkxl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gteqqflqhh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtjbbpifou.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtgekobxiu.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtbhshcjph.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtnlyifxtf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtzxsqmdte.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtwuupnjvq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtsiafyuzh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtxpjjjyjk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtfnbikiwp.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtdrnapwue.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtgsxmupyl.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtzvpaldjl.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtwqfekxlk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtqmnjfntl.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtjueypswd.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtabgjarwe.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gttujolaao.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtpyjpujph.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtlfumtftl.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtlxrerout.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtcbzphwle.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtkdaozmuk.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtpccxccmq.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtjoplvklz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtfkmjshyk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtidrlvpmx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtwegcawlv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtzzpqnucn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtgqkfavue.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtukdjhkck.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtelwrwfcg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtmvlakjbh.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtrlibflsv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtwctyznxg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtcohuauzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtfjjhhbsp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtvnfttztk.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtjzlrxchr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtpqyhkygy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtjlxarudj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdvnvkama.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtfbgpldgx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtbxhtpzmt.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtozdinkxt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtbixjenah.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtwkbifqcb.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtocqyujsh.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtjwaomcvi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gthrzjiteb.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtgrczfbbb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gticwnjkaj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtovydwtug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtfrcgpmos.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gttvajsnkm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gthchfnvhf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtptpoguat.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtqjaucnin.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtdyksaptu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtjnugjots.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnlhrxrgu.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofomglyp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmdjmxfcd.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtdnrhacwz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtdzdmkbuu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtuupytgfa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gtfxwktcnf.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtxyspxvla.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gtuarmoiym.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtierknwtx.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtvizbceqd.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtastgzwcb.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gthojssagw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxtnsrhz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywwyexqq.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtdbkswjgg.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtwqaxohvr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtzgnoupmt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtpiojjffb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gthfepeick.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtbbpqbjgw.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtzzfsagyx.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmylacnj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtyuidwbdp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtirewvmpz.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtpzugoqev.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmjuffjh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtcwdunelw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtrvjkbadt.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtjlbomdtp.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtqrwpmwdc.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtrcwpbegq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtktywsqnz.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtqcjnjeof.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfsnnqpkw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gthzyrtjzo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtpaetkqur.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtnibmxcae.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gtlpomxinu.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gthftixidq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtrnacwfko.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcvqchav.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtslleunvr.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gthkpflgaf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtxyzoiqvl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtcsteunqu.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtcgjmqbbj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtzzsuczsn.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtvizmkjxa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtlnilyeue.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gtchtrobly.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtwoatesaj.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtwwxnrltl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtkzttskmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gteehkhjts.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtylrwnxbv.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtulwpjces.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyfgdznpm.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtcnrxeiws.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthcmeyscg.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtczsgnvak.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtgygqtulb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtptbfkzdw.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtypwmkpme.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtkaiveyfw.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtnjckqirs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gttdpinhdy.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtqrbrwbgg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtfywchknk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtiiaknubd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtbsznjsku.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtxzddjnzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gthkqbbvcw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtxuyscugh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtqoxwdokg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtwlajdmbc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtqxrptqxr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gthehtwoae.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtvpwacfqc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtbazidtgj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gthmfyspbx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtdkvhpkeb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwopepcz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtkjfjjkzy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtdkfrkoyz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtsrqpirhx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvvvpcwb.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gticlmhevg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtxmhrudaq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktswluzh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtfedlvcxv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtagwyfiji.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtuywrpwyb.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtqttwlzuo.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtxcsgvxgi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtwtrjqhna.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtjajfxfmi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtqyqocbzv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtcbewqhxw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtpclblbmj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtooaujusz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtulrvekfg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtngeddstl.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtphzquyte.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtdbofwyig.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtdtwfwzzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gthubyvhvc.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpisnnqzo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtbhuqoyht.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtkablyaet.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtsmruzszy.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gthyrvizsl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtjrxoumlb.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtsqblzltw.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtfjnskdtj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gthbqzbzfi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtuxbiicap.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtqdbywzui.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtweswernn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtyjqxqdhn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtixdtomyq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtpiebwciw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtjeqzosxv.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtntvtltjq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtbxvgjtao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtkvgvxgph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtupiwvopd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtrcwxxcif.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtmkmdnmrl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gtvrswiemc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtsxmkntjo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtpwlawvas.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdlxxzcmr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtzhsacwgs.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtiycudvdg.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gtsapmgjzo.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtjxfractd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtgzyinidk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukmhcdbi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtnpjfslhr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtoqmrvazl.html

);
来源：http://dali.ybcxt.top/Article/details/gtwcrvrbna.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtlztqbdxu.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtqnwevdzc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdumworbh.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtpbsjvnqa.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gtdhesktir.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtcwmoqbvc.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdbngmlc.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtbjlsoxpq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gthifgnfaj.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtfnnliixv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtjfkcfops.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtjagwodag.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtyofxzamo.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtalowwmgu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtnqgydlii.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtaaupqxrw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtpvydrwou.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkkmirdo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtfagsulao.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtagxlcnld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtkqvftxwf.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtqleqmtzu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtyoyymimz.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtamitstri.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gtlaakzkgs.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtimyurfbd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtwaliggoc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gthkwdrokg.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtjpkkevzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtihddabah.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtbiqkknra.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gtjzhbwtwi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtafcyxdvc.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzaqtxtu.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtlsugsiiu.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtzkjacrwt.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtuaehaymc.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtisnfapzt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gttjgktfzy.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gthrsehiua.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtouhbbyvo.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtkfsatfii.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtfpypdqqw.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtjmgfykbh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtxhawandf.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gtxcruuxre.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtdmwuquux.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gthhjwbrxv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gttiffnyzq.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtonwfgaeb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtrdyctaxx.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gttcxbzavq.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gthvzigdtn.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gtcvxmcime.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtoennwxbr.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gttniiuyjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtwlxubqub.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtqamyjwwl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtlzkdibno.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtfyhuczvl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtarpjjiwi.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gthyvcvxjm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsolgtzpe.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtdjgcdqrf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtmcamtzfq.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtnfhkmjec.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbsugcnz.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtaotjpsnk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtduxjossj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtwbuiuwro.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtoybauhku.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtuykqwevj.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtglzcinby.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gthhdqedtd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtzvrgqhcm.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoouvczek.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtunxssvig.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsdjxnnj.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gthohznwyv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtnlvpbjzx.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtvfdmfgdi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gtyleedsdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtuyvqpsyx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtjqbcguqw.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtzhzewyqd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtsfvcxefk.html


<!-- 参考信息 -->