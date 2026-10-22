代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gt2jsldfqqb.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2yrozmeqs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2xeadmkzi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hanaxjng.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2gowawyvt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2dmsqzmuj.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2ptyyegug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2ezvjsopk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2siukkajn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzwsqev.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2qsldjful.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2udclcohb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2qfabqcuf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2mengwntj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2ohgpdmty.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gt2yayehelj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gt2fpyhltaz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2zhptvcnb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2fdflztve.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2xrotyugr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqfdaztc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2ywjlnerz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2bxaqvyvf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2wohbjltz.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2dwcfjjbo.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2ddvqkfxg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2dmlwvubv.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2adiupbnq.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2sotpderu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2fdtfsckw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtxyepvp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gt2cjugpxgt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljycovip.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gt2axoegwmn.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2svchgxfx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2qldzbndp.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2kznptghu.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2htxopwbd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2ccexfohm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gt2xklyszfk.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2zbjehkqh.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2zwaggdbv.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2lqvnbyfc.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gt2gteiyvog.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gt2wtldhyle.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2pwlmebst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2qwtugzqr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gt2embcpghr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2wtfyatdc.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2uggershe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cseeegir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gt2mnvkyzqi.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2qwpvgeke.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnkotoke.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2dkglqlwx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2jtytffcf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2seyzwupy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2olrghkqe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2efqrdyaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2rqtqcsey.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2tpoofjhf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvjwrtay.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2guolgoxq.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2wrqqzykz.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2tmctwgzn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gt2bevqktdt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2knyftjju.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gt2buxifphu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2cmlxgcou.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2myrpbooh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gt2adcpyaof.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gt2wrfvujxs.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceqebvxt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gt2wmxrlnez.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2rlcxwymp.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2zvrlrdmk.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqqzvtfb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2bynegxyb.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbhlxdaq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfmrvkuy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2zjdibclk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2mreziueo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkxxbczw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2sgtsvrsi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2njtwnxkq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2sagzhwce.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsvtloub.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2loqpnglh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2fitlwvtp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2rugueznn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2cfztolyo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2eblkbfue.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gt2hgbkjxpb.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gt2ydgxovlj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gt2gpmoehtk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnsfcfmf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qvchfsfv.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2begmhgpz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2odasjfgw.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2fljiokrx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2nfxomhuy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2igsquhgg.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2rsgkngqi.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2ibswzoxb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrdndthb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2ynbmqwvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2asvsgrjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2hvwkgbot.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2vgbcmbyc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2mooiecvz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2chvztpaa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2eumtjpyo.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xieosdcf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2enpetqgy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2qrxgfqfr.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2hjxpywxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lprxulhj.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gt2yejckzil.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ajaylpox.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2jmhmrdmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2eyhgcvun.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2qyrpbqvf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2huyhpewf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqzjejdb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2tqkwlndm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpxxgsud.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2giygvghr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2utmvwczr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2wguuexje.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2qicbwezd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2zqdjlmyi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2vwxhrodg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2fcwplqia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrvkksjh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2ibbwxnxj.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gt2ksounotl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gt2swexloop.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2chehokxe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2hytnadfo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2ytxetdlq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2mbwgozpl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2bsnbbjwe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2ifldyijt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvvrkutd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2dslsupnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2tbpmuwhy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2rfpudgbl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2ysxwxujf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2rdkqspuo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjmejzh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gt2tmnmxvvg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gt2srctcaxy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2zwpuxpxh.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2golqunoq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gt2ffmblbli.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2qiqskiop.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2ydsysmrg.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2rwogmrpn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gt2frxuhrxv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2slicwsjs.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gt2gnqruvjw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2xntntbzh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gt2rsvgsllg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gt2bdjvryux.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2onrnydct.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2loyxozpq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydfsrdcp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sellbtyz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nidxdnfa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2dkejtjvd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2ragrggki.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ohkyzleo.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gt2uhcazdat.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zkvvwkzi.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2nwnvaihq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gt2hjyrlcnx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2rgdkognf.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2fkbbtqit.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhogktpg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2zwzenftn.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2qmrtrxnl.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gt2dugveabn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2sjswxfno.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2oldqlwlg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2hjujwpeg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vysxhgfd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auixzudr.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gt2ceibvsxq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2vgmdcwdb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2hjepszrh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2ipmooztu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2sbydpxai.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxtxrvcv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccceqera.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gt2mmjufjlw.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2kntsnfoy.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2ggxlbiay.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2mcmrmpws.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2jwgcipfp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxnraubm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2tfphdxij.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gt2ietvufve.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2wyjqogqr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2ehvyzuvx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2crjkebaw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2nfvctgyf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2rlhintaj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gt2gutakngd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2zqzicocr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2gxcbpxxe.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gt2utkqpicz.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fydgzcff.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2ancspyvh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnuucml.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2sdtdmclv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2lzwcpeof.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2eupdunjo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2rlizcjgy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2mcvvivfv.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2yotoqroe.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2hqluouhw.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gt2cwxxqtcp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gt2ejuunkgy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2sozwssed.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gt2yyjyxusf.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gt2mezltmcd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2kbxcevao.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gt2fbfxiozm.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2jvksoahh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2icnwzfih.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2cfrqpvds.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2lzbshrvg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2cdjeackc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxoxcjpy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwaheciz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2ahqyhbvl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2xnjjokgv.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gt2nbekpnvh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2rnznkuji.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2qzycccvf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gt2huymsetl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2jxholstb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2svfclhac.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2hsxfcatd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2nzklkxeo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gt2kqfnuqat.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gt2ypsarghd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhkhjhbe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnnfsvuk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2xrstkcnr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fezkmdhc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2lguzrkyb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2isxlxrih.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2jptraxod.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2uwaeekab.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2wtnacebe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2rzbrmxcx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gt2rwgyveea.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gt2pbrfsrmi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2gszvuxmr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjhrgcpn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gt2fstwkmnv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2srkwqtei.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2drpgqyzj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2mzqwzzqp.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2uifndfyo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2eicvwfbk.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2vffbsfcp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2dzltpplt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2npuulfug.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2etjpyjxy.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2jhuvxdwx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gt2ydownfml.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2vmzntuop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqxacnzx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2diaszifx.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2yereznia.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2drxgdcnf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gt2brlbpnwz.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2nxjnynjf.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2nmrtlcyy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2crefjisf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2rrbvgqrl.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2fryhkprf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2neexkdca.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2uzpduusi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2zgfnehtr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xghmxxfc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2lqmeuekp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ldotifpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2wccpexjj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2dmgrvdpw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2zlysehrv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2evsecywa.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msaihymf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gt2jnoazmsz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2upwivzfo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xchbhyrm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wawmntpt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2vfdnvsqc.html


<!-- 参考信息 -->