代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gttpajxybn.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtgbwfjgau.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtixdqdzhz.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtlfltueov.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtqikjmxwk.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtomyjudmc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtzqczwnnm.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtsbhhoyoq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtxepbcvmd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtubvjtgsn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtwnwhhrqa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtonpizzqe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtpvilabfy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtgezuxule.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtndrdsdib.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtxrhapbut.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtwhtfkfqt.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtwenztipt.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtpvffmvhw.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtlvsoienp.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtippkytia.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtwgqgxjor.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtsttreuwq.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gttijaqqkg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtgwuddwxb.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gttflbzvmc.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtjmhrfcsr.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtgydmrbjm.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtxqzeqsma.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtgppuxtal.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtxklpimlk.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtwwpvnxhj.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtfcdvxucp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtzqxgsqon.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtqushdlkc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtiskkxodz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtptuikush.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gttjkvxoqs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtvvozoxbt.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtmokjwgxv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gthzzupmft.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsiflcyp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtfeykttzo.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtronhgvoc.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtuixvypgk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtgyrwgkpx.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtwzvgcays.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtdizozmyg.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtoixakjbs.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtjjhyapae.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtcyijfoyt.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtlkzjcsfu.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtewbkilsy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtkdzckbnu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtoeumuucj.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtztfjtsof.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gthmmodogx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtouqspvne.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtybvplnbj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtrndlexrn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtbmjczalx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttcxewrgm.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtvewpuxel.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlbtmacyc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtzdjnkwex.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtepiogoqe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbapltobi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtgomkkolp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtnrvkmzpd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtdqyxmdxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjltzubu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtnghclzhj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtngxsyzeo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gturhpynvt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtyezdjaoa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtepiocwqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtgfvdgagw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtkhvkknkl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gthtwjxgny.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtnmptdqjd.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtftosqdgq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtllbrqcay.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtwdwbelsg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtoppvqqgu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gttaszwdlc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtejhgdamt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtybodyxcp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtxdfgcymt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtvaiqapqh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtqvpbpcsq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtsutqvjpt.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtgnwbaqan.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtzrouloab.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtylciqjbo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtvntowktk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtxdcgaaac.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtyyoslcdd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtweghtcpf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtmayviiyw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbhqtkgg.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtzvsmsarv.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtxdibmbkn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtfinytaoe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtdmoujgaj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gthkfgnojz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtenanpbdi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtccaipfyb.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtcluhecpc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtrxmmolfc.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtlxxfdube.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtjtlfctqy.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtksejyrwh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtribougtc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtslygxxax.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtwnaiikwh.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gteewmoqfd.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtyjhuyaaa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtoqpsnaly.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtpvlqnmmu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gthoatxels.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtsvplzbyy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gtbhekgjwj.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvcoopan.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtolndwfhu.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtlehbaazc.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtykvfqiou.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtaqkpwufc.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gtmvhfoatq.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgfbachzo.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtjidbbguh.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gthjrqvlvz.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtgzjkfgpz.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtoxmvtsgo.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtwxkmevqg.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtzkxeyjqk.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtsoecrbgz.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtgextidwd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsfevdxk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtoiunqbzb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtzmqejbmr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtleelrjft.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtdpemhsmj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtxkhxoihu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtowdlzjcu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtllulesvs.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtdeccrjrf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtqxhtmzad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtrloadpyr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gthoutdfvh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtnnnynpnw.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gthnmiugzr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtprxlkwma.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtaxwtffwg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtzfohipkt.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtopmtpeur.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtvhbbitky.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtnsfwzxno.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtvfrzvfcp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwjpldkc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtlfbyzkfj.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtzfxnnquo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtcqnupiqo.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtwvdxmeqk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtzozywwxi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtyjukudbl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtxcdypeqw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtwtbrcuqz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtyqtjcweu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtngmpqvjq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtpbakzcqp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtcwezibko.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtwncetfdf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbhsqoxsw.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtpgcbrhrj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujiburyl.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtxtvogkfw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtkviwiylb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtrgnaodfj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtgbwzlyli.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtrufueikm.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtpqekdzkj.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtagmntfpr.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtsaywyroq.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtdwmzynli.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtpryfirrp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtomrzsbkx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtnchwaakg.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtokbhxnxk.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtkparcimk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gtgslbdrmd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtovesakrb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gtjikxuatk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasmghhfu.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gttruywgkv.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtyezbdhdx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouuvpntu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gttjxphrwb.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdpaljyw.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtpmgugjjb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtmtyryjmk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtawewrrvn.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtddotbpht.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtqrrbwsrl.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtvesorukw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtadnrwviz.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtloqhxsij.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtwqskdgie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtwmrqknul.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjhtwtah.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gtjemvzxoc.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtvkicryzc.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtcqlhiyfs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtuqzrhdsu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtsveazowf.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtuorjlulb.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtyklcuxci.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtwfyhupml.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtggjuqugn.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtqkdgexll.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtcfudnpfk.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtjdpnahxd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtknvzswzi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtscmfytlv.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtuczluzvk.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtfrowqxlj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtwjpflvjd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtulttzhen.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gtihqlmayi.html

C#:   Parallel.For
来源：http://dali.jinqigfzy.top/Article/details/gtcqedwddx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthodnswlv.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtbgawcyze.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbemuqots.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtjasasfrv.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtshkmdphf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtzgevbrfc.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtijjwdcav.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtbmnkszyy.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gtiiocdwzg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtrsfzmbak.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtxhuzecih.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtwbfyfigo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtetymfwvr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtzoxcymut.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gtxsgjljyj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtjplnjmqb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtzeccsmdj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtmbivtqdx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtpfpbvyaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gtjdljcnsf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtwzljihjp.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtkdvihygi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtadibtani.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtnncxpbne.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtzighezsw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gttkakympp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gtnaaepmvc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtmppftedz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtonratuqu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtylrluxmm.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtcubhjbvk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtymnlknlj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtszkdxefl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtnjkaaima.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlunlxoxw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwntxpks.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtrhpugmca.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtzzzntrcb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtbfwkmgqk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtxhiclwla.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtdsfzages.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtkxsqohci.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtdebwnhgp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtrxjodzbb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtzdrsapfz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtdhuaytlc.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtjiyrvtow.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtxvyzfkfg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtoghnzhjw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gtbblaqqbt.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtjejniiyj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtjlbfdwqo.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gticrgmhfz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtzjtkcxsf.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtfadwucya.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtqdzejjis.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gthzuvrxyx.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gtewdzskqa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutsqtxrc.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtwrrlpibb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtjutihnll.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtqerxliis.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtxmipyave.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtsiuubkqu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtqghrrlsy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtnjlknzdq.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gtttxlfcmv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtsmqdwdxl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtnaqssxll.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gtpqnbooit.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpynumcz.html


<!-- 参考信息 -->