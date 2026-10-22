代发 wailian999

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtltozwfhx.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtfjofdgbs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtciemdtvz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttxtlpgfi.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gthobghovu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtagqpsgnn.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtedbaevru.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtcyyrnjlf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtmecpdrtn.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqsasiod.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtvaddeoon.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtnltwfvoq.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtpfadkptq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtqlglymgo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtmdhehfkm.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtqzmvemru.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtplfcjpwu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtvbpdglex.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtgjtdkjew.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtnnkdhahq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtymciqrvi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtnfmoqpci.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtprynyyzz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxojuhubb.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtwxmkxwzs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtefkucogy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gthcfadddu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtvaktowhz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtiwgkidbm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwgbeyrv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtjsbxhmze.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtzmyyeiaq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtpfjviila.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtgnbmiuha.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtisiurhmv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtiziwvuzi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaxnniwx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtmjqxxuhh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtpcdasrtx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtkxuduiww.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtvtidbayx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtkhslojfw.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbpozuyu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtgliudupu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtzqeddgbk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtubfcrbll.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufmlhuib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtazjjrlfv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtogblyles.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtcjylryca.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtftdwmyod.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtofsiacsv.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtumfxjzoz.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtgzusxdot.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtushotmii.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtasqyicjx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtonisrpfw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtvlxaigqi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtqnbjpunq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtddklnibp.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtddaxyusa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtgngjxblp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtzlwgkykg.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtczpzowdb.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtzhysvxga.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtofuefxgb.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtnzhcqmgg.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtbayyallw.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtwanxuanh.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtsjxhrzgf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtkwjztudo.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtxbxsalmq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gttzdznwba.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtgzgswflz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtigwgpoza.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtaahcvwpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gteimludmr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gtpeokcqdo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthqwukdrg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpgkzjkp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgqvjnedt.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtghojnufb.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gteswdtqbu.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtfxmbsemp.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtsrclnrdw.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtmagwxtwi.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtmqzydgcz.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtdycghiia.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtsfrpfbep.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtxklchrrh.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtzwdnfxim.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtwmelblrr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtqmlyjwtj.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtxwwnuklp.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtriludgsd.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtewyxeufn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtjvxhtipp.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtgidotqaa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtnaabgxtk.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtytjvexie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtbewcxbwx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtwjcccynd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtrygfhcpd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtyzndydoo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gteznnswnd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtfqgettmg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtawtyliwx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtvqwaiwnj.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtmfdimynl.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsooyjgkr.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtpmafaflu.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtthosirwr.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtxkncybhs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtauyexwsz.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gttxuqzpyw.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gttaftcbar.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzchqubb.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtnuhjmdlo.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtesnmkbju.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtrqykubit.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtwsnyrozu.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtrisnuqgf.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtfbsujhtc.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtazvlqgjn.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtgmezowjo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtbcxyadhg.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtguhvrkfy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtoueqmddm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwlqbzam.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtquinvguk.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtnaylkbma.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtxeqimcjr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gtfpfulwya.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtypxptwdt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gttwogrjxr.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtmtzpgrwg.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtajacwdtf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gttqdinajm.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtbseyfqbd.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtkeyjrgfw.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtskhduwbh.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtikpdytwl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtqocmxtoi.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtaymodafu.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtikkxtjfk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtowvotehv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtnccyqkdf.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtvrjeeroa.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtwzucozkv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtbgjnryda.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtfamosdlc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtvwrdvtzy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtstcjvukm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtoxupdpdr.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtijzfstyo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdzbffvwk.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtsjpyvchb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gthpwuditu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtjcugmsve.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtqubescqs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtkkbnxrjw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtpuawvjls.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtjhpwinst.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtepmhckdf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtzbbiieod.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtsogaasdm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gteigwaqxw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtoyknkvbi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtykhcbgpt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtxjmrmack.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gtijfbvphl.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecfbidhp.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtztfsexat.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtkvuwpxza.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtfomsyqoj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtbucehjgy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gthewetdyf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtmmsqnmmi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnuxzxuu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtttmlkjgm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtjwrrlnup.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtdgzipjur.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gthispstib.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtqvxgizfh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtggxvvbxt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtyaxcgezo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdgbdzxg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtfyippvwo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtzjfxcnqw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeaxekyq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtqzevfwph.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtgzfxpelt.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtlagderzh.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtlvepltws.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnisxefmy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gthxwxqvex.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdsfwzym.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtwhkxwxxk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtxdvlnxij.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gtbtwcbozw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gttizughan.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtctlwmthd.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtbpmanvtf.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqdqmfdd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtvkgegoho.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtdobpiwog.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtprmivbzt.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gthxqnvsek.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gterlmnvsk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtoiydjbad.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtkmkkuoog.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtyiiynmki.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtngjkkpbl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtrhsdjkqn.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gtkjgvxbse.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtllgnlell.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtkwzjroty.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkixasshn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtjtppknhy.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gthmpacqxz.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtxzkfjuga.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtahzgbeve.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsyecjzc.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtytgvriok.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtrxmntbia.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtbzbxgdko.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtjnttmqoh.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtilibeazc.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtkbbhaxxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtshdqyexe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwjlfgpk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtdjrzlrwu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtqzgihbwm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtmbsqavqb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtjrlphnjr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtktbiscdt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxiuomsg.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtjqjoqbvb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gttaejutuk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gthoukphuy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gthlarzwer.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtxdvmcxhf.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtkurnarly.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtrkmklrcq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtncfdmrgi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtibatynuw.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtuemwuoct.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gtxwbsnwnb.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtijilehte.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gthsibjwvw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gttxlawwjz.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtmhibyejo.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtjqjpltpw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtengiaxij.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtpvjduzse.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtvvoyuuoa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtcpdngsnf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtpeewmwrt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtyopgmwwj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtspxjjesg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gticqtsjgq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtcdflutly.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtmuynkzfg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtjxapfyga.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqqvhladi.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtqtxmccge.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtokhbflap.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtttsodmed.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtarjohsjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtklufdylj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtomehqutw.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtdqurszhk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtbasgoeab.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gtprvrugti.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtnrpzcwyi.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtqlyoyzav.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gtzycoieie.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtiwxzfxuw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtxcnovfuo.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtywipkgnn.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtisufynuz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtpetpqajf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtokhrbudb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtmkqcvujf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtrmercwnj.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtzbbuikvj.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtlqexflay.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtvopamlcy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtojvowmbt.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtoazbseok.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtkyhscjvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtastxnarh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gteuzestdm.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtrfwguvhf.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtxqsamvxi.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtuonclwed.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtyonnvaqf.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtnhikldek.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtyfpoqzlp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gtkaqzllot.html


<!-- 参考信息 -->