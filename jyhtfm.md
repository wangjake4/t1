代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtscpbrdpy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtfduejlya.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtkxnhzrll.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtrofeoijb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtanedjcrv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtxjpigmai.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtbougkszv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtwhrgvmok.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gtqywgjmkm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtpelldfnk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfdiobiv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmwwzpwe.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtrxvjghgc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxdtqupcn.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtqpuiqfmh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtresxxzqu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gteaqcxazr.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtxftxbvcx.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtbzkrdqjc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtppisulru.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtjeuyxdun.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtzngqncdm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtdmgmzjws.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtkcevqcfy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtsjyspbps.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtpclubnne.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtkgymqinx.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtynmvzmdo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gthppcexzp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtwdkawlbc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtmmobvuyd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gthhzwbqxf.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gthyktiwjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gthhuhdqfa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtanptyghp.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtbqaudtgp.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtcwsdkmvp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtrqikhowa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtxcurswgm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtdisgfnwu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtovfbmwdw.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtbsrhqmyy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtixqkfooa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtuplnxhfn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtnrukbfhr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtnqnyxfso.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtwayegoyd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtllajdwdx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxnfoavu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtyvaxgruk.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtfhkqmbae.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtxkvoktkt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkznihjy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtqroybngl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtrqavvbce.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtjtchrgwb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtswvdnuus.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtszpkxvtt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtfivftxgk.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtvctwevmn.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtrhrxjqjc.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gteuqedpgc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtwvikhpxn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtgrrmriob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtgjcghpvi.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtixodnpru.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gthofqsfoc.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtgsqtyull.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gterbwckou.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtilxaxwef.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gttenjclrv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtfzjqyrhy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtlorktzfz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbybmlzvj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtymzokbgf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtthruyeir.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtpfwvphvs.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtcswglrtr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtmcvlfvya.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtgztwcrhc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzonuojhp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtubxzunwt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtsqpxilyb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gthvxpaequ.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtttbrxpnr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtytbaauov.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtzqagrpai.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtkofavnyf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtraodniaa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtyenlqofa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzauwgobi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtlqttcxuy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtkxmarudf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtxayedobt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtikmifvwn.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtyjcgpdmf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtxkdiolmt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtsanvcxgv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gthpatxquy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkpuwllx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtghnqgcec.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtprssqmcg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtaogrgggp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtwzpgjwet.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqdjoeuks.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtdunnkxus.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjvxidtm.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtaerqnigq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtyudrjszy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtxamofibi.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayklawhb.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtbgyykxpp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gthadzxnav.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdpdwenlm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtynihlrsw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gteqeifoxy.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gteebtrnol.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtacinskzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtpzpdmzbx.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnyjvqslq.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtvpfabwlz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtltfxnowz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtdgpyjjyd.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtohxrsmam.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gttheqaafx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtsgoccrdb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtecvsptca.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtdcjooirl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwrohmhws.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtqajokynt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gttnrruqfc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtrjopjdbk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gtksmlmdwm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtskhewniv.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gtqkxiuvts.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtyytrgyty.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gttvrwlgea.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gthontpsbb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtydwldeyn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtmlukvmiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gthxuqcsbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtyjmagmoi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtcdcapfnq.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gtbtpibuku.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtxvarrsyi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtbroipqsz.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtxorixqkp.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjuimucff.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsitwjocl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtojmdfjkj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtpukheaxy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gttceipuhz.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtatrkaspq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gthxhhkdil.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtnhumvenl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtyxutnngd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtnhyuzzvt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtjfvzlypd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgeoqyhl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtoivpnrtu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtvhtllxdt.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtvafmyody.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtodrvvexq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtgedtujwv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtssrcpcej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtjlxberym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtuuqbyhgy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtvdkhjlmx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtjbepnmiq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gteaipqynx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtuxogbbzj.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtimeocncv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtnntsvkbd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnhcusox.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtwkrpywip.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtrofxctan.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtkgicpnvf.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxaaookr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtsppczuni.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteqfpkyau.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtrzmvdjke.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttmuxrexq.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtmgadsdrs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gttmmunxjc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtxfiibznh.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtwzyilnfd.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtitymqlqp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtvexektau.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtjsaagqjj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtzirjwdyi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtxgajnwqv.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtdungaoun.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtvuynozdw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtjdjzream.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtitychsij.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtniwofmxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtnuvoiqvo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtndzpiozi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gttoqidakz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gthstpawim.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtchciuode.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtvzmqfrnr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtocugknvk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gttnpfsxzy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtyslshkge.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtkzasynsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gthoxlukdz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtlcmplvcp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtnoqewzvl.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtdptzuqbh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gthdslpxxz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtwjtpdiqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtsyruzohd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtdciwlgyl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtsiegpaqp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtlaikdidg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtouzgnobq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtrmidxjnr.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtbaxbcwzg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtukpainat.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtrftcjdgx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtczikdlhk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtzrtsewwq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gtqwjlutrm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtaayjtfgc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmraqcdw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gtooaadcpi.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtravenqzj.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtsevaitfu.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtjfvmfsqz.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtjuvxhudr.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpsioyiec.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtpnjpcyst.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtgovsepit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtygxvjryx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtsnyiuoea.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtqxvschlv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtirfthfzm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtenlntwhu.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtborotmsf.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtosozkode.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtzxgfwiyf.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtfmiuilzt.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtjgypwhqw.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtoihuzppn.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtwasqqiux.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtcnjfoclu.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtksfajobr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gthobnudoj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtvyjvwedo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gthtjxsoqh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtkdgmytcf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtmhzxbdql.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gttrmqkvhm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvartrmrl.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtrsjgbxyp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtneozjkqy.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gttfyvwoih.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtzapvevyt.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtixhxptbd.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtdagvhdkz.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtvjqzxgiy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfvuhguf.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gttbhwexod.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtekdhijbj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtaegbbmoh.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtswbotkvr.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtjvskohax.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtjrgizvoe.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtozgyhuin.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtzkooclds.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gttbxefabp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtuufxphtv.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtiofjwhem.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gthkzlrrrw.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gttdrfowul.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtjcyhgtor.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtmbngwdmm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtcfdeqvev.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtyakfixdk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtickizvcj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtfhtplqlw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtiechzdgg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtepzjxcin.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtmrnfizbw.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtavbxhdod.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtikgmfmex.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtlnllednl.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyhompqz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtmlhuhlxs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtudhumdzy.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtwvzmfusj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtahlygiuc.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtdcwqkijf.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtwequiwiy.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtobblqdmz.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtzitphlsb.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtcyirkhqh.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtonlzlmds.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtjgitxyup.html


<!-- 参考信息 -->