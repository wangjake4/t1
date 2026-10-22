代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwscrscw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owrhisqe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2herbfkok.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xywuklal.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2sirdfcyp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jlfnrfaj.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2bevobhau.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2vhidszdu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2oznwfrqq.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2zhcyxhwj.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2lhgyzofx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2lsoadrsi.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2ccyfwejx.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gt2untkfyjm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2ypldzvzz.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2mrcepkwa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2nvmrevfn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqonovql.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gt2ogiwozuz.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gt2dzqgsuwe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2smrbeqdf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2fmcdxwsb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2ecqainvq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2lerrmayb.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2zkgxdvkw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gt2hdsyrqed.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gt2wlacpusw.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2rwizwuaz.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2ehsopgqs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdedhvwj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2plpjuesy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2slqipixj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2tweduwrl.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2jflwfqfw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2jytyqhui.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvftiubn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtzothct.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nowgrhas.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gt2ycchdbtj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2nxbmlako.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gt2ayvfojqo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttrpogey.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2qvgtywnx.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2blandvam.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gt2tawjpvqz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqtsmais.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2mxhfdqto.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2gxwnsgxf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2ymkqjolz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjirfsmk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2yxspjsrc.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjfljwnn.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2wunczcbt.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gt2coaemtvn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2ilcifdux.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2xafwwkns.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2oiemnyul.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkyzkikh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gt2htiydfii.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2ftkowaoi.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gt2hifaostt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2ssovmguw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2igvrsolt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2pwjnehxa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2pabjjvjf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qygsncfe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gt2bbmjhafn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2wxjirmtz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2vjyrzrjp.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2mlzxfkjj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gt2nbdxfkmb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gt2gpnrcgph.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2eejnryfg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gt2comipycm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2uqxeodvi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2zxuovcez.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2mwuygjtv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gt2nnuomtwp.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gt2tcskpngj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztaqhpcy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gt2jblkrvan.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2soxsfyhx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2bnwghjlg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2suvpxuxs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2dpnegjar.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gt2fpmtsyma.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gt2otnpmwbv.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebscntiy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gt2nnpmvaeu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2dehpstwx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2tmyidvqo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2jcspumim.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zouhpzgz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2jjjgkxfy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2vtypokqx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2rzqiyfja.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2aktuafvg.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2hzqcyozn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2elcopipz.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2lheqognv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2snvxzatj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2eoamsmln.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2qzjzimhg.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2wyuudpxx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2tbjhwxeg.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ldoeziyk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gt2bvfrkxxr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nosmjcuo.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2stzhycnr.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2yyygweov.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gt2icyqbhlm.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2qfzcdupc.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxnctdwz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2pbraqopk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2pwveksvb.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2qllvlvtr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gt2asshirui.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2grsiounq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2ddwqebey.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2durmjack.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyutmsal.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrahfjgq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2higjuuum.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gt2sshhzxsf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gt2jyrnrjdp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gt2pibctcje.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2jtkqluhd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2uiielmtq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2xknvfchh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2vmzjpxjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljawkskd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2lodkuizb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2hynohikh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2gcbzqojw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2zxkhotzf.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2euqxmjkk.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gt2xfyijjch.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gt2wlaniomd.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2hqnivxvh.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2obabshfk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2dxowrnib.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2ojcaynap.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhqcdxxi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2mqaitxpt.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2nbjhligd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjkowddh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2reyrncrk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2gixpryub.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2zspofrrh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2kwaigqvp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2mczyhqhg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2yzyyvapg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2bithsaic.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2asackvso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2wtnmbwys.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2ftlaskbs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ungnuvml.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2lyzzhtue.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeqnphnv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gt2xfjrsjbe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2nurjgnks.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khuxodhn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gt2gsrkubmy.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gt2jpyjxevv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2ahbeagdg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2jnqgweff.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2akixdpwj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gt2hpctcbvt.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gt2wofelvui.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gt2mgjhhdzh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdpcklwm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2flwzblcb.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gt2ibdengma.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ktefyvtf.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gt2kklyjvyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2hrrjijhh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2axcijdag.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2hxopyzic.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2tahfdlqh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2rakpspph.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2kajyxlqz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btrycbzb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2xvlpznbj.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2htcohzcs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2waunztok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gt2navljozz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2izmnscbx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2wzyapoxp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2lzubdapq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2sqcsxbmr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2qsmnfgih.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2oubtedzl.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2uiwektsh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2lewjlcqf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2zuggylpx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2jgwrisqg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2fcgfwwqt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2vvajhtei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2rjldqanb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gt2lbpqmokd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2wkesrjvz.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2pexsdaln.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2oxwqrubu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gt2novbxuck.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2dratdumo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2myvirrmg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mobejplm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gt2sejzyaoz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2ucrhcvbh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gt2mruwofpd.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gt2vttusxhi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2yntmwxbt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2wtqvxedv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2drzbuhys.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2inhzvzhs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2smbhnefn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gt2pjsflatd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2txzryirx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2ujymjmlb.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gt2jcnrjlea.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2avlyimuq.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhboigys.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2daibitln.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2uwyrmgpw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2djxnlsuo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2zqldfxoe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2kgqzfckx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2dwboyupi.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2rgeaswyh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gt2idapbclm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2acldlrqa.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2hzalpoyv.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2fspjjovg.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gt2soansiuh.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2vcodpnwq.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2muinimwi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qnegcdsk.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2skimjbku.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2fqcyejhh.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2qvaqxcyq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2dyeyregi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2uelbjyjh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2pjtsrohn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2jsfomkou.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2jvvwnqbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prepraci.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zehgnivv.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2cqzmscoi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2umsgclws.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2mfckyqya.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gt2nhbjtuln.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2odzicxmu.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2irojjpcc.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2fawtksbj.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2gshydhvt.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2cigezstb.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gt2esvwxpdq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2vxxtpqaj.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2sdrrdkju.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2pelnkujb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2lacsbxkj.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2stjfjprp.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2hhmntlad.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2ifbahqtg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2gzsbxfcq.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2qgvciuqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2btxjluhc.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2nynrnwce.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2bdaznges.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2ewcfsrkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2wgfyqqnr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2tmothusi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2gshwinzz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2sxfiidqm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2zxdpkguk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gt2oweurkuk.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2ntltxexz.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gt2kybjfsjn.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2altljowl.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2skkwubku.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nszsepgj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2xrsvqdnm.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gt2ejfwneht.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gt2nkmmlzfl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2weqfidbl.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gt2gtjoghnb.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2qifollbk.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2cnbhzfgr.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2zaivsqer.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2smmefuru.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ntkjqiou.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2fwafxxvo.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gt2mwdxihpw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2zjvzrhgc.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gt2bcqaoahy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gt2iujtjwqy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2rodgxjxh.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2hkdkhqwl.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2glphkkqn.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2utercuvk.html


<!-- 参考信息 -->