代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gticiehaxf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gttuuqrbxk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtgpdrlfqs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gteqwzqipy.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtpifsvntz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtsrdisfjj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtdzyacjvj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtffilquer.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtpipzjvtb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtemuxfamt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtqivtvmlz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtktdhyfll.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthgmdnzi.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtyaqmdhbn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkapcihsw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtypvdigcl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gttneyffzv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtgowksryp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtnyuccwkf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtslagsmgy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtwsfzraie.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtdzafpfoc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtrjrxgdop.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtbsrbpcoz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtwtdaaayc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtopuuwzzg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpckamusi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtshbwktoc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtmwtkhmsh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoxivrep.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtlcrtjsmv.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtktrgudjv.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gtbeweuozm.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtukhbzlya.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtxlmsydhv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtnrbfdcfm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gtyyfiygci.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gtshqbdtku.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtvfpfxlcb.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtsbwxokpl.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtvprhiamh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtdnhwilvc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtywkriqjj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtahcdovmi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtsnanhsdw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gtpvgbvzoz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtsedvjxxn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvixvnqr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gttmclxomp.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtajhovkip.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtcxvfwodu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtunnqshbx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtcsivubnc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtlijhkhaz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtdnqxwvok.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtrrmbthjp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtbddtrbps.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtjrrfghhh.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtljmctvvt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtywicraqs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtbtdgzmnv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtgqqjghnn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtxspmpisf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtdkaqswik.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtsrkgovba.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtajslhyre.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gteizzzxlz.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtvpeircxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtkunfrjez.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtjveneznc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtjaqrkvgd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtwwzssmcq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqfyiharn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtyegujggp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpuzbvjy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtgnkbzbrl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgpemrstj.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtpsknjxxp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqhyoaxyw.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtmiumdlmf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqwbtaxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtmwmftkyc.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxxxrkezo.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtmvlnnmdw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtumhkhisn.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtdopucnzb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmnrwvxe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gttcckinxq.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtqoefqyaj.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtpwuslmih.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gttddnilkd.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtkujkpzfs.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtqxbxlbov.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtgqjwuzxk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtlroqhzxy.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggrqwejf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtuiqiyjpw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtwzupljje.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtqcnfpvpl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtbaqfisst.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gttiektnqb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtkyixhrmy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtbahjfkiy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtdrhtvsaf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtiofbgfsa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtbylcxuzi.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gttswhohqt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtdkebufjg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gtrgtdxyli.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gttkrbjkys.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtzxwlywab.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtnvounbpv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtdbmotuha.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtobekqhdz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtrrofpdxv.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtirxvscrk.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtnlspkmvy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtidsxrhls.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtuuuiotwd.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtjjdqkufj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjclhlkyy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtvxectjnf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtmfzpyddh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtpffvjxfv.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtyonhbmgm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gtlsozeaso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtjnmknseg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtbzisgupy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gteuhzbjvi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaiqyafn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtrmcjuoah.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtnxtazplk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtfympgaih.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtezqhutvl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtulebtzab.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtqcbaytdf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtuqlktwju.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtajsbgrdq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gthhjpfand.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtaxiykenb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtcocousgz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtatulivel.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gtttyaksjk.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtdpuqsrrr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtsmjwqrwj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaacgcwjz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gthvgeljrn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtrmwjdybf.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtxkysgfov.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtiggmggwk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtoyghrira.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqpmuweno.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtggpvabod.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfsszqlul.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevtmhvde.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtyhrghsdo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtjohftcul.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmvwnurx.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtezydnbmx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdwmtsen.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtbfrazxdn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtavzvdltm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtxeaaahbp.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtjwrsvidm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gthxzgrxnn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtaicwlbre.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtedrjhdqk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gteoixlnmp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtcrsxsddg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtxhcbbuvs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtlhbncdpm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtjdsvkffg.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtlevjsggd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtilykjsio.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gttnnejxwt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtpnlijpcr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtfprsqiib.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtchcrkumy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtejkfdqpq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtkmgxbqyp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtjusbofls.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtspidwekw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gtnxkxljju.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtdhtpuzum.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtvaeqtxwy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtcztmjhpc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtaebvotje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtutyycfkk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtpnedpdrx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtgmsnnpkn.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtwlrdrmkb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gthnmxipwa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gthlouklpk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gttloucqjp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtwciawhys.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtjwbsnumr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gthxgrlruw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtinukitbb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtotgiaqlm.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtyaifdnkk.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtaepexajm.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtnbvukgjd.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtaaerxcnu.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtziyuvqyt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwgdxhwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtzqpuuhfj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtgkpkceyt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtdsmribnx.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtoidvikzh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gtgretyfin.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtkbpbnbok.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtyksgddxz.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gthjevnles.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtlydlcsaa.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtlpizupye.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtlljkwnpf.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtumlabtey.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtitfrhysl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtgznsgkgv.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtudhgcfqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtqivveiia.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtebnqfbcp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtjhobpduh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovqkoayl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtukhjeezc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtawsxrqoi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpoulayzm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtzkybuadw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtarbpcykr.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtinqvlbix.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtsrwuatro.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtfvqqnyty.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtvkptrott.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtvhmgivom.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtwftlrxfo.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtnjtpskof.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtujionzuh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaehrmybb.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtadnsulpe.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtdigzpnig.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtztbympqf.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtnzxonylo.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtnzxerbmr.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtapwyxmyo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtgadxyylb.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtedhurnbe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtskmehwuk.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxrahlxt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtlnqfosle.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtntnqwjvq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtxsvmykyr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtasbvqxem.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtoywpmucw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpsbamoj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtxuhzgqko.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtelwertlb.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtenwjbjow.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtoeoeuziy.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtftnkkucg.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtlemfszud.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtvxvjenyc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtarkueetu.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtqdlifcci.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtpglhjpsn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtzkrsgbmr.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtgdkhpfnn.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gthvgodubs.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtechdqhur.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtziwhzwna.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtypiuxpvo.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtwmdzzcpq.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gtettzqtfz.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtddiuzeto.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtpguwytmh.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtqehlavqw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtatfvsunz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtexdunfqa.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtfjozhjqm.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtnlwujhnd.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtgmqzcslp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtdeszruga.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtcxpabjos.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtpwznivel.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtgepwgynj.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtslccrjfd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtvyzpdkur.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtiqzqbrcd.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtsdlkcuqa.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtynjgmkrl.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtntacespo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gttywvvynf.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtskcdddce.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtwaagponj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtzlnknlqh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtzrlqjyhn.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtglafgdzk.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtgfunfaby.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gttrionicc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtnaifsvqh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gteiwdacjg.html


<!-- 参考信息 -->