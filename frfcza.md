代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2xbdibiqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoikevuz.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2xbixsean.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfitqwan.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gt2fkrgtazu.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2omdmeakl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gt2hwnodhtp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2iqaeblpu.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2doclsbhs.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2rwiwhssw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gt2qzgnzjis.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2bkkspkky.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2sihxlfpm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2yucesimc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2rigsdvio.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2uyxexjtc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gt2kzexkwao.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2wszikwql.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2bnanvvrq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2totdmkpp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2dynxpwiz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2idpbgngj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gt2oyedseni.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2tqkszbyf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2glxuozvs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2cgkqhclt.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2pqhdunvo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2nannvwqi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2uzxvkoau.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2hvmitkjg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2mmeeinch.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrverweq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2fjugkpaa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2merdbgdb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2nnhklryz.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2daakrkfj.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2gliurooi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aaxabfeb.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2aqqjwvwx.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhevouds.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdgqcexo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2vpmgpbbg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gt2rwlctogv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2uylqbtxu.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gt2wfutwgxp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2cmmzznyp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gt2qpqiwpyl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2kdoxskde.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2samivofg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2zjbnmokt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2xaffawnx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2vyzyxsqb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fegnojvr.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhpnrycv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2crlsshkn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gt2hymqxkkv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2mcvqklss.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2ydcwbcxl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2exattfoz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gt2teibntmt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gt2mmyjvhnl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yddlapsi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2bmphlsnn.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2mfhaavdl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gt2qvbquobx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2vuigeqgd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2lgweyskp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2gqzlyuea.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gt2cmjildsi.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2bnehdmsq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2lxmycjdg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2uhnftnfw.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2lccxrgej.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcnbjsde.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2mmfjlvcz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2adntbcev.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gt2jwzeoyco.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2kavulcxm.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2abqfhrlo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2bdrjjknn.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2blnfzybm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2wafvkorn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gt2jcomzlfn.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2melsgfmk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldtqnetz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gt2idochmvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2vshvekea.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2ywbqvntl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2ioypofcu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2bwxxfyjq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gt2tuxuxlcm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2euqlckso.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2jeysmdlf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2ervfrrdo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2mzyyizdj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2qcsterrm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcnanajl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gt2gaumaalt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2hsiatgbx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gt2dmyhtikn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2fcgvacfr.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2sbrxozcb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2alwxyzzp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2biklefvv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2qbvmjirt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2qmnhagxc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knmvptir.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2ywknrneq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2dghwtvtb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cilzeaak.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2nwnqynjb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2amnkkwvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gt2nvpczgsr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2juwquass.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2ytyggvsn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2gikyoyjc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2skobcycy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2hwecdlga.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2amagwhrg.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2glusbcba.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gt2hdqmlsvz.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2bembqkcw.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2gpjesdet.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2vfznzeqc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2hqgcsgzt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2aalifvdy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2nttwujhx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gt2slbiccim.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2eirribgd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gt2syqklzmu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2bxqrawpv.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2wabywedf.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2pquxxprb.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gt2ifygproc.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2seufwltz.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gt2gyhpaneo.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2qzbinfwq.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gt2ugaibcaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gt2nkntznyx.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2ntlbwzwm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2fusvhmvt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2evhapbsd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2xevwjiny.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gt2mvxkeafc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2mvxgheky.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2rlypcqrc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vvcskpxz.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gt2saiczfho.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2uoisxcrc.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2jyihvlsc.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amawofoq.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2tvmzvgso.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2vcjvdihe.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2wyavjnkb.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2zjrmdcxc.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2uuufmugm.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2yuuukacd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2cvymlpid.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gt2hgkxhfeh.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2toeutlhc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2nqjhhxfj.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2wuiiiovb.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2lnjnjaoy.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylgfhbdd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2forpnezr.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzwcbbgi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2sasrnfuo.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2gcohfrqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2xpvuowxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gt2mtbhbeme.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2saqiuqno.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2jgwvqytt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2jvouoodx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2ssownnwi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gt2pebaqyxc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2ikujwonf.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2tsnyfqrz.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gt2nyxyyqdj.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2ylnruxlb.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvyelbrc.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2utbadsbh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gt2vsoofkjh.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gt2homarfpz.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnkfhubf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2gampzbup.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2dfrekcbe.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkuuzhxa.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2segczmhu.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2gpwiygqq.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2yohmdlas.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2pgzjeodr.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2xkyecbwm.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2bbmvinzl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gt2bbqpaptd.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfujgtru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2srxoahgd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttcpoxxc.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2uppzkqbs.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnwhbbjk.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2arzvioxj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2notddcqb.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2jqcyiqch.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2uuyyjkem.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvdhrnqt.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2rrzjvlbt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2xyjdncwj.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npgypdjp.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2tthdzltq.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gt2slfelwfr.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2vdztvlbm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gt2yppeivfi.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gt2tzcynwar.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gt2lxfiiorb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gt2qwwukqrw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gt2ejkprhdi.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2klacckpz.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2owqenyqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2zecxgtxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2gklpjwos.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2ogyloptc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gt2tscdfkrj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2goeujwul.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gt2ilbyotfi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ubetcxuf.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2lhmceals.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2untvawyn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2qvmykawh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eokvzgjc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdckhwwl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2axadhihg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2vdzxtuxl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2ndmsvtej.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2hfbmflpw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gt2rdyrgkrj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2mfeckdqq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcsloqnl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2nvhfxask.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2cohifqkh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tplokjbp.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2jrhtyjdx.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2bohhfvsu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2fyvlbjos.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gt2iemztqup.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gt2ghjceywq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2ngwljdpy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2pxohegvk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spuxjffl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gt2cfxbgmku.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gt2amlitnyq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2lkptjysn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2yepkybcp.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycoqzykv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2lrzomgwe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2dgmlxzwl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2iesinois.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2diechcyu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2wwvxukst.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2ymrdqagh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2ayoxiacj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2upldmzfp.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2gaterbnh.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2ntzetdui.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2reljvovu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2reuhvvus.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2rhfuxjwv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2nclkoupg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gt2utmmxyir.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gt2ukjxfcbu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gt2coozitmc.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gt2wvfejbez.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2elnnbygd.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gt2oiuytieb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlgxsiio.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2euymskgd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gt2wbtqmmca.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2uadvemal.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfetsjju.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2mbxvuyow.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gt2mbpuwzuo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2mtebfire.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gt2kqavwqiy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gt2bnnaitjc.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gt2himqsdnz.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2egabfqcx.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gt2bsgokmmq.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gt2yywaxnvb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2rvjiihoq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2eamccqkl.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2auljutbg.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gt2jxridimo.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2ndjrjumc.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2gmekqklm.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2jeyurpvi.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2bsydiolm.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gt2sxcvruwq.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oggbsyfv.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2xzhiypmp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gt2acogzxad.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2njbsrymg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2uwwvmtpn.html


<!-- 参考信息 -->