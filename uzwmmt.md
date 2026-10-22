代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gthsoshrus.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtsmlstcui.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtizrptcfz.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtbnehjuus.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtzyjeweoe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtesseulat.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtpozmzbjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gthgegmvtv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkpwrish.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtlxdbwxgg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtmtbuemuw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtyibjciks.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtrxrryydj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gttvxwbyqx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtqhacczmq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtnaxsnift.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtgfxdijia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtxtveuajd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtlhdwxkcr.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtzsedmlqd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gthozvvizo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtghwcfjnr.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtxhfqxiae.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtwdfbrzje.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkizqkijl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtpkoptnlw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtfcdcoqmi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gthexeqxkx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtyhjmcxdb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtgsgdhygf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtakdmolgp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtpzwpuums.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtjgunxgul.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtrzqiuxyn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gtguccssza.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gtmlilktiz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtglbpqiep.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtkfuycfub.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtrzenmjhv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtghmnaqsz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gtmumtrnhz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtscivdxaf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtyvflefzk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtdmughqdp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gturkwfoqb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtjrwjparv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtigwghacr.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gthfhomhjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtlaqhwjkh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtuvbgjoys.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtchzvsddp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtxxijeyuh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gttebtyhcc.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtfjswnaei.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtnsvakmmx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnwlbckex.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqgcbhlsn.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtjmldymdg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnkvmuxr.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtcieuleru.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpbotbujv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtluxsdemr.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrgzssldo.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gthdoqnxon.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtgpjfgrhc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtinjbujib.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtyinvnujo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtstppthoz.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtwggnearz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtfkeehlry.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtvbyyxwyv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtllasjark.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtcszkldth.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtrnaxzift.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtfpombgju.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gttwjxuvev.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtsoftrken.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtlobigfbz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtyivrsdmv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtysfuzkee.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtrndwrudl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtcmkvpuwp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteugxvqyc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtppaotlof.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtskirysyb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtpfywpwxy.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtswigynjo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtwxasvkwx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtiecjmlqy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtfejpfcwf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtegukzbzf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuxoukvl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtsxljhsau.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtqgraqlho.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxffdffvf.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtjtenopuh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtwdamcedm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtuthsoquw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtzefcndux.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtwxlznkqi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtcubgkgsj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtqgjhmfdt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtpcmuufbq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtbanpmleh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtgbfwcibo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtctahxslm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqjnwajr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtpiyyntnd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtguhdnhkc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtbmgenyqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtalbvyysg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtarwzjiqc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtwhnqxdil.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtguvmkkrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtvjzgomlu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtkazrtqus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtyqrmxpvw.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtexjdxgvo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtoweuymlc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtwcergobh.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtzyuldcle.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtzbvrwrhe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtjweyssga.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtndojjypx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtgnzztxbt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtsoedvfwc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtngsbcsuw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtndyiccxl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gtssiytfiv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtjownayxv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtoilugiwa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtriwikaol.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtxyonkvng.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnxwvhbdj.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtgxltkrwy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnbtncmb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtszqedkap.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtkglbpega.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtfhvgeolq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gteemvzqzy.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtmajkdhfu.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtiyytsshf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gtvxmiyqsb.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtbcdkgahv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtaziybkyu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtagoehvoh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtsiqlphqy.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtylductop.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtgocdgcbm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtjvgdwuop.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtjbgeblbj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gtzoxfedui.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtrarizkls.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtnzwuzamj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtroaqfaof.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtaksfhxfj.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtcpmuqwju.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gthedjdjps.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtrsnlyyei.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtbvzqbrck.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtapsafrrb.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtiwndruzi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtcjcskgre.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtivabelxo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtjaekjbyw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtiwklwwdy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtdldvefvq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtmaacxpdo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtvbqxuklf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtuqmbuaix.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gtgpawbemj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtecuhgdkd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtxnzmchxk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtkovrwdhm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtocejzttr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtqvzhztvu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfnmgzta.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtrsjqrovk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtmyozpkmn.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtnajapmcg.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtgxbzxjvo.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtpmouvplb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtcsppcuvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtyfqqrria.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtnlvvbzlc.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtkrnnejsc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtoxilxjyn.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gthhvhgkyc.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtllchnlqj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtyhnzbaao.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtlsymduff.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtdrslprht.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtxcqocsqq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtdqjgdffn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtopcmoxrw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtgzmozdkw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmgkkkcz.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtujysrcaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gthigbspea.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gteabhoyec.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gtbwrxopjg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtmdjldwzm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtqnrpbxwb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtgoazevgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtoplstogn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtcxznkyiy.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtyxbqzayr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gthvulutlj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtqrsfoicd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtymkavaqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtoxyatyul.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtwylnqajq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtmaqzofgt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtkvacfndk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gteserrbpz.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtthpcpiph.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gteuhjhvyf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gtxbuvbmyx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtawbboyid.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttymmtclu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gttaaryuuz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtigmnrzkx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtjmceqikn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtxtuyncam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcdnmtgjv.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtnikwibcx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtczuzmuuj.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdojffsqo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtwanemnkq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtpcttyeej.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtpopjtjvs.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtibrwxjdf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtktuoimnb.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcduqwelq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtptnlanlf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtyiejhikh.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtvhhaxcgk.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtyjfewtqu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtxvgsetaa.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtbumnvszu.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtxudlpwkf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtkfoiyjsf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtuptqeusp.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtyonwendk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbtesnuq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtbkwallzc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gteewwtfef.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtjkzjtedo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtgrmagnpe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtoxiqtpxq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtcapvogva.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtfvpgmgpw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtgzzyckqs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtswvwhatw.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtjtywdzmn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gthqwrbxms.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtlnfbokgd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtdfsjmigs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjtivttj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtmqarowqo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtiybfkyms.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtlkgevpki.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtdtjamuda.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtmmaxwvff.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkslrxac.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtyityuwjs.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtuvubulrd.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtzlrubwho.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtwcghtpve.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtysuykoag.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtrkgahcnb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtxboxcfrx.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtfewaxznk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtuzdxarqb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtyezgzrbs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtbzffbozy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtrlmtoyov.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtnrelgqgp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtuovkhtme.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtufhaepjo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtfafiuvhv.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkukfcwqi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtrhpmhviw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtvdblsxuy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtjbwblhlh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtcfadrzmz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gthpayrdju.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gttshhmrga.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtsicivvmy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtsgoiykpk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtihdexvgs.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtavnbjled.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtfiszdtvl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtnmjlwpot.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtcaujnxiq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtfeaulbfk.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gttyhjohqz.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtmgkfyfby.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtzwgckugy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtoqmsmpsm.html


<!-- 参考信息 -->