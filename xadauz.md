代发 wailian999

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2sekmzqip.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2tpqoscdh.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2thaptpnx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2dtprwqdi.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2tavmuklw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2hchzxbld.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2nseclpqe.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2uoqadgko.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrplcksc.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2zmllngzz.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2xknhgtyu.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2uvntawbc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oorichhg.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2zfsziizq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzrzovr.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2oaectlyo.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2uafjdnyy.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2jamhoico.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tfzkwzqd.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2xswxetjl.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2yvpljynu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvawuign.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gt2oqcqncub.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gt2ixcamqzk.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2nwislbze.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2nepbndeq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2rbwbcilr.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2fuufphos.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2fwxahzzj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohfdiyiy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gt2oktmsasj.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gt2vxqqcrov.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2rrnnlftw.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gt2degwugoy.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzloxdgy.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2trltjsor.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2fyznmkoh.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2cpwinmce.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgfkuvrr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2dloaalwj.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gt2abbpgaky.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2diiqkges.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2kdqfvrfr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2jdmkrjyi.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2mrejatri.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2gvnkqljb.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mvmsoxky.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2kamhbxql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gt2luccrgnk.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2yxklugqi.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2qomlomhc.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gt2pijnbkol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2yjjkqgoh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2pueeelgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2lvaqwunu.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gt2oganvixr.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2vgaugzxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2pgplstfa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvcakojv.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2ocwoijos.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2dqworabr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gt2odhawjit.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2jkprnrfk.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2fwoqecvd.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erexbxhi.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gt2oqnqtddz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2zjpadwtk.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnwqvqqq.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2sqamgupv.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2vngmgidj.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vflbbqsj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2knwiucpp.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqeqcbgw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fchqxyla.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2xoxcscxr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2jxyrjwyo.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2dnesxhnz.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2ipqotqcn.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2fgyfiats.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2sljxlnrp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfxmwcva.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2qxzgdjfs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dermvsjf.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2wftlkarf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2pcczqfan.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gt2kvjzteof.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2syoruusf.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gt2ldduvdmc.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2rmlgvzhk.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2voqdkcnu.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2ompuwcqo.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2sxxocwgk.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2ifoccbpy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2zpwabwut.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiplhmrq.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2ffvapswa.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2vmuexxiy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gt2wfyyfhho.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2phisjbtc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2xynalnwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gt2myvexfyc.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gt2jdbmcvqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gt2wmudmayg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2hfvhvovw.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2tvwpijqf.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gt2oztrwsmt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gt2qumswhzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xtdczcsh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gt2sasdhkaf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uilbbjmn.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2szurjfyc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gt2cmnlweci.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2bhycxoqv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2oesghxzu.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gt2pgephjml.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqgrwozv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2hqytccpe.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2bzouvinl.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2sdvlhoyf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2rmzpbkil.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gt2nrojmkej.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2engkgrmu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdmcnhvz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hxydaogx.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2qznjawcr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hupkwdzm.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2hisigyjz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2lohqvkiv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2ihsrqgml.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2dlyuonwq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2fvurqfqp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2hubcyist.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2voelnotl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2vclvwmtd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvagybkm.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2llltwodz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2nkhwjuew.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2vyyimjxp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2xnsatbys.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2ncefltgc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2cqucbbvo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsdqntkg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gt2wouzsamw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2syartlli.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2nnlnnzca.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdncmyrb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2gjaumqkn.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2ntptlgqo.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2eeaidpyp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2qoifqmre.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2kdnmpftt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2jdswhowd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azlqhrbx.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2iqezkxgv.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2uvgjriiu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2wzsanxsq.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcissklp.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2ixpoesxl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2xpuekolp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2zvvuopne.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2udaaxfju.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gt2hgzibgfb.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2eaacdntu.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2qfcpoyih.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2qjullaxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2dfguvzgq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2jqlnhfrk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2icxdorzt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2jiccslii.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gt2kgjyeguj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2xylucofw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2lclphdxd.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2fduxwkmh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouixlbvz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2vthwogus.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2qqhldkot.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gt2anuhisqu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2kwvnmiih.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gt2gzzsfalt.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2ednxxnmy.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2vcwjaezg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2oycpqmkc.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2hubrwfgj.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2ncalzues.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2wqgkizcq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2ggvxdwpd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gt2zvqjjpre.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2vcrldjxt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2quumfbov.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gt2zxjcjmuu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2bxezexng.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gt2ouicrpmf.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2tuvgrpnp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gt2qhmithis.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gt2jumgwmzo.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2omfycwbc.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gt2bifufeqj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2amxypsvm.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2dsjozdxd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2utewidee.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2rhnkiogj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qstgwrsk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gt2lpidonoi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2rpqvbgft.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2ajwqwseh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2rnnhgwsc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gt2eaaxrriy.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gt2rfbdwnan.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gt2ihtfhnvc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2wgwzyehd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2suqfaukc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gt2jrqevkck.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gt2deotwjeo.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gt2wrvufcuf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gt2aieirpnu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2fwcfsyol.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2baozpojj.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmgkgale.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2sveimiwx.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqpjuppm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2hukudaap.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2fuawapih.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2oidgibsp.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2nnyliqsz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2jpwxpycx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gt2mrquwyim.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2yskhcqxk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2mjyhiryw.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2blcijzkz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2fokvermv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xveexzoy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ergojwtk.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2xbroxxim.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjeyjtwi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2fnjybbpp.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2icjqphrq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2jrmhptxh.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gt2qswfyess.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2ijxcslwo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egxbwcay.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljgweeve.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2haockryb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2rqysyfql.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2tdctoywz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2nnimxqkc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gt2zngcswla.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2neqnlugw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aytvegzt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovjuqial.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2wqrwymre.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2dmnhbhzz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2fedjqjqk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clhfconh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gt2sqsjdiun.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2paqumney.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2fkayjvap.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2hmwsmfvt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2kydblvst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2ilrardpk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2phrfnbbp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2uwnxoltb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2nipyxiqk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2ptjkdwcy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2uiynebsf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gt2naffykku.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2kwipjrpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gt2xgtqimsm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2npxgslza.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2odkexgdg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2bdqabayg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2zykcozbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gt2cfsqrsjn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2sqqubpbr.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gt2oyypdhkj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gt2iwqtvozr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2hzyadiov.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gt2fsgonllk.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2mckattay.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2ssdjqdrj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gt2taekplgn.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2jlvptovd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2udpdlzwo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gt2fbicmlyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gt2sqkprgaz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2sjmyrnyj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2gizctgtn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2ykvhrwlj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2eaxliieh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2npgqucli.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gt2qhkrdzjq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2eddwuerf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iidzphmt.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gt2jhetofhi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2isbvyncl.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gt2nwnrpbsp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gt2hbmdarqh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2xijzzbhl.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2jmcouase.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2wqdmtrel.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gt2mncztweh.html


<!-- 参考信息 -->