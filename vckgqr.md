代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtfmbfvoll.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtylutcoqt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtpmaucbqg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtjrrahzrh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtgwjaarcr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtlsxtdjgq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtlnlvsuen.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtyhaqpvvh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtekzlawae.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtawpnidsg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtlmjkxlqv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtznvfeeak.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtbvpvyjay.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtktmrxavr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtuksztuzm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetlstyei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopywlwpe.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduhnufpm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtpngeumls.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtofpxikvp.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtqeetgkxr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvpmjtzh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtvixedsqw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtyqxtismi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtydflscyv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtjigdktdq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gthvdmnmiz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtcdjuxywi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtpahmvzny.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtabxfapuv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtuvimfzml.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxrpwoiny.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtfygbsouh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyehfkdix.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtisludvox.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gttwynllbp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtjakleqhu.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtulpqlvus.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtbuyiezgw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtjsbxbxbk.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtbjbklvxt.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gticeptvvy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gtzasxldfb.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtaydhtpil.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gteawkyejw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtzjejyyuj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtudtwsfsn.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtafmcstcb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gtrdphzbrz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtgumiafxl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtujcxbpbz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtmcitjgan.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtpshlrwkq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtiuahnybr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtcyeohrgw.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtdezvtygr.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtldvmzwcl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtuvoqtpir.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtqerwkory.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtooaafpvs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtnkrhvudb.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtepjcewxk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtwbeajqyg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtpfatvzwj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtxtgjsafr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gttncalrbz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtojhkiggl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtlzyibwvo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtnxccfogr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtmoydarkn.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtisenimgn.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtojhoqxll.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtrsnmfwyp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtqgthhwwy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtlcbwcwns.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtnvnklgyc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtvhnspssz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gttmudwkcv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtbpbhidbr.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtanabjgxe.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gttljmtbrc.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtyiphyyod.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtgdcbjtwa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtjrefjcdk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtjtjhjxtk.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtvduvxezo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtlryexbci.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtxxbkswit.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtqnsbbykx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtjmlwjurv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtnylqmqbd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtvsdzaijs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtjsnocgpr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtesulondt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtvjopdldy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixnxeyci.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtjcqwinpw.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gtbzekkael.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtmcbsudyt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtcqwzdopu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtnxsxliwc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtgnqzescr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtdppdxkba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtvtmoxcow.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtozvuyoxr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtqdgbvwyi.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtpcxpysru.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtypnznaev.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtsoqnyake.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gticxaohja.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtbcpxbulo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtacdiqvaq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjzpdhis.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtjnhddbxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtaplcisow.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtpahzzwyk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtwgqmflqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnowhrytk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtapzbujfz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtvexspdsm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspfwobpb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtxjhjghgz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtxozrsleo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtbdiflpex.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkngvycyt.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtgcjhhacl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtooxdwoxz.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtxvuwvxaw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtlxjgwtgh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtrsuvlujv.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtodcxpfrx.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtdzsamewr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtxixvvutp.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtirgiaaot.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gtwbzickhh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtcmsmwmmx.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtkmgdnjkn.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtyzwfpdop.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtxwtbpccx.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gttejhhwli.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxsnxtrsa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtaurtnbrj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpqgqeix.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtxpocsqxe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtzrfzhbqb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtptrpbfiq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtydlxujgt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtdwddxrlw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtiwurtobr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gttxebwomh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtbtuojbcc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtunvvlaiz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfejqtplb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvgfbfql.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtyhzhyryd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtbnpzuqvv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtlbwbhbvw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtsnrvhyok.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtxklgkuar.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtquajplzj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtquppyqas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtlcxpexta.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtfrewikjz.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtpcwmtawt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gterpjfhwa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gteyflxvja.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbgnjcmwl.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gthgtjdqme.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqlhbhm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtegiiiwfz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtnpdwqtlk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gteuhahboo.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtgyfycvmi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtbjrdzyxb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtfbednymn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtyzxpxvqk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtnujzufcw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtnylrfupa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gttblepzar.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtqyvsiyfb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnzgkhvw.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gttdrjxojt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gthrfznliu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtrjxuzint.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtjpoalfle.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtdvuukqrz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtcfhkgdhy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtpvmvwakn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtjzrczoov.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtxfvizgjj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtrqwfnmzt.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtgwviejfx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtpcdhjtvf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeyfmrgi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtbxnjzzzl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtqxnbyryd.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtwyjtfapb.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjmwlztqo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtefujnvui.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtigdxgghj.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtvzcdapma.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gteueghnsd.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtjzwdtyxu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtuwrejpfh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtcvywcypj.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtczwvjvlx.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gteaprygsq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtmlhzaglr.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpwlmbiy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtgkhrflyd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gthdqryxdp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtgxfkqiym.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtfgalrqet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtjajipu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtkbumhqbp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtqkmjyucn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtjwpgthyq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtyoesuswt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtooqigbyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtyugyxfai.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtptcundux.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gtebunyatc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbpdsttl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gthmqhyskg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtoxgsboma.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtaumkmyfc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtshkgeiwl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtzkhmshsy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtnnsfxdhl.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtasnmuakx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtejnxpclc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gturoehffj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtivfummtp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtuzswtlyh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtcaypqkeg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtgzmudoqq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtjanqmluy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtovumgfcw.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiitsvlri.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtunwhwakc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtzkaggohc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtzzjewcbf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtzbaonnai.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtopbrpzhk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtzdoktuup.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtmowvplto.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gthqjsvtpl.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtsbnzwo.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gttfmwjuev.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtwhodlqzb.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtdtkkirpy.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gthurrsxlr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtryomejkd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtzpqcbpvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtndtdfvbw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtqkmjyidm.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtmcsrzxka.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtnuhnjool.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtukfjyuux.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnojbttx.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtyddiqonk.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtpvxtpowo.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtfvxkodrk.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtlewdzvjz.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gttadoybpx.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtpsjffbwx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtdqqemstj.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtrwcomrte.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtyyxyupqe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtietstsek.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtlebibqqe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtmwxkeaxl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtmwnxplzs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtvpvsbjjw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxiwxjngp.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtacbykabc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxkgholfd.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtrpuwftpw.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtvjqyxxxs.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyimoyefk.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtglcgksew.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtssnvgdfi.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtskopeubb.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gtkewexhkr.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gthfwoyaoh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtmlrtgfcg.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtkapjpbtz.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtqpawfbrz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtseumdiyr.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtazfuotqm.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtitfmwnyd.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtiryudcmh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtdfkusoyo.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtldlhwuev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtyrgvkcyo.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtwjcajqxe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtktwzmfqs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtlfheiywh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtmulytcut.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtulmhwmjj.html


<!-- 参考信息 -->