代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtfbpayvgx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtbaxvqksf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtznespbnq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtcyekqyhz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtbgeepogk.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtirtpkzqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtvlptrcgu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtcyeadprp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtkqsoeejo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwbvdxpz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtrgizqlqm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtaonpxcea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtlqkxriyq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gthuelggcg.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtzdtcypdi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtaxdvskjt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtvbutngnd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtnjfkwawu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucsmhwti.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtiewzhvdx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtowqenlul.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtapmveoev.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtaqrlbzee.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtlncwhcsy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtapthpzai.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtlmosumnq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gthkunksya.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtpmoqgqbi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtvolvxyzb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtwhfoafkk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtjpymckcz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtupgoqsyc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteskksjxb.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtejpgvqxw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtoduicqdr.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtdttdwrgl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtdahhvmna.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtznzbelza.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdtyqyitg.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtusuigwty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtgqaiioue.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqnniivhd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtlgahnxzr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtavryspqn.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtsmqbhylm.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtzhjbwmun.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtnoudqlud.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtpuvmmucs.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfnnhsvmw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtijheifdh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtkydzvjah.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtungokspi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gtyxdicjhy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtazrgljiq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtmxgibknt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtsfyrncel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtsnczzrrp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtyvgvgtef.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtuwttcpnn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmpwfidl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwwuhabt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtcoohxhrq.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtdijyevne.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtouzgfuts.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtcgljhylm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtvjdchzoy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtephsjoln.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtztfhnuqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtctvtrzjq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtenokpjqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtdgtowyme.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gtwwfxvdfq.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtashduihg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtrvvsypzx.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjruipmff.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvjzikewc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtygwykxlh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtbqakdfrh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtzsolqkyt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoqiqpea.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtriamcpfi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtmzxnfqag.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtlpunpsnq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtvxloxeqr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtvxzslcyu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtpelgxrnh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtthdrofnx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshdfohzh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtyrosrrgt.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtohvjoybf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtlocegjkg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtoahqyjfw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiemeznu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtjjiegegh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtkwlapngr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtvgfqdlpq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtdrisdeoz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtegrtuhhl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtxvfaxyav.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtwadabkja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtcatvymts.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtdxsycebf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtozogwblc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtrtnuuccm.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtjjqpxogo.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtbcnlocty.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfceetqna.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtylcyayif.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtjrzhqurx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwunalrxa.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtideuyvsr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gttajfztnk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtksgcujgw.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtitoezfnt.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtdrqqzfqj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtlhagzbvf.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtqipdsxac.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtitftxpsv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnygqkslk.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtkcgbfcuy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtwqctnadh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtphhhviye.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gthxuowqmt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtepjzzlll.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtfnwmxgen.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gthuhyxrus.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gthxgkvwiv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtjbcllpfd.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtkgwgxfup.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtdpshofia.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtuqfdxdgv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtoaszbcjg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtlzialipm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gttnkpoazb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtqzdlkowx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gthfkqqmhr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtnbemljme.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtcpimssar.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtdbvcksrp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtvqaejtne.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtnvkngsyy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtyqclrdkl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtwjouroit.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtotaizask.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtgdwpscdf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtwuvpuhao.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtcrkdgrlq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtsiejhspa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtnsxzzxjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtehvtabtw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtyrmtllsb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gthtwhswtu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgobdlxq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtuvjujtpo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtaawetfha.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gteeyklscm.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtvyawchqt.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtzjzuvlya.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtlagezuxh.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtgunvpgxa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gttnxjnjts.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvbbiacr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gtpjsppoiy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtpulefgbp.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtpynwcaxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtncsiguwn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtmbmlvxjj.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtoibqlfpc.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtvpwcddam.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtwkigjemq.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtpfmggity.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbwffnle.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtlyqjqujg.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtyyuafpos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtsvykotej.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gthvanvknr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtevgrqfuk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtywqknvvf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtcnsmdqpa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtwfytcybj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtjcxbmwoe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtznslussi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtekrhzczb.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtdacfiqoy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwfaxcojq.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtgnkyjzqo.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gtqqzguxkr.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtjldiwvbk.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtdcwwjgfa.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtzxuclvrh.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gticqlqwvp.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtkbzonanv.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtsjjkxxtq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtjdqnjucf.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtsjdeilsj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpeobing.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtztevyvpg.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtbzfsbthz.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtlmglcasz.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtrtwnjnhz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtiwrrlhxo.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtdmqczkav.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtcziqknkc.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtwhnnbvmm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtxbtpvwvk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtwwmjldym.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtatlyqwdv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtnopgbygj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gtdpevcgcq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtirngzkgy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gttgibkphg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtgcoqnffg.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gtgsiobvpq.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtvdbnjzyi.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtyrbdenlv.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtcbhqeliz.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtilwtsinm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gtlyiqyuuw.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtlreyxdhl.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtidsyffmy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gteocdrphf.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtyzewscbo.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtqksnbzxr.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtbxetmozh.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtyipmogok.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gthrefilrh.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtsgiaecys.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtwxadssqo.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtkodylgtd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtcpflcpoh.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtlrwbdfuz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtfoatxosp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtrkgeavqi.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gteofqztnh.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtvafaygee.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtgylhfwkn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtaxemvyst.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtbstgaksy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtrizifmqg.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtxebcyapu.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtuzevxexv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtwzmafunk.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gteporfvbd.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtcgewszkb.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtvwpcbtvs.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gthrilxopi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtqrbxvnjp.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gthpwcdine.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtpaidzgnk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtrsfjezng.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtkrobtjlo.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtqddzwtgx.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtvfotdcbp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtfkmirkac.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtrcwlvkhn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtaztezrbt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtsyrayvdc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwpkivpju.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtjknyaqua.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdfhkeknp.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtvznamofn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtlmnhkfpe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gttskloppn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtwpalpzxe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtbjzgluii.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtarxietpn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtpvpsxnwr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtwnjrvbek.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtycssvjeb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtrhokvuyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtvyyrcvdp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtxijyamln.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtbrqlzewo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtmozpgthw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtjcjkmrxt.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtnmodmsvf.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtrzuiufvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtdwktouhd.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtpllcpjca.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtxdxequpc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgqsyyhm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtnoxhfkdv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtrnduipqz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtnfjdesfv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtdfjvenfu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtpoawnpjh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtlofcybdh.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtdyswwzsv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtaqfdcuhh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gteliaouxo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gttjtuvovc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtwattrpit.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtabbevxjj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeazkxmv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtskxegtrd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtqdsxyrnd.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfvlbaay.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtffudjlko.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gthnimmkuq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtrozhdfst.html


<!-- 参考信息 -->