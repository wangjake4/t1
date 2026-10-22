代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2safyjwkz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2sogaqutf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2xzejjyxd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2vndnzegr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyzoydbw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2duyetzqb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2rsdbefow.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2iwdaeahf.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2mmksaqgy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hqrvepcf.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2lfslbcoq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2fvtbesnr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2hhbbdhis.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2pyfweusv.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2imlmrprm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2psyhykhl.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2hhpswyht.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gt2jvnbppzo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2hyadzprb.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igtpmwmd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2rctuugra.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2eueaiigv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2xwvgfoit.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gt2xxiumnfj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2epivwlxn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2mdfqrbxa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2jnsmexxr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2owtogndq.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gt2owwnnahn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gt2qyudwjcs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2cmbkxrfn.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2isdhbxvv.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2dgfdpkbr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2qqtdhuie.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2ikollflb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gneamkhc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2benstful.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gt2rdvynupx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhbmmsxf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gt2pedxxmxo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gt2vnvecghh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2bqwlqzyu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2oqmlucvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2tyrdgmxt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2bxidtxcw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2hcvrsyhh.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdxcyubo.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeeomolm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2bfczrzru.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2rlfymxzp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2owpzdjsn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocbejfur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2nyylmtpu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2dnivzlju.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2iewlvknb.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyweoran.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gt2ybpgscrb.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gt2xpyktzgz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gt2jiitfrhh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2yxyekiuh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2kivnmpmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2vmklscst.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2ecknmkgh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cteuxdpp.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2fyankdje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njygvimy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2szfuelmb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2vxylpwef.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhwcdqzx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gt2epjgjlwi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2uuvwcaus.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2fagcnaeb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2nwpkhead.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2zllsvprs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gt2etcsckug.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gt2ctgevnkc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gt2bbzfoeet.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gt2uwsesrsp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxqzhcfz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2evuemmzi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2yvgwyect.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2riccyvdz.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2cmclqvxs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2iberhdik.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2tbdeliba.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixklngfl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2toyolvjx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2fztnaxzk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gt2rbsskhcq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2lejobfez.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2wxwjvike.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gt2yorytzup.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gt2yteeqnhw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2xxrierww.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2udxiblud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2ezvspjtk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2fxthfaer.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gt2dikwumpy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2lhdluzmw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2dqqxlqer.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wixgxisv.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2zamxyhuw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ojzlsypx.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddyirtao.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2xrrffbgi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwqrdduu.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2tgcknwgd.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ipxnhtxr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2dvgpotaq.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ifbmrgbx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gt2eavhcjdv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2wnhxzghm.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gt2dnhnwder.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlqaywhm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2gqqbguhi.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2hsdecmrf.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2dfsnanbj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2nsutezvy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2csaowckq.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2oqidwzhs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2fcapphbg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gt2upxxivbj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2zjgofrse.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2eldskwfj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2qinnnunr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2uvgbcsow.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2nwaswfmm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gt2uogwkfzn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gt2daxntxrc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gt2lrfoqhev.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgmxqjya.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gt2absbssbd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2mthclbeo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2tlbjwvhk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2kjjpskdn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2xuuzadcq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mteclact.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2tzybgsin.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdpwcdoi.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gt2ccforbqu.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2xnsvmgwd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2bztdfaxr.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2tyalbcwk.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2gtqkalmm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gt2fmkwjfoe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlynmxdj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2ypmonaoz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkkgxka.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gt2qmjndjrt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfcudloe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gt2fkmbyuon.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2pxqsqfla.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2bfgnohzf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2lzzavglo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2pzwaihuf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2xmcvsqaq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2jldxupdp.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpavazdi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvcryhto.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gt2cerpyojw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2ihcfclly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2iqenzhtu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2xrrwepkw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2hoggegcf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2neyndzld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cybdybxq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2xrqkfeeq.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2mqwmhqbz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efdkdpif.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2gfhzszaa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2agrfrhyw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gt2qsjizppv.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgelulze.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2lambodei.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2dqnwnedf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ryyqokzs.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gt2rnnzhark.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qtzdqqyg.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gt2rljuoenq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gt2narjwhgk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2chzkymyk.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2gbigllbx.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2tayjbviw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gt2irlebqub.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxycwqnz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qypqpnin.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2ycawxvfo.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2ghrenuek.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntnmxmwy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gt2hkwcfyrn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oocpgmzm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2rqtbfovv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2moaevisf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2rhbwcsrn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2fywcbbnf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2frtalenc.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2bqtoxyou.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gt2uptslnhy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2bapxylex.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2tgxymnav.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2mxcdnfev.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2ustsamio.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2detekzsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gt2yudpbpqw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2okkxkwvl.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2hqbhlhnp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gt2isejmieh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2zoxllsds.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aoyvygao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfwdxvzp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2ezticguz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gt2togpeohf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2utasuqey.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2kmazjgig.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gt2amqoyvdn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2tvipkhlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gt2rbelqjeq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2jfxfldgd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2vstkdjhd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2rdarbnjx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2lqcuanfj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gt2ohmetxjo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2gyizosbp.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqdehjhu.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2pdrnbxti.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gt2bdzmesuh.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2tonzdeww.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2oqwkrcqn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2gahaqphc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gt2uwuaszua.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gt2stbfzxkm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gt2orqqmxld.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2bkylwvba.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2qgaosiea.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2acmtablq.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2ytwonqlt.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqzreoqq.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gt2jbhtdvrf.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2etnmozgn.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2jqwpldgz.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzpaniqb.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2devfftcs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2ddsqyakm.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2oghyepjk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkunopfg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2jeqqxgtk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2jgntiuws.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2doftckwq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2dlxwxafs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2zcnqdriq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2reifycmn.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gt2opfkaphk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2epclxpjp.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kgikmfqg.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2vxphujix.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gt2aoyazfvb.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2llpvhwxb.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2mbgxclwa.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2ovnxzgcd.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2ltuwvksk.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gt2ctmmohtr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2oggtznqz.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2ysopvkwv.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2dqvipctj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2adhkksku.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2cvihoqbj.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2ohxniuul.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2fwtvgube.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2pvqmkpzi.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gt2jsyurjmc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2jbsgualx.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gt2mjwvmpof.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsfqpsbp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2tuslgyvv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2xrctjjij.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2mmtlbecf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxipndju.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gt2ypnewniy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gt2gxserswt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gt2grvtmdxn.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2nrkmqlbd.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gt2ywovnfio.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2juaztiwh.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2yfnxdyxz.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfnppesx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2esautqvm.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2uebutfds.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gt2lhumkxnm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddfhneaw.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gt2ohuanfus.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2dwskoemq.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2vfhmzukc.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixinagwf.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2revytfbj.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rthgcgqm.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqkrhdfs.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2eiavcplu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2qzjywfbw.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2oogsbgoo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gt2bmzyvvzt.html


<!-- 参考信息 -->