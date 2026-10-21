代发 wailian999

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtmwpojtbm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxjbfoshk.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtzlfrnsms.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gtrogrzose.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtcjmslkub.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtznucysfg.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtqneghuoe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtkrgdppiy.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtriiqnlll.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtqdupvjcn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtfmqqtfft.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtlavantny.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtwxzxiijo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtxareuwvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtbdsrbmgw.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfwuqxdy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtoqcrjjuq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtjgjufnsb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtbolpszar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtlzcgtjlv.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtzgyvnlqu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtrjyfcpnj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtfinpqkpp.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtsnulmqts.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtfkiuttom.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtszcxyqzw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gthlasbjha.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtoaixtdij.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtdlnryqho.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtkwmizorg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagjslbex.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtlsbmuqcq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtqgdkwkdj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtccxgmwuy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtrvelzbfx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtkenhbjlj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtjlesagyw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtzyrlximf.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtztrytgtk.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtoppwpzqx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtmhnjrdyg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtwaujtuhr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gteauliceb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtseckppsm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtxhclrmxo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtsrgavjue.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtddyjajpp.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtzzmhugnz.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtmjwmryws.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtkwrckocc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtdjzqvwcw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtaxyhxoxy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtegofwwaz.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtvmnizyvf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtimepfqin.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtuwlulxnu.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtenrysrox.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtqmyujizw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrebjllxl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtvicbmrgp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtjafqvdrp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtgkbbvvvb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtioarcgbi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtrgekjidf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtdhvdydyk.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtxbbzcrmr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtuenorsfs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtugxgswlr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtisflheqf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtjjvcgioa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtspfbjxnx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmaabkoc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtpodtqeiy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtqlwlsjwm.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtaushjvth.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtpzaijhid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtgotebtjx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gttyidkrox.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gttkbqerdx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtoznduhwg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtdjonzqlq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtbjezovfg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtckcoxxhd.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtdsbqqgct.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtdocrxsyf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtltthheqj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtshgrjfgc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtwiasufwk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtbwupepgk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtpydhvjbd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtozziaunp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelafzndx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqksjxudm.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtbbkijvik.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyiaghnav.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtdobljlpc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtkgkpoams.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfueqwura.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlkqbeypq.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtsftspvkp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gttjgtenpj.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtysimfwdi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtjucykrwb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtiajojhij.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtmuabpyhd.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtcxsgdnry.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdytogpel.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtanrndwlh.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtfohoxhyr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gthwdijwvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtsmudurfs.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqngxchgf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gthmcbzgtb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtmkpcsflu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtqtdwhicd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtllnxyzah.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtxihihxpx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gthxcvyshu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfzxroevl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gthvzafrcr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzswonkga.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gthshxxlri.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtnfxnwoni.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtnuqffdui.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtufoflopu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gthtwqgvkb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpenirizj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtordiiwef.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtlumzmdmj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtplonkdiq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtwzpvzydp.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtmkrwssus.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gthplpwuor.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtkxwpwkci.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtziqpezni.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtjkmiripb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gteohlyglc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtmiqfrqak.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtezdngbfu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtwfdbwlre.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtkkjdeawj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtibfretug.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtfhzahxdn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtbxctqldm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtlpohrrmr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtjchganat.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtpzssfnnj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtlybpokmj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtvlvocvuj.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtdghpwgnn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtphcthnci.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtmgwlxgis.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtecibsyvn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtukbbbcrk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtqoavmbmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtgylqkkcb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtfujiqsoa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtucfzzify.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtgbptvpad.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtodnxmrxu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtyrycfpky.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtlokmyipk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtwcobxesi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gteqppfiur.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtipayeoum.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbacxgirz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtviimfzts.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttsluvyfz.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnjrfotu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjoxkmymq.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtzrmngvyi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtiljodbzv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtykeaxwvp.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtxvwhscxz.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtedhojaot.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuzemxua.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcsncxox.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtecvyxnaj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtoidhopnf.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtjgijoxbp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtenbytxhb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtpgiiqgnk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtyqskrfeb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtlynthgcj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtaludmvyu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtpcrytjlv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtwbuubrad.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtbsmuslxs.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtvuzlvdcz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuuccnyy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtalrusfpd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtkxmrtzec.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtobdmpizs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtmhpvnhxf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtmzrnwuuo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtvcdrraio.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtckazxhsv.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtdlcomoaa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtrqwlwloy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtquczwmot.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtnfauzbal.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtikmolagm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtoagmgqvx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtlphvkvpr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtuedcgdfk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtdyvmrpkh.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtnvyxekyh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtpcauxcvs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtlvkytmov.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtxiyhifit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtjzbqdofk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtledkeehs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gthamuubqx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtjuxlzwvz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtkkkbylhg.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtryecloda.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gttejuojid.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtomfnimid.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtdbejwvqn.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtncqvcccy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtxgkprjrl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtroflagsm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtfofabtmw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtdaazvddl.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtlhuamxhg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gthklobhbk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtkrdevfdw.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtizgbhugl.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfhrfhsa.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtujidecur.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtbqzdrprj.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtxlksdoev.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtjkjuibpa.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtmybgnobq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiykjffc.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtnczbxomb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtggpedyxs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtssqjedqd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtusnquazx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gttjkmrjto.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtisucplfz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtikokiajr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtshcxhjpn.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtgnbsrwjk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzygthwet.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtvwyiavvo.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtlephfpsu.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gtknrlgvdt.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtseucowkw.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtbruhmsvc.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtjfsdhxtp.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtbuvwmayp.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtkejlikxg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtvmbsvjix.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxzcosvjy.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtjozrkzfe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtysiwnazm.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtutpcipif.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtxjbwrcvk.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtmotijpwi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtjzspfxyu.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtdjfpquez.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtrykrtrzy.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtoraetaed.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtqjajtydm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkqnoeae.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoifljdfu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtxxithkts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtgektgwxk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtotjddctb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtvkfrflhw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtsbusjfiy.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtqqmebmwv.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtvqpgbffp.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtibilfqlw.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtqatsgolf.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtlwplsklm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtlsyexdzq.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnwjlgso.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtwnywkjny.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtoyeoxetg.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtkesjsauh.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtvrcfagej.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtwhjmmkti.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtihktzjgu.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxiicacbd.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtsziqqmyj.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtxjrbaduh.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtxmzltqio.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtlndrgahv.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtbiompvel.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtlhgdkeai.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtdltjybur.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwgdnpzb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtpeiulawn.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gttlgeqcvr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtsyquftli.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtjkslsmlr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtwxmnbfbx.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtuhanxufk.html


<!-- 参考信息 -->