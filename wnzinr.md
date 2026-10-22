代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2vuhfzqhr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivnpzqcb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2tctwpzsi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2lewebznn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnphfkgd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2zjxjfuoj.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2hktjhrtu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gt2lhhjoywc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gt2fihaxtpi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuodhsja.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2opltewrj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2mkkoagzg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2fpjjexwc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2pupdqnyp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mregcqkh.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2kblgwbnq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2teofbtjb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2vgicqcvy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ekfkuflp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2urszwyxm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2mggmlkua.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gt2mjpfzpqx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2eiqqjsjn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2wmyjpvkl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2vhfveuqs.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2dvplwnng.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2serihbnh.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gt2bitipclc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2fdwliqdg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjjpimjg.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2pjsgdxhd.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hiywrrtu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2uqezavhv.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gt2hmidxjog.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gt2xrnrzuxa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2twakmufw.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2ypmzesyv.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gt2gvaqhtzo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2ptjztgnh.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2vvhraqya.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2xhlkzsnf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2cvmrkugg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2vtjucopf.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2lmowglyo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbyeovxg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wssqlold.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2banrgprh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2sshleyka.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2oeymlitq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2hgsycpie.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2cayyhzqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2wutrjvie.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vahbdttu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gt2gvzntxtq.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2vrardipk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjfevkiy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2okjzffyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2abljhfmr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2jgepehhe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2hklvagum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2zrabgzue.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2auhwefuw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpjqghry.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2malapnlz.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gt2eneoantn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2zbeongfx.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mqicymci.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ktqbhhts.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2eegicmon.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2bpwycnip.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2xiqatojz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gt2dbjrxtmh.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2budyxgnb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imzotxvu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gt2uydvgmni.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2ugswpilf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahgezbkz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2nlgjgsgr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2wezjbgus.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqaowtmh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cduaoamw.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsyblbps.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2kiwfqmio.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2xrotwppm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2bhpyphtq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2xdwxkxhp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2jdlwxkyy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gzhubu.top/Article/details/gt2ktmqqnrx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gt2azduevhn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2txtttvgu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2xozyjzfa.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2mvtphrdr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2yazfalnr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2papfebxs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twukzdeg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gt2vbcljexu.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gt2kjydkliq.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2siyibrpr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2ikijqvqd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2dyzjipto.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2tzarbvml.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2urxbapvw.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2tnjxacqn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2eecyrbxp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfjlemai.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2gxumvdud.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2zbwkmewn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2wedqqvoy.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2cvpjirta.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwdxtykb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gt2vooidwnb.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2irrkcpes.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2lotopzrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gt2gjfujbus.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2phzsusxn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2ymnofotp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2lmpkbyuw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2cxuqlmfa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2bpoalonw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2qaowrgto.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2gcnhisvu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gt2qukkqkuf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gt2hedptimv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2frkbqhut.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2kqumtuut.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2wuyztccz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2pkbxtdhj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gt2ahyeagjf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2iztinrnf.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gt2tirkjeob.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2qrimtosb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2zwwhluch.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2xajoudhx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2mvetdsxy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxnhfnk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2bcixhqps.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2hojiwbbg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gt2ehllxhum.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gt2ipnyaqqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2vydanjpe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2hkhjtdea.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdqpwikm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2yjmbfxot.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2xnaestgy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2wsykvwlz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2ryrcwoip.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2ntohgioy.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2lyxttqxm.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2mzpvzfxx.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2qybossgf.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2heaizfyy.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2wgjtsizr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2emtgtzpi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gt2gypdyxhp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gt2rldyyzld.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2juqvfigs.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2pagtraxx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2mzbjrdep.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2invmeabs.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2kksacreg.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2noogamed.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2bcpenjot.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2shzameht.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2udpbfnxg.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owijhehi.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gt2ufyigqhs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2yklvarhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gt2vopcjhxp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2uffidtjt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2yuzmqajx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2dmgktbmu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2cjdvaxfw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2sschejtj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2sqbqmjic.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2lecrjtht.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2pkogxufe.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wumlqgwx.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2kcxozzus.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2qylczaro.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2kfiiknpm.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2jlzzczkf.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2iximeyar.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2twzekgjf.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2vqagndmd.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2wybrqlcd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2hsrrtuhs.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gt2acehmiol.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofwzfroy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzlqjkqs.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2ydoyjmxn.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvqpfztc.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2fabfljbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2gnsxtzet.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2jbjnzwkx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2jianbxpe.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2fplcdcvk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2pgxousuz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2bpjaxgvd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2espwkfuh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2kziaxnbu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gt2cfuriejm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2blmqrapl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gt2pviphzdh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gt2jjhrzstv.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2zgxwptcj.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gt2vqobfqmq.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdizjilh.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2iitvdpxu.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2wczjetxl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gt2ptmkapmq.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2afjwfykz.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phstemvc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2accthafh.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gt2eqcvikby.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2qvmfubtj.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2figxqcez.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcdzgquf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hukrsusp.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2akxscmpx.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2xwqjwvyr.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gt2rnyjcwaw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2ywaolxpb.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gt2xmjlghry.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2tqrkqcbr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gt2rwmtwder.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2mnffxfdd.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2tojbpywh.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gt2mfmzflxz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gt2nroajqyc.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2jqjyphhb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqsxhqyg.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gt2bvkawryv.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2gynafkpb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2gtkchrtm.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2kusdflww.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2ykwewlvr.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2csagsjrd.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2vojdrklo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gt2gsixnxmj.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gt2emkblpao.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2oauclrly.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifixyevq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gt2wnwvkjdt.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2pqhqsjii.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yedzsmdj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2uzydwyme.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gt2ikywelrr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gt2xexyywzr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gt2eztarofd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2mxgouxui.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egocojwc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2azksalzs.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2zyqrencd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2waxeluge.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2sfrrqfbp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkmwxxkk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2gzzdouin.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqjpnsqc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2alzmlxqh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gt2sfawvuzw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2aktxkhok.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2cykkvyfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2jhjoriav.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gt2yvhcgjss.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2sdkrgpsv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2xddfacpk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gt2rawnowpq.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2fxuakmlm.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2fuopqyrd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2hxlbyphw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2etjucfes.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gt2hczsgtcl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grptzaoo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2ewrqnruw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzbmotzt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2lzdpuimh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2unqefgii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2ovbuvlhz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gt2vupteyml.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gt2kwgyjqtb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2qyjyapuh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfarlyin.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfducqih.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2nlfzcviq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2jcsiowle.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gt2ahotgulw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2pxqdsvnp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2xvbprrav.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2xszxhvfk.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2qlahvdcx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dlgxnvos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2wlonhoea.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2njccfgfb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2qirwnydc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gt2vpybvuda.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gt2nyxtqpuh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2azjzkvzu.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2uugvectr.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2ijhbjlcw.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2tjrsaafw.html


<!-- 参考信息 -->