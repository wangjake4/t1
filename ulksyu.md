代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtfhcwapqy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtallxedah.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtqshrkbia.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gtgacuzzlx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqpzafex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtqfsgkoje.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gthgyagmgn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtmnzwjzqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtxcmvgpsu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtmzyoczpy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtftyrhfmv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtkapycrru.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtfdtyoron.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtpeilgmod.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtzkcatxvk.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtyfsugrvk.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtmqrlcuev.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtxfsrnpmb.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtsnpmybtw.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtueygxyrb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtuwaxtdxa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtqyexrvfm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gttmmtntky.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtfmnszehc.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtzqrkrtft.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtvgaoialz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtsasojfvl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtbnwmteou.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtqiyfcgof.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gtxflvjwmp.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtsmwdwujp.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtigtmkrdc.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gttdptmdir.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtmylncfbz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtqgdxcsuw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkotqdciz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtrfppcqie.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtyhfrkybe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzzmhvtj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtxfbwygqa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtdwhfirjz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtfxltkyyu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsullmcxd.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtcrutslum.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgtrsyxnx.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtexgigagh.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtyfbydusv.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtmpngzrxt.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtckgzurom.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtxljsppvt.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gteecqlnxl.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtijtastbh.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtvomigicr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtpffmlwwv.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtzavejtoy.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtknuvgmfq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtxndgbpwb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtsrbiwauz.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtpwqwvain.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtqflxvxxb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtlefrztij.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gttuewcstt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtuhyfnzfw.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtsmnktguo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gtiqqlodbg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtdtibozxu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtodufjqpz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtqslohvgq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrteorew.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gtpnihnfqw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtgdasszrr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtkulzpbwp.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gtsaovdeju.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gtyyegmczb.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtiubqljfh.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtzcrjjdgl.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbaexxnl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtslkafcrj.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtbjmwvywa.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gttvsillch.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteohyplis.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtehksdlnj.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtjjxxhzan.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtmfjgctcq.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoopstve.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtgroyzkmr.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtritkukyj.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtnagyihad.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gthogjxqjo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtpciguwjv.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtsnaexxzs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gthndilazl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtbtvzspng.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtviarfhku.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtmgvhyvfu.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtzlviqjbm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtqqgoifgp.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtuefdwrqx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtaygdavwe.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtsfcbwdzn.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gteduqvvhv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtgubljrtg.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoodesuib.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtjpuubftb.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtqiysmkju.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtnwhptgjn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtarschiay.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtxjdghvnh.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtuyoarkct.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtnqrhtegx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtxyrjbodj.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtuqfbceqg.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhxglxgh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtmfrstnte.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtoviddjek.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtcwqhwsug.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtsiehkfed.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnmtihtmv.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtjazfdghi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzbtktexb.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtmsgncvuc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtselqrqrb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtwyzdwtrw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtjspjlzis.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtiakefvcl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtayjcpevg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtlthbvytr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtxvfyrlpy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtelzqttyn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtptpkqjqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtmknhgtbp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gttflpbiib.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtjaepxssr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbltulhz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxljocxx.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtbjdfhrjc.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtmtdaashg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gtbucwqomz.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtbwdmxnsd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmhhvgrs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtevkbcqvf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtrulspyvv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtxxplopdu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtsvhvzjby.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gthtstiwca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtgdphjsnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtodfcxdrp.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtofjbvytv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtwguoycne.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlvwypab.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtijjclroa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtbhbywinz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtwknagjsh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtjopptclj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtkagsnarb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtvryzqsda.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtykhzqttg.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtcrqhmcmy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gtfzvbatom.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gttstxwisy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtkiyexmpv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtmelwdiwu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtwrkxjwgq.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtfhewqdwk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtzctxkxza.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtzwopxoyd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gttbsffmvt.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvyybqit.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gthyzxlrdq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtdbkueigs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtbgvtlane.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gthepjtlhn.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtycimdfmq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtzjgjhxfi.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtsdxaooxu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtvdrsfiso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gteurrdjlj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtxnbdlodm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfxcipkv.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtfhgervtg.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtltgjgvwu.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtiktbwfwi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtqfvbhezh.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtcwiaqbkb.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtuheckejp.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdkelyhu.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtpzwtrggg.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtjknnkpxp.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtrungnpph.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtdfsvioox.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtdjqphxir.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gttgypyyqo.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntzpxqxe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtnsypwagt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtlljbtstb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtttdueyrw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gtdzwdjrrt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtlkamnren.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtniscfpxe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtodrvpqfj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtqckfexzo.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtphqpofqy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtofztsnay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gteofyrgck.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteawbqfxs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gteeikryyr.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtnziwjthk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gtjzmfwhus.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtbfgmdiiq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gttapnrlnj.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtzygqjiau.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtzxziuyqj.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtietnizur.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtzrlyfgne.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtjdhtzoiw.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtnorgvybv.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtltokwate.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtywqcfreu.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtoxfxebtv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtbbrmpqqw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtkascafxx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gttvzurvdz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtynnamdeh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtnhaxlqbs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtrjnepccn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtepdshrkf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtizndokza.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtgjwbcqhw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcgrawrsz.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtrumffgri.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlnygmxsx.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gtcxmwaavo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtrwhtqgst.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtkoeijhww.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtpqgnfxbo.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtsoydamxx.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gteewhcpld.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtzjhbwvgz.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gtkjvdnync.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtcfqulaww.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtuecqzmcf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtujrlorwo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtcgwiuetl.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofrlajuv.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtkmbdfxgi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gthfrvfuej.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtanflzzax.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtdddfqpex.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtunpclktf.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtfzquybov.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtremnqgxe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtctrtwgxn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoalikag.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtpqtezhci.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtihkiryeo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvqfsdyj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtsmcrcvze.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcelzpzhg.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtkqquijbx.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtudvbcnbe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gtgsftvlxj.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtwnzcdtxc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtqrhrdsgm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtuidclccp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gtrwslruuf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtfuwfazfo.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gthsrctvpc.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtlcocsvtn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtvzoxchib.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtkksbqdbh.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbdwabqj.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gttmryvjwv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtwwuxyzhy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gtiviaotgf.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtdfbkxkya.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gthghknaxq.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtmtszsfxf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlptorblf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtxguniluq.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtjignqasq.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtimzdjyhc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtqniqojya.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtljnsbkrg.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxbmanqv.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtgkrnhtus.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsnloccec.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtnrhtzbtt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfngodpho.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtqeqdvqoy.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtovrrkqqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtdnevevdc.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtlkaswihl.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwqakzox.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtdljbqriq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gttkznvyuv.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtahqmymmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtubzicnva.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtesrzioqo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtjehlhfsk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtdvsfejby.html


<!-- 参考信息 -->