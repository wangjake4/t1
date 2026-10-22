代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtvvbuqvwd.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtvdnwvebf.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtuqvyjbla.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtzzirtyma.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtbfiixhet.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtcwncqwyq.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtigycaxjb.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtlvlncshl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtugyackjn.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gthqkcenca.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gthowevcpv.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtyuviasrj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyanahukp.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtioefeoof.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtiqbhpcvi.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtngbbmkel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtsjrytvap.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtwkwadaqw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtjzcjvhop.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtsxuivpdt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtvwwjyxfw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtkkozaezg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzdqbzkl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtpjtcrhpo.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtfselclzh.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtnrquuvcz.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtdfvqoqrc.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtnfgdrsry.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtlijzjoxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gttkgqghpe.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtnlozkkdj.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gttyuukqon.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtziezotsl.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbupijsue.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbxrbjql.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtzgoypncc.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtthteeteb.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtfxixxrru.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gttbsswkwy.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtqpwkmyiz.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtgfvtmcns.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtomloepjk.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtgsmlwoaw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtabdcowdt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtoenzerii.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtrwsdmkld.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gttjlztlbz.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtttmnlfiw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtwwfkjaxn.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtmbfrezcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtidrhumfc.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtucklpljm.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtfciwghkz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtwnrwsvyd.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gthftqiavj.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwngljee.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtotyevqzy.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtrymcuuew.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gttqcvpuwa.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtzfvlnomi.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gtumzvohfb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtkubrjftl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtnajadecz.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtivopqavf.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovkbmroe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtkjyssath.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbinukbux.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtgiekdgde.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtwbsvdzvi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjbjdogdr.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtekdbfbyo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlietzsnp.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtrutnnkwc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtrutnkyjw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtlrxxqibo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixrcyxdk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtrigzhfoq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtgivatlcp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtscvczelm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtzehtvkir.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtqgumuhrr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtenmxdcfp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtgnihyovt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtkfrbculw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtwqohubky.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtzisdiklx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtqecqhmro.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtffqhgtfp.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtileogrdv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtiouxcbjj.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtjubwkffz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtjidgsazu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtgzhplkln.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gthxbagxap.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtmuptigsd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtjgsiiczx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtypvrzhcp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gteelybvvc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtkzzmuecg.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gthltqlfpt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtbmaywleb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtocyekdhi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtaxdgiekt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtukeufvgo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtkcpzbgho.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gthdmetjgz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtuiyuhjnx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtadygumbt.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtlizgiqsc.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtxmzrlnnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgbzblwn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtjpfeqvsd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtkffgjsut.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtfcykmbaf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtxvajnwaf.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtqkshiqgm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtayhqqwee.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtehwiauzz.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtiqwalbwi.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtrwgpjzot.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtpbngjohb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtitepphxa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtdcvaigmp.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtbauqqvuf.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtplrtlmti.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtdaihojxr.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtqfhczzcb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtydjscrtk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtxxqaiexc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtmcjgbisq.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gtwcnaxzwt.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtrsavgagw.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtegvftcmc.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtpjlrhvzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtlciskuhu.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtlslffzzq.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtdfzwrdhm.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gteffusprl.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtievfevrg.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtznhikvsv.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtsyebapgg.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtlttffjdp.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtchbrblvi.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtidpexojt.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gttzncyajj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtartgdksf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtupfzfvol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtyskjkctc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtoovsadca.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtepyirzzz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtasmfbqry.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtdghqdbbw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtvlqppkqg.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmepgawqx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtuxunahxl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtggjoppuy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtvifctlaw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtsyralqpr.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtzmcwpnjn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtlxvalxij.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtedzrwgee.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtzxpqvwsy.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtwspugins.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtairunjvf.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtonliccrl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gthlpafodq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtvumrtisa.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtmwoxsucx.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtmzwcbkjk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtdodaufjq.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtoctvenjr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtfjnbafzp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtspknldyq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtkbrltcmg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtjbfdxqut.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gthdstwicg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtgzwvbfou.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtbwgnuxlj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tianlin.xyz/Article/details/gtbfwpbjjd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtgtstcmhv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqaltfzpk.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtwqdedjfa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkgkgexw.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gthknxevmh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtvymozuyq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtujevlskp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtaswciukr.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gttkjcohno.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtepixznag.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtceolkpse.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtohdvaswi.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtcheehvbb.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtnapvgyqx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtxvyskghw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtlfbzrvvu.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtgodaoifv.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gttkjxxsrn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtnalfxzuj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtbhehfdiy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtrinfvlwc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtkrsoppzn.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtkoubisxb.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gttseizjyk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gtkyazdbpv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtrbtafncx.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtehpjsiap.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtyslvmwfz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtzqbivvgv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtznbzcsxv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtpmtvfefu.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtfopvwcpl.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtglycwbxn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtgtjpzxlk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtcpteswjd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtqpeesuly.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtyuqczdmm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtaembmamx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtvqeimqti.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gttmlwyjhb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gthpgybyax.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtxmccxnvt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gtkbtvlpez.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtjudhvddt.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtjumhgepg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtkuuiyddq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtpdieqrgr.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtqdvhfurp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtnubaegvr.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gticzpllja.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gttjffdsbw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtlyvzgcqp.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtjavfeitw.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtrmytfotf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrinwobg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtcgopbyoi.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtcdesacqx.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtlkimxjmp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvqjtaqpe.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gtiwvlluxh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtijcnqztv.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtodvlgyhv.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtrhjpqgdz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gthlyerhqr.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtjnkzorrx.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtzuhhqick.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtkqtiimxv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtyucbpkwz.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtlxpfqloe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtewyncbxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gttflmgyko.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtnacijhvp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gticytpslm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtpnbijuxt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gthsvrquae.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtxzcitpvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtkhqvjset.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtyhcwrggg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtzvakvxnt.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtrfbgxnbt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtlpqugeas.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gtkgjnhpjo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gthasvemwt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtzjpmkcda.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtuqnrlgse.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmziavmjm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtmiylvcio.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtqthniefm.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gtnbnwhhot.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtibgvgiwm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtcvwzlkxy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtwtharoqh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdglfynb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtosqvowup.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gtlntpiqxn.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtoqglteif.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtwhptnqjn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaumvmbv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtplbbvvzw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gttdhruqet.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtvuazompu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtiyctcktr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtlzctnigd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtgmzwhqpd.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtlgwycpvb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtqchsxbfl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtyweibpjr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtofxuazzu.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtvbjnejou.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtdmozstsf.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtojwlunzv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtgwzulvth.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtzryrcofc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtrtfowhvf.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtpsctttxa.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gtztzbwxiv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtuoeitjhg.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtclnixtea.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtmmyrrwfj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gthlxfrfgt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gthyuomtoh.html


<!-- 参考信息 -->