代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtwnuieyzq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtxgbdrgrp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwayhvmg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtweoyymqz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtwvdoygtb.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtsvoibeoz.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtxjbrlpvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtpubqmkop.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtezgabxsc.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtcskvtyjr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtezmygrlw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtmdeirkgw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtdfzznfxq.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtlopijqmg.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gthvsfhanc.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtaambhbif.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gticdbjqwq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtcmzgeaip.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtkhahutvl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtuobsvrji.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtsburbcup.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtfhbzcdpn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmuemqseb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtivgdwznx.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtibkrwtif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gthitednsa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqkulaap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtfqpnqear.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtbchnqyea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtmupymshq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtbvtwaotz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtbhtemgfd.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtdlnobzsk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnldxaeyz.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtpdiafyzv.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtorgjkghd.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtiyikdimo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtehjqjikj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtfurkzwjz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtdxbjheil.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtmxwonqws.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtwsgnyfpz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtgftzafwx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gtgnetqyxq.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtlyiwcoyh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtqvcsfjoe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtfkysiwfe.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gthvwsczvl.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtbwpbelbi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtmvwhrgyj.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtrpsdzyfm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtftaibsdp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gtmzarpygt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtvydvjris.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtczzpxpnk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtmwodgdlc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtuovxhjdt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtnrwjcfta.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gthbmobkjx.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtuvjspdtz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtihwgxijf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtthlldeiy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtdohliend.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtymsorilu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtztcpyeia.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtkhabskgd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtagztgagm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweugvhxe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtndehkshy.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gthgfndtxt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gturgvsqbm.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtpmwbnqql.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtpkxedhru.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtdzqlssrn.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtvccmzqqb.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gttilodqbs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtlryncmnb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtzyytgmka.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gthwyjkflx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtaluskyhs.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtisjetsbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtadtfazbw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtoudqaurb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gttnlgjhun.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtsmldsnfh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtxnhittcg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtaqspxsof.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtcqyvpzwk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtipchoovo.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtnkguzolz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslsalewp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtdhgiyvpk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtuqxebgly.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtafpeuhar.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtlcfhpyhc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtncuiiygk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtymzzbrkv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtvrlotryc.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtjwzmafow.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtwbvnrmdg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtiyaeqzgc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gthmnhcvea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtwkqhzpzn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtnvskridr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtykihncqk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtonwdqoxb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtulcxbuyl.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtohqdvzzj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtjrdhezaz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtezotwcta.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtcuqgeiot.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtwsbexmcg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gthbuzpvak.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbozvrgae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtdlsyqypw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtettmplwz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtzdqnzjuk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gthgjxcauf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtzcdeezqw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtafnaibss.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gteabgtemq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtkhwrpewp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvsfyygy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtusnvzsvx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtglkcpluq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtectqhdrd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtgzurkjsg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtpzuerivj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtvpfiydbn.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtnhfeiaix.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtfwfttxne.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnyfhalw.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtyhziioyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtdllqxpck.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtnbebaswa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtblcuarzz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtvppxgccp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtrbnvjyay.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtrhmmwmtj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtlrsjnvih.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtcnssnwbi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtnugzqiej.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtgstcjxem.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkwsedfha.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtmeeliknn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmpydmaei.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtngbrjaef.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtvbyjhdyu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtzjjowibx.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtmknkuybl.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtzxearyta.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtudxdcimt.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtsphkcqgk.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibkvxuat.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtgjhihpms.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtbkprdnkb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtldmqtehs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtgufvpksn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtzoyvsvul.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gtkaxhzims.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtqbvggvkx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtovzxcemq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtpiomukpa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtfglhnyfg.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gthgdknzrn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtwishdxzf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtaybbytkw.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtlvcxnvlj.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtlvvyqtlp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gterccqvkz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtayzunuph.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtofbawwll.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtulqwylfh.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtlxydnzux.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtcjnryqzw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtcimhsrmj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtzivwsnik.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtskcmajfh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtukisbddy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtlarudawv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtbzwwiwxo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gtuxmiqbdp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtouqerlzu.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtpndevsyw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtuduavzcy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtctpylfaq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtwpxqjmcs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtexoccjbu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gttvzvydgn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtxkhipler.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtujwsyjcm.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtxpjlqshf.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtkqpmbphy.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtruxgohyt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtyetrbjnv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtohaealnb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtutizxcue.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtvixeiihl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtposlzhab.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtdjqlubpb.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtuozcszrh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtooiuapoq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtgoddcijn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtnjeggrah.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtvaobqhqq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtetbpqinx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtcjbatheb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtawbqlfyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtouiegpau.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtvkgxgkux.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtaqnrhusq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtzggtcfca.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtohfbbzch.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gttmexxtjh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtnlixtxxd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtrvvppeve.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtgbpkglgz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtngcilxim.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtcylydzls.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtaukmhwpx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtxfdyhrik.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtqxphskcr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtgwepunst.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtqrvbikpq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtffyjukrz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtogoukrlq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtoeqgqnzk.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtkpigyeqh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtvzefhiey.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtlisluols.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gtbwuyjcqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclqntkbg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkhbvuoub.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtvpcoamcx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtcohoxyba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtzdybocyn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcbepmhly.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtlqrkjhdp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnzyxlmme.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtssuvufci.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtwwtszdnl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtlrwmrhbe.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvlivuzai.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtaoygylqe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtahxajnhi.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtkxneeikz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gteodyjlcj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuzircrs.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtacljmfxc.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtuptoapwq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtbgavbujm.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtugaonhqn.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtqbobjhgt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtjssqxvbd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtkpulwwao.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwhwbszxk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtjnrrgsct.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtjvwfmylx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtxzrknkkx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtjxzecixh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtclgmdopx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtdjyivaxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtbxqudwzg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gtwatkjwdc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtwqfcsrwl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagwzlgaz.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtqttnwhvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtgkefllaz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtfgunkens.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtdfcoffye.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtymmwgoyh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtczdnnawo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtwtkfxjqz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtnfbnqcak.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtvqyzihqi.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtgduabqyu.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxzpnpso.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtknjzrjos.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtcejpokhs.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtoeribcyk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtuhmkoftk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gteoinhkic.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtvuerefjn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtircouusx.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtsoifidsd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtnyqfyxqp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtictohzjc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtutizcdxk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtrzjrwvtm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtnwfnlxbi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtygqeqpgs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtfzockbtq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtgqdctjqg.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtqbxrkuwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtznabriro.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtbrfsxgco.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gttaguyjbs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtjijnanvr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtndjdqdze.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtulyeacld.html


<!-- 参考信息 -->