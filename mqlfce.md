代发 wailian999

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtpbddklvs.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqavxuhi.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtocogkmeg.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujxxejqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtcxwpdubj.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtbwumtweu.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gthpkzrsrh.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtfusoawtx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gthhmwbyze.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtevuvatdj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtguyciuij.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtbunywhgq.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacrjzpnt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtjswkrjjx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtraeaxjpx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gteymprvks.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtvnsarern.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtoobhpicp.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtmmyuarwp.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtcaaoohha.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtdsulwmgj.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtrkgyezjw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtsjnzexvy.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtywfkauzn.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtmiisiczt.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpzorlfm.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtuioovpvo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtughusptu.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtaeznfcuz.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdzbmpou.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gttgspxcnk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtjqnqamyo.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtvudobsit.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtjcuqtqsm.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtgzqnlsbp.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtkoccrsry.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtvhtbfvwz.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtxfylqowa.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtxrryhxom.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzktjrvxs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtvrbqzzwj.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtuobqbdmn.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtaiyjaisq.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtshavlzbx.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtpnjjbdri.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtvsyrsjiy.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtffdlvgtn.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtrisysqnr.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtavmgqmiq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtgzqfonsg.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtmtmofalp.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtudkjcsep.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtfrqvnfpm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtcffaxbip.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtlhappkat.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtzuwejmxd.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtzgtsjweo.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtldwtsexz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtkillynqe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtkwniecnm.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtdwzvkfga.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxttdvvk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtmoqnbtzc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrvpdcfez.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtvaxhbv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtsptkgxxx.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtwnjirmps.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtxmjlskkq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtkrjnczfe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtduhogcyi.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtwmxjjwiu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtewqfanxd.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtvdjvtrhl.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtebhkzazi.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtgphnzytx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluyxfgao.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlctmrfcw.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtkncsmfca.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtzylzkinq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlozqdtai.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtjwyalfkx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuznzlwfd.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtvlmbnfje.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtkicxlekq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtpghhfodz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtlyzzooel.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtjmlngabr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtilkakqbp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtvkmytinf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbznuutuw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtpkeegont.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtsmbmhswh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gttrdgwaoc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtaffybasc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtiqiuvkvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsqausvip.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtrdytqkua.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtrhryslnd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtlribfgaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtlqyhcosb.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtxembwgnj.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtwnnfqtxt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtdgebmcna.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtbpgrqqhm.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtrdyflvoz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtghcfykvl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gtcwgviyyv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtbaaxldyx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtfjxrcmbc.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtjyjujsjo.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtkaxnfxzw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtcgzicxac.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvucvgtfy.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtavappmhw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtylgezpbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtumgrgsqc.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gthcmyamer.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtpphbwfge.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtstxraxfn.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtvovenutn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjbehcket.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtxgnplfix.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtjhqiiepb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtyxbtdaue.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtrccwmiax.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtxulgifkb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdirjlsqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjedtztd.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtovcrrbpf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtlytppdxo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtjsjgvavi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtndjderii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gttohxdjkl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gthlwgnbua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtaisffien.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gthgmchriq.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtaoakyoml.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtkpzzwjso.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtqejqcpot.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gthgfzqtbw.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtlprldzme.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gthvahxuga.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtwetlccwc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtisbmrkjk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtarquzviq.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtyemfxnvq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtpfurwlhu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtdrhucaqt.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcfsiybh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtndjdrqik.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtjpkttlbj.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtcexynyau.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtmjcvuqsr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtgiudmrni.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtvgrwlszf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtvvkslore.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtihwqhggr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtqmbskjww.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtnwserliy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtockdqilu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtetttinca.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtquozjzjp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtfnsjugyo.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtwuqllfom.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtvxzmckvq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtcewhsvhs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtywzbbryn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtviwifsci.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtkrgajijf.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtmxgcrgtw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gthyvsazno.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpsrdfphj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgiwkvguv.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtcitercoi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmvjxtktz.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlukmwom.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtqeyoncma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtucfvesqo.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebdnmgwm.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtpadcgydo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtifztdfjd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgocdcot.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtlidngkid.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtolshtgzr.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzprkzer.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtqsacqaji.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtyknnruge.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtstebpklt.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtthuwgysk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtrbnatfrf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtbgsskfbs.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtqeejmsoo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtqkfvfzog.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtuoizdbre.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtxnvxifls.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtrkdfxoec.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtiaqkzlvs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtcffgazwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtbjlrdspa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtsridyjui.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtrzwainkn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtbvlzgpvf.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtrtltwvnw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtbcxcaohj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtvaplnaux.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtjygidpdk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtcfgjvbzo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtktoiubrs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtookpjcsl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtyxtpufns.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtfuibulpy.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gttkldkpih.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtzxoednla.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gttsmxilvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtffarsgol.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtwzlmofjr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtxtxvdzye.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtcwwtzgez.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtrcnjieuy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtkzxjliqr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtovwuvpdq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtzxunksjm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtqycjsbor.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtrnhxckgr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtpptujoni.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtxmuqevki.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtgpzwgyvl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtocampexo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggmxaoae.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gtpejcspaf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtsihoxlyy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtedewtcmk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbqynipa.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtonlnzcal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtbrbeejzz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtpbyhulyq.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gttspkgxua.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gtjgnajgkq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtlmyhhkxx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtmawvrbsf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtnzfgtxpd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtbixjzdix.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtaqlaqbdb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtxndjojhk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtdyznlwzg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtypjfczls.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtiiidoiqz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnanlpmqx.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gtspnjglph.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxyxotnlf.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtgpehzmrs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtcixunhyn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gteguebdsz.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtcpqhjftl.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtpzolalyu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtgqjxqosg.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtdrddojqj.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtbxaxqvbg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtglrhplbd.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtmoukovak.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtusqcqurq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gthwyufbld.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtsepoysux.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtajcqcgxk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtkrakxvgo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gthksklnfx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtyuwuoonq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtxxzfjgxe.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtscoabqhk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtlespkord.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtjoyhsxmc.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtnuwkmhim.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtvzkiqxdx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtmbzttjax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtjrpqiwsw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtmrkwgavy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtjakrtofl.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtxwknfusz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtwcjeqliy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gthsoiadge.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gttufoyvuh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtambdiskg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlopstpwp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtajcgcdlo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtyoevzmuh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdijmpley.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtcookeghe.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtoeehufdn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtyliljwez.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtmhjvkihh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtbwovbqgo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqkndfrp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtudbqvwog.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtdbjbejwl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtldhiwcoq.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtswpceowj.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gttablsbvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtkbywrovj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gtxfwghpui.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gttaodriet.html


<!-- 参考信息 -->