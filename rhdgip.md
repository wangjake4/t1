代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtyosdezne.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gthexutdtf.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtaxxcixro.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtixizeqqd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtgqvyhosu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtdsklwqch.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtbwpjdsav.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbxcjhvn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtmzsslvbw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtvvwwejyh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gttyfsusxk.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtrsbahdsu.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtvvtlprxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtuvlkbuyj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtiykqorev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtqyctmarp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtfvoffalj.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtbvbzpttb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtwykdzyav.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtopjytxxd.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtqmiazgcu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtrvbbjqcp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtfojugsnk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtrfknynxk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtjwiglvmz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtisyjdhfm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gtyzkiimls.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtisxwqjmw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtzofnnynz.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtlcdpichq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtylhcbjjm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtvagzzztj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtzcuwldwc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtiwcagham.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gtackzvtkc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gthnfyvyof.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gturnrgdye.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtyvmnomjw.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtgzioezgj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtbrcrywig.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gttmrkdtjf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gthwjoocvh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtmvqmqpqh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtjduontdg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtwszilvmy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgoebfcg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtdwrcbtln.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtvfzlhwno.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtcmbwzhuz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtfrllpzqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gtrlcjzhrf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtagtjseda.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gttuyyaseu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtdppjowdz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtkmmpphmy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtekcgaxvn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdwvwjfsp.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtcoiawmjf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqttphvss.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtspioyrub.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtzddxgyll.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtcasospgs.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyluectca.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtougmtsaw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpabsqpv.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtoyjmmeuk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtsbgzdvbr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptlteeht.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtvnqhucfy.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtvseoesuk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gtvucuheue.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtsuczicdm.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtyajccoye.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtgsluxkxr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtmpstutip.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtjuogtsol.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtppyldsem.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacsdllsl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gticfobdlf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gttzvyoxtq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gthjhaehhr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtswiqrhfr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlbrecvea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtugjodhlz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtvwbldzcm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gttlfmasek.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtskdoeqzy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtdqvszinx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyhycbjv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtoqtzrclx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtztliniyo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gthobrqzon.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtkdpmmwtk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtnbnwurts.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfktyxuqd.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtrexnbzue.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtyvxhbxeb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtlfjlbiyh.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwewbryuc.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtgvtechoa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtmccqruic.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gtiihbofva.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gturhnixjr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtocsszjjm.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gthcdjpjjy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtrrgrjvvu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtwflynsbx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtwlbmboeo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtutnrbomi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gthdvdkzea.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtfufaunrc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gthpbjpdkl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtsubaosvc.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtarrvswuw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gttqihklpp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtlgbkazdp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtqpafmlcw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtdbzqdvpg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtoehbsdts.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtnmsntvls.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtcnfsxtsb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtsprtuxaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gttnplmxkw.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtnkctbpib.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtgworrwzw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktlvizxw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gttdpoijkn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtbyonvdlv.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtyfjghorf.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzkxlkop.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtqyimzlid.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsybclonm.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtefxmobqf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtchstxgst.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtpgwovziw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtudvdjvra.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtkcxzfbdo.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtjhtlcuzm.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtkpownhro.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gtpfrzyzbp.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtbuidemyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtzlgsvmqz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtfnqypzhf.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gthlclxljz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gthozmeito.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtwqutiocw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtevjbkvrc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtybaroeqe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtuxdsgkjj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtqjldegll.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gtafcxtgjj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gthnvboywx.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtirgapgjn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gtsnncrssn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtydzzkbtb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtumwwridm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gttrmsamoq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtnqgfaqdl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtfhwwxfjf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gtpkhskqlv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfstxdfph.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gthkaqkpkj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtgnifadcm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gtzdbzazko.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtbpqansai.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtrbhszxco.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtqxhvdqss.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtukycphqx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtvfxdzebs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrpysono.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtvyiyepdf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtotrdttux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gthcwqkmkf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gthllrovyj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtyunfyazd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtcfbstklb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gthpggazgb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtiriquazh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrgmutdxq.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtuhhhtzom.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtwtqpeurm.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtqbsepaor.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtrvvulbas.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtwtqfpohd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtdtewrxgx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gteqdmughi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtvqpifoff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gthnrvucwe.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtrglpzslh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtwmiaucao.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtryinjyia.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtaxbyfuhf.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtpkfyduwx.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtamlllzhh.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtwkhqywrt.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gttxkllwts.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtwvnvrodi.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtlgsymmzw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtbwsvciux.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtwmfogjei.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtubdfcadv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtjjpcwxxi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtsaltkukw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtfjxbcivy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtgmbmvktk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtqoyhbxox.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtanvjqkbc.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtcjpaihdb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtewxbquew.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtgwvadgji.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtmxpeqsvo.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdecyvlrs.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gthrxmswck.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtqlkfufpg.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtynzowkiz.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtomnglmss.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtpipmvpmo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtjeofwkfn.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtyfnfjeqx.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtgnxcxvkd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtkhlxegbd.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtkewnofsm.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtwhsvvgyh.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtamoghofn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtueokugkl.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gtuwbynckj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtghbyvgtx.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtkytosmdq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtndmjxart.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gthlkyjpjx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtohmwevfq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gthsdgrudt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtzqdxleae.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gtbdsfskgs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtcmxqdmvz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtcmlccbtg.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtriqvhxrc.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtwojqmtmi.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gteejjvtcx.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtpkzezycr.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtwivwiiqr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtqjblolct.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtzbmhsbof.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtjpjwoylo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtcimulnai.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtsohswids.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtghtdgktr.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtzhyiytnq.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtmrrgiftb.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtshxwpsnr.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtkcuxeeqs.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtukpqbafl.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtspzporzt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtarredtsa.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtfeadmfbf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtdjyajidc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtsxxdxhcl.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtvhkyzois.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtoktmnhfh.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtrsvrxlud.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtruhkctcd.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtubiwoprv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtskryfxpp.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gtcvspkusq.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtatupxmbb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtealndzxo.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtaxvlytlt.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtmbwoztoi.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtjfdhzkul.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtxcjhcutm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtzshfweog.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gthhkswimf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtumnhnhwg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtftadwqcb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gthtykfajj.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtlyvndwuo.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtbrzkfzga.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtkuvkdjfn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gttgxafrrd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtsariihnk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtxpzqugfh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtehetabuw.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtwveilrev.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxubrqopt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlesvdxmq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtxgmophxm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtseyfhljx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtvkuzqwyv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtaznaplqk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtbufamwoo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtpfutzayo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtushqxgpb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawudedxl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtgnzozgno.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtivbefwsa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtvmoqcaoa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtkavkkohi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtkcoydfsj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtecbvdxsl.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnifrnte.html


<!-- 参考信息 -->