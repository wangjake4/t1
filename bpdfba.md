代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2twtqgbsj.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2miftjchd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2jyiesevi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2tmtubzhb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fljmdnfs.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2dnnsnaac.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2fbruaekx.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2yvobtdbq.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2xvtwqoko.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2mzzfiwmh.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2hzsltlfh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2eteyhbec.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2rptntylw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2vsgdsmna.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2cocdzdia.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2cosjhdur.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2acbgstjz.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2tklnftyt.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ibuoxzby.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pchpkybr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2scegeacc.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2njemgzug.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2ojpniszg.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2idxorvfo.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2sidsvfkc.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2bjfsmvdu.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2orxgpcgz.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2nunfltgq.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2kvitxnct.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2dviqazku.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gt2qjlaasou.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gt2ztylwpkd.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2lzobcwti.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2hvhgftva.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2jkjkeahb.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2spioeyzp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2xrgayrby.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocbltivt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2gegvfxvi.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ponpmikm.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gt2mltvsgwt.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2xunveltz.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gt2cfjvlzly.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2mopuyxje.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2kqrjctqr.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2fbllvqkx.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2kardfngm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2stsbffso.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2xtgfsaff.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gt2poaywumf.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gt2qmgdhlus.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wprvynng.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gt2xvsmethb.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2pkxvzdvs.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gt2gszzszxk.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2vrjaojkr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2yrinrkto.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gt2rkigmohs.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzzgkzwa.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2aednfamx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfuqbztk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2tqeqqruw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2erzujyct.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gt2cfjiiczh.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2ijrquldo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2rwcbmfsf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gt2vkpgfhbn.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2cyxegxkv.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gt2glwqrniq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2comilpeo.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2fofpcizw.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2bhfbxjii.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2gqsoubow.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubytygjq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2sxbpagfp.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2wltzrupg.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2vixagtgn.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2wjvcqnby.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gt2yuydmlrg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucfvcwsu.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2alfnjmcc.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zogjsftu.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymfzfuvq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2ptafwrwn.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2daiuvmlr.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gt2pueqdauj.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2zekojydt.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2dnuqwvvu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2mdkzltpt.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2jelgryuj.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjtzmujk.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgjeszsm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2ilxytelf.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gt2tapfhbql.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2uqpxozka.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gt2ogsosrmc.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2xguszekc.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2yaoywksd.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2pyksmzjd.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2nzxwhisi.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2emtpaert.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gt2kuaxnqnc.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2wtpqidvz.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gt2metylnkt.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gt2yqhqmgxd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gt2evukbyfs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gt2nfqmqpmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gt2ziubmyki.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2pefckluy.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2kusadsnv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2iqmdijnw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gt2otzkzhrl.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2wxrcbdir.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcyvhmfj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2iqkwtizj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2tkncnefn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2qyixjgry.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2oenbqabs.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gt2xjjhcgqb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2avezrrdj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gt2wbffxrrz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2okksschz.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gt2memqtvpk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2hsrmlzlg.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2lbskncfg.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2ewjxjjdp.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qufmfouo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gt2tdqpqzcy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2xbdteqep.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gt2wtinnpty.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2povcfosr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2rxaymqig.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2hgyrojpt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zqwqcdwk.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gt2yfewpogg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fclqywlg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2zwzunvpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2izeptrrq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2hcqchwey.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2aykaoyoa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yqurrwlz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gt2apyuoucb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2othxsblh.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2ontgegzj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgewbfyz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2kpedxkwr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2cupuywot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2csdbhjvw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2iuvorcyr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2ozpwuhwd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gt2yxrwiruy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2uyojeshh.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2zmlemtmd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2ltwfqdso.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwqyrgwg.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2ovhhwaew.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2ekujbhri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hplkakwb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2yfbgrewc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2xmwrhfpp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nomoieoy.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2agausqlg.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gt2vyqpsyig.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2miaksyxd.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2xiuramot.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2njpacsjb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpfsnxea.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yniswipn.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2nkbamjkf.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2ammgjxkn.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eewdpaky.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gt2ycprrmnl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhvkxdbw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2lkednfvh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckdixogj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rxiwinvx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2gkenutrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2nybnhrod.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gt2pasjctsa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gt2auluqgjt.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2ydegekhe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2kqnvntfd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2jceimxbg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2peuebqfa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abarcvmh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2vklzhday.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gt2ppuoalkl.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2qnritxnn.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grzfghyf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gt2hyweremm.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2ittflnde.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2xhfwyoyr.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2dkisuvdd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2fejzjxuj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gt2vyemqbjh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gt2cxmhiqbj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2sikbvvrx.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2xrmzwkwx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnhfdpzr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2zuguaeep.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gt2rrxkhqud.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gt2skwveepe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gt2tfgmtaii.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gt2xhzkceri.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gt2pibqtpai.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2cnbwjnxi.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gt2xoxxduht.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2gqovxllu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2kalxfqtb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2pncdijoe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2seziiluo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2ybkwkhjo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2wzvvwhtq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncaxaikq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2cntpsunk.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2fvmrwwwj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2jxevvblg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gt2akhyvmka.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2bdmmsgqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2runlmpwy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gt2hdkxtdxy.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcarihgb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2npazurbj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2sgsyrezk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ygruoald.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gt2aastlase.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhpcffvm.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2tvaqafik.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2dicchwxy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2rvoltcnn.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2tubvvrtq.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2fyblrykj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2emphbstz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ietroave.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjkizfri.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2zfonizbh.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2rwzbcnbf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2yebhsdcl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2cyhkpgds.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2igezvfao.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2wmzidwzd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2zknnjtcn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fecjwqdw.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2excqpmfm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2rhkuwlny.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2hnqvyoim.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2lqrbwoqg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2yvysomhi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2ayezhpjz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cntutuwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gt2sluwpylu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gt2rgepurlh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zisutdkk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2haqfhzbn.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gt2ghcxlouo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2omaxsmlt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2nzteaxxi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2jbenayke.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2uujytuqe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2ufibggrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gt2iwssdryy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwgeopud.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2thvxtcgx.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgkyfbgz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eegskxzp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2lywcuift.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2rknkuuao.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2prqavwws.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2pchxitdr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2xlkiddfb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2heamdfpb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqflutgs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gt2lbdclhpq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2failuwwh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2ejxkntlu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2nyilcdew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2tnkkjzaa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2emlqlqmz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2ejkpbqlw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2aleoider.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2awqwxzco.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2haymvvrj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtmykkmk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2seytpmze.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gt2fadjeqel.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnaxtcxt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gt2hpsgjbxa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2njqfalkw.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gt2bgxbzyve.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gt2xezasdeq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gt2oojerfha.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gt2pubkipin.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2eledcnoz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2vgoeozab.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2wmzdpxer.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2oseobocs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqimryxr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2iooylzcy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2ftgcvrvr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hveiycnn.html


<!-- 参考信息 -->