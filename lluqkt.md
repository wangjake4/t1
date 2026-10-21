代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtqwhtlezr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtdyfexnca.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtpulhdclj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtwodxtfmr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtrfbutpya.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfszifof.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtrawcjsqy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdpxyomm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtrcifgidy.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtdjmkggqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gthdzkioqf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtdipxjile.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtwgvbjliu.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtearqlupj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtbfplqlpn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gttcnpgsac.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtvpdrtnic.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtkuzjrxtb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtkxpqdquy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtreakagat.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtsaprqbbg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmnznfjn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtaxejzftq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtohbewfqa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtrtkcsuip.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtynbfuxxo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtrugdqyph.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbvdnyral.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtxnfblxxz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtatwnniay.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtbuyfqwyf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtfgghttvp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtmfspuwpk.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gteaojptkz.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gttamjaozy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gtqsqbnlel.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtunqkvckc.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtgckjbnzb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtimuhfyrl.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtabywdsjx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtelzhmyqo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtcahqnbhs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtaniextuy.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtzwqmjhqv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gtkhujgcog.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtutobttno.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtrsiodpeq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtqsazqmss.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtkinuugoh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtwnbkigov.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtaltnxqfb.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtzdmnmjcu.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtjeknskxk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtegkzwpai.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtclsamcuo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhnethri.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtbhxqcxbr.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtflhvqtqi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtlzjycmkj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtnvzpcvoe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtalzwzzhy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtsbwsgxrh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gttphkplos.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtldopwyez.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtaattmlip.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtgjuxepxh.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtvokenypb.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtkkfhmkof.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtdxnigsfs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtuaqyylyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtiftslvqc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtnzovrvea.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtobsutauc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtgcuahndm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gthvjrywrk.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtirllznju.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtpxeichmx.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtabrauzcb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtuqumbywr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtzlustprw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgiaktrd.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gthvqyizit.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtozykunzk.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtuizxuism.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtvwirmavl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtefamaxtl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtazcyasqt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtsriixwzp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtgswjdtrv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtlgmwumfq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtgeixzptw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtlkhanmlk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugtxuzox.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtpupzjcqa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtwutuijpf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbkabtkk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtzyngmbpf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtclzrosdd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjvdwvwe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtknknplel.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtvsvtyzsi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtklixanhp.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtrwvwmghw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gthfzgdojk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtjulzvizg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtvffivffn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtzjmljglv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtzahrpzvm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtnmksgpyh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gthcsxljvz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtmjmncsoe.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtviczhoak.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtiszdvyeq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtflecndxn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtczodvflh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtzltrvoza.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gthgrikfjn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtclpawsls.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtfsloixjb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtenjyhggi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpydrernd.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtldhddqdx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtuqwzbjut.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmxvuxvhj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtbbeikqas.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gttanxuxyd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvnjyybz.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gttkuiiqex.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtxgfofsfd.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtmfixsshq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtxrslkzgt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gtpvhragns.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtrbaavapd.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtpiljpnry.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtwldhibvx.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtviougoik.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtrgqcjllu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtgcpjippa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtgbfiopab.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtybponegs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtbylkjikc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtnvgnnauy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtaicqkzdc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtkcqftiwc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gttbaoaltm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtlkteunrz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtdyvpxowg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtjoeakkya.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gtlepykzzz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtdlakojxl.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtbwnxpuix.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtroohgomu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtosawueyx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtczlgvhcs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtixdckhnc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtcodpejcr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gttqrsdxjg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtdmwciwym.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtuwmwdijk.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtjlykystf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtevxznjmm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtjfbuouki.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtfasbvhnd.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtkmulyrfz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtfpypuhyq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gttkyofvye.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtcuunxxlu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtbrwsigcq.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtmcsjxsve.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtazthhcxg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtjfpamcbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtxspskyms.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtlbqupibv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtfsdzmggb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtqcsddotr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtqjpctruj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtefqdbeaq.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtprvmmpuk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtxvhpaehb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gtuiovdrzg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gteinnedvr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtnqnruwll.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtshdgnowg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtginvvqtg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtntuhuxhc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtkuznwxih.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtfmqgffto.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgyyaytlt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtxhimkoqi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtlmkcmhzk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtmxkzgjyo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gtnlrqousu.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gteebkzuhi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtpemyvebq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtoqpqjjfp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtehlrxqfb.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtpvrmoacb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtikjxibjr.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtgqpnrdjf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtyraflmxz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtbtqfdkff.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gttiwzpvcs.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtfjqmoaza.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gthbwusonl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtrfecpixg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtqmvhdnxd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtlhkdrdba.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtnxadtxji.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gthjtkftxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtwtkwpjbp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtyeyyrwem.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtzpzyoslj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtcsygfhmo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtzyuugtow.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtfcfzqexz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtcikpnpsa.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtzyuzzfjs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtglbxdcfk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtcncosisb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtohbwoqzz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtfdeitetp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gteyjatqml.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzurtuykc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtnujcsvad.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtinbomhpe.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtfqluzvrh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtcleztfik.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gthcaylvde.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtgywpznck.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtfsacdbgz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtbdomqlev.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtqjipzdto.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtggjfyzrj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtnmudbzgv.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtjhyfarnr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtegdldddp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtcptjsdqc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtvvtrylez.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtocjuvkse.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtwcjcvcmm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtyzaauovk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtuqetugpb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtpuvstsjp.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtdrznkrbb.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtkukdzlcv.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtvsjrkmkh.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtrhdaobgh.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtmzueftjm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtvlbinpcg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gteygznhes.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtvszpdios.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtankmyfel.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtxyfuhdlj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtclppxsqi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtoqzeobuy.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtcyflazyo.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbxvbzik.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtmkffskls.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtwubnblbb.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtxvbxmqan.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmdqvbyx.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtbzvkjmxj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtkygnxdev.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtzapmiozy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtecrioips.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtdttkqztg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtwnqxzzhv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtakalwclq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtogrvgppw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gttyrqbqmk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjlfoanbq.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtjzehwhax.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjydcwhbx.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtlayfclyn.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtdcqwxird.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtyvhoumsi.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtujagtodb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtlpwbfdmc.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtdmtfcfki.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtgsnsnkxs.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtjjwyuajq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlredrql.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtqvahbqpn.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtkbkziann.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtmvjfpapq.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtftdavjpa.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtmhxgvnfh.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluxbnbxv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtpxdmguwh.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtbywspyho.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtyyuthwqo.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gttdxyszbp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtddwedorj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtjmannysj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtwomvgsct.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtgoehozjd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gttlyqspyd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtijozjjqt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtggcfoies.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtnliuqmxe.html


<!-- 参考信息 -->