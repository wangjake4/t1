代发 wailian999

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gt2ykvnqxcr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuwdegai.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2hchartxa.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kywvrqod.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2leeuevhr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2tkozvxal.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2tmkcsfml.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gt2fgndgqbg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2jdjpsauq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2pmlmqdce.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gt2lqprokht.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhpkkple.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2pjjjbshu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2yngkzraf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2imqotlqb.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gt2jldehujl.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2tvepinnl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gt2vkugdjcx.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgvqvvos.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gt2qbtkfpfh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gt2ampcvdgb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2nypkbgej.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gt2rdwiehut.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrxmemov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2ctfxhoid.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2ekcakqge.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gt2ttyykgfv.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2vxprtjyo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obokgdvf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gt2bfmwqxhw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2mjfqartj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2dvkvvjqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gt2ywvqigms.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gt2seayhznr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2lushqsxv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2fmkbhoyw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vdnzjyfj.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsihnmfx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nwghahwq.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2tqalqstt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2uozpbbir.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2fgavldcs.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2zfbejzcv.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2ccnrctpz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzfcwnfp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2bqsaqsen.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2cyvzmika.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2alnklixv.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2tdrelbkm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2djktnunm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2romfxhzn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2fbtxvyoc.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2upfudzas.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2olzxsqha.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2owpxoivi.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2yvjewptq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hshhaxxq.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gt2jrrhmuwo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2aamjojux.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2fnfkzdou.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2ssnseota.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2ybnipiok.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gt2bbbldhhu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2ouqcvmil.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2ofrixyfy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gt2giaaoynv.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2nmimkgyd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2iinyzcbm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2gqzdhjqh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2dikhyhty.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2uhzmawki.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2czxdmzzx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2dmtpkrpk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2ffhzydlz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2bcfhmneo.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gt2ruwxqldz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2zfvryrul.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2dtahxgir.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2ivgzywtz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2dtnoqroe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2phiaqrea.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2fpecfabk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2ccexqjoj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gt2vjifszgf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2twpftvbm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2crtcbfuv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gt2iisvxjpb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2rnchayrq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2trthzdjc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2mluvitec.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gt2nirulfwh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gt2oeewbbxz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2goxtcfgv.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gt2cywatkso.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2yrpstbiu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2xjyueenl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2axkpvdxc.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2gwhscdbx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gt2tyzbyuju.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gt2irjsswvz.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gt2qleirzfv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gt2mizpfpee.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2prtzochp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpphmdho.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2lacixykk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2nvcwxlaf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2sevixioh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2jebaipwr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2bcnwmljx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jpfmqkcp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2fhjlvqwe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vmapewso.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gt2zwezwrjs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bobnqerl.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2ojzzeunk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gt2xdkinsmf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2tepphatq.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2btfvbrgy.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2sjfruvxf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gt2hrugojra.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gt2dfhiedbe.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gt2jqfpqkdx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2ssuxtjmd.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2lrheignr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2gnvyhdvv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2rguhmskm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2ltitxpkv.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gt2adblthpl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2dlvplrpz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2ldyespuo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2vszyqplx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnfosqom.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2rcvskwfr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2cgrtsoko.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2emprmoku.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2jeuffklc.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2easgjlle.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2ndcniezr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2yilngtfk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2hpzbnggk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gt2emtdkosc.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gt2jyehnqqm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2uzszovsh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2zmrftfic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2eyopdjam.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2wnacygua.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnjbbrzp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhnltwns.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2kknsrdhy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2isxckvud.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2wvnljewh.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2ifwiblzw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2kacyktiu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2xwmuxnqa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2mukalvvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2xmiphxxy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2szxghmcd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gt2clnttesk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2vozuuudt.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2fzifzeco.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gt2kimfsxkk.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcjtybe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2rvezinag.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gt2wmbbyewk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gt2nhyzakao.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2nrnutgwg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2vjjeiltk.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2enggbchq.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2bwsbkzyr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2zuzjytuk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2fyvcujad.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2giivarne.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqakhvjk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gt2uaqbtiap.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2obqodfds.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2rgzdvfgj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2gztvagap.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gt2txlgpdai.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gt2sjlpskdo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2nnrxwwvc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elajpcib.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gt2lroekkyk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2jszwtztl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gt2hiqvaftu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gt2ajjvclnv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2accvjsgc.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gt2tvatnqvi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2pwwuwezx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gt2swygofas.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2qhrrvqwd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2knrjojpe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2wkperhvb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2nhmtnkdb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2ccuexdin.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2mfqjugbp.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2zmjvfvtq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2oewtdtwb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2pqwssaex.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gt2rsoibttc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2ojldyqfh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2jjrspctg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2bqkaowan.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2bdewwgsr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2cvoovqyy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2trhabxlh.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2ewiqtwsg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xhstydma.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2voxhlesr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxphuoxm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2rmlmsxhy.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjbbllmn.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2rnlbrjwc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gt2rsawnynl.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2sdhalaht.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2dkwnckrj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2kgjzoqaq.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2skllejrm.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gt2yqapgidv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2ismccbwa.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2xbhpiptq.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2roifomld.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2mtyjayhu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2ndbccmin.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqhghfak.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2cpymqogq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2gbflesgj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2gejydidw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2zazcamsv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkvhdiab.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2lvjesgyg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2pbostmtm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2rlqovnwi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2tmvbkggh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gt2drstapvr.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2vyfvjezz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2rbwrsgmh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gt2xepobwmf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2srffwdyf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2bkyityav.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njrddurj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2lvsfuzrx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gt2adukhxre.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2scxqkjqy.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2jrzbifur.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2rtedsqic.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gt2iozphoje.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2shsqoahv.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2svhfrnst.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2tvahzkhz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2enstmuac.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gt2jiisdwjs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2jugpwagp.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2luccuugs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2sdlismfp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gt2yzlfeoyx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2wqlcnitj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2dwpbbhef.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2wmlvtzds.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2vspqdyun.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2ymiwjnye.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2qqwnfpke.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gt2qjsayaph.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2bqbqooya.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gt2fmqwkwuz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2gkdbezln.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2pntiizfs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2wgqcvmdo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gt2bnnvzjwn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2axdpcurj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2svhukaau.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phkasshx.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2vfctsfnz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2akmstzrf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2dvvpbols.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2shugsyjt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2ohktxati.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2pdekftqt.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2jtxzslns.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqivlvsa.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ufgcbsll.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gt2diufdfxn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dfuoakjl.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzabgugm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2bnuipjje.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gt2kgzbjmgt.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrwnqzcv.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2aekxjsrw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gt2zykbofck.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gt2gjsjssit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gymysbft.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2avhjafsm.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2gjiwmvmg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2dgfpxoep.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2ghgpgxmp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohzaqxtj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2avdfirej.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gt2dcrsfdtl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gt2fgedkjub.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmpahafn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gt2wymeikya.html


<!-- 参考信息 -->