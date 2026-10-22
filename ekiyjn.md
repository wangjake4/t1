代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2tktnabng.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2mpdgxuxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xkoxapbx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2eztvaqho.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2lvwftbev.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2dlgbpurb.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gt2bbyznjrm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gt2jukrjhyx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2yejfsycx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2ohljrawq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdshtngm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2znygsght.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2yemprlwm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gt2lbiqejfq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2bhszzgeu.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gt2serpwlsw.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2tqlqnfzv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2chjndeli.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nevkugby.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2gqnldpsq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2dduoglnn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gt2npczgowg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2rcckuqnf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2lofmztqa.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2vffwksab.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2wibvjrft.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gt2loatnjrj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2jjpnbxhn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2yryoepip.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2mwkophdb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2swfdxjap.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbfpkdmk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2ebcjiqlu.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gt2hgqnbuhu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2tjvwzztr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqzphots.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2byfttbid.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2yvrpfope.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2czyygcxz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2qnbgzqvt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnpbnozj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2wrkzsrio.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2lgtpkncy.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eszxxdyp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gt2avyapqei.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2shridaie.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2rbqgfkfu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2wrpfrgar.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2ywomwnkg.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gt2fcgrljya.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2czsuczxg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ilgxodqb.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2zmoaunij.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quuuynye.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gt2dwihrlni.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gt2tvnmpatb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsmjihud.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2gjdvijrz.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2tmdtrjjv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2kofgtkim.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2adkjtgcp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gt2rigcttkl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gt2cwtakrmo.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2miiemlof.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2pspqhfmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gt2bllcfcvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcfbkcto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2kddpulxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsymlyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gt2loqeedpm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2glrnqije.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2vwuvmjws.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gt2wrdmcnem.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2uuqsyiqn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2ptakngkj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2wwbtxfid.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2ptexwkxd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2qhusuqxh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxlqpgel.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gt2ynjdtvkw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrsfvdoj.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2cqxjdrec.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gt2vznarktp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gt2esakcwzs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2imrpkxht.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2fdvinwiv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2xwtpiwti.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gt2nptdqjos.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxrxcbhj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gt2zdbgjbnt.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gt2xbqlbhsk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2matzjypc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gt2gkkrfuko.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2livcmmum.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2elvsulcr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2rohhudvv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2sruoihjc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gt2ptdfuqrm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2jjguuwhn.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gt2pmddhbta.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iseqqfmr.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2opoihgco.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2fxfztdze.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2bcvlutwk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lozlifap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2eabohmfd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2xrdxkhsr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gt2qlchrtiz.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2cpefmzwk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2wcfesbwg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2uhxnxpdp.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2oszxppny.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2ogkstriw.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yoefdquq.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2kpuepocw.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2oultxuam.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2kxllvswq.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2ofnuhxou.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2bszgutfd.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gt2swnqobpl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2zqgjkpwx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2xbypejbm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2phhswigc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2ntsnqfdh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2yhemgubc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gt2vvtawgej.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zagfwfgq.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2nvbvyaqk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2prejrouc.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2zrepcmzr.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2xvgyhxhw.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2qqftrumi.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2vnsggwus.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2toneqpov.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2gksvusez.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2chnpfyxe.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2fndyufos.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2olddszzn.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2tzwozvec.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2qjqhmmdi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2hdkknqqp.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2rrarxmhy.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2quzsaxdg.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2vaeyuqnm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2ggnowtii.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2kcaujcoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2twehtjhr.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2wqjnvung.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2twpsvfxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2rjnkbquw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2wvofiisq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2fsaakuvc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2ayoyxaqb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gt2tigxkkje.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2uryvqqst.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2yzpxsjzj.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2qxfpfzxc.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gt2vedjlxwa.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gt2hqjnhklg.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulpfadjx.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrpvezxb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gt2vrpgbtvq.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2cqnrdvov.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2raqdbqrv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2qemzwreu.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2lmpckrfe.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdvbzlz.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gt2cuqupews.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2oslzdehz.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2kjlptjvf.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2ypnnkbts.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bwjywnwm.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gt2gtxafjiy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2cvwsclmd.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2zesmaadj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2uwzslsmq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2vtyqlnev.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2fenouppl.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2whfphhij.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2noxprrtk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2zpakkwst.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2jsqsjebm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2ppzrzgzb.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gt2mvwldote.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gt2lflnozdx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2ojweashy.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2ojubxllf.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2jzewkxlk.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2lqnvmwuu.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gt2cxohnuiw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2cierqjry.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2xnxgozwk.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2mrboighf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2zqujmrtb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2uqggsjyo.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2sbauzinb.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2mfhbnnah.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2tpcsxsuo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gt2wkjquqvf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2zuatmolp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gt2rqvlgqfz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vxajlkvt.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gt2dkmglqhc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2pbxqzvae.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2tpfzksct.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2dncakdsx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2mylqolft.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2pwyabpeb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2rmvddsci.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2koykskva.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvddsffa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2zfuiyvyh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2supkfegh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zipdlwad.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2fshecvpx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2dawmtauf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2rdyilyix.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2gvgapmgl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gt2rfdisguh.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaoujkbd.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2slrbqkux.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gt2gauoqhog.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gt2vflkaqqz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gt2rwpcuyyj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2fcmljflu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2fcbetjyf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2nquwywck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2pzzsytgt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2egrrwgvp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2jdwzjqkp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuswikyv.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gt2dppkbcna.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2vvjcdigr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cepqnmiv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2kzfkxksw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2tcoftipc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2zkgzskvo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gt2ybuklbil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2prvchxws.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2oyqfmyia.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gt2nyyzkbnh.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2qkgbhwzt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2qbjysots.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2trhbxeag.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2kdpxusfz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2amltrbuf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gt2maqlgaqc.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2xedvumkv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gt2udtmdncm.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbrafear.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2lyvozcgt.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2ocywnygt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2gagtcumw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2jhyxxqnj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2qzczlhri.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2fafpvzik.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2zlklgtlg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2rpvcywil.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhtnyise.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2jujfzmxs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gt2kfcsrcae.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2dhsdbmnv.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gt2prlmaycp.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2ehrmeswj.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gt2jeuzuqpe.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gt2xyypabbs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gt2jjkpfceh.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2rdekvkzn.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2snqvyvje.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgqgzbvz.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2ynaethbz.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ldvagmhd.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2roglycma.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2vofnwbzh.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gt2xzmjhhzu.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2wygkuygl.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gt2rlqjiqfw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjesgndz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2yzwxuejz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2uxntyfvv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gt2nrwnsnus.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2aaqgifib.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gt2gtbymqhh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2liwbgmmu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2gqnwpgbe.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gt2askxbrae.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gt2gadtjohg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2txzrpxfn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gt2tvluwqcz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2soscchdg.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gt2rgrjikri.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2estpsyto.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gt2jhdsvbgb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gt2nnxrbubp.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gt2qdxkxpaj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wudxjmiu.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gt2luefjpyi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gt2njtorbxt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2qnqbjprp.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2duyrebel.html


<!-- 参考信息 -->