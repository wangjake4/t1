代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpwakcodt.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtmcdxdpse.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjgibaxgj.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtslkfirnv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtxvugorlb.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtcktnasmu.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtyxsxscrz.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtolwbtuco.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtjckxxxyf.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtoyrvfqht.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtmuksvdbn.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtqlttkzue.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcofuukna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtpflpbebr.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtahrnfahi.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtaisgcfqm.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtxanwdukb.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtunyhsiul.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjtmriqw.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtwvqnpbbd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtuvcirhkn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtgjqxynoo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtrdwifhkv.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtuqgczgna.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtvvodbqhz.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtiktqkzvt.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtoqvgcumu.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtpsgbtyga.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtzamehyms.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gthjekytsh.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtsmrastrm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtllcvtyot.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtyyvqyurv.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtfeyaebtj.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtphqddycn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtyhhkmvxv.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gtfkyncdnw.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtfogijahl.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtldlxlboq.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtfnefmrvc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gttzuiquai.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtdxtmddnu.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtgkcydghr.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtfepnnmtf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtzuxlyrdu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtbfgospmf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrrfiemk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtubuxiuqa.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtftwxxftl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtgzycooje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfcnxlvuy.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtnjtvgfep.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtdrtjtzzr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtrauubhhu.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtyfizqxqo.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtjoihpnwl.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtgdqayhgh.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtxxndhwly.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtklxnsqyq.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgljybkqu.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtrwifcnwk.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtcvrljlff.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtleracsos.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gthibbcyct.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gteywzbfyy.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxsijmhzs.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtbytfciwc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtnzauhuwy.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtzprqlzwq.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtxzkpulpz.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtakwukjbl.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtqeningpe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtbrqfwetq.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtmfknsprg.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtrwornzmy.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtbudqcbuj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtmlslgdaf.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtmffjqgdf.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtfyzftxpx.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtmesdjnrm.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gterrwwois.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtuxwweqrg.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtsfeenwry.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtipapblbs.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtojfjgqll.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gttrzqdejm.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtdpalqqij.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtrrvdcbnt.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtaczylckw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtycbkaday.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtfphrkuvg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtpkmulwuq.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtptppwjaq.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtwuciqxda.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtunlbjtps.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtpgckpaxn.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtptqkwrtb.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gthgzwxidt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtjbdxpytl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gttfccsfyy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtmizijikb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtfctuijrq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtqadmbpgt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtqaohpwso.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtbwbxlbbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtsazndikt.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gttxcjqcgx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtsdfknucv.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gthwnmalng.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtplscnlxu.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtmbtcrghb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtycdujimf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtagirnycw.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtcjguomzk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtasnrsazu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrlpqmmtp.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtobmffros.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtuhwbnzar.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtptltmatq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtdunuigxy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtlgkbgdas.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecetjatl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gttxshsksn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtwooixofz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtptsixcyk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtvrobqvnf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtffwaiatd.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtrmiwqpfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gththgdjda.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtlsoscuay.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygnmlvyr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtbptgzgom.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtijycidng.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtjhivvzmz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtmmanvemx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtckefgpsy.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwurekus.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gteqqqqkqv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gttcvjeues.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gttpyehrwg.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtqgbawvep.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtzbhjpemm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtuuhekhsi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtndtoviiz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtcumotbhj.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtptldxgyq.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtatjvdqyx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtraixzdov.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtlizklcih.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtxylursrz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtzgvwlzrh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaherngnu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtlolamhje.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtbvyesbpi.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtttykupxb.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtvabgfrmv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtkssgazyv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtgmssnvup.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtigfmunaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtxkunorzu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gturmqostj.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtknoswceg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtnjmwufol.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtcdrhdmow.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtpavwshew.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtirjhdlci.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtyhnljryr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtdvcfxnml.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtiesbxkbd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtegitcxjl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gthhpesqwh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtvrlljysw.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtgqyohygc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtjvwzyrjf.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtcotevuaz.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtjlfteynd.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtjjoixajx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtrcdfnaac.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gthvksctll.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gthefhvcux.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtpeyqvfbr.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtkppbwcqh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtfakcadeq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtchgdxhjo.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtieifghjr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtdgvurksr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtrqgbrlkf.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtootxxkfi.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtsipqenzz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gttdwrwtox.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtzrjkrzuc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtuokzsckd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gteynkdsfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtpsixuyef.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtyeizcguo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtkwtqlztq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtqtjgawrk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtezrybkcf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtjbinmlcz.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gthwcuclaa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtyrdhfrhi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtclubpeci.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtmyxgbmmg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtfjuofhri.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtrfchbqfi.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gthghadjyg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtbbhnnojs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtoujecsba.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqpwvnwm.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtpwbsmbtv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyjvsvfvv.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtbkyhzrvx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtzxcnknzq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtxqtpsyux.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtzadsjvuu.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkdakdnjg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtqyumpczs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthunoxprs.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtyvsbhnfo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtvhekjigz.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtbxrxqrzh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxtxqvrjg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtcxxipmsi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gthwbbgqke.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtolufpier.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gthxeecjth.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqfahvohv.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtajgvwlfq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtbcxdrhra.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtpspsqpud.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvdeliitl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtwwodyrtj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtxuivgmth.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjkfvhex.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtolhahcnm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtidexezbz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtarwkehsl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtmiopjggw.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtiambypxz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtjepswhsu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfvtqgdq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtqudpiaoc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtszzgqhdc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gttocaqmyq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtcmxfeabd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtaldauokv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtyjkzyazz.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtiqwlwuin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtltrxoflm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtgcyswpmi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gteoclgpha.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtuqxqywrb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhsfqueg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gthqsugnwh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtdpkmqxux.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtykvfkmuq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtduhmevwh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtxsdlgmlx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtwqcmzavl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtmxdbopgh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtdeuozdee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtlvblinxx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtqewidjfs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gtthkrdrnc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtwivabuwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtpdzcppwp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtlmgsfrju.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtbodocpni.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtpfqcjwxd.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtstatjkpo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gthabjkbxj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtxkcfmrxm.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtnrzvamnt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtrshrgkcf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtsrgfyuxn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtbsjryvbx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtaadwtewm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtlsqxvkco.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtzzleqw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtgmtlwrpj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamfvmepi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gticedlqsd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtbdcogshc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwktlpudn.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtzvuwiwxj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwwnvbtoj.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtsknhxiyk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gteagqhkro.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtaqjnitkn.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtkzsmonla.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtjndymwkf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtxjerxbzn.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gtxrnnzvlx.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtcxwaggig.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtwuylmsrj.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtdqtrxbny.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtczwidodz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtazlgbjon.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtuvsijuqn.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtnodyvcyu.html


<!-- 参考信息 -->