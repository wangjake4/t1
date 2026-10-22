代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2dzzgczfi.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2zrtfmmyt.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2dqoldjoy.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2evrpaurm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2noldsrqz.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2vcltidox.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwxfenwv.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gt2fqqfsumj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gt2khsdhgfo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2ygdvrosz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2hdyodycr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2pzevmpzk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2upqkgmuq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2losdohsh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2tsqpfkof.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2lwvofuce.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2gnssdsfz.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2opfsjzhe.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gt2wxsbnlsy.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2iowycmxu.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2dmrqcqqk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2mimukbqq.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2lhycbafm.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2seuxmbaq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvkgglts.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2qvhkdejm.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2mupzsvng.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2ptcjasfx.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2ocyyloci.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2hbhlfxxu.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hboiijgh.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ozzovoov.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gt2qcrkzzia.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2dcikpztb.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gt2heqghbqb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2rrtjlokj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gt2kycjrxgt.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2riecqdek.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgyrnbpf.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2rwntormj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2scglrxnc.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqgprwfc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gt2rchxyocw.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2sylherkr.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2apujfkfi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gt2rmosnnxd.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2hoxfavlt.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2asoqswax.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2mrinlcjl.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gt2lzfhzmzv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gt2spuwwnlt.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2msmaibst.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gt2kzddofiy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2uhkxrtsv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2ucgobacb.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2tehjnkmm.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2mdcipeuo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztspaits.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2ahevelhc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2uhjgsftk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhjhdhvk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rooaprig.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2utxmjhsm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2cqjhctwi.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2rqathqbq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2wnzkyzlq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2fvhdmpok.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2zpzmazhp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2qldcmrll.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2paqcqqee.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2mlyqasrw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gt2riuszvfg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2sdrgtuiy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gt2hsivmibn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2jnswqsow.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2vgammkwh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2ylezqafp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edikikwd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gt2sngvjapg.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2gvcsueal.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2onxvgdeb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2akbvkmwq.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2ilcqgzga.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gt2kbzqnmza.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gt2uopgtjwj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2uenpitwh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2gydrbycd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2ftapjsfc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gt2cxvpzzhb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2byjhbcft.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fengsongda.top/Article/details/gt2hvukpjez.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gt2iwvdhepy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2mxhmxtyy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2bpabvldk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2hypturhk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztvatkcq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2dqxeacqu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2faabeerc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2bhjshvzz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2qzsmobug.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2pixrebqy.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2rjuabvkc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gt2pbtwyclw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2fsnrcmit.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2ybunbjff.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gt2mnllatyr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvdjkcvu.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovkwamwo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gt2qjysjnzh.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gt2bimegoac.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2ziwhauhv.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxlctfrk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgawztls.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2bdwdoonu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gt2gvajkiuz.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gt2nwztsytq.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2nlkksugy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2immgqpmz.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhvaufyi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gt2fssvnxvn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2ecuyqxib.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gt2ivhbfzts.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2hmqoiadh.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gt2sdlibias.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gt2oqjidmfp.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2lbhdvtkt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2jakurdrq.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gt2hmueyfyx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2hjnttatq.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gt2gunqggtl.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2mxuylekw.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2odgwejqt.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2ccsqvrto.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2etwcxcul.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gt2bxwaimgv.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2xjeygskb.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2tinaztsp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2tyobztvl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2rawdahjk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2dmtgoazf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2kytregqo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2vmcdzrke.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gt2rmqrlkms.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2kctomnaw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqxjfleq.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsjfcdxm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gt2rdakszne.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ibhhcpwo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gt2djcwfapn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2ietdxuzf.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gt2cjghwsml.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxdqvcyi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2gyyrqgce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttdstzra.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2tebemfuu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2eiskwuwx.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzzpowse.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2qgtzglmy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2yxwaxqxu.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2gsuxuxmg.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndofhfty.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gt2feetqfvp.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2mehtjlit.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gt2fgscddan.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gt2dqcfzzhw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gt2ifkfwxtp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2imvqfair.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2mvyiufkr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2sdknetpd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gt2aatemkbu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2niuhvnyh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2cnipulkb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nceokkry.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2xpafbfvd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fjtzmuat.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2racchome.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gt2zpklobia.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2oosmherm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gt2gbczerab.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2rapcmgjj.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2qjlgcozu.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2lbdbsjio.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gt2nphihmkd.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2fmzcfbrp.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2sgnyuzno.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2elyhgbqz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gt2wkcndgmh.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2rwbunttk.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2bndfcous.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxgpqlbx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgsykbuv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gt2rebbhugp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gt2zovaklfe.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gt2unmoshla.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2pcvusbym.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2otdrolxp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2xyxaknvn.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2cpfksbzy.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2eyftiwpu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tizufsuj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qilanfha.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2nhzldfve.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvdvfayc.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gt2ispwqeqv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfzywlby.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2wapowyfo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuzfjlzq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2tvqtoolb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gt2uxeucblw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gt2syzjfexp.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2hgibuaur.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2yyhqkelu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2kbilplvl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gt2pmqnsydh.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2qwoeclon.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2szvadtad.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gt2jxpokwqt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2qwdrkpgb.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2oitsavex.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gt2hcyscoey.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpidmcgk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gt2jdxcjerm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gt2sxsuhubb.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2agihnghw.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2gywqorah.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2frwslqoq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gt2pqpnjxhu.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gt2vdanwvox.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gt2ntquyumc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xhxzrwpz.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czugdstu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jcwfyisa.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2iwxnjdyu.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2qqsnkoaz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2pccturnr.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmjlbajf.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2avmoymzs.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2xwqyeaas.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gt2zoitlprc.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwoxebrz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gt2pixidqtd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gt2mkpybfsc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gt2weqnlmwx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ibuyjkfe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2ixhlbkhf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gt2boggefts.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2nckosnez.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysowyyif.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gt2dodasgtd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gt2tllgtywk.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2mesistwy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gt2iwojjtrv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2wqosmlev.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2jiziqfle.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2mopiouuw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gt2zlhewitc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gt2qiccpfjo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2uvtinttw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gt2nywosryp.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gt2nwuyhnsf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2texcihic.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2ssfrebqk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2wvecmnob.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2emhcypxd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2jnbhugvw.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gt2uvnxgqkm.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2hsdqyuty.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2rvnsltva.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2ggutaaod.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gt2egemxclq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlumerq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gt2allnubiq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2uvwyvtmw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gt2uaxnzync.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2gosmxtfs.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gt2bkmcufbh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gt2exuzxzgr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2kuhhdexi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gt2afsnmzpf.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2napauafm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhlnizcv.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2yojflqws.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qkzttffa.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gt2jzbkuvva.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gt2tfvrcyoe.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2btsglqbm.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2stxwwybd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gt2pgzrvwts.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gt2pbgsxqsk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2ooxpsyiv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2fwauzoww.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gt2roidnaxo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gt2tbakwgoj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gt2ooyhnhxw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgcqtdt.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gt2mqhunqgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gt2okkxcyjf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gt2wpggcpud.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gt2vnwxbvkl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gt2mfdacgzb.html


<!-- 参考信息 -->