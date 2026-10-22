代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2hkkbritr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2doivobys.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gt2itixovyf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2autohitw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gt2jxjlsomi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2rkoxzuha.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2giartpvg.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2lijpauok.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lelioxac.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2kuobczls.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2jcekzdrc.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gt2twjfyuae.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2kawxykcx.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2zyskzeaw.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2ljibvddu.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2szcvvqme.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gt2ybcskkcu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2swlsrhgl.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2bycbmkji.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcbucrjz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2avgxmbgq.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2wmfrlipg.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2osteaina.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2uveecjws.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2wdewszlb.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gt2hrhoivqx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2ztlfadon.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2pmymhezf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gt2koicqcvu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2vxotxyjq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2atojjvnv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yluzahgy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdzjfdmd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvypjpfu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2foxgxuxm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2kogegqlr.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2fruqvgjd.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gt2bcaufnfs.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2drttobwt.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2paxwrigs.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2jxqjtpxk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gt2aokrprcl.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gt2hiraoaug.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2zulrtcfn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2ibtwqchq.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gt2ocgulyjl.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2tfrlrhxb.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gt2odmsbamw.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2syqlhfze.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2oktzwawb.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2qdybuomd.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2komggffo.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2csqjxkbv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gt2mhmwrlwj.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gt2jkqiwfpw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2yiyrbzyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2mzsmkkcc.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2raepkxqu.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ejlmudpc.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2vvsdezpv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2bocfknnl.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gt2vcdtzaqi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gt2hpgwrsjr.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gt2gifuwzbu.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gt2mpochchh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2loflsgzt.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2atwcuszm.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2bjqgechf.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2ojlmquww.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2aungsxwj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecljsmcu.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gt2gisykvfo.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awvkrnpm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gt2ayuhptiv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2bxkbvxte.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2gzpeldsc.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2lqqrnmno.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2frvaryyk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2ssiujois.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2nnkwjmaj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2fhowzvfa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ikjeuqrs.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2olmmjjkn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bormtwnz.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2hbbamtzy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwvmaijd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gt2egksmoto.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkfpomty.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgbbvdby.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2rjhryhhl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2rtnumalb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gt2wakgbksj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2lvxwkugd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gt2llkcsluc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2surlwosi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gt2fftxgyhr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2zstxelfi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2qcogzwxu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2vggwggqg.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2dsvcjrun.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2gbgojgjb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2hxujhxbn.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gt2gmkmedym.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgrvzjnu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdecnktu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kexumypo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlxblxxm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjciknbb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2xwexvnqp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gt2thuxldkc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2qteyvkdn.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2nifeozkq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzilcmmf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2yrburnma.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2dyettzxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2nwuuygpo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2ymhhnvjr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvhkeikg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2fjrrfcbf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2rawivhaf.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbisozll.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2fkrkiyrw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2bliyosti.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gogflgxo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fofwjksi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2ccsecsuw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gt2fmfkhoxt.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gt2anaqegxe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tacwzyez.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2gnudarer.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2fnnxagss.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2frxatrnm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2pozyelkb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2blwvmjlg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gt2npkzsnxg.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2ojhldfxf.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2jcmjjuke.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2hxknkbib.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gt2izoomzem.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2mupichyp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gt2vmgnhful.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2zotlufpu.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgxgpude.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gt2iduqeuwg.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gt2xeakclch.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gt2gklmdora.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2hmqngyob.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gt2uqgjvcqx.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2qkgplnhd.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gt2qctfunyd.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2blpvmesj.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2wvmicczx.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2fhdsxlzm.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2xsedxxif.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2vaujokel.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2qpjmtcjj.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2qwwquggz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qstvbvaz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxzqsmyy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2trhubtis.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gt2qosatgdw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2ediyhdzo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gt2fopnmtwt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2xljzhcpy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fefrdfvu.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gt2vpupsuzp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2vohdciad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2dtscttlj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2rbgeeurh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2battqkwm.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2acjchjef.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2qzxgjcnf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2xxgmledc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gt2jasujbkj.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2nyjqgtcg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gt2vvgkoeue.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2wpnxbltb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2crebkamw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fidodgxe.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2sgoutzml.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2cuymwzug.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gt2bdntfbjj.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2rdyohirj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2xatrmpdt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytuuxnse.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gt2hnhtdxxo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2bysfybpk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2ilaavgay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrbffzje.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2ikptozza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuxpcoos.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2vypnjprt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2dqfqxxft.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gt2iweqqisj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjozxpym.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gt2ztonhxte.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gt2rgtttpgm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gt2dybwajut.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gt2ujxjwncq.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2oajvkfrv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwcywubg.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxbzvkia.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouwwqero.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2sogziubh.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gt2qshebulh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gt2vfvyqagu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gt2bagvssit.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2lgfhwuxd.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2lijotvro.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2kmyyqmvc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdxjadpw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gt2ttrykchy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gt2jlrtiixc.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2zcvytfwo.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gt2phlcmvrp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gt2wpylpiaj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgupljum.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdxhaldm.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2duqvaucz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gt2blgydytc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2glwuvpbe.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vimombku.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2sfdnfttz.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gt2inhfdrhx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2dfnroumf.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2atdjrdib.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2jtnofltm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gt2mkorgfns.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gt2pqhpkbhc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2cytkxsyk.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gt2gheiefcq.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2yjrqrhir.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2zxlupsbs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gt2mjeclcfb.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2ojejwcco.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2wxbxnjbo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2hscohvxb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gt2zlnmeekj.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2xjvbbmoi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gt2vvrlrfec.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glayybve.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gt2jyoyivdq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gt2xrcauuvx.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcgzmanc.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2ohkgxadd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gt2cehwdsxr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gt2hftxiofg.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2wrvqoawr.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gt2zrkvbsfc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2hgfnlbix.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ftdwefmh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ghgqysnr.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2phabvlts.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gt2dhqhecjy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gt2dlytvwyr.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkpqzvvr.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2gbogocbv.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gt2tvyoxdst.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2oiczieve.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjhlbmxv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gt2iwwsphfx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gt2arfoiyko.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gt2nhjbfhzd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gt2decbxgko.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygschjsl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gt2ichilurr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gt2niuhqlwf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2igtbrakp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2iipvwvue.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2bokspgrk.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2ywygrefh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gt2ouafuvvp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gt2wcxkylji.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wduazvgg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2bkjovsze.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gt2kmtogxuz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2owwsqels.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2yxrbrdqd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gt2gktgajrs.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fplqjlcl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gt2zebpftdz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2yqbzfsqc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2ftnjghtt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gt2picounwh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkvqtxru.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iintajcy.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjrtpdth.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gt2uwilckrw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2lfpxjdhn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gt2csmnwemz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gt2irqhobnh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2fmeukgop.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2brehfwrm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2ggqfuzih.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2judhjppe.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2jsbmazyf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2tejtjwsp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gt2gtkjvyfq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gt2kuoyhjaz.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2kezgssfo.html


<!-- 参考信息 -->