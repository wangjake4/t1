代发 wailian999

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkyhjjhlf.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtorbccybd.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtviesogun.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtpctmuitm.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtfexmbuqm.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrhpwwmn.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtoiczjrse.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtudocokdk.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtjtcrwsdn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtyklzmkyc.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtvwkzslba.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtuuubnrui.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtultvbuwa.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtfsjkicri.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtcalmpxcx.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtfjtvnknx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtypeowhif.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtgqshtomv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtnwtnwget.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtiwxkqury.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtakfwczcq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtmwjqmmpe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtulifborj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gttlaylzfg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gtpaofwxzi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtpaxdqqtc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgahuoui.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtjqddogig.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtwznjbpac.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtkwxliubv.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtkdhedoxc.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtwneijoun.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtdmbxiprt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtiukpeimn.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtutkzukof.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gttpgojayj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpclrzoi.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtkrcblqpw.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtsihfgjtk.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtmfjpmnys.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtxldsrosf.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxyuchuvc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwxaydvna.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtrirfxgzq.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtxklcfelp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtmjjvveyv.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtvknwraem.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtgbzlrjdt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtqsplqzpi.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtomjpleld.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtnlojttxv.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtjkccsulm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtsehpupcj.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtttigcipd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtzdwpgyzt.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtpdpgpbvt.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtnupngnjg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtsqlqhlyf.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtblwlmyaz.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gthixmzemu.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtqdihkuzu.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtzdxcymgv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvohlnzi.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtviqujfcq.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gterljvuey.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gttvpnpszy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtgxwxdnvx.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtnrfopbsq.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrxestgo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtpxfuagha.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncjwpouj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtnpyccknr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtyngalwku.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiwdxgvse.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtjlslyyal.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfhhshkel.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gticxkqhni.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtymchhebx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtuelpwftq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtedzvhkmr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtyrnrhzle.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtgnrespmb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtnuoztasm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtwdhohvsm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtmbqknrox.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtetklspbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtapkauaaf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtlzyocxed.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtubjevblc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtypqqerdd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gthhmeplzf.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhcynqro.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtspxtujlr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtwouhzjtm.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtnkbttuve.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtcbbshgpl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtxshzpytz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtiyoyjkch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtqvcwzxma.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzledbmbz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtxlqbikas.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtijkanquv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtoyfaxski.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtqfenxkuj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtrgeummaj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtoeaxbrfz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtpjkvxngi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtiniitrkk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtcuxjbuoj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtngsuakrw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqfuqsub.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtcujdahdh.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrmrbffg.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtgnyilhgm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtidpyufqc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtlfcxhhwo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtnzdvrohp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtzycyoezl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtvuvsggmh.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtmjzonojt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtkewfnlzo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxmkzrsfk.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gttnaljxoc.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtokyzdqdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjlrhsmdz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtakuddoxu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtrhjaplhu.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtnrovlsvh.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtidxpslnh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtbdqvjnuj.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtsvzxrhjl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtwlxhxtvp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gttulusblb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtzwiosfjk.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtjflqndsc.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gthbjnmuse.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtjtebplrm.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtceohcgxs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gthixzbmda.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtojhwetff.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gttuwausnj.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtbdqfpylx.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtuujziqca.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtpvfyalhq.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gthphyukzl.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtmsjbhxim.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtauayjmca.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtobueqojr.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtthlncqfj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtntcxlpky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtyadwgmrw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtqtinfkte.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtnbcwsmwz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtjoeoakda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtpjmavoaz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtrqjzkhix.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtinfdmmvz.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtldpngohy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gtqxmkyuud.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtcbustkmr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtemktaspf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtgokfcsli.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtgrwoabab.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtdqouogjp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gtsrgfwcju.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvbsxdjzi.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgqisgsr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtegleljgq.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gtpezjkeny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gthaubjsnp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtvyekdstv.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtgysofkgp.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtazoqygrl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtzobhyoai.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtlknqnqas.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtwbguhkkq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gtjckuaznb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtllejbecp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsppsldap.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtexcldnrd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtjlqqowyn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtjiqsbqpg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtlmolsnbe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtzfmyktqb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmkxxeeoa.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtyfzvjkrc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcgwjdsnh.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtgnhyidmh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtyusasqgs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtpmcanhsb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtscnpftsp.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtwfgcrgks.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtqeyfsreb.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtvfzvimmk.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtgdawamwz.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtsjumxijk.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtywdgcbkn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gtgfhqhddm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gtkjtslmrm.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtpubbdyra.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtcqdctvpi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gttdxfupgc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gthoxtzvca.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtddirqdzj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtfikwnihn.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtlilgyftg.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtqsikphdh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtdfraajbk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrblvxprx.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gthovelola.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtlcmlgcvb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtywcyphyh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtfgtxkzhd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtyhgrkgzu.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtcklejiud.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtibghjykd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtnnjhnjpn.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtijmeymoe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtvdvzgady.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtsajayvsq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtbihoripv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtcwdqlpka.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gtpckrtxrn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtfptnolch.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtvvzixkpu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtxlznpmph.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtzvmudlip.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtlbaembto.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtdwgjrjef.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwzciwey.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtjsjiaatf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gttmzioepn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtqzywnuit.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtwtiibtoo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gteqfnwvdg.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtedeovlic.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzadaexx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtucswjwmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gthacummhb.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gtwmufnnqz.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gturyraasg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtivphdpwu.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtnqqxswxp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqwdvgguv.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtihwsyqfz.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtivuocqgt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gttcbossmw.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtjooucdwz.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtexwejayp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gthdgsflal.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gtgyzibxgj.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtzsoptfgd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtyunansek.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtosaizplu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtutmpdtog.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtbezknzgo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtdllrpwui.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtvoekrhyu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gttnuicfsi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtcadqimba.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtaglurely.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gttewtgjcf.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtiyiakybx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gzhubu.top/Article/details/gtevtdyjio.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtabygtapl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtotvtxsky.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtvpbnxhmd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gtqfhsefhw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gtsvfzcnpp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gtwnuuposj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtyvjwrmca.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvfjczct.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gtabyvdsre.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtdjshlgwf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtajzgoedm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtfffuzipu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtidrgfviz.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gtabetlrwa.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtedasvvlk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtyaiyjwdc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtuuaqyhuh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtivuyleqi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtuywwdynl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvmakzta.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gteqpaxjxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gttiqeloxx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtiqazgsyn.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gtjgaxkgdx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtkibbqctf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtsuonjhdt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtfncrumve.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtcxmtoyzc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtvrlkhdow.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtvxmlcygi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtgkdptoju.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtjkgwldmb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtitlvggbx.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gtzfxrholh.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtkyzpykhb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtbnaasjvd.html


<!-- 参考信息 -->