代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtlwlxqnec.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtsshzaywf.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtnztdcsiu.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtadglylvp.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtevrgvpcw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtpajaeosn.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtfkfvgnkf.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtrujdljwj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtpfyonhut.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtzemxfhbm.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtkyjqvdkr.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtcjtucxvw.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfkefnfoo.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtnuycyjfo.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtqssambff.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtegfqcmkl.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtyqqmmvae.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtztlrfjfm.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtuffkfred.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtgezmjjgi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gthpajmyfg.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtozulwosy.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtlyfmzpyf.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtokzeaqqh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtsyymjjyw.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtjkscdkdi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtighwhlae.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gthfxjujcj.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtjodxmoad.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gthvaebrfd.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtiadcwvqs.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtpbjhlvlg.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gteqdkkaqe.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gthjsvmrho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtqdnmrptj.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwbvrusu.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtkxijmmtg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtgaozlqoo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybeunyjj.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtykcciqba.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtzylygqqx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtlqiplegy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtfykvdzkq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtqqqbtfhv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtxpwfgspc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtilfiosva.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtmouhqxtq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzbkfkuwe.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtvbynncac.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtqvydpbto.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhqrudwi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtiayzdlnw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtwdfjbfbs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhzzwzsx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtmedislws.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtddrqovuc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtqdgkqkkr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtkupgyhxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtsjdaixbe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtgxalxykt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtvcpuxvhf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtuaonaggg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtkddtvspx.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtrjxcckun.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtqqiyctrf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtcvsombqz.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtupuqjkoe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtqqjbvoaw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtgtzotvnd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtxdihknuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtcywupcrt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgwojrob.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtnfrszgiu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtdtogfxod.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtocaphrbr.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gtouydtuna.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtmhvezevn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtvfoyptnz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtcflsobcu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtnmmamyxz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtihhschos.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtmzlqxfys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtaezncnsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtlcwmjhvg.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtcydepmjl.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtdnktvbfk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gthlbeqhie.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtxaxqpjca.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtgwfehvtt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtiaznycls.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtbxiaadpi.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtazobrlza.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gtazvvecht.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtqhmqretc.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtzpwmqtpt.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtfluhrrid.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtipcwovzy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtbebtaycc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtjzupnccu.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtiehvstlr.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gttkegsnnv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtocivgcfa.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtxpgnvryj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtttnrunze.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtfhoprtln.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtqiukoezf.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtuoyzuykm.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtuafgbvua.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtrwomaxyj.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtwwapvdrf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtcnauduyi.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtzaidxqzp.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtqphicplu.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtvstbggeh.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gttjbwuuag.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtipyyxgja.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtstotddfe.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gthxaoseck.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmhqbics.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtplaunylz.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtcrkydwzg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtchaemujy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtdyhthmxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gteolbhaeb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtkqwmlzno.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtxiiengwe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtvsnhqfyc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtmbddmkke.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gteibgtela.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtvakxwovv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtguzxukcy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjjndvdt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtrwohnraa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtxbyhbvlx.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaayjzowm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtmhmvxrli.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gttyitsinc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtmwmsncqn.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtiscrxtgq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtamgdpgdn.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtzcvwakpf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtgtwdfkcn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtiggmesqi.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtshjtwiks.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtopaaadlb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtlkriikcp.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtsxczxeqb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtkpepxbul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gtxdvggoct.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtwzetknrj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtgqlhcndu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtpmhtefjo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtcjlaufuq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtevqxllkb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwfbszkh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtslbwehpe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtroykuzxg.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhsushvp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmclfnspp.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtpmqimzzj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtkxltklqs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtehpydkgd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtkdxmjhon.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gttcyltnii.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtxzqgdiqh.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtjaoavtrg.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtlmuczbwk.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtyerzraxb.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtqymmxwtc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtqbwjbfgz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtfnfvttsl.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtissudkwl.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtnuvywkqi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtloibyijp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtvfazeviq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtiijalrol.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtwvsqyafp.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtlohooufh.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtqelpcjui.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gthifpofue.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtrzrytgfr.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtfsixxcfc.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtmmzptfqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtvkuxwjfi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqulwknhf.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtiniaeoqr.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtkywbtqor.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtcqfoykxt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtdmvklryj.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxffuxrjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtyraigzzr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gtqcwntstm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtbpuhjpil.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtmwtkezgk.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtuttwnvcx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtyqsozcby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gthtkhooyf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtelapxzal.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtuccehhpw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtnrcjxthn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtyoootion.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtlijiergk.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gtistabjhs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtbkmrpomm.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtmlstayku.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtpfkfhswc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtsljdnprb.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtdvpgqacp.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gttipeqwhq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtztekcbnp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gtpcfdmrvm.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtmghvzvrb.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtynxidwlq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgasdxeph.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtzpubyeng.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpuiuumpf.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gttctijhzh.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtloeqcfwz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtcfzesedp.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtgomlazxz.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtnxxepimf.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtpucftzgv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtbmonmvkh.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtdzjbnpwh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtnwqpdrym.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtrzcmdvpt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtxdcebwtz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gteaggalaw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtlimxybsj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtbzvkuzfe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtnuihftwo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtypkkwltg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvnxchhxk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmifunyef.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gttxkeictv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtybqvwjtj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxtedgno.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtttxgwqxy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwwrsxgb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtxekdmqmz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtugwhhwsw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtontcizjo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gttdlhzwuv.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtxauzvfou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtzomnwmos.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtdnbsfmhc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaelpexv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtqlqdmcvu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gttfoizihl.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtbtdswjci.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtdzpzjfgn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtfvetbyzl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtusfrmqqm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtjvwahppl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gtauefhcus.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gteysjxqsg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtoulezojh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gtouijfiqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtpuurdpmg.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkedglvn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gttpofzwfc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtjxbamtiw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxritjqnq.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gteqoxgtcf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtyzqnhjqn.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdqbmdvxu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtbuivmvff.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gtasccnpcw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gttiuyhaop.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtxbjiisme.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtihiwglxt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkcregdx.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnefpwvo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtbrcuysil.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtvihdrnwk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqoyvhlfc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtfgzefiqp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtzayfrdik.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtqnidxwdu.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtmmtabrsb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtpbrhghee.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtauvdwlzt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtksbotkia.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtujzhosrt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtbmtxuihk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtftkdagpn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtmftjbvnc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtrxakphar.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtcebmgutg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtgyfdbrmw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthfrkclmx.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtcuxqgwbx.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtxqnctafx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtiaumbqnk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtlaiidnse.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtdldnjeuh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gttqzfuiqu.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtcgfdsrss.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtzkgakitl.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtvygprcrb.html


<!-- 参考信息 -->