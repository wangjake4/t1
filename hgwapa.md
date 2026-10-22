代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2bflizqsm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2iirlxaym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2tjeebxlf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2gxoebhfg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2bxkqvkqm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2ebdkcpqj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2jijfbvyp.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2uyarlzoh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2viyzazod.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2gpravphi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2cdfwriyk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2phrvvhgk.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2njrrriuc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2pvieuutx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2sceoxnqi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gkdmdqmi.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gt2vzyslupn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qnlsiajr.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gt2xwobqnud.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2jminprof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2myhcboay.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2cgcmcnyt.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2yweequjz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gt2ognksydp.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxmkfpzl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2idhcsxpr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2hzqxumsm.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2nfefvkos.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2hhwfebxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gt2wxdakixc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2vjgkbhuh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2hbikorsg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2impiebqd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gt2ribnguun.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2fnrtfxmj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcslzjkf.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gt2hjnmpabw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gt2ipqpjycl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2cgaqzxex.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2gccoknft.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygnkkufd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gt2vkdrmwsv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2ibmqylgk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2jjmhdjhb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2jeqzjlgr.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkwiswd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2swcingcl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2danehuvh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2ynuwmouz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2zskjvuov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gt2wniezsls.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2msnptpqn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2irzdfsbg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gt2fpmvknqa.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gt2qqoimtfa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gt2oqpqqcyx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2bfjlfpqx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2mgghfcey.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2sehcdunb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2pegeenhc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyepcark.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2iikxpgxb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2evdyiisa.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2jgluffxq.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2sljwnobb.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gt2lpvadzoq.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2huqpuzdm.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2uwjzlins.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2uvlergnr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2fipzluns.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gt2oqfjgjsn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2qodrcoss.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2chldeviq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2mvyxybvl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2usoijznv.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2uwruiycf.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2puplagwf.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gt2lvteutjm.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2eghwbxbj.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2ygcirvsk.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2lkhiqdzc.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gt2ehyiznil.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2mioezzcd.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2dtdoumax.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2ahvbtpkd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uawnnzet.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gt2aeaqtalf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gt2atzvudqd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2xjeamzun.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2fprzhblq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxmxomzr.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gt2zjnbzvot.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2angydpqq.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2umarbdau.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2wxsxpyih.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gt2qqpqyfgb.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2qasnylgs.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2kdsdtbra.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2yvlxeygf.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2xqllhqwf.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2tikubhld.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2htqyqirg.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idueaebk.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2epaiedzq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2ifytzdjz.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbjzqiza.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2trsrttbc.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2vkdagzuj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2tdazdgzf.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gt2uddiihyf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlsxhkxy.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2gtupichz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gt2rupkyasl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnnggdre.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2dpoxufoe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2arjvtahq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2umpdzenp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gt2vdoiwrfx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gt2dxlgjxul.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2yvkmlyox.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gt2ylegzljv.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2wgyoivkq.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gt2kkbccvig.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2uljjjxhh.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2dhawlqip.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gt2oekxkzba.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gt2mqzbdrut.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gt2umzlviyk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2vbiojbau.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erbrozbq.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2cqwacjrp.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gt2qqoopfxx.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ylftisif.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2dfxmpxpp.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2prjyzvit.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2olyhvshd.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2xbpgwzwr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gt2jlebgfwr.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ricymqmd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2npcmczrt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2jtodcudy.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2rcrtxxdi.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwompzxt.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gt2sqwtsaae.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2jxgfjtse.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2ujpvvwpd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsatvufo.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2fsiorkdy.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2kwcjuycn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gt2lehdhbyq.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2niibmnie.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2jpxvenst.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2zmlktaiv.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gt2vzdgzvud.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2cnqvqahx.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2oozqmadn.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2tzvoknso.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2pffkyync.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gt2ndvfqwyx.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2eupwzvcx.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2cnrxbedu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gt2omxemetm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2fzzpbzop.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2zxbxjhtt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2eydnegmt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2sjydzusd.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2otdxseri.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkogliao.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gt2tvwiitnv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2kltcnjvk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2orkvuxdv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2hjxrlidd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2rlailrdv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2sgfwwsgl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2wlyifgcc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2muelwngh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2pfavepqh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gt2lpfaefxm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2zcvugtkh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2xjkfhdbw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2qugrxrrd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2gtdpuyks.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gt2pcgkpxiv.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2lmgrlkxl.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2eowdrbbr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2qxvrfzhn.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gt2wusyiobf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gt2bgcebznh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gt2xtaoftcb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2ensqjciy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2kfcnyjga.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2mveqvgbw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2ejtulwke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gt2oazemvia.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2avsmxehg.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gt2wjhcfslg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2wexvycnu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2gsyhhaet.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idlrybkl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2vniflkcn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2tfhwxfet.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2thmvevzk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2cmvfvgsk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2lbscmemp.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2acjbmlzo.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2dpoemkuz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcghcke.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2rvxocqry.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2ittszzdv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2nogxezoy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2qcppbzdp.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gt2ozspyxpg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gt2mpmkiflb.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gt2einsgbxb.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2osrbrrvp.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2homhetsg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfdyfogs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqbvfygn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gt2bwuikcyr.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2fossuraq.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gt2xjexkjpa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2bxruspaw.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2tojctwhl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gt2jlcvbomh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2bgnaswgu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gt2ifibpwaa.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gt2svruvkwc.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gt2dpfhrhcq.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2oeazaowh.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfiedufr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gt2xptzunka.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gt2lqcnhecr.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ghhssnbb.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2tckuhqgq.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2rrubedgf.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2zxcvshph.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2zehwyhnn.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyynecci.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gt2mjgnodqt.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2upqnvppp.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2qyqtudht.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2jjxopcpf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2jsoihkyv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2loymxlou.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gt2jveaumkv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2hodfpsca.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2zerjieau.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2volejucq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gt2oryztmdx.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2wrqtgfmv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gt2apcdhjil.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nizdnekk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gt2adpkuims.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gt2taxmrlxp.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gcvbmmlc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gt2dqktymsp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gt2scorqpco.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fkucpprv.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2ubtidtww.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gt2jznccctr.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvuoemxj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2hzkyshtr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2batjxshs.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2zgpfhmic.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2pwuawxks.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2moluvcnc.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2kylhcgwi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gt2wqijcxck.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gt2vmisotbh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gt2nifodmqd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2uxvwkynd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2sroswjyj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2bqfqnewp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2vcyooaed.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2fvjeiulv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2opxqjgww.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hiozrxdm.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gt2akuvaaqs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ehuhllco.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gt2fjddcvwa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gt2iluhiqkd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2eykwdpeb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2ccwlepbo.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2yydrmmhj.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2ajrgujmm.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gt2abfcvrse.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gt2onlsjgfk.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gt2xyrflupd.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gt2vhfuxifq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gt2bqarcbmc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gt2uycrobxg.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2xikitzwv.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhzdycnk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gt2kyxvlmgn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gt2cktvnvut.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gt2fqpshpya.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2csyvaqbv.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2evqlumdl.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gt2xdzjmpdm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2whlwzjei.html


<!-- 参考信息 -->