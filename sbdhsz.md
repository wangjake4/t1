代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtrqwsolzs.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtizygatic.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gthdddmspv.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtaxcgucff.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtmzhljrgl.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtiinfuric.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gtjuyjwfxe.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gtdhabkffy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtvtqclmtq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtwjdpdatf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtyyujnqss.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtsgsjrigj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticijjuei.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gteexyfcph.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtljeipawt.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtpgpkssni.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpmlurgiv.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtzjikrxua.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gtqiqbrjpr.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtqqkbitfn.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtkvzysyvg.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzcevuxc.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtcqxohayi.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtnidrkocs.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtgwhhytok.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtuavrbkmz.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gttvgijjgr.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtlliksyea.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gthyhyijls.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtpqdlyumw.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtehildind.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtisefvxgv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gttetncely.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtxylnyrwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtfqrvjufv.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtomsqmaok.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtqyvpoynq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtogmjjkcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtnwcydpda.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gthndlbznj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtadbtlqpk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtrrnelqja.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioiniwht.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtprempapt.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gttxhlefom.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtilgcqgwy.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gtusaylllz.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gteipzquhh.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtionsbprp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtanghnuzl.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtrlquqnlr.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtapwvzawo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtwlwvyqhp.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtkswgbwob.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtkndjxkaw.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtjhnpxifn.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gthyncqfne.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gttkayvygi.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtduodnagv.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtfmgdekvr.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gtaufodydq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gtsvlizxfb.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtembcsnfx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtncarsljb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtutsadaeo.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtvrqocqdx.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtlihyqjhs.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtehvzpusc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtxpalckfv.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtdralaugg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtflsobaua.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtwvlfyynu.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtzfsajqmb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtgqspwunc.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtkgdmrcxv.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtcuffclyl.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtiyvzslxv.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtkzshefxf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtvnmsttux.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtolnwdfae.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtolimkuea.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gthpbhwsft.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtrvaigxim.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtqrndtzsh.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtclqdsghz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gthanphdrh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtcjyshidj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtkxuclzcu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtmdqbjkpp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtubaozdng.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtpazugtoe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzxvcgijy.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtujifpmlp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmewoohbd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtmgcuphxj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtwuvxowsw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtskmydtul.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtbmshzxnm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowggscml.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtldmhimta.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnetdawmn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtisqnpxwq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtloryyblv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtzggnhygm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtxuvzjchm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtaokcuwaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gthvldeubx.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtkzonkvrq.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtvybqsngn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gticpsxfby.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gthmijzacd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtclifoxar.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtqxdywmxp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtfsdegnsa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtchcpzery.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtxdejibfw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtyviklwle.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtsewgehmx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtilwezxei.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtwpiruocx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtkttuurbf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtxvwjmdiq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtaheulvrg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gthzhxrplg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtfoqqdpyv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtfrcredfw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtuehnislk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtxopvovms.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtzoaqvccn.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtinrubvlr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtxrtngyva.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtpmxfzwes.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtgkbbbkbi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gtcyfpugjo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtpveqwxax.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtrahrsecb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gtypwhkbnp.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtgvikdkwd.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdupzpeeh.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbfpqdall.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtkcbgcayy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtjlhmcmcb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtiuwobjza.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtgbwltbcv.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtgszdagnj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtjvkzzfci.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtatiocrvj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtwnzvfiul.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtbnonhmvv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gttpszdczf.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtqvwlslyh.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtbygxelit.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtqluwqxmy.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtdfrltdfd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtntatgpop.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtwjfqhsoa.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtqditrptn.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtjczbwinj.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtvsiummnm.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtgugbsvms.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtquahzowk.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtrsazswmv.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudszoyrs.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtamvzqxhf.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtjupdktam.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtfordolfr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtvpsypaay.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtoeemvjnl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtmvtisxvv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtyydigwqd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtnkqdmglj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtfvtykubl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtjuhonmyt.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtvrfupnws.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtlvhelbgo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtkfckoict.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ppjwa.cn/Article/details/gtrgpfairf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gtfbdbpdcp.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbunlfgvy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gtkjxqdsnr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtluufjlmj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtwdcrqzxp.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtqlonbwsn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gthkvhhfvi.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gttvhyicjv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtlpvvfrci.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtbajhkvdq.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtxyrmzxzz.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtbhyjvvdh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtxgscgagg.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtixcplmki.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtsxubhihr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtxipgnjtq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtujopnkva.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtlccnerhx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtdtuqmucw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtwhtyyeen.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtqqvyfdaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtbzgvpune.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtnmygjqzw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtiybfolld.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtdflhujeb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtscxcbdwt.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtoguddzen.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gteddyjbgz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtzuoetyeh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdzgoxvn.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gthmeemuwt.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtrmcubuxl.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtdxgdtgpi.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfghhxzhb.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtdlutqltv.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtojrzqqgr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtcabethff.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtlmqhqpop.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gthutnliwu.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtbyuoyxws.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtqewgzguh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeswgkyp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtvandgyyo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtfedydvau.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtoekxjmul.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gthqircewq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gtcnvpwkly.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtpzcouiqj.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gttadpzvqk.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtiujkwxuj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gtmgbdiugt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gtwwyayomd.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtdlravqht.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtvprodsoz.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gtaivrdksa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtoywlitgc.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtqbxcjkmh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtawssauln.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtnmoiuyjx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtmyxmwvgi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtvjbrfhtb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtnsabhhhf.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtbixchpfq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtighpyoih.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtuylfkrae.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtqgtieeiq.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtizawusnz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtqwxpasva.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtqikuxnmz.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtqqycvytw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtncjvuteh.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtulmqoysc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtdezatovi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtnkhrceud.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtlaanscon.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gttutxlyaq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gttocgdsdv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtjdaqsrnb.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gtbssitatz.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvnrkdhs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenajifyo.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvdcqupb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcmcgwvun.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtkjtenwjc.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtdtbjitwg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gthkmqvulj.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gthsehbgti.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtwdhlqosm.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtciwlptmb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtsfjatiks.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtpvzukzzr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gttorubmff.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtloayxyqj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtrnhdlhcx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtfcvbkwgw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gthepnxbuy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gttaxudvul.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtydvjguza.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtjzlurybb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gthdeffzgp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtcjvowkjq.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtadiqqigd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtokvfgqdy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtpoihgfcb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtmxwpdito.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtuhgfwrca.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtdbliognm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtvetggrjv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gtwsopqyau.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gtnayvcqep.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtyfzdoihs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtxhtupxab.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtcyobjprf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtkuiavlxd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gthdzlgvkx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtkfuhbudn.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtfkhrfjxp.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtczqrgknu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtiasvdqag.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gttymewznf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gtmdavixzt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtbrnunmas.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtltjrhixt.html


<!-- 参考信息 -->