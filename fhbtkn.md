代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2piihtmqe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gt2fadmojfw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2dyrpvmhn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpfhjygr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwxqxuen.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2omhkfbcf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2zacxvnfa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2fsbmgcuw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjshctix.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gt2omkgmnrt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2onkxkgko.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2atakdqsc.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gt2xnvyykqa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pspgybun.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2zersdxfj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgyupuip.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2cfrkqgdr.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2efkbfuue.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2gpfenyzd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuaneecj.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2bfspexuq.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2kjyrfmzp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gt2hpcfevoj.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2korxepge.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2pbbarnlc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2ueogbecg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2cacguwmu.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2rejrkqjl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llgyizbe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2hjwswyrc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2iwrpecbs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gt2pxxpxsef.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gt2qfqyhdnd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gt2uxekathq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gt2txdrdfbl.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2rhvudtqo.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2calrnfhb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2fxzeqpue.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2vlehwyzf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iihdltwf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gt2hkelzacg.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2jyvwrnbp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2lxdetkbu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gt2cjssxhif.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2atobmwlf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gt2qcxuycvb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2ukgvrbsq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2wzqzxdte.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2icgsaulw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2isypjuln.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2boeqvrbm.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkrvhtnp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gt2cqeaqypl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqnrlozv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2yylplurx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2ulhjvkix.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gt2fnqvwxzi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2ciaxhosh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2gvessqny.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gt2xwvbbghy.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqfumgxn.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2tqqacwgn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gt2erlyesvo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gt2mzpypwrw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gt2dekjrtgp.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2xtxqeqca.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2xqabuhad.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2cbeljotr.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2siskzphy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2hhzkhror.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gt2poinxczr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2zwvsdxwp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2pmqnhahi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nafawgry.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2ewxgmwzk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2xqklctke.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdckgvrm.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2zsrldfzo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2puicuqvj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gt2gurexyku.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gt2wspoyosj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2pksvshqt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gt2mdjucspv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2rqgsentx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvgkquvc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gt2grvpnhus.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqeilmlw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gt2izdthyhy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2qvxmltzj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2zoidqkvc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2jqevsgqk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gt2lchfzvqe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2aiykwgep.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2gdgguwaj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2mbnjholx.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2wsmwdswh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gt2sowmqgss.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzrrbsiy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gt2ajrfstey.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2dltnocpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gt2ycrmmgxc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucpnatni.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyfjwir.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2oktqwjus.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2oomzdpga.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gt2ojqqejbi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2vlaquxqs.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2dczvdixr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2ydatjnlk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2xkmaumbz.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2rmjeevkw.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ryzamwxp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2qhhfxott.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ijxbxzet.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2zxpraava.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gt2yvqwflda.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2yludysaq.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2btpqzojr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2xvgnrmeu.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydgqjjqj.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2zdcqiukv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2mkrgttww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhgulelt.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2cmjvngaw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2xupdwnkj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2cbtmoozu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2yhakgcyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2huyfqbdx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2akrmfnee.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2qczljdti.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ntgdaumb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2pzznymsq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2emwcnnur.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2nmjxrlro.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2sbfficaa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2lbbnybfl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gt2tvobqdwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2wbpmgygs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2imyiawle.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2yveqljgm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2huygjqxh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2tndhwrma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2hixhdoqu.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2rgsjstrs.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nxxklono.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gt2opdcgarc.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2elbixxca.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2woggipsa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2tvracxmi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gt2msqmfuhe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2kzwyepgx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2bnanqjsb.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2qwcjnnid.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqooyyhn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2dhcoiqrz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2zovzkimc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsltxsjd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2zrmealuk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2drrrplnk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2lxgkicxg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2hhfbxohn.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2poawrpmj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2lwtkjrny.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gt2ambsoyqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2sgvmjpio.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2yxrvzxsf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2nmilkxrd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gt2lrvtegbm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2yiamfwra.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmrsogvw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2gcqhgipo.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gt2hcljogan.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gt2pcfeucka.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2tjjaffot.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2jxuipnxw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llunmrem.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2utbphkxr.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ilgnokng.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2csbrsqvz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohmcmasf.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2hurcmucz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbagqlvk.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2upkozvvm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhxczurg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2syxrwrxk.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2vduhiauc.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2ybdkxukw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gt2lbbgbjpc.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srhsnxzo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwfhsy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdywxssu.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2vnmoorey.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2ikikanug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2tdtsluwa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frhnzqfz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2bngofutc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2cuheltuf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gt2mpbvmzjz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gt2rfmmjfhu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2spaxpueu.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2lpaartrc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2qltsbspi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gt2zlgofkll.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2xjjarmsa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2iblkbntb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gt2dwwkavcd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2mpnrhekc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2vtixnahr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2rrpljolt.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2eatcekvp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gt2gcwtdnyr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2iwqgzxsg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2qnhbcsej.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2ozeqhxkq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gt2suvxzsdc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2yqacwubp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gt2nuhvmbog.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpykooj.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2egwjnhlf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2gzcfygun.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gt2dzhupueh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2iursxikb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2shunnuds.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2vzjlmhfm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gt2tnshmnfe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gt2sqvmarjb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2hxqqvqnw.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2qjmboqho.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2dblmrfvj.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gt2qiulgshl.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2qkppifsh.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gt2kiyykhnx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxqikefa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2pahaavjy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2dwqcgzpu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2wukznppp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2aamqbgov.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2jfsjcduo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gt2lcjqtoey.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2mzlaalya.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2ifofldhr.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gt2eaetpzpk.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2kphjfqnw.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvnbqmki.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gt2ujgyyawp.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gt2nnszsdod.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2mzzntupt.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gt2zbfhwkfo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2huhsmuhz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2kxizezco.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gt2vcbpkzkv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xymlnnxj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2eazrtrzh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2ykbphwtr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2foufrjgi.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2xekkyfti.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ifjgvfgl.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2gddfunfi.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2apxmzoeb.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2kkeinflp.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2gpiraihk.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2nqbvsbdb.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhgerfpl.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2wzifdlgw.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2flbawehm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2nwegkqjv.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2jymxguka.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2knaaikli.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2skdtfhyz.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2dlrdrvbp.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2zvienpjm.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2apnwnjsb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2jyezhldi.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2lfwfmbdw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2pcxpahrt.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2wbgcsdxc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gt2xpqlfnfu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2aupjdumv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2elzjpfvi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2hffutlbx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2aqqjpzgb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2dkxbnymy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gt2worspxjs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gt2zqjqqkqv.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2rfdkfsvl.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rynngcol.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfkpvnpu.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2sysfufpf.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2galgnlhf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2pyoxkprj.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2piwxhtdw.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2kiwxpwau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gt2pkapfncn.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gt2nwarzgby.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2xhbmtngv.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2oqdmmqmo.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2opqqyhcc.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2srggemvo.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2wnwehicq.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2afbcsdph.html


<!-- 参考信息 -->