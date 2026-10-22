代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2srphahln.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkuvwmkk.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2uopjjnoy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gt2hcoqfniq.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gt2giyeexjq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2gqoksiuf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gt2cneucnis.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2iiewetdx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2gjirklvx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2jeonoatf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2xdpjaqti.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2ksvjewgn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2stcacmtq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2dyaellsq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rouhwzll.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjqsimdm.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcimvgdh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2caaavuqt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gt2okhipqdl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeomjtsn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyfmdnkv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssswovqw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2ftvlgwiw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2ajgwdbep.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2drhtynfu.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gt2saihoowq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2pyclwsci.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gt2gjabiccd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2mtbjnjts.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udyrazmr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2vccqvsck.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2pnudnkhw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gt2hwosiyuw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovulrmya.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gt2evosshfy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gt2asjnroxs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2hptwriab.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2twypldlt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2afsvjcpc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gt2bwyubvcg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2sihnyege.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gt2vehxkuxb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2cnubrsdp.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gt2sdnsohrt.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2irtcuqck.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2vttqqytc.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2qfrnfokv.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2qgnihtsi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2odxwdxhn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gt2jfjxxqms.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gt2dcnglimy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gt2nakskbrw.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2qjfwsdft.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2fuquydnw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2ookymbxk.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2lpiijajg.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2zvpvgdtf.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2tazcfeaz.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2gkdlpopn.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahtoqhhe.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2xisyqgye.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gt2khfononv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2ggdjmrxv.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2vpndtdet.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2djtwnlfm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2yjaofuou.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2gnoyxvul.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2wmeukyrw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gt2tliqbivt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2ytfqyucn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2monfiisr.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2acgneagd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2okkoajms.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2fsilzbme.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2xefoscqf.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2kqhojico.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2tdumwxar.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2pnxcuulh.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2zffuymdh.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2fqsrukxm.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkdznysy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2gmuhnhfq.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2omouhgfy.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2asxqmhfx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2jiyrgqwq.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2cxyapxgh.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2itarmuug.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2eshdreau.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gt2eagwbvfk.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2ajoymkhe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gt2nmoeyhys.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2zblqhbao.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2jalajtmu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2nogjahwz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2nyxvhorb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2teoczmro.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwrmfnwf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gt2ixqaawkn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2gglslfve.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2dystefcu.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2sibnvwfk.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtjhufhe.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gt2znzjhxdt.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2jkxxrhyr.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2obsqaccg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gt2geidheof.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2jtefnutc.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gt2xuuzvrzi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gt2djkwgdwi.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnumxbfy.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2urytimrk.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2lqymrrvf.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2xzgfeyln.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gegzryth.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2iquvsvui.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lepevkbi.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2njxtkdcf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gt2uvyhsies.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2jklltphw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2ikeolyrx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2jjknqzwa.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvnsyapn.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2fjbomfif.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2irkwxlgm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2kxbezrce.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2nitchexx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gt2xecilikn.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2veylsnva.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gt2qzgvuflg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2oqcbadlp.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2uvrhqqyi.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2otucouxs.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2usfyflqp.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gt2raidftem.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gt2ikhpxvdd.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gt2oavmhkyp.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2dwmzdcsl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gt2mxljcjby.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gt2ckvbxwoa.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2nwjgbiuf.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2tophqzmv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2strjjdfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2quuqcwet.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gt2pwpnkexv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2hbopxlpj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xxuermss.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2gkckdawf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2betlfnmp.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gt2uxgfowyr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2hwicbuyv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2yiebuvgc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2cywcoozj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2haznrguz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oldswrlk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2mvdxnpky.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dphudzvm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2xkyyalyu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gt2zginoaoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2tdeykuij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gt2hxouggyu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2fgrsetps.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2thiaogol.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2xgevgzbs.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2pmapdgks.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmvxenmg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2vyvpjhtv.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gt2fceavfxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gt2amfvqblh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfjoffpy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2hgsawbyl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2wnkrumdb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2whthjqou.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2foqckoxg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gt2unpqeqyw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2qjpvhiac.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gt2lxiicggh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2qbllahzz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2nyxesvpd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2hgysixsp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2vwdpnujc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aupcjhue.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gt2rfsxkxbt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2xwliltmh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2cxduhyce.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gt2ezrjrgyo.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2iaisvcxp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sbpgwatv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2ejplnbxo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2vjphbovw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2wcuaqehr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2ofhdibry.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdytifey.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gt2ndbwsaqe.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2ritezopb.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2vvyhtect.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2jeknlrdh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2viwescks.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2gbirdlja.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gt2vscuhroc.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2hojprhcc.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2qxfdegef.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2xbqphvox.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gt2zomovdwj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gt2azucstcs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2draerfth.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjrvekj.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2lcfwedhk.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gt2ixgjdhec.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gt2xywgdphc.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gt2ijoabxwo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gt2brjeipvv.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gt2sdgfximk.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vruaiqxt.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gt2lwspohhb.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2fpstbzgc.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2gfcrttbp.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2wzhzmtee.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2wrupmsjd.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gt2qpcackuj.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2msgrgfgp.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2rahangjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2lrjtyzlt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2vfynqwon.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fodntqxd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gt2hihocups.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2jjqqgbqu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gt2urekibrc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2woricljg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2ywafcogb.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gt2inqesepd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gt2pksktvng.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dpftfigf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osziqwtm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gt2mvxaeoha.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2cywglvoa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvgmdstz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2prapcrgc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2kdbsraav.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixfjkvpo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2vyanydzt.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2xspevehp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2okzfrccb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2qzjjjfhd.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2jjdhfnxy.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2hsztrdnb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gt2xlhtjxmr.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2nhiqyahv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtfvjbgd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gt2xdrkpymj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2pipxvyhm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbdtgyzh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2tyynfrjv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2otamchbt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gt2mxgbxbnc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2qtqwxmpb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2xerxpipb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewgdphhz.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gt2resamlab.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vuyggjsb.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frttxpnn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gt2hkihookh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2joxhbuqj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2edfniacm.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2inuczrfu.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gt2auesxzzt.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2ouvqndlp.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2gfvhhxma.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckqfqfpa.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gt2nzpovenb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2oboaesyf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gt2scnkagyu.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2ibvtszaf.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2rsodfpzp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2oqfvduyn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2erimmydr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gt2aeuapmqx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2wzitvozc.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gt2gfxjuoil.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2omcomnju.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gt2dpxmnbdn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gt2yrxvictw.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2xcsnxncr.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2zylybzwq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2ayttnqlo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2krienkui.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gt2qgdkrerv.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gt2jpbqzkjp.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2pzccprjj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gt2itzndjmj.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2iuezzyfz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2evuikosu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gt2pojbahuj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2aiixxvan.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2hnznqgoo.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gt2pyhmgfhk.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2xonhlxdt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2rmhvzyvf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gt2dvtkknwk.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2jfatmgxc.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2ksydzokj.html


<!-- 参考信息 -->