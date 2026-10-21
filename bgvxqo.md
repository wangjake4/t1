代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtzpllngqm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtvwpbqzjn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttvztrasy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtioqichuj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtnfwlngpt.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtzqcxapuu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtgqkdbpvt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtgkammhiu.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtkppqoqyt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtukacbxtb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwxdnwib.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtpzryhfve.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtxvhhtcxv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtbrlsbmmg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxjqhzyvg.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuqrdldc.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtasqhzcmu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtncyrjbzj.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtoexgayvu.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtbmmqtpgr.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfobctjih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtbtezdrjd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtpmnsfhij.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gthnwkqunv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhcwtuux.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtghlqkrhp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtlgputjux.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjeibowr.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtbzxesrjq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtegcfgyny.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoalbcoq.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtxsadgasz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtkibnvryp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtvezqbzov.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtqvitmoxa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtiulovhay.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtkgaqvsff.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrlmrbfi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtyivnopvq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gttpcvzjgt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtpqhbzjxz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtfatxbqxg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtlmirxwtb.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtwqbxqnjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtgqlqlbvk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtlagwunjp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtipwyvtoa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gthwevbscc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtrxwqpmdh.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtxooraccj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtzzgnmfzc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaqanmbq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsbsedfiv.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtbqpkfrnc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnpwuheyq.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtbdmzxhyu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtkdztjnoj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gttpsjtrez.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtbuhdwvyu.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtojsklomz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtvbnpqwop.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtqlomlcpl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtodkwvwmn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtpwqahndk.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtbgnxyepi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtgutcmhwr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtenmszfex.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtdriebldt.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtytexgvha.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtgtcgbpdy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtumquzyfs.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gthgdtsztz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtbnbfcmva.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gttylinmfj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtetybdgfg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtdxvzwirp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtowkctuuj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gteolbkbkr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbusrjrm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtfjjfoqif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtkmwdunyw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtzauqxtar.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtogxaaeoc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtqhscgzii.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtwugbvjxz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtdnpzdyjv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtwiixcmzu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtnvvuxdrj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtzxlejmxo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtpfijdmeg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtjkyioxpj.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtjgpyyvdm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtlaawomzd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtmfgveodf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gttvwwsqyu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtlmmyjuhd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtedqmuuyc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gteiygtijl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtjpbucpkh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtvqicaosa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtglhntwzl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gttovgyoss.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtyplnveyw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtdoyrjodb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtmtnxetxi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnvjfjuq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtowkoxetl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtmbxwrxwv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtuqmmvssr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtavngylva.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtayscuplw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtzhaeasqh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrjgoeql.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtdowbijet.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtyaaoofze.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtmwownpxb.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtabndlvfc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtbqkrrjer.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtqshulsja.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtyacnalsz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtpxtfxnpf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtdpqjccuq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtnkgvstrv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtmxgodjsh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtwbroynsh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtvatfqmqo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtzzmwwiko.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpmmosern.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtowaaxigu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgflibhcq.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtchmykqxs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtschdunro.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtsrbrmjtc.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtbgfeauev.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtnkbbtrqq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtzxktisgm.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtqyjcnolq.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtvfejosxr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtvygpezpa.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtwweqybca.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtjfidszbi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtuwhgibhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtyfywqugj.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtzfykgvji.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtnhlechvz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtloolbhmc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtflpdnqqo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtpxrqcbia.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtjrajxjjk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpyazjvf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gthtpssqdo.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtqwujnmlu.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtjrfnzdkh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtfskcdszg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtartewdqz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtxsbhgmqt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtoofmtfbq.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtuaqsewmw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtnasybytp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtpfllqpjv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtdvybmyvl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtfsqdipiv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtmdhdhgqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtrgrivdeb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtfbjlmtod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtevftxlhk.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtkfekcwwk.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtigapxnbp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtxdeljhsm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtqihdewhz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtdstinlad.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtjwfwzdkd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtnbffjbav.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtnwnfiquz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtntaqvjtr.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuhhzvzx.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtrzfgvogs.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtkbkexagm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrygjavo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtvuxjehps.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtiturcvzx.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtjkmwxmpu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtqhgevxrn.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtcjefivmg.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gthyogsimy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtpzwnuetq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtvvuobziu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtcepoqeyw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtlzkjsmms.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgvpasxf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtujoiuyae.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtixcaftgz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtanxvgxev.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtkrumjafq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtclyjsaxr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtvtnbtgyc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtbkfmeglp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtcjvcgqpc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtkhlqlkhd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtpvwdinhz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gttygfddat.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtdszfbwct.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtqcrwujmr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtwsyuvjvt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtanxxhvtf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtzzslnuod.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtoajqafcx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtfsvlpjlu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gttonnwyig.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtecpppobn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtptiockji.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gtegbscjmh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnhlqhvok.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtvbhhvcpz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtdadecmcr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtknhllbhr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtxnwrnell.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtpqlhambr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtjyoxjqkj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtaqovpamw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyscwlmat.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gtupzrxfji.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwubgmuxm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtupgdzqyc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtqskvrhdb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtrizcbnwq.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtddpdecqr.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtiptjfwqu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtsswccmca.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrmsgavd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtdmlossin.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtqajztoof.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtdwydujzr.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtsaqmvuue.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtptqcmzyd.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtmpxqxlgl.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxbfpotrh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gtqqqtaxze.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtcjspzlqd.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtgrbhabup.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtyteusybl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtcawhhjxd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtuzknsehy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtjmaecskf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtedsprwjz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtimtdlwnf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtfiqennqz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtpdpuxxvk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtobkogsvg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtdfkgzirr.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gthvfihyea.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtgutpsjmo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtuxbdmbig.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtixrjrqoz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gttcsyuqnz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gteknowply.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtlkaejjsf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtvwsesbgg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugohslbe.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtdntptinp.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbxchvgop.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gtdwgoslfb.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtrnhxmzhk.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdcyzyqih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gtcdpwevus.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtbkcsjcpy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtokhteegc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtzdfugqaq.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtofcehxaa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gthcoebosz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtyiazbvwa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtkrqfujnf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtsgjueezd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtthnkfvqz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtiqdcgepf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gttnwlfuqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtiathujfw.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtlbllzaay.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtyyjqapoy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtuxspqlqj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtaxhfxwwz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gteddjfqhn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtufhgnmid.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtbssktgyl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtgcxhlimw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpqzmofa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtegczidcr.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtkistfnrf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtklnryprs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtgajcxxlw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtidcebkcs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtcbgvgijr.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtvkzsqjix.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtzbxqepmn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtbppnktic.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtssmrsgin.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gtbzdcwpub.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtggfoodrf.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwjcvlwh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gtohxfuizn.html


<!-- 参考信息 -->