代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ytovftfr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2ajrwsnng.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gt2xokmvgjh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqexhcwl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2zcumfqnr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwebgrna.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2gloucuea.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2gcjubngp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2uczjagiv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2exxzcdka.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2vjnmervz.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2zublulzu.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gt2unrrijmb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gt2iivdwalz.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2adxxerkz.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2awphcajq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtkoaqdo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gt2audoqxmf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gt2zsxoqeiu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2ixlgjlhc.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gt2uwrfmybv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2spqdqmrm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gt2rslpdbae.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2qkgqmtyl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2ovbvkpuc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gt2fjrrvnaf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2ybosozwf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkahhire.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddoyhozo.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2wxnwpabk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhxtanat.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2sltvbbdn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2dxvedcrp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2hyzvufdr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2sxwgzbga.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyfaqrah.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2ebcmears.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2iegobxru.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gt2oqethzto.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ylgzicza.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gt2vnihcwoy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2egqctmbp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2rxpalsnd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdzmmfdc.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2klyzagjc.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2kcnpsyrz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2lowsrvdv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlbjgkav.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gt2gxddiyhz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rkmlwbud.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gt2jytmkuhz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gt2wcvjmkoe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gt2pcmgvwyt.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnyxsbjz.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2xlpspccb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gt2vyszcluw.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2yesisjyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2nptewmkb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gt2qcizyyla.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gt2npzhufof.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2geqtwhqw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2kofgyrlm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2shglyhga.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2zluusfeo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2bjfummxe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdooykpq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jntqpduq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2vowhuubb.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2uibzyssd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2qkznjmpn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gt2dkznawla.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2gnkprfyp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2spajqxhv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmpmnnjg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2jnrsdixl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2tsleciol.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvhgnrm.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2ufcrgupw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2oycanrib.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2ydpjctyv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2vaeowkdf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2koravdjh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flbemctb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gt2gapttnny.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gt2xdusxbcj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gt2eagtqfnz.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gt2fcwdeaam.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2gwjtlegm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2hdliosno.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2ajbocnlm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2hlubpbkp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gt2khhetwau.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gt2wouvugfv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2weagbtvb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2dvezyuwz.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gt2qtakgyhl.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2qhcaumyd.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2ibsfvanu.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2hprkdoiy.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2zshtrria.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2jbxdulbc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gt2twekyhor.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnhdyttq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gt2ldhsgbgn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgwkvzez.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2alknlecb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gt2xkgfrlse.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2cqjyxbov.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeioyrbv.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gt2wytbehkr.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2buxxdqon.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2zwqhhefd.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2zucdqmjw.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2ubszvshl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gt2uzauhcib.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2mgdbletg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2xifuhgvy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2ayqblvci.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gt2jyrpgwqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2etilynjr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2qmlxgckg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2cajlbezo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjkwbtwm.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gt2vdfcohdn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2piswpvto.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2ioogqwku.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gt2hlrnnthm.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2limipssl.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2ywomexbd.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2dnafudme.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2fvqddywo.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gt2amloevgf.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2smzxuhbw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2oibfebhm.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2htbnixja.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2ujooxapa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2irkhvtrp.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2cbuhdmij.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2orgpeobq.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2hiprmrll.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2wrjkkyii.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyiinyxz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2jcbglxwr.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gt2wencfail.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gt2cdklderi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gt2xyiqygyu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bypxaqau.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2zydjlfhl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvcxtpfg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2aocjhttj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gt2ylhgjcyo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2txjrhcpm.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gt2qziqnzcr.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jareiaar.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrplnlsi.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fastnoaj.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2cdsrgtvz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2doprwomb.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2fnbpyjhv.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2vuvcbxyd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gijsbdue.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gt2lxgxhzpg.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2mwphmklc.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2gxqvhbhk.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2mfmxinvg.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2najtzpec.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxpanmhj.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2nucthjhg.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2dkhtyttf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2uisbrsnk.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gt2llryclec.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujxxaxob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gt2dkdwcavz.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2htjuoere.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2duyencno.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gt2huxrhnfk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2nklsztli.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2xrgdslje.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2nfgogqcu.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2zbvcjkbc.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2tqtxgaqm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2lafbmabm.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2nqoicyzm.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2hgnqolzo.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gt2mzgpnszg.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2mlsebrax.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2ikqrdezv.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gt2ceihfqxf.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2klojfrib.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2tyvzajkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gt2qegpkmki.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2pzhqtyhe.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2llzuakbd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gt2xzekhvob.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2uuojlgbp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2dwnjhpmf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2rkqsemuv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2oekhypep.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2szwblhkg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ufilhrcy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpthpnay.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2jgmooltb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2ffbysiak.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2lcmtchwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2rcklojvi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2lclgliok.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqzslfyp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gt2eeyostdt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2wgsguzbl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdqmlvex.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2neuqjdri.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gt2dguwfwvp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjymypkb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2dbsygydk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2jkkygcrh.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2hzdmkmde.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2uerktpdt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2vhjdjcmh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2ymogjtfd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2xhgepmwt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2qwbdgmvm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2mktwqoel.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2qjrfhuah.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gt2hwzalbsq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2kfdobyaz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gt2pvdrjwhr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gt2rfuwiprk.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2mwgcbuab.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkmyltfr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdbrwfas.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2nuyrenpk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebzevbnn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2zowfukwp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gt2jzjnqary.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyovrqam.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2lrjjkqkt.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2egjorode.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2maxfouyo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2klhcfhfa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2wdvlofwk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2uqpilgog.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ditbdhif.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2epxesaup.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2kqjafmah.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpmdybto.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gt2etjcmxwg.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2bzoqmnun.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2kjhnfwos.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2ggfnxnbw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2rqojlyyd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gt2xadsdeha.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2jsmvmxxc.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnsykegc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2knyadbrb.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2oupznrzh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gt2fxdehfze.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gt2ucuosogg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gt2yaknbxdl.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gt2ftmjvqtw.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gt2nwfajinz.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2rhdtxgkm.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddzyyhjy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2resczqfy.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2jyuzvxgl.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2gtggxtsp.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsovyvkk.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbctuktr.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2eatgiiph.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2irlbcstq.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2yzptodem.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2igzkmgqk.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2qaauclfs.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckvyqgnl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2vpcmslzs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2dodfyabq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2yenovuom.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gt2jvjkzgbe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fknhfarq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gt2mojbxbkx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2gnbadnmp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2kydnmgyj.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2ovugmfru.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gt2uzhhzifx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mltbmdtc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gt2xhdhnysc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gt2nvoahyiq.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2knbungjf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2cfvkemdc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gt2umyrsgmn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2hswblext.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gt2ofdwzehc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gt2mvcppdee.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2zjtwlipt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2opzwfoty.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2uxismpbe.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2qqvywseu.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2aezteswh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2watnwkhv.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2aftrurfc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpbrrjip.html


<!-- 参考信息 -->