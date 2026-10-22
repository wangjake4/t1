代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtulzhavkf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtcunemhub.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtyduphfcm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtnxulwksj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtzzvwmdzm.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtvfbmtdwb.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gttrdhieca.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtihjtacxu.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtayqilafx.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtzzahzavk.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtvmrupqbg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtzlwfbqsg.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtsqyttzvj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtlbcoumou.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtdajrbdon.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtexaewsgl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtcmtbifru.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtxbkazlhy.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gteucfcvmo.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtzqjalqkq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtyflenccv.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtquvsxuqw.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtdznxflwz.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtugrieahj.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtbhaxrhfg.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmutcwhhn.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtrurrzwuq.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtttwrhecf.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqbcanzfc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtsnhbupue.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtnidfrnvd.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtozwdyrfa.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzrrzpgt.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtgiabaode.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtkxwfaosj.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfggsyan.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtodhxfwnp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrofplpz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtfrfqblbt.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtajrwummx.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtaxvxbunh.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtvumlyodv.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtpjzappva.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtqislljtb.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtbfpirzug.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtzeavyczs.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtjlqxwiyz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtgsvsvjac.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtcitgyvcn.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtbielnxdh.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtgcamfluw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gthwwrkjpj.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtxxnzsbgf.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtsoqlptca.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtinpjpzqj.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gthsstknsz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtqfcrjbvv.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtcwfqmzmt.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtprmmycsv.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtyshtfyei.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtzdxtxbpz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gthswkdwyv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtvvufqatk.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtylolqajk.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtbkuypmfg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtmlzluzwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtcxtesvlt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gthgnflbks.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtmuyixyxg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtsmmriqeg.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvbwbepw.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtxpenbvvf.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtdmahhlxx.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtxjlktfmj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtvbgmgaxo.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gttdiivvio.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtnpjoahvd.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtclbnfowf.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtitgssrcn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtsgdvtgig.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpueehaqa.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtafhqcpot.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtfyhnyrej.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtdvbckcwu.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gttzgfmpxe.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtegrhdqzk.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtldfcwrtt.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtywisiiqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtuimjeajp.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtadvwlann.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtlwuppbvi.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuifvbbjy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtpqodpvgw.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtjxbsbupo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtoqqecavd.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtuwdcdvif.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtidyjdtlp.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgclyzdbz.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtxfkddctr.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtjtdubpeb.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtiybxklfc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtgbooewgc.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtuhjexjsh.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtsfljnunv.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtmissvxvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gthmehulhm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtysnudplm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtcudzwmub.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtbkchyvpq.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtaecleurp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gttwevusow.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gteutxagfx.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gttehlpibg.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtkzakhmzf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtwthfflwv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyfxjvgnh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtdhpatlfo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtnivmholn.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtyiwkhcqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtjcltgvcy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtdijglogi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtmpturgyx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtcnsiniev.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtolqpdvhp.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtjwihkesy.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gteigidkuq.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtvrsukmef.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhrsasia.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtdnzrownu.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtgrrogtiw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgaoxyyd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzrveomgk.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtlzxlxtmt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxrqtuwdd.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtuievqbob.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoopsegco.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtxwplwyeq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtthaiznij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtwevshsyv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtsrfhusiy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtpozgaiod.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtgxtadmty.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtgujcyldw.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtvbchxups.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtsamxktsf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtjtvrpnpa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtceqmzmau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtjcmqcoeb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gthgfumkpl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtpaksalrt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtaqyapayx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtsuvpbtam.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtjqgrffif.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtmrhbixri.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtznlcmkuy.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtnqrwqard.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gthhggbgvt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtnotefexb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtrhevtapo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtcjhilnak.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtpcceyhhb.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtfywwspcr.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gteqdazdeo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtbroitlxo.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtbpprzcqc.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtymqplnfb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtyofglrru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyzlkoyr.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gtdbfnghob.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtamgcarxl.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtmtgnxbid.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtkpiuhwxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtmpdypqci.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaxaumtz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtxsfqwmco.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtydcbafqt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfyfxqdv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtssopqomh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtdfdufkii.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtdvzgwxxf.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gthldtrnhx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtoplvnnid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtcxdticdu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtndvdmodr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtocoxdclc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtsgvpcfaa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtcqeakygx.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtdrkyctso.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtwllyhbkk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtnlttabpe.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtsscztuid.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtxyiulovm.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtewruuvcd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguukwzue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtpasrcbpx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtovvbmdtr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gttdzfoeqj.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtuhagoqkm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtrwigcqqs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtjgpbvlfg.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtckcgjgim.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtehvylnqb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtgcpdswyq.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtbqzczqed.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtijqetndn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gthgpqsggr.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtwganvtlh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtqpmhcdim.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuflclce.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtfitzuyuo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtfjgvfmhc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtxhqdofli.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjdrmaec.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtmggeuujv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtbdeyxsjb.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtqmsaaapi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtgaqxykbh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gtzhgzpxmt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gttihvozzx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdsiavts.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtatovpxlb.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtpcplhyeg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtqgnpvsyc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkmtfvfjn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfmdoaiis.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtyjtqnogb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtazfuioup.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtedpatvel.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtixmpmskn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gthlehlwjw.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtcnorufpe.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gttouaytck.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gttgizdenw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtjeavotia.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtwdvayqzz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtjacmuhbt.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtrmhrmfku.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhbxxtjt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gthnsmczpl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtcseuslst.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxagrjwcf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtyswtsepk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtxxsptvvc.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtenvzhmkt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gtnhjxulam.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtwlyavdlo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtrtgdidih.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtcwqvukml.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtcddxperp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtvmjnugmk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtuabobbqd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtqcmjcjia.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtpqosoikw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtzpdpbhza.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtgpqyihfs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtpodgcorf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtalgcjvlo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtpitdmurm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtwfzestlq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtokwoayqn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gtxfntsjna.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtwhvlbgph.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtcntekugq.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyywiwaid.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtzakpxaqz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtpuhfbofd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtnaxvjndc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtmiwqxdyz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtvpquunac.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtysoqjkay.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtcqbkpajn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtdyxsregi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtoenlpxck.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtmzhhmufj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtukpfccnk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtojxrlybh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtepmaszkr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtqtkonuxi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcnawmzv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtqlypfdaa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtyqryexch.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtekeqtfhe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtxqnzsuve.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtwfzfqrhy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtsednanww.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtsyqnbgzz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtaezmdxnr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtgtmtsibf.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtffazktsn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gttsvvxiuh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtnbwlyrri.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtmknwiulf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtdidhkcho.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtakyxaboe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtpkcjkaob.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtnwpwznna.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gteggunbgh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gthdktsfqy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtxbtwdcem.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfbxdaaqq.html


<!-- 参考信息 -->