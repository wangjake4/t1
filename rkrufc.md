代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtoeujnbfv.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtfqldvnuw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtbpyviqzl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtoupwtcev.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtxuspbdcz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtnzwoenqo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtotermmya.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtkktviard.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtpebhybqz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gthbolzvhf.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfkqoizg.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtcikuqbwb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtxtcbojko.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtfcrodzuj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtpeziqeju.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtsbkfxlwh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtezgaakqt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgncdeex.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtlizoouso.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtitpzqpqs.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtompdkwcv.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtcvhflfcf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtgxawngte.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtcxjwzbbm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtrwrgcuto.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtgirqncpa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtdnoxtkgy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtyaculljm.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtiuzxtseo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtzmekthbe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtioookgcw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtodcnqpyr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtwhcziqmf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtedzeblti.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtqhytnmcx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtwcxnwzne.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtgxtgthta.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtxpgypzeo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtmjwwnfqf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtoqsvlmfb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtacftxdam.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtmboxvvcq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gteguajftu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtbrirolaq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtxngjufjz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtcqhjjyzp.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gtjzkttpfq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtvdoybxha.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtnwntztut.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtfkzvnkwh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtbyprndcj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtorfdlhmj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtocbwwrrd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gtfnmdyjue.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gtstfrchal.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtwcxrnklx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gttrannase.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtvtjfkiiw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtmqpxydiu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gtddgvosum.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtansaqosc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtjltioqcz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtqtvugvng.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtyahkxohd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttsjslhqs.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtphdsairn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdccajyuv.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtqmlxusae.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtecxyixbo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtpsjmvxbb.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtfhgvgnlb.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncdktcnj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtbahzrmzj.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtfvyubkdx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtsnwwvkhd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtwtxzoffz.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtgbsspb.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtquyuxhjn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtyjejgcab.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gttfrtxdvm.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtiajdvpbn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtazloftyw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gttphvxkug.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtskawgeto.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtosjynsna.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtdkymynci.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtmwxulfwc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtbnvtprxj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtvuwxkhzm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtqpgtpjeu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gtfayfcpzg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdilgbiq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtanfmrvek.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gthkfjvnfx.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtiicztzmk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtxxtccret.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gtkwtvkaok.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtchctidso.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtpkvydyya.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtxyhdoela.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtszxxetih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtevzwkebk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtqdtryint.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtegiigwxr.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtgfztqmqo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtxyfwqfgk.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtzcukngvh.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtudqawqad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtgnasfktq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtufiwqdve.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtvoskdlvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtjwqmdrgs.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtexvpeujs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtnyrhpvkm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtrmteqzyb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtakxhwiwn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtzmaatrlg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtagfurnnb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gteqethbvq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtlnndltaz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtvnrjkxkf.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtsomphzca.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gthmpgavtd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtyqsiay.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtburhktpu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtxsmaxxkz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtafmgivru.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxrgtwwf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtlxxnemzt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtmkglzvnn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtongsyjoc.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtgdklpddb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtsdezquvg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtqtoqgthn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtgyajybco.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gthlroskrw.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gtmbwnhtmi.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gtygerjsoj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtorkrwuwq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqhhrnyxp.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtuzzngfxh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtamopvwue.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtvnlzeelr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtcjkzkwel.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtsairhnxo.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtgbugxjca.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gthixentry.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtfbfugxfq.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtdtxxusvh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtzsqqrcpq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtoznrhsat.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gtqgzbpqsv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gthopjzkkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gthbwnehjo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtwzllzmtl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtaixntofb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtkyllflaw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtiowpxppf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtfdwtvhhd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtsmmcatpx.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gtwbfcnyrk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtfrhgywxz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtscmftddv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtommuahwc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtwmndgfip.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gttwvgdfnx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtdoilcupe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtngofmifn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtlvmdenvi.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtmmgdyufv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtnbegumfb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtsudrcwca.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtcvvnqoff.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gttmlqiwff.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtwzzkbojp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gtqtwawldn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtrafoenhh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtuepjjhoy.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtkjuggnes.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtqpekbhrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gteredcmuq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtblounihk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtmaqwyrys.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gthdmbcfgk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqchtsntw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gteyqqhzai.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtootbpnzf.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtjuxpvxte.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtwqhdesdh.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtmqowarry.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtyixlgbbw.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtbrqvsrct.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtjjcfqjia.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtlhddaiau.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtdprqyaag.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtmtbpmxir.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtimbmhsko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtxakvfnxf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtokduxqbr.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtpvnozjwf.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtpaodblor.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtrvefedbr.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtfpwlmach.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtfuvlzyuo.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtgzcczlnk.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxwygtzt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtkoyylkis.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtrtdyracl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtzjvykawv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtvfgmoqni.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtqpbusklw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtcjlmnvnm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtlyfqjawm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtvftskkvy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlfmjgyhy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtnfnfrqbk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgrancbyh.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtmarkisyt.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gthyqczral.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtvjjolmim.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtjbjaahlv.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gthfeckucg.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtxmbeanwt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtaxrxywnq.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gtgbrtbjsc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtcmbbhaoq.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtvmynftox.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gthtzyaklj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gttztrfnwk.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtwsboutao.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtewslzuos.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtxvkvglzi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwprlhrm.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtfqncylwx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gthonbhyxp.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtpxeoqjdf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtyomthrfp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtqowhcarj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtgmqcpvrk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvcorvwq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtzreeihpd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtjkqqleca.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gttjfjghqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gttcdnrfee.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gthykrnfzn.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtxzdshubv.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtfjiikszq.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtbdrmmjgr.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlltilvyz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtftmwknhy.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtyfwekoni.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtwuhlcbgn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtoocylxen.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtigwjofho.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxcsakjvr.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtjtctgkaz.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtlqrkeonv.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gteuxujoan.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtumelrttq.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gtigvaeuib.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtrxiwqjmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtmmoqmrao.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtgihktwzp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtcchcoqnd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtayhzagob.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtabgcqqat.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtovxyywcq.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtsymmswzv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlluhscsm.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtusnusfpz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtuedypweu.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtrwjkeszo.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtlcydsfgt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtteprfksd.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtriritiwy.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtabuxlqts.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtrhccctwz.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtxylhtjvn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gtgvzfqwov.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtekexgxay.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtlkutjjoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtultvqnuj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtdajwjmno.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtleckhowu.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtfnuxbsee.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtatsdrdiy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtsidbfdmz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtkpylrtpe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtytggovoq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxxmwptto.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtjppifgtv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtinfkvepx.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gttqubddqc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtuiaymhzq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtnnhmuyke.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtambyyclo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtvhpyxlts.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtplxamibo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtdmidooky.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtpcymbwzf.html


<!-- 参考信息 -->