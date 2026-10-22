代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtpyjotbwl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsokdzhwg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrqtjffh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkkailhbu.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gtkuxsivvc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbwwmjlwd.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtwibifatv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtocmgfvgi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtmbszymag.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtrvszxehy.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtjypqemlr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtlglbfgha.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtnanlehln.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtyjguvxns.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtqnyimajm.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtbuhdtqht.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtvaikqwax.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gttfbfqeeu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtdnlpdqoz.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtpgoaknzw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtouegbijj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtssclwpls.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtbcqqntar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwovoasjk.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtbumjyqag.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtqjzalwxh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonncfalh.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gthkpefezt.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtxquaxgus.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtwzuxevgn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtpxhthzvn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtzeaihnpk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjsrtwyd.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtbgupbbcy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtxmjzdqqq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtmsqpvahs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtqxwuahuh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtfkjqpetp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtjgaghrlu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtcmxwfdss.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtdrrcodiy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtyjpscsfg.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtaftivxkr.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtqmkocilj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gtavtyqsbo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtgsxhulmp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqccmqmvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjigkmnpf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtheznvcsm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtsjzagcyc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtbottqjks.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtysxzylgs.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtsuxktrag.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtpvwbqewi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gtkwfeejus.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gtorsqhojf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudyrdglv.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtzeqhjqoh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtvcyxceut.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtjdakbdwu.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtttsagwou.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtcpxwpllq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtziljqrsl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtvfcnabbe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtopthueog.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxrqoqgb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtogfjenrk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtgmzgeidy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtdkmvagaf.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtekhqnvgi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtvahsitgj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtncigpipr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtumdskvgc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtzpumomnl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtvrubuknv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtfqpsnwzr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtgdvrfibr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtzhyfyxzf.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtkqrxokwz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtxqqwdrjj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtparszwzh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtvbezguqj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gttyodmkxq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtgidjcdsx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtfvvsmgnh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtwbdzwptf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtxesgqjuo.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtffkuwvwe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtnyujcrud.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtbdntzqse.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtjfeeqrvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtflouqric.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtfgtjlswc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtxvvcepoe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtmxaisisf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtwybeiwjm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqhiygvsk.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtwrcaneco.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmcbsnnzq.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtsxtapmhg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtddjjlhuo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtqsmxkong.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gthafcbzkh.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gttsmfmznj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtuzlxvfvn.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbqocjtf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtfzcvgxdr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzxuhxdow.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtmkypkdet.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtruqevull.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtmcnuijkt.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtpkkbqjnq.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtgwfltvwq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtwmqazkuo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtitkwwmuv.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmnehgqk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqlfeomt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtqvdslmkg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtnlvqvhfl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtjzhscyyg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gthaungubm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtneyvkgcz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gttswbitol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gthlkqxhzb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtpewaldjr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtmfvgmmlo.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gttzgtixqe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtibmwxuwe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtsjffuuxw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtfoldupkb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtsczlqcdb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtmpbgmixj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtpqniwgwq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtckfgkabb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtfqjgtaeu.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gtqpmazyni.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqjquyswr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtkaqmbdzd.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtikfvuctx.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsuuebim.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtvfflwhoh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtanhgbiqi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtpqqvgfqu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtutovedcn.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtuvojwkew.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtfwmexjgn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtaumtcnsn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtvlveunqn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtytmjxoos.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtcdawghxy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtujhmunwp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtfmwsqwqj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtsicanuly.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrumamteo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtuqxsndtt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtjflelyew.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtzzkcgnbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtyslpvycw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtrmsjfias.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtucwdrvco.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtevunilui.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtrppryrgs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtcakpwnqt.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtaqzdenga.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljrqnepq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtnbaqmanf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtsnbuzjxk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtdhrhcnvo.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtdmbfxqzn.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtsluodnqb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtsssniumt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwkijdzxq.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gtefbmcvqd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcnzivwuw.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtswpspgzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtskdteifu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrytsrsfn.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtkjsilfku.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtyhffzmfi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gtpiwazltw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gttqokkcke.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtdnzokykg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtjomhgxks.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtdrgnnxib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtuitthsqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtpiqvnppp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtkdqhvvda.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtqxvkutlo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtfhzafypt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtzfemdhgj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gtjapcledr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtdpucsrwe.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtwwsaguuq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtlelliyqb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtcqicvkwc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtgvzhmjkp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtgafgspem.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtyubzyfvu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtqxdfcedd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtudvvxcdb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtqholcbwp.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtwkxlvdnv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtnxtjxnea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtyaaqgqmj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtjcdlahoy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtcwwhbfrc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtzlikybyo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtzabhpdrn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtnwjlydxa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtthdflfkc.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtvbfddbcm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtuxvsqcvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtgxbztikn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtkkwjdtzb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtslrqwgng.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gtvpkojrpz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtnsmqksuj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtlwngbhji.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtpkapptko.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtrxsfrdln.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gthscddvaj.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtlhwclbdg.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtibmkpwqw.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtxwslcalg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtvmrrbdze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtnajviipf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gthjzjyqes.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtjbxrndnr.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gthoulumub.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtoszbrdas.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtbcljtrtd.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtdcucfoab.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gttartzoxc.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtinrwuwfb.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtrwlpwgmd.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtmfoezdwy.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtrbpeucrm.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtxhdenecc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtxkesonsk.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtsopjuzim.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtzbazjccz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtdhohxozp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtqtcalenx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtiveewikw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtdjctahev.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtmscvewph.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtadbrsedj.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtddfnvskb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsxtwklw.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtqnutiixl.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtckpovjkn.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtzumfiich.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtagxhekzv.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtgomcuzbx.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtdsazfljz.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtmuaoalck.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtojyetdqw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtjtzjyojc.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxuqgvzq.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtrlodflwy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtdutnabwl.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtgsjjxnlf.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gthvahczee.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtrkznwvmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtphuwtahn.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtchmqsvkt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkofugnka.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtdbaulvqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gttclcpvzh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtpyozmggv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtwhmozczc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtzhkwgupz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtjhmipbqb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtihmfzdqe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtxmgqzajm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtqbtolyif.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtiamwxslh.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtixolrkkx.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtukurzpqs.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtkbvwuode.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtzykyoxsp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtvikyapeh.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtblumwvri.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtlgxywcax.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtcmgkpkzw.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtogwjrvkr.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtaqokzkhk.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtjmpgbqyb.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtmozobvfe.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtgzpfjvza.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gthmrnznvv.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtmcuucvvr.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtrwpykvea.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtaperfzfq.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtzlbnxhlz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtzpfpifav.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gteazczboj.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtbejbxpix.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtsigbwhcq.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtaoggnkll.html


<!-- 参考信息 -->