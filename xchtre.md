代发 wailian999

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2ymmevwwf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gt2gbrbehki.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gt2vftwvmfu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2lrvjjgmj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gt2obofnzye.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2ovzjpkwl.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2gjutorlv.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2otidkkvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2kqqjtzrx.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcikjfyj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gt2hrtiajcu.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gt2nshvkrib.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2kcjcctpr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gt2fhlsabap.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2dsafsfzc.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2icgtrjwn.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gt2vnnjbufy.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2fbncgxpv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gt2gopslrvg.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gt2pclrkpry.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2hwjnrqpr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gt2iqnwstff.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2uluizdnj.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2fkmwuklv.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvqvmyrw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2bbruvowh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2emgjyvee.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2evtwrqfq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2alickonl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2sakchgce.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2pwycmezw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ckoqomvn.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2qpgonloj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2uesihoto.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2fmxheoma.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2vecjjxrk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2qnscjsbh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2uaeyicbs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2oodipfmq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smbhjbxk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ojyakkka.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2sbgekdxl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2ienxjlvz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2jhgbnlbc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2gcsljoyi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2vfyxdqef.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2owqcpjyf.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2ikbspngb.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xceefhgh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2djyyewqj.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2gajwtewi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gt2cqaipxjp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gt2lsultbdx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2gvozhjnm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zifalrzo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gt2zhidowwj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2rgbupzur.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwscqmfb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2serugnty.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2xxacqoun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2thlgkvgl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2flsrwplk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2nzhlqihd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2qaqialrb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ppojfrhz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gt2gwdrjevl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2bjzjaevn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2ntqmicce.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gt2xmhkwduv.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2xityuxvd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdxjorr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2upwkjlvu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2uufkebbz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gt2ejwxeebq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2wzxiibhu.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gt2xdldmjbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gt2gtnbdhvq.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gt2ugonrdfe.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2qkvhrjwr.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2qapylmec.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2rndpjwis.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2romhkybb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2vtaqxzpr.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2jrjwdpdl.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2wtahjqwc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2jhgfzkoy.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbqgudaw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2bscjogfe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwnabyxz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gt2oeyxgfyu.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hznybuiy.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enrsggff.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gt2zgqhrrgn.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnaavrxd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwrjxrti.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2qsulszcn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2peooxnco.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2tezaixvg.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2rwcguchs.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2nkjaaaxe.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2erilxqor.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2zilcgofs.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gt2gemdekaj.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2tifqicvg.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2szbbsriz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2fzouznbi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2muiiddng.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2mzlkezup.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2axnfgyyl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2csciqont.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gt2cozaaksk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2isbdyfkq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2sfkfvidk.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gt2thdennpd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2kfoawoym.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gt2jjamrkek.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2ateejlyd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gt2pqjoakxd.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gt2ymtlqtje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gt2yqvooenh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gt2ukesyfuq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2oholdswu.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2gublidwl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2qkyjyany.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gt2ubpdncuv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2hmhlwsfh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ardiqbar.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2kizjjrob.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2rmqctuvf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gt2vadhcuwb.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2forqsurh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqpuldtz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2qocpwdvj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gt2votsfsdv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2bpitjjzo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gt2ufkwcwdl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2reclqate.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2vrqxniph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2uijeebgu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlmcisas.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jjxehlbt.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gt2gltolhun.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2unlbwfdx.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gt2mnyrvqzs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gt2eoxsrttm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2jvfpnkki.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gt2vvrxagyp.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2ybtfxezt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2daprlxlm.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2kifpaofm.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2icyuvvgs.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gt2vnstjzcq.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gt2bieofbph.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2oaacfwum.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahrheqrh.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2pgugcxqe.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2vqjjybdo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2ynbpcvce.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsfvlmvr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2wbhokhsp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2peunqbpt.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gt2ghcuwget.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2ovexinxo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2rwxifahe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gt2vmxwhpew.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2ykuevijz.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzwqcdeh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2yulztrvx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmcducki.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2oltxvxqz.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2rwcacjmc.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2renilhzv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gt2iujslgxx.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wlogbejb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2scfzezey.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gt2gfmrjhhq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gt2hossvpjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gt2gufutdzf.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gt2wqdfhtpk.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gt2cajcqkms.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwqrqtcr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gt2cekdaguc.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gt2wjbbmula.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2dsokiklj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gt2ohwogqyf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2rbwravux.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2unpcwnkj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gt2lhjsjpks.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2hevwhnkx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfarmptq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gt2gsuhkcyb.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2qtzctfdd.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2xcmmkzjt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gt2ndgpdicn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2ohntapjq.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2sfjuwkty.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuufvvch.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jmkneeqs.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gt2tuqprdmx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2icvwtzwf.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2eijpabhv.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gt2vrpoqgkz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiiursmt.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2ljgcsuot.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2vlxiupks.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gt2disdrnsv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2llzjywtv.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gt2qevvopeq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2rxprmsjg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2hpeeevii.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gt2aftutrnc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2vdblzszn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gt2yslxysnm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2meyjrqvu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2nmnofxfm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gt2qtwlegtt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2djdlpktd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjwrdqzk.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gt2sipueyoa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gt2vzwkhogu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gt2xzaptgng.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2qabztkyh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2avpksodn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gt2vstpxsmu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gt2cgjkoiiu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqufhpdq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2utuzdzaa.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gt2wvzobboc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2hopyuesn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2sgnorwgp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2ubmeydie.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2dgaxjbvn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onkqywtr.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gt2alcrbyzj.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gt2jigaryov.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2cyoskexx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gt2kqxkvrce.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gt2ewxbxgmh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2ltamdkvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2seuytphp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2nyeyifcw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2sbgcjwcu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gt2sbwldvub.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gt2bibssmui.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2ojhyehxt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gt2xgrexxrl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2bccqbtwk.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gt2phhgpvxv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2jiplkfei.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gt2edibemxd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2uhixycgj.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gt2rhznxfng.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gt2hkmoodos.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mqnxyhvz.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwsuixcc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gt2smlxespj.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2mejkjuoz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2feuqlbds.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2mxuncbsj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gt2nrgnoiay.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gt2jefznnra.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gt2psvaiddt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gt2pakquruq.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyvzgkwz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gt2cdkllefa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gt2huevtpsc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2dciwnhsn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2sndnoact.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gt2pyzjhbjo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gt2zplcosdx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gt2mnglvyfw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2gkcirgky.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkgirlhp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gt2vxdnmhuf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2jyytuxno.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gt2shbcmakt.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzhbqyne.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2vaixyzyr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2vfwdfynz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gt2vygrutul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2tngbhcfx.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2aarwezzz.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2sdyztbsn.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2kqgntgsh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2ubxsmzye.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2tnpvdhjt.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gt2cwtqtsob.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2rhvxposo.html

);
来源：http://dali.yuxming.cn/Article/details/gt2daktxzjf.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gt2yoiktlke.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vymppzec.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gt2fhwuwvfs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2jmmraekq.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2tlotqaka.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gt2vmwsspoe.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gt2rszpldql.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gt2vozueold.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2oyzleezf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gt2bceejfnp.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gt2uwvsnfgx.html


<!-- 参考信息 -->