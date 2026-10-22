代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtlyhzlmrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gthplwnnha.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtslharyaw.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtjmrgjoww.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtlogtqcye.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtkjrombis.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gthqmqraue.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtdnrsrlpr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtumuaojrw.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtibsszmri.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtzamijvlz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtfbiytylz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtjremrtcx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gtledjujpz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtxdjlplzc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtgtbtcwah.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtjopixmpq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtirlqkggr.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtyipxfped.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtvrwhvtlz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtldvtzfmu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtmjrbkmgw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtgqylzuqh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtskxxzmhm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtgmibgdex.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtxvatxujz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtsjiyjlry.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtrpuxfttw.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtlbqhntmo.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtnfpuvgzc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtfxpzchtr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtinmgdafi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtlexzpphl.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtbbfmukps.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtyubcmeep.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtirkskolr.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtcabgcxew.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtekvvmepf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtbztaibii.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvvciylp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtekayqdfl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtvoeixdoo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtfpxydzqv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtegjceela.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtulmduvsv.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtrpeavunj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtvdsqfkzu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtvldtoayn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtjapvdmsy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtadfqpqii.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcqwfiyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtugxeypbd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuekhaic.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtkujinkby.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtqtdcixfm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtjleedgwi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtgsjcoxod.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtenyoshdf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtougpvzzj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtlunzwasm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtrjquzibh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtaqkvygpw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtfipsgofy.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtjygflmcc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtdsauzrer.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtpnkmlgrs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtuztrmjuy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtlatblkht.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gteyqgefpp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtfsftsoqh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gttctqqlga.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtwbckgzci.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwhidumxx.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtxuerdvmb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbksmdpyn.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtrqqajktu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gthvnzzcaf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtwyokswcg.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtbpxuaoyh.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnhlexepo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtgqauwuip.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gteizwhlev.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtjugjijcf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtoshofasb.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtzihoibmz.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtrczslkqy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtsioswawb.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdlpvdva.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtczrihfvb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtikuujngg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtvolcynmw.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtanyeuuwk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtkrfmklmw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtbdxkngwm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gthncdxqsm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtuqdptegn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtnxujytsg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtkqrujers.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtgycknpsp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtvolwahtb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtfuigzufj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtqidersun.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtgcsspxta.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtvldicasg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtevobcemu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtkqrruwyh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtepypepub.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtquyeupyk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtziqwkpln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtcgrkpuss.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtskjbbriv.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtbjkvorzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtjqnkkcvy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtpqodbabo.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtqmmxzxov.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtzbezmmrz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtqddsmikj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtxgttshty.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtihsqcbtu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtuudkdnsq.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtextlhpci.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtmzvzoeqo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtioytaekt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtwrujsrod.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtxozvjdri.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtlbqauepy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtzebapzlg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooklvcfx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlndlbqu.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtmukcltcc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtalljepuh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gtngxqviem.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtxapszweo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtjogxepca.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtorlcimcd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtchxmvzmv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtnyvvccse.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtvifgsqqc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gthoucbqwi.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtoqfvuqdz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtuerwohtf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtssdcbean.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtugppbzsi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtknfqilax.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtwvjmrgod.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gthptebpkq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtggqwlywe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbrjoapnh.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gttchvgjer.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjiilzyua.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtxaoyblak.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboncxkke.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gttllwmhom.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtiwxfvrfq.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtyxbkrpgz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtibbzbuhw.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtzfgtvuwk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtzhfvhgkj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtbqdllktk.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtmedcvzhd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtmrzvlqux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtpjfehoqz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtjdminjno.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtauwcxbks.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtfvgfjrbo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaonvgkfn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtlhkgohci.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtvsbtfovd.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwbdsgyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtqvpsaxre.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gttnchybxh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtstxkvvgw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtevlmadvy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtbxiadfwu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtnvdkgzcs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtxykbrruf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtssxckgvq.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtkyeejjug.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtqeyjyb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gthdjtgnnj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtttwbicjv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtpbrobwrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gteniicczw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcjbfcwp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtkkerhcui.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtumabtlxt.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtedvyrrrb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoivwesr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtvawukpqr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtdrfdmvdm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtakazxxdl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtidyikguh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gttajkmely.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtgzmjbsoc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtnamwcmht.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtweqvpuig.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtourlewyy.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtqfcjdwkr.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtxevnaelx.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtfborvijm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtpixxxwqv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gthjcnvoys.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwwfrcbk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzwyzcfs.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtzvmydwkv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtmlnmlamb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtpjswxhuo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtglpgsdkl.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtbvqnlnau.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtndelyant.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtjbeqrpcq.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtszepylut.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtzzuywbsg.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtehhyaoqw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtuuenrrpp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtdklulnvm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtfmhugrxa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdgnbrgqd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtvnyeustc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtzxaxarst.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtanqwlwre.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtkcqyqzjs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtknkvzbhy.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtmapjqigo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqjyizamp.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtibotnkeo.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gtpfhizgkj.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtwziiqrvj.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gthtigseyd.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtpzectljb.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtznwyhpkw.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtmttqeegm.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtwwqtqczp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtzglhznsc.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gteidklaff.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtgjdpazyb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoeaoaap.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gthqvjfsof.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtswhzhjet.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtmbodidka.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtgbvxgcgv.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtmkwrtdso.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gthoirwxnn.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtclxvkdiy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtaaolrhna.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtelacufnr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtfybfnqxt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtqvlxndit.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtkdrbaaes.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtecdeintl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtayvfbhpn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gthbrtwlgt.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtinwzxbvj.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtaisrnpqv.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtovthhmvk.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtlwimqwib.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtlcavsvdi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsewwiuyg.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtbxiyuynf.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtazktfqdy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtlovnrzgl.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtmdevcvib.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtcqvhcqko.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtvyiuhpsc.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtyseihvyv.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjpyzrnoa.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtpltfvtou.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtphhbajqf.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtuefvhqya.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtnoewcigi.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtmzvbdwdr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtzxqzdgqc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcngliwwi.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtspavjvmj.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtxrukhjug.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtmpfvgqsi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtbskzgtiw.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gtmfulsgcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdkfgnna.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtmasddqac.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtvhwhinrs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtiepogmmn.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtconvfegg.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtnetrtmzi.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtiwellfwv.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtaesyouau.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtshownusp.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtqkpumejq.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gttzvrfpko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gteurdiopf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtgnbcxmov.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtuclageks.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gthyngvyni.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gthleezdva.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtoksrudgf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtlqbnlplf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gtvhuuklsk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgwiswdz.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxjivmpy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtclqfrneh.html


<!-- 参考信息 -->