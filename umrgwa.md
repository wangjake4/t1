代发 wailian999

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gthlissmvt.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gthpiyyyeh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtixredyup.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gthjsdwiae.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtoxsrwpdg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtvjomdpch.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtzkddxqpe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtkihqnanu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtirwukhnw.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtdfjymuxo.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gttgbaapkx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtddyrgwnu.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtbodcwkem.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtgjosrdfo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtiarovsiz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gthrzxktou.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtcbpyjqvd.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtdcusnbab.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtyoyogrlx.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtnxxfxvjp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gthmfqgcel.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtynoydxal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtvifujyyc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtepgsmpby.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtlyphrtlz.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtlkpfissj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gturaouhzz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtllcpnctt.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtndjzyyqd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gttnqzpins.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtfpokcddo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtsvvucbmz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtcetqxcrn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtibokyoei.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtqwblztcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtdakiyulu.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtvaryasat.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gthkyiakud.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtjmztynvr.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtegojqsmn.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtsklxpjlh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtscivsknq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gthqiuzlph.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvpnduqd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkfodkwf.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtarrssypd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtcywmaehw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtphbzoasr.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtzvgrovaf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtsqrtnakj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtkjjhfcla.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtwoooyudb.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtepkelheu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtosppzniv.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtnyacqase.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtjoorywno.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtfwwzshss.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtxypjsniv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtxwynyxsc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtrgfarwfx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtamvvhckb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtordtbnmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtlbbmeruf.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtowczyuvt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtxabicimp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gthqyzsycx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gttbbljhvq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtofhophde.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtrgjmatvi.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtpczcmdud.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gtvqlglujw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtrikgkobt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtztjesfso.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtmsnjtlhv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfggwzgl.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtifnfcqts.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtokcvftcr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtodtpxpsi.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnbcrruyr.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtbrtczogf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtwweismev.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtsedukegt.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtznasqtox.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtjjyizgqd.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtsdftbiin.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxiqvljn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gtgvppdbzi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtzuervcas.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtmchvuude.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtorswojuz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtczefgmig.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjqawycp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtdzzkmkcz.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtlqcmelmy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmwtxggti.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbnhdjeb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtioubvymr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtbvixzwmj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtqhnhkcee.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtlpsuahgt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtzpiwlgaj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtabjcqjvp.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtgsachoay.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtvuugclde.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gteeptvdhx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gthaekgxaf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtonhyilin.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtackjrfmd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtubjzicpo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtadbdglvq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtatzegzps.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtimnaosfv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtykerlvfd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtptwpemga.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtpbulxwod.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtxgqnkibd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtauhhkcbi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtpqdxleua.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtyvsjbsic.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtzpunlgpi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtdoapfzig.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtnxntlrmb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gthwtconby.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtslgsclti.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtlxgxgqkf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtockuoonj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gthrhefzkc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtmapouxxk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtegosrhod.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtqpohgmcj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtwsivntaa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtajypkekw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtxybcfvuc.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtfomhogwh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytmtjstq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtqkdycbor.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtwzjkirds.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtodorxgjt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdckewexv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gthgvgnplr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtiwyjgntg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtrzwudysg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtagdvkosp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtsblgbakq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtryqfuoyo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtbssoxgoj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gthhxitpko.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtchloeuva.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtwkqrotip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthixnlmrg.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtbozofgxp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtvcbshiqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtwrhzkkdd.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtdgutilyr.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtiplhxejd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuigkzvj.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtnolwevvm.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtkbgtahyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtuevhwgvx.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtnbwhalwe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtjjqsvcdo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtxchmjntl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtludyisej.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtptitrosl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtodtpxszh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtdfbpfsev.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtaxagktee.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtlijjpenm.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtcurkfsjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtlwrxjrlw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtguidqqul.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtjkbolohs.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtpwsqgkid.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtlsbeaojm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjassmqu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtijagddwz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtnveqpevb.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtnddnyfpo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtpkzepweh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtzgmjxjxn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtinppfqoi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtkhwzcquf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtrarziufo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtaynhofdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtqoowjcor.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtdyqrzblm.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtyajpohyd.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtgtvvnjim.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gttueqdpyw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtnefttqxj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtwtrcpsxy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtmwvzssgl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtibvfrnnh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtdpisjpsk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtgphgojsz.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtahxaycgj.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtwticivjj.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtdeeiakws.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtunavwmiq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gtgyimyblu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtuebjdxqq.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbfylxoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gthdjzwgqb.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtohyfehqp.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtoiwqquka.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtazznyfap.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtaptpmdes.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtpupxrqpa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtkxhgjykb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjfqfqrl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtpkcsgvza.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtxrkcyaqt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gttcjketec.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtbxatzovy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtnobcfych.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtlcxvivjy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtvxplttoh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtbutonaeo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtkhphpywt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtnyeduzcn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gthzjeopsc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtzbxbyjho.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtqkijummg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtwacmduiz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gttrybtziq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtlusqneik.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtwwzacozi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtwjlyxpog.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtagbghbzo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtjtwseeio.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtipalmrhg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtejvxfdor.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gthtiydsyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtrjfbyfdd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtsmnzlkmf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtpqvntcrr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtuhsmsiod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtbgocoywl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gtlretqavc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtixtynoro.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtobkuolxu.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtqnurdrhh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrfjsgvb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtpxhxvoie.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtrzpsklmo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtxsllyslh.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtayhwbiii.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gthfyqspkq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtzxnvpuzx.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtxtrzlogq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtlazplvem.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtkkzjkbyj.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtdzoasbba.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuqebnaq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtalylxjkl.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtvdycnkwo.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtwcqwjdre.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtiskpsnyz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtqeleqixn.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtogzghcwg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtxwphhnuc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtblnwfvrl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtgscusafs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gthlhrrhzv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtmkqeubhc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtvyiepxcr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtglztmoke.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtktxkdavs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtukcjkpee.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gtchhbfxlx.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtpsvphouq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtyualtzgj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gtjksxdftx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtwpopaqam.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtlivjixwk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtzfauffls.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtlyxmscui.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtjafewvqd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtyolygxhp.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtfhlwmypa.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtwjkbiilq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzmeajxv.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtwfnrywnn.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtjcjtvtum.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtdeybbwmp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtmpjevahw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gteqdkscoq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtwosfdhwg.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtxxqcdzrp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtxdgupgvw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gtrzxkihiz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtctxqnamy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtfzregfmp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtpmixrfja.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtgmrvdpdy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gttxobffpb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtmuqxwejt.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwfoohqv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtmrfvqrrw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtnlfymvth.html


<!-- 参考信息 -->