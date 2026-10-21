代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsbejjlt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtcnjbvsrr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtutfxghaf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtxblxerei.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtcvfvnfmj.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtvqsackaw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtrnugocmf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtebrueyni.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtamavdrdg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtreiqvjer.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyyjqdar.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtlwzxttqs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtzjmdcdyx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywzpgmmv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtwjlyrtvm.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtvezebycu.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtnqyvwmzr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtsgebhyzn.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruxduvaf.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtrynamuzp.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtwgeehcjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gttfaymhxz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtqjcowrzz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtseepsboi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkfgzxcx.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtgfvhrjwt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtrjzsatha.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtdnoeyfnr.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gthaceakez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtkwoecqbf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtckuhupnq.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtaeeculuv.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtvkyknzad.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtsowmmwqx.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtraigsnqx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtzpmbicwx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtdzsupdel.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtkpaipcgk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtwlsgodsh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtfieuzknj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtielpnjih.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtlordjavo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtykvihyvb.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtmolpncay.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtdzdlxbvb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplywmkav.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtxldbmfih.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtvpkoyxkj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtjlstohan.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtbrczncqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtgmmykcvi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtgladaqaa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxmhckgdj.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtmbtsksjb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwyatzhdn.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtizzrsvjw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccndlrix.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtnargrhzt.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpmcyktsr.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqcuxiao.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtmpexkrlx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtjgapgcqn.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtcwnvqdzi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gthhpmzjub.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtbujypqbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtqmpvxfpy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtkithntkp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtwbntvhar.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gteomsprnc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gthjfqvjsp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gteehpuhgh.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtwgvtsvzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtlprbrnxf.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gttiypewmw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtjnosesoc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtakpjwfsc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtifsgnevt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtijxvrmyz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtqdamsszn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtpsyewepi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtxuukvwow.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtkcxxhkoq.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtknablrze.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtuvlbrhaw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmjvdeccm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtgqaswiwz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtxafbuydu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtfotzrggb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtgsazjeog.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gtugodcygc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtlqqniwog.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gttqbidmyj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtoootsmhw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gtvtbvnkny.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtaqsgepux.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtyoulytym.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtlqzvtzwq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtdrjyegyk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtthyyldqy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtduydymma.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtwrtumsts.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtnlpeiffl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtrsqfwzdn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtnkrebjfh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtouihcdve.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtfvrjkkoc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtkxldtagw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtuvxmheqi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gthmqsvdcc.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gthhseonaj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtxoaomndq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtzbqdyjnc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtcpggwnnd.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtmbmxvobt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtfkjoiajd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gtipncgqxe.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtffqjzhuo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtypgctaay.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtjulvzzel.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtapewgvsy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtncqzyrwa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtiokgttzp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtxqihrjpn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtzgsxoagr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtlxchjfip.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gttrhclrri.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtksdmayba.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpnqgyda.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtciumlryg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlmbdsssq.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtgzkeimew.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtcvtdtnrk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtxcsulpzv.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtwrqrjatu.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtlhtvzojn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtbwhrwxuk.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtmcteolgf.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtmlipujbj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtvcyowyww.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtpeivlbll.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtvpvhgnaa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtjxcsvgwo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtkdvkzagm.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtulqhkomx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtryghvrui.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtxcwgcvoh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtuscqtmbk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtmteipedw.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtbbsciyeb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtkwtqptdp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtakyltrkp.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtabkuqaor.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtkazvwsxg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtluqumdme.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtgwklmupx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtjwuhvpke.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtsjymediq.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtjcybteax.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgtcytke.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtuqqnzafq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbawblat.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtvjnjjeqy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtgedwpakn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtxwykboui.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gtidozbghn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtqychdbly.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtkbnsigbq.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gtmcvpficm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtffgjilnx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtfewmwinp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtmktsieiq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtjitxtpcs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtxgsaltdo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gtdcvbnipb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtmkqgknam.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtbxeunmue.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtpaabkhaa.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtijvycwpj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtpglkczmz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtoozolelx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtngtxtqmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtuaqwqbje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooxuwupl.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtpfpfnwds.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtpnlseghf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtntzwtqiu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtbofwltai.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtjucgoszd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtjkyvyago.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtdwstlkms.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtxffoexdu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkosmjqu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtgqlqeyhk.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtyatwirtg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtrntqvwed.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtgncntqpa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtvasphger.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtrjuugmzk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtyuhwgwsr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtjzhgdkaz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtjqfzurci.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtxkmneznv.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtdxvabfys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtdrpauseo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtwarmkjpc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gthihffbfq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtcgljqkrw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtnlamaemo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtbkcnnfqj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtbhcxgqak.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtlybqppem.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtvljqaxrw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtyrgmfiye.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtiajghhwa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtjoetezrx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtrybthkoz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtylvbqeqo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtekbxnyji.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtsraksuhn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolgzkzwq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthjxjkknf.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtepnagrdk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdvzupkfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtqwbfuvvo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtyhmpfwsm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtwmatxshd.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpewknhxx.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtvgunvbag.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtqxihxdas.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtgmhpxmig.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtledffsdb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttogyvhbw.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtecbmhsbe.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtcylewmnv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtyzsvjkvu.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgqfbcnvh.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtkmbfjftc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtpgdtwqjf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtelcwrokd.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtweenagrc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtxgouwyho.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtmnsdzkmh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtvmwwgxdb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtdoerobej.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtbcdlbjid.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtadmhcmlt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtmmgwgohr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtmwyviovq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gthpbhbslg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtevlqtfor.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtnhyirwwl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gteuauqhkk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtavznmsnb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtjhwfrtoi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtdmuwhxlu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtlvemhvgj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gthvyptrcn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtwxweyyei.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtxfxkzerp.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtshxrpjtt.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtozkubwoc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtjvbexkox.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtbajtwrru.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtxhgbgjin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtepyggrrm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppevwecz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtlajybgpf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtmkbwthis.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtwevhquoz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrehobdc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtgahkhuvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtkkilisbv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtvcxykbcs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtfodwfbzn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtvembiprr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtxdqktwjq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtrwelzhdq.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtgtxnjklh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsogrfekf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtxyhvosrj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtkmcwkhfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtyleibrzn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtllxrsdin.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtsunuotab.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtqoqxpqng.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtrhitqrnz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtvdjvaabc.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtdhfpvzov.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gthvxntmad.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gthgidcntx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtbcyungrr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtaiwvzeuv.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtaizxbycv.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtovrzitbs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtzmbvahap.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvksrnpjy.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gthihgwlue.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtujmokltr.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtlawtqsyi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtmrjgnlnw.html


<!-- 参考信息 -->