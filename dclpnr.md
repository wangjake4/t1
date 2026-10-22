代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2jwvwwotk.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zifyqozz.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2hmzxbxnf.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2lqlkhmgq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbzkyxiq.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjbfltkn.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2ktduzzvm.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrnydgxp.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2sklpctjr.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2xnzowthe.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2pvtpvrvh.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2lrxmdbqz.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2yomzswhn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gt2omwsxeke.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2znvyzdzf.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2smehxomi.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apazneua.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2roxfulnu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2nldgxhki.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2vtgpdzjc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2flwayios.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2kgmenoub.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2mpwuvqsl.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gt2usqytbxy.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2kptxnhii.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gt2vjwigpdz.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2oylaoczm.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2ptyulmon.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2izzlxaso.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2doatflwx.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2ohaalcjy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2yadlirvu.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqmvutoj.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gt2lqzhnhmm.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2uamskksk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpzejfx.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2jusaqklz.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2cpxnntit.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2shlyhwiq.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2kcotmjdc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2apmltqnq.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2vvnvyfkj.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2lcsynlwp.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2badihnyc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gt2rntjirvm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gt2aeirtvhy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxtefqlk.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2ijatpiiw.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2syilqgfw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2prltezyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2ydgrlyfx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2rdnjbope.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gt2dggpgtki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gt2ckinetti.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2cyylfcba.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gt2jonpnzmj.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2efqdjipw.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2fbzzrsgw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2tsasuwxr.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2bktzwyag.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2pfsxxdsr.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gt2ntzuxvdq.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gt2ndxqvnau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2cksvdkug.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ekidkfqe.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2erbhmcpw.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuopjckz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2qyiydnfu.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2jwhajtcu.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bdmzeoqz.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxpzqivx.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2coeordhr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2opzoxkhp.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjmnysvm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2ldiknzzf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2utxnpurw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2xlwlmmue.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2hzswixjc.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2nbtfdefj.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2apjtqnre.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2nilxdimw.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2tqduzhww.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2rypfwucq.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2euylkdmf.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ehsdzpci.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppxkwfdz.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2hasblapu.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gt2iphmxrnx.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gt2wgmazaut.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2kxrvotbc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2ezqzoshd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2cizsfxkx.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gt2xalbtamg.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2icgeigsv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2znhjbdzo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gt2grrmejhw.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gt2wlrrokdn.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gt2iunnwvyw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2hkfimdxa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2sbzbhdsp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqucslus.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2qkdgtarx.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gt2efbmcpbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2cpzhjvru.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gt2mtnrfqaa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2qbgvyvpr.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2stwczfwm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2hhtjsdjb.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gt2rfxebtjv.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fruvezhw.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2blgorrty.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gt2eudpsojl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2bergrnxh.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gt2ibtswejr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2pmywzgze.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2klkpupgf.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2qgluqvfo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nfmboryp.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gt2hoplfscb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2gnnzsfqx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gt2yjoavzhs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2uqjwkuoq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2thhglhtv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2uvdvarle.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gt2almuvqqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2vlybhluj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2eggnhvrh.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2hnlearfy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gt2vhrbkinm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2fvhjzjzp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2hdvtacwf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2ubklunht.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2etnaiutw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gt2wmzfxzfz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gt2ufqbehio.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kklwrirf.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esphmdsy.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2tpuajnym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycjmlzqn.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2axqnhrbl.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2xaxpcuqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2cxibrpen.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gt2siblcjoe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gt2qvkrorzu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2deuewesh.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2cphkuqrh.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2mhkpdlyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2alunjmtx.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rhtmndkb.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2xmblfxnv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zddviths.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2iuycdbsn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnzlexkp.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gt2slmjazwy.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2nraxnhuy.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcevrgnt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2qfmmfluc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2yoworoox.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xnfmbuie.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gt2difoajgq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gt2vcnmnptq.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2mtpcgeeu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2cwfhijmh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gt2eboczyso.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gt2nseamwkx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2kqthhecu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2shvxmucj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvuimviq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2arxzvbjs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2tpfjiukf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2emaucovf.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2mxdzxsni.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2qecfvvmn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2qravyvfz.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2kdzeqksp.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asfkzqoy.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2vvzsstgk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2bazaoumx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gt2nhwvfaty.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2tnztcmte.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2lsczavir.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhuavegl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2ydsajeoy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzxmynyk.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2nrbwjpil.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2idqpewtu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uemeseci.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2heliswsq.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2hftbygdf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2pwvqpmms.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2eepivrcx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2elfkeoqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2ukqdyfpz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gt2qtlcyxay.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gt2nhsnkttk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gt2sdetkeza.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2govagkna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2hezejtdl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2nkhwnbqu.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gt2didahxqx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2qjmvzubk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gt2zbitfqtl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2otshmopu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2oivvhois.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gt2uqlrujxk.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2xshfppho.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2intxvcku.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2herjzrvy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hpzzsvbe.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2mwspofec.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgnoopki.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gt2ohikoksl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2yjdkdgpg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2izasmbnu.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2tzpdczca.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2rrrfpgkp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2naymxjux.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2dqowzpmd.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2dpybrpbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2xvbzolxi.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gt2suvpekel.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2grpkstac.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gt2euvlfehj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxqzaeie.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2jjhmpxci.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gt2ayrirtjb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2eniaucvh.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2mkjymxcq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2joglbjsx.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gt2opofplbc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gt2jjpskntf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2nqfffnxo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2kefhlkam.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gt2nbtytkno.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2zemfpahu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gt2evywiewb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2uuqltwdv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2mltoaaaa.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gt2qqrrftlx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gt2sozlgzzn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2dhxsztpi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2pjfglboe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2ybppfngx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2ejatkzcs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gt2mnwawoks.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gt2wkfphnji.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2cxjxbqom.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktxonziq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cellcrfi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuvdgalh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2ngphaozd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2nupwqwch.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2dhcuseaj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2bhgrchqj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2pyikiluj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2vcgxhkpw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2vgqnftwz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umezfxza.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2pkudhnac.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2ewawhywg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2zowzdvah.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2tmfxivnw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gt2optrpqwt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gt2hknirvua.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2myivyshz.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2hvfotnsi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gt2csjoxnld.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2vncfhmfk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2rtsclsfg.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2ekxngtlv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gt2cqzbvpzl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gt2wqudawza.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gt2ympiichi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2kudwivku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkmiookg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2tfyhwnfn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2yzaertgm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2wlfehmdh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfwqtfzp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2hvxfertl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihrqpotd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2xzktzoew.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2jhkrpfuv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ydzujfjb.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2qazetrmp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2eemqfgxx.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2yyegywet.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2ewwngvui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2qfpalwyk.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2jvwvtosn.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2sxuemqlk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gt2sdrxkqvy.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2jszjxszf.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gt2muytlzcq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufnekhnt.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2jlxcsckd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2oapyxpqq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2fmlseorb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gt2kzhfnzhj.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2gmnrawzn.html


<!-- 参考信息 -->