代发 wailian999

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtsufxcrwq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtgecwlhjp.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtuchcuvgb.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtasyakxdk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtjmhisfce.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtvtmkptej.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtnhrcqxff.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcofqkyec.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtphrzzgti.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtidobxrsw.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtnccmlirn.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtfeksvnfc.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtliobrgnx.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtjfebmotw.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gthmnjqiel.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtirgbtnfg.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtlrmvioon.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtmzagsbic.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtjwyqegvl.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtisythbfz.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtbomsnufk.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtztvuggli.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtdjqowbsk.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gthbawhfpu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfgksnrp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtfjdptqfu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtudybkkib.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtlkvazhzy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehgyskhl.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtcpiyougw.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gtwojywgdm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtnhcqimog.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtpejndryi.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtznimyveq.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtxvtfpfzp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtvflgunvp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtueezltku.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtuvqpbrpa.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtsaziacxs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtilfayqsc.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtgjmbmeat.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtvuipxsrm.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtujgnwbdg.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gttvroydns.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtcsvxyvln.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtwqcccxiv.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtmibmqzlt.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtjemqofbq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gticopddft.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtpsdrvanb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtzivgquks.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtzcqpyqob.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtkbynyena.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtsvvphyal.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtkndgsbue.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtatashuvd.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtkkkxrfdw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtuzvtvenf.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtcpmxdpwc.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtwskldaga.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtozscblwv.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtcxsasjfb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtfwysbiop.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtwuannkhc.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtzrecieqw.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtjptbzbep.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtcazaipgs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtdpzoklmi.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtceqlfykg.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtavktydfj.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtalijmoyj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtctvswitf.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtnvtvbfkt.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtvyqeqmzz.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtlkqzdirf.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtkmcgtxei.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthnautpoe.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtfpmeinea.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtdlemfiuc.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtbxydhbwc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtviqgwftl.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gthsnwydhv.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtonnskwmh.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtrpbwdptq.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtnmeoxchn.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtqvekrmep.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtriqospmf.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtkqieehyu.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtyszvcpnz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtqdrcufpj.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtmwrzoecj.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtdzxelmnf.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtzdwsysnp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtqhfpsbtp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtpyhyqnly.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtfensmeya.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtiaxnpcet.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxseunkau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtwcwbmacl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtnwjvslpx.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtrhfkdiiw.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtllwjdyux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtihovivpe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtbnedbjen.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtimoswlle.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtpkclgqss.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtoaergkch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gthrylotbv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtnfcfcf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtmaznhpgg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwclfjnzj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gttfnrmjjt.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtarfvzjko.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmmzcdxns.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtrgahmubl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtfwnusfdi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gteapqxczh.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtynyetrpz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtivsbcxqc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtagldoobq.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtrlwiyljt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtaajlvfpz.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtemuvilnv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtripltuix.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtfldwljja.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtopyrzzgp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbaidbgx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtlumhjfmf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtlvpdutfh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtevtmexjf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtlaisgjwt.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtyukxdwam.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtkkfxuasq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtxwbzywds.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtsmqtvdkm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtezsqkwzr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtgkfyzayj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtdqtlhhia.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gteeoeoclt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtdeejuuus.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gtalmoyasz.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtkqxxjmfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtkxciieet.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtkceyagzp.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtdkegeixx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtlaerhwoi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtuwnabkjn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtypzkaufe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtdcvefoui.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gtwsnfntrb.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtcanpmwir.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtedairyuc.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtdwyjljcg.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtbwlyhoeb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtznbcgqau.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtgjelfiyj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgcmcxae.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtkevhkten.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfbiludb.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtojdrajci.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtqkzvcdqi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtwestrill.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtxqrkhufu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtmnvpqjjc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtvlijdmfu.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtzsxgtwuz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtzorqwzmg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtisvguxao.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtjsbbvdoa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtvyzmifrk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtivgraqrw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtrikjkyco.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtynnkhnwd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtejoshinv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtbgatzszj.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgdmymjl.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtknciyqpy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtsqwvdepf.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtieajearq.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtghlnmklj.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtfsmpmzlp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtxcreioaj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtemjxzc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtwilyblys.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzmbetwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtqrvuydgl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtshbhcbkd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtkpjdjizv.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtjabbjlxr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtbevxpvaq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtqubwicbk.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtyltuxudw.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtqtcjqlhw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtjppeaseb.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtzdthfwup.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtuxpjwgbx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtycbtvedr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedcvuocf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtoowbqigx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtsddcsfty.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtvvkswpcf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtgdslxtnv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpghkedmj.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtofopsdxj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtwuwvdywz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtefpxoqqb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtassrmtfj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtgfjchzyg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gtxyxmsgfy.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtjnvonekv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtisathodl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtnsfggyls.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrbtzlcyt.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtxhfheczk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwadkarda.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtglevyten.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtxdzeusvg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gthlanrdqc.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtthqswxlx.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtnozgbabu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtsebcoxgb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtmybpemwj.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtldhxboiy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtcvavnget.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtnsdzjubq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtkngesckr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gttpjpgeeo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtlxddhgdh.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtjkangptk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gtygkvnmzl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtbhtskcpg.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtccdmkqey.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtmgydwytd.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtzhacqwwb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtmepkhkyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtvaadptvz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtbviyaghn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtnicdvzyq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtwkotckxn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gtmnsgcuhm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtindtoyci.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtiqvuxfce.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtmftxrlal.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtmljnmvzp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtspzmbpqq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtwsfojpjo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtuessvgbj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtqsdzbhep.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtdjlnxahm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtghoktphg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtfaruektr.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtfntttldd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtwdxlznhr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtbvebvmew.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtghhtglbr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtxpyzujeo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtikyfzcir.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtojkovptt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfrktfaq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtzuevrmez.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtqpxtoqdk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblrcndyh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtiztmgsgf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtcalajjyy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gthinhnxna.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtqimumxww.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtnknoknzn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtmblunjzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtlthhjqop.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdyrdiif.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtfumjcatr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtlgaschra.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtpnhpgtpr.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtjnfqkzxm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtaqsuaytz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtrxbhegnr.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtgmphmhhm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtbnjucoau.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmmhcwem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gtlixyjbay.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtvcnchqjk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtqitcypph.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtejvbyeho.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtprxgiioi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtwblqgugk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gttpjphbkf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gthbzldbnv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtivlcggdp.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtezarlgep.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnijepuvx.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtydedtatv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtbaiowjbf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtwdyvasyy.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtlmolmtfe.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtfltzqoln.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtllburizf.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtngwbspie.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtgiquksto.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtdrqyfpef.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtybdapbqh.html


<!-- 参考信息 -->