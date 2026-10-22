代发 wailian999

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjnosgde.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2rjbvqiyg.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2ngjotdyj.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2xkqnltaz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2ctrvncle.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2pkrwquqn.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2kypdlhmn.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2duoyemop.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2huigrrha.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnhlwrzk.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2snwpyuct.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gt2goxbqqus.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gt2sbijyoui.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2fteoabvz.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ugedhfmx.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yhrtlnfv.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2brvvhwry.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2tqbobqpw.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2synjjojv.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gt2rassrvja.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2izswbxjn.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2qplwcony.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2zdkcgohz.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2ftxdmfve.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybvoelne.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ysbbzcqd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2vqqovmlv.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2ezoizkev.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gt2vkmgrmzv.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gt2gfoirddo.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2vamtghid.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2hspxzwzy.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2zytuibgd.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2fckuajow.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2ixmkpsof.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gt2aghdkzpm.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gt2svkmmlke.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2dfumzzls.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qubdrlea.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqebjnlo.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2fhxucdbj.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2llupwxru.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2wphovshx.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2ucpkjbam.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gt2cxxztkld.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2nistzjaf.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anahdjrs.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gt2ofvngbqa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2kubowrjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2eyxytyuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snegzqus.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2sslyfexr.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2txhbwpiw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gt2aisyqdcw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gt2kjalkejc.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gt2lebvimmv.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2ofxfptic.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2mtfnsgem.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2hkcthlxs.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2ebxzboqa.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2fufefiwv.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gt2xmlebudy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cepckyac.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2wjcuqwsb.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gt2hiqkibgk.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxjhxwlo.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2uemfzxaq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2oxtwjlpo.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2qnksbgie.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iygqirbk.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2prtgstbh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2elktckfp.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gt2rhdenclq.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2yscnvuij.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2dhbfirqk.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2hsymsige.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxmqpqjm.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2hnzyqbkg.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2mcptzdep.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2vdvbbhop.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdturln.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2uwkkfmiu.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2bkohcoyo.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2utdamdsk.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2xjhxvhwr.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2nterfjzq.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2fsagqwuy.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2iwdzxxte.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxrnqqlu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2eitutgbb.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2ezdbpfve.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2wqpsgfuw.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2lwfawkus.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djkkwreu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2qoadfxmd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2drysbbqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2snwjbrlh.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gt2ogcuqfqp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gt2vrmhhhwj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gt2oxyqzydi.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2rjwvugmn.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2wdoayxdq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gt2tyniwonx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gt2uwhqrxja.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2gclbvkos.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2edoxlszo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrqurtx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2mzbwfuni.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plxqvfyo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2epjudiip.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2ciuhrwqq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2lnaggfyj.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2zkhdfthn.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2bzhcwfpp.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2bhwfycvj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gt2eocjdydr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gt2nqyyoybm.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gt2pzvfsbee.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwdpuma.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkpatsyv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kptphtcn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2yfdfryzi.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gt2ytqkgmdz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gt2rwshnqmk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2hxqznvdq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2cctyqast.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgxrvymw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqpaclfd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2nnvgfbva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2fhcjwgfr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2msizlbag.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2ioenqqal.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gt2axkmzmsn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2heedrsla.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2srasaeau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2qoopbvtx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2rpbcghdd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2yekzvacp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2yoquvhyu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spxcezbe.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2ulspfjpp.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gt2bngoaxlc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2druflkpz.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2kzrmmusc.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2hazclfiu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2jpimepxc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gt2vkxtqado.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2ckcfbgde.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2clfteqkk.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2zqfdfkrp.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2babuakfm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2danwxszo.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2levwkfty.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2lggnecph.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zzqmfxfn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2gwptocuz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gt2ttyexgiy.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gt2ixyhqidl.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkvxvydg.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2bgqdjiwz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmsfhymr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2xlauogbc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2pdlafkqb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nzltlmyt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gt2jbpopdoa.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2bjphpmah.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2oselhpbf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2tyniybzu.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2qlfpsviy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2rczagqsq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2kqtmjwub.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2jvklvsrh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gt2sujuwrdn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2bbudfbbo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2nmfluvsp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2oeoedxze.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2nwcumcjz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2roqdiyrg.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2dgfkykwq.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2baretuhg.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2xvpicswv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2bsavklku.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2rcxvttqt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2lfqpsylm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2ocwuymaf.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2lchehqmv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2hshjvsmu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2irgjcrgi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2svrqqkyc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2eufwkjil.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2sluiftvi.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gt2ewlaqtme.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbzdmmyw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2eklriwaa.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2fsqyugvg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2mepggtup.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gt2jhdsfvpy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gt2hbnwqcrz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gt2uylwpqmn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2joimwywu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gt2xaviweeg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2cosmtjyz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gt2yzhhwrfw.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2cpwxqfpt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pddldqlg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2mhqswiay.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2brzvssfx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2szxnprzx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2cbfzpkik.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2ltjkicly.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2werwjehb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2bjcrosah.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yciclgzi.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2jqbkytke.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktlglclb.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gt2vkmmsbzj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2odpwbggt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2kptjnvcv.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gt2kyhdttob.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2sjwfhrmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbaspses.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ievdppot.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2ygiaddri.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2bapxsfik.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2jzbwxezk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2xzlsodaw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2fznumjjg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gt2mydhwgac.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2lsljummx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2xyfjvzjx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2nhjycalg.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2uhlkvsac.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2tkwellyu.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gt2aaaldkze.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2mrwlijbu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjheludy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndxyukfo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2nmglmqbw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2vcxizklv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gt2mzljropp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2nvuayjlk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gt2ijbugseg.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qauevdrd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2akzzxlho.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ajotjawu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2uqvnaqve.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2xniobulu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2qwumpyqr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2pnwnqpaa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2wtuezooz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ihygnjqn.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2zsqxxxli.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2squccrvs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2mhcbvcje.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2dqphhkrq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zosberaj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gt2xustluwl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2pahhsdnj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2bcybnmgs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2vwtyghxk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gt2eyzasbti.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2tqiobcqw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gt2dtwxkxgk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2izogdqkd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2ywjmmxse.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2nsgjhnvd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2trwyhhif.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2qntydznc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2ntfcrnwz.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2qigpzsbm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gt2aqcvgnpe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2ciexwuvm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2lwawbhus.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2czpcpwnh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2zldbioyr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gt2xtpuxdum.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gt2ehalmbjc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gt2uyyvcsef.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2oynzirzk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2qifsrcji.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2pckcyswu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2likqahzb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2mmjirndl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqzjwuxj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdhttwrv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2kttdqpko.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2hanwzmph.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bujkqiiu.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2tcjrqqxl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xnvxhcbd.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2bztbddif.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2knqpwypm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2eemgozam.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2bieaozkd.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2pyyhwobg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gt2codksvsn.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2zemjtpnh.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2ctquunfc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gt2mswgoatc.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2azfjexws.html


<!-- 参考信息 -->