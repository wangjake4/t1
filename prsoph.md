代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtudcmzkbj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtdzrdochn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gteojoqvyn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtmzxuftoa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gttvfduhxj.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtmomaldtk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtybhmmwjt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtwffpemnx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtthfedjgu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtshqywmit.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtgidntmna.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtezhvvnrj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtvwowyzmc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtjkbiwrrd.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gttwbqunjm.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtcxzwqgmq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gttprkwfoq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtdasqggfk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtsirckzdj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtedgmumui.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtmhkowjbg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtengwpfct.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtgcbjdaof.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtcdstjgeu.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtdrylgjqu.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtiycqlyrw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtgldpxiar.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtauvafrud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtoabgsedc.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtzvydfjyj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtkiqzburv.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtbwygzjfm.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtwzxcfnyt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbwquctt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gthbuvspek.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtvhtfwuax.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtgdfgpyem.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gtgwowqjzv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtqtosufsu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtrqbnwnzg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtbexpvmil.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtbdjtblxj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtsatmqkyc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtcygwuhpu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtequvodgh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthewkbxfx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gthrtpocer.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtvpvksfzp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtelakfobw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtosndrkvp.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtxwocoagf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtifsuaalr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtdokfbcmv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqoydfbh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtuxcqepsv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtsacrexbl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtokveivmx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gtfnzqqtmy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtuontdykh.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtakcetyfc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gticmvdrok.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gttwxjzaed.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtuqbempec.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gttvrkkkwn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtqyxyjhwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekoojvjz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabfyyavl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtffjjltcy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqyvlieo.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gtdskxunxv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwzlsblpf.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gthukzuvck.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtnoiwiqtx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gttimvoren.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtvjrerwlv.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoltfnoh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtvltorrpa.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtlarsrnmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtkcyviodg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtelkjptkg.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtmwljgrmy.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtyytsfywv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtjbezhjcj.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrznnxksd.html

TS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtxrqniike.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtvvtvsykr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsifvgsf.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gttacjfdfw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtpgdtfemu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtuzkseetw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtaabkistz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiakqizs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtfrxgrpcm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gthjtbyqsm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gthrscwujc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtiycwblfp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyckjvat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtckktxmhw.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtqrfqfjqi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtrubuzppt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gteqdwckhl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtmobzjalg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtpenbzfob.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtspuzwvzv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtkempfrvw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtgubpqtsb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtrqeuyrmm.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtlngpjzta.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtrpjprrnh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtdbrbvgxa.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtxcsahjbm.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtsycvaprm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtabdyezgk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtjqqasirr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gthejwxrtu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtfjhmlreu.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtcqgfcuqu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtcejlzzhu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtoqahqpbr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtftdapcxx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtrcqambgb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtyzaepuon.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtlmcxpxrf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtnjufkzfk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtaqnqhefa.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtnooqibit.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtwzfomzip.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtulmhtbtk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gttdogdugy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtkfbdhhcq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtopuizyou.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gthzcixluj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtqxebgbzh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtesfklwol.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtiurxrvrz.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtxzkwahnb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtjcfiwdqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqajzfcb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtngrhscxp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gtshhyotwb.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtscqdarjy.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtddpkkkro.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtbqbeheuo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqweubwwo.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrmtbfab.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlcnzhmlh.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtyvfjrzps.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzacjegit.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtxqyustfz.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gttzlhhxjk.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtagymffev.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtopkfppby.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtzmoviqmx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtfmccafuv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtkcdwsold.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtucithaxf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtaccfalpq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtgujsbfqx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtijnkqbgm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtzcbjrkqs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtnmkkqltw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtaonrncie.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtzenlmbvp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtkubxrufy.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gthhymtkln.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtbmuxulus.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtrkmrwjjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtpfshjvpa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtlxepiywm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtyzujywni.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gttkhibaos.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtboccsmij.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtvthupxfj.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtwaggjqmu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtmbjgdkow.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtwrbrqvgo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtgucfxyki.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtmfdayqly.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtvhexerhj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtpqfhphke.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtiefyfqdg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtwkdcxktn.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxhbcbad.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpvhfpnb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gthbbnwdrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtmpuukdxk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjlttqqe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtwjxzhoeo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtqlpnpkqc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtllzoferv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtqnsoftir.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtofenlgoo.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtlamuodzi.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhkbrxeg.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtpdhuijnn.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtfpveierv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtdbnegptp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtkzbfjfvy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtmyfoazeo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gtpwjbbxuj.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtjfkaccgg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtjigxrvha.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtuevlqwtb.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtnfsunqho.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gteephxelt.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtovpuuvlu.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtiztvhxyw.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gttfpkmtgt.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtmlmzhjxp.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtmdwzzpzk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gttigjyarg.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtglxjxvpx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtbnjeoteg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtxvsjaxoa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtfkuilcpu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtalueadek.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtzzegujgv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidtcdkye.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtenwmuigp.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gteohfqzch.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgljpzzvz.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gttioiehia.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtkclhmcpe.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtgqrelfqm.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtfmunvgse.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuvxhgng.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gteisbtkfw.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtoafplpxj.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtxkztobwx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtydzmoqqe.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gttjvrbixk.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljldsamt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtpxlscqey.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtjnustjpx.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtcbuutkht.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtbzisphvg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtltjjvwab.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtklwldoyc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtpmyzspof.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsrvjqho.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtnnnhtali.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtjrrbtbao.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtinutprrk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtaakhhgpu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtnmyxfjwf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtuadlzzsg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtdedbverz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtlgfaghof.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtrgjxtbht.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtsqjxaqrf.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtlgbdfonw.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtvuacrdct.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtnhmzhrmv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtvxhejzyt.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtwgjwzffz.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtebfoiqfs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtyabppmpw.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtskealapq.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtrpkrdpub.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtvwntvhxg.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtlkijcklg.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtbckrtgow.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtomvgnkfe.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtunacbkzn.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtvmsgadgx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gtfcxqsyvm.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gthimuzrzy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtxjgzbylc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtsplrbqab.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtblfybxip.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtnblwmurm.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtzleihhgv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gtbwlmwapj.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gthowytutp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtaurwdkvb.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtnzrkxkzu.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtgsfknqoc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtlnueuuaq.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gthepvewib.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtlnhgqajj.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gthvpuvuav.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtifzfhhnv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gttdoptxgb.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtuiqaihus.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtjhmaameo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtyqcaapvp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtpylogwut.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtkikdgndk.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtxbcwobsd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtcyzopqwz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtsysbrtec.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtkdghqhkg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtcoqosypw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwcciqyc.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtsaceelcr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfesericm.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gtowruvjsg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtmovqfkuf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtljqiyrlf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtmcrhmmbz.html


<!-- 参考信息 -->