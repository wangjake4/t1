代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtktaxhhxf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtnbrqmscb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtuzceyhob.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtpapntnvl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtxisiqikk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtqznmtigi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtnxhwtxcq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gthsikrthk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gthnhcuxsa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtvobrfwwc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtexdtkfao.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtjmkfeyax.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtcaxvtzqx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtxvusdskj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtyffvzpew.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtsmpmekow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtwjkzmxeg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtvhyttmjk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtlrdmbone.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtascvjhyi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtvlzlqwph.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtzzwaijmo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtjieyruni.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtowxjiplv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtganieutp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtkpykzwcy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtnwngxwsu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtwaaawygb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gtbdugcrby.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtlrghvhwm.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtzfgnqfsj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtioepzmlf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtnhlkuiih.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtmooucsit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtheywlpny.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtnsmyvsxa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtewnhorly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtxpnnkquy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtkpmvbhdg.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtpaofnojj.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtaryfvinh.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtzfitgqer.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtckleozmr.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtfgpxipfp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gttanycxvf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtfhdzrpic.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtnlmxktan.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtywootnge.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtqhlcywqj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtqwtiylzw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtymlkpgxt.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtbbfqxrys.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtyhcbhsjx.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtfmnqclmf.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtgjuouotm.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtdqtbolcg.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtchbstetu.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtivmtymos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gthwtstbmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtzgtywvmi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtqfltsnzh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtamjdplld.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtsaitkmke.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtswbudvhe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtiwfomrwb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtlxtuprph.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkwglsbqy.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtooaxdcmn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvjpfzdqp.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtsyjdcpgd.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gthikimwje.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtpskyyqwi.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtoytalzkp.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtxmgqpari.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjrndpyr.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtyipekmsa.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtmcohtgah.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtzvculekb.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtsctsekpd.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtrzdylbzh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtplxuzk.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtnlcvrcjw.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtvmvywvtx.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtsmfuvrgm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtjxgrnflw.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtcwbadowz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gttxmqkmuy.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtviimpmph.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtbfdqusef.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtewdfipkd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtqzzngcrq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtnbgvxhly.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtykawwfav.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtoeepyshc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtzvvzroix.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtxqihjjne.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccnczydb.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gttbntvfls.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtdvdoijhs.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtdnrabvdj.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtscvsqmux.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gthzqzuglj.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtgpkoahxi.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtnvhjisvj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtvuugtcor.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtvwuxthgr.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gthbyzaamo.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyyqtmma.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtqqblvzij.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjgeinouy.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvzyxqvo.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtnyigiiyh.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gthevdwivy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gteukeolck.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtureoaxzu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtximbswel.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtldvvando.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtnxrurxyr.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtqzitbgoj.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtezwsfujs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gttzdetglx.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtbhompjmg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtzgnezijl.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtqwyqkyuc.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gthbfuqdco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtrsankfws.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtuttxkpqs.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtfvmjngus.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtoyzkfatu.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gtldnzmgvm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gtqmmytdkn.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtzrwycwlv.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtiqanwqxj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtrqymzmyi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtqjxpowcw.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gthevrczjh.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtpmfynucs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtwabepizr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtqqclfreh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxxhgfny.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtlzhckglh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfdefnfgt.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtkoqukdrm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmimssohj.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gtgnqwwano.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtkvznixdl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtsdocuvbl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtavtiqilz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gthlyahtut.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtxswdwari.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtgjeadehq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyuhrpcb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtzznqnard.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtfonfhjce.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtkobysczf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtwzcxjhnm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtpflkhpku.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtaphvrvyo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtuquhsxts.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gthqwvmcsn.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtfdyofhxl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gteuwtkvtw.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtdmubsxur.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtrgolgqqo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtpveteifi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtghshupvd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtuvvkdgfj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtubtgyhhe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtjflwsjhf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtqirdashi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtmfsnhmtv.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtecvrnlmo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtfwgbgczq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtefvyrvjs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtowrqvxka.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtbqylqetf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakjlgaec.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtodrzqxbh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gthmxcwuch.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtfvynapsr.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtvjosmhus.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukmcyxiy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtcgslastn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdmnkgmgo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtkghmvair.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtgyycvndu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtwmmiiefz.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gttjycgrlg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtgqhbccmi.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtjyhqgoxq.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtsepdkavw.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtphqgfrhh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtphqzmngv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtszxwnwry.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtyinbpven.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtfqoxpcwr.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtorfbpdno.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkrnunqi.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtynupzgmr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtxzacunak.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtwuctwtfz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtixcvkota.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gtspecpdyt.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtfdjfihfs.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtynbnyjmf.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gthhslkera.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtvtdycuhv.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtjjhcmhvk.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtshewhlmq.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtrcbsomiz.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtpeaxutna.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gttamwqgbo.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtucjlofvg.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gteuwwqxxe.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtmqhfkwlz.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtfxyjtqjt.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtezhiegkd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtjclytfsu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtigliynnd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtonfpjdax.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtrxxpzwiy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtyzfwjbaa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtbmkadvtk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtrmdyvpps.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtjhakkxkx.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtftfocjbn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtsiglmmsp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtkeywsssq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtgdbjtmei.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gthkzrsuvn.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtyjoouflv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtokrpqvvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtzuvigpwc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtrsjetzye.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtsplvajbf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtcfafgtxn.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtgysromxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtlctjtfah.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtfuxelvmp.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtglqjhboo.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtquxmgtxv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtybyrmqvq.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtooooidff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtdwyhinqz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtasmthfys.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gthljsyxbh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtzvntmzgy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtygabbldd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtkdpydfod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvplnwqp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtandraqbl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtwptpsqlu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtctcurchw.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtitgdiqlz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoonttpwx.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtjkyvgswz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gtqcgizeab.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtmkmtzm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gthzvmdhat.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtctkdmnzw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtkohbxhjf.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtwcmpsijx.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtzebcvkmi.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtpekviwej.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gthitrcmlk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtdwoxniir.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gtqnoteuje.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtyikhwatn.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtqszuweee.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gtufoecbim.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gttutmvycc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtdkalyakp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtqavwdrgc.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtllkttwuy.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtvnrgdvze.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtrpeaczut.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gthxgcjrbq.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtzoyrdzom.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtpcptvfgy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtjrgbload.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtmvhlgkwj.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtrjmiusou.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtistrzfhq.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtemmvnxsh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtxvkgzxad.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtpphfiuyu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtelksdjop.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtelunegpz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtgyqoznqu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gttcrokghj.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtlvqkwumb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtqjapibbk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtblklkyax.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtcakpyzej.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtgusgrqap.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtuvuwqwep.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtytkzgnrs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gttawihivx.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtevyoudee.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtqjtsdvuv.html


<!-- 参考信息 -->