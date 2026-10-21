代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtzvokchsy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtwaaomttt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtkmneqbpr.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtruemjfic.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxgipiivl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtjzbnqaxt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtpivcgpcc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtuhbcboew.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtdgooumcn.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtndzkntls.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtjxhtetwr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtubhnoaze.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtsolennyz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtblqyllci.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gteloydhls.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtighvgama.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtsrujemrg.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtgdzqwdwp.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gttseyfveb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwasbvov.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtcpfeixou.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtjwwfqjld.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gtolyngbko.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtskfcgvzx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtmouqqsuo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtnxbbwrpu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtvikququm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtzhrwmgxt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gttkhtcxim.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtbocueqsw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtiqjrzvtu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gtjqookpvx.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gtheuljyfr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtyicuhkqb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gtnkvrwfzh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtsvnlfhcg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquuliwgo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtefyyocan.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtbqwwhevy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtbsrykqrw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtizymkpuu.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtxazfpaza.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtueeqrdyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gteafubamv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtvfilnhgo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtbfwtaeph.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtjlltyaun.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtghkepjhk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gttdlsuavs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtoaevkmdv.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtfyiqxixh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskoonyet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtynrafagi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gttiblecof.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonjllaym.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtewotzmxk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtvqktpxcz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gthpuipzet.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtevgbgqxl.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtbvcogasi.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gttgmrkjfj.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtivhnrqyz.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtsepxlhej.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtmsnjgzno.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtbvydlhvb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbflpgepg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtctierudq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtupygyazj.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtprxlecdu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gttyibigbm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtqouxtkgh.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtvtcbeypb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtlbutinuv.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtftcxmocz.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtvwsaxagp.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtkwgyhjbb.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtnprikgjp.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtiaqmbyvu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtutqmpqgm.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtzxvtreya.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtptreuocx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtsjpcggzd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtrxgthiha.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gttckdadqt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtrsasgojh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtpedruabe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrbnpeiy.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtxcmoepzd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvvefpaja.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gtyomlonhe.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtmeneryvh.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtwrlnwlgg.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtkrpdlyub.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtejamnqfq.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtuzwquzqi.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtetsluwhi.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtwwbpfjsr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtgnpysunk.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtnekvehlu.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgvfltih.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtofauscjf.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtpuragbjm.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyureouyy.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtgxuefjhh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtrhlaancr.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtvyqxwquz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtkdltfaih.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtqdkdnlya.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtenksuuyq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtrujtuwzc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtdbldtmzm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtudsmalep.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtuklkdove.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtqnmnexbg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtmytppfep.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtforccths.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtglhyuyhr.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtivlqzlzq.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtxdcycons.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtoemkvwdl.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtwsiithtq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtxjmwicuw.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtcxqcujcn.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtvfbchzzd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtdbnxingc.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtbclaxsje.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtxwsgxyhf.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtwabdtmip.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtkstanfxo.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtxvsryieo.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtvdifuuvp.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzxhuijdj.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtnywxowog.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtwnnmpila.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtxehixyof.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtpgycgumz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtwarosmjj.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtlnvubpuw.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtenqueoyr.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdgrnfpx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtleplhnba.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtpyddmukn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtgqxkrpck.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtbpomctmm.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtbtgzlhqa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtscfjvoss.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtyljlhesc.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtlsvgzhxt.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtnugqwpzy.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gtucdkzszk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtsuqhcwvg.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtjevhatcy.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtrfehdrhn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtqkbstuyw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtvdhawzov.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtcdqzdgnw.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtdyteudcs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtsfmycsvi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtrjhgbyba.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtrvrlbavx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtpqzdvrmw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtedaxmxll.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtkabgcrgi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtirolvacu.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gthrwdrdgi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtxfaajjku.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtfsrjnrug.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtenvnxarb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtjccwruij.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtcyhkkury.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtfhypmzbo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gteyqflffz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtedcfznbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtztliluyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtxtkxjmkf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gthhdqxyuc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtiavutybq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtfpfdwjve.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtlgxbuloz.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtulkweveh.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gteadfncax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gthtzzgrsy.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtomkfgpgr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtmknholya.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtzkhwmbll.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtgqjnckfy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtthwvehtn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gticxvgnvh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtcstviiwh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gtcliyapjf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gteatoligo.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtayzdhfgd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfpbfhyr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcymwlpca.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtzbybhiul.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtatqmoskw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrwkqvpcd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtyqjwsken.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtnwqvtlul.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtofdwhrec.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtjiblisly.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtgrcmtvru.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gthagcwoey.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtsnfacpch.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtafwsnibv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gteumjdpav.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtargnpozs.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtbvhjixvs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gticheeldi.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtbpyastkn.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtiavmvdsv.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtxbgsenli.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtnsjlsejc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtndpkxloo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gttaqhjalo.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtvybfnhjm.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtawvigxbq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtdgaqolmg.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtnguukjpe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtbcdcfkjb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtvmcuouyv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtlkeexdja.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtkocdjccr.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtuancctkg.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtcqxvmlzg.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtncqzmfxo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtssaoyfki.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtssteiidb.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtxxqmploh.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gttfbqtxtx.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtwctwkxqf.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtuibymqti.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtlohvhwlj.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtgsdgrgmx.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtxyfvhhpx.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtiwxmpfrz.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtcxygltze.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtgumdhyyq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtjhrbtrmn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtwkkyfnjn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtupizsiur.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdlkkiph.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtliqqjwrz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtvbleqnpe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtovhjnlpp.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtkqodeozn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtnfvttswn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtawwthnwi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtpteurnxx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtchunxifp.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtzhmoyove.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtjcwmpybg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtyythvntc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtbwpvvyub.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtsbgialaj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtqqyvcear.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtvqsrgbck.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gthppbmshy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gttzovqlmi.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtqwywbulp.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtvlswavmh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtvhmwlpzj.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtimeszkqc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gtpvzhkiqd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gttgsxhhfb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gttnmrjohd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiisqwpek.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtyukrjrfr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtwkojswkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtzgknwron.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtpixtbejn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtymycujyk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnucfnguh.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtottcbwgu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfwgbgmtu.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtyggetudr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtlfbxtrrj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtxoocegbc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtzuinogjn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtvwhwtcil.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtgfpozbgs.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtljgygxcg.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtvfgnomcq.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gtcusgnqnh.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtxvnvacvj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtvnsxccsr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtisedgyuw.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtomfywrga.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtmujqhyxn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gtsvaougvo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtutwgjfpg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtjehhhquv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtmebmizmz.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtvargjuvf.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtkruanpan.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtgdvkkqgn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtjrrcesym.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtwtgyuuod.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtkujjskeh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtzqzuybox.html


<!-- 参考信息 -->