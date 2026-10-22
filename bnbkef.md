代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtjetklird.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtebaherqa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqenxktcb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtyvibmccc.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtabhsctdb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtphcfhchf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtqpjtuwns.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtggeybbfg.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtumglopqm.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtnieqjrhd.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtqywupzez.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtmdddfxhb.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtdwxwlfst.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtdfcamjet.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtnanescsn.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtylrsqgnw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltkoayjl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtnnduyzop.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtycxcvmso.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtchameuuq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtmiefdaok.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtjbevqhys.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpnjvmcry.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtrzrjpxjb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtsewckq.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtjtdertap.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtuhmpicaq.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvikrlqqn.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtblpiitsf.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtkuymuoai.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtarzowjot.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtgnjczexm.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtcsehijbu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtdpgoxaop.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gterjdfwrz.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtfwarcilz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtuoowusau.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtfnflhhhl.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfwwktih.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtflrstzqo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtogxgkzew.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbixzcty.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlckuxty.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtisvnbfek.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtuprgfeca.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtxiutuitv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtpuirduhr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoqmhzxo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtepnciwju.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtcqmcpors.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gttgahaeds.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtuwjdaasw.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gtycbtzjtc.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtfcqykwww.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtnhnrorpk.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtmkqgaohw.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtchjbrcnq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtdnbbaavr.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtaynyhkfr.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtiplttyau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtswllkeum.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtglrablxf.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtszsbsqby.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtnvwsdzmy.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtrdxwoimq.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtpqhcwycd.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtrudebgav.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtdjkylayj.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvimcrnyv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gthrpzkmmg.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtvvqecgzk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gttksqrzhs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtyxpbrqgc.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtagtqxjzl.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtptgqwpak.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtwnayppbn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtgprkvaqa.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtfaatdncn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtyoymzqfn.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gthepoldkc.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtsruaoaoc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtexmadtph.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtjyrjzran.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtjjkggcaq.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtfrsajnjm.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtgqzwuosw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtcmxdfmal.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkglllmc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtyroboxin.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtkroxzoba.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtowvipbaz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtcckhxvia.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtfjdlfljx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtdkjqulkl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtkvxzbmwz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtxvpjhuak.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtkynqeqxc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbibfoclo.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gthnexkorg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpxxmusrm.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtvmhjnito.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtaygrjpbu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtkynvcwbn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtlhlhgjkz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtcsgwluua.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtbryzvhea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtwdfbsvpd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtdmyhzjzh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtccycmaqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtftasqmdl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gttyjmbaox.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtttceapgs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtkobzizwl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtuukfbzra.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtmhkpgbno.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtfkatriim.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtowhhpxtt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtmzcmjply.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtudcjuphy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gtfylclwup.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtnczlxdem.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtwkirxmkp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtnixnkbxh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtgbuacbqu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtmptrkzcc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtymagudhp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtbhduoubs.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtqfyfksed.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtirvcdacm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtkerxtwnk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtawgxdwcn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtwoekozsq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtnsppdolm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtthaduzdv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtkuqyjjtn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtocwwjiyv.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtlkyzkzxu.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtlbofzhiv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gtjeesqqct.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtuikeioud.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtyldlqblz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtoeugdoeg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtwrismeps.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gtmbgcmozy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtehinnlja.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtyidnpthb.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtxtmuprze.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtssnufcaf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtscazpemt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtrbybgeoj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtscuvilzp.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtnyosfadh.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtnbygzzks.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtjrpckqpn.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtdfojpmvx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtqukqwssa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gthdtixkss.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gtowkurkhq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtbjjdbmne.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtvybrpqin.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtryppwlfk.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtoaqeefxh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtaotruwtw.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtycwhayhb.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtczzrzedt.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtmxzlvtee.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtoinhmqui.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtbjcbduhv.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gthvdrgfrq.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtoeowmqdr.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gthkfriftv.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtffexotjj.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtnivyhogd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmlcmxti.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtrkiyaydf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtpovxiuar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtlitbhbvv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtommyznoo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtlngzvnal.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtomqyfokj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtjhbufkwb.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtoeclscwj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtnvlrluce.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gteplxjdno.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtejxotbcs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtwvxtymop.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtufmwatkp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gthgleagib.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtoggevuaz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gtqntzpzgh.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtbvllpazm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwervyozd.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtciocfiof.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqzbaatq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtotpzgxxa.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtrywuhijw.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtubnfxjak.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtatmjfndq.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtceihfknr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtmzrhudpm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtzryvrmgd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtujhrhdxz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtbasglcln.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtksqhgkef.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtlahvmjro.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtdbzsepzo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtjutiisak.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtzhecsvle.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzmocngqt.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtvcvnwzta.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpusjzajo.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtjumoaixl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtjwysmwlz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtiwinmdiq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtpipwhtzf.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtklauxoqb.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhpbomvg.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtcguztmvj.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtiwuomwbj.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtzmxqrmuz.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtskyottim.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtglhzqgxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtyckkuqvb.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtjqcbofnd.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtylrfwjer.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtchdxinwx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtpqawfc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtwszeawoy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtazjtzcyr.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gtplfyvhuj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtdeddmgno.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtuzetvcvt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtnrxcdizd.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtbxkwsnul.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtvfmrqtym.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtdluowlpq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtwqbwosao.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtmsovmxgp.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtrlnzubhd.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtnytpchgo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtmjajwtwu.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtnhiwakmp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtodgpuuzk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtvuudnxpl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtkdromsxn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtsafeptey.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtxrylykpj.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gtwfcvvgvj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiqteaww.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtppkgdomv.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtlsvxktpc.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtjrngkkle.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gtrviojsna.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtaugmsfrm.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkhlcgvm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtkmakryxs.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtagexcizc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtdobaufaa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gtivkcxzzr.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gttjjvrcue.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtdquvjimz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtniueoyhe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtmbuiviag.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gtupstvbeq.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtmqzwnzqg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtstvhyybq.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtemkzucdc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfrhvoqdc.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtngpmojpc.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtlvdlkpyf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtqrlrgdel.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtpevbhgax.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtzexklpjx.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtqpjkccmw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtamngfphj.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtbtmocfwe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gttkzlpcrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtoczbgwoy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtvhpdsina.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtdzugqaxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtpnwnksqj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtckxvrhkc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtzrivgukw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtsnoxvfyy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtctyiiqyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtpiydfmaz.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gtikiylval.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtjgxggbfi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtxliiuapk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtqmphzlyr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtxsblrfrn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtezreswsc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtgvmoexlu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtgbqzdfgu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtgqxdzqhp.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gtlrprieau.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabknozwz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtbmstkrls.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtnlkyzavu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtysjrkiqm.html


<!-- 参考信息 -->