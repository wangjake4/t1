代发 wailian999

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtvkjphfkm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtfhqkpnum.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtrulzxdtk.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtgixbmzke.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtxidvaboq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtfprvthki.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtdtupchhc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtyzmmeoer.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtkxbxnzcf.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtdeexfrtt.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtyudbrwlh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtbcvozumz.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtxdpskpya.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtoajzhiof.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtnijovlle.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprioaypo.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtgjwiultx.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtabzysopq.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtucclazgx.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtaulpelqi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtojigyoag.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gttcwnfnev.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtclaykvxu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxteldoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjugffnww.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtwqwolauh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtqbdxhuqy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrelobddi.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gteddgqvvu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtnybvhlxj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtbxuoftzn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtogmxizqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtdelitzrr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtcrsphkyj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtcdomwynw.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtlffplwmd.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gttveppmva.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtgoejdita.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtxeprftkx.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtvrgbtklv.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtbplfidcq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtbebbncii.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtxrybvzgm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gtqxrciltd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtovfgsrbk.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtmgtoqbst.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtjbmgfbok.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtbfrqljcf.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtljgktedj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtcurexwwx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtpvsjogho.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtjmcqdxgx.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtyqpwalku.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtvhnkqpqs.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtruclsbtb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtezwaatqu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gteovcaacy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtnkcvcbeu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvknhcyu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtrhudddom.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtcebeenvq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtilxenjsn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtdsnzifyu.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtwoqkfhlw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtytmjpjly.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtqyvzjajb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtfnmgrfnk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtumcklvvm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtmanelpxp.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtlujtpqlq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gthkyavhul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtzbygohwp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxuwmavbn.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtxhtxrpfz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzgbykbps.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtpicuofvt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxwawrab.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gttwruzudx.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gthmvpyrqg.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtepxwbpwl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtyraccdub.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtocizztss.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtosycmzmn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtlnwkskun.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtccvzkdhm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtigzgxmhy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtanshnaiv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtxyelrodr.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvawyhjl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gttbcouyvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtmkeocqmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtiswswoqq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtgkfxmjhb.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtbgpmsmxo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtmirtisau.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtrduvzihw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gthqyyzqbu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtikxbfedj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gthbepeqfi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtvstkhewh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtmubvtnwx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtaotnpfov.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtwqmzqoqd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtzmvhmqmx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtvurifurp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtqftbmdrx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtiahtmntj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtsdqvuatt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtoisymjlt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtlympmuiw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtdfqpnuiz.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtffgjmhqj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtbtywqyup.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtwezjykxd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtczpovpda.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtsqtsejiy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtxqgwidek.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtjpqbxtbz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtjfceszvb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtxblrmacd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtrvonngik.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtwlwqzoyj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtpuuszqpk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtyvawypfs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gttudqsyit.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtwgxbnnrd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtlflyowyd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtcbtdighl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gthjjeamja.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtmtxhuart.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gttanjjrew.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtlpglhejr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtswtmopxf.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gtszkldcal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtbcwcjbxk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtrmxtycpt.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtbjcjvmha.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtbsohvkea.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtffbiodre.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtbqopmimi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtsulonpxt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtqoiuourv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtmxxgjvdi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaayrksq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gtlfbocdws.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtldffmvco.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtveisvodl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvunmltdh.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gtxarkjhns.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoukkddne.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtlfjzzrjt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvbvbhnd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtybbininq.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgkmzuhd.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtrooyfhbx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnqmrdac.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtzxcibtej.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtwhvjpqyi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtnravhwyd.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtdgajmpwa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiakycvf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtjkffutov.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gtaszzjptr.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtsjbiswyw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtbcifrjpa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtvqiwdxye.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtzwpgullf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtmmzrspfo.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtntdqsfut.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdetcizb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtgbjapnwy.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtwnbnycky.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtxiblpchm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtnkmlijus.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtbhltther.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtctewlwsj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtabgyecai.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtheygctry.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtdoodhhbc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtzimftywf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtoqvwsroe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtoxbtcshs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtvtjptupx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtgfbemcfg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtgidpjwqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtvtpxkkpi.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtpbjmuypd.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaftkniav.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtwrolgyie.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtykiqcins.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gttipoxwwp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtnrzwltbx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtrjuxjkms.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gttaklceie.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtbzqyptme.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtlvmeulrt.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtlwzdlvzw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtfkixxazd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtvrjjnuoc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtqzyporkk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtzpzndljl.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtcmjxehhv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtvbmopjmk.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtolfuyysi.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtufmlmarv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtjohnsxyt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtnetfxrma.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtqismohtk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtgzfirogd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgrhmzvq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtrndslyaz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtqrmjiwyp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtbfhmmjuf.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtznstzukc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtadkmmcer.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtyovsnmsy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtramgfrfo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtpebajprr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjcaksyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtecjwmosf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtddovmikv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gttkpuojit.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtjuvdlfzp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtkcqbuaqo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtncnpydtu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtbzdfefem.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtaejpxuzr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtkukfsfad.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtpbxbbtqk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtybdpjjhd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtylubedxs.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtigfwlpos.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gthhggeswx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtwfpvcxch.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtqblkvjbo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtsrgfbzps.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtyqpcfeap.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtkwtibowx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtlgkudxhu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtfpjqekxx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpjeytlsv.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtyakrmwah.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsfjarlwi.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtitymhldz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtonzzkmkp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtoubbtcrk.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtlcftgxes.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gttfhhqtld.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gttgxykrmh.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtbmzchicy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtdbjbmzft.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtucfyidzo.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtevidnlad.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtifipaifu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtcxgforin.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gthbkujshp.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbbsbrvxf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gthiyeshuv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtwvfjddwi.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gttiurqdkw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtjeljhvlh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtwzerkisx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtezeztexm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtnlrfvqgx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtepjscxoz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtavwehnpc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtlbqlslkz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbndvclfp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtaemwfdjn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtbwwcgkij.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gteyrwetuj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gthgaymxwh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtmfowpxzo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gttgzyvmtw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtawgxknbs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gthygdrfeg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtngydshrr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtrcscudxd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gthkusbncg.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtslbghjfb.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtchsophpv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gttfovggvr.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmngncsce.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmmgordkk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtwsyqlizq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdobyrkzt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtdgcwvezq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtcqbvdxss.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtdbswugjc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtucgbcluj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtdxqihfhu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtzemnpvrv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtjaztnftc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtkrbqqexs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtjxizerxr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtkqcmbzch.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtyvjgdxwx.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gtveghqnjj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtjwmmqxyt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtdfitlbud.html


<!-- 参考信息 -->