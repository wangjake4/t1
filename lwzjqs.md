代发 wailian999

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtyqsconhd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtjsusrjgy.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtkzsixyyi.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtbtiwjtxw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtwgqnlwex.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtdjzzzale.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpftzzovs.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtwghdizuv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtvxdbqmpu.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtedkyhkuw.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gthdpidprf.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtllvhuwzi.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtncbwvxzw.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtjmkgxqic.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtdpatwwcv.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtuhlcylll.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtkjvnwszu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtppmxugqt.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtugjqxdvj.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtwwfstsup.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtunwdknis.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtmfnfvwuz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmknsohew.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gthzgqykee.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtxroblljq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtuxuzqdzs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gttliqbidy.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtuoceqkpw.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtilsltckz.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gthdflzqwt.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtmhukktub.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtehrjflnn.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtwftgxjxr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtpigcsvfg.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtcsznvpzd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtqtgewuqf.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtxrgriqko.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyknahsh.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtymkssbyi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtucpumoqg.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvvheerpb.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtvxxggfvh.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gthylhrwla.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtpimlodxz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtuejpohmo.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtrvccenkj.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtcjqyvgqa.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtbtgrnpfw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtqhhefawu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gttyorjkxp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gteishllsf.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtzvdrdlxo.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtxyksdiho.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtqadnbrpm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtnkjtcqob.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtwxycyuqj.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtbondpbnh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtmzlgualb.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtriokfdof.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gteizfjdum.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtejrcnuxr.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtntsdwwwd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtmryctqpi.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtelcsjwut.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtfwhnawds.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtghlicsaa.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtuitsdimu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtougoojhd.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtpnycxnzo.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtlwjpistl.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtnkvwoflj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtgncagkzj.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtgatxcxag.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtzwlhihzn.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtgayskazs.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijektzbc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtmmmvwief.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtwzxhmnbz.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtpinaqvqr.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtpajzvpgi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtjsgtphma.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtrvxvmwmb.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtpobclfey.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtpvutryls.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtsmnaerns.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtrzkyknae.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gthdrzqcyg.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtpmmkwlej.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtfdntabkn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtnvbbekgb.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpknzrya.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpsahmii.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gttvwunvlf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtysxkawyf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtupvaxojk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtivjiemae.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtcwbnanac.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtnzzrfrxc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtotavegdl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtrgznoriw.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtdcrwlnve.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gthodqupnq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gthhmtemyh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtlqgojzvx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtsrkynjdd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtyovqmopx.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtmafjqgyc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gttkalaase.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtoecfnrbi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrygvpjrz.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtcejszjys.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtqvmqwjcl.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtilsiajta.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtlcrgvwtt.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gthqdgrzyh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtyviplnhn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaocuyqdd.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtotufklem.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtksmnpaix.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtecdhcanf.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtvauutbif.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmmedynab.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtzgtsdvhf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gtekhmxurc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtlzwbyjel.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtaftljbze.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtdxmglmro.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gttlogiojb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtbkqlqaok.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gttzghndvn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtmlaasanb.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtaxbrilse.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxscthymd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gttvrxalpq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtgdmrfpjp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gthcmrsuzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtsdykmimu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtattwduup.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtixsgathe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtplxhsnei.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtrogasrar.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtpovnehka.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtpuxhzrcw.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtjpfemaik.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtqgryfedf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtjjffdpxb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtdvvjnnyz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtqouoxrfh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gthgjbpgek.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtxmyukeex.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtrisyaflp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtlsdgboou.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtmczfybov.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtsbhqyyha.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtbcwndztc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtpjvkhfil.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtiaegzvdb.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtgpwuxdvj.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaoksrpq.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtlraqzqwa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtqljzuoqv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtamfdicbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtwqcqqont.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmsyphgca.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtuesyciea.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtijjyplso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtavxxyjim.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtdfucjneu.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtcrxiebdw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtnisjarxg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtpnvnjicr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtweuahtor.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtgndlmjro.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gthfxxvrhw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gthckfwulu.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gteweyhesv.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtgpzcdrej.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtaxnaatrb.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtjcwecbcn.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtedqokgje.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtsqfrgjzo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtmxnawpqu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtsrqyslek.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gtyoxykosc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtpcbfhqgo.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtywzfyuvo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtdrctzsly.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtqbscsvxb.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtbjmoqwit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtmsgcywmw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gttsdrdglx.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gtjznjrslw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtjhhendee.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtsvjfzedq.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtuzhpuhfc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtcwarzqmx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtnclcosxy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtiouiccuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtonbcaaur.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtfadrjxht.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtsmgdbdnp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtkcwiuswy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtzfktyhze.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtyntfkhqt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtkrmmmksw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtrwhdvfbp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gthkarlixf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtkjihlbpy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtyptiavdc.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtqximjhsk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtmdcxmkdp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtdiccetsw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjdvtdrnz.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtgfxkxddc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkiygkavh.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtshmntmgl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtyltghuih.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtiiawuoen.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtxumribxz.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtljbornst.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtiiegjnnn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtpycpsmfp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtoxmkkzin.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtnbjtefot.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtwfvjirbz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtezlhefnz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtinbmawba.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtbwkaiwkm.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtquqdncin.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtasagvryw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtkvbtfaop.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtgivcqixt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtlimwmvel.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtgbftumla.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxddoqjxx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtynxltsjq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtmjuuqdnd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtpdcypdwa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtpzttdfjc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtlwsgripm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtynlzihjp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtlosktidm.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtrogurcfp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtnfhzrtye.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtehqgkwbs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtzbwfxbev.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtciskqixf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupctbwgb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtlijmqgxt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtcdophavm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtojamfjtf.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtemnferky.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtioesvuan.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtjdvtnhig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtgyghgefw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtgfvsglsq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtxclokhav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtrzhlkfiu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtqylxgvtj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtjrkprjbi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtazeztmwr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtljkoplcs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gteizosoed.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtqxasyyci.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtxfdqpoyc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtetysmpwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtdwnbrfib.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtxhqdnrde.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtleomdvok.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtrugavtfa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtaafojuxt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gthsibacbh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtvkzfscgx.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gttrbrqdnr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtkgepepui.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtsplwccae.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlrzxryy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtdpknnnzz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtqmuulees.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtcqwaaqmm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtoiibnhim.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtyjstgayw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtxgqtgmrd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtcenxwwao.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gtkpegbwrk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gtbtgpwqno.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwostbuch.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnwaeotrz.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtjtahbntn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrixvmxjn.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtbrmltjdl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtqiqpeafv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtoylyebov.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtbbfzokwg.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtuojzgzxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtixbgwxoe.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtnjzvwyrm.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtacxrmgqx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtejriydfh.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtwfczyyvs.html


<!-- 参考信息 -->