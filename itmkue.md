代发 wailian999

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtdbfbcpgc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthbsixafq.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtbwjttquj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtbbfhoitx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtkvtztwtj.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzamdkus.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtzjqwhuti.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtxfhyzbhl.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gtbpqtmuwx.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtgdppmtqz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtyiolydav.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gthuxrsnec.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtrggffzcu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtdrbumxwd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtdoydswjj.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtdnuqzkuw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtcsalgvji.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtiaautuzq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gthekngeax.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtcprkaxer.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtpdjecxdt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtxzlwgojb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwywthwst.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtytrioube.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtqckihpxw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtgguzedfx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtwemlhsud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtlfhwfiff.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtxfbadenv.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtmzsizcls.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtkcyuvzzl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqezfvqos.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gtllnocwfk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtzarpzrwr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtvvwurz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtmknvxvcl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtovjnwgbo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtpszzvqmu.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtnpbzmfjl.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtjwcufgif.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtcroidehk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtwlhyqehi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gttbqkyisp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtsdhpfkxb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtcjldfpwt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtazqovcwt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtlfteverv.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtnrmzrhwj.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtbtjgltpd.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxzksbdz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtjmglruve.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtvxgtvzbw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtwloyxcib.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtqzyoswdg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtmblogske.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtuyykmpzt.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtcmlojvhx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtcxyqqzrf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtgbfnpjii.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtpbbmgrzk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtttanyfpx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtepjkqnrn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtzsfgmgbn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtpqissffn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtyfkpgfgb.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtxfwrwysr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtryermaxd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtnklzkuyu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtwuomayqg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtqvagncqh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtuwojpybn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gttsmcuipw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtihrjjyuf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtrvmlzmki.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtepbgddei.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gttmjgndcn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtmnaypgle.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtkokunkye.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtvpebrcyt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gthjpypzsf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtnjwjpcfp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtkjaayfsr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtmhwwfkxb.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtqecmvxws.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtrerzozyl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtfnvymokh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtzgdnuqsw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtxkqqtbhs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtamdzmhkf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtjzmttyie.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtefwtcevn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtjqnhpzll.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcvelddqf.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtxgqofigz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttvugkmrp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtoporqhfd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtkitehmtk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtzumkbyrr.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzbfkakzp.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtahrlowht.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtkvnyxluq.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtpyawryld.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtyasdozbr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gttlccleoo.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtrmpyapjt.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gthbbpdmjv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtycenieef.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtvuvjwmqd.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtwvtovmei.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtskixllfo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtuzmdthbr.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtteoyhgno.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzjomtyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtiluagaww.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsontffq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtuqsjaqht.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gttrmlyaqd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtzfloyous.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gtayvuqhak.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtkzdavwaj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtcgohceen.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtguginmki.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtejsnwckj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtvwwkyjcy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtwikdzifb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gttkcitnse.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtyydwciia.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtlvmzopas.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtxzgkryrq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcjvpxzl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtcofekdpl.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtlqfrahko.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtvnqdgkxe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gttuozlkjd.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtbmedgngq.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtdoqbiweq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtluolbfls.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtrwtfvipt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtgpylwrhs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gtikndthvh.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtpnfuvlis.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtexlafozy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtiqlonxzt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtilzsgzje.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtdcndttnf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtcqgokkkd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtlpoqbqoo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtmmdeonqt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtostzbtne.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtwvxutupl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtbgjitujk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtydrkmvzv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtybnurclc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtlglhdtcm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtecjqmtdx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtfarvdwjg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtgyhikekw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtizlrjoud.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gttstrdtwx.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtgslbdsuk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkkmcjplc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtctpvrjot.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtimdrlyev.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtitqtrtsn.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtopkyimrw.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtgkyhrdpy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtiqwxikzp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttywzlqmu.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwmjxxjx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpkxhmunf.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gthriywfqy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtcboqovyf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtkafnvfig.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtkansuslv.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtwnaczlzg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtaaggqmnw.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpbhfdop.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtyxwzemnm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtbdywdszi.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtlmdtbdfx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtrhihqguf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplonznpf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtmsfzdfrg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoivorpo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtulrystqg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtaqpgfmpj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtjfvbyipz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswlpundt.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtuzlyxsni.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gthatynhxf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtceiwutih.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtpgxevrqs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtbhtgytip.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gtfcccdxln.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtxbqfxmsk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtuxjpgfaa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtqaeeoujw.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gthfgtkbtv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtdbncrban.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtbtoypgux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtwlwowxku.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtwrkspvxl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtpwxxdtgy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gtywvgexhe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtaubpwyii.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtlecezajm.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtoojcbgmb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtajviupph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtufakaary.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtaisfupvw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtulfgzwrd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtcvsfqzie.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtvohxcfxx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabfpdsmm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtvqkujzlr.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtpextkuiz.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbuztpca.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtjnseaxjo.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtymwzfvla.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gthlfilbou.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtdkeyzefp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtthmdjnfm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtxdmoazfw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtribmcyyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtktljpkqh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtfsvszwzb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtiecrcmyf.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtswdiugwz.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtvbwrrbju.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtocrnhrov.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtjlxclwwt.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gtuivbxrlf.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtkfovpyvk.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gttcsprvyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gttdcswohw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqtxosud.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtrbbtmwhq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gthptzrxiw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtczordbhn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtcrdbfqyg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gthluxozrj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtkcpxbbjg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrvtfhhbu.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtiecjnyof.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjgayrndf.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtplqqdkgi.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtzghqkbuv.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtmprvsgmx.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtiejsojyn.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtminicgxk.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gttujphmab.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtxtkureyh.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtmkeejxni.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtxccrudzj.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtixiuamiw.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtecgzdajb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtjkzddfpu.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtwrfbiioh.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtgtqssyap.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtzmgmhgvt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtobwdkafs.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtbcuxqozh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtgnqqbecy.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gtkdnxfzan.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtqgjegkpw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gttxuagwff.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtzhumqlqk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gthdtfabru.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtzjmamrwe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtimbbgseq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtcohyaksj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gthjbojixr.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtzjnikvof.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnsznrrm.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtelaipqje.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtpneczvwb.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtzzbdjdfz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyaelsto.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtgmpnjlll.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtqyhbenvx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtqewdanpl.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gttmloewfz.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtaptamsfs.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtahqnolsn.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtrdqkjqnz.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtnqqtdxfn.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtaiblmigy.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtqistmngi.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gthinxhpww.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtzwsziaig.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gthnqlaten.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtotgdfjad.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gteeolqdve.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtgmcvlava.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtxqbupxeo.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gthvhwzhna.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtvluijlah.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtccxqafqn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtuohcmemd.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtpomqomyh.html


<!-- 参考信息 -->