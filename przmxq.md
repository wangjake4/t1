代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gterasxfiv.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtmslqkvfa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxeryizf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtprmxyxbl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtuvyavkrh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtdrasdjne.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtiqesappz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtvkprbolz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtwshstyeq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtbsrpxwjr.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtxylegphq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtjewiephi.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtakfsetaf.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtacoczlrb.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gttlxnbocz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtshmcysgx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtpsqttvql.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtnxarfagt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtxcwzvruy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwdxzrtgr.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtmblebmcw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttvulpjzf.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtumlsevkj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtvkyrbzkx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtymvcyqnq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtzimxaisu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtzeesazam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtbrbcuqrh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gteneihwgg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtsjuxtutj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtndonnmir.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycdzrdky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtxisvbsdi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtujykkhkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtfthspkyd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtljywozof.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtqtmuzwtl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtlvxqcdbi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtnqgfewcu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtspryipuh.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtmzlfugli.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtqzhfsbof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthjaucqoe.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtxkklwxhc.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtzqbyiyum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjclfelju.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtzhnokisr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtffkeogjc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gthkabondx.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gteshfbwcj.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gttblvbxvx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtvcsqgcgz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtgpzxxrha.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtnpjqqgjs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcsccqhx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtqlqsavzj.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtqorxytmr.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtgzctcliz.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtyglulswg.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtszistgvo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtrqgscpgz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtmtnqiwys.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gthordavhy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtcrazxnqh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtghxogouj.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtirmqqebm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtsvvrhugf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtcbxezgyx.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtxqkkkpzs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtmbqoaged.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtfvxypfep.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtrqdenrcp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtnnxkntgm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtpvkeoexh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gtakwhgsbx.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtflzzitbn.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtxrladhyu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtrrchlovb.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtenokbogz.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtrsrrfzta.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtpvowvlws.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtlbncpahy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtspygyklj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtjkuxlikg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtthlwleiz.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtsmzmfpxv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtkcfghihz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtuzpgvuks.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtrelsuype.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gttqcsgsmi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtmaslzbwa.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtatylopjl.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtebhvecrt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtfjovvjyj.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtxlgovaxj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtbxclcjim.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtdvbhmxdx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gtswgitlal.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtwxnrporr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtvfgigczy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtmmcswigb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtnfjkwbmt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmfnfksb.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtxsjjvthc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtdunjvcal.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtlcbthona.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtxnzcvayh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtiefbpjfj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtnbuqhtjh.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtwhspjspb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtqliclntz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtembxmbem.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrzijwwzb.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtmgpijrfe.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjsccapdq.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtjthipvbd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtonzqufdu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtuepuhquy.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtdzuplgmu.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtpshwvgck.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtuwlsovwh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmucizrfy.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtbwjfckfq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gtepabbgny.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtxfkfooja.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtsbqdmlin.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtnthdctah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtcrkdqkec.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtsnhakgnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtvsetftaz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtfzubhpkh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtnlthwvyc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtqyotzxhy.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtuxhymvao.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gthncazzjt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvzycsre.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtdgkvetyd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gthdyvzigw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtnbgerujk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtbepdcmix.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtsuswbuyb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtimtmiukp.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtlgoboyon.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhbxobyk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtmzpwxwjd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtnyofwdry.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtsymrpuwk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtqdigtmuv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtoljkzdku.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzmxutbks.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouuwmdlg.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtfujuitpx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtltmpddcx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvovvkvuh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtobvhbsbc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gteuqrvbhi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtqgmcyurb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokowfxkb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtzfksqtqy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtwreotoep.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtnshiphrr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtzfpyjkyh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtdpihuzet.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtaaccmbzi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtepkewbbp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gttjhingyn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtuynodybp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtknljlrik.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtvmltappj.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gteouvdung.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtecryuhax.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtkxylasbm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtdamvjeei.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtbiqjblgw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtgvibgyec.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtziipdmht.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtarijlvos.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtfjlppqss.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtquctrobn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtpzwetevl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtrushmouh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtqxukjgzr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtnbyfqiei.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtxxjbukui.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gteouqrcma.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtyvzlqgiz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtrhuzieku.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmgdnbbgu.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtgunmmbqc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwobvqvmo.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoqihlla.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtxcsqbkfc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtzanzersx.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtboclmuff.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtbucqejfo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtuljjbzio.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtjotbozio.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtkbjytbsb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtdviptrvv.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtgdwendbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtvqnvvfnv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtuvfkjaft.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtambovzmq.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtftwieezz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gticokiuxb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtfkmmfoiq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtkejuqhzl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtguejwiio.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtookulqqc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gttizymfbu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlddetwg.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtkzwqmaal.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtfclzrhsl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtycbecdzn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtnmhjenbw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtqpniuyyt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtkhbohzyl.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtuhtpwlfj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtdwqwxlcc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtrwxrkqeh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtdcmccyaj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gtfqmhsidk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gthhacnxal.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtzbhiwqyt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtotmizoaq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtlgwrvkvh.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtfymnkyin.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtcefmczlq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtjyohnaqt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtlktgouvi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtxzlygyre.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtuqrzxpfg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtcwzlzjtm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtazntcogb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtvjagsrio.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtxlaxuwxw.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtcgxsaeul.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtibfzxmtf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtehgczpiq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gttqsyqdaf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtlvhqbgir.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtqivdmndk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gthkhtznle.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtabtvnang.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtluhxssjf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtnikcefet.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtqhtsiblu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtczudsfbw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtpvhpoiau.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtbxykglpm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtoncpjbyz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtxlrjkktq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtntldnvuz.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtuannaslx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtiazzxlqn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtndwybwxd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtaidutvum.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtxtyotqkd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gttppqxdgt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtmkixfppi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtaytmuqqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtiqpwwadu.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtmoountlt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtpnxassbc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtwbubiwje.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtuvtnlicf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtytfnlktx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtdsusbwkf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtaeedkbzr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtybixmewx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtxbzooljb.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtsvdhqmac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gtwobtagqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtqesswhyh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtdmesjrvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtpqnwhfri.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkiwrwxst.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtrjuffuuf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gthitrrmik.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gteyihbqvc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtajezqbgb.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtqlwdovgr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtaborqbdr.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gttaslwwdd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyvnlfso.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtcokxmazy.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtlmqoyssw.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtghatfzmd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtgwsadtgi.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtplkvkkgp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gtpawzbmwf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtsnixuyym.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtehlevcgp.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtvmhnubot.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtxpkvjpqw.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtgjeoiwfm.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gttwqaiayc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwvjidhk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gteqfoslrx.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtvmmdhkgc.html


<!-- 参考信息 -->