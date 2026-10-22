代发 wailian999

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2cnnzricg.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lpysjrwk.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2vmgfzzzl.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2xqbhxzvl.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psvfavmq.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2flozonsq.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2llaextja.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qunpmkyu.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gt2zqiwkxar.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gt2qohjkinh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gshivfbp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2wgufexoc.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khrcwwtj.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2rlrccdum.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2wcklxdxp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2arwiejhy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mqsbvipo.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2emnahnmy.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2wpdioxbp.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2beyqkcml.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2nmunhmgy.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gt2ltmtqfxi.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2dmlfvyay.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gt2xfzwnhuo.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2yxbxpmoo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2qgpuchqq.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbndgkdj.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2wlvgcjwj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nisbkwts.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2qaspxcbz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2xwibrsgy.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2uihedquc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2xsmvpknl.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2oppmiiiq.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbdpmmqc.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2kjiefrao.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2bvyfscyn.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2ilktbdbv.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2qezmpabt.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2srrmwoes.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2qvorghot.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2mlkrvtrq.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2xbyonatf.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ncjvcpbu.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gt2oxafiyit.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2yhnlqfyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2urduwfbg.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2jbokqjmy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2hhtuictb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2smwkallp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2ikdlcaoy.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqzkskwp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gt2vbxodjpo.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gt2kqtvqyzr.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gt2rvmgzjbm.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gt2apmfwcbz.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2gpapytdh.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkkfgsvv.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2sppfujzf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uegihkai.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2fwqrvqib.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2gqbpgykv.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gt2pcwfaoes.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2dxuptzev.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2yuuyhejz.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2noplhtpm.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2zsvjvppv.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsvojncu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gt2mcttxgsg.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2kldwypgy.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gt2juuxtvzh.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gt2efeaefqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gt2usrispwk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2tdmmzwhk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2gwlceyso.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2zfevwmut.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2fhxkohou.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2usljqlyy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gt2fdpkjozk.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2edxefekq.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2pknvwoqr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gt2uukhzumv.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2rtxhxoqu.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmrtcmmf.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2oxseuraw.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gt2uuxvjlab.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2xijpgkoz.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2sydyvgml.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2cfoqcvie.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvrbijgf.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gt2ggrcdoge.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2soalnbtt.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2nileepbp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2munlbktm.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2vfhlndcp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2yljoizgy.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gt2mdleszjy.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gt2yvgeglyr.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urxfdvpi.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2naeuivol.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2wcmcuriw.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2hnijvsbb.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dsjddfjh.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvehsqmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2guduqemv.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2htqrugpa.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ewuxnqyy.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gt2hcxkkzgo.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2kgtahgac.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2mnbnwhqn.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2fdeyajfz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaxfbyo.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcppwejv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2vgfbdfer.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gt2eipcewwp.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2wvipjldh.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2scxzhudz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2qhfecdyv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gt2hkdacvjz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gt2jciyarmu.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2vfyfrnem.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gtdjxxaj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2mcudtzrs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhzcsnme.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtqpxhxw.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2cyhkqbig.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2rcghugju.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2vdaokqox.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gt2pahrgtwv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2yhfdzccq.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2vaukyijd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gt2ekyruzhr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2taixhdxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcfmjvyg.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2hwiyluln.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gt2dogjfbod.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gt2cphjidbv.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfconire.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2tzutidql.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gt2uqoxnwss.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gt2bqmjvkpm.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2zriawoow.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2wawtjrxz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2auolqqdr.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2hirhhimm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2yqjmjfmj.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gt2qmsykewv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gt2ejnqzerr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2dzjgchun.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2rdlztazv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2lvqmcbug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gt2qcuitmyl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gt2ifbfvave.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gt2dqhiyylt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gt2zzbwyhfl.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2rxjezvvw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2gcdaenvq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hprliize.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2yohsvhzw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2sxrzbfjj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2psomphsy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2rkriwmyt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypbgtsxi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2zciqbpkw.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2cuyyrujt.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2xxocnarr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2nnwcwgfw.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2tuymmbcr.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2olzdhipj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2ewjxpeek.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2iyaathph.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2pacggrju.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2fdrupkzh.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivboapqy.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2zpnhnneq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2axnqbnpm.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2bwuxihxb.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhospmvv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2licovsgf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2bqqxpkja.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2xojvgppy.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2bzhhvunu.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2bqsbjcou.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2qfylnbki.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gt2wuyhsrji.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cgzycxzj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hhfvuzfi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2dxyfvtwa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2opphnibx.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gt2ddwjyqak.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2rryzfkdj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2uzzcsyak.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2cxyalxmx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2dfkrltgt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2ulxpporq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2rjdowwrh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2jfstmhli.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gt2ywyvwdpr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnqpebki.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2htcujjro.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfzwanwi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvstnfpz.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2kpadhywi.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2vnwokyvg.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2rxdpxiqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gt2dpxccwyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2trbzoelf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2dazaoaym.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gloejnjl.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2cnvcahnl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gt2nqzgvjgv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2qawpxleb.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gt2ybwspjoq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gt2qwfjcuvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2joisgdxd.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2vudccnde.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gt2fgaddtkc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2hugzzrzb.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gt2jcxawvnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2jcdixiyl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gt2etztbnji.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2pdmebqjt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2gwfqafvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gt2ikxgxzdb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2ehqjyxsk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gt2gkcbjutd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gt2xnzkcbqd.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2lkjpzpap.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gt2wblclgnj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gt2arkbndgn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2jbllvqfm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2oxlmujyn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2eimppsqz.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gt2ybbsveem.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gt2qhbqxnta.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2plmusoda.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ngwdxxwj.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2mdrxzzop.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2hevljihx.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2hszkohav.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2dtmsfdwg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2xbnffwzr.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2itbjajlv.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jejnfeio.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gt2deehxdbl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oclzipym.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2lrsydter.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2cstjqbdh.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2eautedfd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2kebkwjrw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvzdyrgu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otzviklv.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2ueobupss.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2awagajbf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2uzyabzpn.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2vxdzepac.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2xytqzgxp.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yupkxlfg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2xunvlmto.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gt2meebnszs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2dyygtrhu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovqbvqbw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gt2yvojaxnm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2ozcrzcmh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2ssrbczjc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gt2mmbbcrom.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2zbfbdbts.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2ocqizakm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgelgmtj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2ogxlhoac.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxynhzyp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2euvrammf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2svwnbxkj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2qjvrxzqx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2fmfkwjui.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2eefktbnz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gt2yllahobu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwdsumtg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2wauqdnut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2cepnhbvd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2xsubgxxu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2eghipabl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2oozxdpiy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2nzbtvdtg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2xplwvtdr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2tuesgfyh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2zsghmfnc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2oysppfpf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2crcunqly.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2poiyhikw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2oaxojcyk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2hozukozl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2rssaqilb.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2bjevzphd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2brsykryt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2mbjemvqd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2nkvbnzlu.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gt2minfcpin.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtwqgmyp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2keeylzby.html


<!-- 参考信息 -->