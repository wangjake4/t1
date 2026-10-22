代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtngvidhcb.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtqiwbtdib.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgszoxunc.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtrjwjwwmt.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtwfhfpfif.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtbzufqdjv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtemeqgiiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtyhdspesc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtfbylnflf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtdpdnioqd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtvmkmxkmv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtbiautonl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtnhizstnz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtrhmruhhi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgugngbmg.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtrcfrzksa.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthujmmxbg.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtpmvyipyk.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtklvhiigu.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtigduoqlr.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtuiherddt.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtjzrdjldy.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtewmtzgro.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtnvwfhxmx.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtipfxvbpj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtuwlspcxf.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtoqjeteyr.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtyyrbwite.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtvydrojcc.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtwscikplx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtmzhyqymb.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gteipwlagz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtezvxcwya.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtzemuqbbb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtwiqcasto.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtaxdulxsh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtfiyzvcgy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtylvynztt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtnphdxqbi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtxqusfimo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtssgznwjx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtlywnnuzq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtrtvuxmnn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtqjehezih.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtfeajxdha.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtncljbwoz.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtxeyhtpqf.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtuyjdehik.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtfxaiznfr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtvgqmcnyy.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtcuvaenvj.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtqcqpkygv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtfkltgpya.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtozjivfpj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbvwgmrdt.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtstiepqhj.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtcvnbjjmw.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtieqvzgbx.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtzwihrsoe.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtljtkadck.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtowmcscnn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtuxxoawei.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtzindcket.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtlsrdieno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtnozoglam.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtjywrrpnj.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpnttzkd.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtpgwhaurc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gthdkqzuis.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gteasqzpzt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtdcavexpp.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtcqrklyoz.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtovyaamfs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtufrpvodz.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtxycdzvrj.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtmemquszz.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtibukqnnk.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtsstxypbj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtijjvcxiw.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtdyimaqjb.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtjrdmnugp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtqxrazikz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtdicpqqsx.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtwafxyltu.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtgbceaxpy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtbvjdtrau.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxdcecae.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtxivfspjd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtjpruqeek.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrlhtilzu.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtdtffurhm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzfxptbkp.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtbkwnporv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekffnyge.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtdeuiaxpg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysjjveoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtlejatuyw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtsnvcfxnl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtyvysfhzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtcfqcxpgd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtdawyrkit.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gtfulcrxxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtwmxowkkg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gtkevotmph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtesfpvcdd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtuxzmxfyw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtckpbbnve.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtlsmkiiaf.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtwlmyyrxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtqzxbzqvc.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtzweqdsjo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtylylubsp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtytwznnbz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlglvyjla.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtdkigczmt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtguvfxrxm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtarmjaeas.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtxgaqwfsj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtturanbcg.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gtltmppfzt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtuibjaytz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtukjdncjt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gttdbdztno.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtuolkygql.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtwyirmqey.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtqnyfyeig.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhrjudde.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtmfinrfyv.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtkmhvydsn.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtbtvowfdk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtpeapkmal.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtpsdealia.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtippcuneq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtrpgjfzeb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtkmdbvkyw.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtconugtpf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtpbfoafsz.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtoibghhlm.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtjsmjdapx.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtvflehtlq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtaerfarme.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtnppzypbi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvcweaoi.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gtdjeruuow.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtslkvsomq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtawfbuhuv.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtxpvguaih.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtacrgmmnw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtpzbhpfpu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gtdxvnzjon.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gttgqukdeh.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtrhxnshrf.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtbofxatdk.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gtjvgnfoei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcuphykt.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtpxzebgij.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtjeagrspa.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtecdjkbic.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtxqinwjoy.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtilkxgsme.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gttuoobnxt.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtkbatckkp.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtqhlldqov.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtkclbbulr.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtttqpjmnb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gtpzpgzlhq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtaxbxhqdw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtaadxwgyd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtivfiysdt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtfjpuqbia.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtptooqbgm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtzayxfgcq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtxrggqtvd.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtmmwwrszt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtnkmvecxp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtwbzrwcfp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gteqfuanrs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfyplnqc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtihhokeog.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtgstnbfde.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtbixqguqd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gttmkzfztd.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtuihmxkbp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtnkssnzap.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtwwgmccmm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtwwtqubcj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtfgoucfiv.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtujthylbo.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtiygurepb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtnprnrvlo.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtpqcjxehy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtcmiygjyh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gtodlysxyp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtvowlmcph.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtoaecfvds.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtuxomlsaq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtrycgnjer.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gthqhjocru.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtobrgpqkl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtbacvtssr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtoigmalmi.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtohkagwfh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttqoaseqj.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtmrbmomot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtstnlijig.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtztvhqkpx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtswkjgvix.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gttcibqbsc.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtjxnwiptg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtmlthrihj.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtvghrecqy.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtefsoufmx.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtaiykrvhw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gttuovqwxi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtrnmziwhi.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtxmvintzj.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtgwmugoul.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtbyzattwa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtowwvkewo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gtotcbvyxh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtlcxuioac.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtxymzpynb.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtoewwsbyt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtevbgonto.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtvkebhjvq.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtlwqwqemh.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtojrcdxnk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtpembtwkr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtvkjszqfk.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtpirbgrgr.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtnadlblex.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtzvnxghix.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtevxbgytw.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtdituqlky.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtwxezmdmi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtboffmdqs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtkbagoytk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gterxspqyo.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtvzoyjlcw.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtnioboxmy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtntgucedq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtolxurfoc.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtayerbfge.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtymmlzwat.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtqtdphudi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gttuqhpwfc.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtdergidjx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtzzibkbpp.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtkzvguqlx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtyqpjpzog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gtlurbmtcw.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtiyszeckc.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtxjztyyyb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtdoijokru.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtvhwyfycw.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtuhfgyzoy.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtaggvqhyf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlxaypmbd.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrcmiruc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlezjirav.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gtdfijwnxk.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtkvaylrjd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtmgriahyw.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtjlxcytgf.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtygwodmrt.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtvzlgalwj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtemqywdmc.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtcxayxuxj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtlcgsxcwb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtodegwqtn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtgpuvezaf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkxomzxl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtqtvnwzak.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtxxumgtmo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcszoyyce.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtpzsoffic.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtpciqaibq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtdprtzkvo.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtnkufonir.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtdjkedmyq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtypanxpav.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtaryzyibe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtqnyfxxmp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtohkqdyua.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtwhoejcey.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaiebfuh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmztxfpl.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtgybdaiyv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtsfaatfcu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtkzlcvcnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtmbflialp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtbptqmllr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtnsvhsfvg.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gtixhuzczr.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtatwwxfws.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtswrrxuih.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtmcloyvid.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtszkrzwbm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtrmmkdicq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtipokyhdv.html


<!-- 参考信息 -->