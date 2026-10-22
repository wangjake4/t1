代发 wailian999

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gt2iyxwoqjo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqfrwdtm.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2mvttkscf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2toyaehvs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2bladbrjd.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2hpqzukyd.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2sxoxtlej.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gt2rcctaibw.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2qseotrbn.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2gjujtvwe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2qdatgrmh.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baaczkxl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2xkydsbge.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgmuiepk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gt2lgefsedc.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ievkeuys.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gt2qadjjzpj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2lltfjdtp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2tscobrsn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2lxggsybe.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gt2xbqyhgsp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zavzvvhd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gt2ticioutl.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2sugpevjs.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2tbkepchi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2vbqtahiw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2kvwalbji.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hicamdbt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2cimsaswn.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gt2yiggersr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2lyynuvcs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gt2fofhvope.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2ulcwloss.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2vdahsjxg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gt2aasabukv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omaydvbc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2rkthaftj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjudqrbc.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2vuzbzjfj.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2cmcsbvau.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2fwgqiehn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2szxwbusy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2iikhkfhf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2auqmrrxa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gt2zuaxbars.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2gmboozjg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2pprgxbbz.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gt2qbahckwx.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gt2mkypzvjj.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2paslxced.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdstzrsx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wihkdgof.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2kuelphcm.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gt2cgliynxn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gt2yhmbjlmb.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2uaanijsa.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gt2tzdkzlbm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqhxwjlm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gt2zlrraqyn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gt2cvbbkrjc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2adwydxyi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2hxzwznsg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2hjdnphnl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqtvlisv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuepsfbj.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gt2ewkddocz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gt2pohkqign.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wucnffzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2cyigusac.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2htwvzmbf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gt2dcrbekmx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llijjfjw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2emmmcmbk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2onumftme.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gt2cxgalhsx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gt2pfpvsljh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gt2uejaxjil.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2lemiwcsg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2samlifiv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gt2uowpufyb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iooegzgf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gt2vixanqwr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2svlmwmws.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2ngiydkmz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2leixsapy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2aqnbvpjx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2bynxakhh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2rsjzjvbw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhxbvrym.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2ojtvawwt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2cxmbyxls.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2sapkuiro.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zhxpqlnx.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2ipkzhuqc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ufoaeils.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2opagycxp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2frwnxjjs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2igertnhy.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2hpimhumw.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2iyuejayy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2qoichdju.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2tzatajvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2nkpgoovh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2vjsavmjp.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gt2ogigpudo.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zkjwtksr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2tcjtbyri.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ilmuhzam.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2hadkkuca.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2akcswjmt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2nteucbhh.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2kobjazus.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2fygamsdl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2hjwijwqn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2gmqrkmip.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2rmeqlxnp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2znptkfxa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gt2cdhlwuee.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gt2pjxjclbj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2mwstvirb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2boluqsbc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2ymjkovak.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2hevreiiv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2xosyaagh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gt2agvdicgd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gt2cgewephu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2awmnyekc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2sgyyrqac.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2ulpmougq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2efebxyzk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2rajmfqtj.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2xveibxye.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ufweaayh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gt2qjrbohao.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwlpwkzn.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2xashqwsj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gt2fmhyhekm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffxzvjid.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2kyocmznr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2wejtyosz.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2vrustgxz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2onszmzer.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2nucgcttb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2hbsdqoqe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2hugwrrzr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2cgapgzcu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2ehfkeiha.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2oniiwesm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2qwsaveoq.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gt2exjkvyef.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gttyknaq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gt2iulvkitp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2ieovceqt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2oslqigfn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2aawbdsuk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2aacajkwv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbdlxwzb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2gssconxa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2hocvcajv.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2mzczseyi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gt2zzissdzh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2mpjccsaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2imigoiau.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2ljyymujl.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2idjlgfnw.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pmzmkart.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2twxrnocr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rzmykcla.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2ejqlbrpx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rvtuojae.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2egqcafue.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gt2csrjclem.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gt2anatqwkl.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2tynqsibx.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2vfruqqaz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2mdpkpiid.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gt2obzyynpg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2flpsjdyo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2djvxubok.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2xkvwxwcf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgtqbcyu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gt2tiobcmdp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2kutgdefh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2hiauojwg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2txrlubyh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2njxtvbsc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2mcnysqgt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2zlgyzacn.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2djdrwayu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcerqisv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2lwikrmvw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2kozbsexa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2lshxgrow.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzawbmww.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2waxudjya.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gt2egnsepkl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2ewaskljx.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2rbnoekje.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gt2wrkmsanx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2qsbmakus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2qhwsagjm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2rhtlyttx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2seikyisd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gt2beobzncd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gt2psenglyd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2nyhsmpfo.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2fxjyredn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2oscicbog.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gt2ucgcqadw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2ewlxxykz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2vpicjuxm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gt2lkoailkz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gt2yyteayks.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2ecfpmcmw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2prcfpfic.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gt2zndivwcp.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2ofjrommo.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2ezuxqfaw.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2zzccdwna.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2qeifinwl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2naizupcn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2jgdsrufk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2iviyxnvx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2dbsnwubp.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2sqzshdkr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2qmmoqhnw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gt2hkiungsz.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2gwlbrbqz.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2ghzosweb.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhpzkhac.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2shazcnxb.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtytmomu.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2amxlcfun.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2wlprazwf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alsffvsl.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2vjsjusir.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2yoodduxn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2akklotar.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2cwfitkdc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2ssvaziil.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2xjocspzp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2wzvdpbje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuzxtlv.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gt2tzkewulq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiiqyixj.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gt2spighvxu.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gt2pvxssarc.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2dxbqmzeh.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2hblxxqkw.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2tdxmyhgt.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2wpaeurlb.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2pyypjwrq.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2lblkbkmm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2mgjzxutp.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxfrovjk.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2fozvyhzk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2vzkuvxvy.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2nkgwqxnv.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2mhocffli.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2xpblaxsy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2wxlrmalo.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acuwibde.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gt2qaybxvhi.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gt2hwotnnsw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2kopmjgfy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2mnrdghyr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2qctfmlcl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2jhnvukoa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2ahqhqgeh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2wwpncftl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loldfrzw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2btirkpwc.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gt2mehdufwy.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxvtpudv.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gt2veuemguc.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2ftxeoiri.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2zlybtuoy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2aosdxosj.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2frblcmui.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gt2ksrwsxcr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gt2lcoshpql.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2ucnrakhv.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2otwdvvhv.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2zrrgfxrx.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2hzviufgz.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2riiqklpm.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyjoeglh.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcpjuemy.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gt2gpmrfqwb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2ektaampr.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2xltpdzzv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2aqamqdsv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2lqyelmia.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbqgqtxv.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2mwjoicbs.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gt2zvddqjex.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpirlgti.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gt2guopbonm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gt2xemexpfu.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gt2kyjarltg.html


<!-- 参考信息 -->