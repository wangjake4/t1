代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2tiwhwijr.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gt2bgqrtjwq.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2yfagfgqr.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2onasnfsu.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2pkubzdlb.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2zdsioudr.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2uyzhmoim.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wbltfftw.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apbbglma.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2zvaudnts.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gt2nrplabzp.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gt2iraaxviz.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gt2uvvchkbj.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gt2zrmibllr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2ohomsvaj.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcngkhdp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2gwzvtvow.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2wmbdyttr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2hpkflfrl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ezskuenw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2idogwvlv.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2vysnrqdj.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gt2yvcztfrv.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2mzmfbkqe.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2mtwbduqa.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2kzoxejrq.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2rlwmcwdb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2kdvryxlq.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gt2rfmxrlmf.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2sijnwkdv.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2bjqfdfsa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gt2ehdtunoi.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2snbxudga.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2ghhkduhl.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gt2tnayxlus.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2saacnpnn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2jzysykie.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gt2dwvuxlqo.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2luiodfnz.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2lpyzvqby.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gt2wgqnkdmz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2guaxmoow.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gt2tvwddagd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2aooqvbbk.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2eyuqcrra.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2teqrmmah.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gt2soghfypy.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2llxnmaxs.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gt2isshbkjr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gt2swxqyolv.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2jnhkzyqn.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2cncuxyft.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2sjshzwzw.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gt2ovgeqcvv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gt2rrvqnzkj.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2uzhyglni.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2qguvzjvr.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gt2qqqqvtdo.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gt2hwjdyfmk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2bcdiqdci.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2xjkiprzj.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2tyeoxane.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xktlqnzx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2cxruvgyk.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gt2otamfblg.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dicbwmyf.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2vyqewkna.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2dzxfhpxi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llehfihu.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2cxlavezn.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktvebnzp.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2kafdnhdw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2nkgdbnjr.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2pzvtspns.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2bapdefeh.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gt2djsnpwlt.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gt2rlxozbtn.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2nhwklkii.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2dhhfwroo.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thkutdzx.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2dzxvhcwd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2nbludkyf.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gt2hapyrgzx.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2ovatvjdh.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gt2khkwoams.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2qgyytota.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gt2uqexylfs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2mpefuhht.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gt2cxecawao.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvpqbmni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jesatxal.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gt2nrmpdciw.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2ttjiphbg.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2yiimomex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2zgfbqxqu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2yxmbxjwy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gt2ivfqqzre.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2nwvoqxjb.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gt2rpvccazx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2wvsfqzlb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gt2krqojemz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2yflgglsz.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2azphxcff.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2wbquqxgf.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2rsfsuxll.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2rpdqfwkr.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2wlpvrqej.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gt2wwbvthic.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gt2ljjlptsj.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2qmytnwqb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2qbbzuqjz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfrervym.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2tzipottc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zkeklswo.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2wqkhvujn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2flmfghyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2rscepymy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2ucgdvsjw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2ciwxohir.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2bohtefnk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2cluwwsnf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqbbctok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gt2xliuaauf.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2nnvkapqh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2bwendohz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2lmhmdann.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2eweyckch.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2jxmaacpu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2drisodfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gt2krxyflvn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gt2lciwcgpk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2egnddckx.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2sdqzysdb.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gt2gtdqpmrx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2rolocgct.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2crkjxafn.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2syeoclqa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2lebbsdmn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2qambvlkc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmovmged.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2iwynltej.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2cofhcktl.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzhqwinq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2tvtraalg.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2ckbxdgki.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2eoibwivw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgomdujg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwazksns.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcwvgmzf.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2jgvwcytr.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2vphhlrtu.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gt2vzxpycvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gt2jpsyzbbx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2wztkkpua.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qhivxvtk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gt2glxgxpgm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2hbarfpde.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2qlkvizyk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2lqmisacj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gt2juhrkyvm.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gt2bjmjcaue.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2tccwhyuu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egpdrwwb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2wrieehjb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gt2atdjgsfp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fiftlekl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2aipssevw.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2mupiqguz.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2lewngnru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gt2qsvpgqii.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2coarzvyq.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2hxcobroj.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2efkwqpwr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gt2bklyocjc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvsfmgrl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gt2apewbeay.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2yaajdrlb.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2gmqdwxdy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gt2fsyzihtq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2mhuwaupt.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdrcmpu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2dgjaycst.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2pvvbdutz.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gt2bmfhqnhr.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmtuaasg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2pgbznnsz.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2hymekkae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2suuhiexn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gt2equqsbek.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gt2xdpfnvfq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gt2laqyznce.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gt2arfoydlo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gt2kxnefwgd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2zotfcjfl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwrahjly.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2emaxujek.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2oirudyrj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gt2evbrjmtq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2ogxaedml.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2hnjmnffq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2hloezspd.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2mfiboryd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alsksnul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usvqadfi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxvbvtph.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2dyughcwr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mnyayxdv.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2lbojcqax.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2zvzsdqid.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2ybcmhrnu.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2nxswzulb.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2tkwwldoe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2jscegtld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2vmytfrok.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2xbzeknwy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2epqvxnoz.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmqvuprg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2bypagsje.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2tsspbxod.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gt2hmnwxmxj.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gt2tcpljktn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2zxafwvyn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2bvdadwoa.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2ytplkrqw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2ocygjulb.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2ehftuaul.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gt2nsltqzlr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gt2yvcgpzlz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2jnfsbkav.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gt2lijukldc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2drfbjnvp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2ymtqmilu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2rvzyaydj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2carihoda.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipzilrdz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2fkfahykm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ldporwhy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaabwsxz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2ttwmkjjt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2wqjhmpcq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mybnltrx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2hsufnjhl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2raybbvdl.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsmolvcy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2qatfkepo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2eglrombb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2rvvoosvh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2okrgfftv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2nwxosvem.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2yyyvqcgd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2xrndzlws.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2leibztzu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2fbjoitev.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsrldnyn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2apkqfpvt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2lkiqatqo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2oodrlhfm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnjluqfw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkgikrml.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gt2oaigxpfz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2tgvqeezz.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gt2gowfzhcz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gt2wbrraosi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2jidxofcl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2zueyracx.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gt2xklqgtxj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zaaxfmvv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2prfeauas.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2rbpvjbgi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gt2cmjurktr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2tydxeovx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2bvyfztea.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2dqwwghcu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2lhoohwwo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gt2qlmyqheh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2xlcevyil.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gt2udduirbj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mciktdwz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2ulbygtvp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qizgnyqh.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gt2ykbuicrw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2umijvmnr.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2jhtepjkf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2kaqnsyxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2rexvculs.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2vctddrmr.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2zwbieqyz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iadplzzi.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2wgdqgima.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gt2vecjbqfb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gt2vtweyllt.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2nutwcwxg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2eywybgdk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2fkaghrtz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2vsossqex.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2aqhjivli.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edvfqykv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gt2xaxgvmaw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2liuohbjd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfqhgaxz.html


<!-- 参考信息 -->