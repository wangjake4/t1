代发 wailian999

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtehzacikw.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtczjbtzed.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtajhayeob.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtmhpnqifd.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtjlbyaekn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtaolpmnbn.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtjcaljngo.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtbpmqncye.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtrwxwzktw.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvuviudfh.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtxmafovla.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtbejlzgys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtshrfoxxd.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaeoqqnd.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtbnywvnfw.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtflzivdgv.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtqhugmumj.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtiwoqwgdj.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtkevwlthy.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtlcfxgwra.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtpyrihpzj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtphhngyzg.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtcrshvycn.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtobxsocoj.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtuzyhhidm.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtfqfkjmzt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxesxnupv.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwjkkogy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtugfgmwtm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtrinqnxys.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtrnmxzuhw.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtjgaajhge.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtsupdjogv.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtzmjriopa.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtrdsnudlf.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtxkjduhdj.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtwckehdnz.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtcqbembmc.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtkbqzwfcl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtqwyholol.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtjqrvznlh.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtqmxzafiz.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfsshrnp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtzzyyhdqj.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtbowdpvbn.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtajtmyfwn.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtsxawruez.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtpirlxtpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtzwnfoftm.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtmpevbajc.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtrnfxzrlx.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtgqvhbgxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtftbciioy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtopufawhf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtoiowvknz.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtsbiguuvb.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtzlfedwfv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtzduiouos.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtbaalnopa.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtvktpddtq.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gttxzwvbgy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtxmepmool.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtuvjzhiam.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtmvyxfghv.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtpjlvqwqk.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtxggrwfsm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtluomdcuf.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtparepkyr.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtlzfamijp.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtzacnzhkn.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtptyyvzvx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtktzqmfye.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywbdygbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtfcfugtff.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyurjbcux.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtqzgpcqst.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtyxohkjdu.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtpvdjpqmh.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtandgfjuc.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtesaarvfo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtplnhinpw.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtldnthlyz.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtrlbfhevn.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtfuhcuabt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtvnijgsee.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gttgyhlnaw.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtygjpxqjm.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtjqqandsp.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtspqmbhnu.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtsrgwzbxj.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtukgaaacg.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtfmiqhbds.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrnbvrgia.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtzrchjgpv.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtzabgnwuo.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtqnxjkflx.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtccaacvxq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtcecuxlrs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtxalrmyvi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gttwacxfzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtyxfefbvy.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gthgmxqadp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtrdmxjbhh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gteppnujyn.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtrofpqbnu.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtvgdrlecm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtnpgizvgk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtzboqdbdy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtvxddkrcs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmvsyrib.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtzrvyszwp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtvfjrituz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtmeefoikx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtkkrmacjg.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gtxbsxjdrn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtyczxitfr.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtqpwsubye.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqprqlojq.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtgdfaggka.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkfpxpjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtlicyrbie.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaxrubad.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gthxnmfcam.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmjfgrtoh.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtvqqehisc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjngrynem.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtpbkracrd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtdnfoeheu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtyqxvkcig.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtuenaeohj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtbqdsbovm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtjhtngwcy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtnaxngbwd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtgoqnabvf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtevsmwexy.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtbmwqnowc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtjqsktpsg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdpfscdli.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gttqmmepyr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzbcacmci.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtqfiycxms.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtvhgdzgug.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxhbrefmy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreqzgcuw.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtwevrpldj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtbnvxlqpz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtuclcytnn.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtaftrzlrd.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtljpouvka.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtqplfxlkb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtiwytgguk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtzqrkcurv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtndtjvplm.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtpppezyod.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtnigrzxdm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gttiuelhlr.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtvyrmxzdw.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtsmncykzl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtrvqzbcss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gtxcvmlzgc.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtljtbftul.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtoqeflzrd.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtroiwbxph.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtnsafjstx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtmdwahmuf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtlfrkgzou.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtdaqdwpga.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtajmiylre.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtmgjaibtz.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtwdpfknno.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gtknrgkdci.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtbcxjlqas.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtzzqtjkzf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtshxgwfwt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtgxguwlma.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtteazdtpp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtzpfnwyck.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtkvsijuir.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtelmpbynw.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtnhdklzlv.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtrheysjwy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtbclzmimy.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtkewixwms.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtbrbvxhpa.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtgrxuvzlm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtfzzswutl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gtiarknlai.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtuwmcssyj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtuwkqbnlm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtdynhchmz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtzvjkmiqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtokbwwasp.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtfbvxjffo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtpszsiyth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtozguaccu.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtzbeihzbx.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtdkotsgsy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtnctvpdfg.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtpxactkxc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gttykfbwkb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtpjunfpfh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtepdsrebx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtythpevxw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtqyqoqcfq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gttkuzykdo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtxoiouset.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtmtincbks.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtbvrusyxg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtbolsfble.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtaiyintce.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtzovqwhgq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gthucebbgt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtlqakquev.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwienszsp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtcduhszfc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtzrkxnumh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtuzqjsgkh.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtmvyrmonv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthpabuepp.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtkyxtwzrc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtxatiwoma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtruchzdzn.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtjunyjtfn.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtveuvadjt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjqeqvqr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtbtpnnbua.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gttyccyoqw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtdckmtpsg.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtezauokrq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtxdiaodup.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtzmypptzu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtxvigwwju.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gtrvokjmwx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gtsjtmxqfo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtgjvgonof.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtjajpsxtq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtxmhwcdps.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtmlzoxszi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwapuizn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtosohkpti.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkhakcrh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtqwnvioxq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtlipqsott.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gttgmqtmsw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtxrrxaulu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gteepxlheu.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtcnhahkid.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtwbzazcpb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtlgoclewr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gteewdpufn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtebostmfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtdrmaogec.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtaxrfioox.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtuxwqhjcw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtrrobydpn.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtmwucvgrd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtgncjqyiv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtqaqfivlj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtubbsgpzr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtlgdvabvf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gthnndyhzs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtdsvvvmas.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmtxctif.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtzehqzjbj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakyecqiw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtmudavxxu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtjyurgawr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtqemjhwid.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtqgydhwvn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtykjmfeuv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gtusomniun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtehptlrrh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtuyujlfmk.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtenbddhgy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtexkdyhpv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtveepfdkx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtkxikvrjh.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gtgvtsndgv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtqmloflbm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gttmvzfwsl.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtvdijaatc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtbznjvvxb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gtswwxfurw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtmbtimobd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipwnwtdp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtnqzwvggl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtxdrzoyzr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtjhsuhwqg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gtlcxtxfuj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gtzmvbvqsy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtmkztebem.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyxajxpoc.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtqlzvjbws.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthenucqlh.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtllniowxe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtyyzdaahe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtnjzmevco.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtildnosmg.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtqwofxqlb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtrkhqawjp.html


<!-- 参考信息 -->