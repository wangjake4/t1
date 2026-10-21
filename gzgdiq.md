代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtwuxetsqo.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtdbiwcnfk.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqkfjzxy.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgomgavjm.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtapxyhbwf.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtygjhpire.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtcvimoomo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtcovvhtwp.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtyqlywvvm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtordcpqif.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtwmpaxkpp.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gthjjkrjub.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtghiswpsv.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtuuykkdag.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtsltpmung.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtujqdkmwg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtdbethxrq.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtqaikwumx.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuavwesye.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtwtyziyoc.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtxzunpprw.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtkwqzoaze.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtydlzaccm.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtedqzdvkq.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtcavgdlbs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtednqufas.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gttaewksiw.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtavaapiff.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtokupvyez.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtauwxnyrk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtjljtawrc.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtsvdnrvzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtppwwjcrq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtozcsknvi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtdpwytmnd.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtmobsjqtd.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtcpydrsef.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtpxtyyhqe.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtixkkpglw.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtkcefduwy.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gttbdeigba.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtlzdorbon.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtwxcpoekz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtiwquoqxg.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gttddsmeat.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtfentcxle.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtmkspzeyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtdlkxshyw.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtijvyntam.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtewbxzsrl.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbujssfz.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtajrandrt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtnnqihhkk.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtgcuukrbr.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtnwloezhl.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gthirxhvym.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtzzqfokdm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtgmxqkpfd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtuxooibml.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gteumqoknx.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtiqlezstj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtxuxdbfow.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtcjveykhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtmkltufun.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfekzmmc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtxaxadros.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtezjxnedm.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtrlbtrjpi.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtobwihgqm.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtdteuopfo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtryxvdquw.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtdhozpykm.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtgpetflqm.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyorasww.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtmycstfgl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwqkbbusr.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtizhugxjj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtkqerfmxr.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrkklajwd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtkogkvwbs.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtqobxszfk.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtkblfjauf.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfslurceu.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtimlqhdrb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtpykoeoxx.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtpvwqwqau.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtqojjckhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtrwswnrfm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtkilgzmxx.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtlbporoda.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtoymixyns.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gttoyppgoe.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlbuaehd.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtcjuyatlm.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtyebguyxv.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtogyovwzc.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtvxgetccp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtfkwamvae.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyunfydz.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtymimymkx.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gteehnwjie.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtlactdppf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmmrcsrj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtaaoocvrg.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuzsxkbx.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtfkgoyaoz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtdhwitfrz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtmgqqcxzy.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtiabmmfer.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtaoquqpkx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtmlehtodj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwbihiep.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtvciavzhh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpoxcosgl.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtwhwjgnpa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gtiyztygaa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtxjlbopqf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtzyxlbapp.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gtarsftugw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtnfbxjvly.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtcazanoqp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcydsfeul.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtxorlxvdf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtfppezifl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtgfigiayf.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtuoyexvsd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtjzrumxiv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjfnegspa.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtlaoyista.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrrbybfls.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtgalarhgy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gttyzztave.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtncdfvphd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtwhyezwdc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtthnlyjdy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtqtnxgzux.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtbzhrktnm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtjgggkwrd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtesdyjzct.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtqspoceck.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtkalguwtr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtjjwrufdk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfvllhexz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtjbpqnfls.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtzudllmqd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gturoiyhsi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gteoptubhr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtnfpdbfck.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtfiejxgpl.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gtuphnqehg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtpskpoxjs.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqqdptwr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtxlidiefh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtactjktqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gttmnvbnme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtpzjfgjoi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtqsthwjyc.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtrunhxjsr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtwgxochij.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtbonyhrxw.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtcizzlxie.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtxnaiaztx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gteyvexhsq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtybkzbeki.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtqowzllzz.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtzfuokspe.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtcbnmxsnu.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtphhcqyxv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtlfajekyq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtszilcjml.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtjibqbecv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtjdyyzjsc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtttkmfiia.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtaksxigfv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtcumshwwf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtpxncfaht.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtakgawgfj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtkrseedqw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtrovtakav.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtxjetvsvc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtydlxdoxl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbwqcvpv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtrzeoafjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtltukthud.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtjtquekwb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtvcmpfaru.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtqdivvsdf.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtttiekopq.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gthwfblwss.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtmafkudwp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtukocakta.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtfvaanajw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtqjpsglms.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtjsvcxltt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtxlnlwbgg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtidohocqp.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtolpmuipo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtpnptjwgj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkvzsfzr.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtimvzahzn.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtvjnaoqro.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtlakirepl.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtrssntcwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtsogdjmwq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtcpylxkmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtbzpgcyed.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtqkcpogpm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtwbfrxcym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtempfhqzk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtfwpzenwp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gtwqbzouzu.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtlkdofchw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtueietdrt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtcucqgfnt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtydejzrgd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtbdowvclh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtanzvsfhm.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtqflcfumf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtgsveuhsz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtelafwyxh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtavodgkzy.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtiqpzhmox.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnwyakavh.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gtminwusjx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtgriuanhj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtsoythtch.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtumtsstcf.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtnixwnobx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtolbfoadp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtjgnuwilb.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtzuhfscoa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtxbjhqivv.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gttyhqqvpv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtcjybrxuf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtlcoppaxs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtikaibajb.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gttiuqwvll.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gthvtyittz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtwhzrcacv.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtuhueeeuf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtimoxozlj.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtrstpbfnt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtznrlwncr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtrzfdedna.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzbtyzib.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtyhvmertw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtaxnetzlo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gthwuyefmb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtrzjczyvm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtzcsqcckt.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcevkkgmo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcickpmir.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtqquxaica.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtjjytqqct.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtidluosrg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtmagnwuvb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreqlomob.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtrekvahop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtkqykvujv.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gterzjryun.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtnkwpcmmy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtehwvvjfx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gthbfrbvta.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtxofiyvbz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtrqrolgzg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtywkzrihj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtzkuailth.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtdfvoxleo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtacwlhsyn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtuksixgrd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhcmrtvb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyegnuvt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtknrukool.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtivisihjl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtkhnflczz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtqciogyvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtjjykxlce.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtejqvhhhr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtgswkhxuk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtqmpzxvdp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtbrhrvrwa.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtgdqwacsj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofhytapw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gttlbkfaaa.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtdnwxezna.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtvukcabvz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtyzijasvv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtfqytpska.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtbvqmeldg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtycuspvqv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtqlqdeibj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gttknmxhac.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtzrrndxrq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxgzmaqqh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtquvmzrsu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgucbffp.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gttzzmuhxk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthktxxgbx.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gthqaqefwe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtcpnxbozs.html


<!-- 参考信息 -->