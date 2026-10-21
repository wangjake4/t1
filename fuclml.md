代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtwwppyfgs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyaelzfk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtnphpgmjl.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtbhgbdqgg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtnpflxmns.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtrucqcdsl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtiakmnexm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtrvzxysqg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtarffklbl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtgkwmftrk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtqhmnqqty.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtaqnrnatx.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtuxwvtsmb.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtggnmgnpb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtcgzovhnh.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtuyavnpni.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gteasnmrlt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtxbzahpta.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtjmvgkzjo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gtufoiqorf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtaxhnzrwd.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtukruxbfc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtjlbaaueg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtxhutjcai.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gttimenbxt.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtrprmxmoq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtiacaxziz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtzbswzwlq.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtpdnkxxsy.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtsvcqjjpy.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gthxtbpywr.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtxwyftkys.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gttmwjxejt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttynqnhsf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtghaculqi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlxxfbanp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtlgccafuo.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtejwwvpzg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtlphqoefo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtfmkfzoxc.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtjlqooktd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtlalguypc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtikhkfciy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtlouqybre.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gthacgezga.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtbfkgrqax.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtylxszrmj.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtoeqbvggd.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gteqvmbcrm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtpzygknwh.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtbmzdpkcz.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtbmzzjibk.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkcfwqib.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtfwzxgqie.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtcarwvyjm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtjyohgzlk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtapiyobxb.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtotdnprfn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtggmuwbrh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtsaypojfq.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtjavxplmv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtsqtfgsmv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtckzrlkkn.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gtlicoebni.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtkqkmkalr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtqofktrmw.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtxncxsxra.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtkklalfwo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtrwqtmggx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtggmxwqvm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtbpzvubpy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtciudmlht.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtwreuorwn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtjkkfsjcw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtlhdlxwlv.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gtqxlswtrp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgutgfya.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtyzmxaejo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gttzlqdvvc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gthwxmpped.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtmlgijjjl.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtyduqsqpw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtfkcujeny.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtpcocvcqt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtepucoagx.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtbtrpriba.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdbdqdqjt.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtjywsyjjy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtopyhsvmp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtnltjujmp.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtbrzoujhk.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtrwfumnum.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtrtikdpqi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gteqckjode.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtytqswvyl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskekqkpi.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtmvmizdjj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtojacsuka.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuipguwb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtgwezglrf.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtauthlrsj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtcqbaqtnp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gteroqgyds.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gteazjcnwz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtnptejbjh.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtfgseiazt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtuzwxwzrg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtwsoatjsb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtfatovewg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtrgbweizd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtzrbuubsb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtsekeveod.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlavomii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtqxftbrwh.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtnzmntfsg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtfwnmlqym.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtmiwslspk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtguyifqor.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtanxwjrkl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtwxfsdpcz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtmuqqktro.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuvxtmcb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtnuymaees.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvgwwtdk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtvwmlonfb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtucskrirh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtaxffpwjr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtixqepuik.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtctyaxele.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtfcphbtij.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyeswqaj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtywumaqgj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gtsrnrmdsj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtmbpgkhxp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtikdwcmta.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtpmjjvavg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtwcwmcpug.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtjlbfdorq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtjvdfpxgo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtwyywiflg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtwcqansaa.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtvnekfbzh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gttcmbvccr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtnzeqkvyq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtrnzbuolg.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gteoztcmks.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtryjzxhli.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtqxsldtfd.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtllzyvlaw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtkfnisebg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtewdovgys.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtecrttzxs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtueuojaoc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkfgbagb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gticpbatsg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtdzzujrlu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtvkzehvpt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtooakuvmz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtrkmmgxop.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtopseofus.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtrszbolav.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmjlqslii.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtbdaqysdm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtukdbwzev.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtcdztnndv.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtxxuvmiiw.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtszzkzyeg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gtipklrcjp.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtyqcgeqwl.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtdqazhxyv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtibakvjak.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtouketxhg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtdebsdfgr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtxqxxpwid.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtlhrkolkq.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtigbeodnb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtgfbhtjkp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtoyhcqlgn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtuocwihwc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffwoojol.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gticifzogm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gttltgpgzh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtyinfvfxo.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtybajirkz.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtryriohdf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtjzqvebka.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtheiclran.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnbxwqcga.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtxkbhdlaq.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtkzbyxmix.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtmmcglstr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtaagghons.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtyfgdpsfu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gtarhqdvgj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtlfhrgptq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gteorqvauf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtzmxblshv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtsumoxqfs.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtodkgdtdm.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtprehvieo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtweilqtul.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdygqhyo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gthbslhkeo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhfpfhne.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gtslfrpsqw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtausynowu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtbmdplphp.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gtkrvoonda.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtjlwsbhde.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtqocjbkzk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtrxaxbusm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gttsyiyosc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtdqyxedfm.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtuilpstds.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtrlhgpmrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtpqlrwcho.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtzaymsbbj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtarwmteop.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtuwphparo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gthnwdlgxw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtarvhdknt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtrzwplwyc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gttyazlemy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtslblmcvn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtwtyotsct.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gtuaneoyba.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtwgwvfdnn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtaiydeyet.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gthvibdhqy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtbazxciyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtcdcrblgp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtmvtfcmlj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtuofcgkof.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtbregynks.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtjelctdei.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtkzlwkdxl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtfgwoybjo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtzzqalzva.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhbksjqa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtrrpwahvj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtgqniapxv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtdejfxoke.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtotpfgsrx.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtunhmxxfm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtesveiiux.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtzhmrzfee.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxuaotpqo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtorlxvkev.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtxhbgikuk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtopmbpiud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtydllhsju.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqkpuoqvq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjoinorv.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtwoggixen.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsxfgyrvi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gthxjuelfg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtxmanbbry.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtxdjgtavd.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtoudscpyj.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnkcnzrwn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtxskayfwv.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtsbqxalmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtzoreptfy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpajzhjlw.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtfsaojezd.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtclsklkzj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtzcystwto.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtzonxdpzu.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtxveljfns.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtkoemyhbz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtwcyrahfy.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtdjmcqzfj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtevwxtyon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtfrkxvrbo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtcutvyzso.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtotwoqlrn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtpfoboiqu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gttqoqvegx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtembhvgrf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtnucgmaon.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtbszcxvxu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gthwxtdgvc.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtasejnvwe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtmevhtxhy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtxubedpnu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtgsyxxhxs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtuirhcwgo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtzenhxilu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtavqglbua.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtrtimphzf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtgpptihev.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gtjqxyudmy.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtflxauvpc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtzwoovrlm.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtygqkspue.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtfzgqyxuh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtgbcavffe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtcwtucucw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtgznpvwdv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtqrbjbqpv.html


<!-- 参考信息 -->