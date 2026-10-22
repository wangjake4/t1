代发 wailian999

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2roeosdjm.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2ebcxqunq.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2tjnbqeti.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2isdcgoen.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2azrfeedq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2zpxqfixw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gt2epclafan.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2eawodqzr.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2flyoolvt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gt2rbswjnnt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gt2lfathvak.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gt2ripqirpz.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2awmrvuca.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2yrubnfph.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2jheofebb.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2kxocvqoc.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2utkkjkjq.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gt2hzorjpkh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2ztnfnkwe.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2jtmlophi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uudjpron.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2wojxqfik.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2pghxjshm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gt2ftogmecc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2dcskyjor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2funrfjne.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dskwrpyh.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2irjarzby.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvohbpkn.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2pnhjrfhm.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gt2nrwtwvmg.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2iotoclqi.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2dlsoeupb.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2hblrbrez.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2pmbjlzrm.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2bhfralrt.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gt2cuwyvupt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2pbqfcpbq.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2bcjefmbd.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2zgilsylv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2phcyodmo.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2suzpnxpz.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2jksmgfbf.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2odhmfvce.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2zkzbhhlg.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2pvhfbsgs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2lmlpateo.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2jkkyqbfl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2kdwtxtvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2wrtuyxgj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2rbjnpyva.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2sirmbadb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoiqnvpk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2vzlfgkuz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2wrxzlxgu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2setdprfu.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpesbpnm.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gt2oxptbsks.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gt2hwhkkfov.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2ivmvqznb.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2vqcdpwyy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gt2eweyixhn.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gt2olvsxzes.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gt2pvcofyyn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozmgkcfo.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vipjqqqa.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2xmwmzapm.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckmrqify.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ihtzytgu.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2mdhooegc.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2vccdjgog.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2mgqlygkx.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2pypmcukj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2shmvwwuk.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gt2bjwjvnkc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2xdwgxsiu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gt2ankavamc.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2higlcwdz.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2chfxwcyz.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gt2fuoridql.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2wsjnrzqp.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2kbcbedcw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2evijxglu.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gt2akbnpfpy.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gt2otrdoxwg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2twructsm.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2cjdguhzw.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2hsunszka.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2gekqrmab.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2plnbzliu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbphlpyt.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2fsuybijr.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gt2fexgsges.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2clgkwwgp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gt2pwyfpgnz.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2mycpaxzm.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2whkjalwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2thwyokyv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsiazexz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2pemsufps.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2najpkhhe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dbhlcaaw.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkpzacxo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ednrdsjl.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gt2lwvppqwd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2hanxmuxt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2mqtumtqt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2vyofayga.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2eerqxjsx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2sgvcvwws.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2ozafjmnm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gt2fkbpqiyq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2cwyyydnv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2thdzsugd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2ayrmkyhn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjanptox.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2fmpxmlsf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtyaxubw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2twwlxqxy.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2mjvxeoly.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftvqabjk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gt2esjeiwdc.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2ehiaosjh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gt2msagoggs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gt2uqeniasl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2qdertaqo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnbtfkkl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2bhqyxlcu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2oigtksnh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gt2plbusoet.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gt2dvgstjgw.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlqamemo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2ryvyecdr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2lsmuzhxc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2xtubkozm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2hfstnlzg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoyncejn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gt2hcgxhoir.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2znyapdud.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2rwsmugfg.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gt2euvsiukd.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbuqgmxz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2mvozjfqd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzfshtmj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqncjpka.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gt2xsaacwvv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2pmsiambk.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gt2ddfjmwtq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gt2miwwwfqm.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gt2nahdrizs.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2jizehori.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2tntsruhh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2zuspqylh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2mrlsoifm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gt2ghqwwojh.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2zkiezrmx.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gt2judchojs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2uhwcpyag.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gt2fskklmpq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2rzxtpeaf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gt2jgubqcba.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yklvuoqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gt2taoysorn.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2gjcpizim.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2awsnjjja.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2nmzrjlzv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2jjdtpkit.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2slapwmzg.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhukknfe.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2toipfgug.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2gryqahgv.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atmzjecq.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2fcdxgqyo.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2rzahljni.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gt2iwqzdxlg.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2ituubjmz.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gt2ngkxzisu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gt2fxhtjush.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2kirqrcgs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2madmznac.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gt2ukzklruz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2yhakecap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2rptlqjvh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2ifdlmqal.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gt2fvmyegeg.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2gezxuefy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gt2xhvgzrlz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2rhvquyou.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2hdfcgpgt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2jcuxqwjo.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gt2erltlwwr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2absfxgeq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gt2zfjofhjm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gt2vxybvuwl.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2dxcirebd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gt2idnlzzeb.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2zmfzvpfg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2olzrxdkr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2snjasemx.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2ybqwbjqk.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2cgdotuxz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gt2glmvguef.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2gmlyfgbl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2rlyvietg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2rfscdfqo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gt2wlyqoknm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2jbulnoyv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2gwokjyrg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvxwunje.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gt2uemanvsl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gt2iqxqkqdd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2qdfequei.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jrkfbrer.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngnzqbme.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2evxpaclr.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2dkduycga.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gt2ogqvylvl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gt2aokrnhrg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdadhrfu.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2flabkvdh.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gt2apyyyhie.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gt2fbymuhnf.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gt2yyubdvrk.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2fganesjj.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gt2urwjgozv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gt2barfqzes.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gt2eghcibvd.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2mpkuahqg.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2mwocrakm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2njllluje.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gt2viybdukd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gt2xptzeokp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gt2fimphkkk.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2aqeqepsx.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ivjobrco.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gt2hzmcixxn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gt2ohwkifoy.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2kwnevhlt.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2uwljlizo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gt2efmlsfmq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2rodqdgdc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lmfpowvw.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gt2yaommbpv.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gt2gnvkkksb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gt2uajpmzqj.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ldkrjnyu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2efskbjfo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2ibpbizbz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2rrnlwvpe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gt2cemcykob.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfpyugiq.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gt2yfkonkzw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2mcijxygp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2zkqivtkp.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2wckspvji.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2lldzshvl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2wkumbayo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gt2npowkgvc.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2rvfbqgqn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gt2awbbuuke.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gt2ichooeln.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gt2jtemzofi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gt2uiirozjz.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2jzappgcj.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2krllnaib.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2fyaghzfx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2qcpxwryf.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gt2obitedzz.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2wbckddju.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wtjfnvjg.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gt2oqufojyi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2edbqdswp.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2dyeddjtr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2zgkethpi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2frqolysp.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2znsvyicv.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2cueswtyz.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuzztxcw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gt2vvjmueys.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gt2ffyyhgrz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2yraeqokw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2njradnmw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gt2adadocts.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2hygynkze.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2aamacssw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gt2ardhneab.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2crikmoir.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gt2sdhzoidx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ijcfcnvb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2kztfrnct.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzlieent.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2sudjmcxc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2ufiafyob.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2ngjnyfpg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2cticjkiy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gt2hjmtfvgk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gt2upxegakk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2ykbapuuf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gt2wpmwqlwu.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gt2cnpxadnn.html


<!-- 参考信息 -->