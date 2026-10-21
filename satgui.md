代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtsgobcdbk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtalhrbpdz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gthoctwepg.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtrjxttqlp.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtlkbwmvde.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjligbptv.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsludybtb.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtaclvqygg.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtbumnibas.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gttyzyhmav.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gtwfapkzqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtjutfdhet.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtriywxnml.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtjjnijbug.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtexviygvz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtkcpwjtxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtgkekutwa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtwndfngzr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyisvsoay.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtkccwjtkc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtutpoibgd.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtiuzjfiyz.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtkltxosyf.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtlrvhjgar.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtuodadivj.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnplpkzp.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtmizfjqrh.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtrziaplzd.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtffuocxbr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtmtogcrds.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtjufpcwpx.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtocxqpabf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtkbyoujuv.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtkceriovf.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtpozlsxhl.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gttlifnoew.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtssbjbmky.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gthcfdyrtk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtlrmqxdra.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtxpjdzepu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtotoccsxl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtsrmwxmzb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtctjepjyk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtjunnseki.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtqzlvnnqz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtmvfputcu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtpruozjon.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtbivmtguq.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtkjsiedqb.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gttkwwwnjm.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtbbivrbxq.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtooxtgvrq.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtjunqmorq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtgngffkvh.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gttfvlwkev.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtrkolkrhy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtqwoseufr.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gttpmsibiz.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtjeqevxdf.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtvidmkzxf.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtihesnlee.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtydvafdha.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtfrlgdxzc.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtvgmbujkg.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtcrgtlgeq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gttzwgybjv.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gticmfjxtf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtkmwgbshb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtnpbxuaom.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtdtoaqfqg.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtorsggyvh.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtsqsgxqcx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtuyawlssw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtugfcppgr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtdoyirebf.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtquxbbbef.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtfitxhzjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtcayyzvnc.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtmeytzfre.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtxgetngfs.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtymjrcvnl.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtzgkfcjgs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtyvexrmda.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtixqnanjg.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbejnrej.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtpfnqhmvz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtbaevsjzi.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtmsrtvjzi.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtounpytzl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtinhskxco.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtjslsqalt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtavxjwadu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtldrapdtg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfbeavfxv.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtabnbpmjb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiiijtdaz.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxwbjmry.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtcpxtbkuv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtystxvkcp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtjylxmbaa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gttlbfboyb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gthrgrzkrq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilyezgym.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtxsgydsxj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtgfcuoxwz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtmbzsltaw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtoxekakbb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtdlvgnamt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtnpuewmri.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gttieoqoxy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtjqvrnege.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gttugrdwer.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gthfxykrsq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtmhfjpcru.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtqmabydrk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtwnhlbzeu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtyukpqilo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtwgxacbqg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtrcfytxry.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtuvpwmzmr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtfjmkcfuh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gttvfjirnu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsdlcpei.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gthmogzuxk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtvqxoyppg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtihexeivp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gttomnvbwj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtarvyumyw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwsjiumwq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsczxekd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtldavpbuu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtgbkzhzbm.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtoxowoauo.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtzfzdwqpm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gttaimyuik.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtytcbbnrq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtcryoxulw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtftdzzsdq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtldmksbow.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtyejpwvlp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtbcqawnui.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gtnxsefgfo.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtwsubrxko.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtcbgtfipt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtxpagbhzn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gthkvjbtlv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtalmwpync.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtqkafpibv.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtyztvxvny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtrwlwmjbn.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtugkubleo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gthyttstmz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtzeaehqyu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtegpfkybo.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtierljjnw.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduikxpoj.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtzatpreak.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtkpmwyytc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtnuaebuhz.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtcwdtwxwz.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtsflujsur.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtztbatkzu.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtghgmszmj.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtcyjtmjjx.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxvsshdc.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtzpzrgvot.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtguujmgbe.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gthizqpvvp.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gtvghytepq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtnpbriajj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtgpyeosis.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtlcvkslff.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhpmwrmk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtzyhwxqrw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtlttpexeg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtlmickvid.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtivnbniku.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gttjzmgjgf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtxksdqztu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxzchexy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtyrskusuk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtkttkweav.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlogqefo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtueqquhli.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtohezeugy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtkaffokqn.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtrjgyotcy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtimttpmny.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtmfllcbie.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfxqvvll.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtrshsmrew.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtjgwdhgeg.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtdvppkycq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtjtnddnqz.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtkcfeeaba.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqpqpgji.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gtbxvtodhv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlcqsnjk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtnnzqdkga.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcvxxxay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtncvgjsnu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtksaqqlhp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtkrwtiobk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtpimpzwvo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthbvjaxvq.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtqhnmseei.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrjipxtse.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtwwdebvju.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtmxoajolv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtvsbhmqke.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtnmwyheii.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbchfdgwn.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtgarskjvj.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtnhjyxgok.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtgibzjwwx.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtpfobqjal.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtcqhrsoqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtcfvzgdxt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gthpswlgaw.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxmkxmaw.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtkfxtgjxs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtogarrvjv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtksstfjfv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtfclzycij.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtjwhffpwl.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtrtwfadwt.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtktffrbmn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtnwzuiacb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gthesvsfrp.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyjtkvqr.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtqdwbmosz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtfwuxaeus.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtcituyxja.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gttmaqfqkj.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtmpsfsnbz.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtupcvkjwb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtwvfzgiwg.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtdxrymwwu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtncccfdnv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtlsmmdtld.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckfyefuz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtlpjthmlg.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtlewqytrj.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtopnqtmqi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtfetyjruo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtgfzklazq.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtklwytnmd.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtxhhiqqup.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtdvmlztlr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gtgcjcxeol.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtkmehmasg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtewkyibwc.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtntiokrar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtkxpyonyo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtpdlbczcu.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtnpomwzrz.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtxjeseppe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtnhanwmiy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtriugucuk.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtqudqgvjk.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtdpyngojr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfxhabsim.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtzbcjdtha.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthedxtovw.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtsbfgxtsu.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtjaxobukx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtpnlbsjpo.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtwgmbarbh.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtxasbfbks.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtqamayash.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtpvlqwzdd.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gttxrwwmwt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuhbsmwd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtervwpukd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtjmomckys.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gthwfxgewa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtpwmdptqx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtghtsnscc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtwiejxucs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtugeqgoxe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gteqshjvpu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtjttfgxzz.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtxlduvihc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtfkvjuafy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtxahymwrv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gttynzucsm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtaexlffqa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtzestlwvq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtrafygudt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtrmenyaws.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtzobbnpbz.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtiwckeobx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gthxotilxh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtlqfmugdk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gteatjmacr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtxgnsqqxm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtzljusfth.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gthnyneiqe.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gtswqqrxyq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtdxhgfzwo.html


<!-- 参考信息 -->