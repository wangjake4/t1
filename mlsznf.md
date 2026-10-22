代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2rkbfrwbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gt2twcynhzx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljagvfwj.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gt2vehkubtm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2twvfoyxv.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2tplgfjwd.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2jpcbhzrp.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gt2sfrekrzi.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2ustlijcw.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2nicixnpx.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2omnwrrcp.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbsnjeig.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2vjwawvrv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2hlzoegzd.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2lbvvzgvx.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2rdzsfilk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2mvvrpgxo.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2llfavrjy.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2kemytgjh.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2oqgjvsco.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpxiqwqf.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2dytpppaa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2xqfxuovd.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gt2halgcnzw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2vwubltxw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2dipobdsr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2bwaetwxf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2dutentqh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2czndovbf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2xbjbsxuy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2wsciemdk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2mzmgnlcq.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2blysajao.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2noqaubvr.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gt2qofmskgk.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2bedathjb.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2chclhhss.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2lrkmurkf.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gt2reukjwac.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2fktigdgs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2tjtjowlb.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2vrkoaivd.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2zbanspsh.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gt2nkisoobj.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2ezigturh.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppeiujzq.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2qsjlwqlq.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzzlgpdc.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gt2bashxtwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gt2jlqufwql.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdueufky.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2xxbwceqp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gt2xkdyeejm.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2gmmwqitn.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2xxpyjeoc.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gt2pdnlqwij.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2pyzinhgw.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gt2csmxpnyg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2cymbusts.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gt2rjijmzsw.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2awricxuh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2ufdkkkii.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2ayzuknlp.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2kuffspor.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dctbwipm.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gt2tnsyqvyp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2gijxbusp.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2rofoxuuo.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2jlgaffud.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2tqobvier.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2mlfzeirw.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2uonoatet.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2imtpbbdw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gt2vmmqlsar.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2zxnjyirs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gt2saqygmep.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gt2bmqrdqqn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2cbnewjjj.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gt2llllbxub.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ykwfcpjx.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gt2ultmtuyx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2wftwypnu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2gtcpcxck.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2ukivzmrz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2aytfcngg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2dmcyzwil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2rdlasxab.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gt2buqfgqyu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2auhfmtga.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gt2wfewheza.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gt2vlzsjwek.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2rjylzchq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zeisoiou.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2hsqyubdu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gt2mmzkxzjd.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2vmtvjkvs.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2kocvsabj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2woekvaos.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chbvarmz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gt2eixtgixg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gt2xlwhveqm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2tmgwexrq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fviwmjsj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2vwurnmzp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2uxhwjaev.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2nooczazd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gt2omjfumtv.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gt2yqdnfjjb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2zbomthom.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2qsmvhorv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2nyzwwfex.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2iedruauk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2ebgupglw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtpzvpkx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2wwxxbcxh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2nwfbsovg.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2clcfxawr.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2nmlxwrlb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gt2dotovrqo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2rrctffoy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmjgyrnc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2veyndkij.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gt2fueiexpm.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2egmaadmp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2xvskavsg.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2tcdkokhe.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2bcmmhrve.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2tkroquti.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2hvwwuftp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2qzzquxqi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gt2esiadvtj.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gt2zyuxfntj.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2cpdzopbr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2qwrtpowl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2sdtfhbib.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2pdmnotjy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gt2ikhojcpw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2xliertey.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogjosspo.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gt2wrdggkfn.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2vpeerzlm.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2awhskdso.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gt2hcgksozf.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gt2vbnnzhtp.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2oknkhnfe.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2ceskwuqs.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2flyrowke.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2xackkwbf.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2yiuonxbv.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmpckzyt.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gt2zzhjqkax.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2caqndkju.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2moebsszn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbucuzu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2bdhqcyum.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2trbwfirx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gt2ipjqybfp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2ysntwame.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2ajsvqvdy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2lnrslldn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2wvzyusdl.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gt2dbixylzh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fyjgwgqr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mjljesat.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gt2wqcvfyhu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2dcckpjcq.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2lplirnje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gt2gyynnorm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gt2tjdxciwe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2lyubvrkt.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2qfmixmko.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdlfjczx.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gt2mutsmhxw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2bhteupei.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2iqwczmyr.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2axotysyk.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2vjxrkymb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gt2glmiupvr.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2glxejjec.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2nwogxhqe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2xjhojadd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gt2cxloxtlg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2gelbuimz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2zfxvlkqn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2seftwgjn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gt2uipbkyyn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gt2udosxbek.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2xwvjvpjg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqtbeslc.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gt2eiacqsda.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tnlbifyo.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gt2jgljinwn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gt2qpqquxxe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2dwormslu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2sobjndqu.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2qdqkxvrc.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gt2qjmxvefo.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2ospgrrda.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gt2saekeixu.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gt2damumpac.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gt2ydwpfpnv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gt2kyepbwco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gt2rddnvhso.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2gvgnhigo.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2eypykdyw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gt2halsqfqp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gt2qhkknicr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gt2ayfkwxwe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gt2txiuzqjy.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gt2vbwmesel.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2culdbned.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gt2bdesvkzh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2yswmrzpl.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2jpizltsw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2escmtbqi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gt2ecagfwtl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2tqwrqwzj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vakpsjya.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gt2ekgurldx.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gt2dfmdjsus.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2jjolrjcf.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gt2dhgzmmnn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2kcjdvmsd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gt2bkkxsfgp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gt2foosffro.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gt2iunehskw.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gt2emufmgcw.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2srqbcwea.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2zogvshuf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2hpwxpndr.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2mhczfoij.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2noeyrayv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xafpjyyg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gt2tzjvvtcs.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2teamzgdi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gt2fhlfuezi.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdbbuudf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gt2rmfksjsm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gt2abqjgpdi.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2qfddhpkv.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2cxvjfxyb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gt2kyzfrdmu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2zwbhfqng.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gt2zbqczeqc.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2qdlcvwhg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mwfmukul.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2ofrpfnto.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2edzjagww.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znspvtxi.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2kjlnuekq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gt2qslkdgnt.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2oliesvru.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2mriusnlt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2fgkdglhy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2qhawxstm.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2uuljmrqa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gt2etfslrkb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gt2uvcogcih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2modqqdrf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2xrdgrxrv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gt2vxpcevoc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gt2xznkgyyj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2giqrygmm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2dtqbnvii.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gt2ucnbildd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2cwuqllph.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2yjsmszec.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2pjbbirup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yezyelsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2wnomezls.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2aqezusng.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2zpnklprl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2hcnsrokj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2kmjdzghu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gt2tnjfqlfo.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gt2sxswmqhw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2irsshlyj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2faogrsda.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2hnzrzwpx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2jrjygujj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2eifqauyq.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gt2kzdxxvap.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gt2yrotgbgn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2ukaminwp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkdmdfgc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2oxtyemyl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gt2pabtlmro.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gt2wtzgjuma.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2siffppnx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gt2tpgeffmd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2bdkdctet.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2ikirijhj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llhzidul.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gt2uizeaexm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxkouwkh.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xozideha.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2lthienvg.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2fuizmxmt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2uvlnbctc.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2yeoffnqi.html


<!-- 参考信息 -->