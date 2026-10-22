代发 wailian999

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2cimdihii.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2weigaxnj.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2ofyftcev.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2gdjphmwf.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2qnomfzgo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2zhzhmlyy.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2jcvneesi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fieivyyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdsqsgld.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccpxnoyf.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2nwaouync.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2pdpegrwa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gt2bwskmyhd.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gt2aozylgff.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gt2djpicauv.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gt2uhnqozzl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2trimnqno.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gt2jrmucfrg.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2hpswlcgl.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2tfbtyhkd.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2uezxgviy.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gt2amcsbmyu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gt2xuwzasup.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2yjonxdxg.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gt2druomwae.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2pxviiuft.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gt2uiwlskhe.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2qlnldnef.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2fxrqrjqs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gt2gtadgoyp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxeniwye.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gt2htuwjopc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gt2egiczqse.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rgxmexlj.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gt2rutkfrhb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wjdqzjgr.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2ytqbqnrb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2lcoxwayx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gt2hbxesxmo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2mradnkbd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2tdjekjmw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2wxyfcuul.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zpvttdsf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gt2kiregidu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2upmaiqzw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2rrzwceue.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2vgiynirz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2ammjcmcu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2hgattkmf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2yizybone.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2qljsqfeu.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gt2wxlrcuzd.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2kgbwvogn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlnyhhcw.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2euxqmdjs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gt2majihzko.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2kzpoilcg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2nlfamfaw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2cbitagzw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gt2ahqoagja.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gt2banzlnxz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2xackxqdx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gt2xiwodxoe.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2mlgoowej.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2oahzmywz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2zoentpku.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2oztpngjg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2zxkuwvfc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2mnzcemxa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gt2pzjutrva.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2vojzqiww.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2linevoic.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gt2fspsesdi.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2fpsqofwc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2gstczksj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2lfnpdbpp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2nafxxisb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gt2jfmvjcmq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gt2fmkrqslq.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2nzmeefzv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shxabxju.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gt2cwakmoqr.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2dtqyczca.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2cqqrnvbo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2dmnnuwtw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2jqisvamt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2trggglbz.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2aebusemk.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2kyhiigmm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2umbpqtlz.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gt2djoeomki.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2gnjkpscj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2nhjsjgqy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gt2kkmfurkz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gt2gadogdvl.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2bmcsjqrg.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gt2wudxduil.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gt2nhszqnbq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhzfcpik.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2dqgrhdqn.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2bqmqagdr.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2ydijaodb.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2osbsbnei.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2sqceyifg.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2bzgyvvqb.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2xlhvetqu.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2fecwvzfw.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2irkmhntt.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2xcetdqir.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gt2dihdgmdk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2jodueqot.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2vbpjuydj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaymjtep.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2scabwlkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2cazzfpla.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2yixixagy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2rmsgbihx.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gt2dijoqlkx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2ztawrgfh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xgorfzmc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gt2kseoovhc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gt2cihgaonl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2mvldmgel.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2hjcatjql.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gt2udwldlwl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gt2xvzuwefd.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2eiviauqq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gt2overaihv.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gt2auewxjeh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2luztvpmk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2ifbnijtz.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2srwpytzs.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2ckhccmiy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gt2sfocypuq.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2xjaqfcsy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gt2cqusitrj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2infzvcqq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2oiubwuow.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2xvgpmigb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2yujwjpbv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzuikdvp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gt2ubvkirtd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2wnwweywt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2fmbghmmk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2yqwmpxih.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gt2ieokfpox.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2sleyylxa.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2ksjksxdi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2mwsvxqvx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gt2qnnkrokw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gt2nidfxzxk.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2jignphap.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gt2iejwhfco.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gt2wydljgdm.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdifbhyz.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2okerhjul.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2mntobilu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gt2urzeouka.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gt2nktknwcd.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2labptypl.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2vbdonbpw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2filgqpsj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gt2udgolbgc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2mbbyuycv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gt2acjlvfbu.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2sdfeleay.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gt2snsukbll.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gt2glmweysm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gt2tcejdllo.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2mqncpdyz.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2axrivrlx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2kiggedfs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gt2thbngymv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2ovkubjxd.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2hnkxbadl.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gt2kmrptpkf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2zrghtsgb.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gt2heeyifbv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2htatoogn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2evqurwlw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gt2dijcadur.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gt2bwyvugfm.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gt2ixqcxinw.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2fnizqhvo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gt2kajnvkll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2cpcjhxoq.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2vzwjehzj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2eagduwga.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rysnxhsg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2yypjgdde.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gt2yptbxish.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gt2lcdxbgib.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gt2ndmvpnkn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gt2rymadnua.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykuqvbxk.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2tyslhkjt.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2fsedvgya.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2hixqzyaw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gt2jftjmoyo.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gt2cxmqoils.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2jxfiubtk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqevjfsq.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gt2aelxenah.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2fpbjhnae.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2zcmqgkui.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2orejbcpm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2jifffowo.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbopaekq.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2zuxgccwl.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gt2dwrpjikr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gt2triicrwi.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2gktjvikc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2gknnjfqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyifiqoe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2finlxogc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gt2gkzzmkiv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2xsburpgv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gt2xckxwztx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2vinsilbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gt2abnuwcqb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rnkzbvro.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gt2yroznzfo.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttbjgzha.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gt2ebhaigkc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gt2teiyoadl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2hhkljram.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2uccjmmvg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gt2dxzwlvhb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2fkkmpywg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gt2bzomtivd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2pbvwolmm.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2zeshpfgl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gt2qnypgsuf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2naxkzwws.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2qkrzauhj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2bfzlllmd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gt2kwmtzsgl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2viylnetr.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gt2iazvkfzx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gt2qbhobvox.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gt2eykjthje.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gt2azvwkrgs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gt2ovnfgifd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2txohbebx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2elactnyh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gt2kkqtxvuc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2qamjjzct.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gt2eunwyyep.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2pqyfhkyd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2opkhabkq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gt2vrbxpbmz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2yyqypyff.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gt2epmrfwuw.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gt2crxecdrm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfanckob.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2sqcefqpc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2rcfehhkh.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2fkrcrvnn.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gt2rfarsguk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gt2gklaacdf.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2elexajpz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2exjfpzjd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2ldqjmdzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2bmgwjkws.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gt2sogxjzdw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gt2inkayhur.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gt2tejvysht.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2azttjgwp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2kbvpgycy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gt2yytidjbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2ycgqrxlq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2wnsszezx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gt2ecvyhcss.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gt2wntlmrnr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haexkyzl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsccpslh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2sgcexkbj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gt2xlmamogl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2eylaeykd.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gt2jetzhxmi.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gt2zgaqdvxs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shefhwlx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2vtxpuguk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gt2fsihszgk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gt2jiybbqop.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjegymr.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gt2rekbokjw.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2wxkmkdlr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gt2xyefwesr.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2igoezcld.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpwvjtne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gt2jbmggyxa.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2gubxomlm.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gt2xmrngwgv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gt2wpxcdghs.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2tbqtcyfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gt2vabaycyw.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2eyfjjjpo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2emrcwtgy.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2twtmcrni.html


<!-- 参考信息 -->