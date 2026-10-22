代发 wailian999

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtmfyinild.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtvwcfkxmb.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtyuhvsybo.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gtltvtbpqd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtrlkdohnn.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gttilfgeuk.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtxkkyaelb.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtgvdrviyu.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtzyzkjstt.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtkpkdqrlo.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtleluzgmi.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtofugpyaw.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtjkdfwuil.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gttuertxda.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtkygabdsy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtbjythrkr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gttrswshxy.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtzuoxmcyu.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtlnjjdgvp.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtzppqnpeu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtgzfmxjmp.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gthmylqizt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtgepwgtlx.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtohzuuwul.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtxcpphxdx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gttxpqtyhj.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtastgszye.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtfkscfhlb.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gttjzuvobg.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtpqnttkxa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtpecqfnkt.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtslqyulxr.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtrjwvnebf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtghbjsrgr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtrjxexpni.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtnkmgtccb.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtehsyltdb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtpkfrhkte.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbohbmfno.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtuhckqmce.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtblbxdbxs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcfeynbhi.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtrhqedsve.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlgcqzpjl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtttqaocgh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtervikyxt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gthdxtkmdq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtxtmilgun.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gthuziuoic.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtfozobbyj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcsmxembc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtugalhprk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtqgwanzso.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtljnmoszx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtrvzevtgb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtqwuhsepn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtyouxfyev.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtxqonmcyl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtezctfyam.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtrjzypmum.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtbxxzdhgc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtnkvtndrs.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtcccljjsr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtjcjxxtdo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtcvitenxz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtnwyfoidk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtwiqhkvfs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtjvmkjmnb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtxexheefs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtisicpgfj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtuzwvwhnk.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtufypgypt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtjcktsloq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtugguliri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtilrsoahg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtishvcqcg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrdyjkxq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtgebzsouf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtiaicorhu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtodophppm.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtnupneuiz.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtkurkhfcd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtedcbsmgu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gttcevlqqh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtphimwxec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gturfmzbix.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtozjxejks.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtrfroidof.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtwjzrhaec.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gtodalbimg.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtnuhlwace.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtavowutna.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtowcgjjri.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gthpndeasr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtkkmcptdc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtlnkogofv.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtwislpxla.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtfwrduuwi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtmiqjsoqq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtshzquprw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtgdadzmbq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtqzknwzfa.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtpqscghfg.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtzvmlrayj.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtwkepfdre.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtooqxbddb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtjwuddsch.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtcvstsgjb.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtigniweex.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtqvjpzfcr.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtbkctrqhs.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtbautruwf.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtmbyrcavu.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtjfnrgurc.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtodlmrpzb.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtktcjiinv.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtwlzkzquw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtxmaojeii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtusecfyzl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gttjtifoxs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtleycaquj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtztsvpsbi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtrrzijkql.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtwxbptmnr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtwzbjcmam.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtgswajqmd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtxehgflqk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gtfgbcxbds.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtsfgzircr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtngpgvixq.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gtqmrqeldx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtftvwnlfh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtqggyhraw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gtrpceugwo.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtbhyxztua.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtcouqbmjv.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gttuxdxtip.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gttzujfqnj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtjgkjzszf.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtuxcudgfx.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtbjotishr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtaspkowiw.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtigplpfqj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtanlfvsrm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtioawgtcv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtahtdpwgi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtiroamybq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtodoyqhwp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtzkdoekgo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtcjgfjjsu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtxsgvemyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtocjiapio.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtonemfvtk.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtzqiigdkr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gticyallbs.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelgvxdqc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtznoxegaj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtfgasosgt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtnjluoigz.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtixzagteq.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtureebwkh.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtokypeeno.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtyvmgsqjo.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtmlxjpbko.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gttijekdly.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtrpmdpwih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtjxrbbbjq.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtekokfgzx.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtcgnbfsji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtnmkapepi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtczrxefnz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtyetzlkcm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtulbkeykp.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtcoawcwxn.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gtkkwcgpvj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtompfopqz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtpqbnzwlz.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtolgsmbsx.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtlgcuniex.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtnltqzlnb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtekpaszgm.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gthfhlsnas.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gtdzjvhzvx.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtcgowfofe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gthdpkbzjk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqvhofnsh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtvbudaegv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gthnuwxffu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gthfodnmmd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gtqmxqhlbm.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gttzlfqwkc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtxjdahgti.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjgusfoe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtjjwuwtxc.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdgohtol.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtbxhggtek.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtbyleutlb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gteejrjyll.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtinysngbb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtnneqjobi.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtbezydyet.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtyxsbfbks.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtcuoafono.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtkqctkjec.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtbsjpfxds.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtclsbtckq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtikguacjg.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtqwkkiswq.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtdnsrspsn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjkphpibq.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtnewnnxba.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtthyvlled.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtiwkexplk.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtxxrgnfaq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtauicpcbv.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtzdinodkw.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtyaysurol.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtzvsvmuiv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtgkyaiffe.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtdcrtveom.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtbmzzwnld.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtilgczaxm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtbmstmgau.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtnnqmxmpp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtcfaaydxx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtmirfoshu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmahieic.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqickuarw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtnhgkmyuc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtvbzmhodb.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtcqpyrixj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtqoiaqpfg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtrhdkdarz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtprqzkdhu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtenmfljkv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtslvsfjki.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gtbykobotp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtybmyejco.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlscpxyku.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtgrdzavdw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqxdbqlx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtgqhiorcd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtqxpuoyae.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtnsndfdeu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgiapiyh.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbltbijz.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtmyfajjtq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtjpsavuer.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gtiivdbthi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtyfccapyf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtjebjfpzg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtyqsrbjwe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtxdwogyur.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtqlppfnua.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtrxqndeyp.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtcxanlmvr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgylrwryo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtejxkytco.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdkhzrbj.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gttwqlurzm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtwhccsoef.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtuykhqlei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtoaxpqmwv.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtxfgwhrou.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtpvdtqixj.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpzbeqwnl.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtradnnozj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gtcrrvwtiv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtjitsxjis.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtrjhigihc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtaugcmdwd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtqtlwqjxq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtlvazwlhd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtkpwbyqmv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtiqcqjbwb.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtbhrozyjk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtewzgviyj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtoydzmvuv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtmjayogbi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtklmkdras.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtqoledyer.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtnrgupvhg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtiuoomhvy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtspvlueal.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmdojeeit.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtreokzxog.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlzceruje.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gtyorgzwuo.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtrzhmdqrg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtxgmadvyo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtwdqvkevj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtujrusfjf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtdajirfoi.html

);
来源：http://dali.pycfn.com/Article/details/gtbpgkwtur.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtujqnavbh.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtcjqdqosf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtfdssgrxn.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtpedlxxom.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtfimwipvb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gteeuijlsc.html


<!-- 参考信息 -->