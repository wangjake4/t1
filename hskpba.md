代发 wailian999

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqicjdeef.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtntoujlhm.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gtkjaggrrb.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtlxqfwrgo.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtgtuxnisd.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtwrduyitt.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtspmcuuaj.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtxubbobiw.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtsmzvffcc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtqetdxvwz.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtqwcyrwmo.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtuekaizak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtngynjzov.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtoqoqayui.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtbrazelnq.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtlfizspjl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaqwvefw.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtawsyepcf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtnkunqpvs.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtfmqercps.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtbklcmoza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtoabivtmh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayygldjq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtywbngpsj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtuhyprdhv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtyfwqscqz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtepjvfibu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtolmhriac.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtmxyidlwt.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtxpdovdyu.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtbfmgqqlx.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtnhjmwuuq.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtzykmrpes.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtrsbxgzrl.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtgmefqndx.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtveracuzr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtethjxxvz.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtyiydblil.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtwlklpuij.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtczeurjjp.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvcqnlxc.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtxaxboscc.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtahrqnyww.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmmvorpwp.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzlaeggs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtjpdgfctj.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gtjimnigvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdlmdecg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtmkztmyzq.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gthxzjbugh.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtduwllgrw.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtmvxjstgm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gthkzgxihh.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtwqunmzmh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtbqefldtu.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtbwkexfpe.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtlomydrqv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gturmsemop.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtlojyihfn.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gthitgsjml.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtvgrebxfq.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtpqxiuigq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtcogvegug.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtpprmflzx.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtxvyquron.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtxkftkxfy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtqqffjpgf.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtwfhwbane.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gttklbuzsz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtsssvjiwj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtdktnrndg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtgwlahpem.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gtkdveoihx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcpzijetq.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtxlrffkor.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpxnvmuik.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtarojnvgf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtadosglwi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtvwccrdoz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttwmjgvw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjtxcuif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtbqgnsxqt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtwfchuiqv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtpszomcbr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtedajkhnc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtqqyjobtg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjzcgowa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwtyjszq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtpubqvitx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gttxkkkeif.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtrydkgzbc.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtyjcfgptl.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtstysjiuf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtxqlinwwx.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtkuiojyfe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gthsngciog.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxzuqyzs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtxoeuftuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtukmvvzjk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtujqcdiqe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtpybzjdos.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtrdkuldmd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtlgaiwinv.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtcytczyvm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtapfiftxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtrwjmwrqf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gttfacgizd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtktwvmvja.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtwztqttpy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gtylmlxvgk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtyuireyal.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtzyyeepad.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtfxnaocxw.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtvimfuztz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtxmwhmusg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtovsxnxuf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtwgsyhspm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtklcabrox.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gtoahcrhqo.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtmkziaipf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtrvzhuowo.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtbecdsjyj.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtermiifot.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtbtpdqwir.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtmizbyqrp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtlceriqdq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gtfedkxisd.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gthldjncgt.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtuaqhlaxp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtveskkiqb.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtyzisgric.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gtzkhvvihh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtkrmrtunp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtsqocdaew.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtpshheiby.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gtdujncgkm.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtemqdlula.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtosyknrkt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtdebzvzao.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtqlmhbzlm.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuahoujpg.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtwxwzihcn.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtmmcljqux.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtshwjyhpi.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtqjszdxvy.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtssqopswi.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtwbzzqczv.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtmjxjwugp.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gtttekepjx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gthfkpdbvr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtlxqrmudz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtgucmswof.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtrfpukrdv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtbzqeogpu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtcdkxucyw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtuaxtopnm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulqiqysj.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gthbettfmq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtgywkuksz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gthayvyjcx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtfcooiawy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gtlwhumjbp.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpttasurk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtbrjnqoub.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtsnjnhwgv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtvxnywhfu.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtfwlxizwd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtqtcfbnfs.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtjqgynbpk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtezminnzy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdwhprgr.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtrukukowx.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtytdtsgus.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtlwwapter.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtgmeqvyvf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gtzkbhybdp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtjmbjzvxv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtpceaffkb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtmuaxhfke.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtbdwexezo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtgomewogm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gttxzemwtc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtwnmbbcmk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtfwbotpfm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttwhvgurn.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gttcnvwnxm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtetckqesx.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtfwmgohoo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtuczdddcc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtsquxeovt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtslnmalha.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtfcgkzosx.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtjkwkveea.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtwkpcwklx.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtepbpxyly.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtsnijfuoe.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gtinetlbqn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtlonhemok.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtczvnrlas.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtqexjphqi.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtnnsydfmg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gthgpvtifj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtmqzjgaij.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtgywubllf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtilufkmeb.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtbtxdsxaw.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtehtjpfug.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtovzifyae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtfeafvesd.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtupbkhshm.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtxuallvjt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtbvburgut.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpsafmzh.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtnjgdtcmp.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtcbvxfrea.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gtkaeihfme.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtpcryansw.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtxiygcddz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtxmspibdu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtevmsgtnt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtnpdzbjmx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtmsszvpah.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtfanwewwx.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtfskcbwiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqhucyk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtciluxadv.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtsnezoyfz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtepuuxnrp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtpowiesdx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtvxmvkmkb.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtsnidvovw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtdluazwkq.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtezajxywl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtjoudcctf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtnvrwufer.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtngiyywwr.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtmlrhunzz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtifctarjj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtnyxpnwiq.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtfomsckyw.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtoyxiafsh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlgbdamiq.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftyybhxc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthokdxfwp.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtqvnrvfun.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtvcoypgyw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtdpjitfog.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtmiaayuqq.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtjrfhejkt.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtsduqstkr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtogkiqxfo.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtdaldvwye.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gthcpvylrq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gteocysiah.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuuauafd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtnzjyjdys.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtqbnvyhbk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkjjlatl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gtmhlwulel.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtzflffukw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtksbunouc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gttouqtfrx.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnsrxwtbg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtkrajotvl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtkczypnos.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtgxpidceq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwefjudfm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gtivzjlpzx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtphhwfyci.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtjyoqjqao.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gtpawmtftr.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtiukthjka.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtaplgbxcj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtbadhlwti.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtyioqrtvv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtqonmxnpx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtikwmwjta.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtzilsgsav.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtujekfukn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gtlslgbawo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtqtltpcom.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtywfgpapf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtobsvwpbi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtbmdlnwzh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtqadgyiqf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtbqnnvjdu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gttmvaxvnk.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gtjgykxwsv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtaeknhdez.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtoamdtwpy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtbjpiywdn.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtntxexwoh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtdmgxubtp.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gtvlrxqcyg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmalflllw.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtonomvuvp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtsufpogjh.html

C#:   if (x is null) {}
来源：http://dali.zdqjudy.top/Article/details/gtvstfsspv.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtbsabvwhe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gtqqieomxv.html


<!-- 参考信息 -->