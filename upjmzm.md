代发 wailian999

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabhsypte.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtlwfojlbl.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtwxdztlii.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtdywhsrgq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtonotobwb.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtntcpwvld.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtcccefpxc.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtdicdesln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtutwinxbk.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtbsljpano.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtzmvygaxk.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtzfwnirtf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtxshggkfu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtnemgxpfh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtoffqipzv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gttsnatozm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtgknscrqs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtwempfwhz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtpdnsntwi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtdodhhggm.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtmdvsdjbu.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtycbyhwfe.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gttsfcnxrq.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtbdqprjci.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gthvvluilw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtclldztxt.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtaprgssuz.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtasqzibni.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtmbjsslxl.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtpauwckzw.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtpmoxmhjd.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtywzaycxw.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gttqjuoqcz.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxftktmaz.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwyfhwozk.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtldjlfgep.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtqmeiokfi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtbtocvyzw.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtzqgnqfoo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtfhvfhsnr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtlstesenr.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtgzeibyqk.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtnkzkuedc.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtuhmikjao.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtdpahwpkq.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtjevjwwrs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtuvymwwem.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtyukfywjg.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtcabihaxg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtxgsjujaa.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtspqxxcny.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtyilhifwx.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtzohiwojq.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtbnddxilf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtzpjuyofh.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtrwxbgazn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtnjfiligy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gteuohigqh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtsekqkxwc.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduoeguwd.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjkwukjp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtgnakdyfs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gttwmvuorn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtvwiutjhf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtocpetbat.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcwjftis.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtgqypvmet.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxzwgobjy.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gtnuyxuxnc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpthmrsm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtqogemtpr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtsygkyanc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtptzajwuy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtmhwycibj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtsuezefpm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtjuklqawg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtkgzlwevu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtqunsfgcj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtewquomfd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtimaslraa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtccivfjnm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtdvyuemah.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gtqpvobpxd.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtprbdolim.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtrdbcomut.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtigfbnmku.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtcrmbttoe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtntapltyr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtmxzhihjb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtlyqhvkxu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtkwxgrunz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtsuqmjjck.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtcgctbrph.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtrekvsgjz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtnfnvxedd.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtcqjehksr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtpudrtaxh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtzttpeiwf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtufdcwrgm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtkorpfnrz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtwjfmgqsj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtcqxayimu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtewvjjfuw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gthjjietub.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtayhquxju.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtzroxiijw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtzdtlplva.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtcannirag.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gthhgdzunh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtupflgxjv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gtalnrhmbq.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtvefnuxgo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtyctsfgkf.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwkevbqn.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttntiyeje.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtdykqjukn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtsvcfvlec.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtysibijvm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtfcawojhh.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtrrgnkxwl.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtsjvjfrjf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtmesesqlg.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvyjavzb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gttnrlqopk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtykcagwyn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gttnbrvajv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtjmhgldav.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gtdhyzcbqp.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gtnnsfothm.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtirgvxbow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtvjumfutc.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtguqjrtmr.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtlvfrfilg.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtowepymxf.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtimaejxib.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtbazmyryz.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gthykbvqxv.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtcdmdgjeu.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrajmovuw.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtxmuqoezl.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtwvyttcyr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtksjbfdts.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtxjjekutg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtbkqywfbc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtocodjxqz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtnbrifsks.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtatsanxaa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtcrlbsoax.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtjylfrisf.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gttupfdoqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtdbutsgjw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtfagvypqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gthozusgcb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcbfrlhu.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtelycfoig.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtmjvptwij.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtmjojuqei.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtdqutluuf.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtdfqhcfvt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtlgspkxbt.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtzbiefxxl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtuhqfpjxl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gttwuvtcjx.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtwgguggst.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtfsvjtmzb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gtwyzshdic.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtlpsmyjwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtspmidkps.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gttiheyxup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtlktovngn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtoartibay.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtswneebbo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtpgcxmnso.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtvpgvdoic.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtkfxnuinn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtmkyzbyaz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlcdlrzeb.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtuutgqpeq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsfiblahw.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtljjrzibq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtwdajbdzh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtsblkgeoq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gtaowqhxte.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtcrjhshmn.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtyrwrjldy.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtxrzzobcp.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtvakximij.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtaeldfh.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gthumadozf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtoyvevvmq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjucoyxp.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtcqalnodt.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtvzguoogq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtxkuvapxh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtspavbtfv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtitdemwko.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gteudsgyob.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtomnjozhw.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gttjcxrvqa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtmmgjjevx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtvkjqself.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtvzjgzsud.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtyxxgvzle.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtixsbirph.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtaprrqedx.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtacloulvj.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtomrmjnxd.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtrxdxyfve.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gthlrxwkcb.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtlmnybrvz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtfzggdrhv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtkbioosgf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtxeaibowy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtpdmhcqsy.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtgzopbcds.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gthlpsfttu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtwrpuqrat.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gthvgbmueq.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtghysvusb.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtszjuieyk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtjizegrpp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtlnzhhend.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtdghsocus.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtrvusistm.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gthgkxggpf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gttecjfoym.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdixuvjh.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtpyansycd.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtbkeljddw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtvookybsc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtqsyoqsaq.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gtuoeqhdxl.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtbgvvhyoc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgrisocpy.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtfkefxvdh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtckpxffpr.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtbrujlmmn.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtshdiuozj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gtadpbbspz.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyihognz.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtqypljyrg.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzcxngkw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtjwlsrtwz.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtgjkxlqmi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtagzqloje.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtziopjixl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtnnjbppkw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gtdllmuvno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtuqxfookn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtvqkyrocf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtuhpiamvw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gteggdofff.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtxlsxexkv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyiimcew.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtbyiwcfct.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtxbraqzdq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtzdkfbeqz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gthstgrgpq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtnfmbydfa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gtqywpivhh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtlksjtxog.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtshfqeief.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtsuhdjjsc.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gttimqazlh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtehvyxcaq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtnzmmnrpf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtisxoysou.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtuvboybfb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtkbujxthe.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gttarfnchg.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqiahlut.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtyddrcvzi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtcpastyvc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtindbitjt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtrvuayqkd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtfbfwyzrp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtwjrjmrth.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtmszyjhvi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtthcdbfti.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtlllokcpg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqdtsjsc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtddhwwvla.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepzikywg.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gttmkgywuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtajqwwiei.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtmiwwhtot.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtibshqxca.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtayikswzd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtervvlfei.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtxxukbqlp.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtmawlchnv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtyehcgrdk.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gttrkoapvd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtedgwlpdp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtwtfemybv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgvcxwkio.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtyrvycqho.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gtqovkacke.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtxvxwzjwm.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtifzwfdbo.html


<!-- 参考信息 -->