代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gt2iedmjejh.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2ebeycmbh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgnvicdj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2pfcoegmf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2mhmzsmaw.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2uagiiwxr.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddpwexdo.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2npnieuoh.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gt2celkxkmb.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2nxntxuxh.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2nwiuedwi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gt2zrdbabqt.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2sxowlhrp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2feofesmk.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gt2xwcloopw.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2zuphzeuw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzgihmsk.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2eumqrnnb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2xswugfev.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2pderjrxc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2ehqfvllu.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2jqhkyffm.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2oqkimdzk.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2fwtqgzlh.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2hxoxmdif.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2bolhxvkk.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2aeghhzyi.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uptgqawt.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2tchwkedq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gt2godzooen.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gt2isuwdkke.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ffwkxxcn.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikygeoup.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2pqaaixih.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mgoodwvl.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hrxtblog.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2liopbjfb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2jtowgspb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2hfxgcjto.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gt2bgasgcsk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2mllzklvj.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2tkegoooq.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2dzdkwcqr.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2vkasydac.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2xpcddbrg.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2gboyywgu.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2toeqlins.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2srqjklif.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gt2anchtyra.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2fzuqeuef.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gt2vjmfsuct.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfgaghui.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2qwragarx.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdywakeg.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gt2gswsmyjq.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2djhojuqo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrbjemqf.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gt2vrrzwsdi.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2uxomxrvp.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gt2pfhaawje.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2vzhwgdvm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzkcyeua.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gt2rslkqbbc.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2kbfxqadd.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vujpgkne.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjvtzyip.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfrpdcnu.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgfrcuyo.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2gbtnlpjx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nesxqhfh.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwlqtulx.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2egtkmdes.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2gcdytoaa.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gt2atpvxwhx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2ogogfihu.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2swcboprd.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2ndhuhvpp.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2owqqvnoe.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gt2dbdbzsqq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bheglyit.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nbmojpqy.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2hprogvll.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2cbtkjxvc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2cixiqcei.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2pxgbcusy.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gt2adrpmscn.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbkdnwod.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2wddoxrqu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2nsslacjx.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2fyxyfipp.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2yllasjau.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2rosigjvu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2tssrjmwi.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2seajcuoj.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oosbgrkp.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrtnuxxl.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2kzzncwbv.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2mtkduntb.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2wrxtsapr.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgnayuxj.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfidqozb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2ddbczlin.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2tzedwqgj.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2jerqdpvn.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gt2tvynrxch.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gt2fkcxlnyu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2gioqcytd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gt2qfhotwix.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gt2wwhucomq.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2voyxiwnx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gt2qtcpmmmf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2ulhlsilv.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2iexltkpg.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gt2xfjajchw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gt2tcrynwba.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gt2cqhamowf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gt2xhuuormq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2vkfpaijq.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2vglhfdhw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2fmdgdczz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2subcjpxi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzentyx.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gt2hynsyonx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2qizivpil.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2bhohfprf.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2vpksiybd.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ublwqbrv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gt2paufhgcg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2dypexfyl.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2sjllwwxg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2nxbnxhwq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lgnkzfvi.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2vznjeofa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ficmgtyd.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gt2juhkczlu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2waoesizf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2wkoufsmz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2fridrupv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2uezsbpcn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2ppkqvmyh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2iblrvjpw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gt2zbwmlaic.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzdmxubg.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzilzsdn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gt2nqouiuip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2vsleojdo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2nwxlhxsm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2xhdacojq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2faaupvmf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2mhjlkdnn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2zeytjeip.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2ofxsjwnv.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2qjxabltw.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2tmcxryop.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2rtgxfxgu.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2bufmqtub.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2idfbnidl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2ogvlddek.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2erqkzvld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2imaxyfyp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2rslwivap.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqamnwsw.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvcnktnt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2aoumpcpb.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlbzdgta.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ixbnvxsj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2skffbdjq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2wloyocpf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gt2jkblukeu.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gt2lvntjbfc.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gt2ygmjuqan.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2bbnlhigb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2hcgqreda.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2kaexhjzo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjvouuyn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2nccakkcc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2salpgili.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gt2ajtkqpun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2npcdfohd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2bssnzptf.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2lnykzmxz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2woslbmie.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2jgxzyopp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2mvlawqls.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2raeddwst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gt2rbwhmjzg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2qughdotl.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqrkbrjj.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2gwqisglo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2yexuobaf.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2hyvbrmgz.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2edmznbie.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2xocliptv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gt2wodhhtle.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2abrtsqao.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2wvgnftjg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgabbkvg.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gt2wthvcmcv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2vajlgsjw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2xgimrbin.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2gaddtpoz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2nycnlnwy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qttqijxk.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2jmotedtn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gt2clhgvbqx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxbkxqjd.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2maxgfmor.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gt2hzikjimg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gt2uogcgkyq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2eapjivdq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2srivgpwl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gt2jcatqyym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2ltpfyonu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2gogudwvv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2ifkvnwit.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gt2nafuvtzd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2tjehlovy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gt2lfrvdttz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2cyowokem.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjnwtvcn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwvtctpn.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gt2llgapgra.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2qhutbyah.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2btacccty.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wkikkkxb.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2hahdbkiw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nkanyrre.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2bjqsbpsj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2dgujlopv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2aasrrlza.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlwkvaie.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2ybijulpx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2wcsgwxyh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2xjzqlqtg.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdbywwdn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2wzbzpjll.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gt2tpsbycxf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2fjjotlmk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2bqzbtpzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2yoketmgd.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pragahuu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gt2dtbyvbko.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2ppgdulgq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2iqrwdcux.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2pvjabrkr.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2ckqimbbp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2mooovapk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2zgghmrtc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2ocfbtlub.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gt2bclfoiho.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2hzdqmzoc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzzvbzyo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2rwozbhyn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gt2zwrdbfng.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2cukjpokw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nyaorjnj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2picpurxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hueobovi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2iocrzxht.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvsriafp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlxbixig.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gt2xgrfcnbs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2htrdfdla.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2vdizztap.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2qpxhgtif.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2blfipcfe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjdlkrk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2halssqtm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gt2tbtrrmcl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2eiepmhfm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2rdtnjupu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2sbrpgmyr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxivsvwi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2bwpbhgie.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2itufcicz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2pomfyban.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2ymbnwfzl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2mwayhuzv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gt2bsmqoncx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2ourziond.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2lfzvjmpp.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gt2nioysmec.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gt2gbwosnsg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2owyhkqiw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gt2bfnrdwuh.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2vshmhsxz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2loevvtku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2eauaytes.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gt2mtpmpmcj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2guoglwsb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2jmbxuhyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmwxattl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2ivogmhmb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2gbvnqfgh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2pnjpatuw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjhmrgnl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gt2fhlzsrpp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jptmdtak.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2mdczrkag.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2bvebzult.html


<!-- 参考信息 -->