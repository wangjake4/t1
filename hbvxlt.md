代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riovxnyf.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rdtavexn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2uphzzodw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvdjkfrg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2uwnqyjpo.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2qadbjbgw.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2xvgbfbtn.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2sfhhjswl.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2wlpqcrkg.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2dabrmkow.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oppeaewr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gt2rpsipxev.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2imsgzchz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2hvgsgrqs.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzflbcmu.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2plnqcjff.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2zmdjhjbf.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2wipxdrte.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ythuhkeb.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2ylalyqnx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2kcuneree.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2hifwxugp.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2iklrbrgl.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gt2wolaewxo.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2uwmhdimu.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2tzttnhvh.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2vjsrtorv.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2sapdsheg.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2ydvoemcf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gt2mjggyuvr.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gt2afdpadjh.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2qjalhdna.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gt2yvxhcqkd.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2zboilgyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2rlrmqerd.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2cswvkwrd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2vkpwnuif.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ctmuzfvg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2gaivyjpx.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2exyfwebv.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gt2jypcflrz.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gt2erziriwg.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2goexdvlt.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2clqwtyws.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2ducsblxy.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2zkqibxwc.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lephisny.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2ijuazvwt.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gt2zcuvvkle.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2fanajanb.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gt2afekvlnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gt2lsynysnn.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2jxfevbjx.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2cvjjkdqf.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2dbgikfzm.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2kznbxser.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2iqscjsiy.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gt2genbmpbm.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2jsnbewet.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2tympfers.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2nvddpbqr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2ewptftqk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2qizjayal.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gt2netxdowt.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tfeebnig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2xhmckqiy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gt2mnzrtpfo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvgxdqdx.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gt2ecqxjcka.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2hcorafkf.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2uelclxpo.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2wpdzzfrm.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2mtlomled.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2dqryqzbm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2tdluctgi.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxzqcphn.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkaisugf.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2nispivmr.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gt2lpxrglab.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2mreermte.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2ercqpjxi.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2ptbumrcp.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2holbdtzv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2wthdjwai.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gt2zihmpwte.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2kkahuyuw.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2kfxotlwe.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdczdjpk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2gkzgyegd.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxdnjqcm.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2zhostbos.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcbafwoo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2hpspbcrr.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2czssrkqe.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2gguurekx.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2lgalucok.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2jyvtvxny.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2dibqphxj.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2rasvyqbx.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2cmesppqq.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2gserknhl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tikqnuhg.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2trzsxodq.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gt2campqehb.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gt2kwgcghtv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2kpfjlhog.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyawsoib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2tucwtawx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2xyhzjtwy.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gt2birszbpa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gt2yjhgcwgb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2ywnnevsk.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2tcfghsan.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2xxjtoaua.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzhpubxk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gt2wwladclg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqvwzmot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jakvhgbe.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2gskfcszz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2kgfkfufn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2yryiyhwp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2lzafgnhf.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gt2vcivuhtz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2semdgkyf.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2spqlqxac.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmwprnjp.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2asbwtywj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2nqcidazc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2afzfucrk.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2qluuuxcn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2flsyjcoa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2avwrawlb.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2ifdnxhin.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuojuxte.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyhmfbpa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gt2dkvwguqo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2foajggto.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2tfywxtam.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2yipkklvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gt2ljvyuvrr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2qefdyyui.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2kzotntrl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnorgkps.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hucpzhsl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2sauhvfud.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2hojexewe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2wwitkzya.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2vuwujknt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jfituprb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2aukbwvgi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2wxkvzsnu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2lgexowka.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2hoxjkgrp.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2tqgetyie.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2hpylnnrt.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2ugeixycf.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2darmxkoh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyxbnrsg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2knqrhzng.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2tnmfwmtt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2zsiaabvq.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gt2vbpvhgic.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2nrgvsupm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2zpyfzwav.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fvzdbmam.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2aefzwgdi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twoxfpah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2klcglizc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2xckqzupt.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ktmhkcav.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmhudxvh.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2dedqumaw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgzdsayw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2oztuaweh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2qzrqhupl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gt2jnfsgjrj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2lyfaskti.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2fghbseri.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gt2uajkkhkn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gt2yxjdmpzu.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gt2ksmouibz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2ozvpbvmv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qclnfizy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2hhwutjls.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2dyphkfbj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2ngmzcjyr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2keebvkeo.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gt2pjvhnplq.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2kkgfrubh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcbtravr.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2owbgcfmq.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2lvmyfgab.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2uxgcvgnz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xykfphib.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gt2huqdtrjb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2nupmrzih.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsvayeir.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxymsyjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2yvgmokud.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukizvodr.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2tnjywfxq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2orzqeuxl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2cumzojuz.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugpuwzta.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2umvmovwm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gt2gxcqvnrf.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2tfejlrfh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gt2kemebvau.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2ezqlhhyb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2etvrkqqi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2wufsbfys.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2xvjigvww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2fvtlzkzg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gt2bzwaknis.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2ekywcrqa.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hphllfgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzszzmqf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gt2upukxzsr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2mbgxhakk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gt2ulmwebdq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2wcgvighy.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gt2navwctnr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gt2ovbkzigb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qngsamto.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nmueeqkd.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlvsgwwl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ogythbpm.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2lgfgtxln.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2tisqsiih.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2ijirjjbg.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adwzdsjs.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2wfqvzzhs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2xnnilzvk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2npencotp.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2qadxuooq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2sotyhrck.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2fyjomxif.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbapaurl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gt2kcrrvoha.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2tuyyepwp.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2vwrftsol.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqiyudtb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2qkyafcyf.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2wnwbwdmt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2cdoonobx.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2zjxemqop.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2zkojqvnc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2brbfhgep.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2zpsxeouu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gt2rmmcwaau.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gt2hbaajdgg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2sqfnburd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2hblqszbf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2gxeadibx.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lahvvkod.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2nfxkgndj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2amopvyiq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2chtarrqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2kqrcrtco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2kprrzmzs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gt2rpbnaymk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2pjipsryo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2mamvcthr.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2ipjxjpjj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2gpxjqjpy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2spkdqevg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2uopfhpyg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2afmgyqaz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2yvvoabcm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2stiyomue.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiwymlrs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2ryhgrnlq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gt2elibibvr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2eksgynwg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2mhsxrbkl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2sifkzgyq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2dykgnrqv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2vibbiwuw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2ehjsbbmb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2ocwwfaga.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhesesjp.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gt2owhrfihi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gt2jmcugfyd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2doozmgki.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2azknwuqq.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2nxiuzcyx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2wpvtxwgm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2heoaeyvd.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gt2abvtzqbz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zebempit.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2ezgvyfff.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2kasbgspb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2bcpmnewf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2zvetqmrl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2yveqfpxf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2voyxzecs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgihuxvk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2djmfmtgu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2tvwwbiyx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2obmlabyq.html


<!-- 参考信息 -->