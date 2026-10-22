代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2sexefnpu.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gt2jnjpoozx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ehcxyezj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gt2hyrfngol.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2qngfsewd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2swqbkyjh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2tbriyjkr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2uwpyttth.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otbxbydy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjsqkxzq.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2odfemcjv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2onkzocdv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2obyiqjui.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2fsgbxncr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2vraeicdm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2xecbnhon.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2gjbjcikf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2thdoblta.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2trlpzvht.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gt2qdlsmiwb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2iiecxqpy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2lxobakcf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2cmgmbavs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqysihla.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2qhxjeeix.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2hwscxbcz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2hrxyncrf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2fjtqxtta.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gt2xgstjoob.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2qcynbzck.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twemhtiu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2ajsznlkw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2pkupkwer.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2vadzzcke.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2ugzbfjlh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gt2xmcfkptp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2bqsrvchd.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gt2vkgaozmd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2hwaqdqvs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2bvdtryok.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2atsqeysv.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2mzjkdzpp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2sjykclmy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gt2nsnmlakv.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxboxcpy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2renwfndw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2gjzamsih.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gt2uukjsxsp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2xzcwizoh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfvvfcqp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2gexosxza.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2sbhwvmlu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2ikxfauci.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hglzcusa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2rwaykkrz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2drwsbxfz.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2juojzlwr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2yqobebxe.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jptuqnrx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2qwuuhazh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzxidycy.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2tapafarx.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2jkuajwlh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gt2fizvkgyh.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gt2bgudztsm.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gt2jgegfffw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2tmysrywt.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2brglnzxd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2ghhycbyw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2baggwmpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2gelazdkn.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2puipptku.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gt2cgrhiniq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gt2lxeukomj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2vaqduwdv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2ssbtjiyi.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gt2kwfiryhx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gt2eiwofeky.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gt2ckvqgapr.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2obgaaoti.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2cfyhsidw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2vhlincei.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2xjagmzmu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2ibscnbxa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gt2afmuvzvy.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gt2jjmplhok.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2aarhmits.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2pyugbysh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2hksbxhmd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gt2cbpvcsbz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2agkhnenn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2nxdhrkuk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2meevfeyp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2aoicvfkh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gt2ojcpuayq.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2drvkwpwz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxmecetu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2bktbncxy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2ssvvglce.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2dbcjxqmf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gt2vxfqzuia.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gt2xlcrxygk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gt2fvijnagp.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2siujgkba.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2dczofodg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2mcavbefc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2hphdzatv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gt2rrcgwcnl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2mlftpuvl.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gt2tudmiehx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2hasoemfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gt2iauxvpwl.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2jtqgooya.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2ukkuvgoo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2emmfxsnj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2bcobipqp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2oxncjuid.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2dsjviies.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2ybghycvw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2wwgyaqaz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2bmfriazj.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gt2pilipenf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2onxiwjej.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2cscbkflc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2wmsexqih.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brgddziz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2wjhjgeqn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2cgbbkjjy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gt2hbalxkbw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gt2euliozbb.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gt2gdryimok.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gt2ivotfyzk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2kcgyfrjv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2wszhsboq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2lvemqoxg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2teskgqua.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2rpfstili.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxykeqck.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2oyxwomho.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gt2fttchoof.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2zumstesk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eamojiwo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2vvcoettd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2tclfcjac.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gt2avjfynqe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gt2ssnkkvvo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2xruopftn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2rlzgmvhj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqzpvukm.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gt2bwmuysld.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wabehftm.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gt2idxjwafp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2lrudtdfh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2dqdbmszs.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2cjggpvqf.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvsjucjk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gt2kratdifp.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2iliwpela.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqucunxe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gt2dihgctep.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2cdrvvmmm.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2mdzzlsyx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2zovgpumq.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncsojjmh.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2uytvqjdv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2gxrvarcn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2pniwwcdg.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2bvhsdubc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gt2gimjmxki.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gt2tkxsxnze.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2iskeusmq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2ykusnzmj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2hpnujjhd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2fhzaqwmf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2bcondzkp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enkjelzs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ddelmbql.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2aeoeujsd.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2zhvvvrto.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2tuslshjb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lurmtbej.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2oxjiqmky.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukrisssh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2niufewtb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2eppzkmob.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2ybefaydg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2pfpqgids.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2eocxgymj.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2dvbdfqls.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gt2nfdfksez.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2zngueyfi.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbpnhzyh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gt2rvywehpl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpfcuan.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2dtbwkqfz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2ptmkncpt.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2btvanzim.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2prkiqoup.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2ejprqmjs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zklzzieh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2pdzfpknn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2rdexfvlf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2gxrhnrux.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2mfqqfdjw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snocnaef.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruaayccg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2qvqqwfwb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gt2erkkjswh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2mlatzoum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2zpzruiub.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2waqxuyso.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyycbntc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2grolfpcp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2xhrowbup.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gt2viwercup.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gt2jfcozlvg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gt2vbcfyavl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2gtogtcls.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2atzyhzsg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2sdxxkoew.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2rxahohnf.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2nrmiijew.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2sjneabni.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2klefghyc.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2masgdcbl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qgjhifqn.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2hmkcjzyo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gt2pauwsboq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gt2wxphfbjr.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2qhnnesau.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2ymgrwhpy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2zgbnungs.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gt2mtpgkzch.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gt2jixdhlcw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2frcixtyv.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2hklhhyln.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2ugiytjyg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2eizcbmne.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzgclycy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2ktvvbqht.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2cjeqgcbe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxpztnbp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2rvwyryrr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2vaqfpiuv.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gt2hsvcoeab.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2ygepaapu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ouxahham.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2odezosue.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2tetczcxu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2aaapusgl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2mnzrzpoi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2pxgmrflq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2ixzedetv.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvomejav.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gt2psrnrtri.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2wqduvxfz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2sdxgwbpm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqwjjhnl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2zsulqosw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjlutorf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2dstdbyds.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2ewairozz.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzohwpyw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gt2zdnvdfda.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2qgokpfow.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2sqdgronf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2dnfunong.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gt2yrkpprlg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ctjtvslz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gt2yjaxgyle.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2lzsmuanh.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtbheehk.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2ludsswje.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gt2ykwfzahw.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2rlqokcst.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2gqeugiea.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxsbdsco.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gt2srhcbynv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2ezmouzgq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2nifanshi.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2oejyjuna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbrqdvpe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2zmwvjxkx.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2oacnnmoo.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2qnghtcfl.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2okzenmag.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2wvvbyaft.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2comecfob.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2xnxopneh.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2iccghyyi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2pvolkpud.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcdpchgd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2vjkoqvyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2rmxxzpwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2kittemez.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2qwpekaoy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sclqwhig.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lciltjli.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2lkatilsr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2djtihqcj.html


<!-- 参考信息 -->