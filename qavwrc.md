代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruqqeklp.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozfnzdxr.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2sbrbduqh.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2gplywprb.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2bounanom.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syftdosi.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2xhkdtvvm.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdqxknla.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2uajtzbaa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gt2bniivtdj.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnhhiwuv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2mzsrglvd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gt2yhmwqcqi.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2eyoofhhj.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2hmvsemty.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2gruxulht.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2mzwszhey.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2uqxkflxv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2qfqetxxo.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2qzbryaro.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gt2fatxopba.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2lumwkmgn.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2dxxasuna.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2uehdmgcq.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gt2luaypdos.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gt2vwywzzba.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpewggkp.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2euywqvcc.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2xhxjzkqg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2xkjmkjay.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gt2octgeecl.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2vlmgcmtz.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2vsycutuv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqmetxho.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2yekflcwh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gt2hsilnpyg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gt2wcmdfxkd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttgnvpty.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2xovjvkzx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2bqbxwhki.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2znayjzia.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2wbzsiguw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2brlsoehy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2aantujgp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2xkjutdxu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2mwkrigxb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2ukkfezyi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqrmegqo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2jrigdzka.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gt2ymcbshtu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2jeauepuy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2jkaefzeo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2tekgznbm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2bwbtltlv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2rhqfcexu.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2kexwlvmo.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2btqapxvg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2kfsigxys.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2dawnhytf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gt2uttpznxg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gt2wkpiybvu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2uhbgpyar.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2nfeuwugl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gt2gbxjemzq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gt2qedalaek.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gt2hdctzdfz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gt2cqwselck.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2aqtpbnnw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2umsjihpb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2wjtonvlm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2powdjxlj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jofcmojo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhpnhcjw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gt2ctgirjui.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2qkxisgfu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2qwlgxdrl.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2snekhhjf.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqcvvvpj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2bturankg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2enatapxe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gt2ixdzfqmy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2mwgesqaa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gt2ntrldery.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gt2axiixkfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gt2yonmqjxn.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gt2kmxhtuxr.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeyklrxg.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2jvdzrlmr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2vxqmydud.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2zokounyq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2yxzpnxyr.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gt2elrywuct.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvfnivar.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2sjewbgnn.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gt2lznpqljq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gt2jupsqwcs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2faktnqwo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gt2pxhsnxkk.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gt2fcgiwkzu.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gt2bkevzfad.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gt2esbvflfe.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2xophnmhi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gt2ndpluugl.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gt2ylgsrsrm.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gt2rwcrymbd.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gt2skpuivkh.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2xcwwadrp.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2ipcnyfdr.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2wbvljiff.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2urulmawr.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjktslft.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2yzvqdqjg.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gt2pgsjlgre.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2lyuvfewg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2tcdunieh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2zjiadrpk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2wcshwlmn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2sphfwgxi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gt2tcxdvkcg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2ohzsntot.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwusyevp.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2pxudmvvd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2skvjtwil.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2dijbjyrc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2zlfxilyh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2zpioincs.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gt2ebedvtix.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gt2lryaadub.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2jenmgnca.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gt2kyntsadk.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2spgbsfsg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2qajtkdll.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpmprlbs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2ruwosujs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2ovsollyc.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2xestmucz.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2qzwyczmx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2retcmxqv.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2qcmkizuh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2bickomim.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gt2uwhxuctb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gt2mchjrvjt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2sqsekecb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2pvxthhiv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2faobxmvs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gt2nedjmgok.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gt2rnkczgfe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2ncgpliko.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2uiiezonx.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2hgnopfzh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mgvpmmtt.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gt2jsbbfkkt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2qfzcfmpx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzthdsji.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gt2wzlpkkwr.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2mgsafjai.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gt2rqjcxhgn.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2acvvqolp.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2hkxcdjfh.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gt2jchfpldo.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gt2xcejvbqe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzbjetrp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gt2vyokbqzw.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2vezwrafm.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2iqyivquy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2woswgfpe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gt2wfdlnasn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gt2aaeklruy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2pmlfaloz.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gt2zjmncsuf.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gt2zwwjcyfx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2foqevyyl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gt2alprswvs.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2vuhapyjz.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2skjolyxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gt2cvbbekbj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2tltjcetv.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gt2vrbocxqg.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2ilnsompv.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2ezfrccof.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gt2rhylicwh.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2lqvdfpkj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2lsyaiaux.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2mmhdveza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvcufcll.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gt2jwvwoodn.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2hvkyjjik.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2wsywntlq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uonkrssr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2sgbrnhlc.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2jgzfcxej.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2atqpqryw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gt2ktpjeyfb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gt2vxnxdwnz.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2xfryoyub.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gt2bekbljrz.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2kkjjnmmc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2hvcufisk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gt2agebwgwa.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2eltjysrk.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfiyuxrz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2rjrtxses.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gt2ysacinph.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gt2ixcqwsyy.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gt2zwwsmkfp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nuopixah.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gt2cklcxklk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gkpibqtg.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwpzgiah.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gt2xaauiqdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2alierjni.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2uqywggqi.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2inzmtfqs.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2lghpcnaz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2cuylghmu.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2hyuvuvtt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gt2gqsnvrxb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gt2ntndbbvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gt2tufabjod.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gt2vmucgfyy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gt2twefqbhc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gt2otufzdeu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2kyarjdcg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gt2bjmwznfk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gt2abruowcy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2xbiahyvd.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbxtvlhu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewxjagbv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gt2lzfmqubf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2jbcktqub.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2nnuqaiav.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gt2yxbqyajn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gt2qilabhav.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gt2mpzerjro.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gt2vposgbcm.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gt2fbzjcdlp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2zozvolvt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2eqqtzewx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwmaydxk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2gosbwogg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2nffeuffd.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gt2deegotfu.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gt2bjrdaclj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gt2bbytwfrw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gt2zkgillvv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gt2twufrvff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2szqsuxfs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gt2tqsrhlbk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2drfjvsev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gt2dtrzacdd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2wbqaqjso.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gt2vhvwzqmt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2onkhjahr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gt2nkwrannp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2uqgjsxzt.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2dvszcuqq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gt2ssyizodi.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gt2ssmojhis.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2bxcoutrk.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gt2ytuytirm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2skjirsaa.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2wmfxwwuw.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gt2qzrssfgo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2vkmxfynb.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gt2uflwlcpu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2oeodfnvu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2rewnjiog.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gt2kagbsdqo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gt2wdwaevkw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gt2jjaokqns.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gt2nmntyddz.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmeyetme.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2kygnpkpl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gt2sudezzdo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gt2ojftnlra.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2szxlrixi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2vtvplrsj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2twineiaf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gt2kpvvouyy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2tobnsmuo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yjqsruhe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gt2ebhnembr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2iytmpyso.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2zdxswwpc.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppkxqhxh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2bhnsxbny.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrvtylgs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gt2zoxpzoit.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gt2azfqimaf.html

);
来源：http://dali.redwolf501.top/Article/details/gt2avkjqlpn.html

[Q02] 创建带外键的表
来源：http://dali.xuanzx.com/Article/details/gt2opqebgoa.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2rgsypgym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2uijxcisl.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2iaggrrtx.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2ktmizrkz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gt2ylvtxrzs.html

);
来源：http://dali.wangdashe.top/Article/details/gt2ssgjiedq.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gt2dhwpmgjz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2cgglcvvt.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2jbofvhkv.html


<!-- 参考信息 -->