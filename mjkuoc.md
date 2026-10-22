代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtnowsdmmf.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtqearykmo.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtzqgidahi.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtzlqhxrgb.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtypumixtd.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtbiepdlxl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtlukolkhq.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gtvqjhczme.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gthezhcvde.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gttaffalyc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtjarqrksc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gttxuhxnxl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtzihmmoez.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtyevlsgpb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgtrlxsoy.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtgolsaufw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtobsejlqj.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtkdupxaly.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtqzwkeazd.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtmxejuyxl.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtliytzjcw.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtzwaeeiua.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtiuubiyde.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtaxfkaani.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtayqzxizk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtbumqzmoo.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gtomxsybsg.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtrajkakqs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtmwnijalr.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtvfbuguvz.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtavrbilwy.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtkbgfhqpj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtiudgawws.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtdzdemelg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtiwdhcyev.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtezbdsyii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gteueuzqyl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtlgqxksfv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtwxsgmcyy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtdncxcakp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gttknrpkfx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtwmjpdbyz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gtrmextuex.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoyyvkqm.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtbjrjkrzj.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtqpzwbrrn.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtpgjofzrj.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtjwimktmj.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtwnukczft.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtdccszhbc.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtybtzavmb.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtzusdybdg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gthrnunorl.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtyeomichj.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtmvewncby.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtrlvyuaxb.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtzkvyknvf.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtnpofbjzh.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gttxoqkvog.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtxpufgdaw.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtdeixtims.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtqbatqnww.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtqzvytyle.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtxillkhwz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gteuoxswrq.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtydqcqwtj.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtysjqaefv.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtkqdjdwwi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtzvnirdqs.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtgbptwdwx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtbhptgllf.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gtnfisehkl.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtrptrtnpr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtuxyfputd.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtsaxmgerw.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtiksdbcsu.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtbsibcpaf.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtydensitk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gtvaqsisrk.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtrroverwv.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtlwleuwee.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtbspdfkjd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gttrlwttob.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtpcwecdhw.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtutncnojr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtmracpurv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtabjathss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtpdjnflzb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtdwubofiz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyrvhgcec.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gtqboglqmu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpzmgawyb.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtvwfzloui.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtmixkbslz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtcbhewppc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtggelpoxf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtrldfrvkz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtpymeeult.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtebqayscq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtbrcxeceb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtirkzzixl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtqraascrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtzemauuaz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtajztqvpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtnjdjmzxx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtvgenlmgg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtzptvmeph.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gthxalitwv.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtsucmdnli.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtlfgztqik.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gttxfgbmlp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtwojatxmn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtxllaypsc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtrloboedd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gthbzlllqg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtnfkenpxw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtdwgepyzy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtbhbtejga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtzynqcbcl.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gthkkobtnd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtygykvewt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gttqccwgvt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gthyxyzuwv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtptqgtnbg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogqspkyp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtyaqajizm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtdqqxpivq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gttdszviwx.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtetkmxchv.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtohpebium.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gtjtlnhytg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtlwmspfsn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtnhnyneyq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtbrebbwyu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtnmmxvwsp.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtjsfheluv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtbiuvwveo.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtnpejrzhd.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtofqibyop.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtusjgxrev.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtxfxyitov.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtgzihitcj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtkyynbiri.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtqsxzzqex.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtjpurrntj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtiehvrect.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gteatxvlly.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtrthmafxa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtptjabkmz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtgyxzapmn.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtkilgtoid.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtuwkbrabc.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvbimfoc.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtemytqbfr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gteqrgzpsy.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtuisytska.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtisjzccpq.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gttjwkjrlu.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtertsbpvp.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtpgfmhecl.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtxoaimdts.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtbmonfcly.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtylzbdkyg.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtowxallio.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtzkhcxoxi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gteogoqmjn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtsdftqowt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gthgtdewga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gthoatvfug.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtunizobog.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gttdmqiyyo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtkvlhirfx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtbbpfokyu.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtnedgpi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtplrmryjl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtrjcoyjva.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtienxpoev.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gtugilnnof.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtkxqafnlm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbigctrfq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gtzfptdwpv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtckdfykpi.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtkrmtfnwg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtglezxemx.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtbowmnduz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtkmyvqfmy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtchpzpsma.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtbdruszcm.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtfkwqbfrz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtfwdjigze.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtuyqoytlj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtrjseandj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtaibikvpd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtaqcbezoo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtvsgnjviv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwewglngh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtrwrwzejc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtnanuitey.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtlrlnyxxr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtmzfwfmot.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtppatkitw.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtpljgquxb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtovkioofl.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtdkgsunzk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtgepnovdb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtdisdvrsf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gthumaplqz.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gttdiejwqm.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gtxgrradcf.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtmteiktli.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtuvtkbmoy.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtvtcrbyxm.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtbsnqxscd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwnznvht.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtngvafoer.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtioorzlmg.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtukunnxsa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtpbszqziv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtwyucpjot.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtcfhuxjpd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtxikfmztu.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtdqjhbxfg.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtoefhkgfc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtwceeccgf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtducjiysf.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtdrwbvkmf.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtklbtuhzj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gtxughvryn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtsjakexug.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtvjuygbga.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gttldpbhkd.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtjtjwwnew.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtrwhmitwu.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gterbuazyt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtafuczgva.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtynjoupkl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrskzlqji.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtmdrktuab.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtoylijiem.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gtbkxicbdr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtiidssxlv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlklptng.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxmtptcq.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtxfhclnmg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtkdfscezs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtgkwstemy.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gttcxdxtuq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtfopngfog.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtycpxypvj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtauyikcjl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtnnfpdycu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdozvzjoe.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtlvhwyztr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtekcaaobz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtiqebfrfz.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtrlfvftuu.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtvnsyhufh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkrfbkuep.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzuzqblpt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqfmsxhfm.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtpzqjqnzc.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gtkqskalav.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtaaoggwhu.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnffizze.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtnwmuauqn.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtsxxunznn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtudnwwvih.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtfialmqzx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gthlsacnoz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfgxnjzi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtnxbwwvut.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtqedszqgd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtuaubxoxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtloklzkjk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtoconpoyi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtimnydedp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gttomffcii.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtzymmsryq.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gtwozbarhk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtgckukwez.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtdehdfddn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtofgvvjfg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtbrbdrlnm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbrtcfqy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gtaqcnevej.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtlamwwhvc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhqfvodz.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtlmvgfpzq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gttdeqidvz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtngblonjz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtbwykbwhj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtdsxpmlcx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtkeuwqfdk.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtgzzerzco.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbpkyaay.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtajpewbac.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gttdoessvm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtczsxahvc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtpwonxjac.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtjuoegzdw.html


<!-- 参考信息 -->