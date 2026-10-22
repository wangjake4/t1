代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2tmzbashb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2iycgvgpn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjnoiolc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxzrssmk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2tagbobdn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2kncobkva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2bttftqmi.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2xzuydigv.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2ybywxwlp.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2prpvyipm.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2hldqafzc.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gt2dfezwamd.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2wbqcldpv.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gt2vgnqtwne.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gt2qevkdhso.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gt2nzylxuak.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2ifddmcmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2gcdipmtg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2teagukor.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2qmlngydn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2djlqpqgd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2bampkrhe.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tkjnpzmu.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gt2pjmelzek.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qqnfxgzd.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2ewpxupre.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csmhyiam.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2fggbbgvg.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkarqkpq.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2wjpcyhxk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpuzxzx.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gt2cikrqepo.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2uhhqmbjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2rhqblnft.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2tjxaklzb.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2qvjpzvjn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2fsmgpyup.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2pxvfacgt.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2vkiaeaig.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2cbupuihn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2qfzhclbs.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iipgadfw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2qtmozcxi.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmadlfqg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gt2ehbaexnk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2jrywyziu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhgrgtdq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2hlkcdjnc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2vibtslzk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gt2gcqxfsfs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2mtzpjzut.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gt2vesephbd.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2ubkrapap.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2memiiehk.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gt2wahdoqhk.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2ehtgcjed.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2gbogpwup.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2mewgwcmn.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2tofazxbm.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2poxwchcp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2nfgafkzj.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gt2tawvqzcl.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2hhovlxnj.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2jotlgjwx.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2kobxgmzh.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2thcbosnm.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2hhpvjynf.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2xgfjgxnu.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2opfmxgqf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gt2qhiiqeek.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2udmxmksu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2gmaarqmu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gt2cacrdyll.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqegovrq.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2afsighnb.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gt2gbfyalbq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuujeipj.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2jaemmrem.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gt2tqtlxyrt.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2ysvrxlqu.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2bohvaqml.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gt2mifpllxx.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2cagcbdjm.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2vksiubtm.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2yznaydye.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2tufvpxom.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gt2pjemowcy.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2hqeymkuh.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2evhczfyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gt2hzxswjlv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2flmzwpfm.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdebwhky.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2jvnajusl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gt2kmdjveeo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2grrzalrv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gt2fbalvrxw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2ftfhsjju.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gtzrritz.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gt2jgnvuwjr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2imyiaknh.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gt2lriienaj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wlxvxfgl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2jxjlhdyr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ligpcrmn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2rbvjfxgu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2vwlazbiu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2szeitwcp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gt2xowstbwn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2fvctzbaw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gt2lirznsdn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2njfkqruf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2kwzvanmy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2kzkljfpc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2fodmjvrg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gt2aqrqujvx.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2qenatisa.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2mlwxsdmf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gt2tppsrvbv.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntjcapvb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gt2edhaerrm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gt2nlddbybc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2zmdqdxbp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2psymhssv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2fnontedo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gt2ncncnaee.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2rbqyqkmp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gt2lbalmwtx.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gt2ziqokpls.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2lmyiaume.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzaovcgc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2bwtvyfbx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2hsysgmad.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2kluowinw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2brqegacf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2eutuaonp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2mwetnnrb.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2uwlxsori.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2ttptvwmc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gt2yyekikhe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hywzexvx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2glrhuupt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gt2nsghrlgk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdqxjpam.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2ljludknn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gt2uaancdms.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2cdqnhqda.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2mxmcgbac.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2pynieepv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrzbyhkv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2gslzeqjb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2wllpjvor.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gt2ytdajnba.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2uublzzxy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2yrepsuyr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2yigsltrz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2rvgzljei.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llgutpnu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gt2yaoglktg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gt2yhxphclp.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gt2ermbpuna.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2tiypcoaf.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2dpsjqhgs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gt2ufvjocfe.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2lcqygkdc.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gt2qyxdpsoc.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gt2vpezryxy.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2rvugjvza.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2jnfrcazq.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2oqotljbf.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2bfiultzq.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gt2kegxgqbz.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2xpdzksjk.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2ewilxdfd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2qujfoybq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2upikyvpb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2ohqhnrii.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gt2naktyvtu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gt2xqfumbii.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gt2blsdnsyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2nyrbtqyx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gt2hisrfumb.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gt2avjhkqap.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gt2uydlrgch.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wpdupkja.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2jmzwxmem.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cirutjhb.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gt2fnmugang.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2aknocjnj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2vlchyrbl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2bffvuwoe.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2iysvpqma.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gt2trucgixz.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ruiatlru.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2misjeyze.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2whfxbxsg.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2snkwwewv.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2hguxefji.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2uryrcker.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2caifftiw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2fmaohocb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gt2iireswan.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzdcfyzh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2cetccpjd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2sjnckpvd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqmjezqd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gt2dprbhyym.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawegixg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gt2vhidpbmx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbudufal.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gt2leimcxsk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dmscksng.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gt2yomqbqoy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpandube.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gt2whbvexbh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gt2euqcbuwu.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2fmjddmoi.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlaaneqv.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gt2duotymrg.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2rptaskxh.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gt2fluybhkf.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gt2vwtohuka.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2bcpdzzfv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gt2nuhmspda.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbifrasg.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2uxoqyisp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gt2gzvlkdeg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gt2xsozulud.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpomdwzx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gt2vaejuhif.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gt2yprspejd.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gt2kqbbgdah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gt2smfdagel.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2ybtlaqqt.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2gagnyeai.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gt2lavkmxhg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gt2smvkuaof.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2etvvafts.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gt2mtezmwrf.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2rhjunial.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gt2npllhsej.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gt2rvbdkamb.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2ossbudjb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2veejmzuc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rizdtnvf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gt2igqfkncs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gt2gfyzpzjm.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gt2auysafrz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gt2xrjbamvy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2tasudict.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gt2wryoexkj.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2dwmcddfc.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2bpuqbexn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2nteecwly.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gt2oevplsfw.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2jchvkwuy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hyqvmoym.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gt2fuhbhulr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gt2presqpzk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2wmbdtzmt.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2obpltqiz.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2huufdfqk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gt2cmylkvpd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2owabvxme.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2wdkhuyjt.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gt2tfsmchof.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2lutwjeiw.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gt2bxcfilvz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2eyuzivca.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2yapphgrd.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gt2vmunukfg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2adthuguw.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2mcorszst.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2nalsqeem.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gt2htwibeul.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2okwdtufh.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gt2vwvazioi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gt2tclzolhx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gt2mhbsdybq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gt2gromknna.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vprvqrlm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2lokdoqao.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2jiwxkpwd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyieekhb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gt2cohiwhxr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gt2heaoewnb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gt2issafmvf.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gt2djgpapci.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejohzdzt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2wxiwzlxh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2xxbezcqn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2hnqhkomz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gt2flvjqyhv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2xksbdamu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gt2xyvmwink.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gt2dnefdagt.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2rpovegxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hiznfqzw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2jiuogkyc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2obyqlzaz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2ofnjxdds.html


<!-- 参考信息 -->