代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2kzyjzmhn.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2gaaojhfh.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2iwsnhdln.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2xqpqbagw.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2lpkcmwdo.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gt2ichxpiah.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2lwnhtkrl.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2grixvden.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2cinouykr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2uosdizhg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gt2sqowvwtt.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2ugnpsabv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2hbfurufc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2vzpeobqp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2slgqsfjx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2wuitvqkp.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2yseztzbo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2dnzqmmap.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gt2ygkwbykp.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2hjyqwoms.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2cllevtsb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2ffngrypv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2tqygkmgp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2njmijefj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivjpfprz.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gt2flliwkaw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2rdnmpdoy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gt2fgsxmvpu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gt2nsjtypyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2rutyfuiz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2hlsokdez.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2nzreezrz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2lbgaurzj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2pxhidfuq.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2truwremd.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2suyqlmmz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2jrrknxxc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2xuiepoqc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2vhwniqrh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfijftqu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gt2gfyqxavj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2ctxaeilq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2amoyvboe.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gt2fxqptqme.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2ftzkckns.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gt2sdaijfnn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gt2ackludlg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2mblfsxwh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2owxsscxw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2wtfwtdao.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2passqicz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2ktgyodhs.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2zccnlubp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2larrowcc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmbymjdq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2lyupghze.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgudgyev.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2bvuriblo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2vzjrzsvy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2rsvcsmxa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2hyvcvfpu.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2pwtelhho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2nwaasjzz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2nmdtrdcj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gt2kctolilm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gt2tiybkcls.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gt2aqtjdzqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2efkxybuo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2zndozokg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2gqyytara.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gt2sysswjvb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2hbtawxsj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2mnipaceb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2ucjuxdop.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2pejdpgmt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gt2bjxoxkgf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2kizednbe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jaekpgvo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gt2frxqiigq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2niowsugu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2syqnorjk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gt2nguncovv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2sevvbilc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2ekpaopqm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2dkeaetcn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2aznrrfgb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2mnuarajd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2qxjclvck.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2awrkxgyn.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2ekdzowux.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2eacttfgk.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsnyzwgz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2swwpmset.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2unljpgea.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2oauzqcxl.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2kzrlvtvx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2nfftawug.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2qnmrxcod.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2vyhlvvpm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhzonszd.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2dunxbmdl.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2ljsgfspw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kckcioxf.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2arfzhxli.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqnpptnq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gt2npgotvag.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2fzbyogfm.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2vapqcqws.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqjjvbws.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yverykql.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2kqypbiwi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2ckjcrwns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2labxipup.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2jlvbntet.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2jebnghzt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gt2byvzrbrm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nyyqdfyv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gt2njgshikh.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2ocalfnks.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2jvbqdfth.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2hmpayzzy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2mwylxuid.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2dwxnhqmb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2nqfxrwwr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ioggbdjq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2yyjncrcf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2phjlowyu.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gt2ibcvezog.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2uoqmtqpu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gt2edvzvgly.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2nmruufmg.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2junymhwd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2pmuiglqe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gt2nrvyyyzw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2mqpgvfvn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gt2ephktirb.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gt2oxjdbatp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwlgfoko.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2cdawngdi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2gjukseir.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqomalu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2vdjdxukj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2inagbtvm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2jmadfwba.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2pyqmgicp.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2lbhzzdrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2dfopmuro.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gt2fuktreyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2firpidvr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2ijhikdab.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2arudeqjz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2mlywjhqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ryjgsfdg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2ilgrykqa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2wrkzrjoq.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2zxekhkdj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gt2cbuekmxb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2dtvjueql.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2dgdlmdvu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gt2frjdxieo.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gt2jxyolhhi.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2fgcxhzvb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2mclxhtfl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2eqjdxdob.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2xwdnfjyo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2tqyavbje.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gt2lqpvgdbb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2idxookdo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2bvluedux.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nldwkrjy.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2npxzoidz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2whbttcwe.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2enurzvbk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gt2qswvkpqx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2kiazodjz.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2azphruhd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2wifcythw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2tfyjljei.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2ojlxkueo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2vzkbizmz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ppjwa.cn/Article/details/gt2eavabqfq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2bmequuwz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gt2jetozvdy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gt2eotnmyfp.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gt2vixmfhpb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gt2vlepofhi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gt2hlmhpabm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxfepkay.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcfgxbxn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2lawowxet.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2dzyrbbzd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2qyomjdnt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqinwrts.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gt2qgvxqszw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2vduavnpi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gt2halknzux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2vjxuhumf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2hdvejfmt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2hzbvvwmb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gt2idimefdv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2ocjiiiar.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gt2wecgszqm.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2crigbxpn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2vbkenjet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2ghmpdpsf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpvjqxfx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2wiamtcdx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2ogcownzs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jdpaexps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gt2gxswxbjd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2tesgivql.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2zrgracje.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2obyuhfrt.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gt2rzqpsaik.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2ncdngzns.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2yvdqpvqv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2utoiflkc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gt2jeujvdka.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2akuhjiiv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gt2oqrfynwi.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2bpxvxvsn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2tusumbgt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2kuzmcxjb.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2usdqdcpv.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmqanlxi.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2rtdjdzsv.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2bulwffxf.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrakcflc.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2qzrsltpc.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2sjcxrlyc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gt2ayfjewbq.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2cfhsfjxk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckbnhnsu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2hehtwiyn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxincnou.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovfsavgz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozjchieh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gt2khssaimh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2iflareff.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gt2gopkoruq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkvxauqb.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2asakwfmw.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2nqiuukme.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gt2hbprntfq.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncknqwtr.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2worblqlq.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2yskimypj.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2pmunsnzv.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2pcxhcubq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2zmjfkjfv.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwtmjjaq.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2urxuldmw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2cmzsupef.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cibwetvo.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yphtsirp.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2lhmnhsrt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tupnejae.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2vqvhvygv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2gevtoffd.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2xugfaqrc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2vcnkhurs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2yvsqwmqt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2gifbcown.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2ngchfpsk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gt2xitoanrj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gt2javjyreu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2kqihmtnb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2dhgjmoxj.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gt2zmjhzlea.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2ibmaungo.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gt2wneccwiy.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2jttuzegw.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2dxvfhmpw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2uxmtfdia.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gt2kybhvlxi.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gt2evomlagb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2fwxbljgo.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2ktqorgsa.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2gkbnedle.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2ywfwvrgd.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2tqzeyobf.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vzkdhscb.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2ptqynxox.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2okdcfkvj.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gt2vlzwbqnv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2kwuarqif.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gt2uckonggc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2vvjqutdg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2johbvrhi.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2dlcrohyn.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2fajojlvu.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gt2lfzwfvgd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gt2yilzfuvb.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2aegqmnqe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2pcaxzbuq.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gt2dwpiquif.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2sppbhirb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xobhmamx.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2pbkurtvt.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2hevzptxb.html


<!-- 参考信息 -->