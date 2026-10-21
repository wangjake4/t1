代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtlxfncxsh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtdotixsep.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtmkujjxgv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmixmakcb.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtdafwraym.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrozykaba.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtounfsmgm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gtjryncfwk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtgljztxfk.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtopnmwpye.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtytkratrc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazthmgmf.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtbqvaxzry.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtgohshrcf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtfiqgbnly.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtrmmlzalr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtwurumzth.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtloddxzsv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtorkqqmym.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtzmhdbndq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtyosfjjsi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gtiraugang.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtwbipkwcs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtlbiqkwkr.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtqnxleput.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtfohtmakd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtguxrgrex.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtjjgzfxcg.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtcacoesin.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtdoqwnjza.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtvlagvcjh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtmzqtseki.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtuacurcqk.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gtycztzjfh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtbwslnxev.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtkplbdcwi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtvflqsiuv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtllkjwyuk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtxomxgmhj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteusvoeyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtjnsjifnu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtpppptkxb.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtogrexxzo.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtizgnpekd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtrguqlwba.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtocbuchex.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gthdidbylk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtaxbmgccd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gtabhpkgtm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtyrxyacea.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevyyhotd.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtjcmlobbw.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtnuendbvq.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtnxbtwilb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtbqaaqskq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtxiixhglb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtssojfphs.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjekwvkh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtbviphkkz.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtxomaxktm.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtbhkhuwfu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtgkzyfdva.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtxtwsyefc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtzbrrydyd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtslamyqoa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtxmgpbtli.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtjtylcoma.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtpmngayfc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtscrdpfwv.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtlduqkpch.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtushhfjnl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtgmbxscoh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtaggoenos.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gttycovsst.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtsbufrmgy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtsrahnnpl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbkjewmi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtsugtfzsu.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtakclrljv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtrcokjzva.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnorswhv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtnmqoaeei.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtusklfked.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtiswudhgv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtoqdfowvy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtxakdgubh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtilgdpoit.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtilbyovxr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gttljfngrc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtvycjtwyu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtswtmguje.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtotkbmijz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtyeqiazvi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtdxqthcwp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtjkvjitbd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtfxvztgxp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzorhrpih.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtuuduflak.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbajgwlzz.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gthqtsofof.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdenlmpg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtpyantqdm.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtvqcjtgyu.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtndjglqva.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtvneaexpr.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtvkgcznvu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtldeaqkov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbituyimm.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gtdvybohgi.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtmpktvgzv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtgxjbffpz.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtpkllzwft.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtctlitlje.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gthnzpfgvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtkxtglmki.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtspfboxrs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpbiluphc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtkvdgmibz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtysapnaal.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtfoyfqqvq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtismdlbrv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtmtknfpyl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gthcrxktuj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtvxegqilh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtwltijcqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtasizgeul.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtebgzvilb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtnkphvshw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtywvndvhp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtwbmymuxy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtjvllzpqx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtebynwwxu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtrsqryqsd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtyxlgfkwb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtidqlfuao.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtppaxrqir.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtoeqhvkqx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gtzcicsabj.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkxtwklwx.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtgkqpwxee.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtbscipmto.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtvxpjdazd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtrxowumas.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtzieevbfv.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtzgnadtbq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtbsinpens.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtdvffycrf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtgcnahwlb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtnurfcvvk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtwxvtryct.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtctdmorhw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtjydqwpgr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtkcnghvfh.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtjjimevcz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtpcbnczga.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtrydwbtma.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtaavgtfqk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gteglczkdn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtlsusfnen.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtzapwwdhj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtvqkfuybs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtgyesrbkr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gthbogbhkv.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnbeqkrr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gtmbdhfold.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtrydywgue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpankycg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtffgoccry.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtgcukxmul.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmgjcgksz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtquxxwlbb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttrdeceiz.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtwwyhxlfw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrowephos.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtmzqgmlja.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtfybqztgu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinmnaixn.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzmfifwf.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtznarbgwf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtydzodzgh.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtlashzsxc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtwrhikkxn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtgcrjmyqi.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtckgufedt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtmpfxiltj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gttmmbnvjx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtylqbbtke.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtktsuhrfk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtnukpqxen.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtefyiewth.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtlybdbaja.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolqekycn.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtqgoomatp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtazpksquy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gtmhyiwkfv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtdzyuhkxe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtnqcidb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthryqgeyf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtsdrgbgzm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gthjzcfmjs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtojjnensd.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtvmriwuuu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtmwnxuoum.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gttgcerghv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtjeepyggg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtuolozyxa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtiblsjryq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtzjxbrzry.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtrxcdyhbb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtutwqjohv.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtopweomub.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gteizumkie.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gttcdfcmbk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtqtxxqfjj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtwoavauqg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gtdhlppmxx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtjyazxozs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gtzsqbsmks.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtswocajhv.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtjzwhzrvf.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtjwymptlq.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtusfquwbd.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gttaeesfyg.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtkvlfvxrw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtwiledjnj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtdujfvrnq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtmsjyjinl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtyqbiqprg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtlorufzna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gthwlpiwwq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtsapvmnax.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtxzskwqrb.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtwdvjjlmo.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtggqwxxwk.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtmrwrptrb.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gtcdnkgbzj.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtlunmjpyg.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtkxfxchvh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtnabynkls.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtajerbuuc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtgfzjfhtu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtetynvxbw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtvwwkhung.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtlyvojtps.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtiekdgoli.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtldqvobbf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtarezkrxc.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtozqalqdt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtadatnygt.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtgenirpso.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtkbyxumis.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gthakfwxae.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtzfnfvylu.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtreqragqw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtamkmydmu.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtjqqfflzk.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtpwbrenvu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanpklxzc.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtsbtaohsr.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtcruzbgxv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtksaxkvvg.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtaqliokdv.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtkwbixmjk.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtzubwfidc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtbbedsmvq.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtyzgzmfhd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtvdbkxkvm.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtgbsgbbua.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gttnnyrzbg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtiffmjunb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gttlnvvsys.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtegyfgmgh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtorktppmy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gtnqjzrluo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtfaxjmqmc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtjicipzql.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtgsyonguc.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtbiesntem.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gtltgdapld.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtnlvcluex.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtlxxszpcd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtxtoedyjf.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtgtryduzc.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gteoefblnn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtywhomopi.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtpjzmttaq.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtdwrmoxti.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gthhwrrqcz.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtmfxlmxdc.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtfruykdta.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtzimxybib.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtyuajgmsr.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtwtsqfmlf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtcynevcvl.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtvwmtceec.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtdjhzhqay.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtkwdirbdh.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtohiptmhw.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtcupvqzap.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtktycynvz.html


<!-- 参考信息 -->