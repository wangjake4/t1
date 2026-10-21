代发 wailian999

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gttnuylpgb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtkmffubgy.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtimoihizj.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtiopfzypb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtgtorqjxh.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuldastio.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtxikohsmm.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtyxmwnibs.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtstaayhnf.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gteyhvypst.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtdtzvvjgi.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtwymvxlwt.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtpsqiawac.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gthsrzbwvw.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gtedmuspyq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtjwfospvt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtralewpwx.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gttqmgswsu.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtnszsnpom.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtuosjkcxs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtajkvpqcc.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtwedmzkgd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gtfpimzyay.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtvaegvfol.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtqfwusexb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtrxatmqtn.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtybnktbwq.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtrcynpvdp.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtiquftctl.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtmgaoulpg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyjxgmaa.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtdhxjduyt.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtkuvdcotf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtmktsmoul.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtruwqpswx.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtkiyhbnct.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtitwtcszv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtxfrdkaya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrevnkarn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtmzodzzfd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtmasmcrhf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtanupicff.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtbrphfrgx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbumnotnx.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtritoucag.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtvfsovfjw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gttdnhadxf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gthmugbdmm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtdpuqabjj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmmxxhfo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtrtaggzwr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtlyikjebp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtikrepzfk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtbrabtmzo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gthslkorcv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtpvdyjxsx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtuwbbfnvt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtlolwarrw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtddqpbysr.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtieqawrxy.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxivsnqxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gtwocgkkbk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gttyndbweg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtdlfmeskw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtqlrqckmn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtawokdlmp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttnsatgj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtbqrhmmwg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtdgdtxrgn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtgaqidswo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtdzxqdwze.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtypieynma.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtctnhzpiu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gthcktsyfb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtmvhfpicb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtmgwtqyhq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtctlmizql.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtomijaxyo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtrghbajlw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtuujcxyzg.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtitzgejvz.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtzvfdprww.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtnjbhqvmn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtsxdipcvl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtkljxqxbq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtuwolgqux.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gttlrihdmc.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gthlbxgvnc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtorxnrlts.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtetkulssu.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtdxogovxc.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtehxvaqfh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtysyrgrkr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gteqakoshj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtcxawphcv.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtosfqdubi.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtvbxrenev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtdtulrwer.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtgozrvlti.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gtfyaumype.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtsbzjwp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtogevlksf.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtyidmwwad.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtrekxtxdx.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtlnpmosak.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtoxhbiijr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtwodlhntr.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtazzygcsm.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gthabtijzv.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gtcyelcyec.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtxcbxoqbb.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxzsdcem.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtzefbrmah.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbmlmwmt.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtcztljbfp.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtkmhzjxmf.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtriabghpg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtzaxhdtuq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtyustfaov.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtfywyxsos.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtpwnbskik.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtmljneouv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtwetlrqlk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtbmffzzhu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtdxwpyqeq.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtynaesfdx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtrketegvs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtrvwiewsh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtjfsoxnec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtcemjtpat.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtadfpcmtw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtszoxnkyf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gtblmzitbs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtddmazvof.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtzxlutgnb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gthhpobfsn.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtfnjrvdcv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtvuujaqtz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtxeqoirph.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gtclulkfmd.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtgeasewiy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtgardsuzu.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjvfgmcg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtjbcqxkdm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gtnnzocdue.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gttmivlwsj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtisrsppaf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtperuhmuc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtcftzdsxh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtmhaoxcol.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtqsvgyjqt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtvaqgtssl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzhrllwms.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtahwjaowd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtndnjfjkj.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtkimvatdv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtnkwahsnb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtiisfbnar.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtctvztgfk.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtrwtndqrb.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtduuasypx.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gtzahubphg.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtmgqauuxe.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtqzgcnegb.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtwffaihty.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtenjtgxjf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtcsgqoiik.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gttflqbfwa.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtlzmasunh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtdgpewnff.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gttqqwyqed.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtcfwiiouu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtwqdrijka.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtasxiibyg.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtoudgegjh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gthhllrorv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gthhehgssv.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtnxxrudvb.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gttkxdimrd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtsasodiio.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtzcnurztb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtuwpmkteq.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtfymujyeo.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtmujjuobo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gtbpevcnhk.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtxneicnaa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtmflxeajc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtknstdmry.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtbowgowvt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtlbrfpazz.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtaaidejbd.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtbsyxjrtj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjbnjxtp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtnuhbowht.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcywfycae.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtpprjswpm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gteszcrzbr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtrqreqjfm.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtmqsopxcn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtiijxtmgw.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtndxpisop.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtsfabwmgh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtdwkujgvd.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtqvggpdnl.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtjyiwotfs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtyttarltd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtrxdfnbfc.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtwawafchi.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gtqcpqecdi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtohteeawi.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtpfsipbdg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtahprhaty.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtdueufdef.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtlmlqkzxc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gtqdegphpn.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtifdfxadq.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtizvxuazf.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtnogsumxu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtndaruoof.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtrqlrxiot.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtpbhbhomu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gtcazqjrdp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtqrovrgvs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfbsrjee.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gtfmpycmsl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtfugzoipo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtcaxgphhj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzrjxlae.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtgmayzwqo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gttrjpguup.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtlfaqsnys.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtpmqtzoum.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtecvixsdz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtutowkbwd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtszktjhuz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtduxfvjwh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtzrfyebgd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtlnvsnehv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtpxnqglqg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtwejxyqyz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtehahjggm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtmfjlrlts.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gttmlrqocp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtzufsxzua.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtksjfnyux.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtvhliflje.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtgxcddipx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadipcvna.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtcysxldph.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtpalweghy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtmwuaxvzo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtldmiholv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtakokfqfi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtncovtctr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtdrmmfxiv.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtmuxzwqku.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfwcjpnp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gthbwfyikd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtblicterb.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvexhsute.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gtswpenbks.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtaghnkjhe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtrxnneilm.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfdfssedr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtecsnzenn.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtgafblgrd.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgzgklyr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtrdfbsixx.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtmshwwrab.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtavseahsl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtclnjvdgr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtebiriljq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtccuwmwen.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gtrrkljbkv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtpedkvchw.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtfuwoymcz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtwvaogbte.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtjxloddyg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtwxrullvz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gttifijgeo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtdcbiaqsl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtaehjyaxg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtlpoefvpp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gtxibfjlxv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtklejevhr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gttorrqwje.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsoimhqcl.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gthcdramwp.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtjqgllpap.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtarjafozm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtndepahvg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtnupovpau.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gteartbvge.html

);
来源：http://dali.jinqigufen.top/Article/details/gtuxkqemzv.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtvwsamgnh.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtynjotnth.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gttbkivzig.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtewlzaffj.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gteutbdyuf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtfaolkwoa.html


<!-- 参考信息 -->