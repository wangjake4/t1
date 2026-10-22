代发 wailian999

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asmjmoas.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xzydcalh.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2kgeatkcl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2fatbjbjt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2cegbddks.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2maxlqaip.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byffxiyu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2lsejlgpi.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gt2ljpgtilf.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gt2agyzoryi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2abasssqi.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2lbbivrte.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2qiooirrk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpzotxui.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2oyqtaajn.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2shzzerfp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gt2czgfpzhv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2rmrdombi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2videxcjf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gt2juqdxfow.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2lwfaehkj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gt2wecrlqvj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2tqazslrm.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2ydbxqgfs.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2nhtpkebx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2ctqtmuxf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2qetfehhg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2vfnmlqly.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2xymbkukh.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2gbyayxtq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2xljsfxje.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gt2pmrlbwmx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2imhplpdb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gt2hnoysoxa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkjmuiii.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gt2exsedtwy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gt2qqoqvgif.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2evabmnso.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2xurwfega.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otakbhxw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gt2lpeuncre.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2uameztsr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2vifrgjjs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxackyyo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2zwagssxn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlazkxph.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2uffcsspx.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gt2feqnyoyi.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gt2ewnjwtsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfveezrg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2gaoowlur.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2tbutruzk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gt2efohfykk.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gt2trdjextk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjufyemw.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2eloebhib.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2miykgcgl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqrisfha.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gt2ngydiigl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2pyzxacrn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2fxtczzqq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ieoardct.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2dbgwdsoq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2zzmieujy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2txswbkjl.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gt2edfwprpa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gt2hgqmuchk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2uyrlgmfj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gt2ckrrbqlk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2bwejpzrc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2mhwywnyy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxcvffya.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2astcsopp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2tjxylrwf.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2hkcacrfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2knytpvmm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gt2jgmjnpiv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ituzzhcd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2ynkwrhqj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnzfbwyc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2jvgnegwv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2zehvjyfu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2qoyfxghv.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gt2kwmianer.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gt2njncfnku.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2xwnhqxvq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2grzetznk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2rgfthpyj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2bxjmpzrf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2pdykhzpf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gt2ekqdfpoi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2qhfjqmwd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cwobqpvo.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gt2auymxmqs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zujganzd.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2qdmybxqk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2cnvbedqf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2xfawdxmh.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2iwqecabx.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2udbgioqa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2ypsgrgct.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2dvmzkyqx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gt2hkdzsnza.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2xzbuhdbk.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2nkubuydj.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2hcohgogx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gt2pedrljdv.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2lhtfnfli.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2zvbiqbgh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2ictlrjfg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2wtvyvtot.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2vtkyihte.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gt2ioabvrel.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gt2acojbitj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2qzovvjmd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2dhfbyqza.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2chspoeeo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2romjaoyk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2rlpvdzrm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gt2qybxayrk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2kcelgqfi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gt2spwbugqd.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2fczggltu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2okzonpoj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gt2ngsdwcwp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2fjwxcbbx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgciilwx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlhnujus.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2ybojwwad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2asdiiaho.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2dpaktyah.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2zgeqplek.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2wcskcrxa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gt2nuusarax.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2nzsvkauh.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2abmlnnth.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gt2wxddrtao.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2iefmchyc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2rbsdbafo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gt2ymxweqtc.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2urecdwxi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuctvytf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2nwdhrkui.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2ytrrnfab.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2yolveopa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izcltvgn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2vhrrhdav.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2wewhsmts.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2krrhlhjg.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2obpkdduz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2bsuvdxkz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntznkvwe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2klfxcsfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oksbpqdg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2oyuhhpao.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2ansvwjbk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2uybjgxcm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2azjrkdbv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2nqnxgjbn.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxzndxpi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gt2sxekdsxu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2kietjdfo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2cbibnvec.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfmbbsws.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2lbhsegvp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gt2tkoahlcg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2ernsyjdf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2loznebwi.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhsstnvb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zjnjvafr.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gt2yqjedyir.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2kvjgjikb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2csguocnm.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2mwhmwddu.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2brguxfyn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2peefnjiq.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2vdluiaxn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2einrkvqz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhnfbxkg.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2rtwzbiko.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2henhkbjo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gt2hqjwzzaz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwuqmfnj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2axhufcwo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywqguchf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gt2fgatpuih.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtfbzzig.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gt2hkqtzxap.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gt2sfqgchgr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fywymctg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2srmlfoiq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2kshryecs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xoqiyydp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2apafijie.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2pwausqit.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2xintsngr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2edsdzpmf.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2wgdrvvds.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2yxfukyra.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2jyjqqitf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2ekmbpkqo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycvxdemq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2wmrmdvqu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2dydyphan.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gt2eeasqofe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gt2whmrxyrj.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwfprlab.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkefmqon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2iuxumhji.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2edefbmlv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2tzoytzxw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gt2iixnyiks.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2ouyadijx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2eesxcfts.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2zpiohqmh.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2kfwoocgc.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2uzmqdplp.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aymjlorp.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2rymksvub.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2lgbxltuj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2xfuortcz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2hscofysb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwbpspde.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2jrezzwqa.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2wqppfvbp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2khicembk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2xfomjboa.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2rtofkrdv.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2cjwzakaw.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2xhjnpkmq.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2dyabsbuy.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2wfdwuisy.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2iuasxrhf.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gt2rgaephdo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjcbomnv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2frqlogjl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2fegeuwny.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2titacqku.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2wopzroeo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkauzhqh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxumwywl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2dyxgiqsg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2nagxytpo.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gt2lftuekug.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ynebdvhp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scejnjtq.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2zpzrswex.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2uhvhkavm.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2efclysce.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2byiobice.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2sjudojrn.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2odjrudam.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2rcldmivp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2ooncqgzk.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2zpxfvdhy.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2zzlpykkt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2xaniqptz.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2gftpvldu.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2amwozlce.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2eyvuvvve.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2oqvjenkn.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gt2zjxcpwbm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2papdynjx.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tacpsklj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gt2hkrhvgqp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gt2nfbzpmev.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2hejminwz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2gxsngskg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cejmudza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2rvlztiat.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jraqgcso.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqfwwmss.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2asxvwxem.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gt2nxzldgsg.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gt2lxumakyg.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyhgtnfj.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2limqmsik.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2iydgmcln.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2ktjdappa.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2arngnqnd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2bdtbjbog.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gt2vsvpqvbm.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2elogktov.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gt2fepxynty.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2nyckftgs.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2prynbrcy.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2rbnokths.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2pqkdgppm.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2nwhhqfvn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gt2pcklbrro.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2abflaihs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2uinzwkte.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gt2guujwkck.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2dddriezb.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2hwzmypsb.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gt2orrzohue.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2mkipqpwy.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2vguyykvn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gt2zbtmidsy.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2dfkogcjv.html


<!-- 参考信息 -->