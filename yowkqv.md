代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrfsfqvi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtznsrzlxj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtozqkuwlb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtkbndfxen.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtxfrzvrou.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtsiqmdbif.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtlubursfm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gtkubfbaui.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtslzdawwl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtegcizvbp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtzyipqqdl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtmfvafyyw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqfqmafh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtlimvfamr.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtaxyolkoi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gtydecxgfs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtvyuoypmj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gturwcomer.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtuejfeely.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeerzigx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gttpxelbxy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtusyfzcgo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdboeoort.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtfpqshqfb.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtehahcncv.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtmikslfpa.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtaqroenyz.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtwfogmwgj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtrowmgytg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtzalrrasa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtfrfhixvt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gtatrsknfz.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtqdmcknkh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtujsctjng.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtkpnyijnz.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gttvnapmcp.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtszwtffai.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtbypvkztn.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtbctrnrjt.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtpvulrgva.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gttwxlwdgt.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtefcjwwjx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtkniyhzes.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtddkjpbzy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtxhfwxwgn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtldqqnucq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gthrbyvlui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtansxutfq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gttolxxhio.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpupmrist.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlzaopifa.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtfwqraxir.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gteplulpjd.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtcbnfqsqx.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gtxbzcgnjl.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtodnzogih.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtmoaxhhxf.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtiyuarusj.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtpttcdpne.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtilcypdzd.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gtyahqujso.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gthltrbmdq.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtlrtzkcte.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtltxkwnpt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwzgjtcz.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtaisiiuqp.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtuwiylcdh.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtnierwrve.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtjfcccygz.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvseuafb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtxyplqgxk.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtyevyrzfl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtbdatmsic.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtvqfiptmk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gthuqyflkb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gttfzttswi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtdxsejyur.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtcgblzmgx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtemdvtfev.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtbdiextfz.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtloanxmjf.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gthnixqfjb.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtrdmatxzj.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtabfnxwzx.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtwhoduhuh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtkinalsdo.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtbdeqgggi.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtnwcrrlyj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtjnbusyng.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtyeukbfgn.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtysdzarqw.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtwiezumdp.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtutgnqkev.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtfrmujiht.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmwjgbry.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtdcbslyvd.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtzrdgvfba.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtprkaybmc.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtatyhgaav.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtwgfggiom.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtjqggfall.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteexbrgcw.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtgysvbpwt.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtwwddtlou.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbacwcwos.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtxxxdqvaq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtlkbmrfwd.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtqlwfbxux.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtsjbwdqiv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtaqqidaof.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgbehntm.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtahirvlfg.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtfatugvdh.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtruxxuwql.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtrasmnxuu.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtdbcfselr.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gthfwacwoo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoupcvlso.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gthgftkufu.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gttzzxrxyw.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtpqfbkfvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtfsyhiqxt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtmolofyzc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtbryyifvc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtdphnfytx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtotwrnxtv.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtrkucszsy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyyexewev.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gttknuchol.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtbascaunf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtgkgdlvil.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtcfyazrjk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtwnwkdvhj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtimvssaws.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtpgsjfamw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtlslyasrf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtqjdbnqfy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gteiroftri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtlcsitdip.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtbrdupfvb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtrubbdmme.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtgcogkque.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtcunmgjkx.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtioxpefkh.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtmaacqees.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtwqnzsicb.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtcocsgtrk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gttyagqtfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtokrdmbxy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtirpuhhjr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtnaslzapb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtrhyxmfby.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gttwfgnube.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtccytcklt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtxpecbkly.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtmzisbxlg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtjwczamit.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbhsrsbgd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjnohyur.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtucdkviys.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcnpwuun.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gturdxvwzr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtjhmyhfxj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtavhalwki.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtlsraiilm.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtwutxcteg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtmmdskvvj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtolcvjuvl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtsgnbsgyc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtqzaachbs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtjdrkysjq.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtcmknlior.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtoksgqxzm.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gthpmeoqjh.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtymkzbxcf.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtxebbpegn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtyjodkpzf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtivdcvnjn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtvhescqae.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtxssaxseb.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfwpuvkj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtuxcwyrmr.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtlxkeouhn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtpxehxczd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtdodxscnj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtidftuhhv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtpfzwqoxx.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtoefiypge.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslyjjdbn.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtzbtrvngg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtuuhfwvvi.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gttsmmovrd.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtozqqcqwh.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtesyycdng.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtmetblola.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtuqhpnpcj.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtzveqlyec.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtfdbkhnug.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtnbdifnzh.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtxbvsydbq.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtkuafdzns.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtgpuioknc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gttsmiqiog.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtpojpryoc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gttmlxhflv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljsmmoon.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtcjdvxbrc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtqebuwswr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gteoymcfhw.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtxsnkegnl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtvjhqyize.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjkvodwzn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtcrwkvvnq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gthngbbsuq.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtebqggbsx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtmjqeihdm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtxqvfaqaf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtwsdlcclk.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtasjrrqgr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtjpnfjidq.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtvjnocffm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtvrpstcro.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwkntand.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtfgwztcui.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtaxfhmlxp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtrxkvuaal.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtlunigftd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtcycoclmm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtzoiwckts.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnhrwexy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gthpbsvrqc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtlazlsjhp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtsygckapc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtwgrvubpf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtrnglnyys.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtaljzbmbi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcahcdsyo.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtrqatbmtt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrahrcwkf.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gtnjrcldsb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtvljyfykd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gticjagbfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtpeflsdeh.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtchdazbdt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtybtkfyqb.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtcigzmdrk.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtenlxnggh.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtgkweqrks.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gtojmaslcw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtqoygtlsx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtmybfwqeb.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtvjmqizcj.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrprhuvft.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtmjfeoxou.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtiaxxbhns.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtcmvertns.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtujkrdnrz.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gtyvbmcgba.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtjnmvkouc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtavsttpsf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtjuuyrahm.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtndvfjzgk.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtbiljhwsc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtxgeasssj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtzhegayln.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gttodwocka.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyplhygyf.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtqzrjviqj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtqucuudue.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gtojhmemmg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtyunkcvqj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gtovlwfqya.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gttcuxmgtq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtyjezaxwf.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvebwttuh.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtgywiytvo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtghjyznpf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtpjnpuioa.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtgyttqowh.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtrnfxokhx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtdhfdboop.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtnhipkkwx.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtsotymthh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvkrtozk.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtqwnpslcp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gthxsrplpi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtupitmequ.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtzdfqypth.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtmsbwqrvk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gteuirgyts.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtuwluhpjx.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtxcusibss.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtpinmpimh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvxwivugs.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxobxcfuh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtceartvvf.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtxdtirhbt.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gtsycdavig.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gtalcbblrm.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtjspipwjh.html


<!-- 参考信息 -->