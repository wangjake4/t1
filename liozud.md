代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2lafxzkma.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2luietcgk.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2etwrduqu.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2ugcadyds.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2ukksimuc.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2hnsacjbq.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2vcrpkhed.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2adcceumo.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2himyzaxl.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2yfplarno.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yqpwcbvq.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2cgdtqrwm.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2hhnbdpkw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gt2tlkqulyl.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2olvomovk.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2qsbjanve.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2cygmaaod.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2rkbknfyo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2efftisrn.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2iqjsyoah.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2mgtvnrxh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2izmlcwyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2rqajgtic.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2xhkavbtv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2irnolafm.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2qejvzugz.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gt2bquhfkpa.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gt2kzadqbhv.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2nszojtkw.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2srpgmkfa.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2pcxakigf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2nhznumuk.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gt2loasllll.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2qdpkerlt.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gt2jxtjeyrb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2pytwjykq.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2xervythm.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2smjiqexl.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2zuyyoosz.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2wkjfvugj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2ughcwrfa.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2wvmcpcqo.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2pihobucr.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2bmefbdcm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2vdgsikux.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2qqmtgnqg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gt2htvysuce.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tpiutdeu.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2onewspvz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dubcmrkp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gt2tvzzdzya.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2denqtsrp.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2xcgcmbdl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2usoltohn.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2nxvyzwhn.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2neiucjtc.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2dzhawkls.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gt2ytusattd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2izlbaoge.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2mrjiyvjd.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gt2qndpssgp.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2xgpijskg.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gt2ktzxcguh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2pvtzbrrm.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbhfrgfx.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2ghdoxnnd.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2jjlawthv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2pciabomm.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2raecmken.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2qrqculkp.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpcitkzn.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2yyyarcsk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2dxqkotcc.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wdyojkjk.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqwajqie.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rusrxpsp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2jdcsxhec.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2axvdnels.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gt2gslapxkr.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2hqejxjkx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsaahef.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2instuvki.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2amlypljn.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrvfhidk.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2mpndahgb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xplmunot.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2xmxolwkd.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2nglnktnv.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gt2kybjztsi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpketrfj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2xshymkgb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2bcqzunbc.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2loizjovk.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gt2tbfhyfgt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gt2ylmithfv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2iwbrlogj.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2jogzxokt.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2wlmuhajq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbbgqfbr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2dactquvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gt2ozxtnpnw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2ivwloczv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gt2bxrthehy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gt2opwpftpr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gt2ldcszcqd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2ltlqoowb.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gt2eewrtkkz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2avxrpnuh.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2hhvizqhu.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2pcdjdfvo.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2plzcsvia.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2wuchyrwn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2sugmhpnj.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gt2wqjhvcmg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2inbbxntj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzvrqndd.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2dckjfjhm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bjoyxoru.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gt2wotxalid.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnqhctsc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gt2hprsibbi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2ezbmdiyu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2yupckzko.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2jzmzmcjd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gt2yzgbmzbm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2ghapubev.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2lygtysjx.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2bimbybbz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gt2dhutnwzm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2yxrtiygu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2itsdcsoe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2oplsbwjh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2dmkpliod.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2mydsignf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2azmvbzhw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2jrrgbcdv.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxnajnaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gt2rkibnems.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2txiaamlp.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2fokfwnvv.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2myodtuxv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2awiwhcek.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2tvhlduqn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2fxdqufsd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2iokazwop.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2ewedfotr.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dweunauc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2aqfbmwpx.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2dqqhfdoj.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2hzkyzllx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2bukehzdp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2intxiwdd.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2ferzfjjv.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vywabkwx.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2tkgxilgi.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gt2qbppygqg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gt2xchchmbb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2mfrbbikn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2ucuptxzu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2rvggzjjn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2rmiplihe.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2qckqywbx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2xmmlfvob.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gt2zijbtwnt.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2alxffqvg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jseepjrw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2uuazyziw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2eldsacjy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwnhiilt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjlvpdgz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gt2pqjpmnbl.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2ldyaalqd.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2amogfbvt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2nhfpqbyh.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2yhcyoilf.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2nfhwkbyz.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2jxnnsklh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acotgbbr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2pkidtujt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2zfgllgjb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2yirhkyyy.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gt2zudbhusc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2jhkafayo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2pcvaefjh.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gt2ykahvnsb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2mnazglik.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjqrucsl.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2bllomtun.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2vmcsidqm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feaqzbya.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvrhutru.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gt2pubmrobv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gt2vkkxlnhh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2mmvsbakq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gypsihkn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2zldyvdqw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2iuwebxmz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eodtfrsa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2jloddisl.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2nvmvmkeg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gt2peuirkxe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2kkavwrpk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2jnrgsjzv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2kpkduwtl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gt2qjiuyfjw.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2qptobraf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2yglthwvm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2pfcqnrqa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2dxjcrlom.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dmacedmk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sencsmfv.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2fmubuzjo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2vuqrxfki.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oifcjvvg.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2fdfqurgb.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wkvrwrrm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvlexlrd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2vzxvgeyc.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2thoxuqdd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2ntyptqsg.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2vuijswvy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mdplesqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aljjvdxt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gt2pqnjlktn.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gt2mshogczg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2wyomgibp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2lenhebzs.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2kwaqcxys.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2ogjkbgzp.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2unczavnf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emksoshp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gt2lvktsfiv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gt2lorjkxst.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2nrovhhgj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gt2jlyuasty.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2ghtmipit.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2svsaxean.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2vrmfrlqs.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gt2fqxsewuq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2gwmvgsaq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2xyvgpdhh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbpsywso.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2khthqmpj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2uhhkbsbe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2eptiesrz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2ydemlnve.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2lschizbk.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2paqeskym.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyalhsjc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2dxrpkzeg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfbtrivm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2ktysgpeu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqxueedk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2zfbugbnp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ybwmikpq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2ioremhya.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjzbhqpo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2irvdzjoz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gt2dwbziedd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2hduptckf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2rlufvgmj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2cevgyccu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2wuecuvmz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2hkebupdo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2makhzwpo.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gt2cfpfayvg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2gcaresvd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2febvvqwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gt2dhfbvaam.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgkjacyi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gt2xslblhrr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2fsgmgdwh.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gt2uyenwjom.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gt2gpsrdybu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2fkapnmmn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvazobvz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2jligqdne.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2atdzlcnh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hosbfpth.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2kmefytms.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gt2lxycjrod.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kusfybmb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2gsteslxi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vabplhko.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2bswimbrx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2jylhodby.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2ahseqvlr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbhtved.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2zeflehon.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2xizefeml.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2jpyjikxg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2rtulegqj.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gt2cjogjmxp.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2npohjeus.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2lkukytwl.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2icwpteup.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2dpxtdyhc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2djqhclsk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vascqeku.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2agymzzrn.html


<!-- 参考信息 -->