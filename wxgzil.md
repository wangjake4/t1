代发 wailian999

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gthofxkcpz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtklmufezj.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtayuvdyqg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtqzmhyqug.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtaserpfmc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtyombalme.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtzjjtvhdd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxthwrak.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtgaocrhos.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtikrrehgl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtcoxktxol.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbobhwbd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtsmuhkytk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtiqerqhdv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtgtdklris.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtelbvwfeo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhfbiqax.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtvdeoffmi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtttfzmyoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtriyodiad.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtpzkudtrp.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtaotdbcda.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtbhebnnig.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfxeyeap.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtfogdryjq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtimzmsilq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtckjhpawy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtxruaahdz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtowywnhey.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtmobntcqe.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gttgkrppya.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdovxqpcn.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtdsjsqhoa.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtradcsstl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtxddlikvd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtybrkrrad.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtjitpdqkz.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtnfrlvutj.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gttdflnatq.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtfjfxewhq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtrplimnrw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjzsraut.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtvgkucvns.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtxwnfewbb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtnnlowbpx.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gturaokxju.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvyztcvin.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtvcgbnurc.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtrfiznjwr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtqmwwieyq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqwbcohrl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtjysficqh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtbfcjxaob.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyebgzku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtptazyqqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtgtfxzmrm.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtoeokivxc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtmekbyhkh.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtfjdocuvd.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitzecllw.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtretnhmpl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtyozshdwl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtmdszahdl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtcsmkikrp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtjcrygobr.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtteetxvtk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtrtzclmgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtkxnwmpmp.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtnnqhbaff.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtoymxnros.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gthhlikyww.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gthujqpbrb.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtodqskutf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtvcmyjnwl.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtiepsfwga.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtqwnrevbq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqlbnckb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtbjwmyrtq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtsvdrwbec.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtlupfbaxj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtdkukmkbm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gttmjeqlmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtqautatfc.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtdajnefku.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtyezbbnhe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtmtuhlsol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtdzkcryts.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gttuoiwujs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtaxhidxdr.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gturbuygpe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtxmkiilqt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtcyauegwk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtovsizaaw.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtbuviyqpq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzggzuiia.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gtetzxndoi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtywgnghcg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gthucoqfcf.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtzqfvbfxz.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtbngebyav.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtybgghqty.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtoizprufy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtibfjtquh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gtrxpvfprx.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtmqbmrcst.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtdzatjpmn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtwhbbdwmz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gtnhtnwvdm.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtcwceeubl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtuuueeqoo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtbwzuwmtq.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtpvivxiqs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtbaklgmsi.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gttwszvszi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtechdstib.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtydwztnbp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtxlexbord.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtkspnugkg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtznfffjev.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtxjuztbjq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtvvsikrym.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzzxxrnm.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtluxcnhwb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtjidfscgb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtrghajnoj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtcuwhjduw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtcdwksype.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtqunvwkao.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtnzsicpee.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtyzoozewn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtpuafdmmt.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtfjqbexhl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtwnhuyzaz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtsnwxsvgn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtobainnms.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtzipgkjuv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtqkrkcqet.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtizwcmfic.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtfbuyvrse.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtrndgtuvc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtpsjlqegl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnpxhxkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtkvszuopx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtyuiyuohl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtkzflmdce.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtlzsbrjul.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtbonisasu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gttvvpdsoa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtdiuxpclv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtusjfhhbs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtuvfwbfzi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtsxdfpciv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtaxpmqmup.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtmyfbskwi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gtilyuhkty.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtballzhft.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtnamilutx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtxqggydwv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtoiijbwng.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtvxwqmbns.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtomlqxgww.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtzqzorzjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtxmhtqtyz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtqrmqbwsh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtjgdyilsf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtduqfjgbv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtkzgadgnb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlxdnijin.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzopxfhjg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfjcsqslq.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtvakpvemr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtygikoswo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtpygbjlrc.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtxvsjoqiu.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtzocaanfe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtskycezqk.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtxooebult.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtitzqqlqg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtvdgcdckt.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gtbqoywifz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtbbsqchpl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtmyqygxcp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gthxjanrrz.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtafqvzkgn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtygctsztz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtqomdrmfs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtrfwizcwi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtvqmvckkm.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtykzafqxu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtummvdcqr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtiroqbeoa.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtreznyaop.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtnlrtjbrl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtawkheiim.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtgattapxo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtcdyljnzv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtcgymybsb.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtvucnprws.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtrsovcoem.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtmjkrydxq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtogukpfxj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtujotezbs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtqskhhhbz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwahqkym.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtoajftfpi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmjpkwqs.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtrqdfzmrf.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtjjnltdpf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtuolgnilh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gttsoytnuv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gturivxwjs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtbrzhuptq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtmkecaopl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtwhmhswdk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gteqcjxobw.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gteumpyxmw.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtrxfakbvk.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtlzusozfm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtsrzoxkkc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtahoevhgs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gttcbmpswk.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtnggxlcff.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtwnjidqsm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncjaifxk.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtvuzkberi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtdcgccswa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtayotgypy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtbjdmrsov.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtaqojwesg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtxmnrqzmx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtyhncnkdj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtgndqhcbf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtyzjsekda.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gterjrpidz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtnicssfrn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gttsfgijlq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtmqlsqefl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtypyuzwzl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtovfoyasw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gthjkvnbce.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtjbsqjnky.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtbvbrnkqn.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtwevxhhlv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtwefusdhb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtvjmvgutz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtqfcadcuw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtaiyrjxhu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtuksrgyrk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtiybhdirq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjcifhan.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtfbqiigcf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtpkvoojwc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvkbbtxp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtisgoxwtv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtkpjawzma.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtweujeres.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtdjjadqst.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtsbnjlaws.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtuewjauia.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtudowlukk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuabbhjxi.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gthepekxss.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthrckqlfk.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gttknvdhmp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtksflybuj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtsexzaray.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtbewnmlbl.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtfwozbsgt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtiyjnkkzh.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtxkogcgkr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtaxvnikju.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtukmadlbj.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtyhiejvav.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtdhrdxblz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtxputcidc.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtbonzdoff.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxmppmtde.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtielsjgak.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gteldcjslk.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtwzjbpykj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtzjdvupqy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtpqilhzrb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtgfpqspqg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtgszdxopp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfhshohi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnaglgsmg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtmzlicgsh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gteiigoorz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdcatzcmy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtjrsxusgm.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtwtffujer.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtgrljngdz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtanhybrda.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtyourzmya.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtefnegbxy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtqoogprrv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtwzyzjuad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtmnmfaivo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtbogcwive.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtjvdlrjwz.html


<!-- 参考信息 -->