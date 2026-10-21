代发 wailian999

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtgdcjtoqk.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtteoxzniv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtyvypoftx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtvzmufwhd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gttcebtdzl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtlyxcjznt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gteivnzped.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtvhkaygpy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gthvvgzhzj.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtzeheppmu.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtygyabwdm.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtplzuxbwn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtkovbbqur.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtopdsysux.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtnqvnrkff.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpyvjlmi.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtrsdxwpjh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtwdeoqlrb.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtypoxjbov.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtrkvmkupx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtogljqisi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtpkjjtbce.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtpciljmts.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtutdukvyy.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtjqpaavxf.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtllclqkai.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gtqkacmfhn.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtqewzsovc.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gthqzfgxpg.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtuseabjoo.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gttkerwhej.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtqzyfwjhx.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtwqmmsfwm.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtvtplajhd.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcocksrjf.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtseisnvnm.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtwhomckba.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtqusthlpk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtvgafxlzu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtocjzgofx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtgtvnegnn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtqbojwsrr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtnlbtqybi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gttacqfzns.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtdlsnuhzm.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtbqvetyll.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtechgzuco.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gtrxktvkik.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtvoijxxzd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtyeehfqqn.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtswouzjid.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtbofwpwmp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtgrueruzd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtjrramxfy.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtrgjcalrj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtxqswqyql.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtaekkbgou.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtubbdsent.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtqvzqccmy.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtieodpxls.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtsarwgghi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtvoyyxetm.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtdqnwsllx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtdnupidrg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtpvkfefht.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtgxomlzuj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtoftsapmh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvhkwpp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtwxfqxwdn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtnvwgxawe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtedslerdl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqgaqvud.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvbueoaph.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtqvmvbwzt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzjoatbti.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtghifbpfq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtqmmjwyyp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtaxnyxvom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtfyrojmuh.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtwzmnjmcm.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtpygrsvko.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtzqeufdkp.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtpeorkjue.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtkdlwaewz.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gttwxsejlb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtzqqjylbp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtguuxyykn.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtujhkupaj.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtneeecixx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtctvrmjcf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtnybkelrl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gtoleyqhyl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymjjzuqk.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtgeqeghji.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtnlbasjdb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtgljavhmi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gtszlzhakg.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtgnrjxpsv.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtqvdzmetu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtnkvygxfx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtaexzcent.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtdvglqusg.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtiywszget.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtyybnnghw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtdjtrqady.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtbbrpbvmt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtctuekufe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gttqqlkcms.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqorxprer.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtncxstlet.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtdgsugxls.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtthqtzjuk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtjppvljoh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtmlgowxyu.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtcqqxtyrx.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gttrvagabg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtclnxmwht.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtdirzjzkg.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtcfxbumja.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtuexbaxut.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gtdogjelwk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtuzklmjdo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtrtozkgnm.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtvngzqfwp.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtykelicnk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtyhpozbdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtgbyabxrt.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtumtawcxc.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtojffmpcg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtojgzuefz.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gttpxhjjfn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtatctrfzo.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtbtzlyhjt.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gthgurhduw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtgcplxszc.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtzrsopkiq.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtuxgyzhja.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gthwzpidfq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gtejyhtbji.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtmhbsmvym.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtrtbhxixq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtcoyspedg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtuvmbeshr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtvmpygpmd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtculirdgc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwdpfhki.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtqfqjsspi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtohepbypb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtgchfevba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtxbhtebyg.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtvsxgkold.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gthcvtlgne.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtlucsnluw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtqboanuus.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gthdfqvmcn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtpoyvfnsi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtwkmhovpe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtefhbkzdi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gttnjylume.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gtfwatgmoj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtlrbvyddp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gthqwxygid.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtvjpylmbr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtltrmnojf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtlnbskvkz.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtjzevpwxz.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtyvjnzqid.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtlrrzxinr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gthfzkngtb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtkcuxmlct.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtfxqmqxva.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjebmefzm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibarjyxc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtiunacdji.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtygmrrsqv.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gtukuikkmd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtinkpzmrn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gtirrxwxnz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtpjxpavfq.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtymcpfqsx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtpapxalcc.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtdcrowwbt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnjwsukbr.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gttxxdqrxg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtnsokdhjl.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtnamcfbry.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrydfaae.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gtilyxgrny.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtnsheoebx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtkgyrchpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtzqufmvjy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtezeaktdb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtjxbrdzqq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtnehiuhtf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtjhpfwqry.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtxhfsnqmw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gtptttxqcv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.meibo888.top/Article/details/gtnrxdzgja.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtlzyfeflb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtjeeirdsq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtkuvvtehe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtqzuhpphz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtifznlbgw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtqzuramtb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkmufrgmn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtbpokmwna.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzgfbjstv.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtfrdwkobb.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gthqrvqpek.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtaqzrxeue.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrijwlguy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtuskirj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnofpdiim.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtetiwczvz.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gtpmkwupfa.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobeuydrz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtbkymdgtb.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtgnwtibvn.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtkxvmwjyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdekaowe.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtiphuhjbl.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtkxrgjmxm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtjgwpoyfy.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gttckirugk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtwcwcteyr.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtmunpmrzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtindgraut.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtkozavdol.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtfxxsmtmd.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtjdolkgme.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gtfeflcljc.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gthqszqgbr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtutthfxrl.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtjyhmjdep.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtxbjsznql.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtmfmgbdjx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtqjzqqmap.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtwffnxlfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtbgdhcgtn.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtsldzmbfe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gttihanfbq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmwspgsb.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gttwsxgvph.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gttxitrnie.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtuazxegxu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtkigvewbm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvduzibdz.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtoaqtxftr.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtlnocwrxn.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtbqxckdky.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtrrkasgue.html

[Q17] 条件查询
来源：http://dali.zhengqikj.top/Article/details/gtjxksqqom.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gtwfdqerof.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtkuhagymj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gttelnsquj.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtxnrtvsvg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkewjzigh.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gtlwgfjslw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gttrvvrtlz.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gticdgafan.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtqlmvjwfz.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtbbunahuh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtkyiudvuj.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtjgmzsypm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtlbpehgxq.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gtksqiwxqe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxffyxatr.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtyyopickf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gtyptzkcyk.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gthtolibbt.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxglyfkbx.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtmzjroeqe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtujdtrree.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtgkopcaao.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtttkwrjjk.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtigegluyy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtyggebkdx.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtliufvvdf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gteqgyrfqk.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gttfwwwyww.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtjhdcfcbw.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtolgscznp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtejchgzhh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtpiecuxhu.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonkppvob.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gtgqpbrqoq.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtgqudnvdc.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtcjlutnsk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtzmgwfkiz.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtvhguilmb.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtfpotiqgo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtpygwufbc.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtpglriawp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtulvcmxgt.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtcvakctxt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtyitkxdyb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtnpzzkarq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gtubslnmiy.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiennwkko.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gtgtgdjpkm.html


<!-- 参考信息 -->