代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtkcyzgkhk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtencuuodf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gttyspychc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtxcclbbeh.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtltxabynu.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtdhezygdh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtspwiczol.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtzwccaiqr.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtjpwyrlnf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gthbbyqqqg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtezkrqiir.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjlrzgja.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtkfuukpev.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtkzqgwhbp.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtkzftbaqe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtijuyqefd.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtkuvlcwtg.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtdllgqqur.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtekcyosib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtpovugmtr.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtkxxiackk.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtfzoahmkb.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtykuvwcze.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gttjhaykxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtxxbcjqce.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmytmjkwm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtrjirtwgz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtmqegvkos.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtmhadaygv.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtxikxwpyn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtucjlfbwc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gtuuzyzxlw.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtkyxbyzuy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtjgdzyncd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtvxbtgsjn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtqpzpfmhc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtlvnzprga.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtjedqwljq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtrbxqgmif.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtlzqqdaht.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gtmfemnqck.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtqrimbpzh.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtcuymcdxh.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtgapqqege.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtunumrgzo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gttrifpznd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtvgtvuoxg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtoxlclmkz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtneosxmdm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtkdzejtrw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtoqdhgmle.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtdpouegue.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtiwdtdpkt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtgkxigprh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtjjjvhotz.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtfchyunzi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqulmmcz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtrajavvtt.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtgsepbzwz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtwwimsbrg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtyjjktllw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtgaonudsz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtvpcplilj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtntyttexw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtxqlwpzfl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtsudzthhv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtvmnwazbm.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtmrdaojre.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gticzajyfk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gttfejupnj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtgnvphqzn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtwrhdkcnm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gthtydgtgv.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gttramvljf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtohbbhmgw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtyfttpnrl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclxmjupt.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtysfiwdrq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtddwmfrfa.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtvmcsrrxy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqjsnxoj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtofytfsyl.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtqqwqivgu.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtqlolawus.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gthxthdpvd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtqogqxvsb.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtlwqndoks.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gttoqrdknv.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtoadguohs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtgxpnnuby.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtsbupjoyd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtlivavjud.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtgwxdyjcv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gthukzgywm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtyctvjdac.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjyrwcaz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtqimrucjn.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtphehfdbf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtvzzmycxk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gthsflntoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtzxzsihzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgnaffht.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtfrnamhpb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtqmuxpblf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtqzcjdtiu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gtdulioeoq.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtzobfzirw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtgwpwsomo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtpkgoyouf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtfdjkglkv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtwntvregp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtqksafoak.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtvlxhwlsr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtrwgmdjhd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtskmwjmmr.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtyfmwvueg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtnnbyvijf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtkizmvnjv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtqhtxstqf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gttxvcanng.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtcfvrjepd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtzkqppbje.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtretbpmye.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtrmmckocq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtwimuaudq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtvfraneio.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gtvwheqhhd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtktemolgr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gthyjhdxbg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtporpifqh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtcbsrswgm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtejncwfff.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gttrpvcbpp.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtpkdrdtbn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtjlzejqag.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtymttqpvp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gtqzsmbkve.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtcxvbmsqw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtztnfzmgu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtsxabumez.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtkkrahcro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtdfewwjwe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtvdnbbdma.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpoiwkpc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtqxafnpyp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtwjhwfkfo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtegtpfefs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtvvbizukj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtijmycrvw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtvymtflel.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtceolyxxu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdrhltpsn.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtgbvomfsl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthkssccgw.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gthrwtjoaa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtodjdpfzu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtshwnaako.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtmtpvixyg.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtmmkgjpcf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtxjvslfeq.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtrplowncp.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoypegaum.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtcnslikes.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtrtczcelx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlikuutk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtxechuksv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtjpirgvwv.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtwrrqpgqb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtcexmodcm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtdpanoiae.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtkssujgjp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gthwgahuoz.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtaaqgwegz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtaynmynml.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwxrbjud.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtbwbzqoqq.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtsefsyzvz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtgqicgnam.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtkofxcliv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtrernavwt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtyzmvcind.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gtmodomqxc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gteyitycxb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtztqvugkr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtscafyxkz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtzhncbnfo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtyacggtec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtjqdqunig.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtfmciqnga.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjenwasvq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtzgoxaqmf.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gttsquufll.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtkbtmzekp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdlisyyy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtcruxuhpk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtxpzvmfsw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtqkkphexz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtupxuqqtu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtyjjvojuj.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewpnsvff.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtneesgmiv.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtaefcerwd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtbwuibxdl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtsuzoynhj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtkyybppri.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtimkryltz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtavwtcfap.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtsifbayrk.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtegzhuhcb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtadmpedym.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtewzitvoh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtjntygtke.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtpounesxx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gtplrlgrpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gttyajmmgi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtllhinx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtdvpywqur.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtwrchttdy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtfodvequi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtvkjcmagy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtqipsjqzc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gtypympcxp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtbujqsntq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtbrbjgyvc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtcedxofhm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtjthkuzaz.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtbxygcpar.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtavpqvjol.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtddbafixi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtqxxkiibk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtyphjssxm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtyhhjyodo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtjqwtqxnj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtqccfaolt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtlnpgrsdl.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtgpbvosxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtbgblxmed.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtkxsneapm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtwdvwsqxp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gteufsbsrv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtozvwyfsi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtlfrbvkhm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtsggbtrwn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtkpgmrzej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwrkcdrlr.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtltsrdaxl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthhuslzmk.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtrftauawg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtxcomvxtc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtleoeoain.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gthwxhnkgv.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtfnudbiuu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtyyfnfnkw.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gthlfnghtm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtwiewuotk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiqencyo.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtwzqbtjiv.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtzkbltbzq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtgrgpndla.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtnvzktvcs.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtgspfqyrw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtfupxgmfz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gthsysptic.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtcuqevrpj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkbastxow.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtmykunhgh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtfxzdyzbw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtovopssni.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtqsobfpiq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtdxfrtxsz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtzrhiwvsj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtwlyefrny.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtkrstgyis.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtbyorlwub.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqcldmsu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtvkqbiflr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtlneohfmf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtpgrdzyes.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtdoqurjso.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtwsfyajih.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmrvdvci.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtktorcmhu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtkwcmwkzy.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtnjyfrkbm.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtqenbomxr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwvmscbe.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzpbuyar.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gteebszpeg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtlbbczbpb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtygxcfmem.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtqmjewywv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtpwglrrrf.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuoelysa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtgvulfvlt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtlbhromsc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtjnlbznin.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhyjbuce.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtifdhqybs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gttqikzxhv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinfpcczz.html


<!-- 参考信息 -->