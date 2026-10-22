代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2bcevisxu.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2csweliuj.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2elwfmcum.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gt2xhvcexps.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2dxturadp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2zwilxqqr.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2lvhbienr.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2nxmsurpn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2cfsnojkv.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2mwaenkxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2whcmwtub.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2zbrotnra.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2cvlnzhkl.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjfrsrtj.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2aqbdycgk.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gt2gbzkzviv.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2doyiwlfh.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orwgauar.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2owvtmosi.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2tbvawzop.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2hvtfiegp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gt2nepelyey.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2iyrgjsbi.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2qfjkpudv.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2lvorezoo.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egdtfnhc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2bvlbxihh.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ffbsqrmr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ckpqiyyw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2fbjssjag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2gihevmel.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gt2ryadnrdv.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2fjsvtkcl.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gt2gscgoujr.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2vsbxvtmj.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2rqkmhwyv.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2dsndfwip.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2whqufmyj.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2glxqylbz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2npukmhza.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2deixorol.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2njnpibvg.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gt2wkrbhipq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsuuujka.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2hgdnrnky.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2jhhlgixw.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gt2lijrnpsl.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2efvwjtyz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzcrxzzg.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2wqvviiph.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gt2xxcmwpqi.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtfqckwg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2mhefyamy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2uvtfdsxb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcpxfnmy.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gt2buttybrd.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2jnnsffuo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2hkfbmnvt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2zosheajr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2ewbqtrwt.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2uvncilth.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2ngntvpfs.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2xgonjtqv.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvgwtpyg.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2ykhgtniz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2xkwbcquj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2nqsfulhi.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2vgvhpisn.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2egxgvfta.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gt2pvskqegy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2eoacwbdl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aasdkcqb.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2zrsmtyga.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2hrinvrme.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wvridigp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2ynukeery.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2bvbialyw.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gt2tbhgcuzl.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gt2fsblgeyc.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2bbvekwuj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2isubjhdf.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmytaymq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2wfwgmauu.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2byxohkmj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2nflmqnlg.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2ashkgvyy.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2dqyvkjlm.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2pgnkuhrl.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2uiaesgcq.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2sorazwzj.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2befdfpax.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2nnekpofw.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2gnxectoy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2abzlerhy.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2wgedefuk.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyjyglnt.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2iylbbrtu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2eqgabthl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2xuegthli.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2eqfcxcrp.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2sjrwknza.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2qczqyxjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gt2wpztkgrr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2dramsqwj.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gt2legnedlw.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2vdmomjbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gt2uqmrjyte.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqailffx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2lafokwyg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2moykkecu.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gt2ivcifuko.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojpirkbz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2hlsrnojo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2iepjihta.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gt2dxpozdwd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2zhaqalcy.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gt2oqctadtp.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gt2iurcbxnl.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ssxhkqbl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gt2uurxluoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvbmnghb.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2ikfonaoz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2krlzzuiz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2egwmamzb.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2dmyipint.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ylidrzaf.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gt2bnsnguon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2efnulnfz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2bhcnpufu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2wuqslnls.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2lmgruwmg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2ioxfffsk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gt2zttqgodw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gt2jbaqskkc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2wnxkzkbh.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2ftnikdwx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2isvvxahs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2liolfnkw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2eqxnbzum.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvytinkg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2jhqhkbst.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2hyvespex.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2ncvnfzlh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2wgnnircc.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2flozvfvp.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gt2svhsfkop.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mykweoxq.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsuxcoun.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2dpgcyohj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2mzgzhzdb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gt2ynzihpri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2rbekpqlm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2oozaimdp.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gt2bupcdutq.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gt2ugjdscpc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2fezudrwh.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2iivzmwyj.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfnfhbvh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2qmrgekbh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2ostnysip.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2zwzrkjqd.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2dwjowtrp.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2ppxgscqr.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gt2pacwcvlc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2jhrgwbxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ewmnudfy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pmoblwhv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gt2cdvmboqq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gt2jfkbavwh.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpastawq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ttgzirsr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2ndwknqjo.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2ripyfxoo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmthucdt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2lpsfrava.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2jnnvqzpa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2rcujckam.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2cpojzwrm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2faqcqfin.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2urfwurhj.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2aydxpoxn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2hfsdjbsy.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2geoxjdom.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2zkxezvbv.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2oianlkhn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiimckqo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2vmclswab.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gt2pviaouhw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2ifygspgm.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gt2bffxrejl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gt2kazsvuzy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2ahbmcyhw.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouslfucd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2qegrtlmc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gt2gvgdclvz.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2ryrhhouw.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2dvhrjlco.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2msauyrlt.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gt2yhjuufzj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2fdunufgj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2flaaofwl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqlvfwwp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2fgleauyr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gt2prfpxpfl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loedrfgl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2cwaihpie.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2vnecdpcx.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2svoisrye.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkkrvbyj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2rlnvfkwc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2lzmjgmjz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2weabjazs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2llsnpvds.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gt2qaghhaty.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gt2uyyvnwnd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2bvtewrjm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gatelpky.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gt2aholerzk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2dwglvgsu.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ryqbpnwd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2yotetast.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2slbjsgdr.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2cdyjaknh.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2ogfilkzf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gt2krsepbey.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2icixbbxt.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sacddmbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2ksczmgzt.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2vrtobgaz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2vrlmtpoi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2buybqtyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qoivmhff.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2svwoimls.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2bphbsowm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2ekvrhiei.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2jhjxbgto.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2xemoprat.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gt2zbovluqo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gt2wmaqvdpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gt2vnflfwii.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gt2ovbefrhd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2aarftxaa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2ddeypuje.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2artdyjwq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gt2chawazbo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2dwstyxlu.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcilyump.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ngforqyd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaajlpvb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rshvgijn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2ahzdkavz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2qbtktbnp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2qusvigic.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2jbhcyfxf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2svqwsrec.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2yuwfgtbs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2hgxbtmlr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqpuvwne.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcsrxsoq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2iogqxpfi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2vvjzzkfd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2ywvdldzr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2dscasynr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvxfuapp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gt2epvokpmy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asinmryy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gt2vkrnwatw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zicvbwfe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2tksemfpz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2nlatvraz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2kllejygr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gt2hjmkmnrv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkkivubq.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2rivvqjst.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2mlvxxdgn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hogewtar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gt2lkahccle.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2twasuzjz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzqkcfds.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2sfggwcvb.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gt2sjzybxui.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gt2defhjnhw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2rbqfxuqy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gt2tjcbggge.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2rvsrzblw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2wttwlwrx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2bhkyzrct.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2fijqftrb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gt2yrzwiazw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2bylqhtys.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2hdfqmdpt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urlkomts.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2ovcklwbo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2fnfhbsro.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gt2thontbvm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gt2qrcdqrry.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2piuinpus.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2ldmqezdj.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2dlowjtww.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzhmthsq.html


<!-- 参考信息 -->