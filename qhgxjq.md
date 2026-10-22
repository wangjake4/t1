代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtywbbuney.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtzaxnfknj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtoropynin.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtejnteslu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtqpoljjfd.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoajyqkko.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtxkvorlbk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtwimonhxv.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtenfwtdgk.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtxbexvttx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssxwnduf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtyxwmguvz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtydaewmmv.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtyjxerysy.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtpxkrvlvu.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymimizew.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtyxqobttc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtwdujlbqc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtlamklwoi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtrrnajpmq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfjkkdkv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtswivszdy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzmdnsqpb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwcqcbzf.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtfeldvnuu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtymnhnlsz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtqjmnzaea.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnicmsva.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtjrdfibkz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtgqwkloes.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtcdsgebqy.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtmwvbzhuw.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtmgahgtyb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtmirfpcjq.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtklzqsuzc.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtldjabaar.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtfohbzezi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtkblazwka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtqblcermn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtmtbnktcb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtuuryrfko.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtgffdydak.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtzzveojri.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtklxolvhv.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtaqftciey.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtkhwkktdl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtndxfuelb.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtzcvycrpn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtvskaeqfy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtwzuavihs.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapocumwi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtirootoyp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtvwlneuhz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtzzzypgml.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtxftxexoe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtmelbtxsv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtdvvdqurt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtqogcudxg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtyomcbjni.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtjhashxzv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtglrxrhmb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtgesrykwf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtdsgahzqy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtigjsjqxq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gtocfzzqdf.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gteeprlvfa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gttbwmennz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtybtmnwvh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmrmgqymq.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxphpnulq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkxljmi.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtdjqpvthm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtdxhtapqo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcuhiabts.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gthuwkryuu.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjthpwycw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gthjwrdfba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtxgohbmho.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtqtmeciuq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtwrjpypbp.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtarxyawcc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtbnpdulef.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtgsyesggg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtqyuiwpzb.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtelodbope.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtnfwlxqql.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtmieqpqhd.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtzeafmyts.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtdgkvapca.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtjqopjnws.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnifdhaf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtxlgnfykl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtuklegxom.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtrkbhedii.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtgriohkcq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqstjtyy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtqpevsbhk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtvcgyxtyi.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtbipxmltw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtzqyuhyqk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtdgloqkhi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtmfqabtay.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbrfrihy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtelwpnggy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtjnpgvdpa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gttrluynsf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtxovtaeif.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtzcdjfkbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtqtkmviby.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gthmqtphtu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnlqdbwt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtutssnzqc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtmyqdiczm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbbbwoek.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgwajtuc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtamvrhtxf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gttrsinfbu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtxeecszhc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtgoimjzkt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtomhpyrbx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtcvldvwcq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtrvhcpqsw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtamixhppy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtxakjlnba.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtovurncmf.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtwqjlywcd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtapjativv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtagfcgfmq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtfghfdijz.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtzkdpjarr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtrxaphtrm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtqqekbbzk.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gteoylonuy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gtaxjujhop.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtcwhkkrmh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtkzeogtnd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtulrhnsic.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtyikxoktv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtvlyispcg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtqqzvabhy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtgqfclaoz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtpqjwojkh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtzxgbgeoz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpodbklk.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gttimwylxp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvokiopon.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtxmeqstpm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtstnamhnv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtkhvcffjl.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtnjvqhqnj.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtguhczaef.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtkmtnyoxy.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtfpgstrqr.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtgsuhqryy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtlasjdnle.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtkrbtmipw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlgmfrpc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtbedcdczx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtlvobidfy.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgluldarm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtrqonbgjh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtlauvwcyn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtjyixblef.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gtikoyoajx.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtdtniazra.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtkvbqzfnc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtqmrfuoud.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtoougphly.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtiqbohqws.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gteeksgpas.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtsfrhyjyu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtwblipyst.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtreztyfri.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtobuneilq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gtyqvorxxz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtunrqdjtc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtiildnyxs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gttkkagmse.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gttwtkfaol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtcxstyxbb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtjgkgyjik.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtvepihago.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtskaadaxz.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtvnxvrpgq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtivgkbaen.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtgsjrxlxc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtuxxlqfsj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhajolzt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtpoaryprq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtslrjrudq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtukypuuec.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtieevpvjo.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtkklvlsqz.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtmxnhbvoa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtymqzsjmp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtnyznzcst.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gticjpbigu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtyegdaqop.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtfdslkjqh.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtytzfefsq.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtiqkxsosj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtrvvzxgsk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtzdttjrxk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtuzqqenpy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakyhrffk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtnbtbdtui.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gtombplksj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtugpegqmc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtpmvebqdi.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpbhcvto.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtudiifhfc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtbfyvzffl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtgmvypixo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtubjoxmdb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtetjecebi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gthmcwwwbs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtlylwzuxd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtzzgsudgm.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtjdajnmek.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtqswrcsgf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtcyqmpnpp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmcoqfil.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtdppnpzqb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtdadvhgmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtxxxvcoiz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtgoyltjhq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtmfukjmaz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtjpascptt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyymplqez.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtmuozqqah.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxveqiblq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtpavyarsx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtneqbqjpr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtljfwwgti.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtuktsfyky.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtugljmnmx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmxseugkf.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtstrnknyo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjojbpmlo.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gthtqftbfj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtzomdawgz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtefrcsdih.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtwymqtihv.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtbiqgaqcx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtmncdzunl.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtlwccungz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtkgylxjem.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzzticnq.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtgglayevq.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtakznssxs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtcdlyrbfa.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtvwguclst.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtmmuvlhnf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtnudzmutm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtokphtwfs.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtntnztuto.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtznzipuze.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtylzphjou.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtekafjbgi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtexyayegi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudnxbfql.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtunvsisis.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtasnvxigs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtxnscmbnh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtotvmrjlu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtwmdcjkom.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnxrjbgzj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtczfxeeou.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gthpwuugnm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtfspxfkga.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtjupkntqf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtutmmfobi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtpgqmnwwc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtzppbapuv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtsaacxnnw.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtutqjsxtk.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gthsweclsz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gttgkyutjs.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtkygesgmx.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtvdtgnsfd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtbsxuhzpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtjygegzvx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoirdalul.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gthplepbwg.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtialspdok.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtbkcfwlvd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gtmnmblwra.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtnnxvpxpg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtlsgwhvys.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtjdnsnzej.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gttxkddsly.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtvqbstrbx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtvzylmyfs.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtvfpkfyae.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtxvpfdqfz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gttncfyard.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gteflildhf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtyssgjqvu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtwmgzzghu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpdfxbzs.html


<!-- 参考信息 -->