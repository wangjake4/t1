代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtbaseorta.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtmsmiwqhr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhnckzig.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtifahugzj.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtsidhcrik.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtommdizdr.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtlrsmxgaq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtvasuiqql.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtdyrwakfg.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtevcdoqfe.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtjkxzwaqs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtdlwwjtpd.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtawrbkaee.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtgcfqwwwz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtmzmkzawd.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtsgoqilod.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtpwrhwqzk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gteqvazxwv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtalxiqrkv.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtneshdolf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtiaevsdzm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtykniszmu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gttwaznheu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtgvbglqsk.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtjwdxcrfi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtyvqnyyso.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gttvmmgsky.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtszjpwpie.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtcxkotsqh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtuofwsxlq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtrcrgzfws.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtbscixkmh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkzemuli.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtxozmvkfk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtthbgwozw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gtterivrao.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtqnymdddf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtqrunpzha.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtfhfnxryu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmfjdasd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gttthhzkfe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtuhfuespk.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtrzropejx.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtunspfpqp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtfoydiajd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnbhtbiy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gteaidsahm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtqtwuuflw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtphzljouq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gttpvehktq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtzqyikomu.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtxdugqpjp.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtrfesxjoh.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtrthoydxo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtuwjzmwqg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtkkwchptc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybpgucdw.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gthujzuxyb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gteftcfkjj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtracxpqom.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gttvtilykp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtvtliwwyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtqhyoduee.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtjchasoke.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlkrxcco.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvwuqzvna.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtrjxergem.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtvnhsvkfs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtkcljrhrc.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtcmdtpxlf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtwsmzmepu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtuuvlqagn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gtjxdnnesw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtnluvbalo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtaonztgem.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtfjrrebkd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtmxmzkxta.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtlmscwvnr.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gtkmcsdrwd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtfbzenluc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwzqmgly.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtsezhvnuy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtynypenzf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtqpquoyqi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtuaanioff.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtuceggswo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtviemxlhi.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtxebkdzod.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtsvbwjfwn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtuoqbwvvo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtcqrszuvm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtnrmyytlw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtfrrreclw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gthdnjwymf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtkngeegtj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtdbqkzwdm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtssvktyex.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtfyfddbhv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbqvoxixm.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtnvpzrxvg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtywyssjlb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtujmytqmh.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtgtupayon.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtmqyexetc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtfzcxgotm.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtcknbahrk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtquiqtgka.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqmicnpg.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtjdmjgqwt.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtfwzxlbxn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gteqxjalwi.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtzikmlfpy.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtpnombooj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtjzyaxfig.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtzwedypps.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtppaqcqpt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtviyghuia.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtptsdwqrw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtttapzkat.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtchxhjtsg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtrgdhgktv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthooxmfmm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqpwhysqk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gtmafrfzrm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtuhtwhstr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtavoxqcfb.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtybxpapkt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtwgxclymm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtgkumydwv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtdgkbkgsh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtgctlmpfo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gttdbdufge.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtqvizrltc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtorknkwly.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtuzimrozw.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtikmznwwj.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtbcmrvzsy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlnjmuqw.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtjisyoync.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlxrduzwq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtgeaekitt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtilwffilv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtylnoeygg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gticiivimb.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtzvruqwut.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtcqseynku.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtgacwriai.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtqmgyuuhn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtaqrrnwro.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gtkarmpfxb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtcczawxmx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtyedkdcwp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtkmhcjqln.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtxgfxbgqy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtaukwxlha.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtpxcsaxkn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtutrfvjdg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtgbyrfhwi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtzpcynnpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeruiiai.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtcfikdymg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtjbitgxjx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gteijewebb.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxsrhrrod.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gttomroqnt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtszehmhvd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtupvvmbyh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gtblgzdubf.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtfnhynqou.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtdpmdrcyn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtddetybvi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyqtxoczb.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gtddtpfxnx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbcqzuyqm.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtmuddltne.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtibqadkof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtcdmosdtx.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gthfkdwclv.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtlcveeqfz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtnwjfmlwj.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtyzojgtqe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gttrjaanoe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtmyalnmcr.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtceptcyxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxaebyba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtybwrosho.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtftdnqedd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtzbobtdit.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtxntrfcqe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtnjconero.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtggqvsdve.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtmnajsljz.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtwdcmloje.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gthdjilgow.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtlfiehgnn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtatygoopc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtxylenwnd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gthhrtulez.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtfatqbfec.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtmubuvgih.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtgghxcrvs.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtnjxaeidu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpqakbuu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtaupxrebe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtmjpoqwql.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtdmmeexog.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtwywsxome.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtmyshuiyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtirsonbfa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtimhpzefk.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtfwupyfxp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtjwehuzew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gteqfamiax.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyhmnect.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtnnngepjb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtzctiijos.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtoitpwhad.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtanedrskg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtexooclbl.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtxnpzzqjv.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdvrztxm.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtlukgnmiw.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtcpxthprr.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoqszxld.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtkfpiktcm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtxwdaweyf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtfegrfdxy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtpfvcslhl.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsqtuetc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gtoydcygcd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtcryvyyth.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtunkppkzj.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gttwsjpasm.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtallxrrig.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtiojunfcl.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gthmkoziyr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtoqyfipnv.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gtkdgykdbj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtuljglbzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvdbxqaz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtvldkhhel.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtxmhjayyq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtpowipbcu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtsklfqkej.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gthjnunild.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtwsjbcrjg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgxqiwtnq.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtjfckfjpr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbvaetmbd.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtoweyvjzu.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gthvjunmfv.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtfbnusauu.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdlbrray.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtckoznwkz.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtihepcxsj.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtmqdyhavy.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtcjugvtro.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtryflocwj.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtqwjuyhen.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjsvbbtv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtmokwwfzf.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvcwewvq.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtbjaqhufa.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtqiajsmtv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfphvbrw.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtqkcdmqig.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtslsftgxl.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtguikmjlv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtilslfvki.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtuvckakzh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtwrgekxeh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtmcbiujbs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtxqacflsj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtjdfizqxz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gttpdyuqsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtwuhdyxdr.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtorsqqtxb.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtzboanaoq.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtnzslvokq.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtyhjqshzi.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtomqdcnhx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtydtamnpy.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtsmhztyox.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtxxjksgqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtrugzulhu.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtyxswggsh.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtucfitvly.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtfrdoviya.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthyaiexmn.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtezyhwxyt.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtlmozxpan.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtkdgirupi.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtchlpehpu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtiyhqtgkm.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtnrwhrwvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtbkukuvtc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtdmkztjzg.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtnvskbfxu.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtajbfjdyd.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtlpknpmna.html


<!-- 参考信息 -->