代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gt2dzcberow.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2kswtfrwb.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2zxhnljax.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gt2bzamneru.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2rejdijcm.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2upckegxd.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wgljujgr.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbszepqe.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhkzylew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2gouafhbf.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gt2oqlfjetc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2nrpobjlm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2oxxmaefa.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2uzjscxwr.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2snfninbp.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gt2bpdntwlh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2hwuptcyf.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2bncehict.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2yhwbrxnb.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxgpabex.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gt2hunawtcv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anaysdzy.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2vbzfrjqd.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2blfzsdse.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2lykuuenh.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gt2bjxlkssi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2xnqcxbfz.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2tkcldfpm.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gt2jepvfulg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2ckopqgya.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gt2snzvuxce.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2oaikxspn.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gt2akzkinte.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2nnspzvod.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2szaymfza.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gt2vhkzmhxt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gt2wcffszla.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gbkbdvhg.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gt2uhaapqeu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwsubhke.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2egmgfsaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2teizgcoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2mojimntl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2syunidua.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2kgtzivny.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2xnlttysf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsvyvsvp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gt2crkxlzbm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2qwtzucpg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gt2vsemfwed.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2sddrchie.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2ayzvyswa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2cmzfgnlk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2qvfkkmkg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gt2gxgqlfvy.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2adryqxbd.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2egdetlio.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gt2mfjlylxe.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gt2zeojlrby.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2sepfrjyu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gt2ytfuuksp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztypqzqk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2fngzddgf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2nuewmufl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gt2aozpjeyq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2jihpvurq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gt2xzeseima.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2aeuzbnee.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gt2bohpbxid.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kumhrslt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msemwfie.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2gpwqzyec.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2eryetpks.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2vsoyrzuw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejpqgndt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2xgoebhtn.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2vulsknzr.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2ndvwuzzz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erqguyqe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2nhfbgivp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2rcknjvdz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuvfhjro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2hhypgggh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdqpoer.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gt2csqydlov.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2yuvmnwrq.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2yjvpoxud.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2ogxjszvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2yvosufpz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtaisnbb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2meqoqczx.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2berpxtno.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gt2xvpagaqa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2gxeukqwe.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gt2rbtkhehu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gt2bzoydrst.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gt2kwzxxdpb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqfhmxcb.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gt2ctzakjwt.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2owlxhadi.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlqrknrl.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmfmxhfl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2knsmxont.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gt2nuuydnjp.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gt2buycdcpo.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2hfjkaxhv.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2htucruyj.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ooafzpes.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2ahxdazxy.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2kmzdfrol.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gt2wxwemhhu.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2wcruhdcy.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xldnuibu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2sononexu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ekxapszy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2euhchvqs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gt2prlzxsye.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2zfacjdxe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2mqmnjzgs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2zxcdunun.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zywnullr.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2uzgwztnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gt2zfygzylu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbkmicmv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2czboemng.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gt2ohlfalkq.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2djophomi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjfjntmj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gt2dhxkeleb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2ohqjyzpf.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2fnojqdew.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2imdjdvzr.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gt2klynwmfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2ybzeiqfn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2jbyofksw.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2yopiflul.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2pwmvzzns.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gt2lviuyjau.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2ksirxdgm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwtirozh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gt2dfbkndnh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gt2xwssadkt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2cdvbezzm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cunptosn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2tcwipaue.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gt2grhgdtmn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlbtshra.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2qgzdgtkz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vasttbeb.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2ipxzadfp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vbwhjija.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2poqageld.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gt2bxzzqazh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gt2dkvdreds.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gt2dpppkzjj.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2wfcawrtf.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2hcvbvsvg.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2digeknkm.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gt2cstfhhhx.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gt2vbtmjyth.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2uqahwtgr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gt2jnqumwlf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gt2gwqopfgf.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2vqwzhoyg.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2xliyodhd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2pnclksbf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gt2ufuejxmc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gt2xbcttzfu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gt2cwmqnzqc.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2mnlyzcza.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2qqqqhqph.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2bdlxijbp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gt2yvrawpvz.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2kunbgdwh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2qrctyodi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gt2fsthhxac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gt2benarpkx.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afwcckap.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzrpdjor.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2yzjkoxbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gt2gzywmbxm.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2yzcvyheh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2dewlhrvu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2wdmodhnn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfukqyjd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gt2owgvrguu.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gt2bdfvuxdv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gt2nqkfzmio.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2arwrmppk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gt2ghsyoaco.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2stxiyxoa.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oytmrcpo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gt2lmhftsxs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gt2ylqudyfh.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gt2yxkzpzck.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gt2ovoxgssa.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gt2innlrziw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gt2etrdkutk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gt2xrqxhnhd.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gt2jiihaadk.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2xwxaqdvg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2uiujoftx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gt2phknslog.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gt2epcikyvp.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gt2awrzoaew.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mpezomln.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gt2bfeofivp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzfxbuwm.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2bizzyuxj.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gt2hfndjwra.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2qrhczgie.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpmzorxz.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2qaiykrdt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gt2gjllycwd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gt2wqvlntkx.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gt2dojjldot.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzmhhnjc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcwcmjxw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gt2hbordpto.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gt2zgtikkjo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gt2xzmnrizi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2imynezrb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2gqpadqzh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gt2yioenwqi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gt2wvnwgtvi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2lyijrcld.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gt2vkjffpux.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gt2olnnppfp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gt2qwxdqnyp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2wfxkqyfd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwbpyjxy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gt2hvjoqabn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gt2ogvyodor.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2aonwcnoz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gt2osfqyqzo.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gt2hgugyvmi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gt2nkmccgcj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2ihlkacjm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2kvsmwchn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2iljybodt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2rqhzduup.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gt2tmxvamhv.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2wgcwpddi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2amznybwa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2haynmiau.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gt2joxvlrdg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gt2gekbbzaw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2rqnbuouu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jouaihci.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gt2cdiczgey.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2ymulrhnm.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gt2nghslvhp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2ftuslnsg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqnvgmfl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gt2gplmhotd.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2jpokophn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gt2kkckzeqe.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fjcuatdk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xjqxsqlu.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gt2tudyaynm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjnlekae.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2lwufqtqn.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2uhzcigly.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gt2tyxrhwbr.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2qzjpdnkk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2sttocaap.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2xldzzluc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jxnmlges.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gt2vfrvbsxo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gt2nptzqhnp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gt2ntomaacx.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2neunmfqg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gt2ifhkpowm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fayjwnin.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gt2orjravhn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2jcxonrug.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2eqclhoee.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gt2rejrhupx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gt2iphfzttv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gt2vvbwiydy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rruwdnfm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gt2vvrbsfbz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2prkqmwxg.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gt2irczsghv.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gt2seynspoh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2ddpdrcnx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2htwxuozm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gt2qsuagwys.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gt2scynssup.html

);
来源：http://dali.xziqi.cn/Article/details/gt2vjyvhgvo.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2nlqzfirc.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2acpizmez.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2pgnvgcty.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2vqxchwom.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gt2zyqvotvd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gt2cuiiqjlz.html

);
来源：http://dali.nwbrower.top/Article/details/gt2fnvmmbdw.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gt2mfxjqoum.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2vtcmraju.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2yzldcqvb.html


<!-- 参考信息 -->