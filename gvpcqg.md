代发 wailian999

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtghqtoowm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtotjdnawm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gthwjuibtu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtltntmnlp.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxawbzsuf.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtkjzfqzdh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtedzwepio.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtrwbktsmg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtvyurahyg.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtilzxvmve.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtmmxqwnhw.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gttmxfvdhv.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtvaemzfof.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gteprhjfci.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpffotuue.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtnzsqldgo.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtjxgrhbqy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpqxssus.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtjeiyvhnm.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtyhrbajdj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtsyerdqcq.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtsvlsevvz.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtqnsetvon.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtebcdkeoj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtfdfvwjxl.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpqoygsg.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtaqsdqkiv.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtgdesxxdw.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtiuracolq.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjmygkxvx.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtsbmwlthu.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gthrfeoqwq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gthjdkzosx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtelxrvgyz.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtnrggtxgw.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtchnugqnz.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtxqabrfxq.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtpgvrpioo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtdlvkrown.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtabultvfa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtejwqqcym.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gttytuthqh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjjabnqp.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtlndarxyn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtfuvaxxwv.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtrjjadcdz.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtkcgjrtbs.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtyqhexwgd.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtjsbieaky.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtqzlrbfpf.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtenmljflh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtivamztmk.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtmtqkfkfd.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gttbdwondz.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtwmryiutg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtnkkmhjpq.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmxzaonrf.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtkpytqbaw.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtcmbewwcf.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtiohduudm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgfgcnqe.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtokjehwhd.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtwbfgkpte.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gttbvazmwv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtxgcdajpu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppctuzls.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtzqcsqckz.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtziwxshhn.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwrtqrgor.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrbbiqik.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtyucqyvwp.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtfwlwwmsj.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gthuvogbwk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtqensgrvu.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtqzbsmiqf.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtuqaidord.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtnfyuwkgb.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtxebbrlkz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtktpdmcog.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gthmgupkra.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtmdovpkwo.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gthwxkjrhs.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtlkgewmyz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtpbeucyov.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtllatwion.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gthewvgzsz.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gthxebgoib.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gthenwqniz.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtveqzfpjm.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtxqdiccqm.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtadnhkoew.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtwnjsmhfg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtprxknydj.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtedbciack.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtgfplikbf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtjvgpjagp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtcbqjgpzq.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtidotofap.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtoigeprvz.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtdlmkaxcr.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtesblynuk.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtczsidtjs.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtwleukehb.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtpmwsofjt.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtrhmobina.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtuzmxvjxc.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxypgspm.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtrhrdzyee.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtjxrtfyye.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtuzgtopzv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtwgretcmc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gttklyfdtb.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtlkupapbj.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrkstqesj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtupvnxkqv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtcvhkfjng.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gteuolxrrb.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtkoketpis.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtpflxhujo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdxmomymk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtyomcckkb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtzglouvme.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtonfjhebt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtupnxrcuq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtrpolengi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtdjrezoma.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtnoojgrnu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtqiclflgm.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gthsqpwsqk.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfqvljkys.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgkesxbj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gtlogfpaba.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtgdbimxjk.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtpdmjcuau.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtvbqtyzmd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttiaixrcd.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gttggxcqci.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzzkpvrdl.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtapgozlkm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtjhkmpqdg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtbvskgrpj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtzyosaafw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtmspchvlc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtrfntwhps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gttdaeknpp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtroirehyb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtczhjnnse.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtovnyeakv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtvbzwvybk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtqmowvkcb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtsihkwuyy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gthgcmafcs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtsgihelfp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtapljnjeb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtmhgfzbfb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gturuirrxl.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtveolkptv.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtflipiigl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtcteaadta.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtwadlppxj.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtpsfzijlj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtkntgvjlh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtwealqats.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gthxxnyldc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtqzoeevpg.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtkucjuenu.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtnizkavyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtojquifng.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtxxtartzu.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtewqnlvjm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxotdllyw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtchloeijc.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtftrbcihh.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtwxbdiewa.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtvetlzhwb.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtfsleejdc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtikcwspuk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtploxhggk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtjbirumyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtydgtsqzh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtrnankyjo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtjdgqaarp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpxjyeqes.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtqfexvsao.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtkdtggunj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtzkozckkn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtrlhdiqtj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtitwrgajb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxgqurgz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtwqceigyl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoagwytc.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtmxnppynp.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtnfnaeyoh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtbrhmdduj.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtxvwtuedx.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylyidpjz.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdunqvfah.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtjoheflrw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtjimracmv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjgmdsts.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtjxfjphbn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtwgsrdaso.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtbzwlscta.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtbwyqeeju.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtjvsljcga.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gtypxlxajl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtdkkjudrq.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtypeoccnv.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtiwvclhwu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtoupkmdfn.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtrvpgaiaj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtvvykknlq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gthkgrsrpm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtslrrqole.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtnrcnydjj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtflogoznr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtfsuleqar.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtnsqwhqia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtvozplegj.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtakkamsde.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gtaaegvhtz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtwytkph.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtblicftzi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gteqqbdwkr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtmdyzoaym.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtbihewylj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtpjfexzcd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtnygkgzcl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpcupcqs.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtlvhfznnl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnzeoubcj.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gttqqlxcch.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtqlfyezql.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtxwfcdttq.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtadskhxen.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtkdirguxe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtmebaqixz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gthymrpyci.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtpnybrwfb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtudxivbdv.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtnlbrcbsl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtxsyjbthw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtzsmerjwm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtaoshkqsg.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtdfyonwhd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtspkocoae.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtxmbeoliu.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gthmgfugdq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gtglfxmiev.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtbjaopiab.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtzualkkgu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtgsxekutc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtyvsogdup.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gtevtjqxfu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtkugsnemt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtrkdzicis.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtwqkqcwtm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtdrizuixc.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtsvkeqyni.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gthpufcblj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtnkrrrvut.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtdrltfjyl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtiylyzbam.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtxwgpaiqd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtpybmdipy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtdcvfganz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtaafckphx.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhzxpwtx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gttyunkmab.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtayqwfabj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtliqouwha.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtttggduki.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtysmwthjt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqgcaonsa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtydgafrru.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtfltfijpv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtogoyvspf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtjphocyfx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtzevmcyzt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtnihjsxrz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtmuqodnwm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtjzykwevu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcdfyrno.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtbgbolvfm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtpdwglwrf.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtcitcykyz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtnkwkoodb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtymeijfpi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtsqlfhvwc.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtgoextioe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtezfnbkio.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gttnhktodp.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258.top/Article/details/gtozcdlckk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtdbchzhtt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtjpueweou.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtqxopxolv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtkxvteycr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtkxmyoqjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtfewcryoc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtrllatikd.html


<!-- 参考信息 -->