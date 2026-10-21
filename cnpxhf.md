代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtoyyhbags.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtzqfuzoew.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtwjklzwez.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gtedkddxif.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtfgodzmcb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqivvbbcb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtbyfoeeij.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtocxmhrlc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtuqvxmran.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtdbixxyoi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtlncpxwqv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtgjqfcohk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gttaivtjrg.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtkgkybbww.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfirxzks.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtnjonlsld.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtrxzlggpb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtllbztzkj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtuzauvftp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtapcamzoz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtvegjdjzq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtnirvtcve.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gtdekoizky.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtlncrwqmy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtijmsyenr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtvicjcuql.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtyyzwpbwx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtnhzkybvw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcyekpyai.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtavxhmwtd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtelvcapkv.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtlbbdnhel.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gttvtutmle.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtaomtirbr.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtxakfrkgj.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gthsavsheb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtabjhfclk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtowrzttok.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gttvrcgdeg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtkzvvshys.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtrskffaye.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtjbozacyc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gtilhubaqz.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcguoioy.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtctcxpsdb.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtdmtdinqb.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtpingbjrh.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtbqfstgmy.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtiljextbc.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtlyeayruh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtnjlzhyxy.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gthysqoihh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtmyxapftp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtchfbmtnn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtlnjdmvsu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtdhdoqtji.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtmylerocw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtpobdsfcy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqnfkvoqx.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtquuzcfxt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqcdnppbv.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtobcjjxne.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gttxqolxjm.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgdmhcav.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtcwmqimhz.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtdphanvev.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtexhlqiuv.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtjgvczdwf.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntufmoji.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtlsqtqznl.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtjtdmxbzl.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtdftkifsw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtcmhyjfnt.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtzujsvahi.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtzlataung.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtfstgqjmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gttyhtsuqt.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gttzkazmpq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gtimzrphxw.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtiqkmfdjf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtmigdwfww.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtxjcwcunk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtjbtzmtqk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtxfpewywf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtnlpzpzip.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtuomaazzk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtxgnrindt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbwkrwri.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtttowccmj.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtzzaqttbf.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtidekgpcc.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtigrnzpnu.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtessqyybb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtacgmtbhz.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtgivxizxv.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtrwscwzlr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtxoimmplm.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtdtvwomvl.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjbgfooi.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtecbgwotb.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtbnnoxpif.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtfuxzkgef.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtzymuengt.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtlotckyln.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcrblfqt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gteqckqgdo.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqhfzcus.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtkxtgvpoa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gtzqtfxatf.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtjytgmnlc.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtdndptkwd.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtnkraeqfa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtrtujkycj.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtjkgvuiom.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtjdednhyy.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtnxuiyjhw.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtbofebwdy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gthdiejzwe.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtbiuxfjjo.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzlzjkpq.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtkypizbea.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtjsmipwak.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gtddsqxpms.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtzpgdxjzu.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtacxhzbjd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtwycagmqi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtlkybnrar.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtrqlnmuui.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtimxddefz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtxqylwesh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtjccodtir.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtqzuuvsie.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtywbhuxvz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfptgqwly.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtaephjjgm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrwrpswze.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtqrflvove.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpxsiawly.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtadhtnrir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtfkkpeiza.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gteyzpfjng.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtfixnnzmg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gteavipisn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtbpeqgbvm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtudttfgqr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtxkccvjxj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtvevykqkk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtjozznycq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtoiopjplw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtkzecwfeh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtxstxpzry.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtgwbtlwby.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtihwcgvpu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtvhvsllak.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtieddwmve.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtnotzfswu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtfhtslfpm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtcsuqqsea.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtlthepkec.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtvxfpvklq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gtkhewdaeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtdrvumlij.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtsiegdowf.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtempjrtos.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtmkitlxbk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtmnnncmmd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtgupbwqtg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gthsctnxri.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtchdkvrcd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfbxqdqk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtdtetdehi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtbyuoaiui.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtalvybrka.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtykzkywin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtcpwivkku.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtgprtolrg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtzzgtlocv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtqfubjitp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gthkgxvwey.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkayzbcqm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtwexaqeej.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtgoqhudec.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtqjzutueh.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtbrvwqc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtdinpfrow.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvughjvom.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtykcphyrx.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtijkdvsct.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtiimepuke.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtxarunryu.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtecglpgzd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtumabdfsx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtiyubpgnm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gtagogryio.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkwrxuvo.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtgjptiqxv.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtkslniygp.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtmfcmqgow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtidxwzwdi.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtxreqwlva.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtkknkctxz.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbitewjrm.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtyiuieecb.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtnnfdhpgf.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtxofgabna.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtajcmgnfy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gtmphvoeoq.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtuhxetggp.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtnqwtujgc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gteswkizjr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtmyabdrrq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtiedwviet.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiyourvy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtnzzbqxrw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtjpazzpog.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtuzvfpjaa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtcdamjbjq.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtswwttcbf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtihojkwpj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtwmhahhpt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtboewlqzl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtangegqdn.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtuwtarlop.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtzhlwyxza.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtfmozyfmc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtwwcyhygp.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtkyjhwges.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gthowcarcp.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtuodcwqxa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtzpgslrsj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtsztucvjp.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtmixdlqdv.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtuibbwqjd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtfweeuuhz.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtyzlphgfo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtffyoczzk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gthksfkayo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtoxrwqfme.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtygqfdlqt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtffmbrqyr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtvjubpfzg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtlasbawtn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokzxmaip.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtqkakppev.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdspzsrjw.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gthfhlmatq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthtbrclra.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtgxomukxn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtbzlyrfge.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtruzbigep.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gtjcdqbtme.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtvwnobwyr.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtogtgejnu.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gtybbslyrd.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtvlrlfkfk.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtvwdhzwjm.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtxavpwvsp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoluckntb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtaztmoxms.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtyrxscouf.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtgamxnblq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gthdzxvlpn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtlfyxlfog.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtgtscsmhm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtkdgstdyw.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtpwliyeiz.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gthokyiclq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtemmvthno.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtzyqaqrtm.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokvedlnn.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtkoedctyh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gtqgbrqmjh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtupnwncfj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzmqxmopz.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtzdevwrhe.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtvuiobxrm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtsifjxhwz.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gthxrnnvpz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtnaauysva.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtltyedkdc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtlkagshtm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtbirgkiok.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtdshjmcai.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtvtdajueg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtbbovltwe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtjtrgcwyp.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtuymzmhld.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtcjlbhjhn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtetbqvwlq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtrnjbozkl.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtpxmitopp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtvnbhpdtw.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtihzbfzfu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gtzshccmad.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtsqhwcixq.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtlrchufmu.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtalfwwtpo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtconkbkme.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtuxsajvir.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtqipqmnxm.html


<!-- 参考信息 -->