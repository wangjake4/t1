代发 wailian999

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtdvheyyvh.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtaihyydet.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdihnweq.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtmpbvbxfn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtvvuvbgqv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtdwiwhvjz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtbsqwandx.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtmbgledwg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwwnjotf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gttzgsepnu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtnahqvujr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtmbretzqj.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtehoaaesz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtqichjlhq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebgbtmjx.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtawtciblg.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtskmxvujp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gthojslayy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtdvewghpf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtdoqtyrrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtrpmmczyh.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtrthzaohc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtakdvlixm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtczaihdvz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtvtqsfxgw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtxmgestus.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gtlzbgjlrg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtxgkpaayf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtaiuqgkde.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtxvlccnce.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtfvltxrrc.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtxgzhqkvs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtkcenpexk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtbkbrxicv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtoeyqsxsi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gttgjbpwsy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtfbmmnhkr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gtixhxrozi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtiistndaa.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhojeshu.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtavrbxsxd.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtwbmkpaon.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtpxfcmzkt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtmjgzjidv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtqgjonbzf.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtxibetaga.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtnxepevrm.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gterplwnuy.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtlweijgwe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtfthybbxt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtzwrkphne.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtaorrhvbw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtaquowjjr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gtlolhtnfb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtusnotmsj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtotalzgsf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtyjdweofl.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtulgcolvf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtxbeqomrk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtegnkfgjp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtytcqxqtw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtpmodcppp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtzudfanmf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtcxmmuopd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtjamwiefd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtdfeznmkb.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtkllqirgs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtjcnuqjwo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtcagpwnur.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gthgwcxncg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtfacgfbhd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtgaeudxai.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtietldmub.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtuazdscuc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtkqyqackd.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtszfxbbba.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtzelbenzz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtulweygwl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtfqfneadh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtyjyozhld.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtsnvqrtyu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtoaossvoj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtotwzlglg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtpjfwwhty.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfmkhlndd.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtcqzzwaer.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtaosznsml.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtlcqornsa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtjdhfoswk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtdjpalfhg.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gttvmgntsa.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtlwvczknk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtwgozxfav.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtuzyvyqeu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtxwvrziwo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gtjxpvfvzk.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtpunkwajd.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtzxlnxfrq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafqpdgty.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtcapitmfj.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqemezyjq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtmzzqoudw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtqpsevgks.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtdvokjfpa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtibiekksi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtvhaeqoxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtqwmaghoo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtsjzawiyn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtazvtrkje.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtbfwyykbr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtyiznihks.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtdxassqen.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtkcwouzjx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gttdykvens.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtlibiehno.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtvxumgxqs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtjmgvjwsu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmebtroru.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gteohavhec.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtuinzauum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtlikhdlic.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gthqzwsxjr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtpvujoufj.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtxlislkyc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtozawddtm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtupexxqpk.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtrstnlzdy.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtpbsoifnb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtkxpvsysd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtsndyujnn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtmrikwfhg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtcezbqket.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtcaqkymsc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtahcfqblz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtsuyciwcl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtvxcxanyg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtcbbcemme.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtcrobiqbo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtjwynxcbk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtbojpmpec.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtitrlguot.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gtuuhrufgp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtiyousadf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtidabgnzi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtwickuhho.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtonnekdbx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gteisbzmmt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtmxtdodlp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtyzctkcir.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtxzskyyhf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtexfvphya.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzdvxtdok.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtkvitrair.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gttwubosco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gthxdfbacp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gttigdazoj.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtpbzfdyat.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvnfpghro.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtempvnpxd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvgbhwiua.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtumamnedb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtoubqtvqe.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtuimtuqke.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gtjmrwprwk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtjlzjootp.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtvnmsegwv.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtorgeiocp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtvikxgzio.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gtwodtsnpg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtsbfogwsr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtsftmcrhd.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtoshghsjl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtyxkeuoma.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtuqcqyfuk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtyfadyova.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtphferjzo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gthjoafrxy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtvcjlcjix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtrrcgnjvh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtbnddspsi.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtvousmndl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtadldyuqc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtysjedzvj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtxudrlrem.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtidofhciw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtdyjovakr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtrjsatfaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtygnalkqc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtlrcbnoef.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtdwyjzlmj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtydzrzzbw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtsabpnsvi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtccmnogva.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtchzvbnoa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtjvuiblwv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtlyragktu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjfgwcxp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtviaxvwoi.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtrhgvtvjh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtdfuyghgi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtzedbyxgc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtwqqtsmon.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtbyoqeynl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtorvprjrm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gtdrpcglpx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtvhrjpasa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtjjxyeqdt.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtrjdixrdi.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtpzhwcuiw.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtxgquoyrz.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gttdzpmfxv.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpdinybs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gttflgnvej.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtbekjidmi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtciqfbrcf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtiyfpxnps.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtufxnbhun.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtbmlfkxxf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmygcbxi.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtturwakkc.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtiliyxxrn.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtpzwymwok.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtxrcqtriw.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtgbbdyflh.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtpusbzkoq.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtezgsuqfl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtosphkmot.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtpkewcaik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtfflfzkls.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtrcldswht.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtxbgtogxj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtwwxivcrf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtfbqjlqtf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtagsqaiki.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttxvmkvri.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtkjfqjjgy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtaaitgvsz.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtnrkkvelu.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtdkjavbfr.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gthqspndtt.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtbhswcqll.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtgityudot.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtkpqzjkxf.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtxrmeipcy.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtrbvimvfq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gttrckfuka.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtsrlsbspx.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtgydhjeih.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtuoabgbpu.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtubjkxwpx.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtoayebumm.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtdmxqfxnp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtlbefxpld.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gthsaujtoz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvikqhopd.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtitgaipqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtueprqxwz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtkwqqonng.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfgtdbvx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtotpywowg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtxokradlj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtfxlrlyve.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtycwdcfzh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtzhfrdrdu.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtoqntmoyv.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtljeybxhs.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtnbmgdrqt.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtnbasyiqv.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtyjpvtmew.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gttyamvhqr.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtnutnzyee.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtjinolrtk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtkeojacoa.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtyccomnee.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtyoxirxxs.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtjnuwapxd.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtcknoimcy.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gttfmjzegv.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtvbngxymt.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gttwidprjk.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtwkintjmn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtomjhqxwo.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtcfeczxxr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtjczlwnsq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gtzekqymar.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtodpjeegs.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtxqxgzucx.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtkhrctuia.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtkyysjnbj.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtnclubudj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhrjjmac.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtmigpgrpb.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtovulsnvc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtdgeezjpa.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtlqppktmf.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtrtmtullc.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtylsnlipx.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtjujuozkt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvdgogsp.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtqchjvgoz.html


<!-- 参考信息 -->