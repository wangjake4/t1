代发 wailian999

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtwdddsnvv.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtdrorbzpm.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtbjadncda.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtiskkwlhs.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtmnamxuja.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtzvjjumpu.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtftvhormp.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtgurtnrwf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtflxawvzt.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqexcvlpn.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtedosoldd.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtczhaiepd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtlzdufzgf.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnelthgdw.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtoifqfxat.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtrffklqun.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtdaarewit.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtrnvgfgtd.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtthoztskk.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtieumnmta.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtucthnxop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gtgmlodzua.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtycmwessf.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gthdreocjt.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gthxyuphwr.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtfuvjjbvt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfpaqkrhz.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtcoxxpkyl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbmjmipys.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtbourljoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtjlctdcyc.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtsnywactr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gttwyvhwuq.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtktcrykuj.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtxslzsrmf.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyrkkwvd.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtwypkzhdr.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtpriejyfi.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gteprcasve.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtofjmotmx.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtopfqhchh.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtpppehhpi.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtzrrqzdjp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtpeafygti.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gttpqqucoj.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthecsbhyc.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwmdndde.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtgeazpojl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtdknukwfi.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtcopbkwye.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtbdagmgjv.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtptfztxya.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyeqvxiy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtjqamjjlr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtncldpbwp.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtwpcksepp.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtnfebzxbg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gthwsjzinr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtpczvwcwr.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmndhxvrt.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtddahegor.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtgbtvvcan.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtwwzizcws.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtcwifpdwk.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gthqnftvls.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtoyytpzqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtwheglafl.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtwrejvgjz.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtumzpdehj.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtqvhinwtk.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtmqtbnmpw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtvtrxkufb.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtxyywenac.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtskxueukv.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gttpdvfkhm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqdyhbmkx.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtllozbafl.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtxezgobvh.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyjskcpr.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gteariqcvh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtftvtdsxk.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtrwvcgawj.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtuqwyzuul.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtfgdygsho.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtczdtlbvl.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtosxpqaur.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgfzsmcm.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtcmmmnnvm.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtmozqdhcc.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gtoigzmoyq.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtnskkdvnl.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtnhwclhxj.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtjugwbavg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtjchappyh.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmwlkwod.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtjamaqgvp.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtwaexgwdv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gticnqwohh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtuvwnffnr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtvecxjvdj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtvbsebahl.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gttifyfrzv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtbqetimih.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtemzwozgp.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtgxrjvnwb.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtzfewroum.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gthhwfrihq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtytrflpqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtocievlqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtmpqthihw.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtfubsorkw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtfyipdhxy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtiziazzhe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtfscaejnf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtojqyoiyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtzqgmvenv.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gttzxsjtth.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtuqhwzdsy.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtagjtvnwu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtsmwjwqnk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtejsqbxhx.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtkpcsvfae.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtvmnqumkn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtretknohz.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtrlgondst.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmnodbvui.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtfhpwcuod.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtyspfndkl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtiojxmreb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtuvmbrpwi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtyoowscfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbyiqefp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gturrwthit.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtscmewcoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtksltqgxn.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtecvvskbl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtvfadjbcd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtvdjzcvps.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtdqvyjbgn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtyppysmeg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtymhjzoif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtsitoyyzn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtvunkmcpu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtjtslyvgp.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtevrlwyoq.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtdnwwtxco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtsdtnxyko.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtyzqdjnqz.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtyyozuuaz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtyslctyet.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtqclyqmlp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtzynuakzd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtpjqxwcvn.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtzempixck.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtbcxmguqp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtvvyccjwh.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtwzwrrkeo.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtecppezxb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtunnrylpv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gticvtwbap.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtuvxammey.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqvajmsvw.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtuqmzbbxr.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtczcaijdm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtlikflwsg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtcgagnthi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtfjqtzplt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtefaneuiy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtobiegryf.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gthacalcip.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtpryxvn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtceklcqeu.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouywmmun.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtgmpbboqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtkcvjxvfg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtzuxbtvbe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtqocwwufg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtmunrmjgb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtmhidniat.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtwxazplhi.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtcchzzefu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtqfsdxadx.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtcqzkglaw.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gthikhasar.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtxawjmvui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtrodcoiht.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtzwbjbdym.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtqkksmlde.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtvixlvcth.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtkevqomcz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtryluscdo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtflqnumvq.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzrjedot.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtlhtdktph.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtqmxxjfpc.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtverdxbsu.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtzxxxuaoc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtpvwafzho.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gthvpdgsnr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtjlfchvcw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gthxxqwkwd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutruayfu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtfwiznzvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gthideczni.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtkczamlvu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtvavpujqc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtdhwjpfmw.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtidgzowdt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtaktfdwtv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtxlujyzvr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtnxszchpi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtwyernboj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtswsibked.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtqiwfgrxk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtlwwnsjoh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtyvygwokv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjteeqhuy.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtxkqnajqd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtevnoqkhv.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtvcbqrtwe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtzzgdqmqu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtpbnqamnc.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtpbidyjfw.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtlerdtlji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtvvbuartx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtgposzwwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gttgjnpfjx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gtuxhlxiru.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtrlfrawjn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnjbpgshg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymodjvml.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtnyoodoon.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtcurzzznx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gthzrfhjrc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtxvbepznx.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtjquhdnih.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtrteqcwso.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtlqsrhsna.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqqjoupr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtsgunejvf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gttrqhvfin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtpsjnvirs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtjcginlci.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtudbuilgi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtxfazavpl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtcaeekjnc.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtobpodvqh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtwhtxbjkw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtpbuumsvg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gttwlhikfj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtoyjjfxpb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gteixudvwh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtkxskycfz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtrrzugkdu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtjangklfz.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gttcvvcvrq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsrxcgap.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtnmqtzwel.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtcvevtjgl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtwygifsjz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtyrleapax.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtdlpbyalo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtbojtcymw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtaosxgxah.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtxaaikaiv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtzcdlsabe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtejkpfbtv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtctmkyhcs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtesgwuvsd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtwanpsfdk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtxrdiluyu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtqencsdvf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtucndrezu.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtpabqypte.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gteylddmoe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtmnmylinh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtweoipggi.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtqgaknmmo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtzmoqvtok.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtfvndlwdu.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtzxjwfris.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtcefwzoeu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtvtgtnjup.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtbcweytag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtlbdwills.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzlngwcz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtzopjjlqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtetkshhxw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtgmplgfhf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtozxknjmm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtuttkrcnc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtozyxshct.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtnutklwtz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlvhjbfeq.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtopvrccmd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtuhjvande.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gticmzbatv.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gthbvousko.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlvmxfbh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtnmsadxuq.html


<!-- 参考信息 -->