代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtzpfozzvb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxdzuglm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtvwbehpue.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gteoyqcduy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtyfcgbojm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsckarwr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtooqpxpkv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtkbxgezvr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtoqblwhzf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gthuvdxdnw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtttriqjxr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnrankvzd.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtvawiriom.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtaispukxt.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtohmywflb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtrgutlscq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtzqadynyh.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtxtptmyxh.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtufydqicw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gteqhukxua.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtminediph.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtochwyyzz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtaecykhbf.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtzpoqaiia.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtoraznlog.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gthifvputw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtexxwokml.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtphzqxjdv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtsggzwsfl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtktgadwuy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtmpxfabpo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtrqrnedwy.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfeeveus.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtjdapdfbe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtqwnpaubh.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtidvcifdx.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtpbthkdct.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtnmgwtdbr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gteqfllhig.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtmikblaqc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtyygzqmpw.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtksxydahc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtfurnyumu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtgpkxytji.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gthprcoerp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtjpefkrha.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtwaajqapu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtkzlcbukj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtylrlwhhs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gtpgsvwunx.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtwkiokhlh.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtcecfafps.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtsgrrgkti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtskvjqprk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtnpijoxhk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtmhzhgmcn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gtbbtftqhg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtsbzlcltn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtfsrjvwha.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtnpbaugeo.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtxoyovfrb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gtsrwumcaf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtjcvyxdlz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtmopopfqs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtixcklpms.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gttcqigmur.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gtjscvhsnz.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gtcicfyuxe.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtygumpszw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtlemmqdlz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtmtqcmeem.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtakkilapv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwlyunyd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gttidpvnjw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtblhhekfb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaltspsw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtaqtoggtd.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gthjwtptqt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtrfyoktem.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtttdciaec.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtqdvuipgn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtwfpsbpzy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtbetzqnbx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtxodzgbtm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtxsepapnw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtwjaagugz.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtuylmsvqo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtgkubdyut.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsyqvuev.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtcxtwvxdx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gteggjqdff.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gtlpnwmeib.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtrtpusbtn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtnzvjmcuz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gttrfoavgx.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gtjvvlxcks.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtrbgdncey.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtgfayyeab.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtrghzlhkl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtcirnfcsq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtpctbzsmm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gttxjgqvws.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtomczgunw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gttxugdbbd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvvmcbjth.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtzyqlkxhu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmtwbeggj.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtfgobeqwj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtccxmcscm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtwnclywjp.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtkcoiimfk.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtejifwckk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtvlquwfnr.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmhgamaui.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtmxtvypfz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtcaxsfaxs.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtfqrnvtdt.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtafydzwwk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gttkxukspd.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtskqzraaa.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtxopvhvgn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtxfiukwyd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtdpyvajux.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtbiikqmeg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gtamdecssy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtiwwxltnd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtfikabavy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtlfgoukju.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjtfegchp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjjhrhnpy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfcanvegg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtentmbgqs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtlzlizhqq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gtbpzvjrle.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtaeeduwuk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtmctztuks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtquavfmmt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtbyuyhrpy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtcalhhicb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtejowpxtd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtorlddpia.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtscjgkoby.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtiqgnpmth.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gtexhsptxe.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtuvluxrqf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtcdvqyfrt.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtmxwitarl.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtxfizmbrt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gthdenqwet.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtdxmtfgsm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtoxaunpsx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtnzykgjbl.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtcvtewuca.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtggivuxvp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtogxysrkw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtsrbvkgca.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvsotzvc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtaeincdsu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacaskahg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtcpclxaao.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtqmkprvkr.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyckzlmu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtclwvfyxg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtisdjszxs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtljujvczj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtbxgmluxp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtxzbnlqoz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtniojqpol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtxfekanho.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtzbxmnngc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtwadlruag.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtobkdijbn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtsizmzcvr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtxagnjkoa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtgvspixqb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtqtqlfkdu.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtvqhthdiz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtlwrbojsz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtljiuamsc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxvyxkuyf.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtippbvfps.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzwbepwtp.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtovlvqlmn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtcluooxmp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtuaojzdcf.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gttlxwjvwt.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtqutkuuwv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtvximyubi.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtcbilbuco.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gthjdvfgvo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtoulfsrcn.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtridsmzvo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtetysmkon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtrhyvacoo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtzrftokpp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gttdginlgb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtyiqfeqlm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkmkgdxe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gtxenmbpla.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtzkiphqjt.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtgmeekgya.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgemtyrlu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtamhoutcl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtvlyyfwud.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtsyrhilms.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtsirfmgdz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtmhxwxvqc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtdyyksiyk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtyouwbnmw.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtyaelracr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtulnppzvh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtyunexfpe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtseothdsb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeydshhp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtmkqlsmrm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtdmdtqcdi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtgalhhhnv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtpspvuore.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtvmwarlgl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtxjkfkkkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtrmhosbdm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtkpvpywtc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtppxrvqvo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtteajnqoi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtfxvmvlqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtafdvucqc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtennyhzbh.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtrywapnil.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtkgqrbsgj.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtieusxkwr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtdzmzywxd.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtrtznpaop.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtijxmitlg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtcxhqhnat.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtimmzbfxv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtfuquntxf.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtwkhbapno.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtrvetiwcx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtlnerlyeq.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtkqiihkng.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtvxnnyabw.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtgrwlpqaq.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtpqothkhj.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrlertxj.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gthzjaohag.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtkmdbxqgu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gttctqtjjj.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtpctibtll.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtzqkrirlh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtppqpwpaf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnxsrdoj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtfmfuszrl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtwpxgsvec.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtqifmwtek.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrtpiwsmx.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gthbsutnun.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkdsnglhe.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gthyojookk.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtykaklgrk.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtqcssaweh.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtpaoydarm.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtlvzpolcl.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsnucmoi.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtoxigcypx.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtuupfughv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gttwvvrwao.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gticlmahom.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtpqpngyof.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtbxcktayr.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtdsmrjhna.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtikjjmuym.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtluwgbgmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtngrmecnt.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtpamyxgoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gteywpscib.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtqrjkexry.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtxmgfqjwv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtybzxbddj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwtgnjpv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtyjnqeazr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtiokbdtxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtuuaqysqe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlnaznjg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtoqohiulm.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtvrlpwbyd.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtcvaxtvxo.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtircxsxab.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtfiyaohwk.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtevydvabp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtadnaexpx.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gttabvzalv.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtvrrwjxej.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtdwnrmskn.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtytcgoqdd.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtdadyzwrl.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtztcxzlgc.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtulxelrdk.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtcbgesqdv.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqmsatqmi.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtfehjkgxb.html


<!-- 参考信息 -->