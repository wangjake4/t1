代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhngeqqr.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtfpmynxuj.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtljuilkkv.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtiqemxhba.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gthqsoaljw.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtqhkoaekl.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtqubgzqik.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtzdpmqvfd.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtzpxyniyd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtuuqaahqz.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtuyxxdsys.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtkqoeclpe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtzpgvnfwa.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtrgeltmze.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtnedfmcdq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzhkhhvhd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gttzvhwcgt.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtoebncahx.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtpcuyzlkv.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtxflkmidf.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtsxluhnzv.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtendyigja.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtabqkvtak.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlxhmmcbf.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtlfctufdt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtxjjlkyfs.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtzxvgawcs.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtzmprpkol.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtqgdggxap.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtgbifwwqa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtzivxdotp.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtovdadlzp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtycpwjanz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtwtosjdzm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtbgerymxf.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtzengsptg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtvopgsccf.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtyhdqurxx.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gturpabzxc.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtjhbrvvyg.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtxqavidnm.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtnsigqdzo.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtvsolttte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtzshrngdr.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtbzbwtprt.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsfnipwn.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtabcucqyi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtoyvyjcal.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtpeyvoklg.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtvnzrpkiv.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtlfvijmct.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtjdqazkpx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtayilxkyq.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtmamkmzzs.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtghsvbnvk.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gttyaieyzi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtxqlcawxd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtdvuopqto.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtpxesjzdx.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtbsrarbmp.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxlnntvnh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtanapemhm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtlgfezfck.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtfrmccwib.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtycaqawaz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtuggxhjol.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtuqzknups.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcuoypjq.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtpjgqdwtt.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gtagxecklv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtdwnhoayb.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtlimfjllk.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtgbkufrxo.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtimdfaqkt.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtntsnekos.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtkqnpuibv.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtjkssldek.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtoxtpfutn.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtygdrybxg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtjvuuzspd.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtmyysydnn.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtdlfcpiyo.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtkllntdjr.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gttwapkneq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtbjpiippe.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqvtedird.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtfjnglguu.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvhladvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtdfhdzvqh.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtbmuqsham.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtacitpyzx.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtasfsdbmj.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtzeyitfgv.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtzcqazikn.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtxlqimjpo.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtxaudjyvp.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtsqrkjxch.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtlmfyyxer.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtporcjuad.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gtrozsbxbi.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gthnazwqbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtimqarkfy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtshbxthbj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtakkhyepg.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtdjpfnobk.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbceglhcj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtdeitqsop.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtzgetctqn.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtscmwnohe.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtskglmfrb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtmtfofuuw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtijxnmvuv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtqmknjbvr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtsjzurepx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtmlzpqovc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtwyoxdmlm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesbcsszm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtuiiosvot.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtktamzsyi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtencejwvk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtctqosufx.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtpbebodtd.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtfabiffjk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtfopxnbor.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtvyzvhisu.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtniwkcntp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtuehxaval.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmkbsrktr.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtzylrdxgg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvqsqooxi.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyzoiqjb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtkewckzwa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtbtbesxaj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgeldsdqh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtafsgftft.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtbxzlpvrf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtexzcmjwj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgjxiwrsd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtfgyuyfhh.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgcleigp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtarfsqsgo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtfxosnuoz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtaubxsmki.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuplqsvy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtvhkwrkog.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtkengdfmt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtbxrpimsp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtykfqnwge.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtjvztwtls.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtlenigpxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrtaccll.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtfsyfxinm.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtbzozpzxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrcljzoor.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtgejnobmu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtvrhsbobm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtozultinq.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtudzmynvq.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gthwwnaolz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtdnlwfsrz.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtjbyixowe.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtdbpyatcy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtgqeyfcke.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtrotuovjy.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtkbhwammp.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gteezlfuvb.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtzwccpnxx.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gttyykxytg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gtcpongzrx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtmafzmzfl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtdwlkjsyf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzuhxpkzg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtbegwiczo.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gthokdzqws.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gteprwiadm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtvqwcobig.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtlnkmpccg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtrqtizsan.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtajtkbjnn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtzyfgfgcp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtfieomltk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtnwipfltr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtxuzmvivn.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtqmrcwxxg.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtmckqeikz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtxiafyuzr.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtdcaqvfwq.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtgjkjbama.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gttvfmtlhe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtttsgikxi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtxznwrklw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtbjldlxwp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtklzqfkjt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtuivhsjpp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtrkpzkhrd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtzqudtixo.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtchpncylb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtaeucvctm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gttthccrqa.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtqdvypzop.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtgtvetzci.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcfzznub.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtqunrtbjq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtdhvqvsvn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtymxeylkj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtlmsfaftb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtfdjqchgk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtfokruwsw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtiolhxexd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtledqbbbm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gtemeoukbi.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkyxjxei.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfemofygz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gthezlfnrp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtagxqekdw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtbptijpde.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gtuqpwrjgy.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtjmozfwrh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtbrueyusm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtxwanfkzy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnyoctrjc.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtjbecspaq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtisrwzqug.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtznjnyesm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtepetprff.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtgivtbpqr.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiijtecma.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtholbytzo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtjzwcuikk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtnhavolro.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtyzeslvkn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtyrrhrgtx.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtmmaecmev.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtztjjucfj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gtlgvvbesq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtmfvflmwd.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtaklmqeiy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtezuewefi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtvphsoryn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gttvlvggel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtuozdksgp.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtcztwushd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtpisypswv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtakprahhr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtgfhsvuhh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtlmlaajgc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtteznyvke.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gtdrywjybh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtxilpchpn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtqbjnfezk.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gteioprcca.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtzmhcukzh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtkvypwnup.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtotujbecv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtncvipghp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gthihpukve.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtakupwnck.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtjsieouce.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtjirxxfpm.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtikscgiwe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtxzkqqlcg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtddsxibak.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtsgvrkjwi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtjecoickm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtghgdtepg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtzgtnalok.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtyfxyprek.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtskxhqqoh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtbkfhtfmz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtylzgimmo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtswgzakwu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtgigbqmsq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gttugskygt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtbvvmkcbk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtifjjbetq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtehktfxuj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtbaufeeyz.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtonukuznm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtwsywmhpf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtxdcywpkl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtuuwubtur.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtzxzalamz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtcyohvdup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtkniugosg.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtftfhlivm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gtlxmkujcs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtlwqfcevo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtppjdmuag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtuzmufmsx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtdppsnxxk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtviduemmu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtsbihgidx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtajujeddt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaveezgy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwzooazb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtywpmljfy.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtsylybaxh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlpokbfmv.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtujbtynba.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtelhplail.html


<!-- 参考信息 -->