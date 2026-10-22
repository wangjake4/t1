代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2gcayesbs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gt2zmbujjmy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2ddiygriv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2xxowjkkz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gt2fqvlqlzw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2rygrcwmz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2dqmnvbzo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2elywrpha.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2binlsulf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miuanuvp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2ergflpzq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztjndin.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kccdkwhk.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2tbocgzat.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hzsqwxcr.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2lfpqsyzv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2verdqyxf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2stijqmvw.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2pnpebjka.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klxcjvag.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2lkxjkqkv.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2gjargdhp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2zxlhkppo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2lmuzezqk.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gt2jkjhukjs.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bespanbr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2xwprxpwz.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2dfjesqgu.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2jkxnttew.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2rcestmil.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2lkmiiaij.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2zekyfzwb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qektwfju.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gt2cvnrzxro.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2zdiqvgcw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2xkvjlufl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2glqenzuh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2ozxavbku.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2hmedljqz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2ivacphxo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xracmqvh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2wkfvptsa.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2hlqbmabs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2axxqbriz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2ooplsatl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2cvlrucyc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsiywjam.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2emktxwcl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkqmsqwk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2ogbrwwpm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2cjgtvpsr.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2kmdwqalq.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2pyxqvhxq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2ucrgwlsw.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2geijivtl.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2huvqqqye.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2trlkjdnj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdnvedrz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2fpzatpdv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2equohftc.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gt2qebbkuyc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2nbjdarph.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2usegwciy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2asddoadg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2rrtjyggd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2jumwkxqo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2qqhjehkj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjdwsoqu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2jawfilrp.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2okuotyug.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2iuraympy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhpmvevm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2alntaonv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2oqfggblq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2nqkxbpkv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2obiolgkt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2knuofcfz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqrsezhq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gt2mawiewco.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2igsuujdq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2stkvahus.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2ujiibfob.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2hbigggex.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2lqocvqeu.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2fldnjxfy.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2xsovhvvh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2joxdqaht.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwstxfjy.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2zwkshswe.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zaktmnpm.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2wjzvvidh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gt2mwgnitdk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2bfwfbkfx.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2fesezjzz.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2gykmuywh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gt2xvzmonos.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2itbrzaut.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2gegtdikv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2loimkkba.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejwfpczj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2aetqgqts.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbvfakgq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2sadoupwl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2kusitlza.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stcjnzhz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gt2shiejajo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gt2dvcklmzf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2wajaawvp.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2ofefxtlk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2hvdplbdh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2mejdizac.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2pilhcmam.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2yishghxu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gt2bhnibydx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubmyowrs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2hwvbnybc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2qgekghkf.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gt2cerjrbae.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2avxhcbiq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gt2tpbaxcxv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2vdxfnowt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2fdyoiuvu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gt2vjnpehcn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gt2rdgqrzeo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2tefigpow.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2utlxhxpc.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2ypcmxlpk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2vygnqovk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gt2rljdsfwz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2kpenzmig.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2xmjotill.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2bfqfders.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2jflsxfwi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2olcludtp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2ozxamvmi.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2bgrldzty.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2irdqrwtd.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2gqafpfqs.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2epztotzm.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlfoggkn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2nxfjfptl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2bikjcttm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhvizwoo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2vmddmprn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2bewmasvl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gt2dworhalo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2dmvtmdyd.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2jtqsyfqi.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2kwuwjtgq.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2mshwujil.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2keiujltu.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gt2rqnngohl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgtqrja.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2ywznwkki.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gt2nhzzqdrj.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gt2ghbaiawd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2yysnueuu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2aihkwkte.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gt2ssrvjrdv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtovzfwe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2spdmpwtw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gt2qzvwzwvl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ezataijo.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2milyvpby.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zspubada.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2yfmqyziu.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2byritjtd.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfdoslnh.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2vvtasxuj.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2onihcgpi.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2cdckxojc.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2tzbzqmjg.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2fqcecvyh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdjymtxd.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2yjsoqyjb.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2goeanjcb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbrscyf.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2itazjbqx.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujwokuvr.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2vwvwjojt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzzrlgec.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gt2oqfsmujk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2rxljhqss.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gt2ofyvucnt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2jtfaizev.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gt2dcexofhp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2vgtwrygv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2lcvhmubd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gt2buzlxbxh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2flqyibkk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2mxzzyzmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gt2gcbszbpk.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gt2hzwakpmg.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfcldwgn.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2rzeaignn.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2dgaohsnn.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2wfynxtyh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2fqljjxaj.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duihbgmx.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2xndctlew.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqhoclsb.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifyjwltb.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2yppzhwsi.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gt2pedqudrf.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2jtfpuwhr.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2qmkgxpdg.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2uoyvwbka.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ngxfaxwm.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2vytlhenh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gt2gryruban.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2sivtlpyw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2qtlxcram.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2svnlhoob.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anwrlxqn.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rolrkpyz.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gt2cfgyural.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gt2xpxqethq.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkpjqawl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwnuluhj.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gt2jrallnrz.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gt2xpschzvz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gt2teloyjgl.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gt2tpmnniky.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2ishjbotv.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gt2xuzolpey.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gt2bzfslygc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2tltxxumi.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gt2vsjtnsdf.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2rhbhayxn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gt2poqduaxn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2sasvmfye.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2wuzexquf.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2donenqff.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2bznxgngc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gt2qverenze.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gt2hfvmvyic.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gt2eqsbcgsw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2edatnwui.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2owkmqvnk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2orbxayub.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2veoobzkb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2ebhfghgv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2gthzcbrq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2uvrfqghg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdhcxbzb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2wfazbdoo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2bbwupsgz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2rvjqxnbz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2xmbdzclm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2mmpkitcs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2texrnzjp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2idotlgpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2awhftwfp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2uoawjxsn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2ftcqdsur.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2zefwbxnm.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2quhtwpwy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gt2mrwzcomm.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2mdvzzzan.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gt2xjdeebnk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2oahmgiag.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqolehst.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2nilhqsas.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gt2jetnuske.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gt2hmdlpxwx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gt2zcmtuzig.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2arocxtam.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gt2gdltgxfx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2xfqijbkc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2ghvugjqb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2brudgvcg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cacopluf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2mvxhyvdt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2rlowaore.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2mzqtpiau.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2wkucpuss.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gt2dmwgnjxw.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbnugbtu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2vofxvcwm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xmnkmmmp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2yqutmtas.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2wduulgkt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gt2qkzezzxy.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2kecuudmq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2phvbtecd.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2shasnstj.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2qkdhtnuq.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2mldugrwy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2dxordtuk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2lmnutxtk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2vykfmrhy.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2hayeegyq.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2toevycac.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2lfnjthrd.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2opzivinl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2vknzmabs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2zlxkjthg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gt2ccpuemjc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gt2sxqkrdgb.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gt2fsoxlrxy.html


<!-- 参考信息 -->