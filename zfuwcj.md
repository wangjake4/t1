代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtswvpjilm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtdblephcb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtksgznfiz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlrslega.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtffvukfzb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gttfmnfrhb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtrsawilkb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtnvbfzrsa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gtoqmmndme.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtrduwudfk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtssxblutq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzneehzme.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gteebyhjpf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdovjbkfo.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtxpeqbgru.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gttkspozmz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtaszkzqsu.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtldjhdool.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtgubltbmu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtkkgkinux.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtltqepnrx.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtasbnqkmk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtaxkqudyq.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtsjkbebgr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gticulkofp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtpujodiix.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtzjbdbyun.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtoaqlwkjg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtbiadvglj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtgkxngrly.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtiixhkooa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gtpumqytvc.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtojxjeoih.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtgxdudrjw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtmxkavykl.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtvlpbplfu.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtvrcckign.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeusivzj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtvpbaqcwk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtiqpezhnw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtrrfgqiow.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtsqchowix.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtiejhaubv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtfxqzauwc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gthntbuelc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtqzqkgzrc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtndykaruy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtfjfyskvg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gthlrotjyp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtxagiqceu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtfmxahwny.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtegnpxokq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gteyctwvtq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtsukbgggl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtidssbruy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtvuavxyqo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtqsallidf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtnefkyakp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtllcinwxc.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtktbgvjtx.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gttewoaowk.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtwlybehkc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gtveyjcbqo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtxxdikjnl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtnawytijd.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gthdhguzmm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtycgyrdqf.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtnchwvonp.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtaxzyxrme.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtpyflnyjl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtisiuxnvi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtfomhtamm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtksoawqgb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtixuppoxt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gthcyjzaur.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtigtlbcpb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtmqncbztk.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtujkvxdbc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtddcqntyc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtpslknfwk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtwfnpsrrh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjpbadoh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtdzvuywlz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtcdwqnivu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gtwzkkvomx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtjloudlfs.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtbpufknsk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtbpqltslw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqlufvwh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtcbuiomub.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtpvtmurhr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtmqiuyngn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtixphlsfw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtazxqwkqo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtfdrhnsky.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtufcsiqog.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtyducbtne.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtodxisgdn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtaqeujfar.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtyxdsysjt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtbthvintt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtkghxafqd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtbprlnvzv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtmoepzane.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthusflsiy.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtbhhheqgy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmufwfzjr.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtwuvrewkr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtjzwsrbuy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtavvxnpxj.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkwbrgjeh.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtyyyrziga.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtqzmpitte.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtjpvbsoub.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtyuaroqfb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtpwtfzpbz.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gthaycejpm.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtlycziuqf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtipucnvlh.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxcfzihr.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtrwuckyjd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtwnrzjqiu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtrbhfbclx.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtdynllkxo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtirertdfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtoultkdxk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtirszgwfl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtnfuwpbkn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtumuyaqfz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtfbskpzck.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtvatgensk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtvjeieyep.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtckhnfqrr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gttrbpmmod.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtwvlbhwsi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtjkzeaebs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtfqfqqqmv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtrxtjphdx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtunbqzubc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtosqxudcy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgeegxgd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtogstndvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gteflrrnjt.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtthecicft.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzxjgbvtj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtjyrmazxp.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtiprgdwyr.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtgxirkwys.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtdkczahbh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtfaeamyvd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gthylnzxel.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtqixzkouv.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtugygruwq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtatutkbnq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gtkojpwwic.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbscmaibz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtoimdfwar.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtxfwjqllw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtcymgarck.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqlqsqiz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtpkghpmkm.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtjdnuhtcm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtujuevvfd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtcqkhalru.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtdukvfnpq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtkfsymqmd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqwoofdol.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtwatzchdj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtolybkrgs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtvujqqojq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtbcuwqltc.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtnyjyhnck.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtbrwmzlng.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtwapgftex.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkjywvot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtsioitnzg.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gthdytpboa.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtfmzwerla.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtwtlwngry.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttufyfrul.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtzzuzkdhc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuezdtfce.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gttnglsnir.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinyhsbsh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtyjhblmjd.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglwhmzjk.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtnmlujhgd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtkbkggogy.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtpqkasxqo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtencgeoqc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtnxinmtax.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gticyhiofy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtyeexhnlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtkehrgqqu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtobccdyhn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtrbblundy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtlwuhbmia.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtfbdtcjjr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtzpamphhl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtjdzajfbu.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtaoadzazd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtnwxgluje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtaxzfivql.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtpcdxdlyy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtndqoipiu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtiasckmxc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtfvbzsuwg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtoolaucyh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtlgfkgoag.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtrgqnsbya.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtunorpmsp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtvduauetq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumvaxnsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtdoridpum.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtuoayjqyx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtelnjaukw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gteoexelwr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtdcmfpjku.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtkmbfizda.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqsxajyu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtbzlqvlhc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtyluhafmp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtnwybnhbg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtqaimssic.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtgenevzbl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhkmjyhf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtjvqggtue.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtuzdxzlls.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtbzwsmfgt.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtyyjxccqa.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtkyhhmpjk.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaxotrsy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtetlihcmf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtroqrgjxi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtqbqtpftd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtbzfvibpe.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpkycxgn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtziabylif.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtzvxaqoho.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtkezxrbdj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtytyiydyn.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtbflsafzj.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtjlgcfllv.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtxdjfvgao.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtyhglbhnj.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtdwoivjis.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtkosmbfbr.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gttdqmhboz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gttickrhsh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtoactbzqu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtfxufjmsh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtgovwflxj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtisnrugrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtwdmhcngk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtemjmbbry.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtlwlgvtpk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgkjzdned.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtjmzsdkkg.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtumpaoear.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtbjpvmubu.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtoyatgdap.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtcucdjgut.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtocamrddi.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtlqbvxmtq.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtnbfnmgjl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtqwjkykwl.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtnxeewlza.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtpkmwlilj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtibwpboql.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtkoamffoq.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucscbkux.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gthtnkbkja.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtlwymtxld.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtuktjreka.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtkqrvmuia.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtmqauyvta.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gthklhmjpw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtzbbpxgrk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtxuavmlhv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtpkphhxji.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtcdwigfvl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gthqdhpbxv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gthcxsgbrv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gturbnptut.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtciqwkyko.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtcqlidqyx.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtzjrwfgkc.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gttjqwhcpo.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtynyrndzf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtkemmewwk.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtjkavyakr.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtppovkjdu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtuunptroh.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtdkqiwwkx.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gttmnhqyzi.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtrkpjkjrd.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gteokvymxi.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtqsqbzkmw.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtyflwjqwb.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtxvknhiwl.html


<!-- 参考信息 -->