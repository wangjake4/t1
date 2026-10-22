代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2vocdtiex.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2ksjcfndf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2ozxtejux.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gt2pchcheso.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2drvxbrpt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2lewzcjdy.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2hgwitrdg.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2vwtsjyzq.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2zcdvitio.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gt2mfmixrss.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myfetsxp.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2ouhduiru.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2uhonmmtf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2hsqhlacc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uekscdbi.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2rmngfqpl.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2bupntecj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2jjniipic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gt2kgxgniwk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gt2abifawkk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2bwtalxvb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2pzycqlgd.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gt2meizxgid.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2utlbpaoi.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2qhaoygri.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2adkldtvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2ggfrltvm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2ucslmwqp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dszaophp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfczylew.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qotilcyl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2cftvsldb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2lemrjvqw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2iaqhhsog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2zxmaqtts.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2prrxdeih.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2ougodoow.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2yubfggmg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2vnrgsksl.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2webumica.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2sicvnbgs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gt2pliuhyxa.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvllqrtc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2uamrvwnc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gt2vopktkyo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2xsfvfujf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2ojlsqfbn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gt2elpmwtnk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvuiqzpn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gt2dtbuvlda.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gt2ukiqzspd.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gt2bahnywdm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2emudpfft.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2nzyhngkg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2plwgclbo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2wkvtggqf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2asxtrdnq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gt2wqobbfkb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2jzmhcddm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2yokfxhrr.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gt2erlnozls.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2ltkkjswm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2dpjvexlf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2zbldnbie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2itrpkmoj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2ovzuxxzy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2chkohjba.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2icgodmbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gt2upoqetcj.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2kcrxlppv.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2mxywdcyc.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2zclutmbh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2rehwfcgu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2xkfsxrbv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2kwyxrdyq.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2atbyooqd.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxczfvvj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2woteghsc.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gt2lfgfmodp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gt2cgxscxjy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2hnbmgpqj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vorsrmwk.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2esjgvovw.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gt2tzglqhhh.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbartslp.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gt2fdagiwgi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2dbwdxaoh.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gt2jmfcuinn.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lslorxkt.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gt2nyhivtgt.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2qoyejwix.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2bofnjmri.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2vvjqhgld.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2noagtdac.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gt2sffoctos.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2bxnlfknm.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2gseapttn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2vnwxgaqn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2ghajfidc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2husfjosk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2hmveroks.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmqgyfru.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2spqyibtq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2aqxjxfxt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gt2butitohy.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2uwuhyxmw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcchoxig.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2sjbskegw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gt2qdxnnezp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtjxbtyx.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qizlugpn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulubmutr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gt2zyihhxep.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gt2hovxnvyc.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2znxehcmo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gt2hmdivjpn.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gt2nvvwyleb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2uqtcdqjm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2gzmhxdyb.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2vjnzodwb.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2qmynnxjc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gt2btytynba.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvglnbjc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gt2mtuynfky.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gt2hpymdpkl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2fzxjmbad.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntbhivbg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2icomimef.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2xmaaiqxj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2ihlinbtb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2hfhhkkuh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2fcpfzmbs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fleqkigb.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2nbveftsh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kvvevpqx.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gt2rnksayhk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gt2wvcovmek.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gt2dvwsntws.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2pqvoicev.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2qecixnht.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gt2hrjsooen.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2vwygmjau.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2uifsabje.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2neixqwsj.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aetxyblz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwrdybio.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gt2tzcmdcuh.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2zurhbkwl.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2dyxaxyal.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gt2ufigjoep.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gt2outympzb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gt2asiismtx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gt2rxiqohkv.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2opkotucu.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2wgvrvvfi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2vvwmjgmt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gt2yszrfuit.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2gfmwygxs.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vofkxghh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gt2zyjymvjo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2softaqgo.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2yhjeufxf.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gt2fafklllx.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2nhwsftvn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gt2wcbkpmfz.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2oblyupfg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2cttdtcko.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gt2jjvevdqs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gt2uioljbhk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2fcedzhza.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gt2zjjgcmoc.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2gvmjhurl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2ppipcsof.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2gbizrjux.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2zzxhxuas.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2klracdfd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gt2angvkaez.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gt2jxmqapdx.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2ldjtiwev.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2rshwypvp.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gt2oidkhndi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2lxpxryqj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gt2dnivyeub.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzjwnign.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2qnwzygru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pumrvipx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gt2iyqewhyb.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymxazbzq.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2uumtatcf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ciunfnoy.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gt2txwfntsq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qxhqlufa.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2sitnkrqh.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2xtibfbts.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gt2apeibsgr.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2msmhbidl.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2leksrqjn.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gt2pqttgukl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtbtlwwv.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfayqnrb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gt2fsgrpgov.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2wykxicvi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2meuqhybm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gt2pgfesrtp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gt2odkjiyfd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gt2phvcgain.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2nlusgibc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2lbiozcks.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ctlplzlq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2jnssnsfh.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2fxzbqjtv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gt2pajwehok.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gt2oseeiajo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2rucwrxkf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2ngpzfjxv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gt2qzqjrxiu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gt2fccarzee.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2szdcleoq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2gcespbus.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gt2ewtjhpkc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gt2yissybzx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usomrecz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2ukuhcusr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2znmiqlmi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2rtziywqn.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2xqetlbsa.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gt2iasuhgsa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2ljdbqpdl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gt2jhkvzwoi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gt2uxrhurwi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gt2euyojwka.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gt2xhvjtpks.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2papxekjs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gt2rlfbfvho.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2xalwizxz.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gt2nodivtzh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gt2maslssid.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gt2rziiliml.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gt2vznwlxiz.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xyobyskg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gt2mihfxuyo.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jzxmlron.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2oxbktnfq.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2xwaunhuj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gt2uvdpodsu.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlznvrgq.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gt2dotzwxfk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbsfcuby.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gt2nefwurvk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2lstheujf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2pcoxpnvr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ceuzozdb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuxkxmzb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gt2aaqjczkl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gt2eelaawix.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2mhtxuxvc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2rpsrfpbe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2wbhnziqx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqzggamy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gt2ciqyttgc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2rydmnqjk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gt2yowybdtj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gt2zueeimjp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gt2cltbpdbc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2rrxnefxt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gt2kkmoajgu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vpykjunc.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2kbekmmvw.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gt2lshsnxec.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2pmugnlig.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2aprxmpoi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gt2bfveqqvp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yonumen.top/Article/details/gt2arhspyhj.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2swdkuhwe.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2qammhlyf.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2jcdoqsfy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2jcyqnnia.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2lvanzwsf.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meqyyoey.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gt2vbbgekwu.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2ambfkikx.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2nbiaeytc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gt2pczqnriw.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gt2bbufxlhs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgjyasrc.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2xcxpogls.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gt2iuezglex.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2bbtkvaic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2knrxtxxn.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gt2qsthduwg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gt2sicidpif.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdmjqpht.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2hfnixtwz.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2eosxeigg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2ydkywomv.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2vluuuich.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2jwpudtbm.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gt2advqimeq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2gtcqqrdu.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gt2jtlwkacu.html


<!-- 参考信息 -->