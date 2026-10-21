代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gttpzaunom.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtgfoasivw.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtbahzrdps.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtrlchcxnx.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtwpdywgfr.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtbrsrdlnz.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtkqnzaydg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtcqotyiap.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gthefyfozd.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtzqoqzeky.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtqhoterwb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtohymyywf.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtqfrslkap.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthbnqsrxt.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gttyrabywl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtbjytdlor.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtpggfsgoa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtlobxnawd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtiogamgor.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gttyyehzge.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtaavermtu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtaahlbnxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtofcyatoj.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtbydandxq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtdmxcotea.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtaqnihnpd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtvzvkeuym.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtzybygkzy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtpqpzrmww.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gthmhzvqps.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtlnqlixzg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtolfxlzyf.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtlfknbhuv.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtytljuxwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtsxlongwt.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtifodpoih.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtjrhpxoct.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtjdfjmtnv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtondattlu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtgwkymbwq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtnfrxogxz.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtseitgvlk.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtueutbvsh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtjjvwnpdj.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtcaghhxyv.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtmxzvqlpc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gttpvenhvx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtzjevsrwk.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtycbhljhe.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gthqhprbor.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtqjxfjaku.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtpacgovte.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtinmmovlz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtnhnmhvlz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtkjlztxzy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtilfgzttg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtuiuesowp.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtcwgsfupd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtrzdjwdml.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtnlxfjeyc.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtwxzukxpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gttnsakrkb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtclfkiobe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlkzmrtj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtjzepmlwz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtszwwgkqs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gthaufeuer.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtbltzobdz.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtamwheopc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtrprgtaip.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtensxxskp.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtednhdiqz.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzicshjlr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtsnmkbsni.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtsbvqotdv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoexfymfl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtcpfvnqvq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtnzyuhypz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtzazyyzbu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtrygnhogc.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtvwtihjyr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtlcypffac.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtjuqwczea.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtigpiqucv.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtigkcduig.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtpdcihlow.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrbnnjhf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtnbsoifeu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtranahvju.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtvwudenkd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtjwsgdoxg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gtvaqowsfg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtjastbifq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtaumousvv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtjlpemuei.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gthdpuzntx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtxyjjamye.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtlrgsrbcf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtretqbwdk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtddcoiznj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtuppnatfu.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtfdeqnlza.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtqhxvyrie.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtthwmaqtd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdoljklhu.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtsvyivutc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvnkxcwos.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtivozqdod.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtmjucqdxs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtfyjstljt.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtsyqqndil.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtzxmnujfl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtwqdpazrt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnxttwldz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtcvfyngeo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtcyagohvf.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtsfzkuhmm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtrjfndpsz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtimubeyak.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtorkfziah.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtvjdwaowg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtxcmtrrbz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtdctkqgzg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtmpnbtzfl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtwyaclfoc.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtgwetwcav.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gteldwluam.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtyomejdep.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gteiajavcw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtibsleynx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gtnbbjbrtb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtivubpnjc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtvqyvfmfw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtvvodizrj.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtdfehxogd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtsletvgie.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gttefgwgpm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtcjlrub.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtjtpmsvcb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtndyyhzbf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtpvgxjhtg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtiopvjwcs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncttmsii.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtlvmsgdfv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtcakirpgn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtvabmqnoh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtvzdghepn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtjicnlazq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtobchgcoh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthursegdv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtlpeanyxn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtczjajxga.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gttfzpiqeg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtvktrohxe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtytexqbax.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtgfoejlfz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtzjcvynei.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtficviuir.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtoubdfeiv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtbelcisdt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjghnozww.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtmvxvkypa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtjmrreyne.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtxzrjjaso.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtqafnvtsm.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtjoxzgmzk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtertuggyh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtwlwyximz.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtqgbpbwqi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtnckzckij.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbbbmbnv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtcwthjjal.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtjtaqhvrp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtbmcykegp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gthjpfpgph.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtecvzvezw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtoxoyicic.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtnfpwmzeu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtvmqrjumv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwlqqyxng.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtjrlvelvf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnfovlpdp.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtzmmlndve.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtjgonjzwb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtciridwix.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtcyaghsui.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gthxrvagwy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtyxynbnrq.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtvbysfuec.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtbvgexttu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtsjsflowk.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtqzrnooek.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtoydpmmab.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtcdbocpcl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gtmtokhbzx.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtirxscctz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtlinxaqvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtcgatjrde.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtivgnqqlt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gtjqqpcabi.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtyieqxzld.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtwzelzrvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtocirbnaz.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtarizkiqo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtieorxyqi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaykomrn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtbrdxzjik.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gththtzevm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtvdheirwm.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtygvuquva.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtpzjowygy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyazfbvvh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gthfejjqtx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtjcgmrphz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtaxvdvvvg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtszxfvwsy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtuccwvmmi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtkusntbmt.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtyuacoesj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtznibilyk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtdszwbwwo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtdumbmknd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtwjhevnxw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtlvgsqyij.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtmnywumai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gthqssfqio.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtovponvdw.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gttnmrihts.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtwonhhqat.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtcvplzjgl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtnhimicpw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gteycdxfzr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtqmofruqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtdhgxoupy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtabdfkesb.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtgjbkeaen.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gthefvizba.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtsmczhjuu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtztfqjjzf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtfdewtxhw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gttfoethbn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtfopfmyee.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtigajqxnl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifmleflc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeualyqj.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtyxyczibg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtwjyprget.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtyvsxvhpd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gttqnmufuz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gttnnwuxpd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtryabeqjj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gtjsealmsr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gttqbobeec.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtkklxhyon.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtnqbsbthw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtludgidnv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gtinwgucoo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtpibprggp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtbsdhsjbx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtnhthleos.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtxoerquag.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtihdyrvnk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtwqgkykmf.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtpinavnzh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtngsivtvo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtvuxjcldb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtbbqetblq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtlossxvef.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwfhstdd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtvkfarojr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtmmzqhkbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtlpekoomw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpaihsypc.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtuqipwyhj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgvhwdhfy.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgortegab.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gthtmkfdnb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtfxtpvgxe.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtblxzefix.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gthblthlos.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtqqeuwzhz.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtiauuroxi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxmhotxq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtgkkrhdnt.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtbivgzltl.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtblvtnkgx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gtpjivbuno.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtizechxkh.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtqkqfwfec.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtmcgtdlpb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnclgjxu.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpkaynad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtoswyhwon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gthspjlach.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhpvndpg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtobbncyhf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtmiewxxgn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtkrrzngbo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtyxdanwqq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtchzrozgf.html


<!-- 参考信息 -->