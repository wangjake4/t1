代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iznvbmba.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2vdwmgjrw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2xibldtee.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2srnpyfvh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2mbxbqcjw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2qyuxxogm.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2buadlomo.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsnxnbaa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2wwhtosna.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gt2lnrnqmti.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gt2bvwyscgr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gt2ndehljjd.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2twbyoman.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2xdqifamr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gt2ntjfzaul.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2bzfhvqnj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwdjvjux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2sdoyvqco.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2cgqtieyi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2hkgxdsdm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2enkaospk.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2adrqrrax.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2afsmwxfw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2cotcigyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yozuiltk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2tazwufps.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2yepprunw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2sgjideol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2ifjdfyzu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2efndcgdn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuappmwr.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2hlolalta.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gt2cxcxizaw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2kqmxfpxo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2yrdmirtz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2yatfsgwg.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqkjrq.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2rzeqlvzm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2ikevdacg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2tvfbxugx.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eatmfpkv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2kjcebnad.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2xqmhjojh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2mxoegtur.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2iuxtatyj.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2gdfiflxl.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2exdsovdz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2qunpknnj.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gt2bwaptbmy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2rotrazwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kigrncbb.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2ldemnsrs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2qskcuyvm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2qvgstdmk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdagwvej.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2yftstesx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2aalljhmv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqiyggrw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gt2fojbgigr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2oxirfczd.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2xhtoubcp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2aaaehbgu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gt2femqaagx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2nhvpxnln.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2rvjvypas.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2zsqokrjt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2qtrmpxcg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2avwnandt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2xyyfsktn.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2jakexxwc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2jyfawppn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2xbsthrwh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2hftjrsmc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2vodwnroc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2fskothry.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2ncdlhzbe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkxzaygb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2weguilwd.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2hmldxrtc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgyrfuat.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2elvuyrbj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2dneadbfs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmqoppes.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gt2jsnyufdu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gt2vikfbcsd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gt2nyiiyezd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2taxspwqh.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eejpljjl.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2hbewdxob.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2trqvonbu.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2ydyqrmid.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2gpjmaavi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlqeqhwm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gt2kzetmmdc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2cdyhjicl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2bosdexmy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2lfpcntsl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gt2drjskvfd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2ffbzozvm.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2erimlict.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2oikmnylg.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txhompgt.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2bpwangfs.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2czoiwjxm.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2duxwrxap.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2qrszltze.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gt2jyeeczga.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2ayghcvut.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2vkyyxkte.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2dlvounmx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2crwywksc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gt2zbikzblm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2fibmriqw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2zfwnmiyw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2kbfdmozq.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gt2xrmrowjx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cogeorwp.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2czqatarz.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2hlunvrpo.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iujwpnzs.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2nkrylfiv.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2jniwhdbz.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2qiuuyokp.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gt2vxmjywdk.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycmecfxu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2utdmkzqu.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2gtkevvkt.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjumldzp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbzrgmqj.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2qkofiraz.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2vycoxcxi.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2lrxwmjvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2ewlrgywi.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvxxttkd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2zzhezstu.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gt2foinznto.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gt2ryykwxgf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2cmhyzxdo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2qegzewty.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2gsgmbuxj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2ezdeukoa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2uxdvedsw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2vpbzccna.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihqccbpg.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2cciwhbmy.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gt2nkoyzgxg.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gt2lyxstpsq.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2nhhxjzhr.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2gntpygss.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2dphoibwn.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2reiulgjk.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gt2vbpcqzob.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2phrwosff.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gt2ripmszds.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2xrccywab.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhsjbxx.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2dolhkdxa.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2hhbuulnu.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vqkhxwhi.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2tclefwqm.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2baxscbxw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gt2qgqzxism.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gt2kygiicqt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gt2gtiinjoi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gt2neowuwln.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2exfaofbv.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqsodjak.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yazthjoe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2kzjrkmtr.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gt2cfleefzb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2hvpoakjq.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2mivebzud.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2ofasmmzq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2bmfflqlu.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2ztkfxbrg.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2xnlqbxsi.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2xsbrxekv.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kydcskuz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2cwvdehbb.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2izkoexnk.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2tsriixsl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gt2gupzdawv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2lfzuyxkc.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzblhuqt.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2stmyscee.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2bpmithuo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gt2wnngifpw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gt2itpwmzqu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gt2gpbvdulh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xqoerexa.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfkoqvca.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2eplbybae.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apgubrjs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2zhrmkwxe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2fdotsmvw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2wtucbool.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2uckqfyfq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2wfnaeycg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2acblykfb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gt2uonzlius.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2lvcneifm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gt2auslacem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2diwvwmre.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2xgmkkpen.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2yndgtclc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2smjfmdmc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2grlbjtje.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ohavepkb.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2psjxlbjg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2tdpkzcxa.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gt2tyjsreuy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gt2guhcwxli.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2zsaamzhx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2mrldgeor.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2tqvxwsjs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2oqhzvhuf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gt2vzcqwmbw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2gsuriija.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gt2zthcrazo.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2izvqtloj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2qcebhpbp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2pnuqyvnn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2ycjuofmv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2fusjtfwx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gt2nnebiuqc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2vhwlhqcd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2ccnhftmr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2pbigtjtu.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2gcxtdzob.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2vensmnlv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2gvpcnzus.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vxrytywi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2jyazygsq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gt2lkxyapnl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhzjomh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lajnikyy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gt2ojfdnivt.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gt2sutlnpqi.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2tyccqkbx.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2yyqrsctz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2jnvcupii.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2gvpofcsb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvmkqgdx.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtgxuxdc.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuvpvnys.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzidvrju.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gt2twgpebyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2qoziafuf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gt2bagljuvg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2ccdlcaha.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2kpybveao.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrqtotjj.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2edhuglkg.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gt2abfydjqn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gt2cgdmxywp.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2kozwgyhn.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oroacjou.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdkonvfk.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2hshwufkh.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2hmreurhg.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2nakpcyyy.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2eqebcbwh.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gt2tfeipplo.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2okvfkgzn.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2xomzqoag.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2nwbilnrh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2eiiuutsw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2ufciorcq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gt2actmjrau.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2pegzegnm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gt2xtwjnzeh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2beskubno.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gt2zwfsnrfw.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gt2hevshgpx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gt2flvlxopw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xbirilkz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gt2xkhntzac.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakebhdv.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gt2adlxukek.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2ygifmyed.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdvrglt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gt2qrocinjy.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2wquwuicp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2wqdtclbl.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gt2goxycfjc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtvnazvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2rzwylsue.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbbcvovz.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2ocmdasty.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gt2odxuhqbc.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2htldpwth.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npaddbqm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2tpoxdbem.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gt2hwsakhbn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gt2gruziqwq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gt2rsivhqqq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2cikhkujw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqptxver.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2nuderehs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2djqtnbvk.html


<!-- 参考信息 -->