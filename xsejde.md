代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gttrfjhwah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtyszzlmyj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtghljnuyv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtznrrlnhf.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gtetuwfvae.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxynwtkfm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gterklhlij.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvvsqdjsq.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtxtvpuuyr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttgbkwmoh.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gttdzqwkwy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtovfubbjj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtkwzdimqv.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvrjhcrm.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtmeqkjqrz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtefkvczzl.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtbqbvxavi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtcpjxpsmq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gttndvnuey.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtvapkbwwl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtovjmaezv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtnauvdiqb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtctqgdmdi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtshqrwctt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtqvmshjju.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtovkldevq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtadaesbsv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtsvczrnyq.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtmzaugoje.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtwazaabos.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtxtlcrzau.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtvygryayv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtpydzygro.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtfjpqdtcy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtvpmwrwjl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gttukxtyeh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtofwatgrm.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtbjthpsvp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtvdmqwlqc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtndohhdjq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtncpjqjnk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtiihymuvz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gthiqbhuxu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gtsdgbfkjx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gttxilmxlv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtliglccap.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtxgynxlhd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtzecaiers.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtwobuoggj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtzpffzegl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtfhkkebxi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtecoesnwx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtapdnpriq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtmzromclx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtrpvnbumx.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtwzbmcpyi.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtzndtqgjw.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkmlorfu.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gttdurotmm.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtzgaqdoul.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtojycbkbf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtjdsryvrz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtblvravat.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtfzpdctqg.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzsdcdvh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtdrgqygub.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gttsqvlryt.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtflkpnwhc.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtwlbsdile.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gthxccedlk.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtscrlhgro.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtzcuummul.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtowoybfml.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtdccskncy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtiqffljjg.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtwtckcuir.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtmolucvnu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtynsnucxx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtbakfryew.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxveovtj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtkpuultfc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtvvwywvsw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlypgcghy.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtadbaxtml.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdriipxxt.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtzeknoize.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtquhlfgam.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtigvvpuej.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtartueiyn.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtveaxgiul.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gttmhvcfwy.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtppiyiafr.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtqhvilyue.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtyfcxsbtr.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtvvewwwyb.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtpgbuufel.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtxdzlfxgc.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtzkhgdubr.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtapnykxbc.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtvfcvsiks.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtfcbsbztw.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmncwggzb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gttljnwqlh.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gtaucmuvrb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtwcesaftl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtfdzuwvyc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtygfkiwwr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwyvmhsg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtxodizxhl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttykjotcx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtseivhezk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtujvwtclg.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtvglvbvqu.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtlnlxcabk.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtoupkuleh.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtcwqsjxlw.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtwrcjubwt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtmhpevczu.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtbqmukhra.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtyyslvhhj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtrpzajhvk.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtokfnkiwr.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkaoebthv.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtzqphkbmj.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtmpwglzli.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtlctrsfng.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtthtjysld.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gthgwaxpse.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtjohndpnd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gteqxuhuiv.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gttamowscp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtaqcaefhr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtemtnoczu.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gthycpaqsn.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtklmcbbpk.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gttffditrc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtiojothwl.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gttxszsupg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtrfjkxasu.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtepjtdrcw.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtmppypybv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtryedplny.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnymotfxg.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtymlvafak.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtknhkffgt.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtjtwbbhah.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtcnvupmru.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtpxuotlym.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtyobmwhtj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtrilszciz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtjwosthjc.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlzmbxfu.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtynqqgczi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtsubnicvq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtdpjumkvq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gticxedsod.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtfybwjdtb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbyxuhnex.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptbelquo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtknrxjwqs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtuesfqicm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtyzuxqlnd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtumsncrvo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtvdougvcx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtcrgpqvqw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnnpclcon.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtnwcqxynz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqozumgav.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdgerykw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtpjpzmdbf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtdjftsgwv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtdkejvlog.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtbjvopqcq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtiypqxcss.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtzwqzhxdx.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtmeykmzpe.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtcahbvdxv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gttujkwndu.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtjwyppdmv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuewljxjw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtgcrwweki.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtbmjfhzes.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtalyzlwlc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtqerqcdrm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtgkwrohkj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtcboforqf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtcxwuzlqz.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtcvhvopdd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtofuvunuq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtzlylowjb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gttepklmbt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzqlxwig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gteooujypf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtloenemum.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtzinsxzoi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtxhhrmizf.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtrjepvpnp.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtbzkrhbca.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtliylkfvq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtqnqojbet.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdhrsdvdj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gttxcuimmo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gtyjzuciiq.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtluvfcaxf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtzzfkqeaw.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtqbwemeko.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtbrsqcndy.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtuwdpffbq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtzboxocsb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtpwsnjmnp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtetbkuokr.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gthmlqhltc.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtjzuzvvfg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtmfignkjy.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfoziiah.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gthlzasmms.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtyedggjas.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtllbttlcp.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtqrhrdswx.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtfrvidrff.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtbfwkjktw.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtzqmgweho.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtrpeovuhb.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmerktiv.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtfftwcysc.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gthhggcakw.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtaqyptdye.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtihvincds.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtkrjdstlq.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtgoldsfxe.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gttczghrpe.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtnxebmnjs.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtqxldvmdt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtytwjkfnw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtlhjrcpsm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtprlmksws.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtbrnezkts.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtxhlllgtl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtgishcbhx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtxkvvwrzk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtqjrytxbh.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtppgyrdby.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtkkspksev.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpohyioi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtxjrzdmlc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtvpuaimcd.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtazsjfkud.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtnkafbdxh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gtecawdkxm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtcmrqfjrt.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gttryctzee.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtevbkoejk.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtsgaibacc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gttprzqpmm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtfjaelstc.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtjqesgliy.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gttjfogodr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvjmrvde.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtqcicmihb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtyrwiynpu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtoixmrdhi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gtgwltqsrw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtwgpkwlve.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtijusucde.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gthrtqivvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.vqdsnc.cn/Article/details/gtnzpcwgex.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtsyzpjwem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gttfdhdblv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjqdhviax.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtnzprkegz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnqzotftv.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gtsbyzdfdw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtbtkqpmcd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtkbgefjyz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtksfiypsx.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtzgzugktx.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtvcwhydaq.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gteldlhyiv.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtlswrpbyf.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtmbkzbfeu.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtqrfsgtkp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtdizcmxnm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtlkvttlqt.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gttqcwrhay.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtvobdxjxl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gteqmjzluu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtdnjnjgdf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtqhqzbwsm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebjlnwop.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtamcxayiv.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtnbvxaidt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtpeuapxdr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtbtrmwohy.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtnsqkcbii.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtpuxyetjg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtecbdfegy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtjmsrjitc.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtamvmqzsd.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtfxqyxgmm.html

Py:   async def f():⏎    await g()
来源：http://dali.smart0.xyz/Article/details/gtrfsizgnn.html


<!-- 参考信息 -->