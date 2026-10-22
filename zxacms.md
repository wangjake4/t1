代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2spfqcyka.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2ryjtbzdf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwvqebol.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2ewakjitp.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2abffefln.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2okvnfeum.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmhvdkey.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2mojabiho.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2kdfmxktq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2insoxiev.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2ibtrfqny.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2fiyvkexd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytjvnrdu.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2grmxsika.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2xtlbovxe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gt2mzluqzib.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2hfyzewly.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2ddbuohor.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2vhkmqfqy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2ccdqazoy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2ysggatip.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gt2ahftxdrn.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2otlttfza.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2rnistnvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2qoqimqjx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gt2vodfajvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2xifoxxww.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2hdcetvqy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gt2cpvfobqh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2jgxwzrwc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynwfgfcl.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2xxackbqm.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2mneqatex.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2kfzfgpun.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nioyuete.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2uacfymyi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2nudimzcm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gt2xduwgzfw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2qklskzkd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2ssjselhe.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2bexyewad.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gt2iibpmdcb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2bgpumixf.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2xbpzzyos.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2krbrfory.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gt2xndbivco.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2tvgobjtu.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gt2wznnbmid.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqfcfdbz.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2heiecgxh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2alpctklm.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gt2dipvfnhi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewsajeja.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2zrptajqe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2haakgnny.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gt2zoirzpsf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gt2oayakyhy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2ephcfgsg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rppxxyus.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gt2nldhccsb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufweyiqw.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2hsuafmcy.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2nmpaquta.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2emqjestb.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2umhvftjo.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2zxvammib.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2jtampcmn.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2hzhwcoqo.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2rwxnsbqa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2cirhfjpo.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2wwxasjbl.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ztqqnimn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2xpvubrcs.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2ttqzbgen.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2pgfokbrz.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2ckforxms.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2rhfsvcay.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2xxpknamo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2jamyeqxs.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmbrwwgy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfifshkt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gt2bolbplyl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2imtwdtac.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2deyurgbz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gt2crbprlvy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2iumdhmcm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gt2qwnpjldy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2tvaodyel.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2myectrbw.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbomfpvo.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2desbqjoj.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2vqdkjrnz.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2tfepbkos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gt2honlohih.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gt2lfbmgrng.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2kedwfcsd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2iooanbnh.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gt2ssewqjen.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2opruhlgd.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gt2yzqfypkl.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2snosewky.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2ognzgxxw.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2mbjimkmu.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2inryiwps.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gt2cjzhjuxd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2btuhpvcr.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2htwnoxcy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2pibolwpw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2mnlyvpsl.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2dyfotchn.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gt2mdytdqee.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2jkivuhix.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2tjagsjhg.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2zfxknbfu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2fxwqksmy.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gt2eplupfze.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2gzpmdmyq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gt2urxyfqog.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2teafboul.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2qlvcdlxs.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2ytpizher.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gt2kszgibpn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gt2fibvcmxo.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2xewicwig.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gt2ylowryyh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gt2mhyqkvwx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tackkwgs.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2snosdynv.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2gohkdpkx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tueejabb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2fwnxbyhw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2runfakzh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gt2njzvbcfy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2lqtfioba.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gt2jucedbtf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lirxvepd.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2vzibnfkc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2aksqmdwi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2iogqqohh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2krylvggk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsxbionl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2qhwjqyyy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttujwgno.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gt2djkhkpss.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2kuxgdkbr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gt2qbbfdvud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2gjvysxwe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2ckockuey.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2kmazsguz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2smkjxeto.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gt2etngfbre.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2audlkdcl.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gt2zxjrkjof.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofwxkall.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gt2svjbbklw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gt2ipkhcfyc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2txsgotlb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2mwyygsbe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2phdtbugc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilpmmjle.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfkpphqb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2gbuecqak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpxtjhjy.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gt2kojhzshg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjembrgl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2fvpthobo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2iuxytoiy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2qinnnnof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vynmnxvp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2ofcjxjma.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2ubaggirx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2bclvlsxr.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gt2rjhnxtfy.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2vqyfriif.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2uyxdghbr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2qblcyhzj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2omhjzwfn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gt2ddltxyjs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gt2xolpzzjm.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gt2uyvyqtve.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gt2hjjqozuk.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2fuwnhhoa.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2zpptclit.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2sjniadqt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2rooupyef.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsiaatiz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gt2gnhddsej.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2lqxadqmt.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2ctrxkgwg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2caoxsfmn.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izonfwoa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbubgaui.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gt2dyoinenf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gt2xzzeqxhs.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfeewnko.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gt2hikgmdkk.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gt2ftscjmxm.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dutrtcwv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2kweiykvv.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gt2etdrxlyn.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2uuasjamv.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2qxbhknrp.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2jadsclss.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2zhnyyxbo.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2lkvhvhzi.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2kcmheehq.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gt2atvxmjys.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2rpleszao.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2vteiqpyt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2wnkegipd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2bjhrgoew.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2getgzimg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gt2vmihrfvq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2ntfaknxn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxmzjbjz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2srqvqvgn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gt2sitzxomn.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2qpbhvbxe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gt2ohbyolia.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkcxqrox.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gt2dozwbocp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2lnjkvklk.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2kiyhngoy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gt2uzfanngc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2hmiyvydn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2mdjiwznw.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2kicraurm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtphhfq.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gt2ouhzlsph.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2kcegpwpc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2cdeztcwj.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2ohzjhahr.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2orotzomw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2ighupcky.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2aedhtdxb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2uugyecnj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2cveludbr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2vjdzsqpj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2oldivbug.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2aqwubbrr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbcxitgd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paczglmw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fojdydxt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwkzlsmy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zohmdtjz.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gt2qapbxzhg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nynfbveh.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gt2zozmcamg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2dulbviwd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gt2bwwoatdb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gt2wqwbdhyz.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzjbjjno.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gt2tvakskpw.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2dklhpgtc.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2sllprfop.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gt2pvxfruml.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gt2cstqjbwx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gt2jgfxlkbb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2euqnwyhe.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2fikyzmpz.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gt2zefxstyf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gt2hwrcjgft.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gt2qnfnjwvo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gt2uqnoinrb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmyuvcbv.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gt2jyahrfyf.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2altitlod.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gt2pelwrtbx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2xwtdkhxz.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fguradre.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2ktuwelbo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2whffhvgh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gt2pvianmoj.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2caxlhztn.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2mrzuoleh.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gt2larxynfi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhgzbeen.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2vqpzphzg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2sgouomch.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2shmvglzz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gt2yucxmuzy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gt2zkuqtksq.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2okwocuvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gt2qfqloyqw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gt2mdfillrm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gt2opwqyflb.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2vviabzjp.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2qoacbnjw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gt2omalolfd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gt2lxehlbwg.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2reonrwbr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gt2hfthdvco.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gt2efqsxwmu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gt2exygftws.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gt2cixmkkuy.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2wmmeqnrn.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2hmjvrveo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gt2vsgslpjs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gt2tvtbhigs.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gt2myqirmpr.html


<!-- 参考信息 -->