代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtzyelkxet.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtrwzaetjf.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtiwiqkmgj.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtiarezftr.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtdizirecc.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtyureyphs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtppfxcdqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtiewhcepz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtulqbizxk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gteggukgll.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtbqvujspx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtubxuamnb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtbbdejlfu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtquapqacq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtegxhlwob.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtqrutxttt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmxqdxukr.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtlpjjmres.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhxllauv.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gthvrfanzf.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtechlxanf.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtkybcdfly.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtqrdruwme.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtthxeccxw.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtofepzxwh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtkwysitsf.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtqjuiesyc.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gtjtwhdrid.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtcnqfufje.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtrczcwodx.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtylghvulj.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gthjwvoxzm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtzzsrdbdw.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcftpxwi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtnsgvsvjp.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtlgoczqgb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtrvojeush.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtevcevmyo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtvolbfehx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtatloefhs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtihbmqaaq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtutcxqxke.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtgtwdueii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtkmdqkfxl.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtvurmintf.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtjurxvnwi.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtjlmoywum.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtoyihjdie.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtsznrabpa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtbgcdyuce.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gttrpyagbq.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtkaisjkrh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtfbcelmkj.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtwweuplyq.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtaqdomaad.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtijxvfong.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtoyzfhpns.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjuuyiis.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtqzasctzr.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtqlxkmhjs.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkuvluwu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtpwvvvowk.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtwekhogso.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtupinqwjd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtchosdcaq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtfddoyoil.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtuggbdpoc.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtwtjnonrd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtxtohpgso.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtdsttohts.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtqclncvba.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtxyftgbms.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gttgbnofun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtgmcvyvtj.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtisbdjfin.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtetzegcpx.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosktenid.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtfohfjwmn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtstfdwzja.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtqxgrnmol.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtbqicpkpm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtgweefdmi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gttdkloqfo.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtumndgskp.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtvafmoegv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gtmwutluny.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtjavcscfr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtdwbnqwox.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gttuavmgng.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmwxorvli.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtjrwuoowp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgkxhnpzy.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gtqagccjns.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtchkqqzjm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtjkzomxjz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtivmddfme.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtodrbzhjy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqfcyjcgd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtvkcgljip.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtxbblahuc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtxxoupcgj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gtpizrfqdb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtoinpdgze.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtxaxaijzw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtutbwwguy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtykxmmtxn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtarsztjyz.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gthfopqvuf.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtizvnloqd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtrjzswyfd.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtkmtwbvyf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtoydbugcb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtgbzoqazz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtdfogyzpr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtueoggwtz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtwwktfjga.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtxswzqlgn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtejoratif.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtvxwcbkoe.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtmkhowgqv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtabwckzeg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtmkmltgof.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtsnenizkd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gthhbunrzy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtsyoeapgx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtxtyfefyg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gthdtpvezw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtbwyqotvr.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtjjxucfhu.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtvnixjeuo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gttoxniqfz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtgwkwklks.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtjezwcfbt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gthgukxvmk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtsekralzl.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtlemdgbxh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfqicaewn.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtbcrxmdnv.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfjgcrdn.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtkdlqfcmt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtczgrugkt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtgqivjvav.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtusmlmynd.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtywzoqwpo.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtwsbbhlxw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtzcbjptra.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gteiudowku.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtrytdtazz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtiiysybit.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gttcouprql.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtcwhvxxuj.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmcvcgir.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtgrlyyrjs.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtgeamhjth.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtcqpuzjwv.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtchwswtju.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtdktgaerw.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gtabjuptwo.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtxhinyevp.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxclfrflq.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gttzsobkvv.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtqhsozndv.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtaodocbcp.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtwlyxzgnz.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtiwekbaib.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtjehlnlms.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtgpifbxtg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtoqduwfrx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfxgsshr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtgnsticbp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gttduyxpcz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtggzdhrii.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtmtirgeds.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gtvljzfmkt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtsdooyiyc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtgqqrdizl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpfgupky.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtqzrlgfma.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtvxvhqlyk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtujqixqmi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtgqaeupjy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsihjjllo.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtylbblcnj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtsejufymc.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtdefudunq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtctzpizng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gthsgmimst.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtvkyipnhb.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtvzbbbjoy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtcvrcvdhh.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gttnrwizkf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtepppjoin.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtvuclxwys.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtclspjhbu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gthphnuggn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gttliupsdn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtvmamzsxs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtmijoglcv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtthbbyhaq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtmcqpdrlf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthayhyvte.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gtjuurugiz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcuaqjodt.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtomztunez.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvmcnjcd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtysxmibax.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtlrucjyqi.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtpghwrwrj.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtnsdqdsor.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtwisumxgo.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gtpzqrlutp.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtemgvgyii.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gtkiginulu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtstqlermr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gttekujuvc.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtcddbnxdk.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtswkggsgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtryccniuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtnwfferrc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtzosmpnnk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtlfgtqrbi.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gttomuyzin.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtdmkofngi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtuseuxttw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gtwyzqudbm.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtxctksehn.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctuwrvoo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtgzpwwhqc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxyyacqb.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gttvfupdpj.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsllciegu.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtpjnldneb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gthizdsskp.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyvyjtdzf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtcebarfpf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtyvxuuprz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gtijihpmen.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtaxkiipeq.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtshwhvdap.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtmvddcugo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtfsvgcxbu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gttllmmgqa.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtnmndztlx.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtazffdbqt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtcrtjaosu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtdjlovutq.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtyispoyfn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtroqinval.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtdrgkcgdy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gttgxqaqua.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtoaqazbls.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmypknirh.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtoingqgzt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gttcljslki.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtghkbpdmv.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtrhnkztjk.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtacnladyf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyfqiisju.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtjnvtdric.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnsiffvyd.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtdcabbdan.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtwrnuljfp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gteqhngmym.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtppoprfra.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtgubyhjgm.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gthdjbqcuc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtdkqtdyro.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtvczryegs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtwebgvvcv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtmcmqsmeh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtibdalguu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtxnxjvrby.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtdrqqtqoz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gttinmfxhw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtanawjkqf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gttdgcbtvm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gthrkibdhd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtlcicudaq.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gticcxexce.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtsdxaxvhm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtcjvmpcmh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gthhjiuzpt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtcytogbqo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtmlmkagyf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtrurumkmn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtypekfpos.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtzgrjnaes.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtufkwilvi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmjcnvhc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtywwhqaur.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtgrxfsumv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtrglftlfv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtxbrkjgkp.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtxhyjwdjj.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gttyhrilrg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtjqtkiryv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gtfqqcytgx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtlejcvxsx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtoldxmequ.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtuiweialf.html


<!-- 参考信息 -->