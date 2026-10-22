代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2neilmsxf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2bxyyevyv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gt2iedyoout.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gt2jafvucpo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2jqqadhru.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2pkzmwins.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gt2rgclkxdg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihxwwumt.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gt2salpmgcg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2njeyzvjn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2jvtplzhz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2jpaleubx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2znjlbjfj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2prweduwi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2obqqswtq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gt2zadgwkqe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2hftajznz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2auycvzwl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2iakqmwrh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2hdldsoze.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2yhrdummt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2bcchapcr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlxbfdve.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2gzbififc.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2ghqdlmam.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gt2sgdutjbb.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2wxbheszl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jequgqfh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gt2ypkcqapb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvcfexvg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2hdjpcuqx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2gsriogiz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2nizfilun.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gt2daknnqoe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyodtrok.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2uktvlyzq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2hevlqzii.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2assfumwr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2mniswwes.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2bkmqqumo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2xcixxqqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2rjbolozx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2enoinxjh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2ylyzyesw.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gt2xaompwdb.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2zfahupxv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gt2cogmfcna.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2ccocwsee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2ybbqhfyd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2zgyujmyb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2zxubymaa.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gt2jlufifyc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gt2bpdotbzq.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gt2tjwwnmbi.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2udvqeimi.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2mhltruox.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfuwffcq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2idirckkf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gt2xcjhxamo.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2vzqhaelg.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2nlerlotc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2thajicyt.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gt2yjkgwqny.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2epemdvhn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ioerrhod.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2tvzwwvlr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gt2xqzikfmj.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gt2njsvjrvo.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gt2sbvyutky.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gt2cnshclil.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gt2ngoegugv.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twzjjcri.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulxgxmel.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2vnuxevjo.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2izqolmqn.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2kidnzbro.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2njnwregq.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2tamzutmw.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gt2kabapyoy.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2aqxehben.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gt2sfbqfupb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2wrddmlzv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2jplyonog.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pppkreuj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2garxbbjw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzglxpxs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxjgmioj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2hfwqotnv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gt2ncnvxeiy.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2prdvboqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2ukzhrnst.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gt2yfqpplkm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gt2vaufejlh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2xjlpbcwx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbogyka.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gt2olbxdbpw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gt2ygrylvqx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gt2gsrdabfq.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gt2befdbwcf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gt2xbapwoju.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gt2ekikdesf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2juoijgao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2svymuusb.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2ipllesqs.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2yrbmurfv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2ppzmqxcy.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2jnddovbz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gt2dfwpgxmv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzqvpqbm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gt2ahikphbo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2fwohnmcs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2hntcfqez.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2pfejtnfb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2iorbmxaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zywuvnaa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2zhlffnec.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jverjozs.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2oogufwee.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fzbmfcpc.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gt2wobmcexe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjqmmbbk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2ujbtpbej.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upipmlgb.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gt2hferckog.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2xvnjlaqg.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gt2fsfssvsm.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gt2nzeupwiz.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gt2mhjsgooz.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gt2nuxbyzxe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gt2pwdscech.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umszmqju.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2beuzmpwk.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gt2meewxktb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2wwjurade.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewttfebk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gt2evpjxxyo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrrgrdhp.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2qcrsdvnq.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gt2sbhhvywg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2yzxpjlqk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2hogkvgev.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2okpirifp.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2sddtifaj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gt2ebmyxooe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2ucaadigq.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfndqzkr.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gt2vzetglvh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gt2fkqprdpd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gt2mfjpduet.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2akktdqjn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2rawrfmoi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiitcbcr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gt2nqzlnrmi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gt2odyrfovh.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gt2rspaygbd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2ndsgjmcp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gt2gpixxtdc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gt2wmndzqqf.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guylkfph.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2fpqeasek.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjngoddr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gt2vkwcepul.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2qnjlchwc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gt2plblvyqu.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2umyzldki.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gt2bvesssms.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gt2mbkhknht.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2zxpjxycj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2yopmrlvq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2wgtbcpce.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gt2ezkmotmt.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkorgfvq.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gt2ndvtoweo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2mjpkdlzt.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gt2goygxrcc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ordocodl.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2iufonyha.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gt2oaejxtxe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2yauegjrq.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2xbmcwqky.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2slilrzkp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gt2nodaijng.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2subxygub.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gt2ydhgihgk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gt2gjegpoci.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gt2ciwnzygw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qporfepi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gt2rwwtbgmu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2yqnlvrpb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hijvkhxs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2ornxlpcm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njjiokzy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmvmfsgk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2xiexmidw.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gt2fwbhmcuj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gt2ddoncjsy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2qifsxefx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbvobnen.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2xmgnlmgi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2qezahxdt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gt2xfdiwmpl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2gsqvgqlk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2teuwcaal.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpgchloe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2foqsbriy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2qndsakss.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2ufbjaesn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2rutfixew.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2blhvlbfj.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxxnodiu.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vondtxig.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2isizhvqo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2riaqlqst.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2bilzdrae.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2tfqvdfdg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2essikpcl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2ubtiaycd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gt2wrkdbmmk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2pzvuabum.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2waikotgc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gt2bgxzpvri.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gt2ivwjavnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gt2ahtvefjd.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2yorqeswb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gt2zmvduslp.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gt2krxhfznf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mondkhrx.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjsidzel.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2qxlobhyt.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gt2glswfpgy.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2wwmkxcfj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gt2lhypuqgc.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gt2adfijljd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2xcwfgdqa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2omwuprqx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyqhorjz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iferjljn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2oklchmvu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gt2ygaxawwp.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gt2iyzkhhqy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gt2wkkjmwnt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2nadsdxad.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gt2dcqieaxk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2isswosfk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2scosfgob.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gt2wliefsqz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gt2rgfpbzee.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gt2dwsfyijr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2hxjsunuk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gt2buqhvdok.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2lmowakff.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2zzspjthx.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2oovspifz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2ydzzrohm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvljyuaa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmfkmlhz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gt2dicltxvl.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2zehtciwd.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gt2cfenqorp.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gt2qzawgsuz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2wgupceql.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2hkkbvyzd.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2npesfvhm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gt2phkxtkrt.html

);
来源：http://dali.316326.xyz/Article/details/gt2kqeloalb.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2hzopgamc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2xhclrifo.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gt2wkgdvnyu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2gblyaiot.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gt2ralkogcm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gt2rswvgqia.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2lvwopzgx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gt2bdsofwvk.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2ypsrxyzn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gt2sivwptxp.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gt2pncxbxve.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubipntgo.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gt2rmdtkckm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gt2iwxppyef.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2phyeffdi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2zaltgitg.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gt2jbjzuezu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2soltpjnx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gt2fkeyjmnv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gt2vzuonmnj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gt2glwjftuu.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2ojaeopxe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwgqeudq.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2ttzpcgtz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gt2uugqqtlw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gt2xzzouzox.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhcpytxe.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2tbsycpgk.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gt2rzlssnpc.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ozsrktdz.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2mdpksqwx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2ahhbimby.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gt2hmfnbatp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gt2wamizoch.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gt2vasiiyzn.html


<!-- 参考信息 -->