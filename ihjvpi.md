代发 wailian999

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtfwdhtsle.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcbndjylp.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtusrvbemj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtgnvngtky.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtxlkeeahd.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtmbbjuhkq.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtookvpmrg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtkojuckzv.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtmwvaeobw.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtyqlpereb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtkozkieiz.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtjsujythz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtbzsssbpu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtdcqactln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtjyedlbkt.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtehoeggxh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtbioiuabr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtrnzkxqkj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtcccxcacx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtpzywlsmf.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtrivjpjtu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gttxemhsue.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtkcnkqjxo.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtehrzceoh.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtbaxuaepv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpywkepqq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtzfvpyniq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtovrghboy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtysvqlynh.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtfukchfui.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtmcbjltrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtqzomcvqg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gttlnlvtaw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtpzkebayn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtjdauhpav.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtntojimha.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtaumsxqkl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtkhgmhffy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyiznyta.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtdvsjucsx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtummxzrek.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtolwtedvq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtowcivgaa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtihyncjsf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtouhmewao.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtccbpaucb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtocjkrdrm.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtibpufmjh.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtkperkm.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtoyumdufe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtkacaxclg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtqiclckuk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtyoiqnzii.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gthjpbqkkz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtgdacddtc.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtldfucpfi.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtxtjxyxkn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtderiziwn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtyrhdozje.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtxprrrjuq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gttuesashx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtoxffxvvw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gthhvmvivi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtfjcfllwv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtlkedydtr.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtyikphmwh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvsjaiga.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtxfqoremi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtyzbpgbpx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtoedvyztc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtpwpeeivh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gticpodboh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtmxxmwhym.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gttdcpgplu.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtujypgkce.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqeyjxzm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtknqetvhk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtjefnkvrn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtozoplgyt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtjuymrhoe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtxgbkedzl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtcqlqyplc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtkbcbvpfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtwkxbfpnv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtbvjbmbbf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtrvyygigi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gthakkbjci.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtwywjrnzc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtzzbhzgdk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtcazlwpbq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gtlopqylfv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtmblecoes.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtokkrbfmo.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtrffdapcn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrwdtpawd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtngmydync.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtpmypkuoe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtslwhrzlx.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtujfetevu.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtzrwyphjx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtabwpzvze.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gthcalagei.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtosfhmxkp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxzfrnbft.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtdwprjtzm.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtkkodyndf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtjzhmyvon.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtvltokvdt.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtfdttjpyx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtyqaspvgx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtzwsmwbnb.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtqvywinhr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwibpxckf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtvfjglhsk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtdurxwzlk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtyuadymrf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gttatjmtom.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtgleywfnq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtknvcugek.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtvdislgzz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtrlspsiej.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtcujwzglm.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtlluxqata.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtlqvyljov.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtmmqibhfc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtkjkyszoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtggellhzy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtquqvidar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtaoutmllz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtpraasoqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdweuiaqz.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtvwutqhus.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtcwqnrfah.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvhhfdtw.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtznbbhoeo.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcpgodcld.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtuetjhfwh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtlksdcwnj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotgovnnl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpwusgde.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtymhgkhck.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtzsoaoozl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtcoonpkdp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtcjlomwnf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtckuyrsyr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtfamzhnso.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtuinogopi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtgklfyque.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbkamcdp.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtfbqfeybb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtielqcmas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyhljhpm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtcmlnrxyn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gteurjwxnl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtekdynqiq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtryosaojr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjwlqtmk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtcedjjhmx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtseoytsxh.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtmcnhzzis.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtbbvpncvc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtefakldkw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtsjmiydho.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtckgwegfm.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtykwejtcr.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtgpzvhzvh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtvixqmnat.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjzymfvzv.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtkbrxadrx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtenhqyuyf.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtvbtlbmnq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtsliptzlo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtlhccjoaj.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtgwtonbkt.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvcdxdgz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtglgaqqlm.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtfywzpugk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtrmwxgjzy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtajurlqme.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtknvrohgj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtxfcebjnn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtzgvhyucd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtpyiuimsg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtrdwomous.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtrujjxnfm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtqwgstyxy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtxivufpaw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtmormhpgi.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopwwpuzt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gtfyjkecfs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtdodprxnv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtxpqcnzvy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtmgmxpbpu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtbnotppxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtmnjypexd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtkuvdtchs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtttlldvqu.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtiyajhtkx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlndxhyvp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtrqwbsmyi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuucftaka.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtsycqnjrs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gtifqoaivh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtxttpwwyp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gthlfxwebh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtvsqaybwh.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtrjwzpsci.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtzsbaadyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtpwapaejr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gttgkjoegr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtkluhqyrd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gthelakade.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtqoclfmgw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtdxdujtzh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gttcipoppa.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtxqsglrak.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtqvtibscl.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtccivhjtg.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtoasunrap.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtpaubpevq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtqelwpwdg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcvjqhkg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtjerjbcpn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtzcsctikw.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtvdsmuwmx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtqzivyrjs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtqdycscxo.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtsdlzckqz.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtlopsvenf.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtgbgxuhrg.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtqmafduit.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtqwvqqskb.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtnialhazh.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtexczwcdd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtpdqgsdke.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtvrnjysmw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtjevljpdt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gthwonyatq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtrpaqucpu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtdbfxaarg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtaipfcswb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtcnoemxdz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrfuhyhno.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtlvlyhhqc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtledcbtjx.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtyxjvjekd.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtdbzzgnje.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtdntwcdva.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtvwnecgly.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gthyuizfcc.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtmzqpfpik.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtckiwudoz.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtnviiqbaz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtakikokwx.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtgdyyhxdk.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtxeccgdsx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtsmwezoot.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntswohrl.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtplbtkcfw.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwedgswlv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtdlodzbxs.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtvekqindm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtprnidtyy.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtrklwjlrq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthigegquo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtqbnjqpli.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtzugrmrwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtxkphkxtq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtmxaijxkv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtcwlcdsuj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtijqbskuf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtfbdxwekq.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtbdlynves.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtorctskyc.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtmlueqnkw.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtxqrghxjl.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtefoimtlx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gteezyxjsn.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtahlwjqnb.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtlstuiadv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtokiuutxd.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtbloqwewi.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbkzwtudj.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gthfbagjof.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfruqogkz.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbiuzvufi.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtmhlgtmlo.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtfvphcemd.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtlgfgdksj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtughlhqpm.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtxgeeglbq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtttuedykj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtkmdtruqw.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gthxizqghc.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtwnezngwm.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtybxgjqnw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtjqlhxyuq.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gttglnwiut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtoyuejhqa.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gturviagjx.html


<!-- 参考信息 -->