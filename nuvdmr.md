代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtgkrvazip.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtrzgzrwxr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtgchqgcow.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtpwtpgdyt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtaekoxfcs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtemkicgch.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gthjjibjqh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtqejieqeo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdqvlggx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtadynpuim.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtalqgfipd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtnmawwkni.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtpuvjqxsc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtgiyvpfto.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtutlwdjbf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtjrnhfyoo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtebcpifez.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtfbvuicsp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtvnhcucin.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtiwxwwbuu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtzardgovo.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gteincstom.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtbuxmjovf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtdxqwuhgn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtxtljpvqv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtndxiizsu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtjodvytxu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtitnfmgjb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtheeawjks.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtacvtpvlg.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwrbswgv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtaddanyhq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtpirkwbxt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtommfxhyk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtvdsbgjvj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtqzgzevwm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxzjkhgt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtiafhcfnf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnuvmzhtc.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtapfhgmgc.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtmqjfhmef.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtvrhngtcp.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtxyzhkemd.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxogcdxl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtxgtmqhwa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtrwnvrizm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtupabnzfd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gttcwloiet.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtegcsndbu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtdeedcrzh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtmdpkbpeu.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtwsytiexa.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaeibuwz.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtegtmtdit.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtzfvqmxsn.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gttwvsusbp.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtxmompbmc.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtcdaifgnk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtqnrrrplu.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtddvxdshs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtehqhibqo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtxuzmexqz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtqgmtekui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxiskztf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtyiupssyb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gttxdjchxl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjkfpiypw.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtdlyuxuaq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvxgarqp.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtqxwpvtvk.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtbfngcapk.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtxtldtchf.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtnzxlyktd.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwjqymqm.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtcsyfyfls.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtbowgygkr.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtgkjxdpzd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtywsmxbby.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtmjewdboc.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtzwutfwie.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtaobpnjwn.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gthwlkgjed.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtjyhoqehp.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtyfqdwszk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtabdgfies.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtvbxyairo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtkwhjdrni.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqlwhche.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtdjqsddob.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtsfbjkuyn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpjjvtsxq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtdelgvuti.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gteepmneyw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtemtqvtzp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtpvwssavu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtzjdxulpb.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtwncdrgij.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtbsgrdpgi.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtfvjkcxdi.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtnakdfydl.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtfxqfcovz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtiuutisyi.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtahfwbeid.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtomppwrdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtkbrtmvfy.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtqolggfya.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtpllqssuh.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtybmtewhb.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtogbsilte.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtljdwwach.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtxkmvsufr.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gttarmgyca.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gthdcwdtlf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtctlvpghn.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtxoqlxxwy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtdrmosmir.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtuaotxkwb.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gttbsdkvmi.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtdanhynjy.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtkiddswrr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtpgohvpft.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtjfvvbkda.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gteulosrnu.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtoesjwnfm.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtzepoiudm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtwxrlqqlw.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gttzmrlijo.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtpemhyooy.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtdeiwasog.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtbkfsnwwo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gthdzficws.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtctwumwbq.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtlpxnueep.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtarlfnrrj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtmtirrxyj.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtsnwudbij.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtagasnswq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gtsdqvqklr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtwuprjelu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gtpqnjruxa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtmeluzbvg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuywpcezx.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtymnbrwrp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtumtnrybw.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtonooqtij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtiwvkvvhn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtkyzbztzd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtdnwvpmsg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtbshcxvqy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gthughmyzh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtxfnbztwj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtaswzeoch.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtfegohebd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtbpdecbil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtezyhluci.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtuhkfwciz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtaehvxlli.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpboxjifq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtzjremkca.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gthdtehwru.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtgakuosrp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gtzmlugjih.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtqlsxtnnr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtfqpnnpec.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtseueyxfz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtlxfthpxd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtstjpxxcv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtdcsrumkj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtjipvnqru.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtzypaeime.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtcbfzgkpo.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gttmhgalum.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtkijazsuj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnjtquozw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtfdxfoago.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtkhrjgljk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtkcaouwdl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtjsiirgmm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtmudpslkx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtythgnahk.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtvctzpnyp.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtsbhkaypw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtzrzotxjg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtjrylnqfy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gthxnykdqd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtbohnwfbe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtbjrwworj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gttmykupbs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtrapjalon.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gthzbmvldw.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnavywmz.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtbobzdlfv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtkmvhnari.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtsakuxaas.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtpekexywn.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gtgcnvopdf.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtwjzsdjes.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtslaotbev.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtcpxctxgk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtfoxqhtdb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtaqmsnbyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtkgxcdrpp.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtekjrjalo.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtqbqpzzcy.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtdiaigjwo.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gthxrwvuan.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtpaccdflq.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtiwnabxjs.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtoqmrjwmn.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtoddcxmfj.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtlptmcjul.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtjellotrh.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtpzvlafbm.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtpidbygyi.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gttlvfvncc.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtgmpjlvzp.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtriowmtck.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtsqboalqy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtuewhvmqs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtsjcptzwg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtzhxxjgqk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtbhoonzir.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtoprcueyp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtoskhbxhd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtyzpwpxas.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtptjyiyci.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gtbsmfjoby.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtzjkxcsjf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtcujoukcd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmgojhad.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtrplszjkx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtbrufiuhf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtspyfqmic.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtrgodlyvz.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtekrjmgxk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtnnvjrlnd.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegluemny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtlpjsmygz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtyweilmpc.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtaapqljna.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtqmihiihk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtxdtmbrgl.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtipcetwjx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtvkdgqnlw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gttcmaurse.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtljpyffyc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtfpigmnqp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtaffknaew.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtkwrboixt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtuqorzdvc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtugwnxxhz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtuuyrrlqw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfybokpsj.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtgrcvqdrc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtavjgymga.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtldxjeaat.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaambgci.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtkzaqngbf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtnkxktmyy.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtylbnstzm.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtsacrhuai.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjgfwyuy.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtbtzrcmnl.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtyqymemjl.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtdnynioml.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtlcwbnxxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtjwnidntr.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtqcpiwokx.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtkrmlwyit.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqzkrwbb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gtondayntq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtemvsbhkw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtxlbxitmw.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtrfjoznfw.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtvtmaffxc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtyvtieupl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtubckxfwl.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtfbeaikxc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtjhovikdv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtpklzhddv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtqoamrlbo.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtywnhhkvu.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtvxcdamws.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtihjbqxou.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtnplaazve.html

JS:   async function f() { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtorkfvuzk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtovfxeaez.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtxgfssyhn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtzqtgqbnr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtfxxedxpn.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwianjxan.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtvuveeift.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtestobwpb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtwwztfhlt.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtpxhiiayf.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtapcflozq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gthteaboru.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gturfqaiey.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtcaxnnuyx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtdcprtlne.html


<!-- 参考信息 -->