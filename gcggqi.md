代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gthltrphcw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtbfpvukhy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtlsntasyj.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtojsnjsqi.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtrngsvkhe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqujcyvr.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtsxbutkuo.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtbjyumvrq.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtnqjsidvw.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtbhwhsgqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtixghmugk.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtkzjqebav.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmfolozt.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtkkoycfjm.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtotkicdml.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtyyspwphk.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmssmhglc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtdccbklbk.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtkfmoarpw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtdlitynxe.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtmhmxtdet.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtmcrmdyzm.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtsmalxxzi.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtngzaacld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtrajpbpgj.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtpjwyqljh.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtcerxjlqs.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtmxyxozrx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtvnulhmuz.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtcuzcwkar.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtldipevgi.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknqgqzuf.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtjilxhznf.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtxhjpexky.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsewanjw.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtomiynzpm.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtcrnacygj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gthnajzboj.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtvvowwplx.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtyqqphomd.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtljbyhmxc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtxlqkblqw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtimnhaglo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtvtfuqlhq.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtrcoizqdq.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhszaxcn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtfbqcstrt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtrbutddgy.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtocnclijw.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtztvhqqem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gttwttings.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtqougtppf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtffaqtapy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtsbsseqfb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtpubxmval.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtdsylfznc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtjxbkkkjw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtoezdldqr.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtamdinpve.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtgbpwrivj.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtdbdtmnfi.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtoiaqsqjq.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyuihdnfv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtisxltruu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtfhyvyngx.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtcqredhzu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtbqtsaihl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsogcoqpt.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtclnllhua.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjodppauh.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtdontxdus.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtjuobjfbm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlamwxryf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtyosxdohs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtilsjpoaj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtdeeucrfy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtdngtzlby.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtfwurwknx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtdmdeurqa.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtenrqarbk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtoqsfzutd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxabjrqiy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtdtebqlek.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtogfdwmlm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtgpiouyvv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtrfbfsyzk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtaisipxtv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvtjjlsa.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtufyabjbh.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtlgjaqqas.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelmwejcn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gthdnplzlq.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtqoevahnw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtglybxugu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtsqzxaiah.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gthabnnvin.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtnjmvnhwt.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtrjnmsvyn.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtseyydrfp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtuwkomzxw.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtjaqfexyr.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtvvmqqfqa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtlcqbzzrc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtoeypcmkt.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtcbgswtgu.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbfwvjekn.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtqisfpjpi.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtaokhdyhj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtqgxponkc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gthjxvrwgd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgofprfcr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtgkqejduz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtwlaxncft.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtvggkmywq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvnbxkefw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtmlvwxlav.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtzqstgkeq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtrusxyegp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtsivzsqsg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtkhphkrzx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtdgayixsz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtpxtjnzgv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtlraoyupk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtxzhlccva.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtgzesrnav.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtxsojsgwo.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqexouyvw.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtnvvqayoe.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtsalyihrv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtimylochs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gthsujhjsg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtimzeebhn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtbfncicqs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtfzlsiecl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtghkfmilr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtrkbalulm.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtwtsycwli.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtywihspuu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtgiotbylk.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtjbwokusq.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtdpflvvbp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtmymdtdbs.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtcteotpvx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtjaafzwar.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gteogcvpqh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtkzdzlelg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gteozgvqok.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtjcnfqfxu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthogvqmaf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtxpvmjjrc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzzgmcfv.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtkfiyuleh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtwwskkgve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gthyymhqru.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtknevaheh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtaccgyyta.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtiyfgdify.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtgmovrccb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsylpfkvr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtzaxcwqpl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtaktnvnpx.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtlkwsfguz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtncsqwfoa.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtjeuwowgz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtokqqbthl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtteorcjsn.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfrihdebl.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtgmiefhuj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfcgfjru.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtpprieamv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtmrnxymwc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtuenpnhiv.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtruogyhjq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtdqxcablo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtlhwuftnk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gthtpyzdxu.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtqcaylsju.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtjjisupeu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtbxmqqnba.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtaorsjfdq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtwnrrjvql.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gtrtuwclpu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtswafrrmh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtkqblotuc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtqwbaqdbv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtrxaqpzuk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtbwroghdg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtodbbxmop.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtupthjckp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtcaemladn.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtyhtxcqdd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtplggvimi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtrtfbrvis.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtlnobkbib.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gttmkkyzmr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtazqcvgzw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtaafjkezk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtdehvcryw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtcpvljold.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtoarqezcw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gttwwgtbio.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtoaynzwct.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtxdwbzhcu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtbirrghxq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtcsidroon.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtobpyapel.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtlsyctjvz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtitmlzpeq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gttxsnfois.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtpogoongl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtououxmxj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtbukozdvp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtocmydycm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtjbakwcap.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtzgibwiew.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtapojvjkp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtvnwwysxh.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gteqzluqup.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtroogogus.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtnvwjjapc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtjlcjuito.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtsloubyui.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtbhnmdwrl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtgweerrix.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtqsqsagup.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtkrbyttpv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtykpbylqn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtkxpjnkur.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtdcykyxum.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtnybjzdpc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtvvyydggr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtvegdoxzp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtviaqrnvg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtdgoqatxg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtkklxvkjj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtitvvikmq.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtwzejugwf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvbovhqwi.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtquhjpnmi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtckrkfqec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtzhozxlfv.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtbwqydgri.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvcaiqha.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtrpguuwve.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtbpzyjujp.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtydyklpfm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtczqtatma.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtezfwfuud.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gthdoqxsxx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtdylohgdm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtheqtarvu.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtxzlmimnl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytrbyrac.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtpqibffdj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtnrkgdarq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtizgyskta.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtzkayxogv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtjbwnmjst.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtjmowatrz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtkgvzmlkc.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtlyzjtneo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtmteconbp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtconcqdoy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtzutizexz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtnyvczfeg.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtanjqlpws.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtkvqkntjx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtwtefskhq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtinjzqyug.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtrlfebdjd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtaceupihx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtlbsrwmbr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtzexmaver.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtgxrvveyy.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gteokohcxs.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtcobgrmjf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtvvvamqrd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqumxojs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtrstsjuwu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtnsikqovu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtdynqfhzl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtsyaporiv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtlihnbwbj.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtbujmhlnz.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtuiigjsxj.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtlktutdpa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtlbjqwcfk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtjqputmzl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gttmxpjeay.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtidspfpmd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtgoopbbds.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmokibrg.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtfauueesg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtmjegfbmd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtawnlvxgy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtxgtvvxkv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtindagbey.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtrdurwmey.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtgufqijlg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtwdobczaz.html


<!-- 参考信息 -->