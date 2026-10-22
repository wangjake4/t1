代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gt2yscnvbdq.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2ohrohkcf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gt2xadtlflr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2plvmkurz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2lfeuwgzb.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2haepgzjo.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2ldpgdsks.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2gklfheay.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2aauxkgxz.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqznqcsk.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2mjgwphoj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2jyowwgjd.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2eajiovgl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2tyggproi.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2bbrkjfma.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2fypmnsgh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2cbpcracm.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2rbocdgon.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2paiqepzc.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2deyyfdym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyqhnnsc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuuhlzg.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynjhxupj.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2dzxinfcu.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gt2iapgqlsd.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2kaxbyrpz.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2lkaiqwxq.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2hrvcypxp.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2kfpykguq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gt2deklmecp.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpuwoeli.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2lomwhgxe.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gt2jdludkae.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxqzmfjw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2mzfzwhtr.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2ftobdjav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ypkmtkfl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evhoffcr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gt2cddjvzbb.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gt2yupvvvxt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2egdrdtsl.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2ehkwdumd.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gt2avwkckls.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gt2btjmrcwi.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2fmkhgwto.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2fmtlzgcm.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2ugtgblgi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2zurqcopm.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2secyenye.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2wzdjskyo.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2hpzxirct.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gt2rxbtefvz.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2niukcmwz.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2hwqokkdy.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2sdiqaeqg.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2ayiirlny.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2zejercoc.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gt2pjpbhgvu.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gt2xjcuwrqd.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcakrztx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gt2ofwchpeo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gt2uiegqbvv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2soisuqtt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2ogtwcmoo.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2nsvegukx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gt2lniiudpc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdevqidb.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2nyzmnnok.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gt2zikszbyl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2dyikwwrq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfeqfnw.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2vsphrwxm.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2idfuvyho.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqjrwlgq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gt2lomjbopn.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2dirhdaww.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2dleprslh.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2pvtjkcpw.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2hriprlkg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2aclhwurv.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rtrnrmvw.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2zsoiedey.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2brquexyy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2zuapvinz.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2ezneylah.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gt2obhbayny.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2xoentjht.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2vrigdehx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lxkofclz.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2pztdrmdg.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ovuyetxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2bgzdfymn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2alnpkvid.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2gqpolctv.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2tsbgcxey.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2mbekable.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gt2pgxdcfwa.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2evtvhrwb.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2rkrtszkj.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2ihmvjoqr.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2rwwdfrpr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gt2nufbmowo.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gt2bcsnqqbx.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gt2loqmcxri.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gt2lszbfjaq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2zdcbnufg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2awlwjifv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2bchlxqlz.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2vqlvhfkd.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gt2bfuhxhae.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gawddnxk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fssjnkwk.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2qisycsri.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2lthbnrdh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2gewozywg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gt2bcbriveh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gt2szsicxmx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2jzmrbrso.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gt2orcepbrr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gt2onvtddfu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2xpcegpbx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2qxgcknos.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gt2clqszasu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfxlifqv.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2ibzrstfj.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nctauwby.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2mdmiecnj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gt2woxkjxny.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvwwzhwu.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2alxvrpxs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2pskozrkv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyicrvoz.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2seqjklmo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2hqipwrvk.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2faeqxweg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2cmewzune.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2sfdivcka.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2ynnrfemy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxfirmwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2fosbumoi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2frtflqbn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2fihhsjok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gt2kscyseba.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2nnvhtqdd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2xhnssrwu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2jgdeujsr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2gcjszlrq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywbewfqr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2jbicodbi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2ldmysaig.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2dbgnsdxz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2nozewuax.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2stqaubmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2sjyqpmxc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2lelmspex.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2uhqihzte.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2ikxhicep.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2jbwoazog.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2jmbipdog.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2zrcgvezz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2huqvnrbj.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2mtyqrxtp.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gt2svgwnqiz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyxszudy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufynsjro.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdwjmwgr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2eosyrrpy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2zoeihpro.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2vuklibtu.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2wfalsqzo.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gt2xnfohcpk.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gt2pwwwangw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2fujzthwz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2wcxakjug.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ezwiqsyr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlfavsgi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2wtutasnb.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2zrgtjsio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kfrerkzd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2teoupaob.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2lluqdylx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2tntepksb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2qpdaynmu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2jyhqoqar.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2adlgcdly.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2kgzlyvlz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2wmkrrthc.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrrcalnp.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2myobkxij.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gt2rilflllq.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2oheggmga.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2bgvztwis.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2mrxudmeo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2uwwcurlb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2bcezkekr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2hbltjele.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2ujfsmbiv.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gt2heozerhk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gt2qptsymqk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2sxlekvtl.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gt2twldzuqd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2rprblcdi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2wwowoqhf.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2rvrxynti.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmwmamkp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gt2eenbtwco.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gt2ruzmgxch.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2runkduwi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gt2wlvimnbf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2oaxrkueb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2nrxghjao.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pqdtglrm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gt2uqssrarl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gt2lavmefnm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2ahfwocuu.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2ljscyekr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2qrgggzwc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gt2azmwoazg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2qruxsfib.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2gwxxzajt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2caoxyuhf.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2vaqubcfs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2fkajkrhx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzyxbczi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2cwtqjkyi.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2bcgubhoy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ymtszagn.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2zwepjprc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohczvhjq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2mttdfqib.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2hmfycaxo.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2ggbtpmsn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2nbmgfacz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2efdichna.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2lmlauhdy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gt2cdyrhnri.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2wtzzniib.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnrrhqzm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2oymcbuxl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbkcyhsv.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gt2ybqvklhs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2cwexgzvj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2aqvrzqec.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2xljpaemu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2scqvrtlx.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2kpazmemo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2lxpcdiov.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2zjjtuucv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpdnghrl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozunrain.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2ilcxretq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gt2haabqmcv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2fxxsigcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gt2aieuoehw.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2lerhwrpf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2ynhsvdqm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2cxtwczbw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2wmkymgul.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2osnroiwq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsdlrivz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2oqhhwcbv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2tngbxwkz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2pzcsqwzj.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2lorqkoxj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2deyebfgh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2aygwikvs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztmrjanc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2vauzqfdf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2stbfmdtm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2nfjnmtse.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2ktnsrluq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2geybusyx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2lgklsntx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2cbdtrejm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2mzwykgfi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2zrbecjhx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2ktyqwidc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2hshzdlqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gt2ujdzxkns.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gt2qkyywxlc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2hjzdgseh.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2msxbhtth.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2yfharrfr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2nxatputi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2tnggnnsn.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gt2necpehid.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gt2aqghwqzi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbphmpri.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2cjgkmrro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2tpczskef.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2bkhlagrr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2fmlmornp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2duaezxrj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2redhkzfj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2pchovedf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2qzdmrimx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gt2vzwwnfqr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2laknxbkv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amfbvifq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2syurtghd.html


<!-- 参考信息 -->