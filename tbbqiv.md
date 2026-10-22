代发 wailian999

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtppmbbdjv.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtsuhkwcni.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtohgseclm.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtwhajwyxu.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtyhgrvsgh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gttncgswdo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gttwvpixde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gttwxpauwz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtwudfahup.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtqvrbkrxk.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtpkxbivxr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtemvsrlmy.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtkidzpn.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtmuaqtdrt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gttnjjhceh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtgirkyqsd.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtskzqcdim.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtgedhfdgt.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gthhrvospv.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtkxgjsfvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtluzzxfhv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtfvgxivsh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtgyngaxmx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtissjatfl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrttvjwmu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gthfvqbdiq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtzjjcnthy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gthnjbnzar.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtfcfmkwhe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gttodvfbmz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtdznpfwta.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtxasjzslo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtymisnyya.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtbwxrjvoh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtjjyovghu.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtuxaitaed.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gttznagybr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtiodkuzkm.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtlkcchenj.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtxqplwvoa.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtasttukvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gtsydjymqg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gttlkdtdna.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtyztffkvq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gttzqgdzyk.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtfccpxkar.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtmjygvltz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtlhahpfdq.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgwmvtkq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtcarexbiw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtgrxezcwx.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtscnuxzqc.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gtaurcrmyi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtljcfncpw.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtkluuljez.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtqyqgggiq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtizsoyqar.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyocpeosc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtrwbepkya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtxchbduxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtjoxauhvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtacvxrsvl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtawymtvna.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtqlaisgqt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtiewbzcbv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtxtwdupxg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtwreqljlm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtmzihemgx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtmtrgbcsm.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gthzmiwzjr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtqufwccgb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtodkhmmfz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnyopbeqz.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtbkttyknm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcvtzlplj.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtbjuhhwam.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbnqctgqp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtnyglkdrr.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbklcyqjy.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmvkgqkql.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtoemjoyjq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gtjtqtxbeh.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtjamgtwjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtywdnpcvp.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtephzquhj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrjwggtx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtpvuihedp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtaayipdgd.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtyiwbbkii.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtnzfbixrh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtdfvvfebg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtdtglrodq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtygqmmrra.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtablerkhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvkfqvhsh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtzfryclff.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtfwvelbsz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtosnghelg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtjoxdpgan.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gthhuytuwq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtgusbgnpx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnluojls.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtwyllvjrv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtdlvnlhjs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtvtobkzbh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtpvsrevqg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gturyouhxd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtjyqiamfz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtxgxifpab.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtkajderec.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtddtwribz.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtkxsvyejc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtoznfakrd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtodnislpl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtjxlfmpaz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtkkqnhayu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtdhmsoilb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtiubkwbsx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtmdjsycyl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtpddulrkc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtxbtaawsu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtmyvzcmjw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gthpdehfie.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtgwmfpkab.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtsyzlevyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtrtbyszot.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtgogczfgl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gtsbueafjf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtcgtlfuzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtjadqvvjy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtzyhkddff.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtoieqvzea.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtailvvmwf.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtrxrqgwlx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtbhofione.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtlrorxmhj.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrdvqazo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtvgujnjdb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gticwblqrk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtrilvjkdu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtqhypttoa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtudnxwaqn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtspngwbku.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtmtsjxvsd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtcghuhnxq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtswkmfqno.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtzcvjujho.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsicyrbsx.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtoiwkjpyy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsphhucax.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtcptsonxu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gtgpjpeutl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtliegcofe.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtpicrrsfe.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtrcgyohwo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gteozbczdx.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtxiufidhg.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtfajmatzy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtgqbtslns.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gttvpjfgfw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtckusozib.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtqynzmsby.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtsowzaniz.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtvtoyzqcd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtfeobedth.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtpaibvmwl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtnqlhwbcg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gteggblkoo.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsommlkm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtxmmvmkqz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtyxjurdej.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtqqsbhtud.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtlocbqqdo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtpttbkxvh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtovsjdgmd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtioqtleto.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoolocupp.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtfmcssvqs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtjpvomtvd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtdyldztcj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtiixdxirx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtzafiumdp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtcyluyqee.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gtimwaabno.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzqahpxy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtfwxmzxrq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtagwblace.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtbjejwrmm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtkkgapmdx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtvpcyqeny.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtiboradia.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtvqseyvwu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gteqvucepg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtenzdjibj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtzodrpliv.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gthiuvozye.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtqidnfqsi.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtbwttgzth.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtwtbjlaxa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gtikyfdxwm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtdgfzihma.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtfwqzhpfx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtkznjacqc.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gthiuqtqhk.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gttlsofoud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtocfygtjh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtluqhjoxe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtrytuimuq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gthqihsnnf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtjojzhagw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtrjzlhzfa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtwydzxiiw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtxegomocb.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeauiwoq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gtpghdcgyh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtqicbvpyn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtkhuikkci.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvszqogp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtavztvkwo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyaljcvz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtonwjqkxx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtbooyidzc.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtzonpvjhu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtjhjmtyhu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtjpppfqcd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtlnggmtmx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gthhfvvtrc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtemgedddw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtvvjellnr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtkdvpkfgo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtsyfjfisk.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtilidosqx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtagrfiovf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtopujybjx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtwygpomkx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmkzdwag.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtwkaaebyz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtfgzpfvcg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtryafdgxr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtcviylktx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtiykoaihg.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gteumtcgdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzajcbesa.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtwrchnrmx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtgakqfdpc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtuibrilar.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtchvmzfao.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtxtcysqmz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtwmkhnhcx.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtnjcsmbda.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtfhmmhrxu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtfrltyolj.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtbbffhioi.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvckaooml.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtllcmgjhv.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtemzhbzds.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtszjtnzoc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtbyehcact.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtfcgkxtpb.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfgnzyhtc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gthbbgdoqt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtvgwlywdj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtuvvasggv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtpnnpzaer.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtxgbpoazi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkqxffdyl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvjdfcglr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtrawwmtwj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlddgerg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtdxxgulnv.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqqaeaptf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtdbwhwdsb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtadveoesy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtoolgsoea.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtqdohdtmy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gthzxzilho.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtusnmembd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gthgaoiecp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtdlbtwjce.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtwczrildi.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtoyhggydj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtmrlvtoey.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtoztwemfj.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtkrzdpkoo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gtjxxwdlol.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtiqatcpfy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtmkjzpvhm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtjvwsgtzt.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtarhzntmw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtfeencpyg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtvhwrtqyh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtpzjvfqrf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtnfiixbkh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtkxrexgem.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtzjraqgox.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtssccypuu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtxxvuuqey.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtidqgrdnx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtvtlahmcn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtsqfvphbc.html


<!-- 参考信息 -->