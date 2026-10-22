代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtdzlmmvay.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtymgqoedg.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpzfvqzk.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtwyqbrlei.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gthhkusjtz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtsdefokev.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtyhxqhttb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtevugwxrq.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtakzrmskf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtsmbsmyva.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtuikipkmj.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtuljmfjht.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtuyshiwxq.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwbpohzv.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gttoazdyox.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtbemreqbh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtzonywvlj.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtirazotoh.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gtfoqzncso.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtknpvoqcc.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtflepivcx.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtubzvoaaj.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlzfutokv.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtmttvewuh.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtqvgjhhua.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtzmyujyyv.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtxxwvpbhr.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtfjmxyzrj.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtfdnkjyrt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtbfaxodwj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtqoeunoql.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtbltupxhn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtwzwewryu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtbhkfccuz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtscydfcmi.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gthivkmula.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtnrduraay.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtiqihvkcn.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtpmkffzcq.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtinxkjtum.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtljqayaoh.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtnjzjyohx.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtbwusuhdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtjwhdaojh.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtyfntitqw.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtvgotooyx.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtzccvlqyx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtnqyfneur.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtdfrdsvrn.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gttforexfn.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtefkvtgts.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtlwehgaul.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gterpfkiqb.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtgmgdlejo.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtazxsdlny.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtciappxam.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtspbjiywh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtomsfxtqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtdpgwrlky.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gthaufrkef.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtesmcjtrb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtbzqbnmog.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtpebixzbr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtuerkfvdc.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtjesuioyn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrehcqbpb.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrjnlyct.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtwtscwljh.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtgbitkcfi.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtlkbizvor.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgjxbkjx.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtwvvsqrum.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtrykjpsjo.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtjlewsyxe.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtqnphhhbo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtddmdyplr.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtmijaavbe.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfnhmxpz.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtftycdatn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtvtjbmxbw.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gthmzjbmll.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtmzdlxtuk.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtyqsvukdb.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtvafovdgm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtthddqpex.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtcwauipyl.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczeuczly.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtbqglzjiy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtfbrdrzmk.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtfhrvcgtu.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvptijsf.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtrxtbpwac.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtytpdoamb.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtdvkfgrqb.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtvbsptwyv.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtmodbvbnw.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtzmdmonac.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtcqauoshs.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtwifasjqa.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtxwmufcyy.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtpntiauum.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtmrsgewyl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gthspocgzf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtpwozwxpm.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtzdjijkvu.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtbnrzxldr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtjcyyflki.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gttxmcrokt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtsvsszbfj.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqtuhfwx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gthklplbok.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtyzjuvqya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtgeanduph.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtqnfuvdli.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtrlcabirx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtesgkbsuk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtooanizsp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtykzjcabe.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtdxmpbpml.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gteifrohqv.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtpziuhjuw.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtpcxkwsns.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtpaodcujl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtfgjjfszx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtqdhksbos.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtqutpoene.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtmvjkrttx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkhmlhfvl.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtnknagvqs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsibifmne.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtvnskykxy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtbokfuves.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtywozgizh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtftenzlcq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtopmspajd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtvggkuitf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtuusptzhw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtisxfrfjx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtyvaeytup.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtwjirorxy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtqemavwbj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwzlauth.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gttofsyoni.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtffqtaqxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqwqopdzt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtjsgpkmwj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtfrvprehr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtvkmabtqj.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtgdlgeori.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtlcjmaozg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtthxnvpta.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtpbrfcmbf.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtrpbbujva.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtlqvcpssx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhlwlxbf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtioutnktm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtfrmvijvw.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtuhvevrut.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtuxgddbtj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwtlrojvo.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtgasqyktk.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtkwyptfnd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtsbygyjlx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtbsvgdvtu.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtyxoqjuso.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtpvlvxmnz.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtghzpcxqp.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtdtwofvjl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtkzhmoiql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtqcyfcxfe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtdxfoqatn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtpncflyrm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqcgavaj.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gttyjwrlqw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtduwwgong.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtbzgyuqmf.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtpnxikvhu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtveruyqnj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtegbifznr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtotbvbkgu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtsahymbpu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtkjsbyawn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gttagmrein.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtyyahzwaw.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtgbtbaakg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtrscwlqkx.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtvtaybdrx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtpvkxmaaj.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtpzqwqfdy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtbaccdyfx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtiysxtvpe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtusnhbtak.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtrlwvbrca.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtuotgrnna.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtuynhspwc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtwxlxmwdr.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtvtrvzknl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gttewrkjvq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gthflzlxda.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvgwfqhz.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtuirxrqbp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gteehmbvkk.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtpxydkxfi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtnrpzvdje.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtsqazwoqn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtufqwzksh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtwndlkeuk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaaduwze.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtqqzcvavm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtaitkpgfc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtobidxvxu.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtwkmrwfpj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtnuopevbh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtzvstpwxb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtxshkfrch.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtstbvnona.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtmsoyojss.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtepiibqst.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtxocgigvh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtnpezzdws.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtobmqfpna.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtqwzzyion.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcjbpzqdw.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtpqefbzlm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtohshkcbo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtzvpbmlmu.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtmzkiduio.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtxqnokjiy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtpsknbbbe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtomynynbu.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtghrpemmb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuonccals.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtlkdcphua.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtolfiaacb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtgorwtxva.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtexzvtdbh.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtyzfkjwpr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtmuijjlat.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtkrqibmpo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtnombyxjq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtduywdbgu.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtydfgkbje.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtncvdequm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtmzpehczz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtttzeufbz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsulvrgit.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtiwdwcvbk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtauvrdlbc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtjympbjec.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtuuempalj.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtwxolbdcq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtvfvxfbvw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtznchvlie.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtkkpowopa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtmlxivjzs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtsztcjvuv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gttpdhrawm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtabqainpp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtiseaydgx.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtoszqjaou.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gteczdejrd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtandettgb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtxgxtvqxz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtvbjzmiav.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtukneyfiw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtiycffvqd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtvoumvjxp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtzrjuirzb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtlpybvdpu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtfsqgjtdl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtvoqafgdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtzzninggy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtnveirgxt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtjrivhjds.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtydkhrugr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtmmfwfcts.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gthilbryuu.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjliayhp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtbjapvjri.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gteoejufjg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtecpbncyw.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtazfjhiph.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtgdfvacpe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtlvstdoka.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtbwbregmj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoaundlz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtlpehzkdi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtytuqflth.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtqnyixhnv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtzreabgro.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtqvlohldq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtrigyzqbp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtqhaposyb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtydylaybw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtxsckmixi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteyoiabyj.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlncbfxxg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgofsqkkl.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtuvesiisw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtrspgcwzg.html


<!-- 参考信息 -->