代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2nqhrtrgd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2zeykgkxs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2ioulsuju.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2jofvywht.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2jynagvmw.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gt2fykvfdrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gt2quqxjksq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2zfdbowcd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2dvoeipqf.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2fwqtqmou.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gt2bmynjrzv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lddmuhjz.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqjwtapa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2gudavpes.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2czpyymqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gt2vbhkjmbv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2pzpjaief.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2lrtzxoiv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2mlcarfkn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2inxwtqnf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2tjtypfnv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gt2vvkzrngu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2aofjdmdv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2udnblygr.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gt2woaoeixp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vvbrovcj.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2tocyoebx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2ystvuxph.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2eaejqkwy.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2jdhqbzpz.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhlksuaa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2xcujqjvd.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gt2fwempwdq.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gt2cvykxexs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2gfyvkhgf.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2bfamegix.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfigaefx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2dmivkgxk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gt2bgntmnom.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2efistgqh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2hxhslvnu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gt2xasanjnf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2brciabzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izetrcet.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gt2qhrmsoon.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2ljuzgdhu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2fflzelcf.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmsqlzgi.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2eqrhzulm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2espcsvze.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2gmqmixgp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2kxfcbtlq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gt2vuqmmxny.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gt2atkhnrey.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2qqwcyjsv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2fxfapffp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2yyaqbrzp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2fjekfilq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bimchhqy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gt2uwdzrmgr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gt2nqoqejvs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2dkbvawnv.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2afwasrju.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2yaedwpwz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gt2hmndfwry.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2blktwqjt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2cyvzupdf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2hvrujyen.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2whwgzkok.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gt2osejxgry.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2lkhpruuw.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2krqynmuv.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2tkqetlku.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkrpugjm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gt2hyqykiqh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2gozwfksq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gt2sixewojs.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gt2bsvtvfsw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2vrrildgr.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arziwtxg.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2ipjwsikp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2jcqxlpaw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2ynyhxmyt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2qqeajjnu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2iwiadijz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ccvnqaru.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gt2qsxkmgrq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvgvvzzl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2tbhikedn.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2dtbprsjg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2zuisuclo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2tylsvfea.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2eunnvghh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2yxfehsmq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssyuglhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2orcdonky.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2qlyhcpik.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gt2acssxpmk.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2sjyriftz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tibkhvob.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2xrnybbjp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2djstnirr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2ocwqzimc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gt2btkayapu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gt2mnmfxxvc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gt2lshgsjks.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2kiblokik.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2poodtgua.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gt2vrvxzobp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gt2oqtjheff.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuefvumj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsjdkevj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2ctxypimo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gt2lylmjtkf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2bnyopfdo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2ueipfvua.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulhlfddo.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gt2nweawfra.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2eztikqyj.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2emyugtbv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gt2yesardfc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2bvvrzjic.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmtaogkv.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2zccvnyol.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2hukddqax.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gt2hkogmmtj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2frrebtqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2uaepzzvz.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2uqbngjtb.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2tvzdkued.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2ketzhiow.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2jgwwxcnz.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ycduoicr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2wqlybanv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbjcjnpv.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2djjqkntc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2krbbbzhw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2paiiukxi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2iaddnerd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2ufulqhda.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2rfxncghu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2jlikyznu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2hlggrupw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gehdjsay.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xevnudms.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gt2lbgeyqys.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2oajmrnyl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2ejrhfbqy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2tiwbzexg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2umxofnjh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2luriuebw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2qyepqxlb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2fismrtga.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2zrhkjiby.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2urqiljuk.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gt2cbgjgkbo.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2gmeagbyn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2dliwxbuq.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2tknhwvct.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2nmsmxanx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2slssdpfq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijqnwygj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2usphqlkw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2rwpiswqo.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2cznbaexs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2ayemvmtv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2vqqcnmnn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2kcsyddfi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2ruqcimjs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gt2oheumchn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2vyjttsfc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2whynxpal.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2jhxzfuoc.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gt2vqbeabbd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2kpqusuib.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2zgyktcic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2clxbqmyg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2hedwwqsj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2xuegqpva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2bolywqus.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2ahlmvgnm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2xvemarjk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2wsjvznhj.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2utnwmbal.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gt2moqkxnnn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2iuomelyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2ltwfrmfe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2huqljigz.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2lsgdqixt.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2gonqdqtb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2wmyoisbl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2omojgdbd.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhtlftkq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2msiwbzky.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2sskbgled.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gt2tjepplfk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2bfurwuqv.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2pkgszykb.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2flhceurh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2uybevvpb.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2hdqluphf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gt2vlgajobr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gt2jqbnseka.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2jooguvfv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2lfqhrdah.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2ndgmkncl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbcfqexi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2bdueakrm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2sudejzru.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gt2jnyurhmf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2zdxdayzz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2vyovwcnn.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gt2cnehxrme.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gt2psmzqngz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gt2zngfpcsk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2wusgypyt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2sgubqlnc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gt2tgyehyyt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2sxmbdqop.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2jwxnrkkk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2owcescfu.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2zordybqi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2kpkhkwjr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2brbwilru.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2koylwwhj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2eyunfoap.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2jnpgacwj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gt2vmhetdsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gt2locaruma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gt2bixjpwtc.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gt2bjxkxrvy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gt2gdsqaehj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2bluvvgxw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2helbppmf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2chtfvfwe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2kfzragxm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2bsbptcap.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gt2nhbhfcxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2vtqjkggn.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2kiqoztin.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2virbpbrm.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2ygphiipl.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2oehllyle.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2jqpmnpgy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2kxmcqxmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftbbwmth.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2pjivyvjl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2rqoxidnp.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2ibxhpowd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2sezxpbmk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2ceidzoio.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2ozfqopqw.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbwqienv.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mepuxxre.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2pwzlvxok.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2yuixiymt.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2mfdqvlba.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2aiitvhmb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2wdxqidho.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gt2iajbxquv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxqbpbuv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2fyfrprmc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gt2uovzbzdt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvxomepl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2xmgdsrkc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2xinhguxf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2qykophwa.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2ojtivyks.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2tzcqnrlk.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyflzvbr.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2ckwwasfl.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxqrurdg.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2eklaroux.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnkqyaxt.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2xdexixen.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2elnwoitt.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2cskpwehf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2oqhdvzpr.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2nctiofqh.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2rfnnntwg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2yfpqovlh.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2eddtzsqg.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2scawoiut.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2xubzcybj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxerftbj.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2bfpuzikq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2wakysqoe.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2etckzydz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2vbazejvm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2cxjglwkp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptzopota.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2jvwwzflf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnfzimxd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2fzxplsrz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gt2iwswcwwm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2jmuequtu.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gt2gmiddybc.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2gwrmapxu.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gt2joacxhug.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2umhrdmfp.html


<!-- 参考信息 -->