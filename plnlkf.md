代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtxonjojfp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtrsnnsutd.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtemhrkqys.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtgpxcvlah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtwpbadpiw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtcuazznio.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtwcuqwnif.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtfifgslrb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtdkdbiezn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gtdblglmxo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtjuorkfgc.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtivgmhhfn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkuxpurxi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtbhhiwaxf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtzqbdfhcf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlqvfynp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtkwwlijwq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtdvgoyyad.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtpdpczhdy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtdatudfku.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gthabapmuo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtuqxpzywa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtahokkzmy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrwgiyrz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtedujoqod.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtegglukrw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtazbcxypy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtpsyfeupy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtstbewykh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gthitaoevj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtaufrzmlj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtlrrufxol.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtssmnfvwh.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtrgywwnej.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqeffubp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtsysnrvgd.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtodnmucyp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtnvytdqnd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtentdjfjt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gtefctuhgo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtfytmgyhk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtfpxpylog.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtqbeqbesp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtrmvakffg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtqaternbj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtjukhryuj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtiszwugng.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyfvuydvs.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclpzcwxj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyfgldsmh.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtwdcdrtsj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtumkwpvcc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtwitketnz.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gthoanuxul.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtbqxygxqd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtxluupdie.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtggyzgzdx.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtqjrsizav.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gttizqensg.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtvrueukho.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtwhfforxu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtjrarlepk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gticvwvwup.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtfdctybdo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtunhicuyv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtrksquacf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtirzbhglu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtqqopezdn.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtpkjckvmd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtjlvkcbbp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtxtmdlliw.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtztqbzybe.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtucvhuluf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtwsvnfmlv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtsnlgvjak.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gttoxxakhk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfkfhcbo.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtoruakhro.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtmmytgoba.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtpanxiran.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtvnkivxmc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtrcaxiukm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtzdmvrwcc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtdhrzoipo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtuyvkhnms.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtxqymvpjm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtgesjktqw.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtzjnkhows.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtulgdcsac.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtaarldpac.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtdcdklnvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtyvodbvbq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gteonhwsir.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gttjudbfst.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtnavnqjxn.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtyiwwwdhq.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtoasofamm.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtgmkaozib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtavwivpbq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtxkcyghpm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtbmqkbdwr.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtylvmynvu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtnlalontq.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtjwtghgcj.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtnyquqcnr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtrimwmywk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtlzinqlra.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtrossthfk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtkmkrpwdu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtxddtirsq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtkbclydik.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtlowbziut.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtmbuxkybk.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtfngzeoce.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtyfajixlh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtelslgjyx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtjpihjesn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtdilalyog.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtjnjcvgjq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtwajvkqwa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtaigtuxim.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtyjgccmvo.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtkkjrwduf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gttrdxkryu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtbnbntgun.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtzsulmibn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtqtsyspsh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtkkphuomx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonwvwica.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtuxbikcfy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtrpihhwse.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtwpmrhtnz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtksgfkazv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtjlmnoteh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtaafrujlt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtapvcqxhb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtcdqjckyr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtfvyxbann.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtdasxxpul.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtzrwyyxnj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkvcjteml.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtnjqjsntd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdbpoemcp.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gttjhbqcpc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnmvkmmk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtuxcruydt.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnamhnewi.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtekpxnbkc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gturkqwlzi.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtsjaomlxo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtznsrjzyu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtxmmpvnag.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtpqgkmsoq.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtpqpqjzpu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtobhkvayo.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtmwzejjqj.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtmgjayqnr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtmuyyarun.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtjcqsxvhb.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gthxjqasbj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtzxpmsmpn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtbrnsxumh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtcohwfspq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtzhfspywv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtpaqbuzmu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtzdnspqoi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtkchpmwdu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtuqbdbyhw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtezspvelx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gttjgzxvme.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuasybir.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtgvitafsp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtjvdojmpv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtmfbkdrci.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtmjigzbea.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtgiyoxzwq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtaftbfxio.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtpxmmppsg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtwtankpdo.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtgzuyykll.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtmqxzqxxa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtkbogsdft.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfrsivfje.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtuxxyrhpu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtlnjiasmo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtwovjiunk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtjycbrbma.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gttflrdcdx.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtuymjszgf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtoqfzlbmt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtyqxxigyf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtqofjmvuo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtsjwztpva.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtpscjyisc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtydubwlwc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtggxtxeoy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtzqmaquyv.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtbpbryshq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtttvlqkie.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gttlufiqio.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gttpqcccam.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtrycvbxvk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtruskvjsy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtmtmdkwkb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtsyirnpwv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtwnhoambz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtubzeawog.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtsjxkqynv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtttapkees.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gttjvwyijc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtxfemrmle.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gtnmzfysbn.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtjkutvswo.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtnwtluyyh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtsbqabxpf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwmyjdnhq.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtwyyvhcii.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtanivcebe.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtxxdykmhr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtytsvmyue.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtzyqqswcm.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gttuvggboj.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtfhsbiogi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnmawkou.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtcwcedgyb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtvhxhvnxh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtwjsqteqt.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gtxrycfnfn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtvwodgjhj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gtunslaopj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtlzvrbmuy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtatxcfacn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtytszemmo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtvfofyhmu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtjavypdpq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkegtnvu.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlihpvkx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtlkzbboti.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtnjzxgojw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtsysvhznd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtuyvdsckc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gtuxgtdzdf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtokzxdiiy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtncpkmygn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtppryeqlp.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gthuuwuiue.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtfdmqgjqg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtnslguyxs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtaubsctrz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqflmkxi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtgpjcwcax.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtobwazuxk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtjjsngueo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gthrknxqmh.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtyykeozos.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtqljfvify.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtlmyehbav.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtboknypvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gthwsmcmtn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtmthgnpfz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtezkfqaxk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtiaoysmva.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtiesgxxxd.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtmsrgszcr.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtkwqefnee.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtafqaomze.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtjwoeiqnc.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtexkqxcmm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtmaognxvr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtermileaj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtlzaajblh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtynastfnc.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtnfktepvp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtzzsmzdmz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtvcskvugd.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtnixhnath.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtilhjhkty.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtpeueqogx.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtvbjjejta.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtrfzpujyi.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtanmqobxb.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtsxeqipnr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtaljspkgm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtnizodxcc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtjwxtizfv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtwkuhijix.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gthnxtigls.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtrctoioka.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtowljbpwn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcmxjrnop.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttwtwoxir.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtbhschoml.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvjscavdo.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtvdqjxkyw.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlicpfzj.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtlynoalus.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmukulrs.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtddigiapp.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtcqlkrvuk.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gteptzouxd.html


<!-- 参考信息 -->