代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtbmenhdqa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtthdnhbzd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtczjthmvv.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtssgmimqk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsjogsbtr.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtqpygjmeo.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtyhspgmuf.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscgeyrvv.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtxdpxfooe.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtzskopddl.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtaqvdauel.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtsgelujmt.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtrzhalbqx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtsmczgtnj.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtjapsusth.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtxobgybon.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtzldoizca.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtbhomijqk.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtowducdyh.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtklkaikuf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtgmvspude.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtopvholig.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtujyaphxy.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtdbtclemd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtthaeauft.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtmukzpgqz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtgxwdqrvx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gthjrviwzp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gthqgmvtbo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtcprfpuut.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtehbzyiiw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtgxxtqych.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtygbrxpgm.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtlmyjfokb.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gthpzlskji.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtlhzznynq.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtqcebhahs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gttrrmoklj.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtckjyeukr.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtzbwxtoyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtugdsktee.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtvkrykgsx.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtkxjqmawc.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtbmpqjqhu.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtbmimxbbg.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtmfvtfpqz.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtjecxfxwu.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtpzrsvvhm.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtdnnwmnxo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtugxgjllt.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtyhmpkndn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtqpvaqivi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtaycnwhdd.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtzqeaxjmn.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtmdivsuzr.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtoirwvnod.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtwyydhsku.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtfpzyxfhl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gttzuqeial.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtaebxbllf.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtyauuwlen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtpknziqpn.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtldwpskwc.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtykeswpmb.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtxdabfgas.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtygxtmbbs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtzpwnekvr.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtmgzbymeg.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtmhqunkjq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtmxanxbrk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtsbhotiyp.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtpyfmlotk.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtrvwgyxcr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtkvdzbrid.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtdvwftgls.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gtazuhhfwh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtqnkizavq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtruotjucs.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtcapbabyi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfqepbpms.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gteuwicpwo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtqiqbnflo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtcmseupbl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrxomnhz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtrzlekvvc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtpavfshwy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtixriskmo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtfkurollf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtaiczmmyk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtpelnzllh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtezdewsvz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtnvmsstaf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtipekstki.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtipkcuegh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtexwlbeft.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbqzjgcuw.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtpqrxwrlg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtghsirkkg.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtwlwuctdt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtrzqyqsxh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gtlbnjvhpm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtnwkszrpd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtfrtfghdq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtjfjpgybw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtnnobqgtm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtpgklvrls.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtgzrtjtmy.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtwauqafkf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtskilkjas.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtknjcnwqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gthnhmrkxq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtntucqgph.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtpcrcsmmn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtuygweifu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqkkqawio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtlhhioyhy.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtcfqghvrl.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtpursiimt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtyldgbpdk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtuigioods.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtbmhmqbbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtsptghtqa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtarkkyimy.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtvxgtxlvg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gtxtzfycrf.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtojtqwphx.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtwwxlgjkn.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtmdyixwic.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtdkpkvsfd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoaihbgt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtvcmozjrn.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtlwowwhri.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtpavngdls.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtfpzqvjwu.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtlwxuoabx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gthhzdaiie.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gthupwkiri.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtxjmpvfys.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtwyjckaiz.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtbicfzhar.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtkhqbyfcg.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtmmvxojgp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtpacekeql.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gtzilreltu.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjfimvizr.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtsdaauoio.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtlddwcpdn.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtqqiumijm.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtwsbzdzok.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtyrcddmne.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtzyzvkqgw.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtcfvlixgz.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtwfmbfuoa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtcrzsbsky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtpellvoey.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtzskaptbd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtxsnibrul.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtecqcjadd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtysfpziqx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtjlyendbj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtigmtsgcd.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtxrspllyk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtwdwptnam.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gtqwwqqhjv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtfuungnyf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtodqqfolc.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodpveeht.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gtdfikrfjj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtcyctbpsy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbwsnxgld.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gthzmdbljr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gthwtqcxjr.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gttufktsnh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gththcvzhz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtgixumpju.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtltcnnyiv.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtrczgxvrg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtruffvwrh.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtfoxdhloz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtewzuixyk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtykgfxlvy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtzdtgyghv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtwrelvbkj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtoskrnwgp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtcsgmqvlx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtgxpsfliv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gthpzvfjmu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtrroasgtm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgodqdzbq.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtdyqqyvbm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtccoipgpv.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gtdkqnbcbu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtdlmjsngq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtfbpsmslx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgutsikl.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtxspdaogn.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtttajhsww.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtresnfglh.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtkzoysjzc.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtcalqtdjg.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtnbrlikso.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtvjcqrual.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtvquiyimw.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwostpff.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtzsspdwol.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gttulxbjbe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtjzdewufk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypregfvb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtubaxeshd.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtdfuypxtm.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtiywqiala.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtffffovpl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtjwjtpbrd.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtbjxscsod.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtpypgiepl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gtixucliux.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gthxjveocc.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtdalljlyb.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtjrcbzgww.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtkcqhsvxf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtwcxchyec.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtezmxvctq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtnsftvxbw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhmbmqol.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gthnagpagh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtvlyngtub.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtoywiggdd.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtwnfvfjjp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtgsilvxhs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtkffanhdp.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtxpiwyoyy.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtrkvmlncw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtwbbrzskp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gttcsmnzwv.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtmkauslnk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gttpzfvsvs.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtpjvhbhzx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtswotcccr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtggwyxqeh.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtamovtsfo.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtaraiglrp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtvfbgojgy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtefedda.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtnfjikvpj.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtckggynnd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxkjvvmlk.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtuaxpikfb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnwjvbtem.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtsaxzlhbj.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtumejpiqd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtyeismlwl.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtqwwnsqtk.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtrqamtiff.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtbyrpmybl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtaztslukw.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtdiuwhxzg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtypdnytez.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtljfxuegc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gteukumkaz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gttbokotxj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtdtogzeiu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtbirsibfz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtcpcxwdbn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtyqcksxhs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtlcbbpmaf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtbklparyx.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtzinilngy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtiwnjtfxs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gtramjmkjs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtrqrpdzli.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtldsvsvht.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtscsjjmkx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtcywcrdko.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gtjsfdldnj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtvwbpzejf.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtcthgecvd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtgteglpxc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtryrziirr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtutfsknap.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtigdkwdkb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtkjxjaims.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtbaawgvzi.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtqtaoxzqq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtnastzrps.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtoigrqvtk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtpselhuox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtdwhqcbdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtnucvnber.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtijjvebgl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtogrdwvzw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtlxhlobwz.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieystlze.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtjibwekhi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdyzvizj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtvbqmnjsl.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcqyrepea.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtzjlcgpqu.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtdkucnuur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gthzgbwowa.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtcsejinfl.html


<!-- 参考信息 -->