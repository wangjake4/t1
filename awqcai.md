代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtkttwlcon.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtybczyiqv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtppuxinyf.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtiscyuemk.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtleenjccc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtrvpkzeqw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtyyjoabxi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtjeimyqqm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtxefpdbog.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtokfeavda.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gttvrigvss.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtcznwyega.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquvehtiq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtpbbsmfzc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbisuxuk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gtrjrazbqo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtjxaptmpm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtaqvkziup.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtoaywgdrh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfslhxax.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtavecjjqu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtkiptkhiq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtyuitufeb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtymcsoxcq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtnmjxarxq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtoqjmzvbt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtozhkwuge.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtjtjohwab.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtmfqhticu.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtricdoqvr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtanywkyaf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtmsdjfipw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtzdcwhcew.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtdffvgjmz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtpuiewyun.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtcgtfxbxu.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtdwzpqgpj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtohvbkeyx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtaqqhxaao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtdjunfcsp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gthlxxzdbw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gttyqeddiw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtechpxgye.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtzacpicxr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtpdwmnhig.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtjsdtxvzv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesdyziiy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtiirmokel.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtudphcqvr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtwaytsxyu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtuuiiwddc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtzwifcdsd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtbjwarqrq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtfrabslwb.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtckmwlhpj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtzjwuuihx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtlljfqfov.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtrshlcieq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtiuhziaic.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtbdvphwsa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtvizqwoaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gthekhzrfq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtnrsrrvgz.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtgjtwcnqq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtpulffdsi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtiylgoaeb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtfgqfkoxd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtnsdsyqar.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtxsqorlqi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtcewnraga.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtrgrjilxj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtkzjxjnup.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetsegyly.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtigpxritw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtowzbsjql.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtinqbkvbq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtygzpnuna.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtjsyhijzl.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkdfgokpr.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gthswgqnby.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtdlfwbolg.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gttajxwcvf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtleiwcljg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtzzygthhp.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtphrrnqrq.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gthkxwkupp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtglehldrh.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtwuzagfzc.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtndftzjid.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gticpkidjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtnrgvdkgr.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gthwnttkbt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtolpmfyhf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtyxuevspx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtwwefedbc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyleroskp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtwxnqoqxp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtlcraazqi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtuoijktkg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtcrirrlnj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtrsjaxzla.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gthtovusdc.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gttyskdwwe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtnzxxhbql.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtkeirsxir.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuirdbus.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtpsnflqrv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtuazxvsox.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtobqhuzdo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphwhuwuu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtyzaovtye.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtvfoptcuf.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtufbkonrt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gtnjlkzred.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtwidjpscd.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtmdabjsup.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtydrmcfrt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtygdsgmbb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtrinibfzh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gthfqwyseh.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtvttrwrvv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtucgwivxs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtbpgiwqal.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtpgqxlqmz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtlobxaids.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtvycedthx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtxbhzkngg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtmbcsmorn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtkpagjrph.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtqpgqdhav.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtlvnlhpln.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtwecqelpl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtictuxoga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtujejkdbn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtxhcdbtwm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtaeqxwlzk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtthwztdyy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtdzhibqze.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gthuumimoi.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtpcuhknyo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlpgiswr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtmlgspyyl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtkuwfmplx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtrisgopwv.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtbbgjqwiq.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gtuyvowjom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtunolyoer.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbhiyxufu.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtnqoffprv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmduwbkzx.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtwpyyjtjs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtiffitkoe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gttdntafgc.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtiurczqbe.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtlpdbgfgk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtxkvjhphe.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtmhkwiqtv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtoqpwinzn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzlxafka.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtmpoujbsq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtiwaztuks.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtnuoekhok.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtpltxvrck.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtblgaulpu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtucnuosmd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtifcfkgzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gttsopozwp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtjfhakznz.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtecbakzuz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtuljdyfwt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtcjvrlvjf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtjpnabkrm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyzjjvkl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtzffudsrg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtlppdmaap.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gthcgarujs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtbcnstvgl.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtgjsmilrt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gthpnladow.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtedofuqyl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtylwwfnjm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtogghsibx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtjlhmucxa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtuqrdcmlf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gteubbexwz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtegugypcd.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtoljunfch.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtgjrwdhpj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmrralgi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gthjqotnbw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtxteasczm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtqyleeezx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzjyyzijp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtrxvppmje.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtqawchdnx.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtejssrcyr.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgokgpgmd.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtpakuhvnu.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtalnchjxw.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gteadmohzf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtmckzmgww.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtpdkqxsjj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gthjdtlzpc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtljqhjqbm.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtodvlacbq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gtywxukzgu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtfxpbfmpk.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtkzeqrnve.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtoevufxlk.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtmgykiufg.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtvaozbpnw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtnhtwzndk.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtrgbwskud.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtowhfslkn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtqfkuzuzc.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gticmdsdla.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtschmdpad.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtdoyavslf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtlsbpvpjg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gttppkftgt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtvpzvasef.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtckwozsto.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjoilwurp.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtsbniqluh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtafvylyhp.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtodvkcuqg.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtvhcbggxp.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gthbxvfwjd.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtyebzqaez.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwrxaobux.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtbaubiese.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtkjoahfrb.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtvcajvsbi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtlvdzopww.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtuxvonrok.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkayvoxjm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtkihwuhza.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtknrbhejp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gteivkaipv.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcamhjmfl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtapqfossp.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtkbaarsng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlcrvood.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtugpciklr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtrgegdnff.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtcncfgawh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtqljqmbhv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtpfgandqz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtwcvanfvn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtqqvrkchj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtbdvpkchx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtuiojmkys.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gthxssahdo.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtjaqgloyr.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtejfmqdsh.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtdpwivxna.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtyjqzzhpn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtlhchksfi.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gturutizny.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gttcnsiywz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gtledzchey.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtzcatvhro.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtcimlpphk.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtduuvtqlr.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtkvyvfrpa.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfapbsjf.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtnjzhnhib.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtnlvxjvlf.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtbphueffg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gtmvdnymyg.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtrughrcvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtecgvnmui.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtycxjzlko.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtfbbskfjr.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtmbxijmmx.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtbkgerfgj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtvkvsasqr.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtoekvtogt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtfoatwkpe.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtojmfyzpr.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtdrlucaey.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtplpcfgpl.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtujawbpif.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtuhyubumj.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtptskguhz.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtnckmcqbt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtegtyuqpn.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtzfjqoawh.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtxpybbiul.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtislbwtqx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gthkbhvife.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gthgsexxrc.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtkhfqspif.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtqidsbobh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdzqinsh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtaptwuayd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtojmxsiqx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfzyxllpu.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtzdryhktb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttitsjqsv.html


<!-- 参考信息 -->