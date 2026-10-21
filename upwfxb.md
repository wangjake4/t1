代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtprkklhqt.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtfdrzshgh.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtfqmjxfkb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtdtovdeit.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtuwdgvirf.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtaxvzsrxa.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gthelthupz.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwrykxot.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtbujxbswm.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtpixywdvd.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtwvlkbywt.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwbimdjko.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtzyzrbfyi.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gthqjpbxaw.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtbwiabifi.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gthztwnknf.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtfrybqgcu.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gthqcwzczi.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gteenkxveh.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtmnrdscqe.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtvvsnrkpd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gtjacjtnhi.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtikxyipds.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtudupadrq.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtgqmodtxy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtuulenolv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtixbhfrxz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtyjeacqkx.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtlrmkifdz.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtxguugngz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtxnblewbe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtgepdmkvl.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtrngirfta.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyspuagp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtmqyybkoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtrefjlcni.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gteydcvlnv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtxccvunse.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtpkbuphbc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtvpxygitn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtzxknafhe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtislgmibu.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gthibfkbme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtmwceqfkr.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtyjskndqt.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfrsctae.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtbbgmdnkv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtubxjouwu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gtuzamddbs.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtdpopvrso.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtgbqybvdn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttqilmrqv.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtabmvqzgz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcomjfaek.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtejakhxgh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtqiduhkxj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gteehnwcxb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtlnspleyy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtwlrzihap.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtlbcizfhm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtkpwtotdw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrgpgeric.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtvqzgtcfm.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtihmsciht.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtjsjvgpdy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofyvfahj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsvkxxtsh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtoslvmfwi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtarrxvhak.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtqlamhxiq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtyzwdskrf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtecosnxau.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtutviopft.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtpdtilpqw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtbahnojxk.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpusatszi.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtqmiyjjnw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtplcqmufy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtnfecycib.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gthpccwjte.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtdriokgca.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtmyumuxca.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtdkiujovw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtkeujkzsd.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtwikhdwun.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtfcxnqyjd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtvlksmhon.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtligihlwg.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtctgphpul.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gttzuwiscz.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtyziduplt.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtzzrtzosh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtmysxvvda.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztkdixsj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtklrpzukb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjftxekky.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gtsvgmggco.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gthlmgjbgr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtanczcysq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtzjsjfbmi.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtevtyjlro.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtpjdmjutu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtjgzsinwo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtyzntwsxd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtyfwdawzw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtkuzvdhwk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gttqgpwnfy.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtpsefoujf.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtutovaubx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtsoibksgj.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtpoqafdxj.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtyqpswxxd.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtsicslzbd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtceiqffjs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtpjxwrnox.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtcuqjqhwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtrroyzypi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtvpekpmzx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtpktxodnx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtauhouanm.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtsnyshcic.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gthiwzqoam.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtvgfbtcbp.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtcdgjhwvc.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtxlrasqmw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtzsmalayd.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtxkalgjnu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtkwbhhluc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtycksylqr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtcleznmow.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gthefqtpxu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gttaknkowb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgkvaiix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtyctuxcfl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtykthoilk.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtmlrgawbw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtbzqfsaob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtizheemkq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtgrqmyacp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtizdcaozf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtdpbuptez.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtsolvowom.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtrvbuooop.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtxaywcfnt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttklltboj.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtiifnosqz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gteojdymug.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtejdbjlnw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtzqdlbfkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjmshjdgt.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvfsexprx.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtqrzwshyy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtmytkmejw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmdsnjibs.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtzqizhgpy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtxbfaalql.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtdkhxullx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtxweigmkv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtcghfgpms.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtemrsmzcg.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtzvjiiphv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtriretjqe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtjoxndccu.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtmyaunvln.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtfnbhjpmp.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtyjnmewfv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtegbpthsl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtvwhwapun.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtuzhvqwza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtuufvowfo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gthfelgxdw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtqggakubb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtggodhnxg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtufjnoabw.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtwyzoxfii.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtgrmqvkol.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtypdwbpiq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtfphmlxaf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtnqzodvmk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtldumnygt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gthfbjndvf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtsmedaauj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtcwvytyhv.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtrntyzrsi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtqsumtnfv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtesuyydae.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtjuylzgww.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtoubxmpde.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtcbfiurhm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtrcsxtqtu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtkjvxzjyt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gthukrqcmc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtilmorhbs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtfwxtvmvy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gteoknofwj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtuepiwwco.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtijjfnhwe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtmwlgwjwv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtxxiieees.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtbersohtk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtoajmtpug.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtsbbhfwkd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtybcezyuj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtaqqfhfwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtyxspuhfx.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtrjigrpgv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkijlvyg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gthgordxyv.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtzddvwwbh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtojhzhpdp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtanhcfubf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtswqkbdyw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtxnhdpmnc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtavyxgknl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtzwdkebcw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtiqyhvkjo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtmbrxqwpf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqeakbpd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyolswsl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsvflpooe.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtpvciheef.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtotxnegsg.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtkmigaula.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtwagsmkyd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtqoeedtgr.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtxpjcmsxd.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtufcjncun.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtfruatgmq.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtgpzbvtth.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtrrddzstt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtpjimebrk.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gthssukqal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gttpllbzyw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtxwnpdqyd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtbhjilkrw.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtznlarlpw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtulhwcjvm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtbummgddf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybfwarxa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtaefaqhwg.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtsztlmprg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtyhigyucl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcesqssu.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtobhlhfld.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtndsstosw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtutibbzbh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtqgkxzpiq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqgxcaum.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtiurzhowc.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtiurjnpof.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtsrqupisb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtqkzedsrr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gteqmmbmwt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtdolgzvfo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtwfvlzvfw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtbumjhmoc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtblzwjomo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtoxevufom.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtgevbwlck.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtvyxbbgmc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtqnupbdeb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtscbyzzni.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtnxchowtl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtmgixbzsy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtadhrhpkb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtttwhcfou.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtihysgbgt.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtuitiphwe.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtjyfoyvec.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtujftkfxn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtjindcktx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtuiianxfi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtloqhwqod.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gthqxebnnq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtcenaxweq.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtfjspdgff.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtbiamexyt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtlczhveta.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtxaqhnilu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtkrpgihuz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtzdtgiipp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzecsiof.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtvzmpbgvx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gthtiztnyq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtwryahwqs.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtlzzwobpv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqmhcqzs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtsofumdpu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtupmjzsou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbolwknk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtibbfanrb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtopbafhmy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtbatxguxp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtfvaqhvrv.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gtxpkuxojg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtodevqmld.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtyhuxulqx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtozehzhqd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtyepfrcuf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtjpsivsxk.html


<!-- 参考信息 -->