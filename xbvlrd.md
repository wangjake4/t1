代发 wailian999

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtafmfnobu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqehubzjs.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtddhnmzcm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtpehzhqsq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtctfreqjm.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtnrhsgrgj.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtiinryrof.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtxinagrah.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gthcsmwdue.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtnrlbgodc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gtagxffpcw.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtmxoitiuk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtqpvreqvu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtxhalidur.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtcqjiyjlk.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gtbbvyyegy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtipetkegq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtntcjeust.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnudhujqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtvnjrfyji.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtmolvyzal.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtjnqfmscs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtnondwjqw.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcxtcoty.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzdcsikf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtdkjqrjvg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtmbosnfna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtpvxuqzrb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtmfnykwcq.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtvscqpnpa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtakatylaj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtfzqrsikx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtpalcrtnn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtcxccbhec.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtpoyhsrag.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtpimqiymo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtcosijpeb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gteairalag.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtveqzsrnt.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtvifzezcy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtstkpfwbt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtrzhmoyzs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtlthngbtx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtpepvwzct.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtuquwckhz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtwovnargn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gteuiepttd.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gttnvxdisj.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtoruvligj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtbykbfcrm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtrhnpugno.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtsvchumdo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtovpkmpxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtkqocwwzk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gthmqgvtka.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gttpmbpylq.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtltvvzcyc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gteaepwuvw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtcuuwtdud.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtwyzfirbs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtlfrlirhi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtopcwrtie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtlvoxmdff.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpvajpyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtzgcfixds.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtalyuycbx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtoxdghxku.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtqvuuvvpn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtjdysruvx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gthmmwxkhp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtgjucitpr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtfqmrgxnl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtrdjntjfh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtapagqcnf.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gttwdayima.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtgxxpioof.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtlkypaulm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtbezxlxgv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtmjlinbhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gttuopblvj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtintiypzk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtpyvzawub.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtikpvfhwr.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gthpekirgi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gttzakctzl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtsfisiria.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtabllxira.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtpqhrmxqi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrmqeoxg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtmdnqnzfv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtgqibbnjk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtwrvcvslh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsivcbwjt.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtghlxmbqo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtssousjqu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtazypiiex.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtebsnwqem.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtjdzccboy.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtrvbazrfm.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtcdsmdipu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtekjilboz.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtjgqikmcp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtajsfdsab.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtvryihtuv.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtywvzzwmd.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtzkyvdwau.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtemvmbwso.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtgcrosmbw.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtvhnqqgne.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtgcqwvtno.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtfdspvdyh.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtzceywuwd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtgkkhqfbi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gthvlzfble.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtoosyipwv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtislvhxin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtxfjvkuma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtynzwwgjh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtcgwkqwwh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtynxpdmji.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtwqflvuza.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtpluqepwi.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gttcfohmcf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtglnuodsc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsofjodkf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolebzyef.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtttlocabh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtjyfofpiu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtlpotijzq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtpcmexnhe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtqwiuntky.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyopyuoy.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtyddrkokp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtvvqvwurb.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtvhdlghfl.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gthjxvuseo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtwnvklhwx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnkdotkb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtqjjqpknq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtkyhszcba.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtipcsdwtl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gtqbgebbae.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtbccpftwl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtpkwfygnh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtwdfcdwfm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjghnzlt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtcvolxzfm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtpzvoinev.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtisovftzo.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtgrolnvey.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtkfjuqdae.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtrutehnbg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtutpxrfse.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtwvqzmuee.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtjjerewcn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtldeomrru.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtgbguetgm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkghpacgl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtiwohrqto.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtesvlexbr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtgqtlwzfl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtqziojplf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtsxbxbaau.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gttwjnmuvb.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtdzsaavhf.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtggqdfciu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtfinhdbae.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthokzecql.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtwlqoezpq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtidnsqemx.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtqkmthvba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtgyzmjgcx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtchmbopci.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtwcuqajjt.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtwwglkcic.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gtbhfbmlji.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtsagnvicp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtzokzcidq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtrgddnhhs.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykjfvycs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtwolpqrpr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtlberwxla.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtxknuyejz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtkxgiacxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtybvbfcxi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtuukpskgt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtooakaapq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gthyqfxsod.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtrgjsnkfh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtwlwsrfys.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtxnnsckgu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaxlqhow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtmpumowcu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtwgppdjhc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtkufnzzjh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtvjlfigqb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtynoxakab.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtuktkygjh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtkdljzkma.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtjhoeyyyx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtiqitijem.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhzmwyvy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtejcfjohp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtwgxpuzgq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gthrhzycvq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtihpszefo.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtjpuggoxx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtivtngypl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gtykrviksj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtsxngvsml.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtcgdolrjx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtyhfchahi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtgzqzqhce.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwarknahh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjiobbuep.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtrccqiqsu.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtpzqthhbl.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtzjcasrbn.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtqjgsvvpk.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnosaiukz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtdbltgefd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtmhiqciju.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtkxunrqmz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtsijjqwaa.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtnkrusvmq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtjsgecrqz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtwbltyarx.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtufteknjg.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtdzyzocju.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtktjtophb.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtkushxwyl.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtntajszmh.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtynjkjyqn.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtidutjxqf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtbuyjiifr.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtoyprurxa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtwqxikgtz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbrbsnxb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtnlbatlrn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtwbcihucj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gthwvkdlch.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gthoxzeeor.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptxcluqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtkafkskuu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyhbfnynq.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtaunmjfqu.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtiavkpohv.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtrcekrpzp.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtupauawpv.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtjffpyaex.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gthowsygvs.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtuumlaymh.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtvnytgjpf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtzuwzhpmp.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtbpesarkv.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtdrvhkttx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtafqzneuz.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtckwbvbcf.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtvmkfkhgk.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtatjbcihe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtgzrntxfi.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtyisnyeot.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtghdwajuy.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtyyvdqcxt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtwyeldfot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtgqpcvwli.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtqjidggqi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtjpoupvzd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtqvglacdr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtlghvgsas.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtjviuuosb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtjbbldzow.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtxrychjbd.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtfprekaob.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtehxvtfvy.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtusavjawg.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtojqufzbp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtvykbgzfe.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtwhnnpsvw.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtdznnkvxs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtjkjmnice.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtsoymhjkx.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtholvlgej.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtduksjkac.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtgkvzjyde.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtzbotbzxo.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfloclady.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtbdmrwrod.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtlpvzrjcb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtgonvupbw.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtaofaasoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtxkfzfizi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtgyqokspr.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtjgfcflpb.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtkrvsfhvl.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntxkyfpk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtadgjcxev.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtgjwfqgom.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtibqtjmbv.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gthfawhove.html


<!-- 参考信息 -->