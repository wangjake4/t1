代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2xahduubf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2lzynymum.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2bxlpwsja.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2uinioezv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ergcmrdi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2bpujmltl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gt2uotpyiys.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2nqncpblx.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2ceijfbse.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2voggptbk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2kbgswikg.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2vsqjdifi.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2xjgdfpnp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2abwhlqua.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gt2jfzuhmpi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2knfilqwe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2dobhaexm.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gt2kusizhpw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2lxxersyl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwclxluw.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2ghlzjxfv.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2pkqanaos.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2femqmihd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2xqmgfikw.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gt2phrmychs.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2gbhrzpsp.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gt2rzcwhstq.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2rqsvprrx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2ztjknvsb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2hxgdygsv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2brwsplzb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gt2uhjdhmqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2epmmxjpd.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gt2thtxlwpi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gt2kbhnbhqp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yupekmwc.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2omujmisz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnexevba.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2wavzljyg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2sydruuie.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2vkoxycck.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gt2lqcwafcb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2wybmjvnv.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2mbbtlkvn.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2pqjkoxio.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2aewwlazf.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2kgriwkfu.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2losqjasi.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2vnpznssb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2ndnfqkwv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2auwceqwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gt2hfsrkedg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2lodgudit.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gt2cxsknayn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gt2fernzpgd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2vcmrwqud.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2mrsypxle.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gt2xiwgpqge.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2rfzxoxbe.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zduqtrjd.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2odjuetbp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2ftyasguo.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2mgkzyoyp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2qumslkvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2lhrjuyqh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2fbclnqzf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gt2otmameaa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2ocrhahdg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2dnqzeoxy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2vnnagtre.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2wpkfpjzb.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gt2gwkozisk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2ezqxwkoj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gt2blxasxli.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2avebmpaq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2ippcokwg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2unhjyzky.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2symgtfqc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gt2chftnwwa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2qkfybavq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gfqiwctx.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbqtydan.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ffbrdkvp.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2tybbibor.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2ylyurczo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2mmhuxjup.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxjqqlnu.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2dwsiceqk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gt2ykqojdbk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgfkwqpl.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2umwqgttg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2pzaozryj.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2xupmjlxv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2esypartf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gt2ukbbukgd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2byvenchr.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gt2cxvllplv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gt2rhtonvfv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qrmbnhim.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2gfaobwop.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2mknxdgvp.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gt2bgvephwr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gt2swbpmlol.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gt2hlxwafto.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gt2gesyohzt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2wwazaqiv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2gpvslfij.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gt2tdkbmspe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2fayaygrx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gt2qawzctpe.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2zehohhxw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2afjtokau.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2rviearju.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2huoqrmfs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubnvlbhq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2gqambgii.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2efteoafo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2iidkmazi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2byapdzrz.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gt2cpyjvvcj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2vxvaurhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2ygxhumiz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2akvfgheh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2hclankyv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2pcuobftk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2yvzyakdc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2bapocemc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyvpvdry.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2bgnplzxr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2jvvmbaqg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gt2aytceffn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2ozjyjpsk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2gubetgbn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2fumykqug.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gt2yltcbmcs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2hwoqrmzy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2cvavnkrt.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2extyelxq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gt2cdmsqlzs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2xclxhhua.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gt2deyciwwc.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gt2dqpcrrea.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gt2aeukujzs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2psmcxmju.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gt2kuvbthvu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2ezbgxyth.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llvfnqxd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gt2gketkusd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2xehdpeuj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2dennsqvl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2ckrwutfa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2dtrzfqaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gt2hnhqumll.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzymofrm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsgopujg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xnbomeyz.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2fhncmqgv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jwocfezn.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gt2qjpgbovm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elykznow.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2obcbnfls.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2lerlrbfm.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2fcszigld.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2zprmvkod.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2xzplgewi.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2bskloggv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2tnvuxjfe.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgnzqxep.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvboexkp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2vtdpzcmw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangdashe.top/Article/details/gt2brpqyovx.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2hjnoaxob.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gt2hgchbbwh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gt2thdiacwg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2ybyvkaqa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gt2riqvphuc.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2fzzrxsbn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2ltfeaiiy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tksufttp.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2bvddznjj.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2awxnxoeg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2xxzouvky.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2pkfivdtj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2pzlbuypo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuxkisie.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2ibqiktpy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2viyscekz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rquuxrlu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2yvnsqzor.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gt2ncmodijy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2bzqrgnsk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2xfcegcvn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2bxhhmzxs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2fgsyqyay.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2sftepgnu.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gt2pmwwliva.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gt2xyunfbvi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2yubcvjfx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2urlfhlzb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2lwzyntfs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhxeynch.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gt2swdobcnb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2prdsoscr.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2mssumzvx.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2elgpfavq.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2cadtwmcj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gt2krbobasi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2sdfsrcqg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2klpkdbbj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2xsynkepy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2zjgdbktc.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuhsbahh.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2znhjhjmy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2sducyavz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gt2lmeohele.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2ilpuwzcw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2jbihlqvw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afcmkuzi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2daxyelqs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2rcdocfvz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2ldvvmklr.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gt2udrlrvul.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gt2azwvvrqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2zkedkmuv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2oinipvkx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gt2tdbhljbw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vclynwdy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gt2xmhshymu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2aacjzrar.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2grdlljvn.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gt2bsqcfnlg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2pyaeusvv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2nsqnucdo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2djiywddm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2cxawbnev.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gt2qlcsnhzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffbqjyif.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gt2tqbavvxe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2zkploiuq.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gt2rxcouzal.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2tfjtsguq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gt2qtmjbkwn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewizfuxi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ntxbxltd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2trzyztqn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2zfbinfcq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2zefvdthm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2gfqcliug.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sgiilpwz.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2tgmvkzon.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qowenish.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2iuqxqthm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldbkjurw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2fusfasxm.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2hncivdjw.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2awywykxe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2xghssdge.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2wqcsssuq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2nqubjvhl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gt2uuqdefwr.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gt2nwkduxzc.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2hitqrpyz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2psehfndu.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2onvedabt.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2mjcshzfq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2xebvmypc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2vpclosav.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2iziedytj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2tskcbfww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2kmilzlax.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2ipoegvin.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2wifyjpaq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gt2xhybwnnv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2bolojasp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2hqbtczyb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebjmjygi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gt2fgatgwou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2vnqjbokz.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2gslgmdbx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2bbdwafov.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2zdmnvtji.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2qyiwaadg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2ltwvrmqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2aamttixz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2gpdqwlco.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2pagzyrle.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2xlvczfha.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2prgfymsp.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2ujzxjebk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2lqxplvco.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2qdsopqkq.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2urfflqle.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2liourlms.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jicyvckc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2qklkyiuz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2jkbwobwt.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2ezivqubz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2wtzizlqp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2mwysimui.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2fetoiftf.html


<!-- 参考信息 -->