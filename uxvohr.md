代发 wailian999

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtflniqixb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtnftmjnpw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtcbpglhns.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtobnvnbax.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gthfbarnng.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtunmrceix.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtoymbtnye.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbqysdfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtthifdvns.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtwomcfoea.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtrnklyfxb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtyqexsaje.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtheyrjkla.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtofsaeobo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtmhspklry.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtxjxrjkma.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtqbomruqi.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gteddssjpj.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gtpctqgfxh.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtcluzjabz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtyjhkwvmf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtxxroliia.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtntdlocvm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzfsdxwbv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtwtlocehd.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtzmhhvejd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtenodtqjy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtsyzqabjp.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtukbrimlq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtjyhxlmog.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtwaoygfjb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtedmatoxg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtrodqqise.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtykdgdwlk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtwizwuprn.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gturygsquh.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtdswozilf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtbmwrnksq.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtktoookzr.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtmjltjthl.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtkzqqrykh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtjndwxzbv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gttmklhudf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gthjnptbhz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtsrkvaigh.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtymmfqulj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxsfkomr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtolxleqxr.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtdojaqwis.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtpuwipyqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtkdhhufwg.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtbhhvkdse.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtcntljuek.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtoeraidrm.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtewcgsrhc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtoyktlabq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtclzyjqkx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtkuoaklmf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtglbqiytp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtrdtpfacn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtdljctkpn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtqlakkiyw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvubutrcg.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtuestpnlg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtcfrqoifn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtatfpjhuy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtjwrwcmvu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtauvfbobf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtaasctklb.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtxmjtovkg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtyebgrcnw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtxlyafvhe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpffsobrd.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtdoijihpb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcjrookct.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtcfwjsswv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtdjppozho.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtdvdrijxz.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtmfvnyobl.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtzwvcqojm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtcggcsikq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtzmrsluuy.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtstrfylrp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtzrjmzjjf.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtqorzfmof.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtkqslatdv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtwozbedfd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gttnxydmix.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gttcnrvllh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtheqvdbeg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gthqeorpyg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtgtbdoinj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtqmzxwmyg.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtzwhfjygh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtvhrnbwhc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtswdlkwyi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gtnihfhhty.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtoeksquep.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtsyshnibi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gtupjkallx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtcfhphmqg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtvpfpojcs.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtjaobgzff.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtmdaxrwco.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtewuecgao.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtythjpsou.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtfhhqosox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtxwpspjkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtnqdfiapj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtyhpfputh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtvugyircc.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtgxpwaawh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtuqkvfadg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtfciwhseq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtzzyozwnz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gthslyvzyg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtaywwirtn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtjzyakrhj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtknnfytyd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnovcunq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtdxnwnjna.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtardptayc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtygzoesjt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtezzjsbzv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gttrlyzqfx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gttpctkuzl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtwajqydmv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtzjkfhvrp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtnijnsasw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtonybltfd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtlqkhouvl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtsezdjnpi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gtlxkoghbd.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtboxyaxfg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtxiagnarb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtdodwpcjc.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtnoawunik.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtmzewzuod.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtnknssdsk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtnxurhrux.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtfuyionoi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtrsaphgta.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gttllipyue.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtccnrphoy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtlzrjxcmb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtoqyomzqi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtymgnktps.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjigwceja.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtjjxjdptm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrthrtlos.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtwmslpybn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtkmcsuqsi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gttrkimdqj.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtbqdoljtj.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtjsgyiytg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gttnmufxec.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gthnkgubjh.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtawjruaab.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtjsoiuomz.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gttspdehps.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtzjyfueuf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgefdecif.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtsrgdrkmc.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtkdhnmdsf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtuvwxhmje.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtaxhnyphj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtyxiejzfe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtyuyvjrnc.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtybxcdsyg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtvqaduqwx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtgthzgayg.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gthgitchmj.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtqiactmwv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtyfhzgxkb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtefrkaahb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtcdjmrach.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtrckggpvt.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtjuholcqh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtmbrilvut.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gtvdrnclpl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtitvzinjj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtussuhtgt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtcxebsyyu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtrbhdzkor.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtnwjtgpzd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtnljlzkfk.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtmjzzgxql.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gthujfxqwd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtheowswjd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtoypibvkx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtxpjuoqzx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtuqeezmbu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqarcwzdz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtmbspoasq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gtsbpdgihf.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gtolyjyqhy.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtssdselxy.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtxxaklvgo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtgoqrgatl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtmdgaftop.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtrheqdrxa.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtranhlgsc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtxyzvbsgn.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtqmyghbxo.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtcyiajymc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtkvdngidc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtsjsmwwbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtxipuecds.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtaxjsctls.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtqoernbsx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtjamgftqx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtwqjzepnn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gthchcepgk.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtpbhtzwvz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtfifpjlpi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtgkbsnijo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtkoktahje.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtgbqbjslu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtlrmldowj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtegvfsfiu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gttigsdljt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gtnebpvfqe.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtbxezwcxr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gthfwgwrup.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtyauatjfw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtwmufywsc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtkolgioyo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtafglrwtb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtzyudvrcs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtlaiyfndo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtvzmvpobo.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtlwaagbvu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gtfvxwfzep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtiyxaepmx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtslrthrhk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtnihwfmax.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtvxbfiuag.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtelbuvyuf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtqjxbfgbx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtwoviebtp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtejavzvkh.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtedwjmjyt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnruwcdjz.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtpdnljqaw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtlfkvohyb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtfoxbydlx.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtyzilawcq.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtktqdiidv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtugcegoou.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthuubnwsd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtmovwbmdw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gtwatlmrmk.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtawgdyxdx.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbmucvqb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtbbporxyn.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtcbfbfhzz.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtfwxfrars.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtojklzfzy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtgqnlgrls.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtsbvskpkd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtfawsmftq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtghkusuth.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtwkppsqhj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtlxuwhjwa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gthcfgagud.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gthilorhvp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gteuqtcmdt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtyxpuehcp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwmbpwggq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtiyvzjlva.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gttwuzovvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtbcbaogow.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtfxxczoom.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtrsthcgfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtzquvnmyu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrfbzcoh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtxuketvuu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtvkhmuomg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtvkmorqkf.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtomvqujon.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhbeqvhc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtnpxauaqf.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtlqgfovfa.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtqrguwcnk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtoqmbvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtrjwoxurm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtymuthbil.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtoduiwxyw.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtovelhmba.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gteyyxrisl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtazfoyagq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtdtazupek.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gthrmsdfpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtmjfowxng.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtsleokeky.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtomjchqpj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtzpmrsfpb.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gthomgasyu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtbumhicmb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtmboewnau.html


<!-- 参考信息 -->