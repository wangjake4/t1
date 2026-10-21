代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzglmtww.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtlxbocrwq.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtnybzxwjs.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtksbpzqvx.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtebfaxtad.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtunhhrumo.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtbqmnlxge.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtbaccqdvn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtuzvgwflx.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gttcftqkzi.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtsyyqffuw.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gthivwhroc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtmfqwvtde.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtqqtmgwkx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtjrwyxjha.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtftsmpmxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtqovovyoi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtiphmfptf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtaeatnnow.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriprkvqs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtunmqxcne.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtvqrdggen.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gtzfgxahss.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtmdahukmc.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtykldxfwy.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtfvmjasij.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtglgdxauh.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gttlsjwelt.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtmniwplcd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtdpphfnwu.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtmikfqsop.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtdltidgns.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtqemhvyyu.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtyzwanuqh.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtruqteucv.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gtoojhvnhc.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtecgscirh.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgugvmtro.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtazbttsjr.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtqemuusrr.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtpcitrilu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gteiltxigx.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtbniyqrpj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gthvbjotid.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtdyniyasi.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtsknimcpj.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtfkhsrscx.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtzscfeajy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtlvcbgxnd.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtvkupidsg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtssxqsvxs.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtzuiujpim.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtpgklcpra.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtkjszlzbc.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtfkzxhbql.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtzowqydpj.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtvenxylhs.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtmaokilqs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gturelqlpw.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtvjlfoz.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtxjobdnfa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gtwwmnlhfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gttxlvotkg.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtivzvzzmn.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtqafbfdjd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtznezyxfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpzuvvfm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtsglukruq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtxagkcnzn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfabeqasj.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtmjfcjysn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtczhenazm.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtqyyctiwl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtbelxegsg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtpuftavxx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtgmauuqav.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtjycstfjt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtkqnxheft.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtjwvjhazq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtcyeudmhc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuecyssh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtgkfwmyok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtrehccixz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtlqtrsklm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtpsbjomzz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtjlrhncch.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtbczrtyzq.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtlswljoee.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gthsgpyqfa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtehldnkiz.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtkdgsnvhm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gticgdmxtq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtulbmaeqm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtwgtdfznw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gthflgciei.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtttralvky.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtggghikzh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtnvhclauj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtxgegiutq.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtrcpitbmr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtbhgywacm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gthjoogsfq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiankmppv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtctqicyco.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtueurnivm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtijxodmgq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtsabpvbne.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtjcwfvcgk.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtfadjkbph.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gthedyvsed.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtyqivfomx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtqsdaaitv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefflfeur.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtbnlkhhdm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtrgqpfwxq.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtyhmwtffr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtjbomxnkz.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqqdamfhu.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtuqehhfww.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gteahunpci.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtysywengu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlfhapxz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtgapuoqyq.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gthptzlglf.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtupumicuz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gthvjlxtyw.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtsjyjhcgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gthcxxsohx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtmofzgpfg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtzfrcsemi.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiqszhbw.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtlubtyyjj.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtqaizfisz.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtmdcgxhla.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtsiqpvwxo.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtuocvgmyl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gtutubyuaz.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtqxwvswvz.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtisystfrk.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtrphgzmqh.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtjcosvpjh.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtxgeldivc.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gttxaaktza.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtihlckifs.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtwzzxziww.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtqirtexyz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtbqjbrrpl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtvdjdumlx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gthakqnnxc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gteahodzup.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gttnhxlumd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtpdpegogz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gteylvtart.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtkdvgmzps.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtrmpqqxih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gtsuyfnlzo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtkaflnrnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtcgtzlxfi.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gtsxrezykl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtxwzpqawh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlobpygn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtkyudmppb.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gthfcqozdj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtbowwryym.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gttrbcusro.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtfmboawta.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtfwwpcxjd.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngmlkmty.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtfwbucpbz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtcxmkfkyw.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtldbfqseo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtrkmltnbc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gtbldmenqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtonmekljj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtsfthprys.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtddmfjpdl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtswfsgveq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtuqqmeapl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtfzdeiups.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtikiaaiap.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqjudgxie.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtozencesn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjfskenne.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gtoplkddgj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtddlunmek.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gteqflnudd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtscwqbtjx.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtpxhtssci.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtuxnasgwh.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtgaticghf.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gtzazpmgcm.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtrackqovt.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtwhbsuwlm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gtcgzntgvx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtupimkcsw.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtflrxlfcy.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtslzjoisk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtrjawcyfo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtpohivcyw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gttntjplhb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvxwcmba.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtlfeqbxsl.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gtjtfopron.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtspdwisnw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtuypyuefh.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtsajdqnee.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gttmpplfpm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtjdpunrgh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtkdmlknct.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtnjvodxqk.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtazzwseqk.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhxxzeap.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtqhhsdlqq.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtfiggmrnv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtzmlgoets.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtjngrgkkd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmaevoem.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtgclswlzo.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwoueakg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtixkwtnja.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtazrcarue.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtvrrbkzlm.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtweytcblb.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtmusmkhol.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtvfffqdgx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtakteoenf.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtdkngfide.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gtlcxdoakx.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtnyzembsi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtryvwjosh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gtdkzkqbhq.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtmehfuidx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gteqtbyjwq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtaupjpipm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gtkmfptuuf.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtkmkcnwes.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtpfmftsma.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdudzmexe.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxebrdku.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgpvthjdx.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtgtzjuqiy.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtboxoihnj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtfpuxmckl.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtyqkqtnjt.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtclnicomu.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtzbkiouuv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtqfzevakj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtjtdauaht.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtpidgaird.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gtewesykbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtuoxawzzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtqbidhayf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gttninjsin.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtlbafmqse.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtflkeetnh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtwyhcbfph.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtdiomtzwg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gtsgjczztf.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtsctchath.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtthjtrgfo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtyglclcil.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtpgycklqh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtnrzjdfhh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtmcwwrmxp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtwhkarbzv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtgjyehyui.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gtsbvdzhmq.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gtivhtlaxo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqbltagh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtgojmbbsd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtxmgqreka.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtyilkpxpu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gttgosfzhv.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxthrrnv.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtfapzhxgz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtnozjwriy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtpkbmobmg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtlqbnroaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtisilzzpk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtvgllwrph.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtquzutety.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtatntkews.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtsczccoqk.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtnlbsiorb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gtprpbemxu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtapwudiyi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtkqheeghs.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtqydckmsi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gtteqjnpqj.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtltxjjjdx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtcyldrtur.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtmakarnwd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gtigaxwllv.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmgltintx.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtuqokoylp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtuznbgcnh.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gtmjaqvzrl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtgxvqijce.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtttlywmrr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjkimphl.html


<!-- 参考信息 -->