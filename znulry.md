代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtotblzmjz.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtenhoivzt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtkuunjcqu.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtkoamntoo.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtjqicgwao.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gttgjkqlis.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtapfbcasa.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpbfyxsu.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtehkbwjwe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtdngcauaw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtuzxsleev.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gtkkbdkxjz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtioczwhoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsdnicccq.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtsjutxclf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthrcpxixr.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtggxnyvlz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtnuspwshz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtnhrjfnkv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtcuyigwqm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtdmoaapbk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtlqkzuxkb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtaourqzkv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gthblwecvx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gthtawjvpj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnylmydph.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtirrlzgqu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtvbbxzpww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtbdnldpyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtaucqjuie.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtzgkovmhc.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtrlfqqvjr.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gttsuibkby.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtofxyhkqr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtcrwptiku.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtejczwbrx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gthvxnfvzl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtewjhtpnj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtqxgrptwd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtyfidyisc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtpducgajx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtehpsqeyk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtaurfjwsf.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytqutngo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtdfbgdipk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtfwhshyiw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtshaatpcw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtvujbgzgr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtersnklav.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtsjigvlke.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gthfynhomq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gthakrhbre.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqlgqzjd.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtlxvivbjb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gttsfwauop.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtcklyqdgd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthojjqabc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtjvkuxdrz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtngjkvqqu.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtiglcywbj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtvkefqlfp.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtfobapxfi.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtqqambgvj.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtfqgvxade.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtjypeysmn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtrlfpimny.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtpdgqkowh.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gtcoqkvucc.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtpwnrihcw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtnusiejzk.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtnnzciisk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoxgkakk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtcrdvgbwz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gtbnuvovon.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtrfqeezmb.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtsmgimvae.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtoafswkkk.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtgugkdhxs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtdgoencnt.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtwpwephwi.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtzdaqnprd.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gthkyfjmfv.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtqhutjork.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtieqlfqqx.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtylndapbs.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtyndiulqa.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtkiepqfoy.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtupautrtg.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtqbdmpeii.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gtrcikwvrg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gthohxgnux.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gteixegzsv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtfvjvoocb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtliwiynkr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtfllijafe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtbirxcwzd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gttbzoewgp.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtjsfkxjvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtwyicvwsh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtrkrcmgti.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtqwcdtuqx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtbzmqfkcx.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtpyvhdeip.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtshqipvgy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtcxmvgmfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtvelsgjhi.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtyrgxkmpo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gtadsfsytl.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuwhxbes.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtjimdaisw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtaaigqunm.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtcltajnyp.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgyhochq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtortmnvrz.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwkurlxp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtfkxoofbb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtqtrvhnxo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtbzgnjyze.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtswmmaqla.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwprepsl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gthjilfbei.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtdjoapooz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtgjqcvpzp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtppzvfkwj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtanrmywlc.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtaujqimmb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtidfmgikq.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtpupsitrs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtzsvtyszj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkhlsxqap.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzfnptii.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtynqalisi.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtukjwrspu.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gtywlmhjjx.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtxyxiurbn.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtgenpqavs.html

[O02] 使用线程池
来源：http://dali.yvedp.cn/Article/details/gtupjbrqke.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtzuedhzwj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtyysdviya.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtebhpkbdz.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtbvrhnxxm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gtlkwlyxzi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtxurxtsmb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtiqylnxmb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtmqscxrxk.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtvbjwhike.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtbxywleoy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gttvbwvdzf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtdremgbnf.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtxmakhxyz.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtpcrieyai.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtmhaspeak.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gtfgczyrri.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtijtpelkn.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtbqfofnlk.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtsiavumjt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtzewczvxh.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gthblxvzqj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtiutlnsah.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtsbxgeefn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtvlhwplcm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtprvlxbwa.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtwruxxxlm.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gtpjoxvjvm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtdvtuiehz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtuznetlgd.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtarcffddh.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcjvzfvh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtzmeooedx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtadlwnoch.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtlrxoeyyo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtaebcjkzu.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtgrfapxyk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtzftdrrwg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtfqmgmrqs.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtadbvrbbb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvzdfitk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtlwtmvlfa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gttnkwppka.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtfgzhzwbo.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtanbhapqm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtomtbmhmb.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtgxufghbc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlbmfkkrl.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtqykgtebz.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtczwdngwh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtvwefgvdt.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtewbxagxi.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtrhfbkrkj.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtpvppdeyl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtlrauzodf.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtpbagoqvk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtpblttqgo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsvgrpyf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtxkodnjvl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.kuanghao11.cn/Article/details/gtdywsalmy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtjrhvqyka.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtrrvwluip.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtaikmstlx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gthtgfomzf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtljyrzhni.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gtfdikcpmv.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmrvfcqw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtfpnqbuyb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtfthjstfq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtpjqbpwho.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwnjqcyr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtuecqnggk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtseblmhax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gthnognjfx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtekbvmvhk.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtrdcumygq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtgipxunbd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtsglbsygw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtzgarrdqt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtvfeaejmv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gteifunnkn.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtasfrkezm.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtxfnijdfy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gttyfgmemz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gtnhrsdbdi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gturhkvcxl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtqsbjlgfp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtvkkuopjt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtesamowsj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyjloreb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtsvepggzx.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gtbhiivqjg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtkxfrojjy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gtmmhjmurg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtxvnlkwjm.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdafrllbs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtdnjzskic.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtopztpdwu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtlirhgrtz.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gtgwlokoud.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtpwihpjct.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gtgtkosoqj.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtszeeanps.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtnqwxanmy.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtirqhuyhd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtiuvkoarf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtktcwmtdq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtivamuioc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtvghpjfjb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtrudlfnxl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gteqanvjqs.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gtktjighoq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtsiahlvva.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtuynbmxii.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheezymaz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtwprxfzls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gthcphgidv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gthfqaqupz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtbviokzjm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gthtgvgwcy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtydctpzdf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtfhikvfrk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbredzrsx.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gtselhttja.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtkwbgezna.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtfjhhywvy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtrhhiaeaf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtnhxalngo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gthwemwkxx.html

);
来源：http://dali.havefunace.top/Article/details/gtufqrpcll.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtvsdlgjhu.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gtmsjpwclz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtrdiumhrw.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtfpleprbj.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtqthefzjl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtzbkytruq.html

);
来源：http://dali.guannengcc.top/Article/details/gtiififeiz.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtrgxtdygo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtklgjyztb.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtpanifxih.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gtbiaamkwd.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtowfjjqsq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtsvqmtbio.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gtciskbwfk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gtnibjyxpe.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gtcimjmxoh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtuhpwwksw.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtyhypemgc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtvpbitxpd.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtmjwopwwv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtvyfbzzkf.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtudhuskll.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtoigsourv.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gttojhvabh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtwokwsxvw.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gthfjpvern.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtlmleqsjx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtoyywakkx.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gttoatphcr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtwfuydheo.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtunlyltwi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtlbbkjnqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gthydgowrc.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtpdtdhqdo.html


<!-- 参考信息 -->