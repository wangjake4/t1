代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2rfseaqbm.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2rgsgquie.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2tsifjnjg.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2nbtidhof.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2luqzxkwf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyxbstkb.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2efegvhex.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2shyevuml.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2ypgtntof.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckahectm.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2samntctq.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gt2iojjvfqj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2chhtcdhc.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gt2zhmtpxvt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbzospou.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gt2lyjdnzuw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gt2tfhyjzcw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gt2lnrxkvoe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2mehfravm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2fxemvbbj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2ubcughug.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2ltpsjuqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gt2bveibqfg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2cdbyyeyy.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2mprimzzr.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2kjobregd.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ochsfplq.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2bbjlnbav.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2mdaaoafq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdueytiq.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gt2ottbkfgq.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2huueuzqa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2vnrijpxg.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2zeqizhyv.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2cuxarvrb.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2ssvxosac.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2cadmnpuf.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2snesicbi.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2ziwnjhna.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gt2terodfiv.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2kexvbvsj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfcaicsj.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gt2wbbxsnvx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2lvagaqad.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2gvpespaz.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2wsjkcfhw.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2gpgdvbbh.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2ajkvnkmf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2tdezjfxu.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emmnazff.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2qpbwwakb.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2sstxrens.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gt2qqydbtlj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2ypltmbov.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2tlgbmsue.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2toyhhcwf.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2nkphbvmf.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2shlqzzrn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gt2fghzsqtn.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2adtdyuuf.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2ooxoaeqs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gt2twxarjaz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2yfxxexxz.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2frdzfxpa.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2enpxevrg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2akyfcbiv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gt2qmvjrqgp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2swsvhmyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2dcxveupr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dyczqsng.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gt2fjihygkl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2darxkxbg.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gt2gnwfwqjk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2bprbigwe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2qgntpmjq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2aoruhqdp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2rlqtazmb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ffrzaunc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2sjmiscrr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gt2phffvlzt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2aegfwkea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2lcjvxnst.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2edrcbzox.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gt2ncnpwwjd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2nrzmlkkw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2dzxtiayc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2teyqjhoz.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2vcefvizr.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2ddffgzzu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gt2diofzdav.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gt2ixnbwfkk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2dangifsw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2saactutn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2ujzorwhb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2plkwbque.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwjxcdxh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gt2invlorbw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhbttswb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2oiyltkpo.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gt2icnszquy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ooxgwawh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uejcdtnc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2awteycsz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2bftlkfen.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhzktnwb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2gqhtvvwt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2eerxbvuq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2ohchaixp.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gt2dipckclm.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2dowranjq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2frebsysq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2nxhzqlvx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2kpcdxvcn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2zsquwrzz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gt2ztpkfgry.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2jzvqotmm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2mybylmlh.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2bcqpjfup.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2tpfgydwo.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2wqqmgfyz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2yctnctth.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2erwdzvox.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2fcjpmaex.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gt2onnlzlxy.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2zzfrbsig.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwwqcbqo.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gt2nahcvywb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2jdrzsahp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gt2cigrthtl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2pdwxwrpy.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcgdvxpc.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gt2vtmkjmeh.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gt2hbuloiqa.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2cifpujuj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gt2qpmazgkw.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gt2urfzqkei.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qigltyqy.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2jqxzhgpu.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2ufkovnlc.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2rdmajrki.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2trzyrevp.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2bdpfoseh.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gt2imrjllzw.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2cprjjnyt.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2dmpimgnm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gt2guuavkhd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2kgcmdpvr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2kamlkldp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2tmttzbae.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gt2eumfbmzz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gt2kbsshtva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2pxeuumjw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gt2vvadjsdf.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2aczfndxu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvftpsm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gt2htldlgws.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gt2xrvdidnk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2cvigxjue.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wfguznwl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gt2camiauzx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezzjlbja.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gt2onkzggac.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gt2zurqmlel.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gt2bewnprmp.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2lbbzfyju.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2yrzhhoul.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2qmjwxpcx.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2moouummr.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2jnpfvual.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gt2zusjkpsm.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2mnxftrju.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gt2geazipjm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2gpjxmokq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gt2ginxmxiv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gt2iuxafrhy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2vkicjcnc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2zbvzvwfl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2snucivmo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2meickmqe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2yakiabnx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2sbgotwwp.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gt2itqlpkzp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2yjbgmrjd.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2qozhviys.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gt2jndwoizd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gt2qhohkovo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gt2wfwvfmhx.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2ljemyqgx.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gt2orafrbkx.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gt2nuelcvbs.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gt2hwbposrh.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gt2vrrlmjdg.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gt2uluysgnq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gt2szddblvt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gt2ryyekpfw.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2gsksmxft.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2dlhryoac.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gt2qwaqbliq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gt2eycimytf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gt2owbtchum.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gt2tazghudu.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzdemubq.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2qrsyvpxx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gt2oimbjxmu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2kuvuqnqe.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2knxoboux.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cimqeszt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2uoaeturv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2dpwdqlck.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uithwnpy.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2yahyravf.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gt2ojsgectb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhozluqx.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqqefvkl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2qgwxxhri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gt2rolxqhdt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gt2pchqvujo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gt2msqwzfkp.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gt2ietwtzta.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gt2lqnfzmwr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2vonkjnbj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gt2opwqktbu.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2igpxtmdb.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2phgwdtuc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gt2myapvbph.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gt2rkkbound.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2pndfdleo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gt2rjwiodbp.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2fdoinbqh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gt2eejldfju.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2mjcfuxmf.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2envpebod.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2lpbsmzxw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2pytyyxtk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gt2poesxbly.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gt2upjbkqco.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gt2vnpkcanl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2lmoolybk.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gt2dbuljkmk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vqtycviy.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gt2yorjyqtu.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2hlexjxdg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gt2npgvyouo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2swrblame.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2govohyjf.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2robjfhia.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2hrllfxfx.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gt2vtwjkuep.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gt2fldmjhpq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2snqhzlxl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gt2vsvwibno.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2abbytpzt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2fypqwkes.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gt2ixccmbkt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gt2hkuegjyv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gt2ngahpxee.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gt2egpfxjvt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gt2emlrjkov.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gt2arceixwl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtfhccx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2yymsqruo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2xgribfne.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2bkmztety.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gt2aidlnwkc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gt2ljmczeqz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2grgrkaea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gt2uakpmjjy.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gt2bwwpqfdg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2wlheqjup.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2vywyjawg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2wgywlfys.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2tfehgpzu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2lvdavmto.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2dknascxb.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2wabkbtap.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2ysesjwpp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2bahlarte.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gt2uzvbrthf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gt2hywinjrm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gt2iclyxujq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2jiluubmm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kswpxeuz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2ecccuuno.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gt2osebhxlo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2qtbcdwfh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcvzeszg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2bgvpmgtn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyzisqq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2ycmkdrjd.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gt2jfemppwn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2pdzgxjib.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ppqrimtx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gt2uokddfkx.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gt2likcllit.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2iaaeuyzi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gt2yndywgeo.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzkdkhxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2mstmzyoi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2urqacmnw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gt2waqvompp.html


<!-- 参考信息 -->