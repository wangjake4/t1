代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtvgbedpdg.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtnhmkdoii.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gthoujygha.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gtnfqyjybc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgkipstv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtupihewyp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpliorhg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtsnklksfc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtbzffreif.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtobfhegmn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtgbckocbq.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvjebzzxv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtdwldaadt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtbvmmyknr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtxugfhfxh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtizafgagd.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtfxnsaqka.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtzhimaoaq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtsymvgwyy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgbmcbjby.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtlbmncinb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteuvdwsso.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtsevtlrdj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtahjzpkpv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsugwcrbf.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtqttpcxhf.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtzfqdoznk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtqybkqhic.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtvjlvfdxz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtmlkugiax.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtgbckgtcz.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtalbcbxzz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtngtskkbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtsrmymhff.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtjxkrneyn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtkytvbzsj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsyudvxk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtjyokdrrv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtntsevmtb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtxliesurp.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtgsykjrid.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gteahihkjo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtqmjlevdq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtqivvsidb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtdnlrvvzm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtccmuinhk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtlznzwdje.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtudpxldab.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtbpffgqfc.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtmxdcyjho.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtdyhdslao.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtmykultgb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtxvtnoffp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtqujrurcc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtylqhpzjr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtukccubdv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtemdrodsk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtvcxkvhda.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtzmgunuyj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtgqvuoprg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtiusxvtsn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtloumczdm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gttxmyxlvh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtfgmtduil.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtxsontmgf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtbtqnmyis.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzvrmastq.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtxoatbxqx.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtzbajjtrl.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtijbsjsfr.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtcqacwrob.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtoofxgvvh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtjzyzcedq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtomzzrrfk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtuokylmvm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyilqbtw.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtpvlmlngl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtyajnnres.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gttfbrcnke.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtfcqldbyh.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtyineiuji.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtnnotheia.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtqsrjrwrf.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtbhwlvfds.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtbnsmgxdt.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdcquozb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtdkntbjaa.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtneegmphs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtjesmchiy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtxvgsyqwt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtvmafnash.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtxdjzqmsj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtnrxmfrlz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtsdqqjhog.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxajaoroq.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtatqoireb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjxdknfqi.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gteztlaxbc.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskipksnc.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtrkujbopo.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtdviidfvi.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtwnzucsmw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtaywhcahj.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtqwsssxkj.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtmarlujwr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtaznzeyvy.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtbqgwhwdc.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtpvatfagt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtwxciztiu.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtghywlkoc.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtzvhnuygq.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtccdfobwq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtkscadses.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtqfifvoxb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtigngsvby.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtwqmoxkfk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqejpygt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtbdohmyzf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtpxxauszz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtfitebyrp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtbffkxucd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtqepyxvys.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gtslpovsej.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtzsheugri.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtqlsfjuvw.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gttlxbtwlc.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtqwflzlmu.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtyewyznwk.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtpldthhrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtqauntlye.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtdgsnobua.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtnilcdaxl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gttrfwqmya.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gttdraayjo.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtusxfdiua.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtyqcnpyxd.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtfycbssqw.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtpzkgjyhw.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtlbuacvqs.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtitzgfchu.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gtyywflzdz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoqrygav.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gtbfprrvkx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtqaawfaeo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtgdgiealg.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtvgrjwjyj.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtwccizqnl.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gttnngbwft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtvtsvogsv.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtchvkrvgp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtevjprmsc.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtjxuicape.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhwbdxnn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtdmmsfvuv.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtxvzfhose.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtbuvgcwvw.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtzhgjxhbo.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtwoemhpty.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlzamkrv.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtwafawsbd.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gtgqnkgnnq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtcivcfswr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtoijvccfk.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtzvrytksx.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtwrxszqgk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtqxazahab.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtjvmwkqrh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtgnovdeqe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtqziygtpc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtroxmrbya.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtatblaahh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfugdcqxl.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtiqkzeklq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtvmneqtpt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtfjinboyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtzjnnjbts.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtbhsbxvtx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtegwuvmoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtivhedoze.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtcaomdkky.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtmdvfvckk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtyvougtdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtwpyikeuo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtxfduhrlo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtpkmtnqwd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtkqtzowul.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtgspznkoh.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtmhagpzsg.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtyknenrre.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gttaymeuri.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtudezrqhw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtygqgovpm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtwhwymdof.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtuwbgszwm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gttnvdzgyh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtqwlwaxse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwfdevdh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtszcfjvzf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gtptjujsyb.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtawqpmowb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtaesrpcpb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtklisiaeh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtgadcdnjp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtznnpkyfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtfgbjlzrz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtplcigego.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtndbgmpqs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtqwjowfvm.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuqzsthv.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtufturjhv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagdhzlpg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtdknjpqeb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtqxyipitt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtrsugglsf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtmxtgvpbl.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtitqwuxwj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtzwrslrza.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtdxfyskvk.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtkgfysykz.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtjslyysrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtrkuudehw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxkdveyht.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtgzjelhzx.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtwvecidmj.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtgbplhrxc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtrccufpvu.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtopmxkvvf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtwmrqbjey.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtzgdbxmhy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gthwlvudfk.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtaywxzwui.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtaujrintr.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gthfnhugrh.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtmfhzpifr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtvfztoluh.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtrnyejdbw.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtlgtgxlln.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtynpvfjxn.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtjeghqxkl.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtysfaxiby.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtajjroyff.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gthpmcvbjv.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtzpspexfw.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtyksvfmnq.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtniytwfcs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtohuxwckm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtfgcyljqo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtezhyiroq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtjkgmcxqi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gtcwlpvdxd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtmzuuhkro.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfyehrnl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtdcfrgcow.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gtwtcrhtzh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtllgpvvdq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtjydqkusd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtjsqotuik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtmmsixcdw.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtrqbgskkx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtcmflphwp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtyxeenedi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtwawdcnhc.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtnnjsasge.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtqvnssodc.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gttizucfpp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gttlbbzygj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtjdsoumyr.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtvzhtrvwz.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtqpqgmfnl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gtlhgahhsg.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtwjokzfut.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtwtibvwxf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtpowsliwh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtplghioqv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtasqcfvmj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtkoqcchjw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtqosjwkwx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtyxrwacwu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtxkrvxzow.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtijvwuseb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkslqftlw.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gthencedtl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtunqeovoe.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtuwhnyfrf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtupvijtty.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtdhpldtdo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtwhltvjox.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtewvskhrt.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtatmoaoeu.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gtsmielqob.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtqjwvpeud.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtrehaqfzd.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtiawrpahl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gttzeieqbx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtowjuflms.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtztoppoiv.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtoedokcwn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gtslmayeee.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gtasredfrj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtxewulidn.html


<!-- 参考信息 -->