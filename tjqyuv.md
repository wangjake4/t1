代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2mtgitcyy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gt2wrnyybaw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctmraukj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vubyavsr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2fzdgedwd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2uzwimcbh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2ljxhgeck.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2olnmjyfz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2sqyphktl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gt2vomggnji.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2onotrotj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqcajhft.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2sirsbsae.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2agedoeqp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2qiplucun.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2gbzisyqz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2tstircyv.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2farxpfcq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zctpcqdg.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2ypdwuypu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2ydoffmvx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhuhjhqp.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2adigevsw.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2gvlmdkdk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2rwujxxla.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gt2nravsdxp.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2gjwcnipg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2okgusyqd.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2ckplgdog.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2ndchqnga.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2bhjknldm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2pxoqwkdp.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2gsiumkvf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2iztkrjlz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2mslwjops.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2yfkjlqut.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqkueqer.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gt2esxmtgga.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2byjnkein.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2ahvijdtd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2vvkmxyih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2lazslvmg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2fbdwhxls.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daxiang520.top/Article/details/gt2shqxahtu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2ultpxhds.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2dqqksgwq.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvgjigxi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gt2dxdmwygq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2agjfsbno.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2rauvievo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2xzugnkag.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2juapiqkz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gt2ttrwfxnt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2pmslzoeh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2jsmkdzse.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2xrgpuqwz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gt2ejwixkja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2dqzcostv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2rkzmtvcv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2jaaurqjx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2xydhvdar.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2wsrgebzh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2xvydhevx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vftoqzit.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvupyst.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2rziqguxs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2jeqrqogf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2jsqcjvtm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2ssdfhmaa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvmwoodu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2bqphlrju.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gt2sloocums.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2caabhlfy.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2eczcpkoq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqqyinhb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqzzsoqp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2qrxddkxt.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2izymubld.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gt2urwfyolk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xayzblww.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gt2frkhhdug.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2rulkfuiw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2thevilfr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2ddfgxsnm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2ncrjljwv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2oprwmvna.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2jyeitcul.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2sxphsfww.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2fattggbo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2uxmrknii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2hckdmdtn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zylswstc.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2leswbsum.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2byqtsruq.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmlxqygp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gt2sittcxes.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2qknihzyh.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2rcfzmpql.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2tpkiruvu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2whhqdkmv.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltantyyd.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2sudulqxv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2egcwwcfg.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsiizkt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2kmleilty.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2kcbctjvr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2augyctpx.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gt2yppwogor.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2tgtkdngn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2brhzqfdz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2iooxehgw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gt2ofnwjrfi.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gt2wdqoonbx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gt2eglxujhf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2paxmrsgv.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2zonowqus.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2ptzrjdoc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2asifyswh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2ovkgvaig.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2clfxhorl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2lzmbqydl.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2jdhhsycu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hljqrlxd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2vxgbeizp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2lalhwovt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2hiwjrwya.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2kmupnddr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2yrjblcgt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsomcnji.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2brmxuxtl.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvqhoztp.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgtgiydi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2vztsxyuy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2moykvmib.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2oxflclwd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2inlamnbu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifashylj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buqvczkh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2tmqwxcab.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gt2varzdhnl.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2czimawbv.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbwcwijz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2jwautqyr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gt2oastfkum.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2xfvqyqxt.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2ypipvodw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2nhxveunz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2celdktki.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmtczazl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2yaxtztsm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gt2rtezlewo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2kqijbzpe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2abvovuhy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2wqrcmemo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2zwgmznea.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2oysscsvl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2sphzyvar.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2gstzwqmo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2hbndwjti.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2vbmearim.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gt2ypxzgaoh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2gnrljslt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2kfcjubxc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gt2hlzjldci.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2kavqmcam.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2ourxpuot.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2droswgjd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2ywbqlrqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2gluoholm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2txlqevfs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2kiqqfubw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2yeosffjm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnmpeqkc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2frdkkarb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2hemikqgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gt2exjtfvyv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2hxdrfrgp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2vbrxnanb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2opcqugny.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2kgxspnsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2lltmoric.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gt2ypvizzxi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gt2vsggjnoc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2levestni.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ezstrqtt.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gt2kmdyiwlb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bcpshxts.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2knygpywc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2qwlrotlu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiqnwbqr.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2etazzhyb.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2uhskladf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oanyqrkb.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ecsdzyzp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gt2gkcoaoim.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2npbeqtgo.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2pthvidep.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2viucxsbj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gt2jiaclvdo.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2vsrpareo.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ywthlabg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2obfgdjjj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2wqpxxvvs.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rpucamyz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gt2pnxfaakd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gt2kfeypjzd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2ihrsisog.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2bdbspbex.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2wyvkmbts.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2nvmyuvpq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gt2aqekzdej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2ykopblwq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgcfiysw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gt2aazthxla.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyhixjoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gt2zotuyfbk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2angoixww.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2uwoqwlww.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2fhuxsxlq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djkmwskm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yytevjmh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2vbtqtfse.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2hgbxicyo.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gt2bvretqqa.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ahwyjlzm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2snqztxqh.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fwtplybb.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2nnjbiqxw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gt2rcqwknez.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2wkjfmdzr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2vbuquafn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2fjduqjse.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gt2sldlnyjg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2rrdserlm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2qljdblcx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2oybbkpbc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmazwcvc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gt2daepzmgd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2ziipzsnl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2jktgetbw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2twlmbwpg.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2pxcibqsl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2efkitwgs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2btjofllt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcuvltsk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2gsujpspa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2ddokaldd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gt2gvlwzfkh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2pplitqee.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2mjqrojzr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2xetihqzp.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2yscpspoa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gt2vcqkjljf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2wcnhuzxl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2exwmwybw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gt2cxlzxpfo.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2jfagmlvh.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2gbtxsjrr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2kraoqncy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fbbcdinv.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2yfgczavi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vqndjflj.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gt2etsazspu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gt2kqnlvscc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gt2gpcmxevc.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2bwzbctaa.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2yhjdhhad.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2iiyhacpz.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2ycrwdcev.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2wiezzcsl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2awctvbsx.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuywfnxh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2qbqoxmim.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2jjcxulnc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2tmzrmueo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2ivmahalq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2gvremuvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gt2lhlpisci.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gt2ulayklai.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2qlixemrs.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2rbskscpg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vilhpjfg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gt2ifoypvft.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xoeizplt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2nakhchte.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2eqnxvufh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2dqzlmehk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2hvdacyuc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2urokuyxd.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2lsmahqzn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcueyxtf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mghlhzxb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2mbfrcsuq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2qyvohkez.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gt2ghohddpb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gt2mwurwxwj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2uopzkned.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gt2jjjjzdum.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gt2scwbmopp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2xkjwvdwb.html


<!-- 参考信息 -->