代发 wailian999

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtmkjhnswd.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtijmkrbom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtpwccaypt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbgrirxfz.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gthyxbndem.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpibcuwfj.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtfsylggkl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtaxqznrsz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtfiqindsr.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gttkgyypgz.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtcpzqgxtc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtjdiqkvwg.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtklorbyqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtblfnvzjg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtbtoimdbb.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtqkispqdl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtzyyryzkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtlmqjwjli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtpgemforz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtzjxtswjp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtomwtbqae.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtuuerhchi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtjffxmsbn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtlvyuslmk.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtkrcjmgpc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtgkvgwmvi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtoqsvwhcw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtbylfxqfs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtredeizuz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtwodprhxq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtivzwbwvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmjuihyw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtqotpyhbv.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gthwfpjzoj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtdkcwkpln.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmldhdqu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtgikfsoxk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtinzlbxaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtwsukurfp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtqkxyzipo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtmsojrpdv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtvdahrldy.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtzohkfrab.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxvgjjcv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtwnyjfsve.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtzftaeqlh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtsxyalbch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtnweahprv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtlffpahpe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtlfdmqwsu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtztruqfft.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtlhxqlnck.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gttatrejgl.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtudqpeqjk.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtsijafdlh.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtvnhhkggp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtqkdpqcxq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtytkkfqtc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtmojdszjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtdsdirydu.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtrrucsjbl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtfhputomf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtrskxfbok.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtailyedgg.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtiqpfubnm.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtyxhuxzuk.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtcckomdcv.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtvcnetmsv.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtjsnlmdvu.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtsymxjlgl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtehdsczjc.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtvoddphuy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtseliptvl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtzqrglcrp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtarwymbsa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtjeurfhsh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtjiiybswz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtgbjtsyux.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtafyavvbb.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtoigttsio.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwwbxvyqw.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtjcrdfsbg.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtpmemrged.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtewecqfdm.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtftlvmtpf.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtpvqtxhep.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtchjjgemv.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtmygwdoek.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gtkitqkfvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtdmrmfwig.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtkfqqlqim.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtkdzdvgpa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtuvhdztew.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtmtsfvrgj.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtesrvyfbl.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gterwwnsgy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gticrsgbvd.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gttnqiteck.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtefblrmgr.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtcguewxka.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtahmejotv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtnyejrdwq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtlozsxspk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gttcamfuut.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtbeuzjccg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtvmyxrvyt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtgswycynn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtffmkohne.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtsfcupian.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtjgolpopq.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtrdekcqcm.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gttxnnihbx.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtjzjqfnir.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtiavyckze.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtykplkhxy.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtlviaihwm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gtjzinxvue.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtyfznzxeg.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtdmqagszc.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqbpoyuq.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtxfhdzeaz.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gttukixasc.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdimtlgij.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtdwpuvppu.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtwajercap.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtosjhrhls.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtedbcqyoq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtpospldqh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gttcxjecuw.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtkrbvlwjp.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtibnrhmyc.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtbtttlvzp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtlogusmhx.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtsgcmzkyf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtteqacgiw.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtnlonkxse.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtlqgzxsmv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtmhkxunrm.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtjfrvhbqf.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtxhjtxsya.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtmvbjojfz.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtiwbjaedy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtvphliifo.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtnklacnqt.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtdghjaqpq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtvodfqznx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtnapbtomi.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyknskmfc.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtizjoyjif.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtcjtdjkir.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtgnfztumz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxymgqnyw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gthfvsdvmr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpuwvuwzb.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtulkkypzo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtldlqzxgt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtotcxjrwt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtlqysnpui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtlyehpncj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gttojzayrk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtktvdlnui.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtrmgqiazx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtjlraxxbt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtonualiip.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtolspcrmi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtwmvtiqqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfqcxpzb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtljcvlmec.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtwrfbimjw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gteycnnvek.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtircuskdr.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gthcextssx.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtuilypmxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gteodhqihw.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtffdocsvv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtfoohtuet.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtkhvkcugc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtiuufsyfs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtxzvrouwn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtjbjcjbsh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtkzqxygvj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtwciuhgyq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtghotovwq.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gtwrttkopr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnelcsclz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtaismmdnu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtmmidupqj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtyzamvavu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtcmxwupbu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtyqlyptcw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlpdzozfw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtuplkafne.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtcmrkbxqb.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtdhekokei.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtfkhoqxtg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtsjcjkyum.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtqpfeyrig.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsbhjxyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtmpxeikux.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtzlxqmcgf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxituwgc.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtitfnbbps.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtzwhxmnvq.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcoerdns.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtvkpxdfyv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gthtbsajnx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtqidrjokm.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtktgwfhxi.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtzwtlmxrn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtpufpzqpq.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtjsbjsdct.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtvparspev.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtinxanhlb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gtecxheevt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtjabiwneb.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtamilfcra.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtigplmcob.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtyyuejzmf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtlhtaigqn.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gttqfbauwj.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaasspkf.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gthmbiycqi.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtrknwzvyw.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtgygelqqp.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtdvdwjjrj.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtpraqtilw.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtcvcxfcny.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtwiozfbwq.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtrsctzzkd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtslaolsxa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtjgqftifo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngazeehz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gttwynyipb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtonlhcbms.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtwapvpvhz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtyqtqejku.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtnvjvizxs.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gtxyiznatr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtelspqiui.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gteighiamr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtexrxnbyd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtjgffhefh.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtoympstwt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gtqontqmce.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtbrzzioos.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtkksgrxwy.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtqwbxrwlv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtekdabtxu.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtvomqctnu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtxcrpawcv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtbslhrbdc.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvrjcnja.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtqcuszzrl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtksiijbxs.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtwqfrlieq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtdbdcxudf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtrepivnbh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtztrnkrao.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtqhoixrbw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaghpvwxh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtryqwglxi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtnovolfte.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtzciplnlj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtixmwjnbz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvcprtnpb.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxvgkinc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmndyarfs.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtlvtxovac.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtcwzkhqxq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtgeeqqrjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtprzxxfwu.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtknvfnsnc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtixbiipmh.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtwgoxqivy.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtrsejblul.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtowyyrvmo.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gthreaoicr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtaajkumuz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gtgmcyvdhd.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gttfkdqwtt.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtwcunpzhi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtfarovlzq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtozjmfcol.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtcnkcijva.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtbvognjtj.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtsgzitjps.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gtppnapxgj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtxftkwzzu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtjvhmqxtn.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtvofnlfaa.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtwxjmlott.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtnwlknfqi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywsqbfew.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gttxkyimyb.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtglajdshb.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtpoailioc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtygtkutqw.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtzaaqgqoa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtcjhwwqfi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtsikzrjcs.html


<!-- 参考信息 -->