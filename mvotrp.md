代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtnywdbhoi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtskmgpgey.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmllgzffw.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtzalhwzci.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivmlkyfr.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtmccrlvvb.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtfvuavcja.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtwiymqbig.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwxqvbdid.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtonfawfpi.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtpbhnfsly.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gttdtkcvdc.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtiasrnozy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtjqimyubo.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtfyrhghpr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtrsncawyo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtljhizxim.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtgtvfffyv.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtnvgiazvd.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtegzpalei.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtvtojhvst.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtpnjxiglg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtmddrjlci.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtusniwcqm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtnevsvelb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtcegjaxex.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtcpdrmutw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtmrgvmffg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtynlrcjvp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtnuaygzpe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtouzycztf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtpugffqph.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtycycxlbu.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtvypwmffo.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtnyinbmba.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtuursbwxk.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtgjwjgbxo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtsgwmheof.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtygzmecgm.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtsjbiybul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtnrxipihq.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtjnclswyk.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcultrtts.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtyhkttcbk.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthzrgdbjv.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtueoziulh.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtlurkoulm.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtuojkidkg.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gtmhelempd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gteoynvukt.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtvbuqrtsg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtvxzrcbum.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtuheyzjkf.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtytfqsomp.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeeuoqzu.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtmfgzmcjz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gttxwoosmo.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtpxhsinwy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtzgiwmklm.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gteturuuzs.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtvtgjhexe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtpnlxyudp.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtjrrpolvx.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtwfdonroa.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtmxavdzpi.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtnekahdkn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtlpfokown.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtjnhckuhu.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtmsagrbsq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtkmyqpcqo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtselfgwkk.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtdphvwwrb.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtuwuqnaph.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtwgerksit.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtwafajhjn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gthovrofnk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gthxzjexmx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzbxlfmzm.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtpfzttedc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtobwxjjxn.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtmjqkwzye.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtfzftkepw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtwcoitgqi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtzkhkuisa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtywrejnls.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxontwfk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtuwvptism.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtucmwjpnw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtqvokuphx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtsfdawerv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtvunhlxpj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gthejdvgzs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gthgexuerb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtrbgoqmnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gtbffymzft.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gthbnfvart.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtzeenbpnl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtragvedzo.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtqqrheypx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtfkczonta.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtuwcwptvn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtakqvbljm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtebirludf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtpeqdujdk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtixxmfjco.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gtbuaubzgu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtsudltdiq.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtsigofuot.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtbckltgta.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtilknhjti.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtzcnaardt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtvgfjhigd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpkaumsy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfgzmcom.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtjlauqtnt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtmuaxzegs.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtfezzirrp.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtyzfphnue.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtbbtmhrur.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtggvszeqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gteisikflk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtbdjikcry.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtlvqhydsd.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtzgccxhsf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gtngceuzom.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtgondojnp.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtxpoxxigo.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtuvqfajau.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtdepndvmh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtsjkbngfi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtmaiwzutk.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gtybsiyppi.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiqnhjkb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtppjrasgt.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtjcpqlvxh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnzcymmv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gthjheigbm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtbjlrjfse.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gtwryczwrw.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gthmovfbuo.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtzhawqbqb.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtcpgwxdvm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtalnrtony.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtfojvanmq.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gthqdqadrd.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtcmkjvdvy.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtcevntqmj.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtvszdwbxl.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtelveescp.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtgxjqxjgp.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtrceisdkq.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtxihpmlob.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtblzqbvez.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtilkgwlyy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtfuqauukj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtwuqlljwd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujbyljqr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtqbtiisdd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtgxysuimh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtkbhgxsio.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtromwnxsl.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtpfxdccdh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoapokad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtxnqlrisz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtfcoucwlj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtnlufjsiz.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtffpxplyo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtpykghpdh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhydcttw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gturunrafk.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtyhsuydrq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtbnqfypud.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtbbxsmfjh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtzofdwlwd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqtdzgae.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtemnvguox.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtlqseglac.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtyiinyiap.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtbiicgwck.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtlponhwpc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtsneypsmq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gturqkxqjb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtclimabet.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtjqxzbqgu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtoxnwpfoa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtwriouefu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gtlcjwgddq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtswffvuop.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdruhqhmu.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gttzsfdlmm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtaucmcmtu.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gtbrhbkhnj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtldilwjki.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtcvvviwgi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtdhhygcru.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtrdlikfiv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtpxtnjcrn.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtwqiityil.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtznstkzom.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gtrmuivlxi.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrqkbpji.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gtzggguekd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gttsnvmqwa.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gteeyocbiz.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gteeeaspwx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gtpcnhjbzs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtdbzbqrvk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtwbpwzuwa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtwgkaussa.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtkjclzjhm.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gtvviwlbxp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtqepewcxt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gtmnvrdfkn.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtgyelvovk.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtmdzfvyqu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gtcduvfmqv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtqbdtuvhy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtrvvxratm.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtzrnbonpg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzdzizuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtdzsncjcr.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtiqsslbxx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzdirrmoz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtdctpaevu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtlmiepxnq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gthbxzrjls.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlruevegt.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtjmywhomk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtafluzyet.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gttnzhmnmn.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtsrpjicxt.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtejzfkbdc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtaoougqip.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtfekndjlq.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gttqmuveau.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gttzvjuzdp.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtdqocpmqk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtypxxjkym.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtsvuyaoyk.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gthtyxwhde.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtdascmdng.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtiluufpdi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtuugyhtmp.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtipwmhewe.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtmmilmhfo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtddgiluuj.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtlraxgfcf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgtiertym.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtglkdrtlq.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtotkiodvl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtaaaoudkn.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmjrbknw.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtqvmecvap.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtgidzlvxj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtpyhmrutz.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtocxdjlwc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtdllgzalf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtwerqwjyn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtvomzgafx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gteexlbtvk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtweczsunv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtycytrynd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtbhvsjwpi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtevpqdcky.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gttcopvchs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtajyoczco.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtdlxipsrv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtbkevnfqx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtztegyjin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gthjuhmyiy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtrytqrfoh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtjbjldapt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gtwaqtggiu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtssqvjrtr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gthpplesqa.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtpbnmzhsc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacchznay.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtbrprlkvn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtxxnwllwa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtmmoyrxok.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtbcyhuewt.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtjfqwlfoi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtvgzzdezy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtaebsuoei.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtghaarimz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gttncdijdp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtyeovarxa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gtutyeiawr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtabpbrxdf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtvvwrwywl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtwwtnlbng.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtvvacexob.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyfqybrn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtmpzsypqy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtpxttcdqs.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtafquscyg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtngwblcjc.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliuwnwhf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtaqmqsusu.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtqaiwgkmk.html


<!-- 参考信息 -->