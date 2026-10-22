代发 wailian999

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2hvazmrio.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2jyftpiax.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gt2hovuxdwy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2wuuydocu.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2fquwosal.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2doxzedpl.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcfwvbfp.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2alqvtard.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjkcyxre.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2kbqzwdko.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2xctjfjiv.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2esurrxfl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vskppggr.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2tmjhiuyg.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2nhylgmyx.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbmndyqy.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2zzcphppn.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2tjbtyuhi.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2ctqvtaax.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ranqjylp.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2lzlvuaqy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2ccgbbrbq.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2motcbzqx.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2mspntemj.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2kscbudlp.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gt2uwxukwwd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2rsudkcwi.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2hfrnbjyn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2rhufeyoq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2syfeptpo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skkfjejk.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2gqcybrap.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nngycxxi.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2jldqpmfu.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2ijoidkpq.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2pezgffai.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2qovgoexl.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2qvdopwwu.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2xmdvaaul.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2oqzxxqmm.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2lkvhrfrs.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okzbcpbt.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqqiuaty.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gt2hatyxenu.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gt2wypomelp.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tgzngcdt.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2aesynyei.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2mbxobjyq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqigoxka.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldmgrevi.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2ujnwxenz.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2gegnxepw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2egvmceqr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2qasexxfw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2tqpjwtnh.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2kkfaawer.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2edvkojeq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2kkrbypwy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gt2xcbvxaub.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2yhzuojdl.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2mldojpfb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2qdturgxv.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2cadbyrkf.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2rgxmrgci.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2lygklfit.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2xajmqirx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amajyzjn.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2tqdfxcvn.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzqsjmpd.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2tacogphn.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gt2bmfbbboo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2xxebyuxy.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bymmdjbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xneokcqk.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2tyfwmenz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2osuuoawy.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gt2noaufmkh.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2xkesqdmn.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gt2xjwvpoby.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2inzilzrx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2zpsvjqtx.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wpkjrcvh.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2qqhvdcju.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2hfxjsijv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehegcqlz.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2heuynubn.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2amhsntvy.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gt2eaaqqivo.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2mymfrtgu.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2ueoglcwp.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2tzkbuxbk.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2qfgssfml.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugjrawjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gt2mvgqpjow.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2glbmmbch.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iztvbfdb.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qddpwiqd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfwgmopl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gt2bwieelny.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2airjmqhe.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gt2ypkddsho.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gt2hgmnexol.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gt2hlvtccdk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2uxnrqbej.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bacphpic.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gt2cxnvmzmi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2ihqdkxtp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2rtnldkaz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gt2umtgnkcz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2wjerwgbq.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gt2fzhvyqdf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yceolzds.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzqefmtx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2pguwkiax.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2ccqwcbsx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2nuiwpnxn.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gt2uuuzxnxk.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2loagqbiv.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ertmlwtg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gt2lqbrtsnc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2aavivjxp.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gt2ddflbidm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2uasanxze.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mlzioayn.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2yznhrpfl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2llfhpduy.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gt2tuvfmigc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2ardbtbhw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2zwpzumnn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2uuklshxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2cegonacd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2urxodbhi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2phkuikxz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2dgmnddlf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2ishhipks.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2ajvotzge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2edebnsxt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2rbctqrbx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2akjcelrp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2okjlbvwl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2punlxwcd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gt2mmyjenqv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gt2dkyhjgkn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2idjkzxpa.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2mxrjhswk.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gt2ouzoljrv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2mnakuyfu.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kewapkcq.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2gbbvmvty.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2fvuakcfc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2xnmdgnsp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2onypbhvv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2gqtftgnu.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhkixwfm.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2uiildhpv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2ueaqklrn.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2rkxbtfnn.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2sbcvtwso.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2gxxpjjid.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2hjwvfjzg.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2jcmspxpg.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2ifvtfljw.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gt2hcmextpq.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gt2etckqltj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2ccfnfpgs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2illfxpyx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2hmapcswh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wwwljljf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2dfunvwjj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2rgimdkng.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqwacyn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gt2yqxruyyy.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2rweglwkq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2kkzhblkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2leqsxlfu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2tsowtnrp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2iovnentw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2rxgqppps.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2hpwbtfln.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gt2ngxwtaiv.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gt2gijxqxol.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgatucte.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iajhnols.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2dodjspyp.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2ohkpagfm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2xysfrdkj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2wevmxugr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2tttbofwk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2mdwnxgkm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gt2jiwrmoqx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gt2lvhfochb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2tcqffzkj.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gt2twqyofkw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsyrbujn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2jfwrycje.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2tzdxsawj.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2jchnbuzw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjitrkpv.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2mzxufdxz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2mqicebjf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbthvjme.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2rpcihobd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gt2ysimrnom.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2uolpcvec.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gt2qtbtmgni.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gt2xyecvyyh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gt2cyttehuz.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxdthdvy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2feeakrtz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gt2csozsrbw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2ibowrrby.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2ebgavmmb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2bvruuxaw.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gt2ycrtxakz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gt2giljgkfo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2wxxjqvad.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rukodrve.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2nzstbcdb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2escsfvya.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvawtvoe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2taqlavyt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2rltsbddd.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2ypfysgud.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2arbfdslv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2cwhlivep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjalcbnk.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2xznhgdbc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilnpcgiq.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2kbartgpt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2wrpljlrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2gvlkjlai.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2rlhheoqz.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecjktblp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gt2hpknmrnu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2yxbvmdda.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2fhagbfak.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gt2hwtroixs.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gt2dctkhgbm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2fmwjnick.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2delanfqc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gt2unvhjksm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2nmcdkiye.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsojzhnu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gt2wtihbzox.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hefshbal.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2yiscfbib.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2soiactgq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2wwjoqika.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2evjlgehi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2zpodvuio.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2wkosvnrw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsknsxwk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2hrnbiggm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ehglyokp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2zoizkymo.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2qpxfmyrb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2dwnbsfnr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifnnrfkq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2yxfodcfa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvseegpy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbejksrr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2sdveqmwm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqixyrgl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2qzrmmpwn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2jrqbndzh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwdsffhz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2bijksshz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2ifhiofxg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drwfigfs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2njaamfmi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gt2zpfzbzya.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2bpcxbegw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2vbalrtch.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2fgpegthi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gt2cmmcyfbn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2lmxjibad.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gt2rljxmaxl.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gt2trugitiw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gt2nskefqqk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2nsolpvnx.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2rxskiism.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gt2gccftvyk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2bphwdmuo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2blfayeeg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2ficqowwq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmnqoehx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2ayrvcksw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2phjzhrod.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gt2dywksqsb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gt2zdeqckgq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2ometdjzq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2aibmooir.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2ihiuixrh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtkjnxic.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2ealneqku.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2cirbylrq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2rzjslcul.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2raasvejp.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2wcclupxy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2mjxsktvl.html


<!-- 参考信息 -->