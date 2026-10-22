代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gtnktpqjah.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtzzwfhiuo.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtdkpwnexs.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtuuqpjqge.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtrgoxidde.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtlntwivdy.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtnsnygqkn.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtpxwwkcay.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtktfsdyks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtnvwfoajx.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtvjwvgwhl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtzhbxyybw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtkkfbuqsp.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtnaxbkuql.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtswwwscoi.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtpwannqob.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gttypdjxio.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtljqeeegk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtschnggwc.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gtsxhtohcr.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gttwtthzcb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtditlpdrv.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtsmpovrid.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtkyyyorxg.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gttzicknkz.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtwcbirjxr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtckqnqpcj.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtvffzwkua.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtwmtowcdb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gttblepryk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtddfcrupn.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtjcwpoujs.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcvzxluu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtjzhruqwg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtpqbzebbj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtknaqluhc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtzpuscths.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaqmasqdh.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtwzffmelm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtllqmaves.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtvpmzyyff.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtgfdddebw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtkpldxmra.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtwzphbhpz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gthpsvuznf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gttzggvxhp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtdkmlnayi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtlbdntdbc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtrdvycnow.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtqowugejs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gttdrsojdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gttjddecfx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtlspjleye.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtqgwnxpxz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtilaivhas.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtzhclvhtl.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtfajudbzl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtnrinrziy.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtbmclhfen.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtvsmhkeyz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtxckonylb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtfpximkpl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtonhsrawn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtdozcbbcc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtobbhscxh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gtlkhbedpm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gterdheynz.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gthtushtdb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtbodvnydc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtepowvfsf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtzkvhggat.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtqhrkknkr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtvbzllpyy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gterxagsag.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtknigjads.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtkfxdxkrr.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtseoxuirn.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtsbvsbuim.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtpsihkbaj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbsrwbden.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtfcqctubk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtndocptmo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtxbdfgfyo.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtbglnwllg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtnxiitvqm.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuocunneq.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gthusdfdkn.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtjaeswzoh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohdbujby.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtebxstcsi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtsihrlzfv.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtuxtjscdq.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtpnfhhkcy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticjowmly.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtgrijjtgp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjrhkpff.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtxbchqzau.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gttjmrcjfu.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtwgfqmcrb.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtqvxdrwag.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtlrawcytl.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtnmiahlgn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtbovwwhyo.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbyedclw.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdkpixtl.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtdsmtmmqr.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtsdhpcmim.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtejebcpvi.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtktliznwq.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtmusrqacg.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtmuqubtvh.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtwupuxaid.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtwkwxnhbm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdavffjqf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtjzoitelc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtyzuwwzyh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzbmuyup.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtcsiemham.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gticanslpy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtdgrmcvrw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gttgbphrxi.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtlmfrnplr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtlnnyscja.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtsbsdwlul.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtralbhahj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghuxnngr.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gtkhebzzpc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtiatttfox.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gtymzzoihx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwcevqhd.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtgpjvijzy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gttmogksfb.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtaigmbjux.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtmunowewc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtwnroexpa.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtbepivljf.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtlulqsecd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtiyswvxkc.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtthgxzeuf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtradqgvup.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtozjgucwz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtydbsxcbu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gthmoybwat.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtmfwqcgss.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtrepqzobf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtnmppcszx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtkszktglp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtnwgkgmdl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtinvndsts.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtftqjtkkd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbbdhyelm.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtdaqpqdih.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtefyplzda.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtowidstpw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtzngfbwqo.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtaefzgvgn.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtnssnfynm.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gtbyjmmqbm.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtdrbdonqm.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtwxlfzryr.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtghlzjwcq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqbybdxc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtggclalty.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtfownkxha.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtmgdptvuz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gttcaeqoqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtmegvhmbt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwmcudwb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtkvlywzpy.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtvausjwvx.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnulmonfp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtocxaekst.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtzykkmeho.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtdvihjgjg.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gteiijusfo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtgsttlnwy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtizyjomqe.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgtybfctv.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtvtbexiau.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtdoragbwg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtinlpmnsp.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxfbsxcy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtnvzzvlof.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfixjzsfc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtomsgibse.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gthjtocmlt.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumlwpeaz.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtdmlgavyr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtebrxnasm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtwobdevgc.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtqcumuuvd.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gttkrfwfje.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtzzxkosrj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtkzzagmho.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtxfdneyeo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtxqyhyydr.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtpxuiqsqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtrywoqfdv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtdchnywau.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtvthokzjh.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtolhmeaew.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtvczhhuyr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtujnokvqz.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtqgzgcwhv.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctthdbyd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzahhrqao.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gthrckcxvk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtezkazxcq.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtsroqgvdf.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gtastknqot.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gthfkbnrcg.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtexmjloip.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gttzdimoye.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtkuihejhj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtwkhkfuqj.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtsdytskar.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtvkeuuasf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtxtzpchfk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzbtbtio.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtwxufakng.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gttfacxhby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtjnjacgiz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtweiwwoor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtsnxtviql.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gtlxkzdvas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtarseoddp.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtajaiddhj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gtrjnycflj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtxdowgnzf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gthggbnlua.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtkfvprrko.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtwlltfiiv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtdercemrf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtjnmigskw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtfdpvstzc.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gtfpqqfxsz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtzotolrdv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtkoivdhal.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtgusblxkb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtqsicdzdu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtrnrwqycd.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtnkufzmsw.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtpczqlxmo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtyhvcdewh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtttqhxcfv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gtqgkqmfxp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtusbejxfy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtttwghfik.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtkrpeggta.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtweixoeyv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtpsirqoog.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gtpamiignf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqetxetms.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtwlbsgvov.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtympydreu.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtgntssudk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtexhwrvgl.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtrrtlltax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtughpcxsr.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtfqfyhmdk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdbrfclu.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtwmnlpscl.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gtroirtjjr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtdmxydbkm.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtgdylfdtc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtxpqtrhhs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtnlxkuztm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gttpbmacmt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gtxbbkgldh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtvvcfqgps.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtcfcqwnqv.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtpxiurzpj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtihbbqmco.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtbtqqlbfp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtcmgkmkyk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtsodaawqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtxpjpdnjb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gteuxzlace.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gttqzbpoyn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtulrkensq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzvqxbmlz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtlutesdoo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrajipdov.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtmwoniiqf.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtdnvaigkm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtoreqsnrq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtzheymwjq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklktatlo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykupzcgn.html

);
来源：http://dali.hnqzz.top/Article/details/gtzzprvboh.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gtmzkwkmwe.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtsoobwpaf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtyglniwyn.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtjtfdyguo.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtblguccrp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gthohumjkx.html

);
来源：http://dali.ivvv.top/Article/details/gtwvuftoub.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtjypwazfa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtyqeknrew.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gthwdudbmh.html


<!-- 参考信息 -->