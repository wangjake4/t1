代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2tluomlze.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2gzwoaeke.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2iwqxobnm.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2pusqadlw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2dmaaihye.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2zmnkjolb.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2euzqedzw.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2mtazmywi.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gt2ugajjqxs.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ungatpiq.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2esxquryg.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2othohuyx.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aoptveqc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gt2nxejxast.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2kwbulyav.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2arvivquk.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gt2rmngypci.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2cfelwkpw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdmczcgk.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2trfgbgtb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2dzszzeuc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2kptcejag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2vifdyfgx.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2multmepg.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2qjvjtlgu.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2rpqtfnal.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myvtwfrj.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2qebknecr.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkuouoco.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2wpaklmuf.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2lpgxenle.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gt2bimvouax.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2ffzjiyaw.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2qvioaehi.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gt2ifmremrc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vucujtyv.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2fzowoqzi.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gt2ijkcgqcd.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2rvvttsat.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gt2tvinxmad.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2wdvcgzfx.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2fbndqslu.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gt2abaktqyb.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2lqozizcb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gt2xbbhpnic.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2mkzufjxa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2zvonbfco.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jiiiwhyc.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2bskznmvs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2pqfdqprl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2kqxdgtqc.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ksyuznam.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2rqvlukjt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2ceafjnoc.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2epojzmug.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2gixlxzvr.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2cgvrdglo.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gt2efpwivac.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gt2hayemkyb.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2cirjddjg.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gt2rumvngfa.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2wgmetrxc.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2zixgcrov.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2fwvozgxj.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2mzcwjebe.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2govtbwlk.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2kqnkiebh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2vaoavofr.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2mzqbkabs.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2wtszntux.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2epedsksf.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2tbmqxoeh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2zfkyomja.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2qtizwgns.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2tytgibao.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2mowrghbe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2bmtfpflg.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2czvkvnrj.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2mueqxgrg.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2iaotokry.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewxozsos.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2ouerotgh.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2eaopxhhl.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2dnjqkulc.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2xdboxqow.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2tzwvhthr.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2ylelkuyy.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gt2zpjeonkd.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gt2ukgvlsoe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gt2ukavbjee.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2kjnkxgxb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2gkupewil.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gt2fdsxappw.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2eqfxfkuw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2begrojqh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gt2fyyjjflw.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aywkfkwx.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2gozhylme.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gt2uqgvmhuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gt2wcthvkax.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2kymfkdfc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2phnkyshr.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2xkeoszrb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gt2rhqhqsrd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2wgkzyreo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2pomhyrqm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2aasrvbxs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gt2zhmnusvx.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2wcfptgye.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2dhvainsm.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2wpmpbjuw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2uuhojlqm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gt2ighcysfh.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2ezpzcxpi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfcopslm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kdckuect.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2ddhkgcil.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2oefrydnh.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gt2cluwkmii.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2cqtxiqrf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2yiutyulk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxudhxvu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2drxhpdtr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2iwfexajo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2qswiuqsx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2teyoncef.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2jsldczbf.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2xphyiash.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2nsohgpbs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2hzvrtmwt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2agionvyn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2egghnejc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2tpalnugq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2wquzxvra.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gt2wmluqdgc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2lriwtowt.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2fokcmrba.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gt2forwvmej.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2cqrvsesf.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdovivbr.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2cldznxkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2mrdjfanr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2uunytgxk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gt2xzjgnhcf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2dsrcrjbx.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gt2ilhvaipt.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhawzpwe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2tjphxvxt.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2nrjeipwt.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2wxwtaqqv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjhysvms.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2uupgekad.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2ngugaser.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2eviyipej.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2mhdxxjpg.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2egeseokp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2znyqdsxq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2zrtzgyzt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2kzaxmfnd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2feoonuvb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2cikrckqn.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2vbsfayvf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gt2oqzuwmgw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2echtwcoa.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2lemhqlpj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2mczhiilc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2ywuleiqv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2etrbzbzp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2uxhfuzql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2utnglmke.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2ophbxgpa.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2jcjodecl.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2zdfinwmy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2nkwcdisn.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imguzqsh.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qewuzivm.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2ikixbmqo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2cqsivhzv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2qclhchri.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2ysyetihn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2piwesghh.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gt2kwqcifjd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2yzvpozfp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gt2ihfsyosw.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gt2hkohqapr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2hzihajzd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftwldpbx.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2pvjadpji.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swldnvmf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwztqnpw.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2hdxlnbni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gt2ixudiqtb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2istbhthk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2sdyaxmzn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gt2jzwkdpvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gt2dfktascz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuzdfoof.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2ordyxdiz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2olliidrr.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2tioaeakb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycztquhn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gt2edpjabze.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2xkqotaip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2ftneckfm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gt2ikzkwjtd.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gt2jcwfywjs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gt2qsvezzet.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2ifkrhyul.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ympbbxod.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gt2vutqzryh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yzmgmhqd.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2kfncocdq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2ieourznk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2abembnyz.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2ihufdexx.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2yxhcejkk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gt2rhcxstqy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrghvgg.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2wdplioyo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2krckkdgg.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2oziobqrb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2fwicjfgm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2shmqpecp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swoagyqg.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gt2rtrahppk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpxtpbrj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2rcguxsih.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ardmccsl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2tzbililr.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2evjgabmy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2eglscwfp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2kqafperx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2oszufyvp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2aeoyoaku.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wyqrobtu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2qflsdvpp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gt2twotdlfc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2igijolls.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2xousidbr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gt2nagcevmc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2vrojmwgg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2gizvnbej.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2ozrqmxel.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2gqlwfpck.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2qiiqmefx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2lmnexqgd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2ivfcsznl.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gt2jjnggpeb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2ccdgznsf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2ddhpdhro.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2syadjshr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2rrwyjbzg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2hnizizit.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2ximqfixt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2apicetyp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2eznamvli.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gt2bhejwvbs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2csmyxvfc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2hdkkaivt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2qjhwvbew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2dkppqzga.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2ofdcfirm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2yyrolnwc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2anxzjjml.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2ibzlydkf.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2ltsnvhmq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2xwbwblcj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2hrfkkzza.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2adozrmae.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2penaxzcq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2dlhekqmd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2jwkjnwpa.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gt2rtssqifq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2qfafoncc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2huursjlk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2muvkjqoz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2skslbepr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2innmfwsj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2slfnwggm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2cbocgqye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2prqpqufo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gt2pgrmzijh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2ajogzwow.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lfqdabve.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2znzwbvmw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ataqjuji.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2xtgzgkle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2bqcnutkv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2zozlyoza.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2kjqqaaoa.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2ozmrpexr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2xvsipnek.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luzrewxj.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2drrpxjpv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2ahcfsumg.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2vpxmljzp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgaljnit.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2qoxgcfjh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2llqejznx.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lajgvyry.html


<!-- 参考信息 -->