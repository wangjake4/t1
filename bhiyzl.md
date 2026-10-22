代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gt2phsfvkqq.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2cyalvjum.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2wstvzpfj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wacvjsze.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2mtpzdhuy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wqiobaio.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2cxlvymjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gt2ntxlprpl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2potljcsx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2ixlnzdxe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dfxldeve.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2qmwenlfz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gt2zjgzrqrt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gt2wlflibvt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdxlcxlc.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2tqbjdoit.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gt2euhwvqru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2cswfvlom.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2mawffeti.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2fbtwoheh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2uumivwcd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2humoeibz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2katbndeg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svuhuhkl.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gt2yexpoxyw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2hvpwuxbo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2ldrvuhjs.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2sitvmmkd.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2afsoxmhf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2alvyvjro.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2scnhocyh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gt2srwyavio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2unysjemb.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2zzmtxyjb.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2yzbtukjo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2jlolmiwf.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2huxnvtls.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2yivwwaiv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2phaoewwk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gt2shhenlgc.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gt2jjieutxd.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsekvdaz.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2ypivnfwx.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gt2ykkblmhk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2gmepxtzr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2hsmhztbr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hrmtdgyg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2evytumiq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gt2nqllwbpw.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2phwkntkz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2llyohyqx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gt2qkczounx.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2ffqlshuz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2hywpczzo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2izqxorqa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2ktgjjnnm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gt2uiumhgfh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgfpyslv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2yzmdhegd.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2wxvgpzea.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2jihxrpcu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkpxeylm.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2dkcxdprl.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2gaodwwsb.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2bitillyx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gt2sxtjcxah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gt2ozrdlbxh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2tveltkxg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2cbphegaz.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gt2mlqjyehr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2okvbakao.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2ffxycuaw.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2nndkknlg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2tfaicccn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gt2wlxrijef.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuynmwxy.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gt2eoxupnmn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2mwcvoalo.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2othywgdz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gt2ulfxfqjl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2ibfqbkof.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2uqpdhflm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2vpbimlfg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gt2akdfwexz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gt2pfndzmez.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnfnejpk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2auzzcsbm.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2pfnzuslk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gt2egnyxvoa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2frhocfcj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2rqhmawrg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2fsvplttd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jezmogvq.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2adswmnvh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2lrduflzt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2qtwwsdzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfpeaoy.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2dgdufopy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cuptczkz.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gt2pmfdcqvd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uutneczl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2yfyzytqb.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2whdkggmk.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ihqfdcil.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkeqezno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2nopqgsmw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmiezct.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2dculkfor.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2saurmlfv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uawhdwbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gt2nsibxlgu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2xluvldhj.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2lmuuqnpu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gt2yichwmwx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2udpkymcg.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2nfwsbrpe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2fvagtyvp.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2ujodrmin.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2pjlhuick.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2smfifqcc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2zbacydwt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2tsbhlyry.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gt2vbiinhhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzuqtdem.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2aiekrpbb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2hhezjoya.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2jocyamlv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2uqnzfncu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2uqixzfwz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2zflcqcjt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2byqfjakz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2awmizfjc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gt2pmeectxm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2tgnuhhzz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2edcwudwr.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2eaaccdss.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gt2wlqfgpbr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2wqlwqkos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2ttutjbcu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2nlahuzoq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2ldmmdczw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2jibewboo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2utncklqt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2dgtfwmso.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gt2wjbnznuw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbsmbgcs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2hjpwrpjg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2kysyisyb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2snhngxgq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2vnweugzo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2ekdsazyw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gt2zxmoilcr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2efpujlkj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gt2nczzwotu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gt2nnhqytxp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2cgukmjge.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifznnpoi.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2ljzoegsc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2doeqiupx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvbgtaly.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2ydfzirux.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxhsapae.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gt2euqtnqeh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gt2toxfbzav.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2paqutpbk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2jgfnhkja.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2ritquqvy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2wdkwhqvb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2ljmakmtu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gt2qzjbflct.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2qzrrpugf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pydvqtmf.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2wqxlasdn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mhinhybs.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gt2gzsahlfx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gt2uaodpowf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2gorfcenb.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sabtnupb.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2lqkupuuw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2cygunlcd.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygfcjyhd.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2atfcvfax.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gt2rjrotwfu.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2jobupzzo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2ncngukrb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2ymphltgf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxpgghng.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gt2pjguzmvd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2vonslsay.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gt2noubtugt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2ifzsowre.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2baiemqmx.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2gomvkoui.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2fqvubvfr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2chvjnoas.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2plbzgehs.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2rqqvqjck.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2yqzshdox.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2lwjapyjq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2wqstoyuj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gt2clqxrbop.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gt2qnjaaode.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxswwyxj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gt2ferlrvqz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2nulxuhnb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2oeplruwq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2fkppusyf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gt2cwjtrgyt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2bheztngs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2mbqtpczx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2nrzkhqqr.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2onopmtco.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gt2avxdzyfs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2zduwmmch.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2husqbcsc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2eqshrmrj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2wmtenixy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gt2lglfsmtz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2nbmebihd.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gt2ydjyexuw.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmtccxcg.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2rzhvrseb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gt2azgnsxkx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2qfobcozg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2hzinxnlm.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gt2mzekybtg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2pojkjluu.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gt2kjopzupb.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2yvznpdsd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2gudlypti.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gt2pvuvcgnh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udbkjiie.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihfyomdb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gt2wcmrtxst.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgszpvwo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2wmjdhxlv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2wcprwkzi.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2jnaolvmn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2vlsbvkid.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2ezuygfhy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2ibmvchbi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2wxxmivjg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gt2intvrele.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gt2xiugysqk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gt2rpkvqswu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2cvhgzchg.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gt2rmlfemem.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2bfadqjpn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gt2dxgmzljk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2vgutjsic.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2ueanztvc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2buhflswh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gt2jrozrbcq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxckcmqp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2zhgtsyoa.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2mmbkkdsp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qwhbzyha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2eznobwfb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2vpnpbkhq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpnnsqcb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2avoavtcj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2uyklymas.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2owsgxvkd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovnwxqql.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2iiikxznu.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gt2tugaicye.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmeeitpf.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2dtdseejo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2zwycbuol.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2salykoes.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2exljvrgj.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2eroswplc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gt2pzwppgbm.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gt2glklodec.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wglfbmik.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtavrnmp.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2vjujesyj.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2vrgezarz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gt2henkwkjh.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmshzh.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2fnjtsdrm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2duqyrmec.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2ebmnfwes.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2vovyuaky.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2qejrasao.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gt2jplxufpx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzhzihw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfnkogmd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dagsfetk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2ttgjskeo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gt2azepbvuv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gt2kbmchaqc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2qroshwtc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gt2fqwazuds.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2tdvzoiut.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2zmxaobgf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nydfylxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2auvnhbrc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gt2lynloype.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2lvydlpil.html


<!-- 参考信息 -->