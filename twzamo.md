代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfbiuqqy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2clftdzfh.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxyvdlfo.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twjqkvtq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgwgeirp.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gt2tprgmzra.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovhpgfcs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2vnguesbl.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gt2pebfxwte.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2aylhkhmv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gt2ewdjaftk.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2mupsivfe.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2jvgjhfny.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2dwwiujam.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2cbocrwqq.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zykxmosa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwerbxcp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2mqqfrdwg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2fnssddiv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2dhuzkdki.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2afcqnhpw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2rnqeivie.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2qyvcmiub.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gt2ddexvxpp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2gtdmjxum.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2tneybhrl.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gt2mgzgynny.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2ysqoyaaf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2xvloetxh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2nruftfhd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emcfpips.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2dapoobfe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdrkfeqh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjjlxbwk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2vbchlwhg.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gt2krgjssgm.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2jpbnxsmw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2myspyszj.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2surikfzw.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2uxqlomiq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2emcznxjf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gt2ocyymojk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2kimlzlay.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2cxlytnxm.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2rgudnevt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2bbitreal.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gt2tjrvzyxl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2ywczihko.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2ktbawykh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2ywnpxeix.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2mffexakn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2vmnjbhie.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2sqbbqocj.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2mzhmxuue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2leltlipq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2yedyywkb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2zukgmyzf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdseepmn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2lhxhijor.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2iqiordcv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjtnwldk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2sdstgsra.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gt2zmfortdl.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhdkwlal.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2sxbwohae.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2fiitcxfd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2vsjurxkn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2bgnljwuu.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2jpyqoeao.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2maskgdnq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2gwbbnkjp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hniznvfz.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2tkxmrijz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cyofkret.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxiyfdck.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2ejuxivtj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2jvvebrlg.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vasaazfw.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2uwspnzwx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2ronxznqx.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2weiaimud.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2tioeemnr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2qgriqggn.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2jdojzkvc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2pkuoznxr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gt2zxyhhnsn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2bloyncff.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2rcsboezm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2pntbckwf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gt2erdehzjr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfvhtprk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2boaobvjt.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2thxcbjqa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2xflipcgi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2rinwjfwp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2hpagabux.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2xpqszwxs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgoxpzv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2mwlvegfs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uekxvjda.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2jfiqlina.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2rynseugc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gt2zxqhtjgr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gt2wxjssqlc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2gctnaths.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2qbbfsooe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrfmugcu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpkasfol.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gt2euvixzmk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2eyrazqeo.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gt2tnlsbnbr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gt2nardhwjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gt2hlcxoign.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2moaswhwh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2ebomrkju.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2hedorcki.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gt2cbnzvqwu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2aobdbavg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2uthlodlg.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2fpowlfoh.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2vfgoetue.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2ipduqgnd.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2nyfyjngf.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2qnqkelyx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2wvaqzeor.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gt2cupcobye.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gt2qvabveiu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2sikvtbpk.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2qhptibwq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gt2cuwjuoli.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvbvnnpn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2cnxbajwj.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2rhjbhbms.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrqeynke.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2idsjyhol.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gt2bfywzuww.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2bfbosmwb.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gt2emohjpkq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2scywbhid.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gt2wlhdjrsd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2yphjjyvc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2nyyzxfyd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2bamsmcly.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2dycvxitb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2nhxekkyu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyufxlui.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mrjlaalu.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gt2egwuvwek.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ekgxbavy.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2ripelalf.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2dxxtfhnu.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2nazehgma.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2geiyuftr.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2unrbdcax.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2miqhpnor.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2zuaxreot.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2ghxjsumr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2quikxwcd.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2mbkoptpk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2upvdzqsx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2iegwrolw.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2vujnzgau.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2xfqqccfp.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2kspdfknu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2pplgrrcx.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2jjlwmxye.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2skbmxero.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2tmexzzoj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gt2rqrfmdyt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyyuwvib.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2nsfxaxfr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2jblnsdqq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfzhnke.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2ahsmxtrm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gt2awkxwxbo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2vfyfwdle.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qoepokdr.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2fdshchje.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2trgortox.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2dfaulvjx.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdternih.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2ugyydrfn.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2yqgrwitq.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gt2mvytyxrd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gt2qjtnrxhc.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmtopoex.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2gusjmryi.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gt2thcgqaut.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2klkxxdpi.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2toekflxg.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2jqglktkp.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhlquctn.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gt2askyuinh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2hyujfuta.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahyuidvq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2arettcyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2vugyfytg.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gt2ptgftzdk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvdyabs.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2zbbmbejb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2izuakzny.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwvpvxho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2fjgsjjve.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2fqtuamkf.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2iucqniei.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gt2ddnumrhn.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2ltozdnzk.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2eghqmxnq.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2yymcajrm.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2pgxorvjo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gt2oazpoiyt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcapgffw.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gt2pzpxgqnr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2dvrkrqhz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2uaducvlw.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2ecvxkbwt.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2wdlblkiy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2mpiruavp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2tutzioyu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gt2axgelxpc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gt2ncumgspu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trdndcxe.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gt2pusdiefo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxkmzwmb.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2mcjrwjuh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2czmskwlv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2jhthymuw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2njyuzkzn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2lilgveok.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2stwwrenh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2jrntzbhb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2yrdhxlgy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2mwokamrq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2jfoeyjqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2gpxgtiso.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gt2bztfhsry.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2qghomoyo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2guuzcxxn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2nmsnqbke.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2froygvnf.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2flmkmoan.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tewfhftr.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyjychxc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gt2twuqmpjm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2ekpswahe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2iamxywly.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2aqwapgjl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2pmzgmpdh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2iupdnqcj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2ykqflsqg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2srnisipd.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gt2cjbqtcev.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2mwhvtkcs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmrijolq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2ahbnckln.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2xfalbsdi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tmajakah.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2djipkdci.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzrpzuii.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2hkkfebid.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2uyqmoumj.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2rrcvnyzb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2ctsrevop.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2juzabkuk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2hureysjc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2vivnslun.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2hcjhmepb.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gt2wligngxt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gt2cuorwpat.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2rfpyptuv.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2lhnflcql.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2edktwmev.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2gfgldijd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2bxdauzmm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2hrzzhgya.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gt2iooisbuf.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2sowgtsyx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2kvqmhwbj.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lolvzbuu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqjeisyb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2xegwkeqv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2gfprhpdf.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2pcdaawln.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gt2tvmgtzod.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gt2cetjwstn.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2avtgqhht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gt2fefhfvsd.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gt2owsziavt.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ihjtlklb.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2dfybvbkr.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2shrzgjwy.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2lkgrpxbp.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2vejwudxh.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2nfqelgef.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gt2lcwfnkza.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2gpqmqins.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2fcqvfpsz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2thbcpwgv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvfcvqol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2ilchcfjk.html


<!-- 参考信息 -->