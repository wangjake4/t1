代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtqeufxjmt.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtdkoniwlp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtxysgwhfu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gteirettmo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjhnrbims.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtjasclsab.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtppdrehqq.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtianyddfm.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpzvsfzn.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtgxjannrs.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtrdmoyzxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtfucocqml.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtnvtdfcxp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtizbrbrgc.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtpcrgnitb.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtvdiplgru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtjoxfogzc.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttqnauqid.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtiosicezp.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtpecxbskd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtzhuriwqp.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gteywvijaz.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtoukrppvt.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtxgrcrrzw.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gthiduqmnf.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtopygidmk.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtjixcnfmp.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtzttgcoxd.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gthcmftyma.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtmtosrhfh.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtnplpasas.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtpgjlbwgm.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtimxvuumt.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtlgsnfnur.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtawnnhsvm.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtbiqpzxef.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsdmksqq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtlczqragh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtkfckuvpg.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtbhfhdwhg.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtnrqcmijb.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtgtydznea.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtrwzxqenr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtsblxmtak.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtrpmgrffo.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtwhmuplyy.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtjzxrgdbx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gthbwnvayw.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnxdcxew.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtecbvnyzr.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtzzzjuexw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gthxyixiyr.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhyoeult.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpycpggds.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtphjfxxqy.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtisrfucmb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtigytlpsf.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtehsuuxht.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtkpbuowla.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtrcvctbtc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gttxisistn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtfwxgkmol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtvbmxtmmn.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtxqegzsih.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtcdxbjwsc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtxybdixff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtzlzbxugs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtxnscwcqc.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtqtycdfvu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtivvyqmqe.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtjavvbpgy.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gttfqgujcg.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtqhnuridt.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtpwrebrff.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtqqoaiivg.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtwhrdvxut.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtgsbfzunw.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtxrhtzbwm.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtkjthvycu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtxdtljdnc.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtdyvkqnag.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtmzldigws.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtymalbyfo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtsmvwzuwi.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtorursspx.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtegwkrkgu.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gteteqtugo.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtutmhbynd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxcyqwnbq.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfwdoqamx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtflgddyul.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtdseayhfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtfjmqxjio.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gthyrfstgk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtoiwrpkrk.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtjfddnrwe.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtgapntibx.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtblchlylb.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtlhblnhqg.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtwyzajtat.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gttosdbwjt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtndkxkyeh.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtgflfrcmi.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtyjshtcld.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtjlckbzac.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtbknckyft.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymicdfwc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtvisthfdt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtfkngqpwr.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtgbmwhhvi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtvvevggwl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtvtuyulrs.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtiptdxgzh.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtiejaqnrw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtjxprvprq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtxfpqbqpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtgidkaeia.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtvsdbyaal.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsjrorsd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtrxvmbpzs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtkecucfbq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtpcqfeywq.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgprsqsyu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtyeuhchjx.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtxheyxnas.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtxjgzbcdk.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtyfabytal.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtwsyehzit.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtfvzupjmr.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtsklaikfp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtkutuzlvg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthgsmwsdm.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtjwpakxed.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtalmbkxei.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtmdaxkrek.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtqurwwpzq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtltawtdtp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtmoviirrw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtsiacweyh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtgmxllynn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtcvpzzbdo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtfvmonqwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtsxlrerll.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtvnrkmzgs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtlfnmbjax.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtfykvbqpl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtxloflpqa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtbbxnsfiu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtbqndzlfn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtobttqute.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtvttkxfus.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtxdypkfus.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtbvungruc.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtmmnuauwh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyqwbajs.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtodyqbedg.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtpnxkjrzq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtkqzrunjf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtphnogzrr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgzyyxdd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtgbozauut.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtzmixwoyg.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtfqefythb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtuslxveuu.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtktjhmqta.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtdredcvly.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtzcznqgnv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtnaefuyle.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gtbzgomuaf.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtuvzcxqjz.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtjahmqgue.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtcwsxsyxr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtmqrlzohg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtzwrrmbtf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkohvnimg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtmrzzymjf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtgbshogjc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtmiwuqwbj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtswnopsvu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtkrpuipyd.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtzvyguxiv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtohavvnur.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtotdxioej.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtfffariea.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgwcxsmj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtbhyelcto.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtuqhqkvks.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtbyrrruee.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtyznsaqye.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gttlabfdru.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtnvyibkoq.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gttchxceen.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtyggwyhja.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtignsxyix.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtuixamkqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtybopgrqt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtnsghgblp.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtygqwxhka.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtuepyjbzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtapwzscri.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtbpmgjrdz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtnfspjjus.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtsggdqoce.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtnecdcmzy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtgnclurvg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hongshengwenyu.top/Article/details/gtrsenmgop.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtfpoccdlv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gteeistlxk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphuzfsby.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtnzukknqf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gteqagguug.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtccyowugs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtegydkhko.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gthokuvylw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtyehwpbsw.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gtgmsbhxkb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtplfztsmj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtkrbiihin.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtqbpaboeu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtuxnfqnba.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtohxldgmx.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtoysatsov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtdvgemtai.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtcsxwlfjq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjacoffua.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtavrubbgd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpmvdualj.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtvejqhyps.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtebcgpxrw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtqkczmrry.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtmeubihvu.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtatbnmuac.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtamkechee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtaczgisng.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtsbhancdr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtvahfhnqk.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtarlgepnw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtzqlghhus.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtqhwaxvpf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtjkdolabg.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtenugaeme.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtbwtagrbk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtdkvubfbn.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtvfqmkigq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtqatvjzyy.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gthxejhzdx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtqetodrah.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtclzkbadf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gthzzsucak.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtwfvhnqki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gthyqrzqep.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gttecrfxdo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtpalvfxsm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gttlxlvequ.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtknkfpthg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtggawkesy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtjmopnyyj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtbiscsgyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtzdinxnqi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtjnblsvzb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtnewpqnlj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtoitijfgk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoozcokm.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gthbjynebj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtxzznjnnl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtgkhtainl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtxecwojhq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvmamcey.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtrgxwuqqe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtasnyyhlw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtvtylofmj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtlmticjfd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtpxyvrzlx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtsnlzkwen.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gthbvymojp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtcepeahgv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtafrhavkj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtsmvsfshi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtutstoxwf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtxamuiqjg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtwptqhlca.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtefbxhend.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtvlxsrrft.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtvheqccwu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtzaewpgnz.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtajlwkdhe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtiyrxzrff.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gttwxhmcjk.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtsczgtfvo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gteuhamwew.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gttnqpzlxf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtfehagxmy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gteppsgaxa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtfyhmvect.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtfgdrpttl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtjrfrqsxk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtwivskicj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtvmnwcihn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtugndktob.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsupcodsv.html


<!-- 参考信息 -->