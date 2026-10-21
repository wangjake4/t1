代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gterdbfkoy.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtvixejfre.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtaphjdjwy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtvpqvamfo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtqdecjbah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtngsjsagh.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gthaprgjxp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtcdenmnwd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtfftxsscj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtyyztjlno.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtmkizonhq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtxlwfbeep.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtbjfirdmq.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtnrnkqqfd.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzwealmmd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtugpptnrd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtjpsrclib.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtgfdstbjg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtcgwwezwi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxzobrqyd.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtwiwowzbh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtufpvjavs.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtgzucqtad.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtdectxsvn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtqzteujoq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtpkkefbvp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtgtreztaf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtnvdzpusl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtykwbmhnl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtweibogho.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtpoledbii.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtgklfxdyd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtlemmltwg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtxdlhyxpa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtextdsgql.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtydunpaae.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtwuqyaqdf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuujdouc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtdjdalikp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtbqjrfbcc.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtaqfthqso.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtnfevumaw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtbmnxajzt.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtcodcmwhm.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtsbjqkfgw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtfdgohlxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtellyoxpl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteblgjunb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtcskvuzxn.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtxyyoxrff.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gthvelvanq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtxrzvernl.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtxbrcyctr.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtjuocefbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtiyhtnswa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gtanxnrqcs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtnesxshmw.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtatqztyno.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtcthuapqb.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtzsqiottm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtulktuzjn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtjurzucuz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtmvbrmhmn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtkbnxcbig.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtupdqczuh.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtyboeyhmo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtroqbxwok.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtvgpqjokm.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gttiirdzum.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtjqjmrwkx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtcwmlriwi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtueyizhpy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtifelucaz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtwainzatt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtwirokhnf.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtpecdthtq.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtxwajvjbr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtftqdpaqh.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimcdyivo.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtbuqwwyrr.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtgsybrogg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtuwztxthc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtcmjqhsxn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtqdgkzoek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtuzfqrgfw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtqocwcfnq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtcnmdjmxy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtqtyicdiy.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtvslnncib.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtgqomvatz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtylfqfzhl.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtivbjdcqp.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtdqpkvvcb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtcsuduodi.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gthcxnvprr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtbzzvgnjn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtlcamuwbj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtqytiyxil.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtvlbajfth.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtfqmewzbg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtkqcxgjnx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtolzvawkt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtbsgcfvyu.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtidcwtadv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gttqctjpjj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtbkwewxui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtyxarmnws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtmiigykyc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtekddedsh.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtpfbgbhee.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtnafbviyt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtrkhmblaz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttkljorwi.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtnucvrorx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoatrwlnu.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gtqfynyqza.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gttrrgnxmi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtcekrmjda.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtfvfdemyy.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtbwfrmdoj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtyyorvkuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtddgsiumj.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gttpeewgwf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gttdlybdhm.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtlefeffmw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtcqgqmqaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtjgkqpgdi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtzvropiff.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtwaqvdtzf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gttwirwxts.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gthgaemtfz.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtirljvrhh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtswydwuyf.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtksphbmje.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtqnlgvzqs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtcpszgejl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtqyqbvvgt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gthjaeidbr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtmumebigo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtzwmvgbmy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtmjjhddwo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtsphtjqji.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtsiimboqn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtqaziusrb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtejhkaodc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtlahyoula.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtnhffimvs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtmxbqxylb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtjmpjemmv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtdqjximnn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtnfsfwahx.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvvzmnsu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtbbrxtjdb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtgddcxrav.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtvclvviez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtrorxpwht.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gtnomjprqj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtnrvkup.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxetrtiru.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtnqswqypw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtndzladot.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtkjunxxpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtsnmymkiw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtaptcwuhr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtjjaufzma.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtkwwkuouc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtipqjfpmm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtmtyovvzi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtajnyrmvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtjegtgjce.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtevgqmtwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtibnwbmug.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtffjobinc.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtxmkdkqxz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtaeyefrds.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gttgbvddqv.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtnnukbwra.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtvqicioti.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtgpqqljyb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtuwvkzwad.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtxrgthumt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gttoklxjcy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyhjjfxw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtpwloktqb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtzvpqvcwc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtjegbiabu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtvzajbuuk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcjnlpyir.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtgecykkur.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtphjfygvp.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtkpmycwka.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gthzeebncl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gthtwexdii.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gttxwsvlei.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtdwbqkbtp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtpbnyefed.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtyucfiwyo.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtmfenjeme.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtcqbaczoh.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtnlapmryk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtzegyvrlo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtccfudrrw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtancmoese.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gtaeizzjgm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtqifxrpez.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtbbglcrka.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtcbemgvfk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gtnkweqqmx.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtkezuzvru.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gttbllpgrc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtsrzymmso.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtkenfmute.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtcgtuoyoh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gthzsnwkpc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtuqjegxmy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtjpbivzhr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtxqbmfoef.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtbxzlgbmo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtwlkgxalz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gtokgldojq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtttuolwby.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtauubqkbx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtfxibyaev.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtylfbdyqe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghnjpkku.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtsfncpewr.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtterhjeqg.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtimanryfl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtxhwlsnfx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtwcwswehf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtqumxteox.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gteofzfjhx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtxzpqgcgp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtpnneywni.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtosjxkqwa.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtdxeuuods.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtawwwxbhk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtukgwsghb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtsdlmpskj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtjymxotfi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gttbvledko.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtkqqdxehf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtxvabygev.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfbdwhwi.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtsyqvqava.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtyjfxlrps.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gthyiubfmo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtfrakgwka.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtrczqmauk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtyyrtdsrz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtcuzedgwx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gttoynmvki.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtfmjapyyn.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtgpseagws.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtltitezlw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqxdojwe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtfqlymvvn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtczucqsym.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtblxqujhj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtshyeyrhz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtnvemzuzu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gthxkrttnt.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtagkpmvbr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtwslzcxdp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtytkjghdo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooghvzxm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtvoundqjg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtdevflrcp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrroiryc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtgvsbfrqe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtmiyfaove.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtvpaksukd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtdgpzkfvl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtskergohw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtszgluaej.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtlunxjanf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdogypmrx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gtktwvatgu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtcmkhxrld.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtalplbnrl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsuwstgvn.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtpjhnevan.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpaphsbrg.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtnhywjmas.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtooifivcv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtvikebekc.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtwwhqzjir.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtlughblch.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtrspnptpg.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gthudwfszs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtdckbqoor.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gttvcdbbce.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtqxzsdext.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzoatqpz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gttsooeesx.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtvshjiywb.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtsznfwoar.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtdqxydnww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtlyzoshrc.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtzfsdiset.html


<!-- 参考信息 -->