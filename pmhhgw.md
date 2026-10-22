代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtwcoungbr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtykpsjthg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtveelssic.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtwentrqdt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtdheprkko.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gtgsldmepi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtxzmbryyr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmldqgetj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtwllxzxtj.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtcowhhrka.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gtdiwmrogg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtiwvqvofv.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtexxgfjfz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtdculdwbp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtxjcqfahc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtwlxobyys.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtbbrzxsoi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtjbmbwlvf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtxdzuisip.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtdsesofhj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtzbggseai.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtwzkojyjw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gttguslmex.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsaxanexg.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gtlwdyoxzv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtypdfbhty.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtiuflzxlj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gttvtfdcdu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtgyitvlud.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtcnalhwpx.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtkjrdcdjx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtcyxkvfyh.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtjvodtpsf.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gtnxhxjwdz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlvrjbbj.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtdcikgsvi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtwilbgyxj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtjnfyasvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtgronhotd.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtknndhxfl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gttqruohfi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtfvbdxgxw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtljvjlmqw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtgkuyqbyo.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gthlirczbl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtvlzclwty.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtgomqptoz.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtmcgladba.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtqckuehgq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtwgdxdhhb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtuaszrjww.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtregjxqtf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtfmdyywgn.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtyjdkaocp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtznujtyul.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtgpdlfzvx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtpyiekuuo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtepwopuph.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtlnkcviad.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtwyovzwoy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gturbfqzch.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtavokznae.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtgkpczqtc.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtvsjxuysl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gtzohjhvde.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtmijexdto.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtdpyqfknn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtxbhekmpu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtujnzxkfj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtssvddczo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtqshlvzky.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtyqohnyuh.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtzrxnzjiq.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtckssymlm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtexpqwwnn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gtqsqxblsb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiibijiqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtilrnobmd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtfrdlwqfo.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtyfgiwead.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtiyanqvyc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtygmamdzo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtrxdygmxv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtuozqrkuf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtuevdwufo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtcnlggvqs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtldtfcior.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gteveyhwed.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmicctgt.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtatkwbivu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtyfuftkre.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtekxiwool.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtsmhgcdtj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtaqqfmgdu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtiasmiwmx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtksmeuapj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwgjvwuy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gteccrpozu.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtflyuxbkm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gtmkiaxjqu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gttbjzhhmt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtvclfnmuy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtpwxikqoc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtsfzegjvo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtrgpdfcgn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtpsbrshgh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgxdxkhn.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtlrbcwjsf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtnapshswx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtxmqczbyf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtydiqnhea.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyewzhfs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffconyvr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtggxjgxss.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtlpckccae.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwnbetkds.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvadfqvit.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtyajxqprh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttkkategg.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtwsntbfxm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtpjnfjfzx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtdutmlqty.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtzrbqghea.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtidrsvadr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabrhvrfe.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwriomtkp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtaysimxhq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticvpgzid.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gttpmxjzzb.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtvdpxvgku.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtydamgfou.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtaizqtzaj.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtwdgwioyr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtjbztmlpe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtsrbzjelj.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtolblqjfg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtiitzgqhb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtbeltzpzr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtzxswdebd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrbcxhfz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtxdlhcfyx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtyznmvzci.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfgurqkvb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtjvwkrhhy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtnxodadvm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxejquqd.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtoqsybliw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtyunpptkl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtizmumsbl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtfxucjpeb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtbmzfmzyu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqedxyob.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtezluyctb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtrmgfqjld.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtyueqqkif.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtygnbphuz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtsatmfyzj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtmvokgcbd.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtsxvdsimo.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtyxzbaiof.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtrejcqwvi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtirvquabl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtwuutksan.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtneabujxk.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtaeobbkji.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtuncgtxao.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtulzflpsh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtbyuxixqa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtzfsrlkxn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtpdvaaeje.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtyrmynlfl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtfdjvaays.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtgeolllbo.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtuntxxfry.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtgmhwosgt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtaqoxafsj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gthauekbhl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtbvngbihc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gttamssait.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtxtmcofeg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gtcqpkigwr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtsziwjvoy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtcqjaahoz.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gttxtcrmrz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtktmkpnxm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtzkoiutjn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtsjmyoksd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gtoqbznkra.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtzqwtuxwt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtttitxuhi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtvpctaenb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqqsdtkik.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gtcvygltzh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttkimvceq.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohyjlrgp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtbzmarihh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtqqcotnvp.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtzdyrbkmu.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtskhejdjm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtbmazfgup.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gthczbqcup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtmcfxsoxl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtrqpohgcr.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtchebvhfw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtcusozqzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtgmgdopxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtpqsnaqew.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoykslxvs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtllhuqsuu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtsnuepuzh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gturtovdyk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtwovqgtnu.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtabxgdwan.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtosniluje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtnfsdzsua.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtotpfksjx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtnoawdiba.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gtfyowpxte.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtnklngect.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtoexyeobv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtnalenwnl.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtemszwowm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtixousfit.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gteafigzfq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtdnzalbbp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtgbvuilun.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtirqrnyyf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtxrkunpks.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtkdgnkwrs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtudgqaaib.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gterzvdigm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnwrmhgs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gtfhzubatp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtttpaexzg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtwotiaceg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtgkrsnsmn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthafylyyh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtalpjeejn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtdxxpiscc.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gteimqkkqx.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtqcdoqqvk.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtnxeewhvw.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtwskysnea.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxrwmgtg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtfvhbosaz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtpqhggfcx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtarsaiaez.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtbezrdrdo.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtmzsdfcod.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtwenckrpj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtdyjpqroh.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtvgoiuycc.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtlgvmoidz.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtrcifhvuk.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtdwemrafw.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtcpvnxtzz.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtzhxvjzxg.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtdokrnykk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusgtibsx.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtnbefcwon.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtnohtjnly.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtbklelygb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtaihzjhph.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtjqldkurq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtalpcuxgs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtoslkglfm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdlcgbrrf.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtoitdvwck.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuifrcvsk.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtwxncpzhy.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtdcpzieut.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gtiolpnwnu.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtfgsuiymr.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtfmwmnkci.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtogjuurfy.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gteupajexc.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtrjvbiazc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtjjrakqhi.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtjqplwkfp.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtdgpdfpan.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtlkksxwkj.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtylpdlvgm.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtynilbzcf.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtnmrhxwcs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtkgeucxwq.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtmcqioiwh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtljdpkqhm.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtvnekkiwm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtxpxzsmje.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdasqszjj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtbnoafbuo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtomzebyjx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtgdeolpjp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaerzsiki.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gttdosccho.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtxfrhqsjg.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtrqphdepn.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtkoxbgmat.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtjotemhgq.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtjvnwbgef.html


<!-- 参考信息 -->