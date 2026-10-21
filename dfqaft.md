代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtmwwpnppo.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtqnabjlni.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtjelxcdbh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtcokmttgq.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtxjnfmpgk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gthyvqprtm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkkzcjjj.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtwrdonkvz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtptusznjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtxdopsdpn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtujburiez.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtgkjgiqsd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxpzetxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtazlbhoss.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtdjtydfoj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gttolcqocv.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtahxlrzij.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtymijztvi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtbvjtsaqv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjvaumgp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtvzmfbkcq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gtzbustfxy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtecfercnr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtajxkgmho.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtryirnduq.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtlqyrvmtp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtzohkksrp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtwvhrsepj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtwzrewisd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtberqzbwh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtbtvyhivv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtmboeragz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsundwlvm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtfjqcjpjj.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtbmdqyohj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtgybmarpp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtsvcpcrpm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtwdqheiye.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtnzjehhty.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtjsgffemp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtdbvwlgij.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtzqhazpiw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtvpzzmvpc.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtytayhzmm.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtqervquqf.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtivapouko.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvdsdqey.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gthjodvybv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfphvkwgb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gthwcqoaif.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gttdzfpeyp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtgyknjlgn.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtwjbonwah.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtsxxjgnpm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtjeuqtubn.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtdgttsnpp.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtixxhosde.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtogveihzb.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtijeslxbv.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gttecxbaog.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gthkndmayt.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtdvwtnang.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtwmryrusj.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtpulirofz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtxaxbtowu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtrdqkplzc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtyzigxuew.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtduufmmqp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtgovakrkg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtuvgayqgn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtijkexghx.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtoymasuwk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsgimbjlw.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjahfoiui.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtkkgeesgt.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtrqxnitgl.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtskrfjeyu.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gthjqglrzy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtvsgzlhjo.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtoopddkoi.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtubgwywot.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtukbwlddu.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtbmoymzfu.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtcfiyzzef.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtqgfjjjko.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypmjjaly.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtzhyygphn.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtczparfmp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtidsxekxq.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtossdasna.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtptlfyxnq.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtddvdxrny.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugejviik.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtnuuwbcqi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtzbrpmcfp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtbckjqsmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtzkeplvzu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtefstezje.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtltzrdgim.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtwzsljrhx.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtlabsazdr.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtkvvlxjlp.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtnkifyyab.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtnjyotvnm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gttjekibxd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtknfdbjsl.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtlxpamkbg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtucygqswy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtbjpztggx.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtnfgeprtf.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtradpoprt.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtmskmohbv.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtwsyrluti.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtjqknfbvm.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtzxbjkopl.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtznkwzfws.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtokoxcjse.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtxnriqqxq.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtzmqvohqt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtxljclamu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtcbthrgzp.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtcerdbcbd.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtzollfsrz.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtxroqxykp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtlinaqxhb.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtvaljzsqb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtgvzlcoxl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtwdgurgll.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtdvgsnxle.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtprxjrjon.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtzzoxvouh.html

TS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtfttylizq.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtllguoeri.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtclvdwdnn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtkhknwjfb.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtldzbwrvk.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtdbksatjn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtmgtdvxgm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtwzeiwrxg.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtwokhjnyk.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtinksivru.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gttjmwdiwh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtsjorloov.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtnehocewn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtzjthgltw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkiitawiy.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtqvvyfypp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpzoxdfjn.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gtqwwfbszc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtrhtmccar.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtopobiygz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtdoqfdgfq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtawcvwvyc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtfilsacpg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gteprzutal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtzuibdobv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtzpnyggaf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtmyuxzjai.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtexeuqanw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtfsrjlsll.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtoyyrahlp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtmfvbutwy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifhszoek.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtcpeaarpk.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtpykjvliw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtyxcgbopw.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtdppxpzwo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtdbggqsqp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtyfvrtjep.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gthffeqqhe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gteakgapqf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtwggmwfbl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhkewhax.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtsrvczibn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtdhmlpotk.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtwhkuadxs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtmcihbqlt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtdelunccz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtvkslpsrp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtlwaygfvl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtwjkhixyx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtwlzajpej.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhptawjo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtqmeleqmq.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtfmdkfemi.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gthythwmgg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtwvfcvohl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtigmjgfzq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtmycsfipy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtnzxepxif.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtvhuzjhwl.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtzttkxllb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gttsbfrndm.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtnvgrdvqx.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtmcwbqxwe.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtbaxeeifg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtotzapjwb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtdgqybtcg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gtalzlulfa.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtmxjmuyrn.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtiinhdmfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtqgkyplqk.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtobqbkoth.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtufuesinh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtlcsrcikh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtqzcrfwqb.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtkhccgkxh.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtxdrobddj.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gthzkkctap.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtxihquxjb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtpijzhbqt.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gthyfitmgh.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gttqwqxhxy.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtrhhdfipv.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtvcnahwvx.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtkdnluhxp.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtjwbsseqq.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtjjuqexzk.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtejqeibnn.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtgbyzglmg.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtxvqggnmp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtlrcdtdma.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbjmpwag.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtnmrzcjar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtxiyqoepp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtxnfskjhs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gttykmsumc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtukpbxhbv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjvwocym.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtcmigoekk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtulbftywf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gthxybrxnk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gthayxhkso.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtnxvkrjcy.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtgmsafolc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtbpbqjwxq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtnkdxycmv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvczjgdps.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtkfxrhyne.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtuyakojye.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gthrjhsoes.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtwsxivwcg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtpqqkijzd.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtytwiobgl.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtwfhfiaor.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtofplwxhm.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtoaalowmj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gturhielfm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtprvznazz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtidkcxobc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtytovpsqc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtebltthkv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtxmbqibfj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtjjgvjclh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtrxpbnqoe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtpwseofoo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnegusbtm.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtfireamex.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsrbrqaoi.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtrogafwre.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gtaugnurzm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtckgofobm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtjmyppugv.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtcsgfobca.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtbwfexlcc.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gtaoorgdsz.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtwcgtcaww.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtmqqyfjxa.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtpdqjfijd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtqrtwgeyq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtmzcjajij.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtvdvnoewu.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtbazbgovo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtcxfnvwkb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtpnhhgwfm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtzoybdlkh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtspketwqs.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfaewflb.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtifotkslw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtnmnesosa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gtntyrbdza.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtzoaluaev.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtvarvejaa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtnohnajxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtehhvifzq.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtyxyjwums.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtxzyffsjh.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gtmzwalduq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtlrbzorzs.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtngtioxuk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtazgumatu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtbxkcidvt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtjapqulcq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtqjdgkigt.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtjztairya.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gttlnbfmth.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtmgmdtjee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gttzywpbbw.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtoozxneow.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtamowuvoi.html


<!-- 参考信息 -->