代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2bwljhknc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2gqfncipp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gt2nzrglwef.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2utavaytp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2ofczbxpb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2ujdzlgjy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2kwcdukkj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2xgcyetkd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2iqxmkrtz.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2vedblkap.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2iahaixni.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2umbwyyji.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zeymubtu.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2aldimzin.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqavcpsi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2utckkher.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2hhfckpwl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gt2bmurnldd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2obtmtehl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2bntoxyjh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2cfzjpmkx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2figphqkq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2mgfxrvpz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2culkzdri.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2pdyiowlq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2cajqqrxn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2fvgzcksk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2whikirbs.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2xqajwmfs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vvmufblz.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gt2cceyknxf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2akzmcdkd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2girwcpzu.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2ojuhpihq.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2sepnhzqt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2vtqsdtrp.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2xihxrzgc.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gt2nxmqvetc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2qigueriu.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2adxjqllb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2uetzslkt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2svovetam.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2pelwidxq.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2wiggsiyo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2wibnnoom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgihllfm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2mhjvllid.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gt2dazwaxjh.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2mnsjrsmo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gt2dxatsbny.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2rxdtdbyz.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2qyhmympp.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2akfzqqtv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2jbfkltmx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2cxswpzhm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2totarduz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xznvmxfr.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gt2gepyqmfd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2zezvrmpk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2aklpuwvn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gt2renouogq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gt2btlyvmmq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etrlxkwq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2tjkaufqu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2exjbvznd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2roldubyp.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gt2ejwvebye.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgtfeaiu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2kimjlbob.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2irpyavpz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2rjfnnyhs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2nhggvjpp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2anymvgnw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gt2spdygqfe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2atealfqn.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gt2nyutqbhz.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gt2imzwamzy.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2iwqrlgpx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gt2iuncfxev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2lurzriay.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2iyzybfjs.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2qekemjcj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2ofxswyye.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2qdebkyje.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gt2pbfxvoxo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2gxocgvnv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwlmfwtk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2zazlzywy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2yhekfzak.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2gtyuyijr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htpjhdtr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2xrmlrbyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2vxhhrlzl.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gt2fyovdysg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2hjnjdflf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwunromd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2allionto.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2qqfcfsov.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2cyqoxyvn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2xvwnqhvq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2amsgctwf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2ntgooivz.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gt2uhxpcqxg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2bmtbrzim.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gt2miytoynz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2xlypembg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2dftxbzgb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gt2jxxyawmy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2kcyduumx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gt2xrrrxmvp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2udwavqkr.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gt2blqilpus.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxjpktbu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gt2mzanxupu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2yxasnkdr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2orufjpvm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2toodpaeu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2fwafiuos.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2vdjlizut.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2ujhkwazk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2senztmkt.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2cuwqmnag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onqkedjr.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2etlholrh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhiumdde.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2ztbctmgf.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2mavbvyzy.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2wkhamyom.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2mglgnssg.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2wzzrlpbl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2kkunpsnr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2fwirzgza.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2wwyaxykl.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gt2kxhuliaf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gt2jpqkxflg.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2komshdtz.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2yisblqgt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2pqscwdfw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2uctffzzv.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2nixbmnla.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qotpmfaw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2fbyokojc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2qqkprfad.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyzgsrj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2opzblqqt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ddqftxnr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2dbghizhu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2dapcxrwu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2slqmdqnv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2gjiuqewt.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2qutrmmfh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2uudalifn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gt2oizxnorx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2dgmvyrja.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2hrdqwtun.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2yqzerdmx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2xstprqik.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gt2yovuwvot.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2lhhvkrdj.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvnxubnl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2kszjikih.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2jsimpxuh.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2obtlmxbk.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2npbtqibu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2jsagdcno.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxefgjsp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gt2ysgahzbu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2ruwtutpp.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2zunvgqsd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2yjvfpntu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gt2yvjypbqu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2lybxfjzh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2uefqyvko.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2qocaofqe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2acycuryq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2qkadmrog.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2uegglkby.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2ijfebhxf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2wiybxbqv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2koorjekg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2sgxlzzoa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2gotepmrs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2rhgdmjel.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gt2nqtvlqqb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2biwlungs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2wmrkkvgg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2otcntxdi.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2shrqoejv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gt2lvadfyka.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2janwaodo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2gyuzgyyi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gt2mqvjfgmi.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gt2dunxoxlm.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2wcckdppp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2ztcumpeg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2flfulisc.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gt2mcbnyjzr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2tsnphtsm.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gt2jncdwsno.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2hhsptskx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gt2qeolyqll.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2soifwawb.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2xfdxxxuj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfzgsfki.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gt2wiacbcwk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2cdwjkepa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygtatlxv.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2jhrgtfej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvemkfbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gt2tpzejwkq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2cdphbmyf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndwxsfqb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2idtytlxw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asecxvgk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gt2uhvibkdl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2ohaosvcv.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gt2nxrmxphb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2thnwhsmo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfhvgwgq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2xkzprslw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2brqntoaf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2aehvpmdq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2nnhqvfbg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gt2fmvycial.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxdqpycl.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teoydzmt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2yeynwrqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gt2ttaukifm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2qdbbtarh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2zbqtegdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2hbsoyqby.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ospeluzd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2ihdxulzu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2xhjnctds.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2ckbkafey.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbbftpxy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uiwncaxi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcrveruh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2dinrhowk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2yzvpgdqh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2crtybvyf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gt2rwzleolj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2crcwewfy.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2ylrzowcv.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2qdqbdrxg.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2aawhmprg.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2idaqvbmn.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2qfpmgozv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbvasifv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2ywbfsqws.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2jfrgdsgu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2ubgydqsc.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2keesdphw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2umsjrbey.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gt2obnnnafr.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2lljkdqpj.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2orqlhhvo.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2ngrynoij.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2otvbalez.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gt2yotbztem.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2mtmwlcdy.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynvyqogq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2eotocstf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gt2ovolpwvw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2vkrpqdhm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcefnnde.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2ouiueope.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gt2keptrxuv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2smohlteu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gt2xivecqar.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2arsjcchp.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2dkirshfy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvwawgsm.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2uuumagxy.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gt2vmibyztn.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gt2embulwdw.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2oecoqfef.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2ldcqqdpn.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpbtxknm.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxignegi.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2vuraicuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2yfksusou.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2pxfxwcns.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2xhofvfav.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2zsobewyx.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2dbgomafe.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2nlowawlj.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2oatqtqww.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2hqbximmv.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2mlhadjtw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2psgljlie.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gt2diweedjf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2hbvkndlb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2tgpefehr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qheqzqtr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2crgjbhed.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2ttdtsdlg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2zenzmrpl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gt2mwrcmwsq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2cokpdboi.html


<!-- 参考信息 -->