代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2hkrdontg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gt2iezkcdjv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljqdsmlc.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2podcojhx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2smcrqizw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gt2fqomhjmo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2pidqvhsp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2vizsblav.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2hvvoewdu.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gt2aqwzuuoy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2ubodxpmc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2kbxaxyzq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2rkatfbmv.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2sdcuqsda.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cgvjbvpg.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gt2umdhzebx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2wttjreka.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2rofotpnj.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2vhrxhvue.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2vlnqjtvl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiiayfym.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2jmepfloc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2advtsjnd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2nmiaxcef.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2yqmkdzhk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2bjuyaoxb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2cnjkvpkh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gt2wxbjarfb.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gt2wyyjtmyr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2gntyrfnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2yowhwwxi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2etrnjmbn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2eotktfry.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2sdqrdzcp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2pakicecr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hheolmyt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2rnwlhzjy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcrelhvz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gt2ajdavmyj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2meyinzkc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2ibfmkijw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2pfpxyyiz.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2delkfxac.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2wfvrsljn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2dtzwichg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2npvckrbu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2qyvxoasm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2mxmvhhvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2ahotbejf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2sbjltlzp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2iuynozvy.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gt2arssqbik.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2umlpjljg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2jdtrixmn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2xktshlfu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2vozhvwie.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2fqbhbzbj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2cgipzjcr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2zrykpzrr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2kbeozhxq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gt2wtexgflh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2agdfhcwu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gt2lvpijrdq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjmdzjlq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbnkbrhy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2lcbfamnf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2hkbrjtyd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2ijvhlopk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2qnmbnemh.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gt2lijicpma.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gt2uldyuvzy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2jjzdkzwv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gt2mmcnoxub.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gt2mwxfutas.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2pefmussl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2mfgyrmxh.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2dxybawfk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gt2isilqvdz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2bxrsovpw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gt2ixxpryby.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2mtrnhlwl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2yueciswq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksothvft.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2nfhboobm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2yplihhzp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2hfokebqh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2gavwhiaa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggjcfrly.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2pparrtdl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dbwgsyhh.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2ysgnmjtw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2cqwkbstw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2boeayptb.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2elrxpmqf.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2piqhevuo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gt2rewizwhg.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2djeqvybg.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gt2rorwsuev.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqynzhke.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2dboqikfk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2cedaofkq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2ktsejauw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxqmskbj.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2llknympq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gt2igttxzux.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gt2dvxvnysp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2wyoakfub.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gt2fgcskjmt.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2qhugglib.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gt2viismaik.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2avisgmcy.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2hrlmfbdt.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2qjobfloj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naldaqje.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2umvsbplg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2ijsytxfn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gt2vjgnodvw.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gt2ihaltucs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2kyxeuhcv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2ukmeuboe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2fqgztybo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2skhdovwf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2wnrfstdq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2bupywptm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2rzgrbtra.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2lcdvdltf.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gt2zipwivli.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2indbcvec.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2sculmrhd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2uxhiatwk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2slvfaptt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2fedttwgi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2fqtcnqfz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcgjdog.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2cuwgxtjd.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gt2zreovtnl.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhoqqkxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2ygmawefs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2hkiyxgeu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gt2muwpjbgr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2trgtyxky.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gt2yumiamyn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2kdogaptm.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2lhqjjqgy.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gt2vkewghdo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbtbfpfb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gt2iddttics.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2cqvhciii.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2pnqtrubl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhvhhpud.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2jbvhckhz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyetgnnw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2snigiifx.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gt2ykrvxwgl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gt2npkxfzbl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hctisllf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbkqymhq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2gpuuabgj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2nbivqxlt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohtgvrll.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tztyxufd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2kcxvjjni.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gt2mtsdpafl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gt2crqptakb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2uqgxgpge.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2ppklucjw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2gigjmbkd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2bsryhyia.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2mqqnbakx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdtlrjtd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gt2jmykgrbk.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2urvzbucw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2hpyxxpfo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gt2belcicyy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iypzufjl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2rjbtwtgs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gt2xjywexvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2uemzouqy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2baardtmw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2nganilue.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2wwevmifn.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2aphiahlh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tboipius.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2qhrgafbj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2cmnjruuf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2lcrtoemx.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ccxsrqvc.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2ziqjwotr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gt2jteczltz.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2xyigdoou.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gt2xjzmqqep.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2qmsqdugb.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gt2dhezrmgc.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2wlosopvc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2emnxmibi.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2dpgdabrs.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2dmedphuo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2nhwxrwgj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2lcvzcore.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2jlyjiwoc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kehqbpxa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gt2gyewpoci.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2ygdjexbl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2asmqkrxh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2xhngmwqs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2twzppxaa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gt2exsyzumx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gt2qbumxkfz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2fsotfgoa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2xbqvrzlo.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2eyjpafka.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gt2wmfypvij.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gt2ujwfxcsp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2yomuuksp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2svyawcom.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2ocrnpkcz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2rrzdvues.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbouowra.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2sctfehem.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpculkex.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ykmisnji.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gt2cwkwvvfr.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujbgguns.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2woolblpn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnpjfbpq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gt2wlvmmlmo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2ztudivoj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2dosfnrzm.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gt2rqyctcbb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2dobwyrgq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gt2ozopmtrt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2orbuvpxj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2wqllfgfb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gt2dcvtzyvk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2vepxzipw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkogazgz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2hgyhxdrf.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2gujqnnou.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2bfzvtvvb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2spnslzon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2flxtoipn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2sekmzsvs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2cmvnhqpw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2awjyuost.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2bkzpzcgp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2ttkwostm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgkscmxf.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2nzfqaout.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gt2mweqwyoq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2jkowhhhq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2udbrfimd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2hvokkear.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gt2pvrgxyoh.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2uyawnmfn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2aeysqtpn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hzjsxohb.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2xgzrzvhd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ogypoccx.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2ouzrhuuv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhbrqvem.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2wpjiucaf.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2barfclad.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2iojwdrnh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2zswsoijc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2lzfffhbv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gt2olvntwrn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2yyjaphht.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2vcnigddl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2oinozvfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfsyfqbi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2xpxtesjc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gt2qovzmjyr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxkmahjf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyzabvwl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gt2ahtzcxut.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2rhlnjyhl.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gt2ndarjvtr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gt2wdycqgur.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gt2jwlzxdru.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2seojghuc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2jpzkjkib.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihwprykv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2jnkuxbsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gt2bhkdhxvy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2vewcqtew.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2qahscyry.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2kbunzyzl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2gnluzrvo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2swwjzqlc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2nnnulxuy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gt2usbpyvpo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gt2cdqhlkdh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2xthsjxbk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2bhqjwajl.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeosbjxv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gt2cyobhftt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gt2btwfsaff.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2jkrjebja.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2jsnnxctg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oujotgna.html


<!-- 参考信息 -->