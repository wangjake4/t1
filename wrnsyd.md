代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfzawhzmy.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gttfxsioil.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtghhncymt.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtcycpiwej.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtyapgetsy.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtdqxiguiu.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtsvgfptxv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtrcdwtkke.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtpyvohtat.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtuaqumjci.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gteapnilqr.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtysauqkvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtdzmdtluw.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfiybxdqg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtrmjmdavv.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhdnivps.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gttmkwuneu.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtwwzrvrvy.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtbqkjrqxe.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtolakmqyq.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtfyrgtkac.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtustordmb.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyipuvopu.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtpjqcuvjo.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtpnjtzwgc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gthzujzsvm.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtxlytvjar.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtcybbzxhr.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtrsnjdxkz.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtfvzbdbel.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtbufkobkd.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtapuoumsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtbnyiiscg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtepebgabc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtfojuaqrh.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtoumjqizb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtpyxjeavj.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtsyhzbpmi.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtqxjlxgbd.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gttniqzmch.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gteaffzjql.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlntggmp.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtwwyszhmy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtqiefrglh.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtdzafsjjf.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtwaiagswy.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtopknrhao.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtszvlujmx.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtpvsvogzl.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtkggvolta.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtoplgjmjh.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtwqdrdyxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtkivwrezc.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtutamcdxa.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gthgcpsdxs.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtlzuylkds.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchdphnyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtknqzhzer.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gttdpgmrdy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtqbaimdla.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthixomikg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtlrwodare.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtcvlffayp.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtusgakagc.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtjlenywdb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtkdxgwpsj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtrmyvqokz.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gteijdusfe.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtlpcdkkms.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtkrscksan.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxefxwfb.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtmbvuacvg.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gttqlghlbj.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtcmmmrzjq.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtuvtaaghu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggfxyfwp.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtsekartvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtnuksznpq.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtecegdiya.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtivmsbqpm.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtvnhnofqw.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gttnvtduzk.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtwzyinlxn.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtbcjfwcse.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtfhizonat.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvqinspnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtttynuytp.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtkxuxbxcy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtuvesopfp.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtrxafdngt.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtjbiopsne.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpdcskwi.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtozzfdsyk.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtmpytbxln.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtjmfnhmmu.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtuzpfjxpy.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtofnltdlt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtpyvlmbii.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtxkrmqcxu.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtqvgeilam.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gttxawuhjr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtgoknkodb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtgrefmszu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfzjormx.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtfdsazzgk.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpxzvredd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtlrksgjqk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtaqvzvqif.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtfkjgorvu.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtfbwbyqcn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtomsxowhx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtfhmlggnm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gttgnytwig.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtpgmmoauv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtppvfgbtx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtgpymcxxw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtidirrdhw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvqcnhet.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtdfygsowq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtnzdvsuzu.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtdedmduan.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtfsyufcoz.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxhadstnh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtkfyfhxhc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtldcomlkk.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtsgabzywz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtcrpygdvi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgqehhzbs.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtaftgdllf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtckycczky.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtossucgbu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtukitpkek.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtsaltkoko.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtobqulxha.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtwwihacsa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtvbovkedi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtbdpuuhvg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtlhzrmhvf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtlfdtaamb.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gttmctleus.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtfvycgmcs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtkjoewvti.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtxrothqwz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtthssukik.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gthnsfwpqm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtnglwezku.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtktfdvryg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtvfnlxsvx.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtdnhllffk.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtittoctxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtsthluvss.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtkuzcwhpy.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtaatqnkke.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtdinirdwk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gticiuyktg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtzlnklcxs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtonykdxlc.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtlbannljb.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtckhdcdpa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtetzoxwgg.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtvugqfubk.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtmsqtceuo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtuadsnhvf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtduskjxve.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtnluffccq.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtpefleyyy.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gttrcnewpt.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gteqbqjhcp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gthjnhyxft.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtpvyopcdp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtyhbrsuxb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gthbnqoako.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtycqwrjxv.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtdttqjxrm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gthqerecrp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtlwrwzthv.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtdbeykvwk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtopcqzdqm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gthsxhmlye.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtivynsupp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtccduilsi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gttrzwckmi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiykmivag.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gthqcdqhfl.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtwnqnnuao.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtjgaetwre.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtlfrnnpqw.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtkfxpcypt.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtyblaxqpa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtmfytbvco.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtknrvunvo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtwkuomcec.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtqlktpgtt.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtnmoxedle.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtvnsirfgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtxfcljmqe.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtsnwucmha.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtkvilrflt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtynumkael.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsjukqnh.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfvhpmdy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gttuznfhpo.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtwfdhftqi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtoskzrigq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtkzzcexgf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gttbfhfbhj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtxguinfeg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtganqctup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gthapipivj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtpaxetmpb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtluvftods.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtqffiaedl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtoimbjdgp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtkycbqvoa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtjefknyjc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtxbkekfbs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtjcxepmlp.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtjykegxea.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtfltzoasd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtxjgfumko.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcdiqfgfy.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtcgclcgzx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjjocmnr.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtfkkjkfnb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtnwmoosre.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtlrzwegvo.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtconrlgsx.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gttaqxjcdw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtrgwsdpyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtzwxesjfh.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtpsbzqsup.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtedkigdnm.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtzsecdbxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtjtnebeqg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrhxktuh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtvpyskhdi.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupbddydz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtvnqkjnel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtrhqlqpxa.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtxibkhiep.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtewhgsxyu.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtgpwovhmb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrwzbgdva.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtukgxdzqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpnmnkxq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgvtulpr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtodhqhenn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtjygeblhv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtlqqeptaz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gtpywkjkeh.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtiiywlezr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gtbpyxeyue.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtyzeltnwp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrgqoprk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gttliccmyv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtpdjetsrv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtomohwtpy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtetlonnfe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtxafdljpf.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtnwktwmkk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtlreondcv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtrdzmfjdn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwaslkbl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtzwuzcuza.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtsapbswyt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtkzwzctha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtiknlourg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtxotdlxyw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtntacpglw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtejrxwyey.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlrtzbit.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gteofpuuqx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtsqpcrqef.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtennrzvtb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtqahagswg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtycgrdqaf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtqrzuatmo.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtuyvmhvaj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtswgzwgpf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtcqrzkuxx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtgtwvncvm.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtbznidojh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gttdgptnwy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtahdolhmc.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtycnopjmt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfljbhmw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gterfcjipo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtqgwxtwhh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtlrzymrci.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtqabxuxmj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtzgwsxdyh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtrshhrhcf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtiaqxjcwm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtkkgrucbl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtgbikrjwc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthtishmcw.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtfrzbmwgm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtthywrtkn.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtardpbdne.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtxuqjcqvc.html


<!-- 参考信息 -->