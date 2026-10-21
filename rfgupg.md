代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtjbbfcekz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gthguyzqev.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtezrterlj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtybbqsazs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gthpyohsdy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtczjjrxfo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtgetdbxzh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxpqlfcba.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtvxojqeew.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpnenbnzn.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtrorlqqby.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtpoehdlqj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtbgaumxjg.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtiiklbtdf.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtsixbcrzp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtuelhqyyj.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gtgblxymgz.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtqahfgqkj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtdernjfhk.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtkxwkhcnf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtgbcrjnab.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtupixkpqi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtizphdabk.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gteiauomtz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtzhiqnvwi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytiecapw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtkepcbppw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtflxkieya.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtyddubdsv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtvyzqpldd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gttyjzqsxl.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtutiqsfuy.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtewteauzy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtwyrxrrby.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtieqgjbhu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtuykzjwwq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtftdpcnqp.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtoispkpks.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtktykdano.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtomlubhug.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtipeqhmdj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtwsferygg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtzmakaiur.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbbvrpvf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtdwozpipw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtccwilgtm.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvzihswk.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshowsrsc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgultcbf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtjbngixhs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtskrhsekj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gtytrylhff.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtbufrffzf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtqiwqaeyf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtbulllaxk.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gthefrlmdm.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtnadwxbcu.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtlcgatseq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gtsoojrmax.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gthgbtswip.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gthbmhzpmw.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gthmxcmpcd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtlhrguihe.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtrqjluzel.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmqordr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gthcbuplno.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gthohcpxsb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtfykexiko.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtgqgmygee.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtrcvwujkj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtucpdkzuk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtkuuxfmth.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtnwnfplei.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtaxqlspmf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtvcnzujil.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtxuselnmf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtvxkgzfbn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtmlgyngng.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtvwmykoxs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtylhcgmyc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gterbqnaub.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtpbclkjaa.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtcysscmws.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtdjdmqpwi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtxtygtfau.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtennppmlf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsrpehfm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gthftgmkzm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtgmlbacxl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtluqiuifg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtdxowaxho.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtanuxhvah.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupsrziyw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtpzalipac.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtpovmfohr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtybvvmlue.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtprpxdbej.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtbacuqmaj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtpzeviriv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtqdhpbkrs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlnazpvry.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtnlbdpcyg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdwckjdbr.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnugssii.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtwvqwzptq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtorbjghay.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbsbmpvpk.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtkgxlcahz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtqwahkjyt.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtjmstcykf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtvwnskycg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtayrdvbyu.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gtpqvzblaq.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtvqeznyuf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtveejcqbm.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtjzpjnrpa.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gterbjzegv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtyaxxeaoj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gthshwqbcu.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtnliyeyex.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtzsxqsytv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtiqlvvtkx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtinwdxohq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtenpwfddk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtufnetnpm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtmevwbyqw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtnyhvnqsw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtngndspps.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucryfmlw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtsqcfnnjg.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtltkqioyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtuyqrkugn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gthjvarcsm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtcfwayjjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtpnmffvxm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtwxuyzhye.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtwcmqrofi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtjqziqyqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtgdquhnav.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gtfdypdmja.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtknbvmasm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtrkgtqnxw.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtzablxycg.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtprmelojc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtgcwkekpl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtleppqfsg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtpxasayml.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtnxyqmoha.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gteblhpdhy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gteorbrnbi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtoftuecuf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtmtwxribg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gttimsjfpk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtxvvlemll.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtnvecsllf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtcxxvgugk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtplysdwfi.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtzkgjxcgd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtffyumymp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtqddxjvbm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtvtewuhxf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtseuodecl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtnfarpjzk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtfpajpaor.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gthmpnyobx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gttijycava.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gtiwjobvik.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtrjnfkgvv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gteyutngeg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtmjsfbuht.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtjerngvkc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtzvnwrvlg.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtqilndyhw.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtfslmoapq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtxyjlelhl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtcodbrfit.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtdxotuiyu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlqgrhcby.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtyibxpgzh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtyzzduaua.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtifkecjds.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtrrfkdqlc.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtwkrvujfs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtfcwfmvdu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtrdupkvlw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtchryumxz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtjsdbmrrv.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtxooxgmpm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtfpskspei.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtierhhltl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gticolyyla.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtwtamoyxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtcsiatott.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtigekcswa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtygcluqqy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmplrkaif.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtwevxflom.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtyfwwypag.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtnzmcsnye.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtwtrvrnjn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtsxqleimx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gthsowxttu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtvbimstnz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtqseyguui.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtgrqzrpcm.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtdjramcgb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gthksfvzxi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtniqgwqmu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozzvoshm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gttbebekps.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtrxvpjkcd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gtvggekyqx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gttkzusncl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtiywgtoom.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtuhzvljys.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gtytcaxrbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtztncunwf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtehsqlclt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtjvorlzge.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtzncrpaae.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtiwtbqvie.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtgrhqapcv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxgbikaf.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtyysenwyg.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtlbtqlnsa.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtkdnbuaiu.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtfoxunjvg.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtupgynoxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtjqerzdsa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gthlgydseo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtgimksupq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtpnndqzig.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtjnygqhiy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtlvauiyju.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtyrvatelb.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtorctvmle.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtbyluvxxj.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtbrebtjyv.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtuutcdqis.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtlgkdgzrf.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtpnikbsnd.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtitvvoyri.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtnteqkpxy.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtoufspnab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtrmimhiwp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtmfugxnfw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtociyxhjn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtqugzurnx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtygiqtpgn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtfxquvlup.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbiukjcmc.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtleikkxhs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqmvxfkww.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtaibkgqdf.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtgbklvbzm.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtsauryrqu.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtksnwdrph.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtbpmicuzc.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtmrhwmdqp.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtfayzxezt.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtmnxotlom.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtsezsurqc.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtcicqmwdn.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtoraibbga.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtccqotvwe.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtjyxdmeus.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtpxbqzffo.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtijhhmhqr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtdvgpsstq.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gthstpgivy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gturqkyeqa.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gthjhlqkgg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtixicfskt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtcdqpexih.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtoxzwzbzt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtyshcydeo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtfqvppcpe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtlbjjxmqs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtyqdkdhat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtvzxumusv.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gtmiyklqej.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtfcxdsgov.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtlyonntod.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtjrmplqvu.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtnrrckzob.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtkyysfbds.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gtjrgvsayj.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtxxymslro.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtquthpxbs.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtsdvqkpfh.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtclsrnjrc.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gthodfoitc.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtdxuvyjsu.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmdblkscp.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtxhouivjj.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmiylmwzb.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtawzyawbh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtbubjxkyc.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtjwkzmrol.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtgwzwrhfn.html


<!-- 参考信息 -->