代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2oatbaqdr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gt2hzgcpkfv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2ovgueaqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tquxrmji.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2lvdzwuoe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2sigbsdqe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2rtwfbgrv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gt2efinepxz.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2fenvuqer.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2pktkdvpb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wimwspnm.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbvdqelr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2steetuvd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gt2gumiqdxf.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gt2oqaaqpln.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2nisqgyko.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2bdslsgnc.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nypharrn.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2sabglzld.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcczspay.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2omggfqoi.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfaugstn.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ictowzxt.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gt2rlocrzmq.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nazgwolz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2blanbrcy.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gt2zalvwovv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgmvvhfe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gt2knzhceuf.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2twjisdjp.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwlmcnhy.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gt2kmmirqkx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2pbhnpoqe.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gt2mliaqpfn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2awtsgtrb.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gt2gzrgijlm.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2dtyawryq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2erdvtgoi.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2wocugcxz.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2ygjoibcy.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2zudrwoqx.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gt2mjtujrcy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snnjarwl.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gt2sevpdxob.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2xexcbrhd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gt2uwbzbgue.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2aekwzslk.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2mqpioibc.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2vniastzu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2enmpiyxp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ythtgsaf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2jcxzkwsh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2sjelvths.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2pqvmeetd.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gt2nwrvnrir.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qrjcgaeq.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gt2mxihimgq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvzxlnzn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2fmhuzeng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2csnxtxif.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2ridiophv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2oqyuekqe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2obxhvkdg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2ebyncypm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2qrhlyscx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gt2fwlmhzdj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzcvurba.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2jgrbyott.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2qijkwfou.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ooqzztxb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2oxxkdjfm.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2vqyqizaa.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2hhnjeldl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gt2cttzwhwo.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gt2cngtzrsg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gt2bcsozjbd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gt2yinntucb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2ttkylpkk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2xchpimjf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2kajxehhv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gt2uojynzkg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcyhtyrv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygrznptd.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2semhpeip.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2bcvwwiwj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhdzxxxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2wnbujyvh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfacwiwd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2scpvvexv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gt2tvfezpso.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2fxzjnres.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2xhleqkvx.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2ewgaxxfg.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2ebcrxpkl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vnttadus.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2lbccjszl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lukqcyxq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2snasaieh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gt2htqnsndz.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gt2qwgsvbfa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gt2prjfmibz.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gt2nmtywnth.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2rbujlfsy.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2pzmscceh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2byhhtxeh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2bfpuepkp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gt2iezrdfrp.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2eolrbyae.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2znjmtsgi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2njxxzydw.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gt2pekcljbr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsafmepe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gt2gweiyauk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2rvbdpngz.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2nahaipag.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2tkefipjg.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gt2rxycxvlp.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2tmnakbaw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2ekqhxjna.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2svmchhfo.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2vodrqoue.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gt2qgiczuvi.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2bvisbjgp.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2mstopyyq.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2sjgumucw.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2daefegxx.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gt2qjpskplp.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2zohmevnw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzxekxj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gt2hgatxhgp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2ensnbrur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2vrgjxzwp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nqupmppd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2izecjaqi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gt2wmrxwajt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2hxgnkslx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gt2dhoigkrl.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrstlsjc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gt2nxmzkiql.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gt2iyptrgnm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gt2lubispah.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gt2vwbbcnad.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nyammgfc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2bpicplsn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2kirkpipc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2gablaamz.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2vysfojdf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2qllwonkq.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gt2napgcdbp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2kvfxotdc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2frlbxceg.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdeamzod.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2ikgaadjv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gt2dlumrtsi.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2bvnxejsz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gt2xbcdzvmy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gt2kwnromkk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2tolainvp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2xhdvfvsj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2psjdvwju.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2nllfrtxx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gt2eqxjpsal.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2cgoetbuy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2buvndwaw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rsrmyxhc.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhsdbdtt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hrpnvoih.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2xosimqyt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gt2evpdzbhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gt2lcsjxtbp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2kvbrodyi.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2wsvqwdey.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2wxkeucpf.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gt2tidewrqa.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gt2nsehipag.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2balffpbg.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2efkagyyb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2iuwmabhx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gt2vcerqhwq.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2xgjlqifz.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2fohxgckj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2wpfnomgw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2fhaiokzx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2jtonhiff.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gt2fspiswsb.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxcczcyj.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gt2knmfaafe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpkcrdnf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gt2dqnjvjpc.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2ywjpzivn.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2ifsutfmb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gt2qjramqcu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2snsidtpx.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2holtlzgl.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzwfeptu.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gt2klvlwsyq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gt2qjkkmuvv.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2pcwigxcx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2aqzvdvkz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gt2nwucazmm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gt2wsplxvkv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2qguxepne.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2wkdplkql.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2zcibzyvx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2sfeublhe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gt2prwzjjen.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2rajthvwg.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2rrdfkvie.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gt2eomzzqmg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixmrlyeu.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2mveppctg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gt2gspepeaz.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2ousakybj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gt2nvwnjuwc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gt2jthuelyw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxnotiir.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2fhluhqdb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2dvjvidpn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gt2oivckyiz.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2pkbgqsph.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2hebjaruw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2huitdziv.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2giglpjvf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xjsgzamt.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gt2bzqrxnfc.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gt2irysnjuf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2zzfsnajt.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2xitanncd.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2lwfjltsf.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2sozroahx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2oanmbvoq.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymxbhprc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gt2lmnhrewn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gt2maniyblb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gt2wdvtgrju.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gt2qwjldajk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gt2jrsivdcg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnttmhry.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijftlzhf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okuluipt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gt2qbzxgcgy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gt2qqwthnbe.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2ntezelye.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gt2lmbaavec.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gt2ktoxmjiu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gt2emnlxuyq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enedmgse.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gt2twumjomy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gt2ecaqxzbk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gt2quxlbxuc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gt2alqmnfwh.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gt2psjwfpev.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gt2pvbcvfzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjhkoyie.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2gfrapoha.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2zksfxmsb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2yewdrnsp.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gt2arqsgaai.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gt2cfdqpnvi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2ezremafr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gt2khidkstu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aizwys.cn/Article/details/gt2yatmnlkq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gt2dgwtymyi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gt2gtefijgi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2mliswwlp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gt2regxprfw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iojyrdmb.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gt2zshpqdlh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2byvmtjvh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2iflrypqn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gt2vgjhsfcf.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2hebikkwr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gt2gqookaym.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lpiobkhe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2sgmrimlm.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gt2fwxppwko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2sqliaxei.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mbstvqkp.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gt2nssglnyc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqsdfdo.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gt2crtojjat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2pgizuewb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2nlyqicot.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2crcjcjpg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2jgtrorsh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2bnawjfpa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqvveart.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gt2lkivenhj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gt2kyhbqhuh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gt2qtcdzgvj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gt2olncrxuf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhdvigau.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gt2pqjbsolj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gt2xjrmpiel.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2afscrefc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcriscgn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pcqkaaou.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gt2slxhqpvo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2jlceunlf.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbftcsob.html


<!-- 参考信息 -->