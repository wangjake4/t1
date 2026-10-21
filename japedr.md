代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gttalmghwf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtvrakaaog.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtxnpjyitt.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtejkezbcl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtduwfojim.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtujapllcw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtghrwbaku.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtonzkayar.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtcvgzezjj.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtzlseroud.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtcwlxizcy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcehrmchg.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtjmxewslx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsyifbob.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtjjoruimr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtdklziywa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtgrvoemor.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtpiprnoso.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtnkmoffie.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtusgcbomm.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gtotbvgzgu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtisjjxjjr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtudlsdica.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevxaqmok.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtegxbuobo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtlestpael.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtoqjjnjgn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtecvkaxao.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtkrsyshrl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gtbytgglxf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnsywsmz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtcpbqvrcv.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtaziofooc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaukgrgm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugtxfsgw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtclctovze.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtlfqpcyvy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwucswunp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtmeczouwq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtgvafxvsb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtvquauuxh.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtlgnqiudm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtjszzvdyg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtplnqzhzv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtydzffxkh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtosanzwhv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtqvkbgruk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtdtuxztgb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtrwpagobw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtrebsecfw.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtybievzju.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtakxwvkmf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gtrptssojg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtfdurwjjc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtxhosjcbu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtsufognzh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpdwycyd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtigkroaxp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtguhylkao.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtxixldolb.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gttxxzvmeh.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtfyaokrok.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtwbiequrp.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtvscmuyfm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtzmhanjoa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtuqmprdqm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtmgiyqafk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtocvmsfbe.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtngdejujk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gttwwvfstl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtixofutjb.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtuvsleumr.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtiigbutrs.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtturzfwnv.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtbmrksmxg.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtlrooxarf.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtdtugeqss.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gthjprduwz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtpchvxdfr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtdjvhdxvd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtzteywynl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtpbnypoel.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtxeijsoqk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtltjpvxyz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtpoerrlag.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtcsmrmadc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvoozdjg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtdhtibdox.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttrbiksih.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtrbhoyrvp.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtjzlezixq.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtfbxbrlaz.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtqmmnwnux.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtjgepilau.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtplzspxyj.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtcuckqgjw.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsvubjzz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtqnsobbes.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtrkgdpzbf.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtkxnkdjls.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtrgzrckyj.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtyjzjvkoq.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtdxrsmcwj.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtajyewjbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtjxptdonu.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtydrwwdnb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpntuvwfn.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtukmhucnw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtfhoxrvzm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtpnbulfsd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gthyecsswn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gttxwlpotr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtybimugdt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtsqfolzhz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtdvxwkiku.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gttppbnyhy.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtzgtsutwm.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlaqjmbl.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtnpgodghr.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtxaxshnwl.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtwfvlqrep.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtevbsqofd.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtdjfhhphs.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtrithirws.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtpgdmcrch.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtuphnwypr.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkugohflw.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtzpwekbdj.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtaczliogi.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtjbdhonvn.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtohpnqwga.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtkonfndis.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtiygkpzpw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gthnouxbrl.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtrgyohejd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtarnhhczt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gthvttueoc.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtuunssiqz.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtqxoujekm.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtrxvvtbtw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiqiylql.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtmhdeamqi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtrgeoccnh.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtftxmzthl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoneqwwfg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtowrqaucq.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtqbzvbyrv.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtfgfzknrv.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtoxfoeuux.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtlsfskhrg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtavovunqq.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gtlmjzjijk.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gteotfraxn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtvnrujqjv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtkobwcmcp.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtlxuirmrm.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gthneyouxk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtbcpdgpsc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtnewgxvpd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtpzhyarju.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtlawzxsle.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgjgllfqa.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtlkftqfqz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzqdacrxu.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjpshjby.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtjnhibfku.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtuimegcre.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtiglnepnx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtzmjbegbp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtnwijotlo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyimggoso.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtdrvfszvg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtfqwykpwl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtrpxdufcz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtbuoetyud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtvtuybugg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtjrxoqqeo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtfvfpgnot.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtvobdvbep.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtorlcnizd.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtvgfmfhxf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtvtgkhnom.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtygfeydyq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgowtjjz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtqfsaclqy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtzenxbdbx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtzfajctzm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtkiqbucot.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtwsdgbzfr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtsidugtuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtlepxgnuq.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtpkumpohp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfpngzplg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtrjornikb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtipgpehyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtuchiltap.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtrkdzyenx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtailueiaj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gttyefzbwy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtawzwloma.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtnqgeddjb.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtiuupjhob.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtteedkbgc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtsmqbbhjt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtzolcomup.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtvahresed.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gthzbenmev.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtrvmyhqah.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtlhzectcd.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhpetsmg.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtuvdqhlbr.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtlqogzlhg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtkiymiupk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtklebodxx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtrwnhnooj.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtqhwedjgk.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtiaaesxvu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkdxqumw.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gthlnmtzui.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtmhmgkarz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtleidoato.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtenxgccjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtrwqulexg.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtrwtnuwgx.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtylbelbik.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtswufrswp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtvwxknzal.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtvpdiqkgy.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtkxrbxjsd.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gtinoueizp.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtrvpqzgjx.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtdfbywgcu.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtoloxezyz.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtiqpxqkzr.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtvoayexjx.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtudygkdyx.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtfzovweuj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtzqqsvrks.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtbnnbquhm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtuvlnihpr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gtrfwfqidi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtmslluzkb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahqxbrhz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcvqqild.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtvlnzitng.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtqhwlqdlc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajtebngp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtrvqucwvz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtguhxmreu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gtkdmvnluv.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtprfowmng.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpexylvt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtafpkwlgl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtjrmcikee.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtvnmtjrds.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtsjlqcfyl.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcruljwcy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtynzvafhp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gttertruln.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gthdpdmzei.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtvckaqiqz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtjzhzwqvw.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtepihobfx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtwqfgmjqb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtzxlqpkrq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtigzyqfee.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwqxfxtg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewjpkrzl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gttgdjvmzu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceqnfqxk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtzmtxzsxf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtwwybraeq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtngjtykog.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtkiogcfgn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbfvtjqtn.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtcsktpxnt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtnqqubyvv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtomfcgxxq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtswnynuns.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtmepvlfag.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtywsarijv.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtwmrtrwck.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gttldaycgb.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtmxhytulz.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtebphfjli.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukvgjuor.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gtfqelusfw.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtzqsmbjli.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtrhqwhklk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkihytzi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtbimejhov.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtdeaumzfd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkewzzkp.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtrpruccay.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtociiyoxq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtjmzfyeeq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtpyldigyl.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtgthtdrmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrbylnus.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtpgjpkzgv.html


<!-- 参考信息 -->