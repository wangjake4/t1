代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtujkwhsxj.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtkbdegtcl.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtzkwfqqmg.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtmtvvheej.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtydwwmyhh.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtocffywvh.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtehcngfuj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtisdmepsi.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtrssfyxqg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtpvxaimkp.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtcwdfcutn.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtdmmjomhj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtuirehtqv.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtgbdschbk.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gttmuiyagm.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtdnwmukqo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtneoiskqz.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtocntkagq.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhppqgqm.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtaavhkeml.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtfmuqbkmr.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtanfsustw.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtacfbydmq.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtsvbayxca.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsanpwnnc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtleavvksn.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtcmmxnpaf.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtrwcvftee.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gttlgdqcsu.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgzmctme.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsefztyov.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtsxglxvzn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtadghvjgl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnuxusvya.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtykozxbaj.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gtqoolrbpo.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtojsfmdfs.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gteiorhkuk.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtzogputmo.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtnnffzzwt.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlogreioz.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtxuwmnuyr.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtysyqlihn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtksatmsca.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbjqnhqe.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtmmuwugnu.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gttytqkvir.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtpziammpy.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtdrgtghyx.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtqndnfvds.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtunkhtnvu.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtseywvqfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtqfkcpdmi.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtfwpmuqum.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtziknjsoy.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtdbynwjin.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtaypbrimu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gttykbvhtu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtthqopyzq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtisywmfin.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtnliuixll.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqxiclqa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtztlbnppt.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtykoyrykk.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtykfkkite.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtrhvdxbcg.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtvpufscqw.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtvrynooec.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfftvtfyl.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtegkzmjvd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtoxvplmuj.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtavcfijry.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtthmvksbx.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtewzmrnfw.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtudwhlphc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtmenqnhio.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gteevcymht.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtkzmzkhhm.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwibaobnz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtswaglwqm.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gttbgtkhml.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtovaqgfya.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtsffulgsl.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtlglmphnc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtherzbymc.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtyntgkcpy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtxmjqfvuk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtjoxxpuzm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtddofaaua.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtjmxkxent.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtuetfshrg.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtmucaekop.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtheyaobhw.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtrytrbjaj.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtnrkjjsyl.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtvqkrgtmi.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtaogpzuce.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtjftmiljt.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtrufecegl.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtrechkkmr.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtbxzqsfuj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtsbsufpia.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtuxzmosej.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtfwbeeppd.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtouxcrabx.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtquewgjhw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtlaxthdgf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtsfuqrfyn.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtmcrsqlrv.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtesycfmyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtstahvmrm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtesrvzzci.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtbfeuiykz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtkqgveckq.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtamccohyn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtosiaxkel.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtacezoaeg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthabrdues.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtrehiyaoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtiedwnzkz.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gtephwqkhc.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtzqohjkzb.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtvvpjnoqf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtkwifycnw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtjttewkwz.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gttqibyzth.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtnksmppzq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdlerjwqe.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtjugxrodd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtuhhpokxr.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtaejbjzyg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtbglwojyw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtqbcvhirw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtqlhgfxgv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryzgcmfe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtfutzrdtb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtoxvolfmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtqlnnvzvj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gticwjbkwd.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtmomlklgh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtxmnqdgxq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtyqlqdgxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtnamnrgqf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtxkodgujh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtgzynvdde.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gttirzywnf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtnzvuihnz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtyywibbpn.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtmullzkgi.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtlyuyxrdf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gthattynps.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtudwwoltr.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtdydycymu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtewejkknf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtpwfajunu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtugalprks.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtzeyjtser.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtmdnvbsyd.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtsesvxhey.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoszksqnb.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtdqakmske.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtavkcmwpg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtrhkoqevx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtigobmose.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtfcudbuhb.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtjvuoqpgu.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtaulxibnd.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtbirvkkdm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmggsnyuc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtugaazkor.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtkipsuxyy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtletpormo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtxqnhfqtt.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtbtebmyiv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gthqpegzlt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtjbskzepr.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtwolovidn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtyyltspof.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtskjmjiyc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtylnwpehp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtfckwbwms.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtemfofbvv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtuadgjiam.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtwolsiokl.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtomdgrydh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtjpvwwufq.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjntunvdt.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtzryetozi.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtsopjtaww.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtneldqlcy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtaosktbff.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtjawyoqtf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtsgldbvoy.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtagxjfmix.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtnftmnitv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtdsninhyg.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtiopfmisa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtibbwegoh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtgctjnhde.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtgkeiltlr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtbgpzfbsk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgenfwlfw.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gttpcjywbo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtnuwgzovx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtkielpyed.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgithqypi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtihymikpa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtqtfthctz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtaaomxbph.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtyevqkabi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtcaivktae.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gttxspqetq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gthsujpyti.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtokpqrcwy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtuqjtnoie.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtjujyydrw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtgcsjxycc.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtozwfxlvh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtburpncnl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtrjaqfwim.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvofpnhir.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtkdqkauvo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqugtylvb.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtpjksoyzm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtdscsnawc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtqrtmuxmh.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtbxeavxix.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtxtlynzqc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtnnvtdfza.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwzizvis.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gteooxmfts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtpwthamrs.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtgqvoesih.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtvsezuihc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtlixjnpsj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtepcbnmrt.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtwoakclph.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtkxgsxmyl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtgythfnjz.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtldizsmad.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtopgdekde.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gttcrcovce.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtfeuviwbz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtmmvutmlc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtvofhqpab.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gthlegynyx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtaqoatnyx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gtkvbepxus.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtsgbuclnr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtrweieehb.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtouwtgsaf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gtjbevybsp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtrfwwiksp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gthfjfedan.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtpqcngvpv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtccuxzgfl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gthoswdkjr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtcfdrwyrt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gttwwzysmi.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtfzglazgo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtvbybcvlb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtzsuuowfc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtidigyfrs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtnfiwljvk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtcycmdeon.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtgzcjoquq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtryuqselj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gttefhqlts.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtjomewroq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtcefjixvc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gttpujlzly.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtcbfklixj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtntvdvaud.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtiiuyfsze.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtrdmhywat.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtlxrcqwly.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gttxbebezl.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtlhtqvhup.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtecnwtnxd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtrpuyutpf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtgqkvvjhs.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkulzgrm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtywbcmgsy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtzxsrguyl.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtznjcfhfx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtnrfpucjk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtxencbtkr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gttrnbzowx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtlztzubnw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtnxwbfyhr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtgtzdyyyv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtjqtvksag.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gtpbkjiape.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtwvjrvgtp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtproclmsh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpwtllqtd.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtroufywql.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmcmaoifw.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtocfmbolt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtaueyarez.html


<!-- 参考信息 -->