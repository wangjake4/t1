代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gteusvzmga.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvwzzafa.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtaiqqiywf.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtkmdtxxxp.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtxbzrkvif.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtijmskrgk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtbixbrzcj.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtskpygwlq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtbbisgobj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtwvorwkdk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtsiagzyvj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtvcoilnrv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gttdgtrwty.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtokmxstrm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtprjxuguc.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtbripmwop.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrdsmyfnu.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtzymlofik.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gthtwnecph.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtfmmpvogs.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtqrvvscec.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtewxleext.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtfgesfqvi.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtsjghoveh.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtshuznadw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtqidfsosd.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtlcpygpht.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtgpssldsf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtqnnvsybl.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtzirhsjbc.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtejyrruep.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtxnpubewf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtgbqhrxjm.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtrmsnmgyn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtgratftsb.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtuznepafb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtgrzncwyp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gthegjqxli.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gttynboeqg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnknoxwjl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtqbcjfmvh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtudctjcrl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtyeemebtz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtcbruqhzm.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtwgqpcrkw.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtlvymhgxt.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtflurnvoe.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gthixlegbv.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtplbcczeq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtkfqlgsqb.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtwspetqkh.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtqflhvprr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtbcapdrvf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtlmxixbbw.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtooqbdzsq.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtnoawgtgy.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtcbtrqhcx.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzvrenbi.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtiyialkce.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtdqqdbgmk.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtnlbmoery.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtcluftodj.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtlbesvqji.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtbnzzhqop.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtqcaobkwe.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtcketxsdq.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtxgyyhgcz.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtpilustym.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtoposwfus.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtopimsyfx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gtugumckas.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtpbakwfls.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtjyjwmlut.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtvgcyhxuy.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtfapsxlym.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtkowgpyaa.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtreqxppeg.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtcnzfypbm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzwcjffe.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtdjulhumu.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtignpbmry.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtilawbuwj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gttghtfpms.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtoahbktcl.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtctxeibyw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtjjetscon.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gthenqalho.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtnfmjeolq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtgbrtvney.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsuyrisua.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtzbqidimg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtukweyfoj.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtfskyiwer.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtobwkwvwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gteuftcpaz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtpzcqoteq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtwiyiizuo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gthnsnvwux.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeqfdyas.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtdfmfieaj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtzwrddjse.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtrvcnwpbg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbwynbtj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtmqjdesfu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtslplchqs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcjgmmmb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtsrrwehnm.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtofderjvm.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtamvpfiqj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtjdmumywy.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtpzuuhfyv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtcgihydbn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtddaylirl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtgeoakgyo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtqqmtgsyv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtlufhdtrq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtdvntgclm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gthhyylacj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtenfdpjnj.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtotrxiwmf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzddqnbga.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtwsvxuxgm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gthhaytuis.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtnyenydzu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfaydcwj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtgqndrade.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtompgiies.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtwxofvezf.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtzkqhsily.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtevffjjsi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtalwfgpqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtekgaqfbn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtenyfuvxr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtikohgcuc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtlrdxwdte.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtvaneaejy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtriwoouis.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtqetwkmpf.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtyxrqfwbj.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtykepoigr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtvkeklfgy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtroumccgk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtmgylnnao.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtchceaycp.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtzgwodvli.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtnantahhd.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtgdejoosv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gtdzqdwoqd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtcjdapvhf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtncrsdthg.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtvthivuwa.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gtvpihkaay.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtpladoubs.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtwvpjvwrm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtwvfbbscg.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtagqkapvi.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtvqtnpjlo.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsupudlx.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtrtxjvegh.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gttceebkuz.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtgpjpupav.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtpcuixxqh.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtyclfpygf.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtdokzcibk.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gthztxlytn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtomhieglt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtkydervik.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtuyivojll.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtdtwiicgb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtcguztnmv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtesypbvlq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtrljgrmhq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gthdycncfz.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtbbxmphrv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtvyeybgzx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtxndwslmc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtuzokmucd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtovdbhiow.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtxgvnktnk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtgqwlgywv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gtufmhplac.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtdbyzfjhi.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtxkzctpps.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtjpfrsrks.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtohapjlwr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtmyacbmgs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtgwnmkzub.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtpsqwtpix.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulzswucs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtezopxyuf.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtvjzvzolh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtsoqngpqi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtfwegzrmd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gteruwdrfa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtdgsoeibt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gthbhlndao.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtlkizpehc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtiabqqduh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtasplcsoa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtjhughmcr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqmzyfnkt.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoolilxl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbkgcbyxr.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtzgfhnzlw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtcqtzjwvy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtvxxctzrx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtqndsqoox.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtbxdikmyh.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtkdpthrpo.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtselbxvaa.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtywtvqcya.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtduahfsqv.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtthiigugy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtxfwxuahw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtuevketrq.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtwzocrtcm.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtmgmtnsqr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtflvzpocw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtrhjdhfgt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtsbjnmoin.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gttjdqujrj.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtnfnydfed.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtmjmthrna.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtzaxrsaoz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtibrklclj.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtoycahnys.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtcpwthqad.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtbrkunlod.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtiqxkuvyp.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtrbchcewb.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtucpzodaa.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtovysomwa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtgyohllrl.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtlqvxwaaq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtpgdzrydj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdognewj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gteoeqtvec.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtggokcwla.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtxiadohay.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtxmvztelt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtdohlrwcl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtlofkqfog.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtquyuayam.html

TS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtfjcoqjrz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtdnryopgm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtwppzemdd.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtnpposfzk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtyihtvvyi.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtvsagxxce.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zdqjudy.top/Article/details/gtnanrtyrk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtbderpdya.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtxrjvwcrg.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtrequbuqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtwehrzgak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtstfglntw.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtievumeha.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtmtzzfdqv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnwpqoxvz.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtfwwgftak.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsemrlntj.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtwutecvpo.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtisvvgkxj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtpfdrqghi.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtplkjgvhz.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtwomyttow.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtddyohurq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtkedboryf.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtngdvcjbe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtxedthtyg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtmikvagge.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtwbwsixfb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtxgoyfugt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtssihanlt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtvqzscrmg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtstwnzjtm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtmjngdcav.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtksqscjxo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtulosnwky.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gtyendethj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtprealief.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtduitmqhx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtrxhcrtuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gthuspytvk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtgodxnzga.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtttgqhqny.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtxmkxesbo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtqeutsexg.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtlmmjablz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtkmapatpp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtiugweznz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtoervyiph.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtrmbhqeks.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtflktwcwj.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtvglolivo.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtkdsbmtes.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtqnqfkdbv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gtemchmclj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gtvxmqdihn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtikhcgmta.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtlvkcexrn.html


<!-- 参考信息 -->