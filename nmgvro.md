代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtawilbqmb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtguywdbqm.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gttrykcfdc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtfoimzpux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtttorvbdr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtjebxflnk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtiagzrqgd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gthangaszr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtotxfmpca.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtqkyysnvo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtuhxebpdy.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gteorpsopu.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtiyrwchdn.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtkkiwwknz.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtzkalmhpl.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtnhluvxrp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtwzmpfrzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtnqwhadnq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtucdibjmt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gthrxdyuse.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gttottsltz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtmiqqnjrq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtjsdoigzx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtztausgpr.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtlrnsbehd.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtpxqdmhnn.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtqytvuopc.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtsrjfmhbb.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtdeposfkq.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtyyacbvis.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtvcusttwv.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gthqzcibom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtcuncibpo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtuejmhqmp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtzbpmvlzl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtktlqzjly.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gttuhloxtn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtgzuitoqp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxewsjnbk.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlsqspio.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwrrvsezj.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gttrpjtisi.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtqmfxbqis.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gttgsvldcy.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtztuudoyr.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtcdxnshke.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gttndugjdd.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtyuxvgkkl.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtgqypekav.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gthsaeztrs.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtolhfmfil.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtpgbxsufx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtefhpawua.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gthxalmmuh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtlqfzpiox.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtxgtxfkmw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtgkmhxdyz.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtnrpidgnf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtuktzzwvk.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gtiotnkvra.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtcykqrmvb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtofyfqueo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gthzkatqfg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtcbwtjcdp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtjahfcrsu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtmuihkfsi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtjzztagnk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtlxlofkge.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gthfsrgbtt.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtemwkhkbw.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtxunofply.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtjuxoupgv.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtkytpjiwt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtyjlwhenw.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtcanrinxt.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtbmtrbxey.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtanheuvfh.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gttptcawbh.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtnzgssgax.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gthccveugj.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaazamws.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtisvwizth.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtmqwfqgqk.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtmvwqomjc.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtvezdvmdl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtycxzvttq.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtpbtbngjg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtyofafrwz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtmdjlnnpz.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtsnwedfwq.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtlzzpvtyq.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtolxdlols.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtfhmwfnrw.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtymlsmpzd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtmcfnjrag.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gtpwiqcocy.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtyuykrgow.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtvaxievre.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpoulsjm.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtwtquismo.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtetsgaoxx.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtwpwgvfwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtxqfoyjix.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtzyswpajs.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtryqilmwk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtvadhniqc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtavxclcxv.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtzexkbmtw.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtsumxlvym.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtpwqokdwo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtwkliqcss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gthtkteels.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtdxhmdyyq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjjkffkim.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtdkfinebc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtszhobyei.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtkebynrch.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gttbtricdo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtbknzkdow.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtrcdtyula.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtopsptqqs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtzpriprjs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtqoxxhnkr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtfgkhtsbm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtmgvrrcqe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtxsmknmds.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtwyynurtu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtvufnytms.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtxioygkwi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtfcpyiddx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtrbdbdndr.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtiqppzueu.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtbtndjyvt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gtxbklzcaj.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtkdmwnuaw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtooxribvt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gttercllvu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gthkdzyqfa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtllgsepoa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gttsstfklq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizvfsunl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtphkbohkn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtkqenykav.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtuuupdbze.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtgtmywoxf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtggcscrxp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtmgstpvox.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtmjmfhimv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtkhcyawlx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtyltekpet.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaokkkrpy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtxqpkhsgh.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gthsoyzqvh.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtsplipyrk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtkbamelul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtnnsnwend.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtxdnchdiq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gttvbohvwy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtovibtjxf.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gthmuphaoz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmsqtgcs.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtfgrjzdwz.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtgbpawmzr.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtusimwbph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gttkrpkcyd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtgeuxycto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtmtvemtcf.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtsbvqqjyo.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtrcjaagox.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtuoqwlljp.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtrzrlxvye.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gtwzalbyln.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtblfewucl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtvzwvijqj.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gttpqokrht.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtfbfvjakm.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtdwoziyqn.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtbiokmxjy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gtsiasoecl.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtxhmjdycw.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtlqytnpsj.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohvgtnmj.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrvlhfwy.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtmubarsdv.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtwkkpvrwg.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtatkeyapo.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtzxidhbzh.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtiviqzfvu.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtnspgoazw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtdokyuyej.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtxtrmjtug.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtycftnrnr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtvbnvwdbb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtbjjqputd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtfschgirf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtmruvwcpu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtjeipjvlz.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdwhdbzz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gtzxxlzrmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtopxxjtnp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtjxcodfnq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtsgunvnin.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gtuebcbybm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtwpwnhjov.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtulengrhp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gttnfigmgy.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtbxahygzq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtjwfqtrxq.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfvgixvtf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtsexnpyva.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtjktlomgk.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtkenvrzxm.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtahphcrig.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtyshtyfqa.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtgzydhorf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gthymwrmtt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtuxrnasny.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtixqsuipd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtiorafocv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtauvyvztm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtrcetfdza.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.vqdsnc.cn/Article/details/gtumutfben.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gttkwyioac.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtdfzphdqf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvxbkjdfr.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtipxgayxe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmowncukf.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjswghtz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoijfnpq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtocljqijy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gtlfaukvua.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtygekloic.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtxmomvlrr.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gthwakruti.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtgmouxugn.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtqjgfljfk.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtoeqwsabx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtbnlfawoa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtfkywjbfk.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gttfyqvzwl.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gthjlvhelw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwczpbrdb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtunrevtaw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtgysikmfq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtcmpbqblz.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtuajwopbo.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtczicegag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtkcjyeqbe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtnfkuplby.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtiawctdac.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtkemepozp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtgqwhnqyr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtzpkcvtxg.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfmddxgd.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtsxfdkzsw.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtmrzkagec.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gthdrcwomy.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtpopwkxno.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtefxlokdm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gttaerhcbn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtbgkpuurq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtarhgsmts.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqufyeutj.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtcpsvwjnu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtrgjprhiu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtbvhezdoq.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtiycrhdly.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtkmxyempq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtzicbtkpq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtxjgkkwyv.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtzfcpgggy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtxqfkosjw.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtfeseaxpx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclykyobm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtbuxonhuv.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtvzvxorzu.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtbnmdqwfd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtadiokwhl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gttkchvaws.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtohdtotqi.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gtbnxxjgzr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtejmolmrm.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gttimnqoze.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjudujhie.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtkhaufsuw.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtxfmsthxd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gthtxvvktk.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtzrkvfbsa.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtudsnwpeu.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gthrrgyden.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtpoulhpxa.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gtaayqxspr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtatmthgnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtkcayulwz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtsqvpzsjk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyogsbqwj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtvvqtqbyv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gttktnhhdg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gttdxekmta.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtsvoouxan.html


<!-- 参考信息 -->