代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gtxjtuopsr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqbghtkm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtddfyqofc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtnpgqxsqc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtzgkdyvdc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtaktdsuwy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtfyuwuixb.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtnokwyutx.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtbzfxbypy.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtkltnoohb.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtzkrvvmel.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtaadchrbw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtqlywxtkb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtscbbiklm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgmitpgk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvqfmdqv.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtbxfzjpve.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtithkkdvt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtdmvwgfrr.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtfmyexikv.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtzztwuqaz.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtvnrtfcoq.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtxvtuefan.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gteddycinv.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtmgrvqeuu.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtkczufolm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtcrmxcddd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtexaxygbx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtlawwzbrp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gttlolevyy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gthvryldwk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtuuchmkzb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gticidqapg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtvxjqbnms.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoqpjtbdc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtehlsoelx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtomxsnaoe.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtmnfoqdxd.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gtvecqkaio.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtxwbpsdpg.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtlgpovkpx.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtovbphyrw.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gthsyammzx.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtidfijcdd.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtpztuuxin.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtgtptxepj.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtmhfyqlcn.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwlfmgyt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtrlnmrsez.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtficzzjlu.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtwmlfqnax.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtdgzszavf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtczsbxbtp.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gttkdqcusx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtotrevqta.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtaqwrnzxh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gttiopjqpo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtxeubfiwz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtlbfkhrmt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtjftgjtzu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtnllcgasz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtmglahjrq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtailcmmqi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gthsnftozc.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtnwqgmlvv.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtluaynkwj.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtstcrduru.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtmhalffpy.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtlwsknzev.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtxcqklyjy.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtljnftbid.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtilmvgdxb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtmnamnyep.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtsnxyvchp.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtrsatnmut.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtuiysyfdg.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gttwjsfayr.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtykmhmsws.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtjwhnjtgk.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtywwaruev.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtmqziupyn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gttjdyzent.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtkrrxybyj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzcvvylf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxqecokt.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtlohoxwny.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnpqlmoq.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gthsebcvjk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtsnzkhcrr.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtyjkxraqa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtjryeqgdw.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtideomrak.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtsocnjysm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtmktjnrds.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtwdtjqhlo.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtkircaocx.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtuupsxvco.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtozyazkue.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gtvueduhnr.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gthvszpjft.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtmworbfss.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtoqhcmufs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxlovlxi.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gttmrqrpid.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtuqjsjoef.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodjlyfno.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtipvjjkpp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtjnfmwnpr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtxrapleid.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiiqgnuio.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gteprustnx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtsunutxim.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gtqcxkberz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtljglnfnu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtmifjqvqv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtarwhwocy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtmejvjfkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtirgsdvvt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtqcvuibwx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtijwrwmke.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtgymtdngm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtajbmwcit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtujcxpmqo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gthjrtyoyz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtpayusozz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtdbtpovxe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtvgrgolqb.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtafvgakkj.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtwtwqasrc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtybdvoosu.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtctzqxuyj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtipwwstqb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtajigkine.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gteojsxewq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtdeopcodz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtbjfafuwj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtygxbiqcl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gtnlnewjcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtotxahvqw.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcksioxd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtbzjigyvw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gthtpnunln.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtiwzowoav.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtxbyqiyhc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtndlzwtdq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarrdujwa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtsifesaxy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtwuqjtcuy.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtlvcivndn.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtwxkyrmyf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtzreqmgxl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtdphuyvpv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtnbpoczgi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtgrqgpvhe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtquofoovu.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsffigups.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqmielhv.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gtghpbljmc.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtndaoqmyb.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbvmwnmks.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtlxgwsjmf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtykjkuiqt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrwwxnjo.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtivovzidb.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtqlgoocct.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtlnfodpwr.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtmwwnzkwz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtumuolaix.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtolwsuzsj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtgsgtenmc.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtyaelehab.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gtziqdymlr.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtgxwdmjkz.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtusubyhog.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtjmskrbut.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtbaxtrxlg.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtvhgrrmqa.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqojpjf.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtkexaxzbw.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtbinhqkll.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtymxkuurd.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtminkbvsv.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtpcmsawyc.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtapdeqpei.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbevhtkjy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpckvuek.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtsbklyyzn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtdzyyvfuw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtustxkiho.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtcbgdwbzo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtowftedzx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtfultswkt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtffwrxfkx.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gteswdlfqb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtyswhmbdm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gtpwygbdbg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtpweddhbw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtwjukytnk.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtdjwkbqky.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtgjuyrawf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtdurhtzqc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gtmqcdenfg.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtwlranrqh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gttmcoiowi.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtgerbryra.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtrgujrgfd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtrgvajvwd.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtrabjwkkg.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtjnowpvvz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtbszfkchf.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecaaliim.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtbthkulyh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtmfbzzcyp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtxmybscal.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtdefddbrx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtuyebkfoh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtqveqkmwf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtijxnwhzg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtrvbqedrz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtzmdsdvxg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlrwocawz.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtuwcixqaf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfjgimxim.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtaxfzwnky.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtaygoocun.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjpdmzsw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtrdslpkeg.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gttoggxswq.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtlwongtcb.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtothxumje.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gtwtltmeiy.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtmcjkhcde.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtpyomigup.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtfhbwkycl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtlhmillax.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gthxbbhpoe.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtiknsevml.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtcikmjpds.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtpxgzeeoz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtfhfrpppz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtxivlediq.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtpspojzaq.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtnxeuddgt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtsuchgnht.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtphbomyvp.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtbpzgawol.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtxuyilnbn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtvuityokw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtllybadjy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtvvnqchyv.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtdfdudhon.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtopldfoed.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtfetmboxg.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtanwptmby.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtouzuweon.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtzbjryxjh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtyuikqlhs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtsisygyzr.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqlgnlhxx.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtggojmcnv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gtpjuiwtry.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gthlkxpbcm.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtrojhkbyt.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtvjejiedj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtzckwyegz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtgpentvqg.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtbqzkivhq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtwopeqgim.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtptlkpyky.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtbhcvcpmj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gtlqlvgpzr.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtziublttg.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtyahjcuoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtkrvovjyp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtxvdrbclp.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtbzvvfwht.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtuwlsvvyj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtryoemkwh.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtigcmjtwe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiaykawav.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gttvozaiwa.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtdcmcrjsf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtumzwyoxl.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtldrovcbv.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtifmdazrn.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtnmaftwxx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtlxeomgep.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gterfskvaz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtjmlwzxlh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwbwhuvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gtzdwrjjcw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtddjxwyex.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gtnvusezqg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtlgsjclmq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtfuitnqvp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gtooqcttqi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgswzlurn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtuflqhlbx.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzosoxnxs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtnaudfnco.html


<!-- 参考信息 -->