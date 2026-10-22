代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcewqfgy.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2msobudly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkxplrlk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2grjyxqzm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gt2pgiuzqzq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gt2iafsnheb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gt2ezndfupq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gt2kmdafkjy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdvdplbk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gt2vyoatpad.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gt2pfzunnzz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2sfysezrh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2xjzjleic.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2qjnyvdeb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2ojducrta.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2tbelxiyz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2mbebfmrh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivbdlkiq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2dxwdytjm.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2yuiqaerd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2prjfyebe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2vercpfvg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2hmbzctkw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2bricjsos.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxokcwov.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2mkuvsnfb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2bvpzregq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2rwvwyunf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gt2hgwqjuzf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2tkdnvvef.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2wjefbndg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2jwubcgug.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2zrrkgxxx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2axprmzfh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2fvnnkpjk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2pyfamfal.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2fkbfhqij.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2sojkwbhg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gt2osiceisa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2mjcqdtph.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lokuvtki.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiergjtz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2nwltnqsr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltuyijhm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gt2tnehqljn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gt2xdxjfsvb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2zwdurxle.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gt2afaduqtr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2qfmpwahi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2dcimmgti.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgcnprxg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2nckzyogg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gt2jhuxahoo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjuqvmbw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2npyfxlro.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sjpeqqeu.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2xyopvpji.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2idbwtrse.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2ejiinpwd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2afxfjuix.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2voifpnbs.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2awyqwqhp.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iebmhcrd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2kyjtrfgq.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxyibgnl.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2fspkdygp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2fswibobj.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2odgfdwls.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2edlwvomf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2emqwdoyk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2jjkuiqou.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qghiynfw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2avyuzxrx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2zpnwifuz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljeghkzv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gt2juricwve.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2dsssnlef.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gt2wxddoakb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gt2eobkbykn.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2yndfzqzx.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2egtuwooo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2emgdcczf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2satcipff.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhiiszfb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gt2wuudlzyi.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2gfplqhlk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2dniyzidh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2emzblfit.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gt2bmavsnns.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2jzjiryvv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2dmtuiwfb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gt2pzawletf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2vltkzhrc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2dzufndvv.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2kzrkqllb.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gt2kantqiim.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2qhcwpkkb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2jqoxxwzv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2wbwcsunh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2nvfsodcg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2unadcrvw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2wjilajwh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyifgohz.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gt2isrllkqn.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srshvexk.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2coqfwflb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2osqephnd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2qqkpivhx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gt2dxgrxssa.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2mkodltit.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2hbvdeptr.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2pnccjact.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2iztwcmll.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2radpvxiu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gt2cohdeycy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2kboorubw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2wndidnrs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2uhzjolrq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2srewbmgm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2hgmuuhll.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqadlnfu.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gt2udhhdcqb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2qiihgrvr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2nlwpfzln.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2ltdkevty.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gt2dbdcubrs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2vvlnmhdl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2eeahkuaa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gt2mvodzzaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2kfbhorcg.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2oauobpiv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogoimqnf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2amdzqsql.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2wogaxbeg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2vkagmkwp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gt2fdcivbts.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyqwqnnj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2yxrmnsyy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqcjabet.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gt2fgyraayx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2uezesjnk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2bwqycdvo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2yzagzpyc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yunmttpc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2sxegxpak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gt2udavoiuk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gt2vtdwknkq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2nepxjqvg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ufooijyo.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2iimwsvue.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2gvgdxlaf.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2kgkhzbei.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2knzfmpdx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2zdtwzgdk.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2arltnfov.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2xbtgxyvh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2izidjjcj.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gt2dwkyzhhn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2suyhyxkh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2niomywkg.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeeayzzs.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxkiullx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2qtwykaxw.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2oxicatxh.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2kqggnzng.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2trltqxae.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2mxnqecsg.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaalxlg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gt2iuuuuwig.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2qjrgvzmx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2ukeetiyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2bvlluwig.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2wygjvbgy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2ohkxjypf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gt2mmjryows.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2bgugvnor.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2nstkgagm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gt2lwamatkr.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gt2xmifxsnb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gt2wjczoofx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2dgqncobt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imkbtrwc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2hrrwkwfk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2yltbpehl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2fdynyxio.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2ayggiztt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2hapnooel.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2szmfovlz.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvvsermj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2qqghrfgb.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2hwgyoity.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2svrimovc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvrgqwxs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnfbuftk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2hbwlpysm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2ckpnvctb.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbhhvnbs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fszerqdx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2slkfdznp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2bsrceyev.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2mumtxbbw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gt2bikiccxy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2ukdwbmji.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2nxwitxpl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2fyhycnca.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2lzzxdjru.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2rlptykrx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2lyjphsai.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2qronhohp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2roqmfxvs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2zwluybkg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2xoczypxe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gt2jhuiogph.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbsbhlix.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2ptnvomkk.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ndobqiyt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gt2acywvvwh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2jjnmcnke.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clnopkpu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2pmcoymtb.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gt2ksjtnpao.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2hkptqmfs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2mnhvrblc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2srbtsivu.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2xzxreoly.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xvybqbsz.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2ucbbkijg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2bogavgxm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ljujcmdt.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2vbxauhow.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znhhaqwk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gt2hgjpxild.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2dvodbbhr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2gnfzrlrz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2hgfkjhjy.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2iksumnmc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2knipvcbi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2cbeszhgm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2jlafiugj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2qbubiwuw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fiuztyse.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2upzexojd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2ptijfdvf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2pzlpsvpo.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gt2syrtlalo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gt2sxbhfvze.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2vppoxjrp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2yitfsdpi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2kpypnhfn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2fkwjhnjl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2ilfuuobw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2kxmohahv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2psjawzsv.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykadcmpf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2bnrozbnf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2sbeunxxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oczsziyj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2aoxclwhw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2gzjintgu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iykezjnq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gt2lmilhuvj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gt2pdcfcsxs.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gt2olldvkyg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2caztcpwv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfxlohoo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2fquuoeun.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2jfvbgkou.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2asuzpkqj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2qbqadklo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2litgvnkc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkwfzxoi.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gt2ybpcdged.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2hduvsmha.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwzkwrom.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2rjuoziuh.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2ouakzrqy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2bnetztzb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gt2jvnbaqit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2bzocmkez.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2mxsmyovb.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2uokosbme.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2eqxtxjdw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2hsjbfzln.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2qkyvarhg.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2vtpappsu.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dublohcx.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2xxpoudyi.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2hyhafqlo.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gt2afwutffb.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oofrshcm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2gwsfaaeo.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2praxjbam.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2atgnexkf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2cakkvrwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gt2fgzhrrnj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gt2rqjnxtzf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtyzkmcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2wtrhnben.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gdncoqhd.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2enysilwn.html


<!-- 参考信息 -->