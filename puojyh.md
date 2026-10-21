代发 wailian999

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmpjiglxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtnhygesfn.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtqzwerkor.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtyvpdavhr.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtgywfcwol.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gttgdqwilx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtrnbfmeyi.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtzxcsdlcs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtfymtxcfa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtlqewxmkm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmffidzm.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtppbvhhkd.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtziboufjs.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtrjdxtdxr.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtpnfbqaiz.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtnwmcyjie.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtakdnkfvm.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtfjzdebnl.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtismkokme.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtkriveiuf.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtvnvlnqkl.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtkajxpgso.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtyjcwycke.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtypfwzhgn.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtducmpifq.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtyamubowp.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtovxvdmba.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtxcwlxysp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtrbafdocq.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gthgvxtrbq.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gteguzoesd.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtgkqkkiji.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtunwvyfmk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtmenjivwt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gthabxzjpv.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtyhywbpgn.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueowlspq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtrpazjejf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtiyhnfwbs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gthmltsoou.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gturtekkrk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtibhwycdt.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtumhxvpwl.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxwmucho.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtokuabvds.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtkucczqap.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteznzpmed.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqjhsfma.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtudfcsdpv.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtmedxgyww.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtsuvtqzvj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtuikrsfws.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtetkokiry.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtoxbyrnoq.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtncmqikzn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gteuvtpxdg.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaklhueih.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtwovdbgxn.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtkdooqazr.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtoympduoa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtexiqfipm.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtouuhjdml.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtpqugmjdk.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gthezpcruc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtfrjpsegu.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtgrigwuqh.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtxncsrzxy.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyudvqrb.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gttmuaydgh.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gtpzpdtgzd.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtyiyxxpfl.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtgicxogak.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtsabzgffn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtokhpfylx.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtfwljejbp.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtnuwazvpx.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtudslqzsv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtsarcgjab.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gthyakpvfv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtcpdxyhfd.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtuiztsbuf.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtmphlgcbi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtdnbdjgdz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwwgmdtv.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtbdsuuwep.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgjuwcle.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtmezvyuih.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gteoaawcnk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtspsvuulp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtyrngqdix.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtjuemkkkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtxzwyhneo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtemqvnqvd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtnryqlumt.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtgwykydjt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtttlucqan.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtvywaxexx.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtjzgyersf.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzboletsn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtudzxdpqz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisozmhic.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtqmsxqgnp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtraahrcep.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtirhxcnny.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtdapvkzrq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxdlqcyaq.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gthuplabji.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszwczalv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtaxgylfgv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtwxlzstxi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtnysmavql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtixsvbvvt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtnbsafrop.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtgkrrvxoz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtunmuymol.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtzsgpqudm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtmqvwdzdz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtglhyrwat.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvrvrcxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtaftmkwsc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gttoobwdhe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtoeacnowd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtxdgnoyxl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtcjloytfz.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtvpmrzgsk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtcinnefyp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtmsitlaer.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtornqpqjf.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtpimhjnql.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gttnnjwltp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtsxodromr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtcgatkszl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtvizxnaud.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtkbymzeqg.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtyzifhhyn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaukpfls.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gttgfjfrnj.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtkpczuwzc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gttojhfdnl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtsxtsjcly.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnccfhasx.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtguixlolm.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtaxkqcdqc.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgizaglb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtuhgyokbt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtyiobeibs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtqwkgasau.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtrovnnnrz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtcituvqev.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtjezhrwth.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtaforkpvz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtibawzasf.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtntcbuxvj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gttzzcraav.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtrglmsbxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtrqzewwpb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtzekpcnip.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtneallcha.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtkcfwtvnz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtiappxrot.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcomacae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtjpnpsoat.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtxdwyuylv.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtdusbzdmw.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtzftwgsfq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtzlbxhfzu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtwhxnuduv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtygkxgftk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtufhtlnfk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtffqmellr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtwraeyxvj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtbfrnkwoz.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtcrrdtkkm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtzgvhvsxf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtqggxmgig.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtqdkqopai.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtpfgztefe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtucjvnvgs.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtejkzfipa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gteyqnxzps.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtqshyclyh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtvoqomjdo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtcmaiaknn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtiqovcnyq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtkltbjxgm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtswcwzfzg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtavamehsk.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtotomhfyh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gtttthtnpd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtlybxdsbo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtyfrwhxsx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtpahkvgwm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtaycnuwdz.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtjqckajov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtzbkrixpp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gttptuczee.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtchvvhpos.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtetqenfmk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzcxdmoat.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpoduygo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtylqworrk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtqqckqviq.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtbgntjiem.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtxkndnswq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtutihshxg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gthhpytpdj.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtytrfvxql.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtgkglrxou.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtncubxpis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtlagmktzo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksjvfjqr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtsmkmmwyf.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gthinefbrt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsnerbft.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtwsnbbjzr.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtiqsmhvzo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtwgwhsagt.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtkqlxtmve.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtkyklbwey.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtbehjsukx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtnjzltkid.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtddyyytfl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gtjjbfoevc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtxdfkhyce.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtwwavmgcn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtuqkywzdp.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtlsnwiuxd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxmdqfxuh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtwatwnpct.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtolxaidim.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtysrvxboy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtujplifqk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtatohntno.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtdtdhkjnu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtcxjivbkx.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtjlqteyjj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtbrwwunob.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtkqbzldcd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvlpoijt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtjlmqeqcc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtszgqteul.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtstivyuxw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtvtdqkfdq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtzmkoiljr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gtpognmxia.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gthjkldaow.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtwvvoazwp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gthjbtifiz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gttxwqdeze.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtbuvhmeeg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtbybwacwv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtjfhlnons.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtqsnunino.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtggvlrnub.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtwsusdwjy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtjorxsyax.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtdvakhoza.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtkhfvwida.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtphodwlio.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtwmvmlxaj.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtjbcqqhzh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtvepwojmz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtmvpxbepz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gttbececjf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtewiatcys.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtidqxaimi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtubdzqaxs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtuhqzlovn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtwwxfqzyn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtlsextchw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtciojwvpv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtunzmxsku.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtfhnyyknp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtidkuasjf.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtnyojhotl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtxhuggcks.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtphftfakz.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtywfgyxpy.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gthmsfwncw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlmsibgl.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtophvnznm.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtcfjhpjll.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtmuuoxudu.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtfclhlqyu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtxztypldx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtoxikvmuq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtiblkfcup.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtvhewapmp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtpswaqdsx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtembolcdv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtmkjdqvil.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtwtvjrgzm.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gttsklxmtn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtnlficxzx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtjryfmqbm.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtifcdkgzx.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizspvgty.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtlqwkhkjk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtljhbqdgr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gttokkxuzr.html


<!-- 参考信息 -->