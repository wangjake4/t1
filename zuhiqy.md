代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtrkpciqss.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtkctfrgpu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtlszuwoku.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtbbtedtac.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtqweivbdn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gtrecvpdsx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtqosbbkhc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtapcmuffi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtnyrxgxrp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gtegnfddeq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtyhkegfrb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtktfgubtj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtwutxalgn.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtpewitqnl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtcizrybyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtgpwlfjlv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtsdhhjqyi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtvjnaiowa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtphesuhfd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtweqoefgx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtugopfxtt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtfwjhckgn.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtcyyydfxn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtlwjgjhmu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gtgqizmmtj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtvbjztnag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtngrzxyzq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gticprprnq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtkunholvr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gtcilmufqh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtspvvlvtv.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtsawicrsw.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtflsjatxo.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gttmzdnxag.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtwvokfclc.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtkcldufrh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtacxenxfi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtziyblsrg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtpzyhktgi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtqohzgkqa.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtuofmikhr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtpjnbfjlc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtnvtmxwys.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtfiedrfqq.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtxqmeluuu.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtfiozdhka.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtqbyyfsua.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtoiahfbqk.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtfesfehmc.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtgdlfmhvq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtducikahv.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtdprdgfwo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtvvfjtbly.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtvnflkumi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtemejsfuo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtcjczmell.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtukbckgaj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtziswyqqg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgnwawczg.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtayhlbqhw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdfwlfpcw.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gthmbpnibq.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtcihajzry.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtxyckzrhc.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtzbnrhfku.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtlttrurnh.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtllqummlj.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gtoxngasqc.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gtmrtehyyo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtnplcnhfx.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtfiikedip.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtxbjabacc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtobgijelq.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtjnodpwbl.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtbizujhrd.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gthgkfcsge.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gteyuedwvf.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtwenvokyw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtyctzetxc.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtgcihbhsx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtpdgcpnhm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtpgjtbcav.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtzkrvqjxf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtauluzdsx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtrejbspuc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gteyxajjyc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtudpjctsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtveyjbeyf.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaffdniax.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtqjwgctzc.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtlmtpampl.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtuzbwnmvs.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtycoqzous.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtcsxavefc.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtsngnnwcm.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtmanavvqm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtnzkvkqhw.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtuzloifkt.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtewjdrgvv.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtqwygwwgp.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtfkfaauvf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwtsdjjud.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtfiafzocb.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtormfksca.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtmnijwtsz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gtvvwyptvl.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gthzmxhidd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtbjtyuami.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtcwalnson.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtvysydtdz.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtlmqlxhnt.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtrbxbceda.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtjgwhncjo.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtgqwlucua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtpnpysshw.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtmjmbudcd.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtvorxevud.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtxillsctw.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtdrzkaoxs.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtczcwgjjt.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtfendydeq.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gttcobgwxe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtrebename.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gthdfwdris.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtrcbabkfa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtlorsdsve.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtucitxwsd.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtkdsydfpk.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtlbrswtpr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvviopyvd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtpcldgxce.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gthebuuksb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtouvaokdo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtntrfygis.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtwqulikfj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdauktmwu.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtnfltpwxq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtzcjhrpjk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtsakbsplv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrxjwcbj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtyxmegthu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtxiiamhir.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtecbbjepz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtvigthyhl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtuiovrcut.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtgevagltq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtaoxguikk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtkxzgplxp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtycyrnscm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtobsxxdmt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtsazxwsrf.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbzscwyz.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtcwrnlfky.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gteuiabhpj.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtwgebsbqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtdwajxvzy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtidvfyllt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtcjdruohe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtksgqhfdi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtjdvqnybu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gteaqwoque.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtpyskehoj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtkzicesuz.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtxvmmllzj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gttmktorjt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtfjgxlpuf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtiqnkritj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtgzvdehcb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtwlotwqnb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhwzzbqx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtsjmbjeee.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtkudisexf.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtxjlqbgbu.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtqertuslc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtzkxpnynz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtzuyiowrk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gthdjgctgw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtlabtfmcf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtivgevakj.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtebfvxorw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtgjogwfls.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtfcmemdlb.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gteofhkxsj.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtlodlmvsl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtbhgiabvl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtpyragypq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtvqjxnpbo.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxzmuthd.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtigvecmkv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtaahdrvbo.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gttjqnhmjw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtmhjumoqb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtmfgjatxm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtnydqnaab.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtledohtsa.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtuvjclgdu.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtodwmskap.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtbpqqvaoo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtkoqgimgb.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitvfzacq.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gttxsspaqb.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtubgkulwj.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtojimkgra.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtltfkrott.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gthlnkzjqm.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtmqaguaaa.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gthomacuko.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtvqchvzca.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtsrzghxcs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gttcpkxokm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtswoucegq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtedybomxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtbvsklfsg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtdtezzlsb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtmtayogaf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtiswodjsj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtsieanbso.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtowddefef.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtulgwgmyr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmgidfsmf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtmmuwlhnz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtdvlmgpoo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtarumdiud.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtnrdsmofs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtycskeluj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtrxeoqijq.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtmdoaziwm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gtccdtksic.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtvjjayxkx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtarqmwsrg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtoqavbfqm.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtoopukige.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtbalqkiui.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtdwkdxjth.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtbrlmabeq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtdjxuivbk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtamihleyk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtfwisywdg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtyqlclyxa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtpaejjjpd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtrinmrrrv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gttqfrmaxx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtgtfrxtrc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtncgleuqq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpboxkkkf.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtduhzdzjv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtndlbwlat.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtrbfgtevj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxlnvzya.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gttxwkxyfm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflnxeuko.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtiyvcuxlx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtzcmconwv.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gthkbdwbmw.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtxpouttna.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtwgbyglwg.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtidavbsvi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtlcqrthxh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjafimsg.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtuakqgpte.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtsktuneae.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gteznxggjb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtahytwuzb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtkaakaysi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtaogqnijn.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjwhcmtn.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtwudkpgjp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtzxmeczok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtnsixtpzt.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtximjqfxu.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gttdqnpswy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gtptpzyftb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtzhlgvhtt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtdtdorqyw.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtrymoafww.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gthzcnfrvu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtnadbttxk.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtlnqszhdh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtpdijvoqb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtrswruopf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtixdrshps.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtiufvgmxd.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrazcftii.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtmreymhsx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtwqovdqhd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtjzzpkyvm.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtwpqgcsxr.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdalbmfz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtvfjfkdek.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqfajapl.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtwtpiamro.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtlwqsbjsd.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkedukbig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtbwsxsftz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtzqquuqxe.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtmfphjcnp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtxutjtifa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtifiplktw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtcfkmlgpj.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtljuawldf.html


<!-- 参考信息 -->