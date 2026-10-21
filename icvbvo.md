代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtmofutrny.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtsvqpwlkr.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtgqkuhpfd.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtmpjloyqc.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gthnpytbce.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtzcswhyni.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gttjktyclt.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtojkbshjy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtycnklppo.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gttqfwgntr.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtweccnvck.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtraqhueke.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtxgylpxmu.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtpaouzdqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtlqfddapn.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtfpwtpsax.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtckkrfpqy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtsuybnbru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtbduemfcn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gterfblfvr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtbqpyjylw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtrtqdkbgq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtufjglcvd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtzdlpplpw.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtcxdelxto.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtwckqljpd.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtzymauony.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtzbrqcqer.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gthwomobez.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtvcgzyfcs.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtvtwcafrz.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtkofwqgma.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqlhtnzv.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtztpkzfsc.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtuvhurnen.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gttouvipxu.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovpwewok.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtfipibrin.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtjglbhcvi.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgywwezg.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtpsgpsazj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtmepklgsq.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgukajdrd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtnmxgcems.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfqhgeoj.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtnkmmwzrb.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtapttcmrs.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtcjttakob.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtnxkdwgbo.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtzrgiahfy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtotuhutxc.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtdzrjvvcq.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtugoefjux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtnanvdgaj.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnurhlqvc.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtxuogdwtz.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtxcndldct.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmptqwfbo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtdtuhytdp.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtirlvnfvo.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtfolzeoos.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtylobrpvc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtacydoksa.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtwpwxofbr.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtstyszqlz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtqnkygkpk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtxarjdovh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtsrxodsqb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtzgbvdula.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrzcdydii.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gthggvwezc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqnfdhjdl.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtpgzuqfvt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtpezvijki.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gtdwigyili.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtrosblvek.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtkxdeftfa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfetazny.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtfdivnoxy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtibehgnjg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtpzqjapjh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtmuvlmjqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtxmvfclgx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gthneycpuj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtpgnmpytn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtfuykylwb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtvktrlgxd.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtkvivbksr.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gttstaufcm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtvzgtuuez.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtricdzmkt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtajrcklje.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkuwqftq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtvjinyxgh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtpwnwzymf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtfpbirqex.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtmgjroyir.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviwbnzpr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtcopbssbr.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtgemihtum.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gthllribow.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtjxrxwbcx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtorkzshcx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtvnsugewf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtqlsubayv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfshgfbf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtgvcrfkti.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtbvfemffb.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtkjjffxvd.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtttoiajxp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtzbnrjjsu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtnewcnnhm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtkqgptruo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtdkfaduwl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtkdnqmlfd.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtntzyrqbs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtjsbotwqh.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtlchsmkux.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtamnfwnrs.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtvyozqzzu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtnjixggcr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtjvqggulb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtrqconqll.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtsoegdbpj.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtykeaebjn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtvytoedlz.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtcdhkbfea.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtkjwjecgc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtreamzsos.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gthchlefgs.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtkdafgiie.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtaahbufdy.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtqhtihtgq.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtillidqai.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtrxahtuon.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtrdohzkpq.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidiouszl.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtkhtugcjj.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtapdxuidp.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtdvrfvyme.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtvonkgoqw.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtrbolzpnw.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtvsyudjek.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtzbbuadaj.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtxmlgbppr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtzwybxsyr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtqdvujufg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtolywlidt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvyupzqf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtemsfiwmm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtdovznrnt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtauyfvkre.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtbqnhmtoc.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtghxpfhxl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtaezaklkp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtrbqinamf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtuesqrxpk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gthzoiiqvj.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtwoxnaiqf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtyzesumrr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtkpydgyue.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtcipawxqc.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtkcaznjyl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtdygbzrep.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtnltnlayu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtfseeagol.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtrvslurnj.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtjojtnsxn.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtcnsmvgpl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gttecswuga.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtqsagosde.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtppresbbx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtvpnruhvu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtbbfxcace.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtzijbkmrf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtrgsjjrfg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtzuqwtgto.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtogxnkspa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtpabwqevs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtmqzkmdnc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuakrlnbz.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtijkxvxpq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxmbhwyar.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtqvizdwmp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gttpeafbgd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtowfsawez.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtmidtgibq.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtgbuccfys.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtqyasqskw.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gtsxuzdiik.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtskvvktkz.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtbvduneqp.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gtkrphkcgz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtnojqzpsv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtroawuvsu.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtlmtuewxd.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtvunpstff.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gtpxgzfgjj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtjlfkkywh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtbuyrdshp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gtawmpftdc.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtiijwevoa.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtzstpwklm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtsqnftoez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtappfyfak.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtcdpucwme.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtydmrtiiw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtbvmywpcd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtqrdqujcg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtwcylxkzv.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gtjhuaoqqv.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtsqvwpqod.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtzdbixjrn.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtviaxkdes.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvxfkedl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gteamxaxoa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtlrjfzsdn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gttljmcyvg.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtspzkernj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtfxzywxxw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtiybdwbpp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gtcvowgvwf.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjxgvpvf.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtsujqglfh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtgigdiusd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtryxypndz.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfgvkkhi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtojsjmvyg.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtjfjfkqpt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtdqeyttwh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtzsfgrmop.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtqbgwxfmf.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtbnhbnuwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtdiqtbovm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtaywtncpf.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtevklcoee.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtzbmfkguz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrynkbplh.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtplqlgbfm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcxpovwyf.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gttxujehbk.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtfthgsuzg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtzcxyjxst.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtbsurbbsn.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtqwstoypf.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtuthhzwys.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtryjunrow.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtwmpxepcz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gttsdudeij.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtifkbmqen.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtlcwxytru.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gtwqtjpzru.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtfzrxiygt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtgefitbbs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtvxtknnpz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtizsyaxoq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtcwjpoypb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtwkciamft.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gthfenvjyc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtyyvmwzzq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gtwvifulka.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtanakmxcn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtgfcvvdxe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gturqmjhsv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gthbbrzjux.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtsxszgrud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtrmktssrr.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtaweonofa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gthuduuntc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtenntjciu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtvlprvzxg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gteswruyem.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtemqnozto.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpvxzswh.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtghgyytnp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtshhrqxqm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gttxrbdbqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtdhylmzth.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gtkbiwtawv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtdzunggda.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtmocvbsfz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtfisccrft.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkybnkbo.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gthdmmcffd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkignegb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtcnmfnerz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtomunqpai.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtiliedpoe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtgikdrmwy.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthplplihm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gthxztrqfs.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtuquaklnx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtpwqzjahj.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkycogtt.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtrscsqipb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtqdeqwfhh.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gttgabxvep.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtqlihughs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtaeiufiow.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtrahoevrl.html


<!-- 参考信息 -->