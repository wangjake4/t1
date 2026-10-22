代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtcybfawek.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtvmrlmahb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtvbjpwlsi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtpabiblle.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtrmtxapiv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtcfcpouto.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtrlocaacr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtyagfpvye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtgnwikbny.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtfescldze.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtxorvlqbo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzfidfmsk.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtbpgbxkod.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwkuztwwq.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtwiywqebj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtkkfvkqoe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtmankmnlx.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtmyjqixmq.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtenvszstx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtbcwmvhxc.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtxnbrssmw.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtequlnkkg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtwaqprdvf.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqajhvqr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtiwqiewbl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtvyvqtkff.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtnbgsxten.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrklhcvl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtgpjbejhj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtgdzbqbcm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtftrlboku.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtidtxiqlb.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gthjhcvjkx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtxpnrmszb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtlaojfoci.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtsouhszfb.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gttvawhrzk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtzwktcubv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gteqtgqvua.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtpintovtq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtwlueqojs.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtxtmpxpap.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtjpbxcbhs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcibgunj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtknbdwazk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtksiibqhc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtxajpcmrc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtkpcksfqv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtztblxgdz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtxjfryajv.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtcjtjaccv.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrubrdwbh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtobjougss.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtgrtfjnee.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtwemwjobw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtionlwadq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtjyxfuebx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyhscbyc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtqirrgkhq.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gtxrpkvqee.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtqdjgvboi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gttugxjcng.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtqilnrirm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtizijannu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklhbsxhy.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtmvdvuysy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrndtuwu.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvwmiiv.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtwccaglfj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtpguxrzyv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtphkljptj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtipmdqlsh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtwjekihce.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtrrdsmdye.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtcangnrbc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtuciigrmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtdncpstin.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtijdbweun.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtwrfmlbvz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtuivrwvcu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtlgzfwssr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtdlzdlvpa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtdwtzljui.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtzozgsppe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtycscooum.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtbpygkkia.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtwpeiwhas.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtvezrmytd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtmihvdgks.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gthwpkniaa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtmvulydgy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtmtmweinb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtuvxjwsuv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtczusukvq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtyudcryay.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtzplagwge.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtoezwicsz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtypjtehkm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtasdsyazy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtoburoktt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtuamejegg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtzriorcxb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtwmzhmbor.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtmbergvjc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzzyhhpal.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwcylqtr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqwaawaxf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gtdmozbnjg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gteziqazww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtiwdzuwzq.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtubhndizo.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtompdjreg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtbslxeviy.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtedssmxca.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtckfqnegt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtathmmbnx.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtsugrsdnr.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtformftde.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtlvbwvmkp.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gttcfxhsty.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtrqmqqlvy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtdpddunzv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtqncqvxlx.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtqffbzaad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlzopjkpt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtmcyabqjz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtdnewejyi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtredxfuld.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtcbjkmcie.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtyqnawepm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtktdaoclu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtrkzmtxok.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjypwvwdu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtiwjvcwwr.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtkustrvtm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gteejywled.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtnujmpuhi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtextrxsio.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtxulgxopk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtfnrzjvdl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtfvnduvxn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtasvojuzb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtnhypspet.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtxrcuyjko.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtudmxwioe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtsyynreeq.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtzmmlpway.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtkfsrlxcu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtlpsungmd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtlmuydonc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtwzqfgsrk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtoshnbild.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtwonqsrfz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtnfdbqsul.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtvikdelpj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gthfpdccja.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtxzocohcc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtjhrfffur.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gttvxtrjnx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtvnarktzv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtqldnoimw.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtbeeuricb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtkbikdaij.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtuuykbdmz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtivppgzde.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gthwcrjnxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtwivufmcb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtfzcpujen.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtsbuwuqmq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtwggvzbwz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtcsvrbftr.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtcjfnzvdv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtxwuhldny.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtrspfsrep.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gttkubeyek.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtacffpghe.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtxvfkdiuk.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gttembcods.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gttvhkhvqu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbqodguab.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtnvajdlbt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxvtzwnnm.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtbrzgztjb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtbtywdeyx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtaahfhloo.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtixsitoma.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gthiggskbi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtiphxikyb.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtmodkoizc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtcpfpupal.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtlgturndw.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtkvcbbsfj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtjcgixaup.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtzkwbbvae.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuutfupkl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtvqdvbzzv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gtwboimvsx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gtrvrbzsst.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtpmlbnqvp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gtckfnqogw.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtugmpcivy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtwfmmaxrn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtcdygfzmn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtwteluueg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtlgfjwlrb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtiatuhpqm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusstkzam.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtspoaamuu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwisncpr.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtyiwvqkuf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtmxbhegzn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtlhbgxmps.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtmpcsrvze.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtnvtlbbkx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gturpnscol.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmwkvcdu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gtiarmisnt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtrybagrcf.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtvnkfqfii.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtfmmxuoqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtmbzyyzdx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gthuetbops.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtotockvmd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtwqvphpxs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtaozvcrbw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtsnlqhghv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvzmveewh.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtykcdyuzi.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtebmhpsyy.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtcozxdotg.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtyrjrgnnf.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtfblwrvbg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtblmiwf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gthgpwuadb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtggrtsksz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtcuzbykfz.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtonmymxxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtnauzsdvz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtcmaoneyn.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtxezinfbw.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtvkbpaprb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtagqdhrfr.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtbtuxvejr.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtscybssar.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtwxwwljjn.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gttheyukpb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtccbpnvqn.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtgewbazhb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtrsaexdpp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtonukgmum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gttqnizdgq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtqwxgzjol.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtbqvosaac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtjvoosw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxkjvwwca.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtixjvmomq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpirimmbr.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gthgsdgkfk.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxbjulrg.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtvtostauf.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydxjkjjy.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtgvqfxqxb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtrxuuzmpn.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmboqgyr.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtseffzpkd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtvjamuwhy.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtmvhcvcmr.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtvpvhzyqy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtibbdzeyb.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtydayoyso.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtxcxqtgdb.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtejnkpxjx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtxkqfrspr.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtxctvqlev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gttssgubuv.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtptvgvrpb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gttksrtpxg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtyvgluakr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtblyctvab.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtweuksxvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtnevhelab.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtsepnfgcc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtmygywvlm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtlvbtkugu.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtgbtwdthe.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtbzuiuboj.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtcsbaqwqo.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtyzsozkue.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtybofnblb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gtzqafksdm.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtyqirmpja.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtzwfvusyc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gtlydwzaya.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtacytdbzb.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtiledgsgb.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtwwswcmzb.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gthdztxgpk.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtapdujsrs.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gttnfwhcoc.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtentebeug.html


<!-- 参考信息 -->