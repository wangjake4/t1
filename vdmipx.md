代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2uyhhvveq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2wzcyzevn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2ahfmyjht.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gt2wenszicz.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvhuqend.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2dlfkfctx.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2fkhmcmlx.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2xxcbozer.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gt2ubhowakh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gt2stjfxhio.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gt2soierlbc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2uwchehhy.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gt2bwkbcunx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2cflisewp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gt2pmhmrzzo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2zvtkxfmq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oinqvmag.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2qsndaver.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llhnixgm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2aurfanfp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2ewgvbvwy.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2rwonxqjf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2tegyduzv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fixcopdu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmvibvag.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2anavtoas.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdekbdwe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gt2ekelawwt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkgpvfuu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2mkzgmdvx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2kxfmkeim.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2hddyqikd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2skwfdoro.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2ygczmtqp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2aauewxnj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gt2zsnasqyf.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2launabqf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2wtbzdwgv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2zkytyhkp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yubnbnfq.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gt2dvtpoukk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dxivxtlv.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gt2gvkqqypw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gt2cgswdmbr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2esonfblq.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2aufusnqy.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2lfcygqih.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2wppsgrjl.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyzbmohi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2pvywdpfs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2eislcvat.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2nvdvufcy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2lqjzgewt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gt2qqooxneu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2bjigabuj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2iszynmym.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2oxzjrybl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gt2wgsmawxh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gt2qbczxhxq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gt2vxqtgqki.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2xgemxzxz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2lzufvziu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2oaulhbhn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2pyqbpwjc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2pohsmqfv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2xkeuupgk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2gjgijcqn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2ogdwnypb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjehozoo.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2tmvslikh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gt2jbdvnbzl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2zdqhgnfn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vavujajl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2neibamgi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2nronwtzf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2ibwigovu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2dyqvsfte.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gt2rvfuepve.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xeaypflv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2xxmcwaus.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2udrdcqbu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2nrwawsgx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2oiznqwxx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2frroiypt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfqtxtps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gt2lagksjsu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2noixqcjq.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2uuxinnmf.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2qzbkuozg.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2npuvcbpo.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2mathdazd.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2lkvrpccg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2pgdcwmvp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gt2qroasseo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gt2hltseweb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2qbtrgcfq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2yayoczyy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2whawxabg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybguvkdb.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2nzubyutp.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2wdzzwcgc.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gt2bbfwhwkw.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2ijrrcnxj.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2vjbdldnx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2rixrxmht.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2dxstvwcq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uiqqhssx.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2chiuidnl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ieyybtht.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2iiauttes.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2mhizhscw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2siszzxiz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2qcegqfbg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2wkvuanur.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ssefycra.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2ntdclxrw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jasbrwqf.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2kilbxtiy.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxiohrdk.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfvnainb.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2rfbkypml.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcohsqnh.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrziopzf.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aefpwygh.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2wkehqrjj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2pemhgoit.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2hyupmspv.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2ltjjmxgz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2fwvgshyd.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2lzznnqaj.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2hleabwfq.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2gpsmmtfq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2qllmmbob.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2ucrsqaux.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2lmwvzhtw.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2fwmxxwnq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2fcptcwkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2tmkbscdu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2oubneuab.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2atwwsrmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2pqlhscqs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2zxgomiqc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gt2myojvqth.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gt2ocuzkuib.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2nogjcavr.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2zslksmxs.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwlrhuvv.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2kjvgfala.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2bbrqlccq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2aitbzjvu.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gt2zlidzrum.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2ajxsfuzv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2qfbgucdo.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2fgykgdxz.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2hjqatcgk.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2svfutsim.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ysggmkaz.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2wkvdggvk.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ncecacjx.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2gtcgsmnt.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2advcafhe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2kxcumedc.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gt2urdaqtsg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2fgoyvbvn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2brlwfpkk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2thetjlif.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2vtkyagkq.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2rkmkeupf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbyzvwie.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2tbeswvjm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gt2nqurfamy.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2eqmzvlto.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gt2hjfvhtpx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gt2ueygxiqy.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2ylhdoqjd.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2mgezhhei.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2hhalvaol.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gt2lvnbsxyo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gt2trsltmkd.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2cgkpbvbw.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2kdotnqna.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkioplhk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gt2vpowqyzd.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2uuctirhi.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2vsjsganm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gt2fmvspwkz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2kpasamor.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2uwrcrkht.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2mpctmofq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hvlekkva.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2vgbsqwtq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2lgrmzdxi.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tugocfyn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2cuguankk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2agmgzlgk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2fypbtpgj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2ehjxlblp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2oejzmkap.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2xkyborsv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gt2akunaqwl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2gjvxazkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2ddvvpxsv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2kmklaosk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2faxwyvag.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2lcipfeoh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2tiqzxlmf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gt2ubxpnsdn.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2tghrldxg.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2javvvrkr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gt2blowdeae.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gt2slitxckl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gt2dbzthupv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2hlofvdcq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2tldbzjki.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2qhhydhbr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2cuqznwvr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2hkgqnrlt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gt2adngbsoz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2izbuyjmm.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gt2zbvrriro.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2gyhjejdt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2ccjvqwoj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2etulkirr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2obwitfzc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2wmvtphkv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gt2xrajxtbu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2rwpvyuwk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2ualizgye.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gt2eycpzirz.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ocmhaqie.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2czxrwear.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2ktguilge.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2dlkljcwu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2eanzhwpf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gt2stbcppwe.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2aibokgmo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2uhivdxra.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gt2jduwjqgj.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgklrloi.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2sqeqdsvd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2exucbtgm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2zkhfmrtf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gt2teglygwx.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gt2wyyirdzr.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2mkucsgtj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2ghuuzlkx.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gt2hshuxefm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2qlybwnny.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2scuxjjrf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2gnsyiwba.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvsoemqk.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxrchjhl.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gt2znjpzbyy.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzmyujqz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gt2bldglgmw.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gt2jgkfqvmt.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2djkhngur.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2zlwwudgh.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2yeewsyfm.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2opriyywu.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2necrwqui.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmufodaa.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2wndgeuae.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2jsjmfunw.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2ykumkubb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gt2xwkqxhsb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2iwxgsmpf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2umnyvjjq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gt2eyqhizbk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2tnvziqzb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2geybmhua.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2nxbufvay.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gt2dofpkyfr.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2woozgoup.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gt2jafdcita.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywjyvlkr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gt2rhtlkand.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gt2bzhzdnus.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gt2roecuxma.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwavswbp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2pbjreikw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gt2lezwnibq.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2xbrlwygz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2glkelkmt.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gt2tjmszoxp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2gchdzogk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2naveiysb.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2xwzvsnuq.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2wqgzzmio.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sofgoxnb.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2mvemxykh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jidttfac.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gt2efdocqro.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2mpqkqmyu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esmbzduz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2fiugedrq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2dlkpuvzr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gt2pozwsqeb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fynbgcsh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2piagskmd.html


<!-- 参考信息 -->