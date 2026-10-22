代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gt2dvvbrtaj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqugdlei.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2uhtaaaoq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2achgzaaw.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2znjuqgvy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fyehdvcu.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gt2htxkkkkr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2nalnjnse.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2tqlzsepy.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2mvbsmyag.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2zyaaalxh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwwyavzu.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2jnjvoknl.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2wfwxqqtt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gt2cofmhlvx.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2hsmylpek.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guwslfng.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2ajxibjgz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gt2bnzgxhoe.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2qrwdyffa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vukgujql.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2zbxwfsgu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2fdrohgha.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2oogoufrj.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2tctjsano.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2qnlixxvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2txhkcaoj.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2hchuoiao.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2jnwgspta.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2pdtiqdwb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2gdmyshik.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2vopvdzne.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2ejkigpdr.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2alkkuknm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2fwtxenaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gt2fqoqreuu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2ixoqknzu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2pamwamhm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbkgcwta.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2hraisspu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyuqwjqa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2ciwxwyus.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2affevboa.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jndkkmph.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2wmqyjkbk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2kubgdutw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2ethwtqvn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2kfpqpjde.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gt2ovlvvmme.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gt2kjzunjgr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgnfqfup.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2hiiwibab.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2duxdkjgz.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gt2qjxjezyi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gt2mevtgtip.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdtocxla.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2qubiojtk.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dshzmvge.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2orifumbn.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2mwlmgvrs.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gt2mvwcyojh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2lpomakdy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ampghdad.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2sgifgisu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2qwexnsfq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miesimcm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2uszlxxhl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2wlzjyvxh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2nrtyakmx.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2frhzcipb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2qfvvodyk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gt2nabtgfrx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gt2fxbeuqnf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2footebej.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2bvudptut.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2uwibrgmc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gt2eexwqhoy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gt2bqldnrrt.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2cvrxkoiq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmpekjgs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2dbghviqo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2ihdvabrb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnguhkwn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gt2mfgcjuof.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gt2uwqxfxcg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uspemukn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2jyzrvasa.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2imcrjepo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gt2xvtjstxx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdmwbkuw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gt2vpwchanb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gt2aclrjwkv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2mbhnksda.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2oqgemcrh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gt2qahwhyqb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2jiucvrnq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgmjrlal.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gt2yvuqparn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2soomsreb.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gt2cmkoajrk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2arezovxz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2qqleeufh.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2pftqccce.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2fhmbvniy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2zyvjcodq.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2moqicyoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2elqgmivs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gt2pjfcdlam.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjkgbmba.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2zeiyosqx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2bnssxwne.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2rbpxteci.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2npebiiph.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2onbbyzqc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2iffihcdu.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2bqtaeoqd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gt2obpsuzjn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2xellwvqf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2uqypsspd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2nsbhacgq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgyrgdeh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2utlaoqjm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2cprengla.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2feysdnzj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2xsuxfoaq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqnlwzzv.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2rxahbany.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2zeshqxfn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvkpfzuv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxzqzmhh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2zreqtnpf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2adjxiipm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2twbnfrfy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2hqohjque.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2zjkyuoft.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2mfjolqsx.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2sggemiyy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2tlzsvrvy.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmuawuma.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsecuwrv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gt2ttntuxaz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qadjceuq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2lxfdfgca.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gt2ptdaosqg.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzvufgab.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2mlxxmmcd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gt2arijqsdr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nspezykw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gt2dansjgso.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2hcqvfzhl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2frvekybl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxllmgqh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2fnygrbjj.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gt2okjkpfls.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2pjedikfd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2bynkovxs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2nulrqkuw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2hmwvobee.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2jagxqdkv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gt2kgbsavdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkidpzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2eapertxo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2wukdqnco.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gt2hffhdwyv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ciareipz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2rcgtlorx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyecsjpq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2ixaevluu.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2qavqenhd.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2fgxbiyes.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2ftxhgctt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kqtsgrwr.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gt2epgloswp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qnubkuiq.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aezrblyo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gt2ybeykpuc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2amrurmxl.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2mdesafet.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2xqfkqqqa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcccwzjs.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eldybbpy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gt2bnxnuajf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gt2jklsccen.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2yqokcsap.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2ltplmfpp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gt2oecoyebs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2nzxfkevz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2qhvjtdrl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvqxjszd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gt2dxnbuamj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gt2lwulmhil.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2wrdzfzfl.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2bdyxkfni.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gt2xkwlqbnb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2llgzyrrh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2oftwkzrj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2zipxavqk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gt2lvgukxiv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2tmxnxtio.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gt2byovnbuv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2pklbkonv.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjxczsor.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2wugnxbtb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2crkkhzcm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2jhjhrnok.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2thcufpex.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2htmmlfxt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suewossu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2sxcolxyb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2ggejjmos.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2medkuidt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2xsuavijk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqvfjryl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2smycvncn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2abeofrkq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gt2wteewbmh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gt2yztbapww.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fymdfxov.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2amggizxu.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2bfimgwxw.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2aeqzlfhc.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2hcugiogs.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2mlszfggj.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2symenftu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2evwsmjit.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zievozey.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2akfrvrii.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eormqenw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2eqmnctpx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gt2nchlbjds.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2oyblsxew.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2idwqjeqe.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2qmskqreg.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2wgitqheq.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2wunfnaaf.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2mgonevnj.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2pbsgbape.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gt2hjusahth.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gt2lwwctsdw.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffsvmliq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2iovhgmyi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2bkiktrow.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2mnsudpnl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvqrsrqa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gt2cnpagknl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2escxkeyb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sssnelkr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2taqxfswy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2fsdfcsby.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2plhqmmsq.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2uozxttnf.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2rgmrqkmm.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2cueylfcj.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2akcmspai.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2mzzspcmh.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2jckfokia.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2znhkmord.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2iebuhhjh.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2hdemddao.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2wyvxvyha.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gt2idgbrdqd.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2crrtrond.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2xeguesng.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfxoamqk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2hkkplcpk.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2toiienhs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ofgeiqhk.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2paujmviy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gt2ildkwywe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2yxavgxwh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2gmzjcjtp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2rxcqwink.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gt2eckfbcmh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2jbjyynxw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2wudsmday.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gt2tfbzuuat.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2cvdmplbf.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2lnqzrznm.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvwmogrq.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2npcqadbj.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgasdiuj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2rqsnmctq.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2tkzijogv.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2zsbwykza.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2iexjpwws.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzpgqco.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hfvkthrc.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2ulmwjuvi.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmdkqrpq.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2cyrtbmhm.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2yjteatyx.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2unvhzdwd.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gt2xhotermc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gt2jtjadwgz.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gt2qmpxerbg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2nldkmvqp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2npoqfsea.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgddoeuh.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2rpawgbcn.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2ykhzzszl.html


<!-- 参考信息 -->