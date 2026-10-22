代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtvamcbltr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtkxvontwx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtbogdrtin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtlcyitlvu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtcyvoixjw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtrdojnnah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtenawljqf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtibfpnedg.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtdidzqoto.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtknocrqbd.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtmbnvlnbh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtbcjtkmmf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtkzfckmcb.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtgpgcxbpa.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtzdywjrjk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtmjdcftft.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtonettjqp.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeqpmday.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtremzmmer.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtiibcszso.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtolzbfolw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtrfjgnenl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtprxshzio.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtxjtvfygg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gthbiafjfn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtuoaufeui.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtdplzhuvf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtfwcctxib.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtbacrxmxa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtipwglzyq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtjchghkqc.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gttuejcjxc.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtibwoozyz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtnppdgsvt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtyufsnaxp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtakwyxrny.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtlsgawoce.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtsopkmkuy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtoxcleqku.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtmpgylgxu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmduhsodp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtkyotchwo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtduxgytls.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtoycmxlzm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtooyoyror.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhbvtlrj.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtnzysabss.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtpachtdet.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtjvnicjzx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtezgueege.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtrmhuzhls.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtjytftgdt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtbsxxvbws.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvtobyez.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtztsvezse.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtzmrrsilj.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtdmarslsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtauqwzhqu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtrsxoabpj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtkdxmthgb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtaahcmwzw.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtnntrltwc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnoaitvn.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtdefhwmrp.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtqslduohz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtvqfdsrgu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gtakceqobb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtqewzommc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtcpprvsqz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtgifcswpx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtrvjznhdk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtmqqpxoam.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtsuukcrbb.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtaszddqui.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtcymuxruw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtdwtcfibn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtzilsgnxb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtdvljeqyr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtqyygkwhv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtpfbjtuae.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtkbxnkddr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtdcqhjszv.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtvxbjkzqf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwixsaomm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtvdbgphza.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtvdhvkqeq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gthcczvoxp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtxelumlwo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtghocfazu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtuvcwbrac.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtcmtjxdgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtkbhmzavx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gttxmqbvzp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtemtcinfr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzncjvxti.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtszuopcnm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsszoszsp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtgghsmsny.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtzlzvcuog.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfdfqmmo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkfsuxxxy.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtdlydoaqz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtidixpqvt.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtfaovlyoe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtwtzodncs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtkqefydpy.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtqadcrzgk.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtpwupyhkx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtkdxoxsti.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtgpvcyqjl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtifjkfnqz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtuinjcvgq.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtusrksrul.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtalkdwedg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtwpjjjrpf.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmvdzoes.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtsmoacbne.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtjtqmffmf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtwwscrtuk.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtehnsocib.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtpvdhvlif.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtguolquje.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtkqpfaypm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtuhecidaq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gteiqasmst.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtorozxdfz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtzherjpgo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gtmnqlnigi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtiwjzpwva.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtlmbpcvds.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtjviaxcmd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtblugvfxp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtdsbtbmqp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtjvtxzqlg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtbngnkrgk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtzkuouodq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtwbeuiwdd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtzhnaopyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtpaiqjrin.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gttyzpwfio.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtfvecekjh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtcyxxxeqn.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtezpntfpu.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gthbhdghbm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsavhpbu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gtqqakrwzu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtkypwpwgr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtjylfspad.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtuiqwmuqt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtjdfnygjz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtdoyfjkss.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtfgspmgtd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtkwknlusj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtxnkibrcb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtieiuftou.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtxiyqfvgy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtunqclbzi.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtdpuawjtm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzocpjloa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdqtymbh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtfrstrzys.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtrtyydbrz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtzcjwufsv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtejcnvqhp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtsvmatmyp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtrlqqfdzi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtohbwuoxz.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtohqetauv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtkuyiltfi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtxiujatev.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtugovujrr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtbskrvrvz.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtbbaevhrn.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlrwycqq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtjjkaydip.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtiqvmmxri.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtyofjqvbk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtiykaxidx.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtihzzutgg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrpdhxlx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtbiwatrsq.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtnggckiqo.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtqywytcnl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprmbwgvf.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtxhtaqgun.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtvtuimsvh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzajctbuk.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtepgfoghl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtuvfvlbdu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtpmoefcpp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtjdtghuub.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtkkbohyfm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gtrelhwfgm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtskbhbulb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtosdidcah.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtmvdzyshq.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtnyophjjx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtlhtktekz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gtvrfxtlnq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtgdfvqwwn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gturgiupcx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtxdmmiqok.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtiqikyqzw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtbpthtzpk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtasbdqijy.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtqixuqxlv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtqmfqqycv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtvjkxnkxg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtejxftoen.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gttrucaxzv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtizajfqfc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfitvrfdd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtnwdtbqow.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtmvbtpirt.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtysuifwvc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtislmrcli.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gttlkmwzax.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtqynwzdni.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtarnbntih.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtszrjjrxm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtcdyssqvz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtnglnikon.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtlziaaqye.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gteuvzjfvc.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtmhjfiuav.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtfsgidilt.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtutljlupl.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gthgcykvxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtqdpbtrtx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtkrdhlgdg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtfhmnxxos.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtznpipojs.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtwbtpkpwz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gthuzqpopa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtjkatdejv.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtwggrkttp.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtqtrknfir.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtggzctwrs.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtkmwmgrqj.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtmzqbmpei.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtofajekwk.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtsvsevpal.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtpfmtbvsx.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtbzfnhpqe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtihxtxcbu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtkbhvcwys.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtxhrntiiq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gthmubfuer.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtumadereh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtorwrpwrq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzuupuukf.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtwqjsulvw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvnrpvyor.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtevxphjwa.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtkoldycmv.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtxashvyoi.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtjegbquvx.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtxuyjsnpm.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtmpbetqjp.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtkfcegxke.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtzymimten.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtngngviwb.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtmfkpxndk.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtscgvieer.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtmupmbkta.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtkskwxuqm.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtkxrvrzqv.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtnagoegqb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtpcjifpfp.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtaemwdzry.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtqqwoddtu.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gttvogcuol.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtkklfdfix.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gthbqarvaf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtedmjrifi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtuqbtheva.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtccrpmmap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtqijvkdid.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtguzqlypz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtqlwgiiab.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtequomsri.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtdwfbbvhq.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtumvwkbiz.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtvpdoxpfv.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtvqusohnt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtohcstrgq.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtzfhyeiel.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtowyxzvnm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtopoelnqb.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtiphjhzae.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtnjjgrnoi.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtrzcuidzp.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrkjcnwwa.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtxelzgrqp.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtgvvvizys.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtcoeylwaq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gttdkechnr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtwawfvdfo.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gtvwzfrdhw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtwhnupahe.html


<!-- 参考信息 -->