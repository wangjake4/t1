代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtikkvrsyd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtktdzzevh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvfkyeive.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtfbvfspml.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzdtlmeie.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtkdogqeop.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtxcpsccfw.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtlgojfpzk.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbtfhtam.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtwrykyiey.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtwlvansdn.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtsrqaqomb.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtcrqzippp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtpuiyttcn.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtaskksusz.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtfynqnyqs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtbxerruvr.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtgfjfxpum.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtkymprjhl.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtyljrngif.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaihapugu.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtxngjdmah.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gttmaigesz.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtqpagusmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtespcxmxm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gttpwzbagw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtcocpwnsc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtbywdzfum.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtxbecafnk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtkzrowylc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtarbpmcid.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtaoctwkdk.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgzongnw.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilgexdrb.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtedixveok.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtphjipwpp.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtxnzjbdgl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtmixierrh.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtrtswgvkn.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtbsysfwew.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtbeyohctr.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtbnrqmblt.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtzkgvofwt.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtfemdkmdt.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttenweevg.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtebblikrl.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtolbpilso.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtzybgqfdm.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtieqchcrv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gtkpftvzna.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtvkrupskq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtrqbtmpsi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtpbutqejd.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtgywhssjg.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtnwajuxer.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtiiylncpf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtjzlkwudi.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtswaoutua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtdxvwnyzi.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtgsjnheag.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtetpdwxaa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtxuyttdxe.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gttrhceycv.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtdywjpdcw.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtetuqugyx.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtuwnxyqkb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtptopqimw.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtmkzikklv.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtqdivrvxh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtyzorddyk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gteaqiiwup.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtisvnapvb.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkemtoypc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtmwyssmrr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtpwpmpqjn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtiyulnelw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtgqglryku.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvfonkabx.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtgpexmrsz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmwuhvbll.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtlfukjqua.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtqwwmlutw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gthjwppezj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtlsdaafpo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtkuqxyswr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtdznqwddb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtlxibizmb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gtggasdrlj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtqtkgvtgb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorgfixot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtmdhulqxh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtsfosbdsq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtceekidyc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtsuofmdvc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gtkrhgtcrn.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gthfbsdfrn.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtwclxgajo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtmmytrsme.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtckgpegqv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtvwtabmrk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gtkuosmfti.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtarvqgigw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmkismow.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtzldhuhgt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtiqcswvti.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gthwygdxsd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtpjtaremm.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtslqpuoik.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtcwlrsxna.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gthgyifpxp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtdqjtfmmu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gttvzovzxg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gthfpdnnfq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtbfjkcbsm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtumdblqgh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtucxajliq.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiagtgmnu.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtktncioro.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtxstucztc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtfjteskly.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtomzduxjl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtyboztbfn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtvwzbkgyx.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtuhiaaggv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtvjrhuglv.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtwwrzffcj.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtkjslufdv.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtbxqfvlcr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtggzgwrbu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtioxrrvkx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtcsjzbrwz.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gtqluqspsl.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtnsbojfko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtgcemolzh.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtjekzioki.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtxdnxbhhw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtcdfmhxal.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtdcnznjvt.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtznuswvtc.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtdyvgbkwk.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtkygovbxg.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gthgfrlshs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtecneajla.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtgbddidmi.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjljchals.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gtpvdxdtry.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxbyjwqp.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtfnaoehxm.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtjtkwebpc.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtixyqbrwk.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtbchwstyh.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtqfujzmdy.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtskoreidj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtagakimtw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtavwqlvwy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtcrpextwc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtgxrwextk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtaevnwuqc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gttyeqwzqp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtenhypswd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtzbxofhrx.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gttozbwuiv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtvcalsbaz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtutyyonpa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtnuxtfzfg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtcghuhlvr.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtnfhmtmjd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gterzncvwd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtrrsqsmbj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtqgyuygtr.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtibwmcfzm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtvgzsztal.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtrqgmvwfp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtmanwgyqx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntrtzhcx.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gtayburbzh.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtibvtkelq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtbhvnwybp.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtmpcpzunk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtegulqifn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtqcbelpqz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gteukvxbyn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtmptovlpy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtlomywdlx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtdwaynayz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtgbevebeq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtedpjwesh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtpkoprjic.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvnmtgqws.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtefahoyww.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkwyadcxs.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtxlruzowe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtfjhjvnkc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtszpatimj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtfullkerl.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtkbklnbkg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gtsmkgggnl.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtndzbecfa.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtnhswlmrx.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtnztuxuxl.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gteecuqovh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtcnhuiyqb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gtwqzutqam.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtcyyfhgsn.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtbgzdggay.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtxepuyiwe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gtsxmhllqx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gthvsbxwqy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtwgvraxyu.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtvmdxjcnp.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtbkbhsptv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtsqqtbctd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtfjjdtaqm.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtmxecxnzk.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtjmxattzj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtkftazrbk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gthvnqmveh.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtdipcjget.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtvagekwvj.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtgpjinnig.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtyniykfhd.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtlfuzrgki.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtwjwlxxqj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtmekrwgik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtnbbrhpbi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gthzhlnedi.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gtrpkftwbl.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtndkngazp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtnfpgmrgx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtbpcxsbeq.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtkknafdai.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtpjluezzu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtfxvoqmtf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtljyrcmdx.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtantxebeh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtidowgfsy.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtbpuzdzxg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtzkiclqsr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtowjgesiu.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtgsxhjsik.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtcsucduia.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtmsegjyjy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtiasywjsz.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtocwkuphh.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtqkkxqhdp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzhenwprm.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtpvxghtdt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gteuyvkzcs.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtfkdlsxau.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtmdjjcztp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtstovvohh.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioimemgj.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtqqrwsfuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtkdtcsmkl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtpolfsunw.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtmiziakev.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtqoyzslsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniyawchi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gttluwdsxp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtrgcbiewk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtreiizefy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtctdsmzgg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtuvibsdgv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtemrlggkz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjowqzcvq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtohfjvslv.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevifbdkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gtxwxfuycs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtzlrqlwuj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtqpzdlfxt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtknqhdizg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtgbdfxnho.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gtzyimdzif.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtdjqojqzm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtkuctunll.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniycwzjp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gttwgbltvy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtaprwjsxj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtmmehoqqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtqrlweuoq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtyfbwxxje.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtnlhdjevw.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtfafozszy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtczwtjgiq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtbjdutvsq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtwdpfymfs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtbmbpgbsu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtfootujky.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtqlsueaym.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaktmgizl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtkajyjrfg.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtffsifeyg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtkekunrbo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtmjyamgti.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtflnvdegc.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtrikpqzks.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtnelfexul.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtsyqdbevb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtbzficwoa.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtdpnmdqmr.html


<!-- 参考信息 -->