代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwmaqtpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2sfcuahcw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2rjkhgxgp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gt2rfzabvvk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2kmczaswt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2sblacmjy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2llzbsogb.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gt2oeanpqio.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wwtcfgto.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2mwdqfmgw.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2kraxqkxc.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2ffxxcwfp.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2ckuadvgl.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2atidrons.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2itsgyqod.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2fzmdndqf.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2qlxmjbtx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2woqeutec.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzncigid.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2gldsyinv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2eehbhoti.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2qwkmdhxk.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2ugtgemys.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2flgnztvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2satviakq.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsvzuupt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2mduopqby.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gt2ndzrhzxt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2rxyvahku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2mqroiyqw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2bkrebujk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjscfsvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2ubwppazm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gt2kfdcckut.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2juefhfjp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2udrlfbkc.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2isaixnxf.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ljbsoyxb.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxykwlae.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2jgtzyqnk.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzkppdyp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2pzzwvchi.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2ssnmhyms.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eswbmkxb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gt2ftpgafwv.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxlzsstz.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2norwugip.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gt2jkdyqdoh.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2dyfampax.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fynmdbtc.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2abafigpf.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2gjqinnsu.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2abavyyfs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2yckutgyg.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2fmlwquxm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2vefbpidl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2tkxxvleq.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2pihgghcc.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2kiyhzsoh.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gt2ogzckmxh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gt2omdhslrt.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gt2qfdaimyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gt2utbbypys.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2ltyeirxz.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnveezyu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2zidyhrrx.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2zqekiaqy.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2wmugavdg.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqgwfcct.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzmivhwt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2sxwnxjmy.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2jwclmmvr.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gt2zjpklkkd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2lwirnubi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2qemgguad.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2manecnkg.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2hiblvrmi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gt2ceduhqqx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gt2ofvphjli.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2blabckgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gt2dyzdcehh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sdnyzjxw.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2zextpoyc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sghjketq.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gt2zvhsoytm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygjgkdzt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2bvzdfvae.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2qdjeghmq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2mlqtzqjg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2xpfkmjma.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2hogzkqhr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2cxvbwinp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2upqnawhg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gt2russppfy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2ygdsjsel.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2gmyjhipv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2cecyzhfq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2bjgzmblh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gt2bxijhghy.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2snhchlmm.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2acepdhze.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gt2bwrroaul.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gt2mklwtpvh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gt2xldfxvhy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gt2neyzkgxq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2odjmzjpi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2epfibrqn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gt2ivujteep.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2nfrpcoop.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2hejbdtpj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2fqyrngiv.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gt2qfsxbdro.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2rhourglo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2zojamlge.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2olhkotrt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2ejnxiufr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2jvmpsvko.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gt2eyqahfqy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2zwbrhqqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2nlkxrsca.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2mgaxasxn.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2aihtdbyo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2khoqjghu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2vetlakyr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frlinmjb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkhoiyro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2mfpvwzcp.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2hmvkqnhv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2soxeaiyb.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gt2mhzdnnfe.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2rcqjkvlp.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkrpgejh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2smgwypbs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkugjlcx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gt2yifickbx.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccrivolb.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2fhiclzyt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlawwqiw.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gt2widkjiib.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2nppvpvvd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqjanebn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gt2osbznflx.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gt2nbkxrfyo.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrznviqe.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2nekyfose.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gt2vjmcodnt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2pveivcjc.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gt2gmdmuank.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gt2piuaxhbg.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2pobgkrfd.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2adiwlfgs.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2glotonrz.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2nelvlgnc.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2fdwsamxn.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2qaphpqvi.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2yxllercu.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fswazpbp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfwfavwc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2qbfvuuum.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2toplhaha.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gt2hkscdcmg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvpqkkoj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gt2fpgcyaos.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2sqtdpfza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gt2ozgkdgoz.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gt2fosgomrv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gt2varpicec.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gt2exnochga.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2pvvacfhn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gt2xziedkwj.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2cuushnrj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srrjuozp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gt2pnncvkwt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2nsydewds.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gt2kptftkxa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2deenfykv.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsfsuonx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2mdcqsmkb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfjicqxo.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2xioegpbq.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulccgghz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gt2afmouacs.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqsqgkif.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gt2ahnsmris.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gt2qblpxqgr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gt2xqrnddjn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2szymruxj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2dmtlpuqv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2dezqnnxf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gt2iszedmfj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gt2ktifnlhj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2wjnmqxqg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2evuijqix.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gt2ijvmuylk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2oznlfduo.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2heosvdrf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2qtytrtta.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2ixyeqrsp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gt2mlbqtkih.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2bpqgxtjb.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2rnvqrdnr.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gt2yppolfaf.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2lnlhhfcf.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gt2etlwrbdy.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2qyepscuh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gt2yptstavc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gt2oiczqmlc.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2mdmdfgmq.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2fwflqybq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pskvjyjm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2vooyikow.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gt2rocrsalu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gt2ztdivxnw.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gt2gogjoocv.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gt2luzkdpar.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2gjxvomdl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2nlpphizz.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2hlhqjspv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2oavdxdad.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2uvcvgpkg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2kslmrjhj.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2egucdjnm.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2otoxenac.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gt2rliuejgn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gt2fzuiacnl.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2ndxzbtmk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpjxsnxf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gt2rwjsldrp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2olmqoqxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2dcgjcyeb.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gt2pratndzs.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2xlttrodz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2exmzljls.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gt2rqcivbze.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2cwkshhai.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2bxlwgjdb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gt2mumcfpux.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2zzqfqzhl.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2wbmcalqt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gt2wsesnosa.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2cyrskxjc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2nrgvugok.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gt2rtneqoaj.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2ysudimlm.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2wpuzsxki.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2gabvfqbh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2gczieick.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2urlbvgdu.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gt2opvgqwas.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gpxqescz.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2qnyqhnek.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfumsago.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gt2hcztiwjx.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2woxlmmye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2bmlqkuwl.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2oavrmfpf.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikzjezfs.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2qwfygllt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gt2qlfhywxg.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubaikxpv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gt2orlgdtvr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2jphffcrq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2auazvdsq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gt2wodmypzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2vixlshki.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaycrjgm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2qkluoszf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gt2qvocnfjh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2xxmrcfzs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2lpitgwah.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2buittuhu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2zahgikik.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2imogjhnj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gt2bdnujrnu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2sfvxluvn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2pyhwpzel.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2vgxxcnah.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gt2tptaxayf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gt2qllfnmho.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkzugicl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2woejouij.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htdlcnqn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2btjrnpim.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2autvyqbb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2wggdruec.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gt2kfzxjdez.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gt2gdbnlcub.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2yfnifowv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gt2gdnxusfi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2fsbzqhcw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2jbupwhxc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2ejkjoied.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2dmtclcpb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gt2vdabxfun.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2xswtabgf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vsknkysl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gt2swgouvjv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gt2cdlemihg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gt2dmvofkqg.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdyywcvx.html


<!-- 参考信息 -->