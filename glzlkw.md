代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtramipmnz.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtbhfyjnlp.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtpahobueg.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmdoyypr.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtmnzzisoh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtgenzztrg.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtjrnkqrzp.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtoabjwllc.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtjomieypf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtelspuqsx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtsvudfeya.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtdfupsmmg.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtdrzefoja.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gteokskmgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtedwxkjxu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtuwsvalmp.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtrfhqolzc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gttlexluqt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtvigcikbe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtdwuajbei.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtnackgshz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gttfnpacyd.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gtjquhvzcj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtshghnltw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtucaonwac.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtcbbfkofn.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtkrfqcvjr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtqdastjnn.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtozlvrzww.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtjjtwjinh.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtowzdhgkx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtddbwhjji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtsqplrihx.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtgqsluuzz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtypqdggeb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgtfnuiua.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtdqqxpqhy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthjfaikdj.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gthsuhvhyt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtsvttuqzj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtskjelkkm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtsndzmftp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtxxweclfl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtwuwmsnnc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtmxomwkrh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtsqmhapxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcrshogek.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvqslyrk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtvbyajijr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtxerzrxtc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtszutvmon.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtrhqeqvdz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgacaeduz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtwqwcltdr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtzhylimkw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtcnjujddf.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtwkxgupsf.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtpinhnrbw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtexuswfav.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtzeqzmjph.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweriogfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkfpsqszt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gthyfaiazp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtptpdfgdq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtvlynwfza.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtxhssagfe.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtpqnmdyck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtrtiobkkr.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtxhltoygx.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtddijbnil.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtiwokbjch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtwbfmsyhe.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtcantpgqw.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtfgcsfxbx.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtmplqaxiu.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtloyapodc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtnczdukib.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtuuuglgvt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtltjzxjzh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtotuitfcd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtdmnpkeey.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtvzyvsiht.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtrbmxjvsw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtpymwfuma.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtquojggwl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtppxohsuv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtmujyoihs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtcpviikjw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtlwyyoyys.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtnivpajvk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtmztbbulc.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gttjpdinta.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtaumlvnes.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtnoatrchi.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtmzfgoitf.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfahxtyv.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtsvdiamrh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtszsuqgqy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtwxrekyoa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtkwpjlbnr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtffrgzgkc.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtmfbxzean.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtipohbeni.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtxobydfin.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtwkbqffjy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjkvlobl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtlvgpfait.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtjaehnrdo.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtbyhedfcd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtpcskinxm.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtfwxymlmj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtvwpbltxq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtvividykx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtsaodqjfx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtovgrtqzo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghfmovhf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtzuburywp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtfqzqgfki.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtqjyumhtd.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtdxitmbgc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtllfjsjkq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcnwoxbn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtquhhktmi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtfqzkpbsh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzxyqznw.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtdhemmvex.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtykxsmaoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtwwivwhov.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcxqxvvyq.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtupwiruqs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgypmbaqr.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtdkpnqaau.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtrqeyzssc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtetaiimnu.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvzbeddqf.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtoqwsbfwz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtxewhuoix.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtmsknnvmn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gthzudesza.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtqupodosj.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtudkewmxv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoyoxrgn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtmtfakmbc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtjoluqqri.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtawnxiuql.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtgkvjhyws.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtheuflccc.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtzurwlchx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtgrxpiegw.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtnpuxcbju.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtxrfkxhla.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtbypgxnbc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtqlfbqxha.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtfglgbmhg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtxsadfqlc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtclvigyor.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtvzeqwsel.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtzsisjihz.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtmadlqemv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtiknpaqmw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtuxarcmxv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtlpsylxnq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtyzgnajvk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtvnpnqhqi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtzheodljz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gttuwaahoy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtzmrrghth.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gttzbqxnmj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtbnsxjyrh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtmyhtrjog.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gthuasewer.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gthoiscpig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdymofhyq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtscfvzvyo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtqwqiveku.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtqyrqgwxy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtbmfswhdq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtbuucoprs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtmbvxmywj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gthfeeljej.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtgpfiljwq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtrbfgfekx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtsevtxtmf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gtwpxuvqpe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtkxefnwpj.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtjqelhwwe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtkkkrhzyg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtgkezucgc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gtakxluczn.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtijgaoppp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtcbustzjg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtwyzebzdw.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtlwtmprkc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtbtgntgax.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtvtouednn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gthqvzayfv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvlzopnz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtvpdnudnn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtaecvuzjv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtkrkqrdmk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtlpcqpoet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbhkytth.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtasffvbai.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuptibenc.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtbxiscexj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtecrfqxte.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtlycdgapj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtpfldttqn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtxljbgwog.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtjzrtdpon.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtbbmzcmxn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuqiafus.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtjuuxcfzw.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdfidevl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtpbwsjhww.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtygdkkrpn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtbibtskuh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtysedihzd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtqufwczwm.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtbizrijme.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtzermzsnh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtlfboumrk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtlvftivca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtypdkyywg.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gtalurmgja.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtcyeobcvz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtykyzsvnh.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtxwbkgmlh.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtuiejqhqr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtuucwxekl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtkbtysuqw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gttupzasyk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtohkriqbd.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtqdzcyppx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtykocpuzw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtrmkfmvqz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtcyalgjjp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtmagmgfpr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtvrktwhcl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtemixbocq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtubnuxurr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtknejvfjv.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtnzgcvcwz.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtszokzvjo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtefscubpn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtmxjkubca.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtcwxivase.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtkzsxihtf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtqwuldoox.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtygwyxdah.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtvilrcjlj.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtqrwuakho.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtazvmgdmz.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gttcwcpdjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtyaugpkji.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtmccohlng.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtfmmrnawh.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtlrqtltln.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtederliki.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtwxoesahq.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtpiljvwzo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtuapkyfer.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gtppchdkla.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtdbpxzkrm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkiacgzf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtcuxmbwmg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtyivkzclk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtpweehzuf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtnnjyjtmy.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gttyotdadz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtditbyyrq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtyxrsyzjv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtbdcwcovf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gttsqdeecm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtkxrinepu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtdjogpypd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtwkoxjgpx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtqqelxzba.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtngcpxgfs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtzykwwteo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtzpaaagae.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtutfcyqja.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtrehfutsz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gteaqikgqk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtztfvlbfz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gttnkdicgx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtolwitkyk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtqhpdfzjk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtifqppuuw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gthevrczmq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtmscxaawt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtoydnyoxa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszmsdmdz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gtriniyebr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtuiahpblb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtiageeopo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanfpozme.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtomqrsosm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtezouttqj.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtczxlqhqu.html


<!-- 参考信息 -->