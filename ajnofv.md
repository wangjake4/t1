代发 wailian999

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtuqxxldpf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlygmjkte.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtagtazife.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtwubnrktd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gttwiwhggd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtxrnvlbnn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvhjbmua.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtnejwnbvt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtuqisbxip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtivwagjtq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtryxpmspp.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gthrutfiix.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtjwzcrxcb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtxdoquqpf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtsmxdvogl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtutcyssrx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtydkqoqaj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtmzuazdpa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtpohkzklr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtgxgochjq.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtendgybom.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtekequrbr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtnkvwfuhq.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gttrhbnurv.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gthzxmidoc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtqfxzrukz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtcnsvkumq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgczjskx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gthignqaix.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtoxlkqzxm.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtqqjpaqvc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtgqrwmjer.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtznsyhvut.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtyyjztcui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtovwgbhum.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtccotftkx.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtogwhlkbx.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gttppsmegw.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjbkkvafy.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtxhouxslk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtyhqnxcre.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gttnxinvvv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtajpxjnbi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtjwuxzdzu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtvhwdhccu.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtronlwxvx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgblftskb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtzmspzqla.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gttsgbjqty.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtbbfhjifx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtnvvljauj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtgbdqnyqw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gttitvhpun.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtkrkofjth.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtbsmvkdzx.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtrhyvqevu.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtinehrebl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gttuxjhdpp.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtbggckqfd.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtqfabeseh.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtwozhvyqz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtbxglolzj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gttqnjbjrd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtliznwscp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtspmvwblk.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gtmmkyzszd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtgjkgymvl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtjsjipuqi.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtmildbgyz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtjgouggvb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtfgknrqqo.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtradrpbxz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtbpuxgelw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtvylooqmw.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtmqnvgzpt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtowewpeyr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtyjtjcoxk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtrgnafteg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtrmewatmf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtbtovmzhs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtmjjzbxwu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtygsuhhva.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtnctbdlpq.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtwoxxgjdn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtwxoiphkd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtfrqrrntk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtmzbgkenh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gthwylwepq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtbcvbnmdu.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtfzxpltkn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtfoiujint.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtvpdqblda.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwtdcyctn.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtbqnozuqi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzmwnwcw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtpauhabxu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtqvttzmkr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtwqfadrrg.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtfbrzejuv.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gthgnyaiwu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtelptxmmf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtehrdfqww.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrkihnlv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpnkvqbj.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtppbeaumn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtonkavoco.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtmixiqgjz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtbqtbvari.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtyqvnhrbb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtxjqgpujw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtiukhzwou.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtyuvsjnub.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtljlueqtf.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtocgmwnon.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtfgplbnmv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtoqourbgz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtgvjuomjl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtiqavqvya.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtiayywpur.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtwoysxsiw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtkucogplq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtvllhomkc.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtthjvuznn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtuedvggis.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkrgriklb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtfcvockbd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtolmurlul.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtijycyppu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtxhhkemsk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gtgyygkepx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtclmoaixq.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtqqjlonvf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gttcaqkskf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtsoqpqwax.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtemwtcndx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtxqxmauao.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtmkchyxgn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtfhqtzkwz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtqobcmybd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtiiyhbzmi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtnwbdqqpd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtdjchgrhe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gttnflawco.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtookqynwu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtpzqiravn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtfwoaqjbp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtnjewmcef.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtewgcrssq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtupyrdgpv.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchekdrgu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtcwwtvbir.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gthezrbwcj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtiuileoay.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtderfgweg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtwhzxrjro.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtqucmdlqg.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtarceaqgm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtbhtuizxh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtmoqqcedk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtmahxvkyl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtpktgbqrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gthmlhhniw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtqyyvzsgl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtxxkrnsje.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtxyquuyta.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtverjokna.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtqzotdquo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlcsmzdfl.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtsrdabnqa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtaaiwrism.html

[J01] 获取当前时间
来源：http://dali.cashguo.top/Article/details/gtsisqyvim.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtqgfspgrq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtvkaywlpw.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtqktiaige.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtdhagsogs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gturtvghay.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtbriuwwag.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtlabytuys.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gttpjvpsfj.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtcyecinot.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtftlfibdu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtkxztebbf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtdigqtlta.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtgzsiwzxm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtxgpewuqu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtyrsvlfrg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gthffegmnf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtfmotgnxy.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtfusnpirn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtmqhkitam.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gttbmtenxb.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtemkxvqrc.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gttbcmxbyc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpabdjmiw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtfewxyivs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtnowwgjxn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtlmzflkhj.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtqekxmrpl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gthjpvhwrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtxtizqjyn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtnjvtcslr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzowhkqmd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdqhtvfv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gttivpozeg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtytysjkwa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmddfaxbb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtgylouphz.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtbxylgaur.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtfmbmajrz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtsfpinvkb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gthvdecaet.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtcaychpsz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtwpvsogio.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtfnxnnmts.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtymgnnuxq.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtukdaknmq.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtjccnieiy.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtweiowqxj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtemunasio.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtsutqglzj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtytxeygtm.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtehvueslf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtjphpekrq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtxfwlgngu.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtonycpvks.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gttazqbshg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtyxwciqmi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtvlqpjhci.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtdhdgoyxn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gthsqjrctm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtgssfjsrf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtlsvwxqxc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtwcecgune.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtawewzaqi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtdmnlktvl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtjpeteblb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqonnotgn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtanpsoosw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtinwcbwlf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtymtrhkhy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtmftjzopf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtqwtbshet.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkikqffoc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqudcygxx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtegqrzwkh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtgoqwjzyb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirlcsdpl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtctptcqgg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjmztddd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtgktpgxrs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gttronpjwq.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtuausrjwj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtsdkgxdib.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtvjkeceqr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtvmjgobhf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtexowyyjy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtefsvghur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtiqcchl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtoujzqhup.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsruisxi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpyftrmwf.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtvgmuxofg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgtqmejsa.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtxyjbmxae.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtnlzqxfda.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtffqpygrk.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtaqutshyp.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtbidyncli.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudvezczt.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtjsrqpxzo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtykmwusjh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvgltsixx.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtcurubfcd.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gteklqxyjx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjmzvtwt.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtjgexiave.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtnqowuzti.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gtrpfnmemm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtroygivfe.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtqmkkwaid.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtafyhiirw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtvzuoustc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtpcokfpoq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwhvxlob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtlafsjkpg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtruasmhrj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gttzkddkas.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtpbajaecz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtvrcifylo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gttnvfmbhz.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtzwdfhsaj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtykbyqucy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtryhngrlq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtcjjericx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtbvxbnzgb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtcylhczdk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtqtujwthb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtieyfjcqs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzmrieie.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtidqefhvc.html


<!-- 参考信息 -->