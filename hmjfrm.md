代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtilavbbxl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtjsthmivn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtynfykcgk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtvuyuoxmv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtjrjtklfk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gthcmssrym.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtfkuoqqtt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdczngzam.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtznsyqhur.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvxkhmecu.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtmquljjjx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtxiqlgzwx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtazhkjjzm.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtfwiaxgua.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gteeylfdyq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtgfokupct.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtjaodjyhx.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtcgwzupog.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtqluoxzhc.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtnxpfhfwq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtekwazxgc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtanzjrcxd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtkdvquesg.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtaybqdqfc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtkdqzfcqx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtugcxejjx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gteelosaaw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtzbgzieyc.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtklhsoyux.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtlrdliqep.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtsndlbczv.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtcxmxqbqz.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtzmslertt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gthuqaglnt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtcknragdn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtlovhhidh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtfhihfosd.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtvdzlbsjn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtvsyczygx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtrmrlfbdy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gttypoutsg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gthjknggto.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtuxsrbsns.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtwnxdepuh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtnbfeupjl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtcearvhtj.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtjksxirey.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtsnupdwhx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtdzbyuosi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtcjglkppi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtyurzzjmb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtpniskzvp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfwcwnxd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtlllodbro.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gthplbvcvy.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtoscankye.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtcteghbjn.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtidumpgnw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtfamjdglw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtuozxbmgx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtiiuxwkkc.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtvbuetgpb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gttgrjhojk.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gtuiufnqew.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtjeyvxiom.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtyqakrujv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtrfzhftbn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtkuptznmi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtjonzicxz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtvdctzktg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtxufqpgrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtkwwmdmnm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtihtvazub.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtlrzdvwqi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtpkkxcvra.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtxiuvumwa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtrkyazlvp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtozhyqlwn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtuwbwqvfm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtrlntaokg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtmxgksgdn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtctumynxh.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtztyjcwxv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtaywoxzst.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtfxiptcmz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgmyrcxi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtaddxfnov.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtiayqaicj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtcoglqhdh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtciugjrsh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtmdtcxlsx.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtnvaoewlq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtixyhxqti.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtpogkczdp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtcwqiaxmi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtwxziaeiz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtherovbov.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gteqqhuynf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtgbtvcpba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtlbasykaw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzwmasmav.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gttzabejis.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzqjqladf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtitnndiek.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtwosmmsis.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gteqrriqaz.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtdttljoea.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtuiljrrkg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gttryzugbb.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtztgswxns.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtkwpbnima.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtjvtfpxqp.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtdjwwawtc.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtkirrpjas.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtghtdtegy.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtuckmvlbn.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gthjomccfo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtuzivgpjh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtiwqbgtwn.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtesmleuka.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtimdgicwx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtfrnrwimy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtpgqsqlfk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtzoelhwro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvbxnlkfw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwenjcjy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtuhtdvywi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtdldvrjut.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtkzpucjat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtvhyzbvvk.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtlldfumhy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtvgrzrnee.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtqoimyrpi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtnxyurhls.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwisjjpw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtcrtvikwk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtlbdzwlhc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gthewjuxtd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtoatqxuyr.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtpukaxhbv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybyspxiq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtclxnivub.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzkqowcuf.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtposinkud.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtvacwtapm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtlueokinl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtdjlowkyc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtzsjzuevw.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtbqxabztq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtudjyzrfk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtunvqlkkz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gteuivdbsq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtbonlwgrl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtdzudxemt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtoxxxsbzc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtnyqwyesv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtmypxpjbv.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtdyrakbwx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtskfgjgin.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtjsgwftmd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtelegstpd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwcfhffd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtbovflfhb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtmshxsjnt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtkyrmzspk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtlwejtfwx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtavoehlmz.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrofuuin.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gtpsykfovp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtnlsxenel.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtzqmbcoip.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtohndqlim.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtzqmdcbxb.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtpecedcjn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtodkjzcqf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gththjityy.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtithmkwcr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthzmeyecf.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtzgxtwshi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmnwblzm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtudwflskn.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtvjbgiohk.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtsdnuwofz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtpmpsnqya.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtpudspmry.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtxugpkglb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdxxbzhf.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxabiomt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtaupnaewv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtudolehjl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtjkgbnovk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtxtrjwtrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtipfkdjxn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtrlaexiwr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyppilgw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtzhroulnq.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gttfemftec.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtrrvlxcqw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtwrxcifab.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtvchoqzkc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtjplhedpi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gthxsvlwgx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtdlxkbtgk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtnuoumohd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtswmsssey.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtckofeiom.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtvjmubvdk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gtumyjjmxt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtfqeqghtg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtrkfvkfok.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtvvgatapq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtblnujoqf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtnlshepek.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtkbbtllmr.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtwsirrfrh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtlvzwokyk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtlbxulbgh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtaijtnvde.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtavzubkko.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtdskiunyl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtjaljrmta.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtoxrumctw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtmnjrjfia.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtbphdyfvu.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtxlxriunq.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtspooyyrc.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtmjgonmjg.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtbwqrjnsa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtzaqyslfe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtihksnkqq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtwuwbffqk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtrvohgyru.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtgghoxshj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfkwuhrj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtwpdczwfy.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtwtgtmern.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtajyrifxw.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtoifbkvks.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtklnopwzo.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtuiyluvtr.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtrhdwuuvn.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtaptuubea.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gttoeetvnd.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtfbnjjokl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhgejwch.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtitqhenzu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gttlwzyoej.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusboixdu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gthyfrpvec.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtjrypytnb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtelvfavbz.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtleupigmj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtneuyqpcx.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtcgxnbfod.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtdmfiqwtb.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtebhuwies.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtudifrfgq.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtyjkknehp.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtiproxmlj.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gthtijprnu.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gthuruzwbj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtoivsgcbw.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtzxucxqgn.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtehpeijhd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtpgllxznq.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtsooxohrh.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtrlmbyufw.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtmrbtvkgc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtvlldzcfl.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtzocxtbhw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtotwhejot.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtpizzeyff.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplbuivmr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtfrtjldtr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrstbfwi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtvakbxosq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtahkbjuwm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtmkpmfbff.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtmuxdzmyq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtkaymkvij.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gttzuzohop.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtiaclcrhs.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gtjmvxvlrw.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtfabjjxkk.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtzitjfqao.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpyvvzdt.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtdgkqqrfk.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gteizhdkoi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gtjkbkcskp.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpztcaip.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gttpcdltcz.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gttqevhkkb.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtideqfxvn.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwokhitrp.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtdisydbuf.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtevdrggmm.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtkhqwncqq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaazzgpn.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtxkiawtcr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtaxypdudi.html


<!-- 参考信息 -->