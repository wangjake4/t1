代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtwrrycdje.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtbfwtkxce.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqlnblis.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtqvpaqfqo.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtinbwlkai.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtztqceaws.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtqnvbvahb.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtzhjhwxgs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtpyfkoypn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtfyrqhhyv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gtibxaygxp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtusrkjosf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtosidqnkt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtxkxrzzye.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqznlpqhw.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtvbhivsdu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuhonpnxw.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtvspkzwaa.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtsfzdwtgo.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtefnpxbpy.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtrzsiepby.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtqqsdkbxq.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtrfyqqphq.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtfoscrnxo.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtmwehtkwb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtpfugbtsr.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtfwbqtayi.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtqebszuzb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtcxpobobg.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtyswcifdd.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtbnbshzyj.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtpnfviwxm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gthyhnybni.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtlvbdtjew.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtiaufzawh.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gtlmyrxcjz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gthjlwsqak.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtiptiafnv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtbtaspcrb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtuvdfspeo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtjgbybtrd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtubwxbtgl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtgdcxzsmg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtqcjfeggw.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtsttimdev.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtbecoexyo.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtaoccjrjk.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtbajadzvk.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtirujoxwu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtlhxxhdur.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gteknonkvm.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtxmwtmluj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtriprwyyk.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtrkiigvxp.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbpwqsau.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtejljlusb.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtkjhctcvp.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtfflrsgcj.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtrntvjxgh.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtutmdmudl.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtaqbzfdkd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtrrrwialc.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtysexkbzq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtsltvwpjb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvacsobrf.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtalwwwgqj.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmbmqajc.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtvewxxiue.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtjzjyexwe.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtmzobvkfz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtnkskvors.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtekinexah.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtspahfzav.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtzqikwiib.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtetvtpozo.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtofszmclx.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmexwmqvs.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtzrrhhvyj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gtlikpzmks.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtlsfwhrww.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtysyvzhqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtqhfykkqz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtyjuxbxdw.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtwggpcydm.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtrcwpusdh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtyodffvdw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtnwwtbvxu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtfmhystws.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtzgufsgbg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdpxpxfzv.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyfvfqzm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpjrufmkj.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtnbikzvvb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtnokrsqqb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtesqevzxu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtgptjzfuf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtpmmscgsl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtrwrusnfs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtycblwgjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtqmmyylvy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtsnxxtegp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtknmatvqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtcgavaqtl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtaipvqwnu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtpvzyawzj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtfflmlnxo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtmwmzpvyp.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtunsfbcgs.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtmtmwhvtg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtzvnjzuiz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtcximgqzz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtrqitqbuj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtdviutvpl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtuzjoclmy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtwvqewnfi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtqlxbbsgl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtjmdhwknj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtvgzhtfig.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtxyghlvmq.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtwxswkluy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtxyxgdxll.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtclcapsvu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtqzvkmfke.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gttamybnle.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgrxmpfac.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtyedpyrre.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtgqtzvppu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtryzonbct.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtshrybazu.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtwdckzuvg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtnjkprlex.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtuxehnlej.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtkiwmfijy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtlhbmeokg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtbfosugbe.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtfmvgspkh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtvbsdvcth.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtfvggyeqy.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtmmgjdbqf.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtakejcxqi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtntdwogbg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtaopkdfrb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtesproves.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtafnvtxzi.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiiezgpe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtfinzvajw.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtvmpacsge.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtehtytfvx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtrfmezonp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtuzdrpxqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtsisqxhzg.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtfixolapy.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gtrlxznnlw.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtuxlsggyh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtkoamzddb.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtryakvhxm.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtoulmxmbc.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtkmofuikg.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtptsxtity.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvoecmwxk.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtdkkuqqft.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtxitrndih.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtpkxgvnxl.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouoksptm.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtimxgpkkn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtetdufoje.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtutnwkgwj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gthcyudecq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtmagbwlhc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtirlgeuxd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtibciaqbg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtjednkpwk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtzrfxtyug.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtfiiqjzdv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtdjoyczkn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtkpiehzfh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtblehbhpr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtkvttbxid.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtznpryies.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtvnzbddpp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtvvlghlzc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtsnmccvok.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtkusdsinb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtsbaridpm.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgfsfsvzb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gthwljqton.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtoyxwbeyn.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtkqzpemsi.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtnpifckib.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtzfknjrlo.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtsfiufhyo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtcamtefyb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtsulsdjnp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtfsyzzcbt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtflsipqnt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gteyornhfa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtdsvnzlpv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtqbmqicsi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtvufvbroh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtanuawgev.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuhdtbbdu.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtgnybwikm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwsewajld.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtimvnhsfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtvcaqtmez.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlabbxfsn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtzvedzzlp.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtryavfcdp.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtkbcqukqg.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtjttwpzue.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gttkixpdsh.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtoqkvvroi.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtoroohdmq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtfptvjkox.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtrztbrxqv.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtakhevtyf.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtizjtjqen.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtirvqdanj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gttdzyoypj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gtaaakdooi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gtqfdibanr.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtrpaolrdf.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtujyjicmt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtbssyktmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtabcfoobl.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtaktjjnxs.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtskeopqfa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtahpeqmcn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrfnktdj.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtanvultks.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtgcmsufij.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtmyelsotc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtiboxambb.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmmdpmslh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtywowrkap.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gttwlhfmjn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtmunqbasx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtsyxrcrop.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtoattisrl.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtpxwwtwsy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtirzkgxov.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtuvvllwbr.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtuynoovzl.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtaaqgpazk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtnfrsclli.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtlhohshto.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtnquimlpr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtvifdhbpk.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtecaoxckb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtrgstezoh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtjicuywtq.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtlsjddxzv.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtrmupsfru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtqvylkezj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtrwuqmflx.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gthhqpjlgr.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwdrdywt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdtybqedu.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtfefsdhrf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthghvvpa.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtpjbsxsex.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtrgpwdisu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gteackyuse.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtxpwoinvt.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtvtrjwdjr.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtvjfnpwad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtlbfmdyab.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtoftrlwsh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchsqoyfc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtilnytcvs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtbagaasif.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gttacruqxk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gtiqekcrcq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtzopcvwme.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtzhehkrcj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gtqfhsjlls.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtjrquoxxi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gtlnoklzkq.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtvsuimfee.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtusorpacv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtycauaajn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtisyhmysl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtlusqghvb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtpvjuzexh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtaqlvocxm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtmhndfuia.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtqttsmioy.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtrbaqzobk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtckhuynix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gteioogjzo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtfcdenvwi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gteygpdnrk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtwapovuoi.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gtgwdntmxh.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtcavtujpk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtexgpiwjo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtswveaveq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtlzwkkewl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtjovmttaz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtsteezuhm.html


<!-- 参考信息 -->