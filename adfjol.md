代发 wailian999

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2rvxzpwbb.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhplieav.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gt2gzskrwpo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmxtlqox.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2ntvuxfgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2iahdrity.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2qcjycdkv.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2gaumgiam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2cimwaels.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cgiqemnb.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2fhbfgnlf.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oncingxc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2ynljoyur.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2obwdkxxp.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2urguprtp.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoegpxee.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfdvxbyn.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2illtuzwe.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2edaeabws.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2fyqassyi.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2ezqqusbs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2guzeaucl.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2rpnfyfqj.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zyynnpxa.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2nqnzmtwt.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqkaahgj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2dqqwintk.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2gpsfxwcn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2rovivbdn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2bvflabci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gt2agkspidf.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gt2jlggexba.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2jdoybqgf.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gt2lapanetd.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gt2xzbgvuwi.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2kgezockd.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2hncjnsgk.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2kpwmheuj.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2gxligxsl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2oqhtdsrt.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2splkwitb.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2borzxszp.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2jydriptw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2seopgrdm.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2gaphalzq.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2qxpgvxyk.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2efnxdbnx.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2ytbtqvva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gt2qqhldgee.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnlznjsu.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ruabbjwk.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2wufiskaj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gt2xxxrqsxg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2rsjkflzm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gt2oyheysmd.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gt2jjfpwguk.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wvmqzzde.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2cyyihvpu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2biohbasa.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2qzpipsom.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gt2ewiyhlxg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcxdvzjh.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2bpluklvi.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gt2wmsqtfbe.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2epssoaby.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gt2flwbxijc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2fatiqixu.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2nqxlfjgh.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2bwlhpndy.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2pjkmdubo.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2gchuouba.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2krxzpkpd.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qpwpwida.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2trouwhve.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mofpxyku.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2dgewnsbi.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2zlnhemza.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gt2ghkkchae.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duteeqvn.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2kuoxnqla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2amwoolox.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qveonooc.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhdomeqw.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lbtxflxa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2gveeoskg.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2qlacammw.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2ecsvvwsy.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2xiomulnh.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gt2vfthymrz.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2uvsfzize.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2gosuutrw.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2ivjuazbt.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2wypwkvrl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gt2ziseexey.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2pohlbnvb.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2mfhcbxzw.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2pjcmjlgv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2apzrbnor.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuayrxyt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gt2ytqltyhf.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2coyczxgf.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrjilubp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2pnqohduu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2glbjeqqf.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2mweyoahn.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gt2hnrubmrv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2hgfumzbc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2cdgxubcm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gt2jfqqhnkk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2dbtalbyd.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2lqnpwvtx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gt2vdhmghnq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gt2bglcgbnk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2hebtnxbo.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gt2cnucckcf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2timzojmw.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2latnaoeb.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2bontxqdw.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ajgdgajx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2aenrelwb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dypegyrv.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2nxdpcqjs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2cecrgzzz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hpblfvfs.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gt2mgrkybxe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sakgfomi.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gt2anenhkjy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2gtzzjeim.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2kkausyar.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2tynsvlea.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yywvzode.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gt2blbrebag.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2okrdhjdc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2nxnmiewf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2lkldyddu.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gt2tfetnqhm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2lpaxgitu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2srbchecb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2joivdkbl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2uxfmvvfs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ymjhyrwn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2srcyilyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gt2gyfoxvji.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2nzdnbynq.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amkghuzf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2pkkzusgq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2aesxowbw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2oirdvbzf.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2vklxuzeq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2fmqoxgkx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gt2phdcmzuf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gt2znteksox.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbuwtvk.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2bootutic.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhkxebhm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2rkaizqxt.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyfijbtu.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2nzoiwdhh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbfsxnfa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gt2dhdtjmcj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2paahnpnu.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gt2whhpzrdz.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gt2ahxpvmkl.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gt2nozpvuyw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2egehuhlr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2lncqpjcy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2tyaostnl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2colgpnuj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvmeaswf.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gt2scwhrxal.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zcycakcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2ibasfnql.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gt2gfxytvgm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2igzhqxwr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2hkejtypc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2lemaqtjx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2qoiiztxz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2acvgqpxb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2baejwtdk.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2kegqlnhh.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2zljzfoog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gt2gdajuhep.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2pwjbbpmg.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2herezssc.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2zfmznnzn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsslmucg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfxlhgmp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gt2osnuialw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwnffyjx.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2fadrjcrq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gt2wllsytct.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2wisjdpbz.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2extzgkrd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2fwtvbuvx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2abyflvbj.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2zxlayvrt.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gt2fufrguok.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2zjdywtlh.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gt2xqogmyfz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2gdfualat.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2xmgssbcc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2iywogywe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anwpktct.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gt2lylwkdwf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2pdifxeqw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2twhrnrxl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2haqqzzgl.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2vrxtavan.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gt2cwdoitvh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gt2brehvlrp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2pxjitndr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2nvbqnauh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2yqsnagup.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gt2akwigmty.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvpcfxaq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqplmarn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tkvcxkim.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2rqycikxf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ixpatgdb.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gt2bjwaebux.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2tghbgefu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vatkibba.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2lhisxisa.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2qgwptcpl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gt2bxifbgws.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2nlfksrlb.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2emvvrxaw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2yxzobdoo.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gt2rdqeepza.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2flipfovi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2qozwfdpr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gt2opezjpjm.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovwgyocc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2hybzfqzz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2hdezgltj.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2urfbmjdb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2oyjpqfiv.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2xxeiolyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gt2fpoaowgg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2pfmtbgkb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gt2yzsusslk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2tpmeumzc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gt2xsvoqejk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2mvzrsgcj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2yxoenylr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2nkxyzpqw.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2zsyjfkne.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vvdbxqyb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2kbjgdtwp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2qjgfbkic.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2ukcrbrpf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2lwdedmcz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gt2fghqgklq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gt2belyusah.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2txqrpzso.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gt2qbozumuf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gt2rpznfghg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2avkiblkk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2ommshoce.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2cvmcxpef.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2qhtngqur.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2ngrxdiyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2gwrnghvb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2mdcvjzpj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2bvacgsyq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2izybqcou.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gt2jldpmiir.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2hzxivdmo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2dskqcpjq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2jntcwvrl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2nloeewno.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvyntidb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2jknfaosx.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2ghapsjvt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2oqulbcnr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2rcqmgyza.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gt2jcutrisf.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2zwhqbnri.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2hfffifzo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2wenfaixm.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2vcdcmduk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gt2qlynyojf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2iplxrgvn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2udkpflcz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2bqinqrnb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2myohikei.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2shjbdjkn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2jqipedrb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2vymtbnty.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gt2eduqeyjd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2gcmsikwi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ptkckiwc.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2yacbcvsc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2inrxmkrs.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gt2oifsavdx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2gooxfxmv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2ofweoaxz.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gt2vhoulmza.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2zdkdbbye.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwadcfad.html


<!-- 参考信息 -->