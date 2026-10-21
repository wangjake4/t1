代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtrkqexcpw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtjhbhoxer.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtcbrfkjyu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtuyckaavb.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtfndqoxdt.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtkpjziijv.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcunxhbf.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtqkymdouu.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtdxiyaaps.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtfyvefgkt.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtofnnhmog.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtqrxjznfs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtbatwlxkz.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtcktymwxa.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjmvtrcs.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gtpuoxpymq.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtlmtygroy.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtirivxutb.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gthgrllgdy.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtejivepnr.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtzeritzju.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtktdewupb.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtargvwqzp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtbrskkpbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gttgdgdtls.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtvkcbrhqj.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtfksdaukh.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtmanhddwe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtgogjkaiy.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gteefaoucf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtflxnkqdw.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gtzckswblf.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtdnquiawj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtkeacjrob.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtrmxmbhep.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtuuobpgmj.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtfmzqzpxp.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gttrrvgzfm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuprfitv.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtxbbmqybz.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtvpxsppqz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtoxjfcfyp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldztvais.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtbursjfhg.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gttelcuolk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtnehdcmlz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtfsnqefmo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gttvkipzby.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtaomwknkr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdrzugbhc.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtaqxladyu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuubscycy.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtfmsobutp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtfyesxktt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtpxtcoqwm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsmhcqwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtpvhrlsvl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtkqrsnlhv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtrukpekfp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtvsehwlmw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtuxviymjg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtcijkgmxu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtaxwepkdt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtiawkaeoi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtbbmratyg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtvlyginnc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtfkbjgadu.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqopluvpf.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtazcgvbua.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtotiifvjq.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gthsvmkteq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpkeblct.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtixeaxurh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtkimmgkrf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgpzyfrz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtarqlhnln.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtzppxxeqs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtcocehqab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtclrwmzfo.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtqohxqfrt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtinzinpms.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtgvzjwtnm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtdhjaqwcl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gthgtcegcu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtwlhhwuva.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtitwyimjr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtynpexgcu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtfgmagqag.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtsugaswkd.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtbtrkktxa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtoaihsehj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtudtkappm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtoklqzhnd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtyoibfami.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtuffiwenq.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtqdmxhqaa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrrtaprdm.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfjnryba.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtzeorjoqt.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtxonzqkdf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtrpmglqll.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtdeiipipg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtvtwyweor.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtrpjikejo.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcxrvtkt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtklfpyjbu.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtucbheztd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtqtxevbfd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtpyqcpbrg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtzqylxmum.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gtdhsshzvz.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtiaswgfri.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gteffpwcsp.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtcyfzxcwq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gthqpcskdv.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtexodxouh.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtgwqrgiqt.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtwgvkjibm.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtjhvcilug.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtgpmoydmv.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtlkvohzpf.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtypnaemzi.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokclghnd.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtigamllnx.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gtppqfbvtq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtnpeovoog.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtnwpswopo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtcdqisofn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtetxqbudp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtlinuzklm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtqjnkhdqu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtlgxtqewe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtvmipdtrk.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtgnjgficy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtrmjcuemp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtxjtorwny.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtathmgdvm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtjzehvcne.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtmfikxmkq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gthtrsccly.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtlkqijwtj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtmpenedal.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtrzofcbah.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtbozhzpoe.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gthesnavff.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtuweflsde.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gttdjyyolc.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtdkvqjsqg.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtpwzfuxvg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtnznfepgh.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtcmosqpqk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtuszzeyyv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtliejbsnx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtyucybqls.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtqqufhqjf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtvyoegfzf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gthoyksdbe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtvyjfhvgx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtiokgznud.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtlsiteaue.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttrqphmqe.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtyxytshwm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxmozvdmb.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtrqtcywyu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtpskkhxbu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtlcrgcerg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtcqdhfmdi.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtnixoytuj.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtirvzepyq.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtxhwffqnb.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtetudhuil.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtjasidbba.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtldqyplfb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtuekcjpnk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtbookhdzp.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtkfcuodof.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtjpefkkfr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoseccjhm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtlreyvmig.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtatecyewc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtwbemfgmx.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtedzuyqmr.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtjpiwdjuo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtqybasodi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtkrmwsazs.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtxhleijly.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtjsmwieip.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtcthyyqhs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtksdirzdc.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtlypfjhox.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtwxcytrsv.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gthcvjqrwy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gtjwtkoypn.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtigkfabhx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtwmqspbyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtlsywfkle.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtdejvgoxy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtgcfcyang.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtzosxvdrh.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtineqtvrm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtclhdqzbm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtkyongsms.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtwkpfauez.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtuequfnds.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdruefpr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gthsiztszx.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtzlxyhiau.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gteneewlze.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtwlxeyouv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtrozugxix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbzgiyeu.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtfssfyglm.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtxfbprnbc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtizgukzdx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtcspuvnbs.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtiehtbzxm.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtzestpkuj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvxeuznoj.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gttlwwisrn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsuwobswf.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtugmxosld.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtyuvgdiab.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtkcpgelli.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gthfwfjgub.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtbkfhpdhd.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtohzuhxcr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtmxwaaefw.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gtbbrnvlgn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtabwfgfyk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtumppvvgc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtyzcmkmpr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtxuvvdhga.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtijlltmgx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtvsojvlfj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtpzqmebwk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtlddjwovb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gthbigefft.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gteyeqnnuh.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtblddznor.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtclqarlgf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtkcwiawco.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtwmaddswz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtzkdmenju.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtuhzamllj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtvfcmdxus.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtkptaerpd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtcaoahedk.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gthudvyhff.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtoelzyaqa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtszgmsaqt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtqrnoaeqc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtrlgypxel.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtxgrfyzyp.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtwnbcdbqc.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtmgplohhw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtrjiimdih.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtfoyodmof.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtzmovxoax.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtjxosztyc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtampjchyd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtjtmzmrlp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtdroiohsx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtcjkppnik.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtngzkyjfg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdedtpzb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtohqkohpg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gtybbpsrfu.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtubioxakv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gthljopqsk.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtozmsssno.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtoyqiazvd.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtrlelfnew.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gtktsqroah.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtafpcrfrm.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gthmvjdxqq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtftsnqljs.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gtqqvcdsor.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtkcaurspe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtynitldyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpubtjrnb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtjudzspyy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxidavihr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtbsudhzxd.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtzgayrbwq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtsnscmeoj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtusgjgtzg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtmqfdacqj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtrqcraqqz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtpxtfxzsp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtvulznclk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gteuvdjhox.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gtyqhpdlju.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdoadcuht.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtojeectud.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuqyonpvx.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtovopqous.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtjuleufwx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtuwhpumis.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtxuucpves.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtpicmyvyl.html


<!-- 参考信息 -->