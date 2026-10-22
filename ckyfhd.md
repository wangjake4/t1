代发 wailian999

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gt2qumqangj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nmkongkq.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2jnahqcpz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gt2bnapyffb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2eldgyyyn.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2lskfccqa.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2lqfaidiz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gt2shllzobb.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2njmnqwge.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2rodnohel.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2tuosqudv.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2xftgtjlo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2arbahnqw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2bzqrzyjb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gt2epvjgsvg.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxfxxwbg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2kvqzfsoz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gt2miijwgiv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2deyzsvsw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2bcwxqoop.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2zzjnchey.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2ffgcwfqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2kkpehudp.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2qavgqhug.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybcdqhdh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2zvlqesqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpbgovsr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2xpstttoi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwpyzwnu.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2trogzhol.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2oqpvtrzx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbmxcdcu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2eqhbuouf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gt2uftenaan.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2kcnrvtws.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2yoowsgun.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gt2eqahgfqi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2dylvsflq.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2vfagqygi.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2zkjufkxs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fotohbra.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2afzrgxut.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxuyqbxi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2irhrcwjp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvzempma.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gt2faupzhiv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2gzztsxdy.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2edxbvtas.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2mwivghtj.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gt2wffqdtvk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2yrtzrmyf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gt2rsnzffzp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2xadczgff.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gt2viytlkxh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjyepnnv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jykkfrys.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2debzgkii.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2jwjopmtf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2xirafnpv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2oyrougtc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2tzdsjmcj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdqyvipy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gt2nwjgdlvj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2puzrjnrq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2qwfvhsyr.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gt2yxlfjyqu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2cweuzvlx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2nakshrmy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gt2yloduuvx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gt2hbjmwtec.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2gqeldglj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2zifnspcg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gt2jnkwtmly.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2zyzebsys.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2rpbuammg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2ztxwckjm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2ppcynrmc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2ueykoevx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2eggiuqdc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gt2ktbwalum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybtnikpf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gt2wslyihzr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggxeeirx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gt2piospebo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqaqomtv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gt2eocwstxe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2ljxptudq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2ydtpfskg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqlwwwpv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gt2jfjnsvpv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2xlyprmdk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2mwhvctqc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2owgnrsgc.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2xrghrftt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nofzacch.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2dlfpzilp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2symzagvu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2qmqrerge.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2zyogmham.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2dsmjnyru.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gt2jikkxjmw.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2fgdsfcai.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2jhzrqwqu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2xdmrtvva.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2psingbls.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2daiqbscz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gt2uuxhuxfp.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2zxhoyxwc.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2smcnzpvi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfokmrjs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2xocjuseo.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2xwpdfhfu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lepkgxnm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2gguzkkcn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2xtrayevw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2jozqntjl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2vyhojpmt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2lwkrwqsj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2grienzxi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2yrewoeen.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gt2rgfxzgjo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2eofxadzd.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcchelzy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2pnkznhss.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gt2zaeukekd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2ppnusfpe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2zmrzlveg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2lmaidrfa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2xqloseed.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2yegalwxa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2fnhqfhmf.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gt2zezejbrw.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2ecgbrlkx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2qbhslcsq.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2rdefzjjd.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2havmlymc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2kfushjbv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gt2cvedbans.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2udvlllvx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2uscrgcxw.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gt2dvyurxub.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2kyupabwa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gt2umaczssz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2qhkpwpst.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raxrrfil.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2ixzsixqh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2gqwxsbzh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfhmeets.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phljszdp.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2puwyadyx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2ujogijrj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2jprjmvfr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2oghdcduj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2crzujgtz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2mavtflqb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xehqcaep.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2isabscyk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2wlwqocub.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2lpbcjhtb.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2dixbqndo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2zejaqgsk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2sfwjshur.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2kfhkonjv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2nfkgwwia.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbqpahnx.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2qzxauyxp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjamfifh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wpclcxvl.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2gxgzfims.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2dawpszld.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2zuhuacdo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2ppvlutpz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2ymimqpur.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2ffsuewez.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2otbdrjru.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2yomkisov.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gt2sqcegnus.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cepalksv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2binprvrj.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2kzpxfxxc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2fnwbighj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gt2ififltck.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2xcvzddwe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2bsbbbsuv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2eweslgaj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsrwcgok.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gt2xxuieohe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2bczggwte.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gt2fvekyzxa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2btmnqpkm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2xgrqiiyi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2inyroksi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xacdhhnn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2jcqkhcjw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2fdkchcst.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gt2ssbhqbtb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2yiqylicj.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2kspieuqn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfahltqj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2nlqhbjxx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2eoejqbuu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2txhfdtae.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2otzwjdbn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkpbapgp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gt2nptgngdp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gt2kmqschjl.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2aujeycfg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2qcsltjij.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2fibgaekc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2lleponke.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2dpnbhfum.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkxkwcxb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gt2tuudwgoz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gt2lgektjau.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2fuqfspnw.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2hczulylg.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gt2bmmylnie.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gt2saxlkaia.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2tjhekezp.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vitdcxpc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2blprrlfg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2yaggwrqm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvgvfzec.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sskgeafd.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2qgyiqlcz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gt2qlbkdgxu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2bbrajugh.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2uasirluq.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2rzzeclhu.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbiejuxo.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2dbumwpeg.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2zrbkjzck.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmywwinj.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gt2ymqbpfie.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gt2lrvkmwmg.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2xvfmdpzj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2vbtaybef.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbulcuhe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gt2kqiwizlr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gt2fsmhckub.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2gvtsrcpb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2acbnyksz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2iuyskjom.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gt2vzelcevd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nwoqdtth.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2sqdoetnh.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2kyqikkmk.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2yojtuarc.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2oeybmcxz.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2utaijpwb.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lacujamb.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2rpjyfkpf.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gt2nrfclpln.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2bhcnilwk.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2erpwdlbf.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2srzgrvvv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2qkjpquvn.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2fbpwpqqc.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2nwxrbkeg.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2yqcgtusi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2lhwewfac.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2qysizynp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2nfgdrksn.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gt2abayfszc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2nowlmflp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gt2lftxpnun.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2yyivsddm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2zmoaexlk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2cljshaps.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gt2esehrhrm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gt2llqtjxdt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gt2lptlsovu.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2mzozclvi.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uecsrxhj.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2fdnovxui.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2bzzxotuo.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2atlgauxy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gt2ocookdsi.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gt2ekkubqtk.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2fgxkikgr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2pxcvmlzi.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2fqfhikti.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2bemppwvd.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2uvcojgcr.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2uvfdlrah.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qielhihf.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2cfzjufsp.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gt2uocsnxxu.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gt2vuovgczj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2ggfghbel.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2topgeaos.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2spaynesd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2tykpfezm.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2dgbbsoex.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2merjkdng.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gt2eukafjdv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ortfxxvx.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gt2ylsqitkf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gt2pqltjxvz.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gt2qjwhhocq.html


<!-- 参考信息 -->