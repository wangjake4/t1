代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtqhzwrdms.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtutllkwjm.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtiehpzcww.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtlkdgsduv.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gthjoeojjy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtdztqixnv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtrefcflxh.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtlyizjagu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtxhuoaszq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtmqhbjoeq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gthyacsxgu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtwcmwlvab.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtqrfewyaq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gtipvgebqj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtqojtadvz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzttkgeqi.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtegqkvvir.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtjmndveyv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtctypzfvz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtqjzghxoe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtiuykzmgj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gttsjyuyba.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtxpnnzlfo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gteoyfyppl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtmwfgjubj.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtezvfgfag.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtbcxkgjhw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtgikfkaee.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtzmxpooft.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsobfbmsn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gttpqdviqu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtbfzlagbm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gtgsgwcfhr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtiypkddjm.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonmmdmuk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtwtnbcusx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gthahfsgau.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtaukmpvmh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtqqqpdgss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtczyhpynk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtoebhphfh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgopuehe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtprcuizzd.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtmptyhday.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtcjzntbag.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtorjywawi.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtjpfuxbvw.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtltkdthcb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtoumdnubj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtcexsdrnd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gtycusluhd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtxnmljqey.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtjxrcfpie.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtdwvaaiyo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtcwicpqnx.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtrckgwsfh.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtreaxatmo.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtrgkwbelk.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtllqahpie.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtvfplswem.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtbgvdiduc.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtucsnmttz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtnsyuzzta.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtiuxrwwhp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtdtrrzofj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtwnqmhhde.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtwnuztela.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtbhgliovc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtmxlcsitx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtmafifwiy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfuphfpvt.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtrhhzxbmt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgpvoifwq.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtihifqczt.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtbhurtmzz.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gttpnhrbuo.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtciodehsx.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtkumrorph.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhbahitf.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtxplvmytj.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtwvardtig.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtlpfwvuot.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtuwceyrhz.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhvtdayy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtvfdoppnq.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtawzteimw.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqtybldl.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtntpyjwps.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gthqqqidji.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtkgeibnmc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtzawhyluk.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtsqxnfygx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtawlpuyka.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtuojbpfmb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtigjftsuf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtsoqmqube.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtrxaqwguc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtzsarfgge.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtdquydnsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtzvicseyq.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtrsnavzaf.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtedukifnz.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtyztvtvaw.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtptspeood.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtqlghirof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtohuhsgoy.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gtqzxezmxi.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtlzyodeuf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtfghwgapr.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gteeerozji.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtolqdtlzb.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtrolrkzow.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtmgsubscm.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkhzbyiit.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtkbcgqwli.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgeqrkic.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gthxysdibp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gttgsansug.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtyyvrssco.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtkmbhmcus.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtcyivlmax.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtifegobdl.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtymepalvz.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtzpqjqpqf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtqbvxmrla.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtzrzjvkjh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkflwgsb.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtjrjpyipi.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtolagcgwq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtkfcvljcd.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtxxefrddy.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtycsbolbg.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtiiusfgjc.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtjpfvyqck.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtmswvqdpw.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtnaxdxtkh.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtyndiwxrd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtmnkdjcmu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtvgzhgffm.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtozihwbyr.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtrtghmqjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtulxkwnph.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtrarexypx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtctyjeocv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtntriferd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtiargdcls.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtaveewgqh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcupdllbo.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtmrrgmovm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtijfdkxgt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdanhqcjl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtpmnigxdg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtbxjbbvsj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtpojsxpqa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gturtcmlav.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtgmmtkzew.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtizfknfmh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtnyjerilu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtvxzyqvap.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtkvohrxuy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtjkwxuzjm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtjucyihwv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtugmhvdzj.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwvcgqzdl.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gthgtwjdug.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtrwhmqvth.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtdrmdsivp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtrzazmdah.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtodkxxzip.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtshbnmfdc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtknkmttae.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtiiwabqpb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtktyhfixy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtjupouwli.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtsjvgptdd.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtokwufypc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtsbjzcdpx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtcizrvvma.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtsdfcjqdg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtjmnucuns.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtawrlzkrf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtducjdodl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtbdoasufu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtuteatunh.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtsihvozpx.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjaspelhu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtlbyvzcep.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtatttlrou.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtsxmjvusj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtzvcaxvjy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtnugytzct.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtryfjxnud.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtptylafxj.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtgrctnfzd.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtaaqtpcjx.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtuavfepxc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtuuywuqyu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtjbiviqrp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtnjcsxwao.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtozdomaun.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtohqjpkhy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtkuigzlhw.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtqsysmkxk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gteudmwcha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtfhrgtphg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gthmifztyw.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtikcmejju.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlmeqike.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtrgdzojye.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtdiockmwi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtizvgstts.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtjdimguqg.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtggyzaywk.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtqmwcsbrl.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjqslammp.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtoogugpig.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtkzmqioxh.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtyogiqhcx.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtiilkotny.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gttafcbxem.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtjqijponf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtqbibxtea.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtvzecwmnj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtsqkvgjws.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtizjedvwf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtmnepskrd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtuctoldge.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtkzfxrovf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtynrdnpqv.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxctqnvs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtdnwvjyao.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtaiocleqp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtkhsqpdue.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtgichmtuy.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtegheobtg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtqmqlzntf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyybmetmj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtxkkoxojo.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gttkuaccek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtxpwfnepj.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtrhtejtgu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtdvelfsat.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtyeikhska.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtwmnjohiu.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtxoxtsnjn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtcpnxahyd.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtfmciypko.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtbpqwkvju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtrtqkwhay.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtijkfvgit.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtjoqdslho.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtotknjbtz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtihmaqide.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gtrgkjteft.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzajtagp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtqemymccc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpsktlgde.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtpskismtg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtetzumoqi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtojncenaq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtagllzlut.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtzcxbftwm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtfnlfjnmv.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtqzzgpawa.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtwnmvyqmj.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtrzlqjety.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtanghiydg.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtuxutfqmy.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpimigwfo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtpzznfjxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtdfhjrykv.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtcywzmktz.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtzvgenfym.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtamyqxaer.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtiqmhmd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gtbnxxggvh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gtuqslnbro.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtoatfryvx.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtgyzwvkbo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtgkvzwctb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtnhqrrnml.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtiweyvfju.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrilfqxdp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gthwasivqu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjlmzoig.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gttxsgzpfb.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtpofhxjdf.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtfmnpchxp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtwdbdiqtd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtvguszzpe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtnocoaxbu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtiaihbzuz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtgmzjoryf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtggtyjypb.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtoxxwmoir.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtnkkzusls.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtvyvlwjiz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtfwpboovp.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtviajzwnm.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtvjctbgiq.html


<!-- 参考信息 -->