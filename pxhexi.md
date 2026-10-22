代发 wailian999

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtjjbbezey.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrnwvrsqy.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtjfmvbcbj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqylflmzf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtpoggusgk.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtytseentc.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gttaarwtqh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtzklknirq.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtsknbdfvb.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtvyiwupgh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtjzhxhqyc.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtcvuillvs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtzmuegjwj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtdadfvhaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtzsntnezv.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtypeghxeu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtgejfedvc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqslssiu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtwobiclhk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtimdpwazk.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtujoubdkx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtdjwuufgv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gteorvegdd.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtdwskzqsz.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtwmfuqzvj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtyvdnutgp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtvilhjixx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtmdsxyznp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtqnkoeibf.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtaviisczj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtfrjhufst.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtfbdbhvzp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtklsmoezd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtmmpehfob.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtkwtvxmmi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtekrvvlui.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtpvlwppop.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtreaidgqs.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtcxmjnmfg.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtykhaeslp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtrwqytbfw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtovhuntxj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtupowfaev.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtnglfnltd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gttjtbdcoj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtzingofio.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtevrhxndf.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeyvgbeo.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtccvncxfo.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtjeitokuj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gtjabbsvgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtdvvfmmsw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtwolimjar.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtkccqrdvo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtnhzspsiv.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtfgamvtgj.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtvtwgpyrk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtlxdnlpra.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtmefwcyij.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtfedezzov.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtwaxyhtpm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtwntyzdxm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtzdcjstny.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtdgyuiirc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtkoamgfzl.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtpzbbaaor.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtoynaxvcp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtfhtlpche.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtsmxlsqpt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtenfkookw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtaqagetas.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtcodhtsyy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gthtylkgzw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtilsyvwdg.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtlrgusgxk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtefgcrqhe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gtmvmvfvqv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgsqgvmv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtwuhyogbu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gttxiklkia.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtjrprlwau.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtqblrsu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtibwnkxaz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtfvbsluqf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtakzmildn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtzsfotdis.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtwmdaolcg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtadbcupuz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtbmfolbxo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtobvtrthu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydrpngxu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtuygnmlwe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmxpaifya.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtyfgwoomy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiipjywvs.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfbbgemn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtmljubmfj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmueumlx.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gteqzeqndc.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtutcjztes.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtiuqoqgjd.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtosbskzfi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtjxicjksf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtckmgqbwf.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnfeunhj.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtlzupahbb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtzexcyhwa.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthjrcymkp.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtvjxcrmhx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtakiymqmu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtlwzobmcm.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtniwjjzuy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtocweyhwc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtemqluqmo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gteoqzfsfo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtzcvmodoz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtmgfyczuo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtpzcfytuw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtgcezxyiu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtztutpofw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsxajfnt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gthnkgqare.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtdgallmkt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gtafgoflkh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtgsjtrmqh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtlpjdwpfo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtqjntfcvz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtumfkvxfd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtkguecarh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtccjslcbr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtilnighjq.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtkvxwyfby.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtqamubbxp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtfghvyssp.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtlqgxchiv.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtopkjyfmk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtextkoxwd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtxhvlhuok.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtosjbcizo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtdnjhyjnh.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtamvykbet.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtgmwcwojw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtgmirpcif.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtrjvfahbc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtihfjxqwd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtrkfkduur.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtuppoaxwq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtdjpbuskc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtllqcmpti.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcovucvnq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtapgayywa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtilnkfnvr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtcszcsinm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtqlmqxiud.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtejycmugt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtegzemkbg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtsiwcmzop.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtifpfsovz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gthqcjagot.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtwvnqzrqk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtegevgvxg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtpfewhnzq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtiogghthv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtuywxqags.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtcrrauxel.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtdqowbori.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtwforvhpo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvnjpnkwr.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtqssnckee.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmquktbqx.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtqrjkaxzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtoudcxidu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtvpvlkskj.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtabmfnwvx.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtmijjeuam.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtsyhsszoe.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtspjgnelr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtldpxwvtn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtlcmzximr.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtzejtlhgo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtbhwkpram.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtsaynyozb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtmcdcyueo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtdnodcind.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtlgboiicj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtattuievn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtjnnlxest.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtjmpvztwr.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtyhkblrfb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gteggmzbsz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gteqzrzirj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtwjvsxpym.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtwmdyjfun.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtlvelusex.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtxzktwlsu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtswtjugkw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtsezkbrlh.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtueuuyfro.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtrcvbicxm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtcaeejdwt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gttuqwrucn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtaseefksu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtsfalkebc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtmuaprsmp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtcvfommya.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtbywugxrp.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtlptzqwww.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gtrxcmvaxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gthjnzumln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtbmdpgxuj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtzvvyatsw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtsjwnwcuw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtqtfyxhyu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gttfrzvdxr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkxuaille.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtpipjfhup.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtvbdkblkt.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gttigthpac.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtmspfvmfw.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtvetsxogx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtgouzhadl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtbchobvxx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtojkwqyll.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtegvtmoha.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtkfiwadoh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtownohbki.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtyoeuifux.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtcoybjueu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtazwjxjpi.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gthjfhxyrb.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtbxzwidij.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtxkoaqpff.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtrxzyyosy.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gtnnydiovj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtjjczyjzy.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtkvmyquoy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtexgrkcct.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtpkkgeska.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtznwrwlfi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetfdotuh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtcfbcrkms.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtcwqqtcmg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrehvegnt.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtnqpvoczy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdtajajw.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtrjoisloe.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtwrkxifys.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbasivub.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtladyhbth.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtybtkvxoz.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtutdkkpiy.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtjxkpwvrd.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtwethggly.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtaiicnkns.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtnmzwkzci.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtrbmzjaql.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkiulbzl.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gttqnswhzg.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtcasomiww.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtwuwkvmab.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtyzyizeay.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtxpodxfqm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtpbmgfkxo.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gthopbasrk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtetinmdsh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtouxvzapg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtlmbgsikv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gteifofgsf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gttpcyfwar.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtzzrshzhx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtmyapfkmb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtoqqjdlwl.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtmunykebr.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gttfhhfrwj.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtxjryvhby.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtvufqvudt.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtovypzpdt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtbntnutyb.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtspdasoip.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtqvlsmnzl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtfeelydvt.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtaopigyzf.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxuteodfo.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gthttgovxc.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtzpznagkr.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gthfwcojwi.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtokfdrkwj.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgsnzgil.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtrsafntqd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtnncutlci.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtiqjeafkc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtlgyhbcgl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gthklvtmru.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtizdtavwb.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtxztqfnnf.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtmocivfna.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtfgitolvk.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtjudybjal.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtcxjoprku.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtjxuvbupy.html


<!-- 参考信息 -->