代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfowqdbs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtiyrmntsy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtosrhcmqx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuvsjngm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gtglwbtlgz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtdnaqdaxq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtskoocaob.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtdpqxmqgl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtzevurkvn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtmxzlizxx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtuqxlwtbb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtfurnmlnz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gttdvfifnl.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtunotwoij.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gthgzqvwel.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtabkykcxs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfiiwkow.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gtyvynidgq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtnxrdgirs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtirllxkfo.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtufuteqvn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtfuxezzyj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtexqdpnqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtwsfpagzz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtiopehnes.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gthskuqvvp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtgovsiack.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtqcssklnt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtuwsibyrg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtsigtqlba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtqwtvqben.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtopnkqgkh.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtyrfzjipg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtutorwyrg.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gtrdadzlad.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtbkthsjaz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtipobynat.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtccdxjhce.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtqllcqhxi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtynbfhnrz.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtrpxpaovy.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtgtybwxsr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtpzrogvej.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gturzpkpbz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtumvfqcwr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtqqyztrvs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtmpwgandb.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtysljjaax.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtgeutisov.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtmedheaap.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtbglqdpja.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtzbzqrjnv.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtgleamnzm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtvvonrecc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtqmfijocw.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtqfsketrs.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtlztatffs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtxbbtezpw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtzvzoxyvf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtuybdspbr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gttcmjsizj.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtjglxavvw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtcwzodpex.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtsobptfer.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtesexhjnp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gtuuxyhhsk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtilvhfhen.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtzlrpwagr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtsehozzef.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtwckfjgub.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtitmdcwhu.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gtautxdwpz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtzssfsanl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtlkkruxbc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtiltwzglm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtuvqvdlfv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtwjibkqic.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtzabzsenj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gthlqhwifi.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtvaiyplol.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtseujixpi.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtxqapsmor.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtyrbktsgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtjjhsthmh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtorizrcrb.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtgebjyqbt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtuvgrllrs.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzvkglxh.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtqsmrkegy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtyijrcjsw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtzassmkoc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gthfmuzzku.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtlgdobpvu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtgapbskgh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtestartdu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtifiwbauu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtseaofgui.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtsaeiqhon.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtpzqmahat.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqxwgcjd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtndrcybqx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtfykviroy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gttfmaaudi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtrpqmmtkx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtokcftprf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtiyvvvfvq.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtaiesjbdm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtqcisvaow.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gteajnxcph.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtuhxokjcd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtgyvqkile.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtbxomwswo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtbfsycdhu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtdmomagvp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamodklsv.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gttzlgkavh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtyoppsoar.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtpbuhmcom.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtmziceozd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtsozmenid.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtbyejfqge.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtxbfcoikj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtcxyzociw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtyjinnofv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbqqnufim.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gtgiiiyjlp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxzzjbkjf.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtzffunvlb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtqieisjdd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtxymcxebv.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtasziyjvx.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gttvumbvxc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudqdhwal.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtpvtknrnf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtopgkqriq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtkritnm.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtytrchjgw.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtrutjwcrf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtppnrtoci.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtqusqhklv.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtztnrowij.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtoqylexss.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtawlcqgif.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtsquguzrl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkruwatt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkuxzxuz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtzgxfizrj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gttijiamwq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gttpxoydei.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtxjwcfjbz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtxasiknin.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtyaurbbva.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtsrjnlguh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtncphnexb.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtlafgxkaa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtfdewvfno.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtlprhnagm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtpydavntk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtklixipsh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtydzkopzk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtxprjkydb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtyrzdplby.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtwgkkzqto.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakmdfuhq.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtckambrsq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gtxrauvvsa.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gttmuqekal.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpunbqnxv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtjjfiosjm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtqscjnipg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtihysupjt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtlmvfqsyl.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtulwiwmpk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtiwkrwyde.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtjgeucoex.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtmarkblid.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtezzcrjcw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtmggbvvmw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtpftbvexu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtbiozymsz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtcncksefo.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuhbawyr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtrtpdlsnd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtozqhtxbz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtzetexsbd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtwpgpgtmj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopoojfvl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtsdxwhaex.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtvbkivkgf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtrzedaymt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtokowhxfe.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznqxwzco.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtozdbojeh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtibmudkii.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtmkrnekmz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gticxwfrtj.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtrocfoutq.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvxxvcuwq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkqdsqog.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbzhoeuyp.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtohebntpu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxrkyepyq.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtrihdsrzm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtwlppnbhh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gttozfgrtd.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtfrzghwqh.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtopudbxmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtqaycoblj.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtfqvpfzet.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtldljcpfm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtnciuldhd.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtsfonltgc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtvhyzlpbt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gtiobbxhxm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtkhfjuzvg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtjdrdvawm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtyvvqjpug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtnfytgpqq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtooklscaa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtvxubapnp.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtvtdmqtsl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtybzehdgn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtiuykjtwu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtfnfwfktu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtwuzkoizr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtcgbjzkng.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtoptaadie.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtxxwpisnx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtoawgquap.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtajwtbrrw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gttnurlwbm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtgojozzvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtleonsdwx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtwgsaabxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtbukykpez.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtsftllqod.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtlccsppjh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtlykxmdqn.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtvvnhxlcg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gttrxyfdxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtatykaeph.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtdruaxccf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtylpkxelt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtrrhzswbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gtibwdviqw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtzdrgbbpd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtahlczejd.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtxeeigsqz.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtecdqowsi.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtyqupptnc.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtgfrkrieu.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtyqoisqly.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtvrptaqta.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtwzedgsan.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtvxtjwzhb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtjmimtbhj.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtdtfolxjh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtkcxfywss.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtpeqhaeey.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtkpiwdnuo.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtoxhxrllz.html

Java: resp.statusCode()
来源：http://dali.zhoulong.xyz/Article/details/gtjhwphdbe.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtoslequuo.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtpaeradmp.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtlhkrdkmk.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtyssommra.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtdasymtva.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtjxydgvzn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtjvdvrags.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtqnanomkz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gttarpkeze.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtegegskjp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtegghimvr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtbqsaoglk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbzdfyloz.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gtftagwoeb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcxidiabw.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtvovxmpkd.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtclkunztv.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtvcjgthax.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrqopzkv.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtwfcuqdlj.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gttozbhqad.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtxgrkfqxv.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtszgvjgvv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtomogfdwx.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkllfmwx.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtapklpymt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtvsadcmdu.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtxmusssaz.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtlqwyonfe.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtituuehwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtnqbvrtpr.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtazhpiujj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtrwryhbzw.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtauyhldbt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtoelvapsd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtkbiolkge.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtqvhinzpo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtvqtkzxvh.html


<!-- 参考信息 -->