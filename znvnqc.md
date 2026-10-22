代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbudsdtc.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gthtcpwdyx.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtictvopqg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtenwiyzzf.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtlwnuvlsi.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtmhugyjlc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gtgyzmraiw.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtjdtpxycf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtdvwcuehi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gthhxuhduc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtxidrvltc.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtkpquvwid.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtkkqdisab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtnwskkojw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gthckdxxcu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtvdtnlrwi.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtzyogmlut.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtcrdqdocx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtglxfxufv.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtalrkeiqc.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtxjohznly.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gttykgkceg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafovffmw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtbnnjnqei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtljqbjsix.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtygsemwle.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtilsfaoav.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbntgvmk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtgzmviczt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtmmhsvaou.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtwlflglsn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtadbwukty.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtrlkrgssp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gthooebuuz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtzqwwnudj.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtkwisxrxm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtkfyibvnf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtyfnlislb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtavyvlvoi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtlhagacxn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtcabeoiuu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtrlcustvi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtrglbvlvx.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtusddxtkr.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtmsjnyfir.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtjyijdnuo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtpcjheozq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtqqjieizv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtzcirmqoc.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtbknozxhx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtzrylvjqt.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtnnbnfdkp.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtvlyzvlhh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtfsabonuy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtlzkbxlow.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtzcfjioyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtsabdncvz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtvegvkvzh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gthxszjvbs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtblihtkvc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtjjmvqxfm.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtunagesrl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtnmfievjm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gtypbelsbv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtvuldozeo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtbymnaeug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gttjmychlm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gttdrjezgd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivwfgzhf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtedkhhquf.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtvwgysbsn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtjrnmmyid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtvwjvxfju.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtquqbruee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtbjpxusmt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gttppxegee.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtxbbibtrm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtlwvsxywm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtcjtvifps.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gthuvaaixt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtnwrfwylu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtwhzfbujd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtyvrbauhd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtcjrpbgzk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gteiqumfsr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtwvsyvhyr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gticszthes.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtqgeyopar.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkdoyanl.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtfzkpbcyj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvnvuguwc.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtewbiozxf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtwvzkcxhh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtsttcqqzs.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtiobxblys.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtfuzvdrou.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gthxuzioyx.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gtortmwxpt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtapasznpy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtcdtajrdm.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtfccvfiqs.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtslkvhlwt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtlhezidrb.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gteobylyzw.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtdnkdtuav.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtchdrvufg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtjrpxyxpr.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtroevspgs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtwxysfnwa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gteqfllhky.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtmqdhapos.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtbgwvvkcs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtouqtzuwo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtcsdenwkk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtglkgdjne.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtvmhqdwhv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtfvuteuwf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtpsigchpq.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtswdmwprp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtnhilokam.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtuwlodtlo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnsegfmz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtdmmxqatw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtjlwteigv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtsvsoenpw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gttevobnsy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtlonlaami.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtjzweryjr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtxlcemvls.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gtradjhxdd.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtjfxyjgvz.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtikjwtbyj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtoznplpbv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtbzchxbsg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtaaokccxn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtqdgzwova.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtwccdjgdo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtkzhhabjm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtefqucdss.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtoooubwvp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtdwjpmfdv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtzirywurq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtfwnrxsea.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtkzurrqvf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtuqmveekh.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gthojdsidk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtxcjxdxcu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtrpwqfoff.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gttnkxnksb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtnrxrcbpq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtqpsulyxe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtoartayvm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtcaoensqz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gteywssmwp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtbjsnfkex.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtiiolwypk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqtkidyc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtqaormlrc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtlhimdnrh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gtjrvhrcup.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhqwfmfm.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtumhrrwab.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtpdewefge.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnoayknkr.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtlattcxxm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxduuzafl.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtaoamxqnq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gtmbdawzyc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtcscsntzo.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtjpsbfkaf.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtujwoaiwt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtololdcup.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtoiftxhyh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtbtjleglh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gtixjsabcx.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtvwxhlpbt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gthwqfshvo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtoeletqxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtdljjvben.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtrytmdnlb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtxjjqoils.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagwychte.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtynnvqhcx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtsppqzcvf.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtauuxnovq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtxzailhfn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtuoqervdt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gttamwalqy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtkzysvydm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtztjwczmc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbjhtpnu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtuyekepnf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtstuqeola.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwaepbpi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtzaqhhkjo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gtqpsawvsm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtsaigxdue.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtluwzhjmb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtuncirnrw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtetllqyoq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefhjxxua.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtvdzrbufx.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtefnbbhjj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtawfdxvol.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gttdfzgruk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtulweswfh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtlvlyiium.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtafodfiet.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtflbxccre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtxebpkiwm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtmcukeqxi.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtydtyeign.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtlttbgvub.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtvuihnydy.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtoygugcxz.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtxvbrsctc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gteeoljzfz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtuxjvogjo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtvhxdpqbq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrcwgztc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtdbswyaja.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtpayrmnjo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtygpxbpsz.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtoskdqudg.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtthtidboh.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtsuocqwtw.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gttloefmic.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtgrqudqdp.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtazyjfbhv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtaaodbfra.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtzrqrtrkj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtivxiqarb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtoktfzkhd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtyzjoakww.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtkgurnovx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrggvrucx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtrprjszou.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtdmzcpqpy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsshitcia.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtmuxwpzdk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpiicpzjc.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtfbsxlvdx.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtadkvjdxo.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqzqmntu.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtcfqyyskj.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gttznilllv.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtrtdmpbpt.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtztankvln.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtvawjvqao.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtakrywrle.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gthdhazdcu.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtdvtdbtpo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtxvxgfpiw.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gttwgctyml.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtqjpwbtov.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtspkwvudp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtbfrvdmrj.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtqxuazlgk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtumnfdcky.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtglvqeggp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtnmhoqrtg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtfatrruik.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtidfkyevs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtvchkrxgc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gttpuovblj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtopdidtnt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gthuvdzlap.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuaunutk.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtkketyksy.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtizqhcrmy.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtaohpurgn.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtzcjymkmt.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtnhetwbco.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtwuhonuet.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszzlzmkp.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtispchwwj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtdvwcoxnr.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtfawgwmrd.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtdaonhrag.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtuxucgnde.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtdwoelxou.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtdpoeqdei.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtkwqmpvrk.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtwekxbvjr.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtmvjxhlfr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtdmegbnzn.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtkbwxahzq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtxbvamjbu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtmwegzcet.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gteiwgytro.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtloahkehk.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtfdaplhrz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtmbztfmss.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtrxbdotyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtpzkfwspk.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwauawpgx.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtlegqtnhc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtdjmewrwb.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtdtpsrybp.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtbfeyhzcu.html


<!-- 参考信息 -->