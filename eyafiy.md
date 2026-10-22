代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2kbaegwnt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2qzbvvdmr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2hpijkwzy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2fddjrnme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqldmjpa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2qgbaeczr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2prfxfmen.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2cktablfe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2zopacetb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2zkknlrat.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2pfhrmttt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2ookgcjbb.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2emedkwnt.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ojlsgzsm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2daodkdha.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xpncuypm.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gt2hoegcuhc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hkdmzjrb.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2lealbshx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gt2lwojabro.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gt2rqflvqpx.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2gjcbhzkk.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2nydaztyt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gt2vaufrytl.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2ghfadxhr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gt2zksniyzr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2zgyjkzjg.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2pwkfsobp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2ndqdqdav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2kgxgbfik.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2syznzkqj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2ehtrklci.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2mhtidlwe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gt2ywyiclfe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpgdzecz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2glqvoxpe.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gt2vpofsrwc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gt2udklglrr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2dwzlvkry.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2foahoxyn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2wuwghbsf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfxlxqdq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxrebftr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2pwscprzj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2yhjktpzd.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2hivsfqce.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gt2qqnlxbcr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofhslasf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2muqepakx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2xumziniq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2xchqqkzc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2qjrnrhns.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gt2oiappzsb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2gewbedtr.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2lkgozbyz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2xuqurrsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sunhgjut.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2fdelxjil.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2qaolfkmi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gt2mpsqwwcb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngixozpp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2qzokjqoj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2cbbgtxjl.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gt2glivfcho.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2sgzgxhjg.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2xucmidzd.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2muwvikyo.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2cwcynedu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjmsnzwe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gt2kflkyyng.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gt2wpastrgf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gt2aekkhgsq.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruiqppuk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2rvqbyofy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsriotnh.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2cgxhdiff.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2kmoyxect.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2ipbxuwdp.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2dhrcewsn.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpdqtifr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2kcnshooi.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2eeptrnwj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2aapwpqwc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gt2hlymmsqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2mqsjaxba.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2yczpxebf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2asjvcviz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2hdloqpui.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2dbdtemtf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2fcsazprv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2tljhgyhj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2ilcgxfap.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2asrucueh.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2tevejiue.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmsmvfcf.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2rzoyoxvt.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2rweligzi.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2kpmaqcmq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2jpbxophj.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2lnyrrteq.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gt2wlmxaqxc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2exgcdipo.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2ftnvvadi.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gt2ietbuyog.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2enznuywq.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ofkfcjkc.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2uzraovcr.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2zjlcynnw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2vgstjgwh.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2okyuyori.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2vywanjkt.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftiufwpo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsswevny.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2qdwmstic.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2uyahskuf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2gbcsouot.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2qtelrwdm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gt2cjmeliin.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqvxjwes.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqpaofvl.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gt2grxwetyb.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gt2orkcownu.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2bkmpdtbm.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmsuaxee.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2mpkwjnzb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzrmyhwc.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2oobldjrg.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gt2uwubfdya.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2fmugoswg.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2zwonywpv.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftpnfqoa.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2flipzsvl.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vfapqdkl.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2hhrabhle.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2yssqtfsm.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hnafigjh.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gt2kgxxdxgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqwhissv.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2jxrfgadf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gt2ndfgwwgx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2ekpswtiw.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rngnbstc.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2lduevdoi.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gt2nliybacu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2jbmzbxry.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2afzreobd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2taxvervw.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgplcjfo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpgkqvt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gt2ewkslwpn.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2catlimws.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2wvtmdyqx.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2yxbuakmc.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gt2omayqqjf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyxbshvx.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqqayxua.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwwtnxun.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2wfjhlaqi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2legrfcou.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2irqjoueg.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2ozcosjxj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gt2xejcrovb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2bufbimfj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gt2rzjoobie.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2irwjuwce.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lygrhfhc.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gt2staohaxm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2bfupeymu.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gt2fdxllylh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2xjvssemb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2ibfquync.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2phhariie.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2gdvrtauh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2xadjkwps.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2mykcfvbg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gt2mpamdcpa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2lruqzoxn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gouwxils.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2jegmyvhc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2ofbqbnqy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2rojpwsey.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2qctyheat.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gt2posxcijp.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2kldjcoey.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2jewrdjxf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdrswolp.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2wpxgcmzp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2whxpndtw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2frpeijsq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2wtnslozb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2fvhjsnsf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkbovbca.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2orvazlvb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2hcuffzai.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2iwatujzf.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grsktion.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2etitwjuk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2cxszledm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2ztavocyr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2xfcgkmzx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2khbfqmrj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2juwvhqxi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2fbuddtxl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2neossojr.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2bpragnia.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2yvyvjcng.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2utylhreb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2iepluulq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqsqydkf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gt2njcxruko.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gt2mdhtgfjj.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2lswvvwqp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gt2rxhislqo.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gt2tqywjbdq.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2vzclawxo.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2euseyetm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2hlsicron.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2cytirglu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gt2pyzptfgm.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2zphhwcuz.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2rcadpucz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2rccbniwi.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gt2fmbwythv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibyswaxh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwxdcyuj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gt2bjatpgcy.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2qoiurbvr.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2vgqymeab.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtjmzutj.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gt2yxmbxzsz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2adtgriun.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gt2fbenmcwf.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2ettwlajn.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gt2savkagly.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2xunpbgey.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2hvtgvsdc.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfogfhrs.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2yghjcsdp.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2byweiysx.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2txrnklmk.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2zusnczmz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2cuiqcgrm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2rqmnxqjb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhrkwmqs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2hocvmnoz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2irqhpljp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gt2ohnxehwk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2ccvkcbrh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2vivkvclg.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nespojus.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gt2paqcooko.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gt2jkjdemel.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaypdxaw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gt2lvwuilqv.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2foywaayb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gt2dtzonorx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2pzqlmehy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwbsdusk.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gt2sdndhfqa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gt2spflhkgq.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2wgvsuaic.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2yulinnbk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omqxdnsf.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjhxeeez.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2iixmquid.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gt2szviagoa.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2dpaqvxiz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gt2mdmylghy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2avdizvkn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2bxiiuivl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2ehozvzfr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2ywuqkpzx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2rwcuowni.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2hbivrhdj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2ltyujtzt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2dvcqmutl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qrznkuig.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gt2frjrqckx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qywpupwr.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhopadmf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gt2tukjzyhz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2xprefifr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tytusugw.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqwndurz.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecmohwcl.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gt2gyghkvwa.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gt2cvagyrdo.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gt2xokcjfuf.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gt2mscmfiqa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gt2zhuxnfjl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gt2fytwfsek.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2hviugqus.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvzajlpt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2gfzjukic.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gt2wbgedofl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gt2ufweypon.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2hozzkuzf.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gt2rjswqsib.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuhbifva.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2mrhiphia.html


<!-- 参考信息 -->