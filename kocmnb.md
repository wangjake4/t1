代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2rbialyiv.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2smojjmln.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2xpodxeyr.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2dshponqc.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2larhqbnw.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2ldlwxwtu.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqkkvedq.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffqwwihh.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ublkkyqe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gt2rogcwouy.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gt2vmnnrtws.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2rffmjxqr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gt2sgefjvnv.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2pgwarhsw.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2tscwtkuk.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqzgawvr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2nvclilvk.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2juyradyw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gt2mekarnzk.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2aclcxihv.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gt2ucxjmucp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2grphtinc.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2apwluvln.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shucpdhh.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gt2tdjmvjvs.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gt2mxftjjsk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2ivmdmnmh.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2tsddaett.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpakegkx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2qqorujno.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2rwimxwjn.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2qpkywylt.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2boszctxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2ppnzwzeq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gt2emwszovw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gt2vzrjqftv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gt2raavpsts.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2laescwmf.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gt2gcvyspxp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cruqanai.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2mqbdijcj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkhfdlrf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzjvgezv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2gsoqbcqo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2zlkppdbp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2bzigqzwx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2erdfknya.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldluqbgw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2escutnkj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2wjvaxtgb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2rirutgvt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2brtbsyun.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2olineyjl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2afgxirpu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gt2blykdcyo.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2mmwyylgp.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2wnyvlasm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gt2cpncbimv.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gt2lgmpgpjl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gt2uxehgoce.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gt2irycaqlm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2ufchdmve.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2ccrswjhn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhujxrgn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gt2cqrpzcxz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gt2fzutaydh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2bwumeilg.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taptqgge.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2oqwylnum.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2tfkmnhbq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2yclcblmt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2cdfwfmnr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gt2givkviat.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gt2rjigjzsq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2debqewvu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpsiqygx.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scljdann.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2xjfffpvj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2bzppygho.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2aguelkru.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxzwlpbb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhufuhob.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2wmijrrqc.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2smiamryj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2wndzhndy.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2alweeuwj.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogyxnmdn.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2kpusdcgc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2ktvihwbj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2arkoeyrw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2jgdchvbl.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gt2lbgzaopd.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2xwzzlmjy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrnlmwoq.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2udxrvyqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2vdosckxw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gt2duxdtttf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2flefegml.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gt2jovksjbh.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2piawcmil.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2cjfnwiqh.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gt2hpkuhvyg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gt2ypssjjzl.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2rmyqqhka.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2nouncggx.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2wchritsf.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2yugjjbqt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxlhckc.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lckxnecb.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2tpzvybrr.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gt2umbcvnhk.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2znuytjuv.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjujnyue.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gt2ipafexvn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2hdictbkc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2dregmarx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gt2ddhspnvs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2tuowgqsr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2inwrggbp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2aqrbuvko.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gt2tarzocmc.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2yzswvxvk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gt2rywrmcvl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gt2whdlvteg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2ddaozsii.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2nwousfmj.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gt2neoqxrxy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eavakdil.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2qbsdultq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cdqxufls.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gt2nemjgdqz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gt2tlocxgjg.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gt2oirdmgdn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2bylmjuau.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2roihdckf.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2letfetrf.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2hrsngmhe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gt2xrtnkjrg.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2vdmgkoys.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gt2kunkbixy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gt2bxbhgirq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gt2xtkeqqpk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2ainqdyca.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2rxxfjqem.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2yxccdrql.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2rhvisesj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2viewdgfj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2oqjzdvqi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bpfrhphs.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2gduhpcua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iekyrahg.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uomegipc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxlidrgh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2cwanfezq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2ktvwpdsq.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekkkonep.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dynnegor.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gt2zqhdekxw.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gt2sfgbrlgy.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gt2brsjsmge.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvczhxf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2ayxyhgjz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqqsdspp.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gt2qukljoxu.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2kfmdrscd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2hclxlsgp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gt2oyubadpq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gt2exttvbbn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gt2yufdcfdu.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2osorgkgi.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gt2ixtnruyv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2drnbauem.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbedygod.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phtswqff.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2tsmzboco.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2etxisrub.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2gzaxnapb.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mowacnfz.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gt2qlbnnmdw.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gt2kzkzcymj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpowqsqb.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gt2bgzsjoqd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2mbttwlyx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqwwmlhr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2gofxqlfl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpfymijs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvibymqr.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2cmcqikjd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gt2wjbklbzt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gt2kuzrqvwi.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrkjydv.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2hxdmugyg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gt2enwtyznh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gt2ufmenllt.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2jadaozlx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gt2upjhwgef.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gt2ulcclgya.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gt2nntellqe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykgiuwbr.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2oxojnfhl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2hemibvlg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gt2enwevzxz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gt2bxidsjpi.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gt2djslbyxg.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gt2iatvvgfd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hbtcedkd.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gt2rcklcjyt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2neatosnc.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gt2dviycpdk.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gt2klqunsuu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gt2vlfqctdh.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2srhjfvlx.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2zjbnwsdl.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gt2bttmazie.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gt2xhthohwv.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gt2halrvbrs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gt2uxtdozus.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2grhujqta.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gt2qnrbbias.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gt2xiztoyxu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2mbnrkfql.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gt2hwvrdiup.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2kasqfmas.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gt2trltbrrs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2vegpvnwi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2jgydcgbz.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drkyuevi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gt2kwbgjvth.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2xsjovrsx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2ydxjstvb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2nikyczfm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gt2eifiglqs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoluvcvu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2udezexmb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2qrwdrhth.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gt2ogknuaek.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdpkbkla.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2clthdkfh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2wnrvkbej.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2vxptfnox.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2plzihukx.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2jdmqwmkt.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gt2kgedakhj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2cetzdwom.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2njxnhyvy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gt2vkjaaxag.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gt2fjzoioje.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2ivakxhtl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwsevsgj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gt2qoobkmsg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrluxpqs.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptvzbext.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gt2pbczlliw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2dgqzpprx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gt2vbvdmmak.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2nwodhjei.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gt2koeinzpn.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gt2cwqzuocw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2purspbtz.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2teffdsfn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gt2pwjnnkar.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2nvtcjvrr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ocplvhot.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2stimjuof.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gt2gulueaam.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2gmlqyxpr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2lwrwpqpv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gt2aygilgik.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2olpsbqdc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gt2bemnhmaq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gt2ztgxrurz.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gt2nuuwufhq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2bylzrbuw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gt2mlwgmyjt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gt2yahqopnp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2rpsnterk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ontmwvkl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gt2esmzlxyk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gt2pkiuuchy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gt2tybcxcst.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cieeosis.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vuudwges.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2jrexbcnk.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2kuphdmxw.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtilbxtf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2twrwmtmu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oowaqstr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gt2sbxofidi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gt2mnrppnbn.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2kunkmwnu.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gt2difxdjqz.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gt2qtgzzpfy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gt2edjbjrdr.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2rgbmalps.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcwelwbm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gt2husgzqmr.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2egwcjwur.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2zblfxbvd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gt2fbzbgxaj.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gt2iwzgjxjm.html


<!-- 参考信息 -->