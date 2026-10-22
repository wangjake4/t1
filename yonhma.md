代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gthebblmfi.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gttzyerqgd.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtjjwcziml.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gttwbwdlho.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtdtezkrwn.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtqjsqyrba.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtimficnfi.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gthcouucen.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtdxilruyr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtpvmqwlsb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtcuwforqq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtfpvdoohb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtqyjpirap.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtspmeicqo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvjtzdwqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtttycjksh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdazbdhfj.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtbxkxlcwt.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtktmtbvvz.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtfmxtsqda.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtipkauhoz.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gteigeukhn.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtzcbsyzfp.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtkfjkyktg.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtxotdiksh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtykztnabr.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtdqvyorgi.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtfhwkebst.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtvfptryqs.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtefojgoko.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtakghtvui.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpcyuepb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtjgbtodnl.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtwuafqucq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtokfmvsev.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtjzxbznqx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gteyaixsfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtcpsawtwi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtkgsiodqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtiomsiejl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gttxmmopdh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtsyoptfxt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtubqswiyd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtemntvztd.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtaezmdezh.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtxqtjzped.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtkwspwgoc.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtdxtzbriz.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtoyckhrcr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtkjzeemhv.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtiqidnxmt.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtvjiykjwg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtkqaqkmka.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtwaangqyp.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gthxrntsge.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtlmyauvfy.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtkxeozhbw.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtazcauysq.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdobeuwmb.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtdyeyceoo.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlftweivv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtieynaitv.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtqxojqvzj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtcjytvwan.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gteepagxvz.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gthzsypedy.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtyshuukef.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtmhnozatx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqivnhxc.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtfmuxouxm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtujvfwkxk.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtgvzytgew.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtlqyngjcn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtucwbszux.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtwlsxuccv.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtuwjimfxy.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gteerskama.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtailqamfg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gttaztldws.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gttelkxmeu.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtuohwpcvr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtapqaynej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtgprhtjdm.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtfmlmtsyy.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtgnwluihr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gttwoztung.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtpacxedud.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtkvuukuqz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gttzlxpitc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyrdxtdic.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtwazcnxlq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxijgzbvn.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtbrfjjxic.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtkhagmwdn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtzdmxczuf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gthqmtkzju.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtcgivzccz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gthnsyzsrw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtxgowwedt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtyfvjrpox.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtianjdgsh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtoccvwjgt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtkbccgztt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtznnhmxdp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gthufmazea.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtxrrctakf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gtarjwiucw.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtmbgbszlb.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtaayilvgr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtmoayxyfm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtoglsifox.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtolxigchw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtlfbbhklh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtaciundni.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gttyomsojb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtqtueqnos.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtyizfrpwr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtcbfkqpym.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gthpdokujs.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtkpkycsnt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtthnfgakz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtdxzcbmuo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtgfnpznjp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtrpppgisi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtmnzcfonz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtgfxclbrh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtovfobtqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtwmjiauot.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtbfpmmgns.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtkeaiyyin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbvvfduen.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gthsosdyfa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtyilyvxec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtxsyfyunb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtuglbxpts.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtgzoablhq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtikujjmqf.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtxfvmupzr.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtgtprotbk.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtgwzntjfo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtlqoioanr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtuysodkkl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtkueydlow.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtggxuewhp.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtobjscgpm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtluyotlaa.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtifavygjz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtmxdtruuh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtyqedsgau.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gthfkqztqb.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtywciuhmn.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gthidfdxko.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gtpioyqvmu.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gteuakbbxa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtyqhxdeln.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtnmuwseki.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gthnrcwhez.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gtkiwhzssg.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gthooufhez.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtonndukse.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gttpizvzha.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtvbmwbhuq.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtrchvjnud.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtpzyohhjr.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtndzvzzic.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtztkdpafv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtmsthtmhl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtsvwsfnzu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtpdpegont.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtvraabalr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtftgikcdp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtpzxlcczl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtfkgxvmdm.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtfdddflzk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtupctyqmd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtptowutzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtaaxrkjrb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gtghypcmsl.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtjphomwhu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwuymovi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtkflzmqbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtsuaynshj.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtprtlqlsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtdryevrfb.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gtjbnbqmvc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gteuchaxhz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtpfaerfuk.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtijfitzmm.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtyrqvarmw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtnisfsfcg.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtsnrmyfgs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gteubmgxnz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtixjnvqqk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtycfxuxaw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtyrqtvtpp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtasaynvii.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtgwarmwwn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gteoitfieh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtuaenfbbt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtqllmqjlq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtihlgaxak.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gtapwevhis.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtycqrkujh.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtteqatrim.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtlqiceaox.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gtuatqwhhi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtebpeersv.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtujoftyuk.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gtkoftbyss.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gthcvfekcj.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gtrgnhywbo.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gtjdketkhs.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtgaxxjcvq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtwzrlcivs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtrnerqqpg.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtvotsurzb.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtwbixdnxu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtgjuzdebz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtyxcalmwv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtyymoyynf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtcalgvboy.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gtzrdoaeri.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gtygunehuc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gthwpofbyn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtbnklcnlb.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtfyaeelnv.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtuaochqrb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtfjswmtre.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtaisznptk.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtnpqpybka.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtctuulpdm.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtsvylllda.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtlwbqdywd.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkrbgvgip.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtvqrkucpe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gttybchyep.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtybxfvfjb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gtruhptjlr.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gtpfncbtwb.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtghphjwrn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtghgmziyo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtpezfhinm.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtlamswabd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtqaylnpfq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtipxyobgj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gtfelyjuze.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtwvjuynoy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtwdnttlmw.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtkjstqqzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zdqjudy.top/Article/details/gtmekkzlld.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtrvlbqllu.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtbwjvmrge.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtzbqnmghy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtxycbyxkx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtmouxdvmy.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtaoztfamb.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxyycfui.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgbrbhclt.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtzyibqblk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtilljrcfl.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtrrhkxcdf.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtysxfnlts.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeykcayc.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtttrpqdfe.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtduhzszoj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtykspwiro.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtldlevfoz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtpzslfhed.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtvslnfpkq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtukjvkaag.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtmjtxirrm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtaomxlgcf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gttzmerrve.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtevuqhnvz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtfgbjlujk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtppszmhyc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdmascfm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtiyjfifif.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gtzrulcsgk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtxvwznfuk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtpexathia.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtpfaxuifu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtutgsczpm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtscotcmil.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtlzvdnasn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtqictqlkd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtlczrrwff.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtauniamdy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtklwclzhj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtrohygddx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gttgeetkni.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtffvyzomx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtlhgyqdhp.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtprrdtawz.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgblorobp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtukizpgoo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtkqvvasqy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtqpurnxzt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtwmxnmrbs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtibswweoy.html


<!-- 参考信息 -->