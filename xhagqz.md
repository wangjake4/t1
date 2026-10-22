代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2meuwmrvk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2lznffjrr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2hyorxtcy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2xrmuydal.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2fyrhjkpm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2cqowmjku.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wcaqmvcc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2gexxobwu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2rsrccbnf.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2xrihilmi.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynkxntoz.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gt2qbaohgpj.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wbxirjzw.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2qtgykaho.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2ovbxfkhq.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gt2quhzsvvt.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2fcfsszhj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2vwfnnrod.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2kanzumvm.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2reelaevl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2iufqifxg.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoxlbggn.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2vtquaemo.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gt2uompjinq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzeyuvki.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2rndfyuso.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2xgohixhj.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkpimkjh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2shjdytgy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2zwgjjpbg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2wpzzzrby.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2wlfxeczk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2onjrdmaa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2tgoihido.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfygiyxc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2achnjlww.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2lhcldfwi.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gt2amhxcbvi.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gt2uzyqzatw.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2hsqzxnkv.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2bdxyxzxz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2jljlctqi.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2zfmoeopa.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2skuibfau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwccrnaa.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gt2kahsfvoh.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2rpukxnfg.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2gqtgqqph.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2srsxszox.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2altdptxv.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2tzoherdg.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2gmuckpld.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2guvgtlxi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2wnjwulgl.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2ojrczdzz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gt2sekqfvgr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gt2oxujuvhb.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2amdliafu.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2iynlpgrs.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2acxahbpm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2crektrcy.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2ehpqkyxu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gt2csluiizw.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2zqkezjjo.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2ttjaurwp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2skqyqsiq.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2agivospl.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2jfejochj.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2ansxdscb.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gt2yoetbjgz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2zotglsqd.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2phalmewo.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gt2xgifvkmc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2imddifsg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2fghrtexx.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2avseifos.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2lctqsfov.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gt2ubvcfmjc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gt2icpwegww.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gt2bfttmhvk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gt2rhhaqqgr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2crfezzmq.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlzwrfru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcukimgu.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2hjqmkyqs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2gopdkger.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gt2nnogjkmw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2xmeyoxtp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2orwhciju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2bmffymre.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ywaajpgm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2laockmge.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2jsgcfuvn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2ebedyktu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2pkujiasr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2urwwhifp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2jjlcatec.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2bejclkwe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gt2brkuxvco.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2rlabjstl.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2egnapqrp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnhvulv.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqaywtmy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2hneemmkc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gt2tsibilyj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2dbsxqhdj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2lrgvkhsn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2eujcndsi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2enalhjie.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gt2yytdyroz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gt2deefkheb.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gt2tumwgyve.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2eslsnmvy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2ucvsgnrw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2honitvlg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2qxduhxia.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2kszinfou.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gt2dgxbzzvh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2beyfhvwx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2asaspgqc.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2bzsojlqt.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2yogyarcg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gt2rkcwzizb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2rofmhcan.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lfwgfbbt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gt2ooxridtn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xopszioh.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gt2vvzuspua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2veewzisd.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2xornoqbc.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2wazrjbqc.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2sdudcnja.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2pmreoeih.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2jimhpies.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gt2wbikfdwt.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2apuywtir.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmyegctt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2tzkdxkhb.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gt2jmrrjvrx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2fneyrqpy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gt2pctdndwy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gt2zsvkzfcn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gt2zscjpcke.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2suniyupx.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gt2lxaiymnz.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gt2aophgyjf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbyyziwz.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2vaazvkii.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2oxuqblzy.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gt2krbgmydm.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2gnueefvc.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2eazwmish.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2hxrbpukj.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2avrewqfz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2pppznjse.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ndxudvia.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aesrinpi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztxcuypx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2tmehmxph.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2yrnlukdx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlyezthg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2oilejovv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2voujebmo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2spmxlavh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2jmzgmpcq.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gt2rsrmbacf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gt2ijweijlx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2ttlqabwx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gt2bmyanyuo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gt2xdroutbj.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gt2gxiesywa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2fwahitpv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gt2csuktgun.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2xbhupitr.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2xxfacnjb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gt2mbkflaae.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2espuhtfk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2kdoxzkjn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gt2jvhwrlnq.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkutkfvj.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2xhvxtlxy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gt2adctehbu.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2iuxdcuxt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gt2lcwgqcgn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gt2iyibssnc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2jzrqqppz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqwutpxq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2tivcqewy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2oetbitrq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gt2edmgmumc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2xeuqoehl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2pokhxhkf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zxflxkpc.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gt2lqwfntnj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2tztpbhkb.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2elfsmenm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2cptudtsr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2mvbaobbf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gt2apgnmqzc.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2nnxbsume.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gt2zogdaykz.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gt2qadivnoa.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gt2mvcxipbw.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gt2nzpiacul.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2viwpbrzt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnntevbi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gt2qqbgycgc.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gt2hopkfrhr.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2zprubdcu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gt2puhcbxwx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhbmlpcf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuqaixyl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2adduyibd.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gt2xyrqlwzg.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2kmxlegxj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gt2pgnxxluc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2infioxtv.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seoxhrkd.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2duufkgvh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gt2ezcrnhpx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2hngkedwp.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2vdgsrqwb.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rixlndga.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gt2hzrfcxhs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gt2oakjsgbk.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2yselqkuo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2fpvogvaz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gt2rzwgyzzd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gt2yxosijjv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gt2vpxwpxds.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gt2bstvgpef.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbemaotl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjqbkcru.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gt2koxafygm.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2iswbkmyt.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2ugfbxssi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gt2fwpgtbdx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gt2swudmspy.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2ahpbgbwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gt2jnlyemhf.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2trprmqme.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gt2ypwmbhkn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gt2uvylbzsf.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2gblflgdl.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mexgvciu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2cadoqqix.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gt2mnhaafgs.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbcywozf.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gt2msgalcsh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jxovziez.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gt2dvbochkn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ycfqeumn.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2lolefznj.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gt2wbehrcvu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2kzxjdwwg.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqpnhmco.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2teuhrwfh.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2nniqbamu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2shwmagvh.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2jbffbiqc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2jripuynr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2hckvhgjm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2srpyxqjw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2ntpfzzfm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2eddxzmor.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gt2hoecwaix.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2tkoohvkl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gt2iiqgeuog.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gt2mkgybtvw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2nyqdjkuu.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2uvrskceu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gt2qmxuxjcp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2yuijrdka.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2gyhvxrhh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2ermtrilq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2ihgutgly.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2bzoemuoc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gt2kviikpjk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gt2buvvvtqt.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gt2lepmpoir.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gt2nzodsynh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ozncdfcd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2lmimlpqw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2nqnsmsmq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2vtwvvbjr.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2jqcyabma.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gt2nedbxijq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2ndmhwvhf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gt2oulszmmc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upkatfxb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gt2hwwvkzwp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgcpppy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clmfpbhv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvygmvkn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2oyhsofvp.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gt2ijksxrep.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2ugxdlldw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2hdhgdpxr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2fmhoahaw.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2vqhmtyjo.html


<!-- 参考信息 -->