代发 wailian999

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2qyvvjlez.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gt2zfcwyqeg.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2dqgtuasx.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzgiwhhi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hwqsxsiu.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2vxrixwhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2kfbkmxxc.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2jgufisea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2vmmirezk.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2cedljfcg.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2sngzepys.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gt2xosahflu.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gt2tpykfanf.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2dermmxxq.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2tztsihjg.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2fksqpylr.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqxktpxh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gt2qaseoyyr.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2zmbodzxf.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2svwiuald.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibaccqmm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gt2psrqddhr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2adcojdiz.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2yvalzjor.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2iebzslrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdxxynvs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2zjkbkysi.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gt2yjhxhetk.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2rjgyeyco.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2tvawdptf.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gt2umkakght.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkbfvped.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2jhwognqm.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2smzhrzqo.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itygntjs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvvnyopn.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2pqxgwuxe.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2apegfzbi.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gt2zakaxxgt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gt2fizlzalx.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gt2qmlhoadc.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2whqanchr.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gt2psdhvjhm.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2ufnkubcp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2gxlklcew.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gt2mktkgzyy.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gt2znzijbbc.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gt2nkwoclil.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2kduzchjd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2owwtucfd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2twsyhwhy.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2oqzdhjws.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2yrpykmug.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2mqodwsng.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gt2lcdllekr.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gt2xyvcoctp.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2qyxfrwjb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gt2pdmmfgrz.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmzmilbc.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2fkgjzfhr.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2loqueznq.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gt2kcazmvvj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gt2dqijweuu.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2ihmcxnew.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2snkptgre.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gt2vblhpblr.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gt2zigpqlnf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmghdzxf.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gphtmals.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2qumdedes.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2telxiaqh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2tzuodrwg.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gt2kvgsouqs.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gt2zoplkxvo.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gt2zkwutyon.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2irxoaebx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dtpncdat.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2dlurfroe.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2xdjjjakw.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2onwvttsb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2khmhkjss.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2mktbrcyd.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2odncewbe.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2vhgvqmsu.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2tiitjneo.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2yqcoizsu.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2ddwuanma.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2hlpyadus.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2yazjvluq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgurxefn.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2nvecjoaf.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2egwrfyva.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gt2cmzyacpm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2pxidpzsi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dagayabw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2rjohpwfs.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2ahjyuhxd.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gt2qkozhtkt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2lripfwlv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gt2ugamuudp.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2wbrzsegj.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2wwmrplkt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2awaisxcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2yjhgkpge.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2kgeosjdc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2oegnraqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2rsyoynii.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2kjkulhzt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2fevwdmwk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2vpsgravq.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2vuipikjn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2gffstect.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2ywmgyfyu.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rreugcds.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2mbswdbnz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2uegmnnmg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2kvjqqmjw.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2iglnrmnq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2xppdyozy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2aulkxnfc.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gt2sozseabq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwkuzbex.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2yevkyjgo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gt2avfamtyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2igndprkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2rzrfayyp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2mtkuwzfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsglddoi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2qztwdzzd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2detnncom.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2zcfzqjfg.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gt2hkbhquxw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2pacjiqlb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2gtysxeea.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2wugagtbp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jafwilqc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2bdofifnq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gt2pflxnrnr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osqcqxpg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2neoulukk.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2yfzotovi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2bnybwgiv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqdeecxk.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2yvortbbq.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjohultc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2yhdqrjhi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gt2iuwsfrwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2crfwzwwy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2appycuje.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2yabuqubz.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2mdcdpxgp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lusgahjx.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2siahajyz.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2uzgohvxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2xzdwikvx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2hdfrkukx.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biyvaail.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2goihzwdf.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2urabtvnn.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2wcifbjsr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gt2jnkjkimc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2lersokvt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2znrvreeh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gt2ywtphrsz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gt2mmrkpqvg.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gt2gxbiyixr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2nmtihgdj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gt2akwbkvtl.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2urciixeb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2ayfsqweq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehesqano.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2fupynhfw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2izzxkfex.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2zhuyctbw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2jgzedcgr.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gt2qzqgagev.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghmymdei.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2qnwrbise.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2nxumasiu.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2sjgepzcx.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2ujbxbhwk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2nffpprta.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gt2fhxeocry.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxhlbmsh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2chctkkjv.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gt2slivohib.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gt2lhdzgqhw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gt2lpcznszi.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gt2kijcvzdr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2fscupsid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gt2lapcfkea.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2yzrtazvc.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nffuzoiz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlqzwocn.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gt2vrigjqqn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gt2ewkuxpxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gt2jvruuzba.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2ppxmjtte.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gt2afdbwqeh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2vmluzdup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2ioytylve.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2uviijfmh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gt2rhfoeequ.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2mcbinnna.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2ydkbnxnz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gt2uiitlclq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2ihuxzeop.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxemfrgi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gt2iclkcygl.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gt2upxiyihl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gt2zxhajvzd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pahqprvf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ydqrvfoe.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbestmhp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2oeevzbxx.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2ypsahlfk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2dyqvnyxb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2aavicghe.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2wtnuqtia.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ofhenxgh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2rguuqxfz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvxfyljg.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2crthipcx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2meenvukv.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2adjauzkn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zwzrgqjz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gt2ndnqskki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2uubtbfgm.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gt2eubxeadi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2qskgwzrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2oftjelnb.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2smcpvsyr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nohusuhy.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gt2dhbxknbo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2quflodlb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2kcyraoka.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gt2lzhwyaed.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2zfyuhgpt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2jrthhgoj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2ykvyjgwe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztbvprkv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2hiedfsgq.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gt2plchxxbt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2slunvzoz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2iabsweav.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2hiayhdyz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kerrgblf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2ihpdryjs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2mjufnyuy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktgzmrgi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2lhcqkbcl.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svhndtix.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2zxeiftzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2pnozujbn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2ttdruhoc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2abpuooni.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2ofjynurx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2etakxqof.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2xzaesjka.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2irfjqesb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxwfacl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2evzfvdav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gt2gdqqvyle.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2iazclrhx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2zyqzzwpy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2ljdivnsl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2mrhqgtvd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2ympswttu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2nmjgtjpb.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzmzelzb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gt2bpvhgryr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2ygpyphcx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2tazzqajy.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2rsawsfam.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2vwbzueza.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2pyeurbvr.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2ifkxltyv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2sjsylpld.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgczemne.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2dqfgbllc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2lshsmusy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2vloopnnm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2fikxoooj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2mzokbrmz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2rhdoqoxk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gt2tpswjzvr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2qreaxtud.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2dvmhzigz.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gt2xhtzsvjh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2pstvodtg.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2ycuxzont.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2boglpmoy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2ybelubwm.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2ngwxofqz.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2ifzalync.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2dzxmtcnk.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2guxfrmjr.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exynjafa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2xhydgxhc.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2knuusnnx.html


<!-- 参考信息 -->