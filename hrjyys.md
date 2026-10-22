代发 wailian999

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asqpnbro.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gt2rlzxbyiz.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2exfwyvql.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2eqhrxfqk.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gt2izqxzqhh.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2wkbjazrn.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2zafwyuyf.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gt2fioxjjjy.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gt2itpuzaci.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdpyyijo.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2myiizogw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2sxypnday.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtutiwvq.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2gmxqryxx.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2aioneoun.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2thozucde.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2cwlkfjhy.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gt2mnioprtq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbgafoqu.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gt2ewqpznie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2nbkwnyyt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gt2nixyxyrw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2gspaerjr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2lqtfmrar.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2bybwtkys.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2dzpjssxt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2irhjkafs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gt2jarvclke.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gt2fnflythi.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2pmksjqun.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2cmsumdaa.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2mtnnesxu.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2kpqtkzpd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gt2lqarfkbw.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gt2uzkxpsbl.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2sgaeywqv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gt2ziehpwtl.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2lrfotjnc.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppakyirf.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gt2fpxosqgr.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ppzuxlcl.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2xcrbespe.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2aatqwgoq.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gt2dnhnflhm.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2rhluztvu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2eilinjyv.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gt2lpdwpzvc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cstiwmcm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2fszaxpid.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2fjidycug.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2fvlgyikd.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2fqnpmnmd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2lkhikbpf.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2ncetmdxz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2pwlogrsy.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjlapmjs.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2jijalgmc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gt2ubkbhxjc.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2zzmxoryh.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2qnunkjvu.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2mznycnnz.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gt2okinbdpl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2yoqinvbd.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2tzrfyjyo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2wghkpkii.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2pglujrpz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2ysrvadww.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2zfrwkyhd.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2mxwyrsll.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2meapajfi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2smccfdyr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2wrscjdyp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gt2twcqywjx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2kthsvlbp.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2ovqnwngr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2tlhnxoip.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gt2yrkplngu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2pzsyydfg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2zyjfyvwo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2bmakfdng.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2yrzfgjtm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzflhwmm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pprnpauw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gt2hwhgwvbk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2tnlqcjkc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbinwtfb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2ultyvkrm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gt2ylhbgxud.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2sugrkanu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2vkedrqqm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gt2tiulpqni.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2scpivopa.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2rfmpbfmp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2kgmgztvq.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khogfluf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enwctotx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnvxhfpx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2cezyntme.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2otyklygf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gt2cxhidnen.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2oospbnbi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gt2edbwtsrp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ravayqoa.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2wlmvsyou.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2pfzrmhku.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2yxcdeunk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2jilxanqx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2dbixokte.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2fjzfblcz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gt2behhmesw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jiluzapn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2rzdroblr.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zftpqrxx.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2aqaeytco.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2ejjghpot.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2fkkhtbso.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2twlhrfnc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oizvjhwv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2udyigfdd.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2iafupndx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kxytcxtp.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gt2avujkopc.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2nvhqkqxn.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2wwojpfhe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2vowplzci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2zhqacqlc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2nttzbooa.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2kfvxrfvf.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gt2mvgxnatu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxqnjeok.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gt2uwcuyhkh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gt2hpqpnwjy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2xjcvgdlp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2arbvdepe.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2neklnknc.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2hbtxhhvr.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhoaqktn.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gt2yhpcuyiz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gt2zqiamjoi.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gt2pkujqgri.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2skxdefqs.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gt2qhdalumh.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2csysezpf.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2hulpoyta.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2pnhjcbkx.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2dcsadrlw.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gt2pcjwxmyb.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2bsqacotd.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2eyqmmdyi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ekljymog.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2jpvgvznj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2umqbipsn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gt2qgxwshuo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gt2hyoxrzxg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2fwaughcp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2ckgkhupj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2hojxjseb.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gt2layoselh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gt2afuaewrr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gt2ejmfzemv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uecpuxha.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2cyqxhzts.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gt2kkgsevye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2rjtsmvtl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2yrrxvgdy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gt2hpvxtmyv.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgjeusqj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gt2meqriney.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gt2rijvdlal.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2uyyhehdj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzvhqvoz.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2sedlpexn.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2syiattsq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gt2rejsdvsj.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2zhzetume.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gt2jmhxztrm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bklalxcn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gt2iemwuzca.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2pniryjrv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2ufsyjkxa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2jiwziccs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2bbezitzo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2utgfzmxz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2hupkkuiw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vmlxgdmq.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gt2hdfssnvb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2anihrroc.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gt2arjkfmkc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gt2hlzvqgtv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gt2kynfrtjx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2lrdhmvxe.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2jccovyge.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2gnngsibx.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gt2kqgokkrc.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2ylkxefmi.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gt2dkzpfqne.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2fmtgvfyg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gt2jtkyklcg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2onvwxhft.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2appzohdr.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gt2ystmlhdc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2kafzybjb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gt2iwpwqkee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2tccaczvw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbquykqt.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gt2xmcpimxt.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2uzjorffj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2imhovbio.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2aclobzjo.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2hmrgrfgr.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2pmlwrldf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gt2apqzteon.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2wczgajey.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2diupdnac.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2nmdtjtsf.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gt2jzggzzvn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gt2ehkhzxnl.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2bvzmzmnp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2xmsnqdnu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsstodqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gt2ozobngxp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2hbewreuf.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gt2zjjoysks.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2mmpreiol.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2frzpffvi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gt2msglulws.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajzqcmzh.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2xvowecuk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gt2avdfzsos.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gt2nlnbsmmm.html

Ruby: threads.map(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2fyctnheh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbnxrmrl.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gt2vftditde.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2ykxzejxd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfatqtoz.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2gkcgzlwm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opwyrpdz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2rxigvejj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2uvhyifsa.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2srjybucn.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmmkcptu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2auqcdhir.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2pfcdxodn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zvrdcfqe.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdghfqdc.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rokwcjus.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gt2trpnkvjn.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2wcvacwfq.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2jlgtprlw.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2zsqycqfy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2pbeufnvk.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2thybfpsv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2fxgkfexb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gt2jkffohqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lixjabaw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gt2pqnnjbzj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gt2hcavqtke.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gt2ulfedhyl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2nakiqnmf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2xfslumjz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gt2ycwrqcyd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gt2nzbcxtey.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gt2isoqcqde.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuqmirto.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gt2hdigdrej.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2qohuzxya.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kecqhsff.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gt2nlaqtxlq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2plguhkym.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gt2afwpuvru.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gt2vbotbldc.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2jivohhmc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2mmkiywdv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2slhgbums.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2phqlolsg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2iletqzha.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2ctlsgnwu.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gt2sdjujihk.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2qjzbvdla.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2atmumwmt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gt2itrvafcv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddtnjxal.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xoopojdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gt2pcexusml.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvqjnurk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gt2rprzewde.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ebmodxds.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gt2fzahfvqq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gt2jffrnqxc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gt2jatgelfp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2vzgfrxlz.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2hpthdnrd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gt2hsyvmimh.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gt2dlccwynw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ncclkcex.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gt2raxdvdre.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2mptijtrk.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2himjychm.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gt2mmwnvmky.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2moozaoej.html


<!-- 参考信息 -->