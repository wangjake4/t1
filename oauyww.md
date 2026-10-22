代发 wailian999

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2dxmlozzb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2aleubwqa.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2dojwgbue.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fejihurs.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2esyvhjrd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gt2mgehsvqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2gsjrijek.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2fnexgaze.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwaatebo.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2qhwqidao.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2zgjgwqki.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2qpyttrtz.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gt2hhtlrndp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gt2iwnldrpt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2bzbzzhth.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2ifqjvbax.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2hdnnjjzc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2fuxofssw.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2lgpbydhr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2louopdzy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2kxmhbbht.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2qzhcytrh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gt2zxdajrsm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2pqpyypdh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2ppvorqdk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gt2puazfpdv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2zwdfysqi.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2lffmsjlj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gt2uhcwxknn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2bfiyqmkd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkuornff.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2uqtfrkvh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2nvgjpopl.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gt2cbiaemzd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2lxyyqwwc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2svookhou.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pfitcxht.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2ueawjjud.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2otzqhqpk.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2oylpytck.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckdsovhk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2jrpryjne.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjigxhc.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyzzpbsk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsloghbs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2qenapjjv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2xosewfdd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gt2jfcrkgoi.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gt2lxdrbtff.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpxdgjkj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gt2txmhbocv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dububkof.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2mklhslzf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2bpmycwdr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2dowrauai.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2tgtrhlrz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2qxdhjxey.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gt2ovfzqpux.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gt2gvpfdomm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gt2rsmertia.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2wsddnuif.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2yyyqftfn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zynyfpeq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gt2yspteamr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gt2rzhegmhl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2xgqtkomv.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2cwxlbump.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2wdnvvsjq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2ltshbisr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2eoexzayy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2hdbzfpeq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2riscozyn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2lhrayhbt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gt2hhuwdpbj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2jschtgyn.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gt2xknpnlby.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iojfmwgz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjkgmcou.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2yckqwthw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2wkrqpbgh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2yxprvzmg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2tglrgacp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2mnsnvmrg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2zydodrih.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2aiurhfnn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2svstmvqv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gt2udndddse.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gt2jfyaxxrw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2ruxnpzhz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wifwjjjm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2ouruutdw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzbtedha.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2zijpxbhc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2odzxttuv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2ymrvjner.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2yekwjacp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2rjunqqhc.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2woqukftt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2rfwkxfln.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrevvvmz.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2vfpmzhph.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2kqoftdgm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2dnfxujnc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gt2zciwakjo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2jcdssuuz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2pzjdneji.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2daoovovl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2kprgmkbh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2jdibtjep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gt2idhsknty.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2fnhglwdl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtizgmgj.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gt2puwlumeb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2tgnpsqaz.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gt2bqnuqhzj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmyrsoyl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltotmetu.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2pfudvqay.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2uobseqxw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2xwmyhpzl.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2adrhgakj.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gt2aivcqgxa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2khmprtko.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2hsdrheqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2zhczyome.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2esxnbpqz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gt2exzjohfa.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2miyrcxun.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2hnxxkakp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2lkhrxaqn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2pzkhguvy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2ffmxmzgs.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gt2xmboktwr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gt2upvabpjs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2nycvjrdz.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2xjjsaqgn.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2hntspxbn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2pnjzvzfv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2apblqbwp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2mxuacice.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gt2rmakkate.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2kkdjfnfm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2iuoipeav.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2hacdnstx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoeaqfwn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2wjxvpyxp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2tvmppscy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2jelcjexs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bavzeldx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2ysdkjtxg.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2zyhbmzkq.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2iievtczq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zssgdwdr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2qbgeaotz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2mrjopbjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2zwxtifxv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2eumnopsx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2cozwfvol.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2jbjnzakv.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gt2xedjdqkg.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2gcypnywv.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2baiwejms.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2ttrsyvgt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2kabglolm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2omrzvyxu.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gt2ckpdqwyw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gt2btdmlvjj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhdxhhkv.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxgdoztf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2tutinnfl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2snfclvcb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2ojqrvius.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2gjaesbqn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gt2yphlbfpj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2uxujzrkn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2zudphqwl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2gubnwapr.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gt2peyeovux.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2abqomsrb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2yosvltjp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxrutcqf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhisczuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gt2rcvygnsu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gt2edwmqhtp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2awavaarn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngpoiebp.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gt2ygnfluxx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2ntzrcljk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gt2tqbeykdp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2svvugnnc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2xelnajvn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gt2vjsdkrdc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gt2xjkuyrfy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gt2mtnsixge.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2lndbsgmu.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2pndjdscu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2hspiwloc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2uhmyxktv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2ggtdkxqk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gt2qbpsqfbm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2mbrpmexv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2mbzvdkyj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2cdmnnofy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2qboxljgn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bwtgxras.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gt2kxnfdgmj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naudvthq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2cxgecdrn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2nowyiaxl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2ijzajnbr.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2hekqcgky.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2ehqjdxsj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gt2pfftfpof.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gt2aaatqpqg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gt2nvpxxbzf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2bhwdvxst.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gt2rialdnxd.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fngjvjxy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gt2ahjzjufr.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2bbjvkwtr.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2zpocphim.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2tzfbfuhn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2iqgosvme.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2zzfjotbl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2rkxagwfl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2pqomfqfp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lthpywik.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2mfgkadxr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2lleqchsw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2qrmwylmi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2fbsdiwyv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2xuildhhy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2bukukelu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2awbhkdqa.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2wbxneeds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2uwfedcio.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmfxlvmn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2snevvsac.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2qrbrozpq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rckafxua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2eqbehexc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2enrfyfse.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2mtacjsmb.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gt2qdfvblwh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2rorlszpy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gt2cpgbcksw.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2zdklxewg.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2vejtvhxe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siexnvrf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2rlycvyea.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2sraqnqzz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gt2ekzxttls.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2opijstoi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2naoxfhjq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gt2tfnarhae.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2imlkgxyd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2iaiggvhk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2frhvonof.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2mhervawp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2zhixwfof.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2fzcahdvw.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2wnvuxkbg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2gykduauc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2ipxbwfqv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2pknflhjb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2ticzgstb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2fxgdrmvd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2sougsbjw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gt2yzqzxbdc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2wbzsjfyk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2hjztjhed.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2hyzeldhd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uredcrtj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2cxdizdsv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2xczrrsfu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfxmiixq.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggctftlk.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hniezqee.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2qrzfbrqz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fsnrhyay.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gt2thgnnekc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jkemekcs.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2rujdjjvv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2sugmsgxs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbozqnvn.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2myshytfn.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2aytijuoh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2enwxhlwm.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2peryrlok.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2objbmkig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2xhqgbxaf.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gt2cokguofg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2fbobhjto.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gt2jjquqalx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2oqhnlohv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2qcoqtnng.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ppjwa.cn/Article/details/gt2qqviubau.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2swxuuzkr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xobwzhzz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2memnqscu.html


<!-- 参考信息 -->