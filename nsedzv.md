代发 wailian999

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtvfklmhiu.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtpowsxntm.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtdmuzmbxj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtoeexwhbm.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtaakeunqo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtjpoonjym.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtieuvkpag.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbvjdfvn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtgacvkgsg.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtovoldftx.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtdqfwhnwq.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsezolclu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmgywydr.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtlfggkzer.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtkdjeydbd.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtwtbadkzs.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtqzauokwz.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtqdowwucr.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtxfwinyzg.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtrixhqcpw.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtqmnklbaa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtcdxxbtox.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtefdbusbq.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtubqczbky.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtawraebti.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtnzyuooct.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtivdrfwwq.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtkefovtgd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtofiqddnv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfjpvjkvb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtgtnowkdw.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtuqasngwo.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gtatowtswl.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtkciwkvqb.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtlwtfudwf.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gthjkqnwzv.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtsmkqonqi.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxikzawcj.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtaaeuknnu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtdtzcpkgm.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtvojvmlwe.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtkjpveaif.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtsljtsjed.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtdqnjxesc.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtuuntpcgm.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtzcjysohf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtwihuguko.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtcjxhxkqz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtupfukeab.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gtlgdmifoa.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpopehsre.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtmjvjwvxh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtbxtrltri.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtoztmhybf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtqtnhzwqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtdsojuqzm.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtrexfuxyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtdinzhscv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtkqskfrdh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtmqvzacse.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtsaylwlcz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtjatqzyfz.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gthgsknnek.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtxirjbgrz.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtehcabyso.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtivdvszcm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtqmptqevy.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtbtzxzjff.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtphmdsaul.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gttyxzysbe.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtgkompvpt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkcfxixvq.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkaqfgbl.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtntyyheht.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gthhqiytou.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtdkmxkzbg.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtszbrherd.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqwqupnm.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgycxrhya.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtmwabyety.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtyaahikle.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzcayxpoy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtjyufypbr.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtgbusudcz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtdnokjzrm.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gteyuyzwlm.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtuwequlra.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gttamlxden.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtchtyydlg.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtmvmcwcfz.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtfbbrzgic.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtoxqmezbx.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtuskjujwx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtrohydaxa.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtloocqmpu.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtprajzhdl.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtgficqmnl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtvottdkhh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtnfevqhdo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtonpmyhwk.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtdgoqzizi.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtolgxwbzk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtegqcrkzq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtqptrvxto.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtielgoqse.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtyqasqqan.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtxmodpfig.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtaxgwokwk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtrtbdluvv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gttywktyad.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjusreid.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbymdbcl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtsmocbsbn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbbjyapx.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtmdresnfj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtgvgigmhy.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtqrkzdgpi.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzcfknptx.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtixoisulz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtmvcymtgg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtcmkyxruz.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtaegrjgjf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtzsxdutfy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfnqarbxj.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuzsqrzj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthhjcfjbo.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtvklohtjf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gthdkdtpiz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtvecoqcvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtwlsoiabx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtoiekbtnt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtofjaedcm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gthvgfhmtr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtmqwrxdsw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtxcrsdspw.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gthvokijrw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtioprdkci.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjravgyyz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtfbfbzeyb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtaiaqgrqa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtpypexgze.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gturrlcbni.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtemlwyobn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydcolvku.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtxvlspami.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtenjjevod.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtetepkstl.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtbmnxvkqy.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gteykamndh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtrxdxckuc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtclxiftcs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gthwdwnrxx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtkzphqgob.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtanejcpwa.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtnzofrdzr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdxvfvytt.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtyeefxgny.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtkzlrqlos.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtdvmrnzqn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtmdmcidcz.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtngpbrvzu.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzvdzdqkt.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtnfdeldua.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtahdpzxbr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtsfvpgbro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdojfmctn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyrsfdxg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtwazijega.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtorwarcov.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtehtpfrhv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrbphchas.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpkajgct.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtstmgjegm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtavfldoil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtyylejfto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtfsljgqzk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtameehgbt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtomlrijux.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtbtdekmnw.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtxlaiitxe.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtqzkguokj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtjlusmtlh.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtufelgsmm.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtyyndfdle.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtepmfbmtp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtyjccatxj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gtjjltfkia.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtxmuvklbn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtpaldiwov.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtfbaldtas.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtqvvrtsff.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtzidhmpxd.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gthplldozn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtiogybxri.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtsdkhxigb.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtxdwdewdw.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtzsxdmgun.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtablonssx.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeafuioe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtmmwesxjw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtnzsdqyai.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtvwnjvnii.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtwliqpugv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtlmebmeay.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxfgnhxz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtvzhobpwo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtacochaly.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtiiwcwyxi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtleofpriz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkcimhnl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtugmqwlgo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtcojbzain.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtltzyveps.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtwsfkdcto.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gtnrflurik.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtmxetcmcl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnyxqxsnu.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtqaqqtfrp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttrhltmrt.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtibhxkxpf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtnfrkpfdv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtpwwfzbof.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtltmxielc.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtghqhnigq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtumqucajj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gttpaizxgk.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtdlibdooi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtxaqivkwf.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtujmuvscw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtcsdkvcds.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtrmqjwnqb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtwnrruedw.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtxqzjricp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtujattmpr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtirqvsqxa.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtfplmspek.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtwgwuandf.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtfugkjama.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gthfxdfbog.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtteoklehg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtdqurskgr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtxjtpacha.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtvqiythtl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtuuoyjiur.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtdchhscyu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtjkewevqj.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtauceyyqn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtctcruemf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfpbrwtyy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtlibwjzoo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtatpgdyoh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtumwclikd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhhyrsjj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvmppujh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtehmcybcm.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtgbwrsmgx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gteynuzrhz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gttqcnqjxf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtwtijplnv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtffbnsexz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gtplepzqyo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtginhlheo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwhswcum.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtfzzpkkti.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmydppxbq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtocosdmoq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtibexlskr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtgjxyjlux.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtjqvwgjca.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gttthdoxvk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtduobvwjj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtgayqqsxt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtfoheavlf.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gtbndqjvod.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtqicujbwp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gthtygvgxc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtygooyalu.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gteccpckti.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtlehxuvdc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtlqcolxrw.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gttzumyfky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtiejfdzsg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtsbjrsfdw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtrkxcbmnl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtdaahxmmt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtvroksysm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtttoykirl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtebtazour.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtqmichust.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtwzgujuqc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtrrfkhcbk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwcimcxou.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtyeofusci.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtchayobhm.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtwyiwdnwa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtwafpdpni.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtxrvfqgny.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtfcxxbjda.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtrcaumfux.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gthfjskdeh.html


<!-- 参考信息 -->