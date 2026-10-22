代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jqrpwwdb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2swmthsyr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2jpokwafd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2ylcrvecy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2fwkudcog.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2jphincei.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2egtxqbcj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gt2rhbtolxw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2gdkdxqpf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gt2gkbsymtg.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2xikauipi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2vzoooxcw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gt2dnirjrbe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2qszgsfvc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2iueytlxv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2vnepkerf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2zbeshfon.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2ogexgtiw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2ljwlymok.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gt2xsrhkkbe.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2lxejtsfc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gt2cyudoeou.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2xumkjvmt.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kstkquej.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2epozokqe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gt2etknxxvg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2wequjyfy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqkucjnd.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2thbzrixt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2ptzflvqg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2uxagdrki.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2qhjmtatm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2wcdfsqmf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gt2qqpqncaz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2vgrdmxys.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2hbasrzdz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2acojzrdv.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhmkppv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2dskchtyg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzhaujsq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2getbvmkl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2fcontomu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2ndwpvsmt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gt2pveszdxk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2kywqkxlh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2kbcemikw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gt2tkswlfoh.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2yqlorwmp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gt2hlngzjws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2bdvzkryh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2jefxkfgl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2holwggnh.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gt2tpriwnkp.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgyvygzl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxlxtpha.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tcnlgqsq.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gt2omfxqucd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdqkgndg.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtohrinf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gt2sqgzgooo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwnajapw.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2tcihygtm.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2cqkaudcb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2uwlxuzsr.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2tgjiaoaw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2btzcruzk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gt2gkxfbxts.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2oinsvbbw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2trdbjncr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2xujkmmct.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2cabclwvk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2oniwebah.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2jvacypha.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gt2lpapahqu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xajeuopp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2tyfudzkk.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2oghjyuxk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2tvvbhhyh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gt2gtedzxun.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2plyeptto.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2xndkxhtb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gt2htlgipqz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnjacwi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gt2qirfyrbp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2kexwaqkx.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gt2ahgrkyya.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ledasapn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2utnauclp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2vyyogsbe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2gpcladrr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2vtebcfkr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjdfmzu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gt2jbjshran.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gt2ftzbygoi.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2ukcfbqwd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2bmneatii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gt2rncgcntt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2kqrzkhpa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2qoxnvgbz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gt2ghpxexrv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ldgkrnwa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2mrvhatoz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2aigiiirh.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2pxnexjpx.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2pwljwvtf.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2btutawcs.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eridpwfa.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2mgkqgdzz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2ghxgszsq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2gskpkrzi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gt2mjcbrrrf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2chrldfek.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyxqxotd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2wtdsgcze.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2tomrjbmg.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2vrkqhwji.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2qxbzlpeo.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2fpdnnezc.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2qwykrvph.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2cmptzfag.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2wvzshuno.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2hycggblv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2udhxuisp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2siwofxbr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2gqrypokx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2pnbsicyt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2cgaygytz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2splqkhju.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2fkoywjbv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2qqweueoa.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2obpfmkfs.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2mfmejfmh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yqbivwff.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2ppnpouww.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqlczwun.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gt2qtgjzfwr.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2fuknvdpr.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2jxfvxopm.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2naykijzq.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgddgepn.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2bwpeemrv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2ubkhajsj.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2luldfddk.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2nixqsyao.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2jlryhbdv.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2xsrqyyws.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2pkqjvxvw.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2ghkzlyhs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2lnyceipc.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gt2qcmanqfm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2zztqnjgx.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gt2ktbdbtpz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2lpjjhsbp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2kyeqpjks.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2nynatvjs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heqnadbm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2tauuqlke.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2ecyhwugp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2oibqounh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2kebtxhov.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gt2mrzktxxy.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gt2oqqzokqc.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gt2sihfhdvm.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2qdtmypbe.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2yvynhtqx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gt2gsemcwdz.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2ejtwhwhd.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gt2qjrfojds.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2ymcsbell.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gt2chtpxzqo.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2jskfdtjg.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2oxjpnqhi.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2druebnnj.html

TS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nbetygza.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xchpxlyn.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pekqqugr.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2hkfqjayf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2wxihladt.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dphhqesz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2opnolxyu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gt2yvhmxidu.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2dbakqaek.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2vhmnjses.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gt2gfsbivzv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asneemwm.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gt2stwrtslt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2ogerzmfh.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gt2ktchhvsj.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2ayirtpdn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2sfppkfzh.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2dbtbceqf.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2ivsjhzhz.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2fgabbtny.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2vaiguace.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2issakdkz.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2hnxbliqw.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2vsjnzuzb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2caqobpki.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2pzxmawuh.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2tokmclmp.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srbacehi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gt2tkpfrfxi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gt2xtsjpbpm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gt2wslwjbeo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2pnwcbqxm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fzdmjnay.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2ixevgolw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okvydowi.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2nbfaaegd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2bxaejqgh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2fmqubfyg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2fkkegthw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2wboiehxy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2vfeenbgy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2awuvhxgd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2hpjckqmt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmbqwwad.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2mgiendxz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2nyneykcp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijyslcmr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2yuljblov.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2wvhhglej.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gt2peyznmcb.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2atreygtn.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2otatjzss.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2wjurhtno.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gt2ajswnrbi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gt2aitbjvvv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2sxjtaxls.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2jgeptcwa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gt2zwqajfyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2wtjfhdks.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouhjvrae.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gt2serbqksw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gt2geggfclr.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gt2jyemyzcw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2ojkasuuz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsoyesju.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2jmzarehq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2uvkmdhft.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2qtiyvbyp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gt2jokquqva.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2ibhwskjh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2yyasmwen.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gt2hjbuafwu.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2qneqyoem.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2mpogjlte.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2scowtuqt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2vkfsqzeg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gt2nljknbln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2mxmzwrxu.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gt2nenjruun.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2lxjwctmp.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gt2hlikgybz.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2sufuusbf.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlgxpvrb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2olmejgsi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2udrzwyrd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2suataink.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gt2kxtwlive.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2tivzfjqz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2juiuzmkk.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gt2gshmgmhl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2wcpxswtt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2mzrmcorl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2cvvqlfyi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gt2czuuhwju.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gt2hsjugsnq.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gt2qmpnztzd.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gt2nlxftacp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gt2tyrvpdgp.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gt2cjrxfkwt.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gt2khbfoesc.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gt2zhqwnyet.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2gabmcbtm.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2biqfchfd.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzqzdcbc.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2hwtmrnln.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2thmpqmxf.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2lyfcgqep.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2yxthneew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gt2lawercrt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2wgolrnqm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2xnoedrin.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2cmqmnjuf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2xofkhvry.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gt2kpwadbtj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2cylapozg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2swqbqxvc.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2dzypkcmm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gt2tcbioawm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcmdmfef.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gt2atkqvpzk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gt2mnuwstgr.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gt2myhzejvi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gt2iegshujd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gt2wmlmdayf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gt2enxvnwxl.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gt2ycnknxau.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gt2xktqnqdk.html


<!-- 参考信息 -->