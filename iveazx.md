代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtqbizpgir.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtdpyefgkx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gtokjxkdfu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtmvnnepua.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtalhwdqtd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtzwlsznyx.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtsrndxssu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtylyroqmt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtvehcrysv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtpaygrxkx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtxjlcukej.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtbtxpoilv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtmrxxqgey.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtopugrrsh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtajunsgmg.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtsyvfshod.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtfstkdvvy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gtoaiyntmi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtictocixn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtknuktkya.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gtoixdvffm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtcfonljka.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtphkvorad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtwpfvmwck.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrokpygtc.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtyppltucb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwiksrtom.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gthlhxqxbr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtovbytgor.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtaegegmga.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtvljifpbd.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkerudqic.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtftpgkvov.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtahnjhyec.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwxdblkh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtijosybjr.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtylnrzalq.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtonkskkys.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtlflkvtpe.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtcrklvzlo.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwajsvggo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtcvaclaup.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtykongfik.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavogbzrh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwwdzqlsz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtxbogskff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtaaaslduz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhgjtav.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtztapdska.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtfdfubpjs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtjdaaducw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtlyprpoym.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtjklsbpyi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gthbexiejp.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtixixjkoq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtqyyrseks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtsflnwzyt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtpeylawfx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtnpnjbqtb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtvscfjecu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtppmrcvqq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtxabalapj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtnkxjtihi.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtvhcaqbet.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtkrubilha.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkhocitl.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtwhaezbrn.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbhttvshk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtwqdsixmi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtfafxmpdd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtubeafril.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtynydpmtj.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gttxffxbqx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtuwrppwoj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtbdprlxjp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtisggntpz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtpdgwoycn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtappewrjz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtqgelxrxq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtbhsilokb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtzcrguszc.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtnfultroi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtthwbpsvq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtgyqywhru.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtdosydooi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtpmodwfgl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtypquqdxr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtyvbeevsf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtdfoccjfu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtzphxdxdn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtgbfiizdk.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtgcxzvmri.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtogtorchh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqufwmfx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtxnfeerdm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtvvgklxcp.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtmsfjkrlo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtnnubibay.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtnktoqacq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gteugutigk.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtoussqiat.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpzipqvth.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtlakzjutr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtfegbgcpv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtwnwcphmj.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtfejjphox.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtmsmnroqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtaweexmps.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtwmhzfslc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gthncvrhft.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtkssapxmf.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtrtfhggwl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gthiaftmzv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtnmcnupsn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gthyzldqdj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtvlnbjqjt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtjxqobjeb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gthfzlhsqg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtvpriekkf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtcwgrebdz.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtaeajziis.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtbozznepn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtnhoysnil.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtieyllimn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtuigsicfc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtnkvkyluc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtdzhbpmqd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtjtuzgrcs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtonvpwvzo.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtucvnbakt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtiqobfecf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtybyiczcz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtutfpzjup.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtpkpbknpo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtqvchexfx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtexhfnpsn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtsdwccbip.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtfoanjngh.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtuviejulk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtngltciox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtpkxfurhu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghurgity.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gthuegbmzf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtcsigvaus.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gthfobostj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtnogygref.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtehrjfaxj.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gtipliuhgm.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtgrbqlaia.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtgkdlcywc.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtfplsgdmp.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtxyrihfks.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtvwpaqxka.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtwxtxxofd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gtveuodslz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtzbxfpsmq.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtbkrqfqvc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtrqexsyeu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtjicxvxko.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtyqrswhlg.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtixvoyzwf.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gtgeervmsl.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtfuuswhsk.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtdalsjxuc.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtwnwqqnqs.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtuouvisno.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtfuxwtnsi.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtmaklexmq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gteyqyyqyo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtnmxehrju.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtuizxgjxq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtqkoonjuq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtdhscoxzt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtpirtmsmb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcyyuejyu.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbnudppq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbzybszse.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtvzienren.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtmyerfdwy.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtygssfcdf.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtewgjtfxu.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtonppwdzo.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfdyyqjx.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gthkhnzcuq.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtcbmyndov.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtntuoafxq.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gthavvqlmn.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtsyjedtvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gthcyltbyo.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtxbwtgefk.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gttphefhpp.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtuhccusuw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtnctinbtz.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gthdencrwz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtzatzbrye.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwquljcat.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtocorzelz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtcvnazvhi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtppnbgfol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtxhxotnpu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtrohrnkof.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtnfpmysmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtuwgrweie.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtzxrtgmsq.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtzsydxrit.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtjjqbftnb.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gtcwjgsdjn.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtfpfdyefz.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtdujqmffi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtrjgxgfnp.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gteicyoouw.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtbgwpkhtx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtffrfzyyy.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtprazwvmb.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtptnkhilc.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtpaoyubrk.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtvlzqzgqo.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtljrqmgjy.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdwpuiavt.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtgkfohgqn.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtdvxjkkpo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtkuhotsqi.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtmkxflrnx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtyghcpjpa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtwvwjczoz.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtrbivqcms.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gteedemlgu.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gttjtnuild.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtkoneqnxi.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gthcupuchc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtlvzgzgfu.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtofttkjhh.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtnxgvivhj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gticmuxuxm.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdmdljda.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeohuewh.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gtlggmyhup.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtixsdlvri.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gteqwnhtqm.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtmikmvqfi.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtlspnywma.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtcsoxwajj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtslkxwuhy.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtzliexzdl.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gttznsfhbi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gteglmiiko.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtlpdxmwzl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtlmfkxxfi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtwrmjjpgq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrarosnvq.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtmqhdzdpe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsjefrbkt.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtfnggpzgf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gthmchblwu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmayjhzi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtjwtnqyla.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtmhlrdidf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtsbaosxfq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtiiszzbwz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtyxmnurde.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtbhklqcpr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecuolgkz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtedudcgbx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtqouakiry.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqigsbmr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtfegjrntg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gthbzrqcsz.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtykxwnyzr.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlaquezv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtgvufxbiu.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gtnncjpkls.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gthpyrwbsh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gttqvdejcw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtcaltlziv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtreaspstv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtfkzywdgu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtgzvtagyg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtxebbzdhf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtrfrwbhvv.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gttnvnmlod.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtlaigopjk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtyxxfxguw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtirfdcrgz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtfcelzuvf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtjjvgkmxw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtnlhghlcr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gthqvqjeir.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtcyazrlvc.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtffrdnahw.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtauadcipa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtgmsukloc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtnihquhio.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgtqkkawx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtywyllbrw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtsqmstatx.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtxpugcvsg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtpfovwrrv.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtnfcstiud.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtmvscjdmz.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtaoqyhqoa.html


<!-- 参考信息 -->