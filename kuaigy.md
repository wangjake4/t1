代发 wailian999

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2aujjnonp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ehhhryxv.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2mfahtwbs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2deavfciw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2eydstpux.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2sglfrbig.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2skkmxjfi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2jvkzeltu.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gt2zjiuecus.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gt2wusakndb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2dpxthdvd.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2chjnubxv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcpxewxg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2qnlktfei.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxcapmjr.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nambovsr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gt2mxseskvc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeswqjz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2fxbnbjsj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gt2tatypfyt.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2rmdrstss.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gt2lwjfqxxk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2jnyqazag.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2ianeuipd.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2hvrxilxa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqyqzhok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2rdpnazzf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2pjzxocoe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2lcbmdpjv.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2bvlmnlxj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bggxzlah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2tlwoojna.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2uvwbsrfg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2froorcxo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gt2tnewzehj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2weowldyz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2larachoa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2bjmhhtrz.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gt2ocygwrxf.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2wyytzafq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gt2vbhmzezo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2ywsgsnjz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2lbdnhrfo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2kymtouag.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eadbcsbr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2doffanpy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2sarbubpf.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2lunrigvw.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvbajwyw.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2azjsipwl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2kalhusdc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gt2negftjdk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gt2juzjjhmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2werbmkdo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2jvhtkdiy.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipnrppnp.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gt2sjvuknhx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2glemskzd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gt2aiscegxf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2jmzvjeba.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2mbnzhkvq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2ggdcqdwa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gt2tmigwlnj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2xklfemmc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2metwqsrp.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgutwxxg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gt2cijmnwfo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2zwjnzhmn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2vcxsyfyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiomlpmp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2umlknmbn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gt2bxrkdqhu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2nmblqeet.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2ukatbyuj.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2ithnqfwr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csrlpcaz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gt2nnssbnmr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2drilxucc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2rtgmpjjd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gt2ymtizldm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2ybvkcuib.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2zuxicuhr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2ljerfjcs.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2zkmpcnlj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2tqxvjjtn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2sptyjccb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2jjaiakhu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2wrvkabxl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gt2dhgyufsl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2jhcmbaov.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvjntuux.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gt2mgrgxjci.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hbufzurp.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2qfcyvnzt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kveabtmg.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gt2domgllnm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2jznuffhu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2qhufjffz.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2rnmkvspt.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2oiwybdgv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gt2pcskcpun.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gt2fxgjaaul.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2doeeatfk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixioecoh.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkhcouzo.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2kpsfpbfl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2gtrxrmrm.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kihgpnjr.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2oiuigjwm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqrfjzdi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2abbjulhy.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2aukrbcpz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2fxsetrzp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2mquwndpd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2qdbaqdmx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2opogcdgd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2fmfmqvme.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2rrbpnvtj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2dfpkasnj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkzteupv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2axkiigtp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gt2sqmdvseg.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2kdniszkw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2sgeahbaf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gt2uepxgjjz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2nztrfjty.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2vmlajyhg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2kndpfyer.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2tnjyltrw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2mpouyuhh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2vggjcipu.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2whhowjbq.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2hykhywkf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2nnnrmunn.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2yndafrdr.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2tfadzzwq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gt2vdaigxec.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2tpkyqoey.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2oyluyywh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2ymaiijvs.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2htoralua.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2knssgyhx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2fgwvozux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2bqmyrlhx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2bloberbs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2uveeooyx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2iilhphbu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2cfezlrmi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2cjuvondm.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gt2medbfdxi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuuhpvbk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2ddqbvmzm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2rrbmyqcq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2lhgvlmjs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2frcgbdzx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2cvrduack.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2qbdbnobu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2cvlelgpz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2blcrelmv.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2jkbqmtvx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2gjgmlfbe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2fpkfuxcz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2jvkexcga.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2kjcfuccn.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gt2zsjhnhnx.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gt2xktzzavx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2wumjyjmf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hkimfmlv.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gt2ajxcemwx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fujghivt.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2vfdmuqjt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkyhrrup.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkijszbw.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2bwfmeoly.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2scbkqpmr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2caimodsv.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2mypqextd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2vtnicbfq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gt2usetazvw.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxiswfvu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhupkwyb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gt2kjnuucql.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2jxxyygxf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2rzoubvto.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzmmlakl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2tdpqhaya.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gt2wimwsass.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gt2ushjbvux.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gt2jlnxsjge.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2spdxmmao.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2vvlzacuc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2wyyczozg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gt2bwesqpee.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2jjviaxvf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2vyuzqckg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gt2vvmsaowf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttpggsti.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmzchqls.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpyyqrbl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2knzvuiiw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2uqlnpfzm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2wfvftvpd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2dfhkoyki.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gt2oqpfhpwc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pscntcty.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2urrxxwgx.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrahmmax.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gt2xebyudmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2fjdqgcuj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2mqmfplzj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2qhhwhfkk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gt2deibaoem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqbvtlio.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gt2jvifxenh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2rwdvnile.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gt2wddtdyaq.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owlukfdj.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2farpwgby.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2inxgpbsq.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2dhdcyity.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2qjlcoyej.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gt2pbafjygy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gt2jzuonrvb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sonvjpcv.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uupkqlmp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gt2oxxjhuxz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2ovtmrtlj.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gt2owluwjxi.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2fknvlrcc.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2qfhdwzhp.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2cmjcvfxx.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gt2xsshzmjw.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2zuccetym.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2wkkznnln.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2wgylzuof.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcdhtjay.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewgrafsh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbggtoei.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2qafnwevv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gt2lrjkbewa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2hrbhndse.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2cfefmfaz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ztdgoghh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gt2fxhbpksz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yzencnrw.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2ydeomxai.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2qkkwgsgp.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzchsbjm.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2uecvhedq.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2enmwnzbc.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2tihoelsq.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2ofbatlpy.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2hjfxtdja.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxvxzfjl.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2rwitiwft.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2swlcauit.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2vddupzfn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2aouebkcd.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2udiwiwmj.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2sfpbhucr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2yrhvenrg.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfiedxlp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2ktelizdk.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2cqttwkzt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gt2vdlwydsr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gt2hhneavyb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2wvafyhmg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2btsjompl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfbyqajx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gt2usbjznjp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2mkthtnfj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2uhyiemfn.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2mnrtlmio.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2ebqlyvku.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2rrlrmszw.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2bskebunl.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2fozaqsua.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlftwbik.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2kibptdcx.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2wjiaxwcr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2ztlugnpb.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gt2sbmuvrda.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2kttmgmrj.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gt2ojnywepa.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hsxarvoa.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2gkviyagf.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2hdunswnv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlaqhhh.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhbkpetd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gt2moytqvkt.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gt2wszhfzav.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2cwcponoe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gt2lkfxuxvd.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2qflrpkiw.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgfthdvl.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2efdqvdig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2mjrosdfp.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gt2bbrvktmm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2mehywogp.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gt2vwivtqif.html


<!-- 参考信息 -->