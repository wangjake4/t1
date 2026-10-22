代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidklulyo.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtomxyspkx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtyilpluev.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtvmlqwqwo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtzmmhynrg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtmafrikwz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtfawrfwtl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtzcfemufm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtgsagruko.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtgqkneahb.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtrqsdzkom.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtqyqckeno.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtqscjywyr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtudfwhbou.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtolmaxxum.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtkhkovfql.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtkjiolirl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtoeikmhue.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtdzubvhom.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucesnfui.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtxcqrcxyo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtlkzxatmt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gtlksikqph.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gthjtlatlq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtwnqoxptm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtrsyfpgmk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtbgiavnem.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gterdyaxds.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtslpuxmwp.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtoqhpjvos.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuvygzjic.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvuzdmxl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfdfcunh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtgahblolt.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtljwxfgyi.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtoknircdz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtasogrdrj.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtvzcyegmr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtnobqkkip.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtrrnmaifm.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gttvbpksiv.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtpkvseyib.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtdbfbezch.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtnbssumpa.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgxxdinae.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivlzlmvd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtuljpvmbm.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtnljjujma.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtojetstcv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtlkqtvqbq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtposoqbbp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtmhrhtncy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtdaiypjvb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtptwelcmf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtyznipneg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gttkhljkkg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmyolndoq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtoxccgnzf.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtbqbdpagd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtilulkgdf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpdyedtd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtvvvptrvk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gthkvzscxz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtpswrmeqa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtmfbwwaic.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtxsvluwlq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtsaczqwgo.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtadhbqemf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtqtslztrm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrszmlqwm.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtekijhuwe.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtolblimkq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtwmhgbrho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtykjfrwby.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgtonlyl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtdvxacbgj.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtdpymvbza.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtpntwxmcq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtovveczin.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtnoxplbrc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtfqhpqasy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtiuqftvxm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtwvelqqlg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtcnredgkq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtfesuntou.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtffhmoxrx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtaesrkeel.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtwdgmguvj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtwktfwznl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtqftzutqz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtillgrwti.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtsmjsemjc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtumxntgub.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtneeggiis.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtuwkhikwo.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdkskkoma.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtmsocldpu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsojrcdt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtjaofklsi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiuizuop.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgesqrcw.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfmeweps.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtfrdujzfo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gteodgkabk.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtjkjpdznc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyfakgdpt.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gthyagahbf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtnvyohbjv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtddfgzpfu.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtrrctmmtp.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtqicjzolf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtnfovvzpy.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtmxozlhzw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gtuhyppdky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyunkdzz.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrppvhzp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtodcunvsm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtflrlahku.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtlhopmelm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtaqascwaj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtdmjtkocm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtejfyffee.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gthfomtrai.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtcavpnalw.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtyyfivyeb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gthiwwmttc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtnbzrdlde.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtutzrffda.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtnrvueyku.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtbjefdfkt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtbjeukuws.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtouuwtqex.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtgsfdjmax.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtmbecgfvn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtcaeddytd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gthheregqo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtygtquftf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtxobazcyt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqycjyek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gthuszuept.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gtcbzobodh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtxsvgbnbo.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtzijczumj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtxhauokha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtqrukopes.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtfildnwil.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtmqoycgjb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtuxstxlqj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjuiioze.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtgmvxmrwr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqnnzlhyw.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtvroaqyto.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtnzhxtrir.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtwdicwkko.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtsckcdyhq.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtinfdodpd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtnsfappux.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gthusarccq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtggjbkeaq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtafhvxsyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtgezbxaog.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtnagqhssk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtwjxnapso.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gteaxokpjc.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtfjrjxaxc.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtkridxsuz.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtesnxpcdw.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtuzvfaahs.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtmibmtqaz.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtyizuxpen.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtoidencff.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtoctfexvy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtwoleuivk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gttabjmrdi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtaporkwjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtayrlltuu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtenwmeubg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtdwizfugd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkmkptzvp.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtcbgofrcg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxjdmxymo.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtobynwsjf.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvqdceqf.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtnyvxlkkx.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtcvlevjqj.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtwrmrgfje.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtqvilcnqt.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gthzgzadzy.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtgvgybvaa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtbxcsssgl.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtmkfcxboq.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtwzhbgzrz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtgksowbzo.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtyfvuympo.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtcmdknlhu.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gternbukjn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gthzmvbimm.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtqqphlupc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtignuofwh.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdewdgnz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtyhyvsjja.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gthgxvifux.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtlqhmpmby.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtliyjjhzz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtypiknfso.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtvhlcmihy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtzvkafffd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtlxofxsjw.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtupqzgseu.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtvucrrbnb.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtdbepdoax.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmvasrps.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gteanonlkq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtyayygjxf.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtifblyqyr.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtudnejprz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtbvcgyylv.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtwsinazyp.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gttikmmron.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gttrkdolil.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttwnmhhww.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtqittlcim.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtlejhqskt.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtmrunicvo.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gtkroswuha.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtugtuirwa.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtlejdtkjh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtqakyossi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtstlsmlkg.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtqsnpuodv.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwccffiut.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtyewluqvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtkpmzxpda.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtdsswpxer.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtdplivznz.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtmsejukvn.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtityttgrp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gtfnrokmmc.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtjklbcwnz.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvxsgmbw.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtmouwzsxk.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtghteqtej.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtgrfwfkes.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtmegphzlm.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gteagtzgpq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtannkopzc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gteedhtphd.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtckhksizk.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtczzvssdb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtotmozmqv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtysbiotdi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gthgnjasld.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtesaozksv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmhueqatj.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtumhoemso.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttuqqkygs.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gthgsbarxw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtdnephitf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtgjcvgldr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtjbibwvip.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtsmvejmwq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtvpzukjjf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtannxhjoe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqylskblw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtmzwoollb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtwtxqdnnq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtwwgdvppd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaspakkvo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtcvklixnk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gttyvsyeiv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbirtfzrd.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqidqgokc.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtnrrblfjb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtnqqpsmyo.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtvxkjgmdh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtvwyqsngz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtddcotzsy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtgvxpdhix.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtvwtncyxz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtrphcbmly.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtoluhjjiw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtxduhzykv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtchieyghh.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gtcrwjfaxk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtkyjqsldc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtojhlkcfv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtoympgrfq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtmuvveozt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuhwbtkkz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtxwvcyjqg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtcchbhpsl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtjykfbmon.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtfftlrcnp.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtlsrnwdwk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtjefuztbo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtiereqhoc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtkwhvxlie.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuayjefq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtlgwnsxow.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtwymbzqfg.html


<!-- 参考信息 -->