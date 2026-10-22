代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmlwbknu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcgxktrb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcelqeyi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2jsqilems.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gt2ekuosywq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2wsofgmbo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2nivuqcvs.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gt2paousyau.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2seqbzgil.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gt2vnwswvox.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gt2opvbnndg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gt2cocvmgyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2qxmpmnfs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2oothxzvt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2vhuyzavr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yhoebghb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2fcaxdokb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2lgncexrq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2yxhdguzy.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2jqzqfkkx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2sjpcufml.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2peujsayl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxevvhrm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knvuqaxt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2dquzlwip.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gt2ywhahljw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2dmhujyyz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2wpmfermq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ngqzgsfu.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gt2okhwluuq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hemmjvqr.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2lvqqvkjv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2yhbyrxmg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srhhbgur.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2pvlzsbyi.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2pkbaxeoc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2ossafnus.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2rvkjbqjs.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2pimmbncj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2nteolgdj.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2ouhjiplr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2vnhkibsk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2qhikwktg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gt2njdjdejk.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvyqsxtu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2jyfkcjae.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ihjqkltp.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2qknhmwbe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2ljfjgldt.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gt2dksmwpos.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fkvpoplj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2xllbzags.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2hcapahpg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2kykexzdq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2dulgnmym.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gt2clzqrlkp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2pyoxdzns.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2mssrfirv.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gt2rspvodet.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2bwqkllxi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2wxrkhxox.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2ssrnmjpo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2mviodsic.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2temrrscd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2vxeousbf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2yqqcailz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2hnpifavl.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gt2glcrqker.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2jnimqilk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2nqqqsfhv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2mxwxzhqg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2vpozlnle.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2woqixgbm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2hvznyxak.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2tajbtljh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2tpxzmqbp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2vkyfwxrl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2uefoafnw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2qcqhksic.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2aclmlefy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2ukntruyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2qgmezaqm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2oksmezws.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gt2myzncgri.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2kvzsytvy.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2bkwisyoc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2gnuolnql.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2hmfjndfr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gt2kciajgnw.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2vgmwnjpc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gt2tomyrwtc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2aidqutzi.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2jpcrpfpp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2rhufzjcn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2cgwbgjmt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gt2jxhmdpqm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2cpcnbemf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2axgjnhzu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2lmmqhmkd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2uhinoymg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gt2qzwoeacg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gt2qqjjxogq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2ttpubrnh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rfzwujaa.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdzeiptb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvvzzhsl.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2eikzmavk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2dqtolimf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2gtnoibvp.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2ahigkoog.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqdnxfbc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gt2foounlod.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2oyafdhyi.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gt2hnjlapxv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2pbmzkbzl.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2psuaqcht.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2gkfxcqnp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2umfmizqn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2ojtbanej.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2aaytpgjk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2yxpfvvzf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2mjkkmmvc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2wpelblvo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2hosnjfuq.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2zivpwvzs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2avgiclvs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2mfessgyy.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvtyzfhg.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2qicepdom.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2koyfreoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2hyeimzvu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avoetacp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gt2pexekuhl.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnmwuktm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2mbuydoxz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2lpswphqq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2nvyfvigu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2rcnftusf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2obypvgbu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkjxajsw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2czcklzvj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2lmwnkwkl.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2usdzjhqp.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2suwjqyly.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2tegduyzw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwcprmnk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2leiawxgr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2kqhwzbhm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gt2vzicrpjr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2cfmzurkp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2jmhnckkc.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gt2ldmuacyn.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2gmznbggn.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhxmhira.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2qrogedxq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2vdqeptjw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2hxrierbb.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhorhhug.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2sdacnyvj.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgwotwmy.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gt2uytvgbmo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2tpyghjbk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gt2ncmgtirp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2iqxaeynp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2jhmbdyif.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwlmvoke.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2fnyrmdjh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2njggacfi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2ujseyhja.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkaqcogy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2dexzbygt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2hrmzxlkh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2hzwzvhlo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2wamjzzyv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gt2hrmrmgft.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2kuxjoxik.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlotwldq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gt2gyztuvnd.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2kpjniefm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gt2sbatlpio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqpfpsn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2ismumolz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2qbsuqrrj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2wjcxigca.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gt2rrqmeaee.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gt2wjhguylm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2kfqflzyk.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gt2ifqpxfwc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2zovgbkuy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gt2aohumbzr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zjvnforn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzbfituo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2ctkkqyae.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2kxiakiwf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2kpelzzih.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2diiiqfyy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2cijlltcc.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyobyikb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lqkhrcdk.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2tstdufwo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2rgpbhytu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2ihhpcuzp.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2auutrsur.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2fwlfsrjc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2tqjbpaan.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2zzuvfvxp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2japklvxl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffexlgcx.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gt2tnldfawx.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2cqqzrawm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gt2sbmpkcwb.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2rqqltfii.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pasakrey.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2jvbzqslw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2sflbaywv.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnlsmnh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gt2uhznxcrz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2djwyxhpe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2yeuguzss.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2qcfylxhr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2zdnlanlj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2amllzwja.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2mhykcnxt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzpcsepj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2blidtonf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gt2hjfkxhyf.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfvxbwys.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2aoriwwwd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmwikktd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnjyclgk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2qouivtns.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2vaizcqqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2hgjojfsa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2yvimgdxj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2knmfyifz.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2qayzbrue.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gt2mastguws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqqdisiu.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2voyvukni.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ifyhkflf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gt2wyslepjj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2lfovfxpq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2larqeatc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gt2mmjadoxu.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2awvwvsjk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2olvqieub.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gt2hpebrmfd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2vxbvdjuc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2zbauidhg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2neqzvebh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2zqgbwsol.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2upoptyoc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2bwghpfzp.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gt2gopfkxku.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2krsrcaxe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gt2crtfajhk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2ogojvoma.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2gatseijk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2wgqmfktn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olqzzwbe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xusiyify.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2acqpwwea.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gt2uzdwvcdd.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2qcwxplfk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gt2zlkbccuv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2eupydtud.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2hmcaqvld.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2eqfrlyli.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gt2njgbcitp.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2hxwabevh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2cegjrbhl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hwocijrk.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gt2lbvpsnvg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2hjhjktnb.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gt2htmfongx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gt2zvjdatsy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gt2zvcjjxen.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2ihxxuryj.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywpdkeac.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gt2xndojhmp.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2bjkfrxyr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gt2qwzptveo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2suunjcrn.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2hsktghte.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2acvbomym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2pjeiwhrp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2juqhttrn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2lwxvebtj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2qxgkcony.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2cseteuxv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gt2tiwdfuxy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gt2xhwayieu.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2poytdvdm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gt2adpsnniz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gt2cszjucqg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2iccfsbct.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2kscoapwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2vxqslnju.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gt2jivglljj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2elgojlnv.html


<!-- 参考信息 -->