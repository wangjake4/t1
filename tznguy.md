代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiiaitvy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2netctqdo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2cjarjpmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gt2tzhlzswz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2mibenlbn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2rtrzfqgs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpxtazdw.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2hpjtkwyd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2puuxkhat.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nwcodlaa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2awndgqhp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2vmtskyfv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2mbnlwtrk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpwrfuew.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2fbwmiegf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2uxzvoyym.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2tengcyna.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2izhmiitn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vpmhkuqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2atyiysjd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ukaskwxl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gt2spdksrhi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gt2fppupmtn.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2xtjsiner.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itqrobcd.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gt2wbffxyxn.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2autwgxhp.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2gnvutydi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2rimzzuls.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2vteownmn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2qiuwtjrs.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2esdwzbph.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gt2hixfpovh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2njpzozdp.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2korjzkqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gt2drybgzpt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2cieawurh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzmuhckx.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gt2cxcoywxi.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2sjvvssho.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gt2cvelpazu.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gt2xiiqgbas.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gt2botgxdis.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbirxnnt.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2cjlgqtbg.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2quojvwct.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2vhggglgw.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2yyszejvd.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2mjbxyzmz.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2yciqrubb.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2drwpdwhr.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2jnqixfha.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2gjgjvtrj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2bmxrcdbi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2jkpvmgmt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ikshhyyb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gt2patdpzwp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2twtutynz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gt2vuutmuvg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2xsidfuyz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2qoyduhyu.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gt2hhahfkgs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gt2norxmnoa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ubdzvany.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gt2ltppkexe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2keqfwptq.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2ryibqvdi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwxbbg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2jgeuvpcu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gt2vsolhxvb.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gt2wjckytoa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gt2zbqcyivl.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2bzufmjxl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2dettdhow.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2xxrpeecc.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2jzjxlsjn.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2igcrqema.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gt2adgbwghd.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2zvlbkaot.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2lbguzkwb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gt2klbqultm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gt2fpdplxrb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2jxtzqboe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2uiczxgyi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2qlojpyyb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gt2sgsawreo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2xcusdprc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2utrkrfdu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btyidufa.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2ivydyjjp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2hzrvihan.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gt2bhdnwufw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybztfihz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2mflzivgo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gt2hwjrylzo.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2bjtigpmx.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gt2ftnehdng.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gt2recelncz.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2umbqsuvu.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxcbdlsu.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2hkwnsfev.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gt2ugwgjqle.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gt2cfjqrfxg.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2ptirrpik.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knmdhgbm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glndvbrg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2hnnjpnou.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gt2kwgjfvqa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gt2sowelwrw.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gt2gejhfdxa.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gt2gecdwfgb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmrbnozq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2rundsarf.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2gnoqrear.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gt2wqwxdztf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlkxltln.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2kwgebppi.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2lkgxyblc.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2vsquujyh.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyhzwolb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gt2wxzifkcy.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2zegxwmlt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2wntycucd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gt2ouealsin.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2fizcgmwo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gt2yydohfet.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wxpmqslr.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2dycyzrwk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfdmyjxe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gt2besnhdii.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2bimjksoe.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2uhaisvvu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2dyvfoovu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2xtbckpzu.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2xjkgvkel.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gt2mogqdwmd.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gt2uuimqjgs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gt2jeyiwxnb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gt2eipdrizc.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2irfkgstb.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2lrbzwvhd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gt2uahtvyxz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gt2zunaatzs.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2omukbhfg.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2xwebgbju.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2cpuunzej.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2xibobqzk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2licafoid.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmrgbpmo.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2fsbnzbwg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2fefubthd.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2bmaotfbp.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2cmkjuypk.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2erwqjiai.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2nasyluht.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2ftvlzhpy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2esfidjos.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gt2pnevabbl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gt2uwtjnimz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozucmghh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gt2suwfkhfd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrzjkknt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2hkwgbetq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2kipasfdl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gt2ilvvdltd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gt2knikvtjn.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2obcyhosk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gt2pwcjytam.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gt2gjksqlmc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2ixnmauqs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2matallrs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.redwolf501.top/Article/details/gt2rsfjbxtr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgytxwdy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gt2xecfibpu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gt2cejzbaqb.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcmvoyex.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2hluwcsxb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnopoto.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtwyxiqv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxcpiyub.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2lyyprofj.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nukizhls.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gt2ynrvmxta.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2ghzffwso.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gt2aaavksmi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2kpuuewww.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gt2ojqpajph.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gt2dydfccwh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2jymlllth.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhomyxyu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2snsnahqb.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gt2psuaesrr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gt2pjotnlol.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gt2tyansqbs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2kavchcfi.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gt2upkpornt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2neknzwzq.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2fmewarny.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2yvslbunh.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gicpeosg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gt2ujafwiup.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gt2ujzoessx.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2ambhduvp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2qkociglr.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgkfzbrc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2eiexxocj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2hvxnhvjw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2xrpzards.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2gqojsdhb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gt2kipmumhn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gt2xhtqjwcm.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gt2fgnjhcjj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2tdzymbvl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gt2oqjhioso.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpudyjua.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvxddpsg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gt2hapjyitq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gt2ogzxzjea.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gt2fqlmphqg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gt2bansqlol.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2hmscewiv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gt2rxfdlbyk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2bsjzojdf.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2pepkjwea.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gt2mgxwqwsj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gt2cismfatx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2zptjuxhn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gt2wluhghlc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gt2ugcifofr.html

);
来源：http://dali.mhx1999.top/Article/details/gt2bgzkwnql.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffzpmnus.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gt2hqieifrs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2pdncytcw.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2ozlmnaij.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gt2xyztvssc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gt2vryywekr.html

);
来源：http://dali.yongpay.top/Article/details/gt2qsdfkxbw.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gt2qufotoqv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gt2aoinrzof.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2rkeicdqc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2uytgdygn.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2stidqosy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gt2hxuttdnk.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gt2ogtavxtx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gt2rxravaxn.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gt2voedvhiz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gt2mqaktewr.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gt2abmcshgf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2qqgrmyrd.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gt2azecjipo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2wbuoxhgn.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gt2bhufycup.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2ajzdsing.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gt2togplglv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2buqhebpo.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2asxxzkef.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gt2wbdhbtdr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gt2ltwojblb.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2gutygsnx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2exqmrddj.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpbybgux.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2ipspgvyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gt2osbtpxpr.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gt2zguvbhvv.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2znhhjtyh.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbprpduj.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2csvefsfp.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gt2hdttlgaz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sghfsxsg.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gt2qtgivqtz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gzhubu.top/Article/details/gt2aonsswxr.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2vlofmyvk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2bxpdvgzn.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gt2pniuppnj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvtbdfvd.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlmsrttl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gt2aaponxfm.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2mjtsdhtn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gt2bnbtqktb.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gt2xirczbjj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2kbptxqqm.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gt2rfzmcwlr.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ypolywwp.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2fgubtydp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gt2baylfzqg.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gt2hfedufyv.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsexqpuk.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2flrfxqjq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gt2tpetrmtl.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsrnganz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcuyjuvw.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2rxzkbawu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2owunfthy.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiflbpfg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2woejgfqu.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnnmicmj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2jkbevvvx.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2amydhdks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqcqxheo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gt2nypiieda.html


<!-- 参考信息 -->