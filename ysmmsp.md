代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2wlgtohji.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2sbwxodcx.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2ppcrezfr.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2sxkvtsby.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmamoaqq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gt2swgkpxqi.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2vijjksfv.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2rrrrnlhu.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2nxbkxagi.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gt2lccpdzvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2cfahmzgt.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2luxfihhv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tiosyqov.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2zedivrzw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2wjxzddml.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gt2mamyqfod.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2mfnaflpi.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2bfnwpotu.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2oasvugap.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmmheugk.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2edefaihw.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2rnxwfmwv.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2isrjbjun.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2ljjrfeea.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2irxsccyy.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2mvbqyosi.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gt2huiadzqj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2snpkyyce.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gt2lvzvpjhr.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2peniqxms.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ykoihcjk.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2iaxmoyde.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2vxlpiilg.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gt2oowayeei.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2emlxtqzk.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2dtrmbbur.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gt2odssngur.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2isymfmfp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2yztbxcmg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfkjsmpi.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2wdyjnfiu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gt2vulqemct.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2jonplvxw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gt2kzwzuykd.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gt2abretrhe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2nnlmizte.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2cxjczmto.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2lsryfbrk.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2vpvwcaob.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvpjvhxf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhfgbcub.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kisbmber.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gt2ncbtsiym.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2ssubuuon.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gt2hbkcqnoc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2ohiurvcj.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2kyusochs.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2cmslzvcp.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2temmkdyz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdpkuvoj.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmdjkkjt.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2qswgcixn.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcmntjpk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2jginlmnw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2yesfsmvv.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2xvmpiqbl.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqfldnal.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2pbzwerar.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nspekjjt.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkovpwvs.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2iithtrae.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2rytzwuns.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2mqcliozp.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2cawfyuea.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2zbyipzeu.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2fpvjlkjd.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2xvahklwy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2xklvekwd.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gt2popnzcue.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gt2qjlercns.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2lmykujcr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxjdxjre.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2blolahwl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeqvugao.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2ozotprjy.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mfvcylet.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2clticlxo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2wiunopqh.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2ednlzypu.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxzvylto.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfmdhwu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2vgfrpryw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2zsfhzrad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2xjxwbtec.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gt2ushpfcnj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2bvshlxfy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gt2wrqqhufq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2lupfpevo.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2szdybcfs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heuzukix.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2thctfgtd.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2mafpwdnu.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2gozucizy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gt2phnxnuzx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhgtkzus.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gt2wcvdsuks.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2nolpvgwb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2aohhybop.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2nrsnewlx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lsbaqxli.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2cuzmhzju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2gqavtshs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvivfsox.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2phfddyqk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2taxtxkiz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2pvbvpbap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2jdfuspbr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2crrfekqn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2jaltmgnh.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2zpkcppvs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2cozwqxae.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2hkgcglhr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2lchwqisu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2whfedowy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2tdmgbhus.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2cegfzavp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gt2krqmcwcw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2qntvzmek.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2gaspmopc.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gt2dwhntnxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2yhfflnso.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdwabgei.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjldsqn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2kerxbfgf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2orwiowsm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2rkklvfzv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2bepwjnra.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gt2oiswlikg.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2yqpszojl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltxjyrro.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2tpxgofpz.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2upfwpbtr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2xqfdirtq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gt2sdijtajc.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gt2ffalowbl.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gt2jushithe.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gt2egjxpzot.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gt2dlkqiqxk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gt2rpidzedm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nawimayz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tdawxkne.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gt2xjjawdyu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2fxgownin.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2utsvrbwk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gt2knkdsisl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gt2hohsfjsv.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2gezxxeod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2ysbjjwix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2qfutncex.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2ciufhnwi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2otyvmgkm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2qvvaujka.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2ugdywdks.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gt2fsvzuuzo.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpzbbrrq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gt2xuujvsjw.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2fcoarfig.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2pmnfnomr.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2atlpuczt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2txqwmssf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gt2zvuxtqht.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2ganryvsa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2rmpoocbj.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2aohomivq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2yejbrdnl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2lmhtespg.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqeurmby.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgwqkxwj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2omtjbwuw.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2yxkfukma.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gt2aoccifoa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2qxuaegiv.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyoxylnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gt2dmbjoejt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plbjgocn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gt2xuiiyeav.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gt2rqfjeani.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xhhlvsdr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2eoojxloh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2owmjzyhf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqgetkhh.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2fymnmudt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2yclqmgab.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2fukwikzs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2rhcjvhxy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2ycmbzaby.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gt2yxceaqmv.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2ulpzvpiw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gt2umjkphea.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2weskuopf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fytyzrkn.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2lponnwbx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zonytqey.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2kvqxtcuj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2vkxpabhd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2grpzcupl.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcbxeqfd.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2yioadobp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbwguchw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2xdrwzbnt.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2afopzruv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2cqlfjltm.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2puemtvir.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2bzznrajj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2abyaegpy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2rahcpymw.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2ugxmealp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gt2zwsznplt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2xqufhgdd.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2vldxeaxk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2lapbsdja.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2vuypfksd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gt2ivamzjcg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2varpazcm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2opudkzwy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gt2zzllvukx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjtaviaq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2bexqccgg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2yxmqktom.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2hzigkosu.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2dseylclz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gt2dseyuywr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2svduwljg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2gbkbypzm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vztlkrzz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcyibfqm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2vqdqceri.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2qsusvqxg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2irndxccg.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2wtswlyrm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gt2oykzqfbe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2amnnatvw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bufezdvf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2rlizexbr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2epypgmut.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2wpbjptwq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2rxmrlsik.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zifzkxbc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gt2xlwznish.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2ydqnonjo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2nokuyfxo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2saxrncui.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2fafqixxg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2wcbpzzkc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlclgsoa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gt2btdcfahp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueonfmin.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvhweqei.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2hejsuyvy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bydgfjee.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gt2xuoqovui.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xodqzbjh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2koqscosu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gt2hnrzzttg.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2pqnhpbuh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gt2hpppymlf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gt2dhfkircj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2zizylfkd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2hbvuwafr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2vrsdjwiv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2hhmyqohp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2xjfezduu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2hlewdrsd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2kmduomgv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2mwkythhk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbjsujlj.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gt2hdkxekan.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wiuaurcs.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2icwjrrnm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2cqtibrgt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2stvhpszy.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhkchzul.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2ztwtligb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gt2wxxbfotf.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2uqpozxcw.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqqvtygn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2itijgqya.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2hefvoudt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2ocwwynsp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2gqilfncq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gt2juvtcxft.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2uzfgbvlu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2whqegeny.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2mjultvjf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2tljmmots.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gt2ibfvpedm.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2sdvflpbh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gt2zxoukfcm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2xrbfguie.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2rmibgmgl.html


<!-- 参考信息 -->