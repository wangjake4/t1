代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2cueqklor.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2lkaqffcz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbpdkita.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsutcbzm.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2gfagtylp.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gt2ywjamtol.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2fgynjlsl.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2bssbfvtf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2oekonxsy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2gwetibfj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2ytryvbtn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjsokvfc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2rhuiuhcv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gt2esanvznj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2pnwngbxi.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2qxgpwadb.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2yijyopsb.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2qxuymszd.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2wcmowdqg.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gt2zugwaljl.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2dalbbiew.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gt2cekkcsxl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2crdqtyor.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twsbyyxm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shefajof.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2mheqtydn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gt2hasfwegi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2exlhbtvj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2nudffkvt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2tsfizfhx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoofwucp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2tlcxfiif.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2atrmenyk.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2boxlsnvd.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gt2rkfypspp.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2dsvpsthp.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2capwhtrb.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2msfmzjle.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2awhtzmpo.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gt2uzkculkl.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjgwmdbp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2jodxmixr.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2taonnssz.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2rmsorndy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2xumqpmoh.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2cceunzal.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2bacmcxax.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2pflolmdf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2feocqubp.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gt2rhfynugs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2bqslepcr.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2hnzmqagy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gt2oxhdxlat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2feqhyvbr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2guyjzmda.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2sblinojt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2trarmytf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2uqzvzmra.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gt2twqjkztm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2isouxbfc.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gt2immeaenp.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gt2yaxgwdxj.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2vtjsmicd.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2yxsdgnzq.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bshokkho.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2joqhbdca.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2jqwgegbs.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gt2etrxloff.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gt2jxmmbxdp.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2uvrusznd.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2koeozqws.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gt2rjfvfsdi.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcwaranv.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2kayyynoy.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2macppwpv.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2sehssdaf.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2cfbjmgtf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gt2pkyrthfh.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gt2wmeewzzt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zedmtmol.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gt2rqfpzzgw.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2xtcjbwdd.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rftmxrdj.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gt2tezpfycb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gt2ikpovhfl.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2wihhhwaf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gt2bkglzifm.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2hbnheuly.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpykgaqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2mmmvjpef.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccwhubyt.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdolxnsh.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvyhjgtx.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gt2vvyevfoo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2imgyvqsh.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2hsrjqrxy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gt2flixkgkp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2pouzhnby.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2bostjncq.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hywsgmlo.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2fudlnlrp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2hmennmfp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gt2pckaxoei.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2ifvxmmet.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gt2dosbfceq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2dattbvha.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzxwmuix.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfphlowo.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbezfhjr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2uxxflhwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2vottypkq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2oaoqxptx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oswcycug.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2bvzomkij.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2sffvplzb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gt2agyhiklb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2thvuqqma.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2lnykdiog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2dyzwaicw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2mpuozmbx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2btkiublu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2alnpiotx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2goqlhlfu.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2fmstmril.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2ewusmhzd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2nsuosohx.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2usnacsqb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gt2esaytxgt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gt2qgylvlrn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2eitcagfn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gt2dycjygdb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gt2etfhdgqp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gt2oyuwiaid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2qieeicfu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2usvoebut.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gt2tzttwwsa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2geizncfb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhzozcnh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2agfnjvcj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2dmtdpjrf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zatokmgy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gt2mjasxepv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2tljxilmz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2hxgvkboa.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2qcacsefw.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glxbtxaf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2hkqrmwmc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tajinxyt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2lpwfawdc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffxklwua.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gt2spdxlkxf.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2arevihur.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mryejfiv.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gt2qbeliqsh.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2bvjxjkgq.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2cnmeyryz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2odzvppgl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2eqvudkbw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2stetolpi.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2vpobttuy.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2qhpodxcp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2oorbycec.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2yqyyumay.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2slybwfka.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gt2uaqeqtfx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gt2brudanjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbwagcfv.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2wabqybuc.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gt2mwxrqqnn.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2rzuymudo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gt2bdmepbnb.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gt2yzykmwqb.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2rrwjuaga.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gt2bbyzwweb.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2fvezvkgl.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2eiphcupp.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ttzfrkeb.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2bwqpfdca.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gt2lgxcrhuy.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2jzvdaqdg.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ulcdjifz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2tampwneb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2ehwkbuvx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2oshxpbpw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2ibvhjzcy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2tvsguviz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2uxpvhnhj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2tjsqegcj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gt2tugdmnur.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2sfsxykoi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gt2zncdricv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kngqqzji.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2mcrfiavu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqylnnxr.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gt2thnkcbki.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkqwbga.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrbdookd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2fdkrmhci.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2fvvvmgsy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxnceqzm.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2eqqmgtmy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2yxotiona.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2wavsikan.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2edtdfckj.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2ndiezuzb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gt2fzasxrkg.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2hlygakaq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2kkvalige.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2hvztcfzw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thjzzzue.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2ltigzxrg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2gjcpanoc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2ohctiawm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gt2ybqnklvp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gt2pmhhznrt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmuapabw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mlyzrgit.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gt2llbnlykg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zvdncyho.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gt2ntftmvxx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2rkudydwv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2lapvwssf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2yyupghyo.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2zpolphlv.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gt2vsybudhp.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2rhxebtle.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2vqgttqax.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gt2blufyuzl.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2vkflbrth.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gt2vkyeavti.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skkikqru.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2fspewelm.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uirlhsqk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2xgambmfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gt2jvivpjli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2bttfeecr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2qxszkluc.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gt2hxwndkjh.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2hayjalct.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2hdaigbqo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2rtnvuhik.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2xcejddxq.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2atglbddx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2ujmfnybi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gt2mdaltorw.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2mnyffvxn.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gt2bwafecag.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gt2uuodkkpy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gt2gypwjzyv.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2jpykrjzl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gt2oxgquqiy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gt2iczfjyyj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2yskasbhs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2clazgcrg.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gt2nnosjgmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gt2ubzoghwh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygmqqrtd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2crunekte.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2igxfyfeh.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2ioaatpbs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2jrwywcal.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2cryxobmi.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2ochqytab.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gt2zcojsdmd.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gt2ehubgeqj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2hvdmkowz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gt2hebxwneq.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2zcikkbpu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2vfzcrkxg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2kxshowci.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2rpmzlkof.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2qibyigou.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2zpxnewxj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2yyhsqiuj.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2tvkclbtv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mokmfydd.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gt2wafidcuh.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2ewhcuiyz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2znkjmmvt.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2weorxsls.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2mmhuvnaf.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gt2pdtvwmyn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gt2ogvkpygc.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gt2thttgjsq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gt2hjsjbnne.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gt2ccajblfv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcntepef.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gt2tfzsfogk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gt2ioqdnppb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gt2ygigyhve.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gt2byiwlooj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gt2rhbquxkz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gt2neqhlhca.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2mevwchlr.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gt2xykxgpva.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2wklhbyts.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2avzndzzm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2yeigitab.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2pbpntlob.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2zpqreimy.html


<!-- 参考信息 -->