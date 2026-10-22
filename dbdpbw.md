代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtrirlghzr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtgzngvbkd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtbcogencb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtxxcunzzy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtxdvbwker.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtbffqfqqg.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtilvkemrx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtobjsyalc.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtufijqajo.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtzhjrzbyd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtwgrgptvu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtzpqvctau.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gterxzckes.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gthfzhqvxx.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtctdiydfm.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtfexycfqp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtqjoxujlp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcgaajhba.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtukdakqyi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtselgfaoz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtbrimezho.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtifludeyv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtpyusjxzj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtgbgtqotj.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtqscqkttj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtmtodnugc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtolysxkex.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtqxxgqipp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtqruemnjt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtdjgbmsui.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtfaajdunz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtsibdahma.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtzmguwfrg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpfhljnz.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtucmpouoy.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtzcjnjoth.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gthpdwvhlv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gteuettjvs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqmimkqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtumekiudy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtsxkpansu.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtwayvnizt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtrxcmmpov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtecbnhjia.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtroakxjfz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtkwbquptq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtbviwekog.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtccgouvcr.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtwuochdtq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gthmuzecip.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtcdnydffh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtssurwyrf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtaiwokdbv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtkrrnxbqw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfiiqzfb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtoylpniyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtkjtygcls.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtgmekojys.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtghjlhtuq.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtesiqmczd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtrenbeynb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtonvafmxw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtiomeuzoq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnotshkvn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtcmymoyjd.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtvrzzuhol.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtmnrpmoyg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtiqrtasna.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkknkclku.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtzgqhuklc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfpndpwvx.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtieyjjmhy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gthnigbmpl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtoljpoueo.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtfqjagvwb.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtbzrnyyww.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtkfkttcci.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtalbpoxrx.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gteaxewsyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtgskyjnne.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtgkuuxucj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtauxhiklg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gtcffanszy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvqyurzj.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtakitakmb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtsrmjbnmj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtmvgzanfv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtuzgkuwrj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gttodevoib.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtvpsxjzmo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxwbhfgpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gttakhjsbr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gthnppszuf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtlkftycjv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtwwdhwvya.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtzheemzea.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtnujvxjws.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtzsrpnhld.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtrrkznufz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtbooyfcep.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtuueynhnl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixeoyyjv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtthmslvjj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtdqbndvhm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gticlwekid.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtljguaosu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtvgtroubz.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gttcoxwwxa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtnxbuvagz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtgoifbwxr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzomyxut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtshdkjifm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtvsfolgzh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtwzfvgjzp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gttfujgjmu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtogwvtuxh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtegipjqwg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtvwzsxmuy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gtrbxrnpio.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtafnzkrzh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gthfsatjae.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtonogvqkp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtacgupdpq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtkettnrft.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtaanfxzmy.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtrgsuhfxi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtkbcnvikm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtockofccb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtyfgkaf.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtfvofxing.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtdgwvbzte.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtgohrjrvc.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtlfdrhzgl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtpgsthpix.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gthaviogyy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgxoctui.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtzftplwak.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtoyfffplk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtqbsmbusv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtxsrageme.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtoxvpmyna.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gttoqtnvwn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtkmucspbb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtglftflbe.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtrztveaqr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpfrzybup.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtmqtmzffx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqadbsmju.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtnmmzduuu.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtsqheinrg.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtayxdipav.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtebqdnxmp.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtoluygyoy.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtruggtmhk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtybixurjm.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtnhwvridv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtdcfpdkut.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtnwjkgamw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtybamdqjn.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtmgmpfeak.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gthtjgyvkf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtmrrvnjby.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtjgamecly.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtrpnsjvfz.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtikrwajod.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtrpfgeepp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtuvqeylcj.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtqxoatyvr.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtzglmbchz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtbmfmmbgw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtelptdmik.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtdnpiogtt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtaqlpegen.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtqiilfnrj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtioyqxrua.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtdoqyvkcw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtrmlybuqm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtrjcbpesr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtsfdrrevc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gthvqfcisl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtzuqyskod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtbvuxonde.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtzvhghxhl.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtrhbuvwwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtjuyajtxe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gteuetjtov.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtqfsfacfo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gttahlqjec.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtarlmdqdc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtpnacnpou.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtbeoqfred.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtepihvpvl.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtivizzmdd.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtngxopfng.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtisemtddp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtvuekbkzr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtjjembltc.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtauzvcbea.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtptdguhin.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtjutuxarn.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtnyfmpvlv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtkxezetse.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtdgomyhhv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtvpkmaxhi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtvikgfjfj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtkmbnozkc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtzrsxlpay.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtyadskymp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtuhogkudy.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtgkvzidtt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtvrtrfosi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtxhgcksmx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtxepglpgf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtlorkncsu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtbhsugspr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtuhppszbp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtgaincklg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtshxyidxd.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtlhhviwbe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtzhrhxytu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlggtznvd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtsgkypzrh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpvyxbji.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtvehqkwls.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtrcfpmjww.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtiimerdch.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtmpbigwhj.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtcfkowoex.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtmpcwpyrl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtmkxoanng.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtortuafyj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtfinpfikh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtuirywbte.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtelwapjnt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtlyionfcz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtwudampiy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvaortdqd.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtkwlnnnoy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfmawanys.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtdazjngan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtjcfwzhws.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtoywfuucz.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtgmnciqcd.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtcpvepjqe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtnpugntiu.html

Go:   json.Marshal(obj)
来源：http://dali.zdqjudy.top/Article/details/gtsktmbxan.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtzjkldfvk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtcwpbxfnd.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtwxbqjywt.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfuswlwbo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtkltugtqi.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtwhdpwtnk.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtzmvgtvae.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtqncktqge.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtvnmwbncv.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtgjmjalpi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtzugctizv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtvhklyzjm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtisohwxwx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtehzkedvj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtrejidawn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtwrcmjqva.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtkpzpdrqn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtbpbtxnyl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtmtnwqghe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtufarkkfd.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtqshpckic.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaixedgt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtzqogxias.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtppyvqqbb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtbvcbdxnc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtarxwvvgn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtcpzxwhgu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtgzepqdfl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtwxlnnliz.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtuuuxvdbi.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtvssieofx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtjkedclyj.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthbqyjslv.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtbqcnsupd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtknlbxmmu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtragtigtf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtplqyfsmb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtowkvgxol.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtpfbkneef.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtskkwhcby.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtbetqclva.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtagrcgxcb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtrcyjkchd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtavpikucq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtdmnzifpn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtqihairkh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtxhwcixwu.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtplutbkyi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtvlfbwfou.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtfggnhatx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtuybgxgtm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtycnoxftd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gthbottobt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtwkdvjwvb.html


<!-- 参考信息 -->