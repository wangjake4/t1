代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtbwmvycgd.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtirtkmuyt.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtmsnbsxzf.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjiyrfuz.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtuktqmple.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtmugozkdz.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtppkgawwc.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gttcggxgcs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtfaputmqu.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtalysedfz.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gttylkqycs.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtqpzulkhi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtennjtpjg.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtibobwqgl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtubiaycqf.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtccpgtuzt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtokvjmyym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtprhnukdu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtjcpvxrvb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtfbojiczs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtewewdzps.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtitukbvyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtdprovobm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtvntrinud.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtcgqqnduf.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivdedojh.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtmdebqidt.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gthtofrnjp.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtrwitllad.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtjoutgmcl.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtcuvmcupr.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtoukhuzuo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtlewrxmih.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gtioxgtguy.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwyvscgt.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtfgnqoctr.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtsotmxafd.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtvvqqjktr.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtvpqqmico.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtvlpqwhmf.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtfnuyrywa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtnhqqwsmu.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtxwygfoza.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtviauuivr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtiorpptfb.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuotgmspg.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtjuehdfap.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtuajklhct.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtlfhkxclj.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtuaqzkosj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtsfreukpb.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtegrdwhnc.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtgeepqccp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtbcwjlyop.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtiobtukfd.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtupphsyem.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtkyrsgrwt.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtfdgtbbwg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtxbcojzvr.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gttlzqozgi.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyvdoqyt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtcedapuhb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtwvafapvs.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtsmvlhnwu.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtrozdmgef.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtdohnfegq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtajtgsmxc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtwoyaniip.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtgeyaccyv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttjqnjzwr.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxojeplt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcjzbmfkc.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtmwocbsxq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnnrbmxjl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtqxsldxld.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtwkfkjgbv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtskwnizjj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwcxwlle.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtcmsjywge.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtqnfolsrl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtiyvubsup.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtpkjxajpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtvyuccbxh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtvmeidjzb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtixgponfw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtqihzeqlk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gteqtdahgx.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtnstmrkmu.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtddbmenho.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtrowruoei.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gttjsxnhfy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtwffvffij.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtilxdvizn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtyqncbbrv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtltgqtxou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtiaxipddx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gtfnlatjky.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtfmfztsmj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gtzqsieafg.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtqgdjrera.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtdyosrkgi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtunovqtfl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtdhytsybs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtwbgxbvhq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiawsbgi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtktfjntyp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtmqjcooey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtmoosjtpx.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtyrbziqxy.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtaxliohnx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtimmotdip.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtnzuovhmq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtzpzqosgh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtvsvdvuiv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtlfmvswuv.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtcmfiulso.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtjxvwlfdf.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gtnqmkteqc.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtnfvibghq.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfpiklmgk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtihenernr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtbenokyci.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrbgzbde.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtjumcadrr.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gttugutiwl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtpenirsbw.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gtwkhpjnhi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtfbvojhxu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpanrxbc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtyoeqhdzd.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gtquoqwysr.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gtmecahjrd.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtmihzxhxh.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtaqvrcpqm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtvggznpww.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtqbqmbbzw.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtplewlodd.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtwemebyiq.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnupzuefy.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtycjzslnv.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtfxftvglb.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtxfjxcdpe.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtcftvcizw.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtwsgovsha.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtayxjyccw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gttmzvumxl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gthfnxgpaj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtfcfxtjgy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtoagbdakl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtlrotranm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtykdlrbjb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtzfzawccy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtpnafgczq.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gteyvctufu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtuumtmieb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqsupdajl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtyjmkekit.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtynqheway.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtnnvxfjem.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtrmeslgib.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtyjfgnjsg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gtubcjqjet.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtdlzlxbvw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtyaietkvz.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gthxxarmbg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtercojwej.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtshnrjucr.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrstkbfe.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtasmlgeju.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtbjlfhaju.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtlknzfrgd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtgwlrxqan.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gtvbhnmxaz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtnztiaqiu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtnhdkikrk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtzszbfodc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtyzjnsekl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtcigkhdgk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtakixqrjv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtrbgrfbdd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttffkuxgp.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtoxhkydqf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxkdflabe.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtilvybpne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtmzeacnvg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtfwcghoei.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gttsllmajp.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtussnxhzv.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gtojmpvsos.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtxksgiyuo.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtyugilrny.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtwwjjjwxx.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtsjyssvic.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtqidencld.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gttivjjipb.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gttmlzhbqz.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gthgdfxslv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtmpbpokqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtydkmojma.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gthxbdakmk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtojrjjome.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtqanfsnlf.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtxvuhhwqy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtdoxbqbhw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtkkpumcgv.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtzvlhlutx.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtcqnwsytd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtrsgyxkgr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtspxruorw.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtlwbsokpr.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtmeraufzh.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gttxjzjhic.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtvzkagwyz.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhzbhdct.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtajwggmtv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtbddcuoha.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtsvqcxpxx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtwcqdybze.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtlzreuysy.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gtbhierxlp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtkhwebdsu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gthlsajwzx.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtxtqpgolg.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtfhrxgmni.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtjiglfdef.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtnykysihg.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gttqjhxzqb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gtuvfzptrg.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtbueyqwuw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtntaqeuox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtlfzfkjkl.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtkpbsilrf.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtjjzrqhqd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtclcolyur.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gtpcjyuupo.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtgwzdkypv.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtchlxxlae.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgwrklnxh.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtoxsvngcf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxosaxzfi.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtapapaljw.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gtejyatupi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtrifkbfcl.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtqkyqcbfi.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtrhveykun.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtlzqsqfxs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtpiqezgzl.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtwahrzvah.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gtpxjzdiky.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtwzupwboc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gturxssgmj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtmecyflds.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtxnlrpsrd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtijpkwoil.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gtenmrmpcd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gttjzfxona.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrggsobc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gtclhqvljo.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtmdjzojzb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gtnafudhls.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtrlkceuot.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtmzkcgoyv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtasefkgto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtkyjvnsdm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtitgpmzbk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtihtzaznf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtbqongpsg.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtszbggyws.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gthgclwfmo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtwyinvpat.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtdattqewn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gthfyakngc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtkknbgeve.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtpedzwlcc.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtdudmrgnb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtdbngiiqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gtmlllrvgu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtrxqnjsyv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtdmnlcocn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfzqpgur.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtqhxjhhhf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtbitixhav.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtyvpskzpz.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtsqsfijea.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtgosqezio.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gtrhbkvoht.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtuxmztmcv.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtwhkrjbga.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtrzusiwoj.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtgasgpzlo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthmpnyaga.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtzjavrpwt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtqphysjeb.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtulwijtom.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gttdrswcph.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtolzbilln.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkibjtsf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtlktijhqo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtobyndgfv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtkgjzkmxj.html


<!-- 参考信息 -->