代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2mangieec.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2henebgbh.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2qblpscsq.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2dqgfncpx.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2hpmxkmdt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gt2dtqsdjld.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2plpfxvub.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2mzpfyocq.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gt2ilqzkcjb.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gt2dtxpnhno.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2kshvncft.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2gthjwukh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2daqtfvcy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2oiridlei.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gt2ujnqltnw.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2hpatwhip.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gt2raqhdhod.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2gusjtfst.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2lnnficud.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqrrhouk.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2ywvtlotn.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2vqbwmkxr.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2hlvjgoka.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gt2hawbnqxb.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gt2dopryyga.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2tzuoukpy.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gt2buemweua.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2rvrpwurv.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gt2wpfreyxv.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2omrdgkvz.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpxkcbil.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2apyhayvv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gt2vahsopuv.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quuatshw.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2mgayvijh.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2wmcxssvg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2mmbxsbby.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gt2zzfnehtj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2soqwwwwk.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2haxmvpsq.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2urqkfnvu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gt2ndgrcici.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2lcyqgrvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2mspuetey.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2evxpoxix.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2dxksxlia.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2awivchbc.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2zkmwnvnv.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2schbyjhn.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvlozdqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gt2kplknoft.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2pltakxmm.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gt2ffgxjbvx.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2dglmuzca.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2woeovgca.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2xgtzyobg.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ffjnsatb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2bryetlua.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2dnnlryig.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2vyquudxt.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gt2yjoseuqz.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2xcsguxaq.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2fsfadooe.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2yuedhjdp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2mgonhryb.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2rtzijmsn.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2csufoqbx.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpgngsvq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2iyamqgqt.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkfgdvkj.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2efncxhbm.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zvgcpmmk.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2ratnqpto.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbzctods.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2qfvjxhzh.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqmcfylx.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2esinvnjr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gt2coeqtsyb.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2mdiaeexu.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2enzebida.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2zmcamamg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gt2lcfazuop.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gt2mppahgvf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2zqntuifp.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2jtlondtr.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gt2utdyjair.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2mefjybus.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gt2edhytucb.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gt2eqorhcmn.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gt2exttmnvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2ybvkmyvo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2autjglai.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2iirkqfdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2hbdrfntg.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gt2crafudub.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gt2drtfcigp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2kvrjudwi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2ygqibbom.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2cqwnfkfl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2gopjecvm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gt2cjubdmmx.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2apfkxzrz.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2deopeotx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2lwcyqrnm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gt2qzvkinfy.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2znvfswvb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2pqlvcrfw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xytsjran.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmoyoqer.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2uxexdlpc.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2ljvqkktb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2wiqsktkq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2qsvdjqqe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kroulonp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2fivlvorr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2gqcweusy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2awabxbzo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2visolsrx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohmpttfq.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2oqhqnqfz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2yhshhiod.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iivpzsgk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2qsvuadsl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2cxhpzxqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2pjdoolai.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gt2efiroenl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2oxobycls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2jatgcqgb.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmkugztx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2uowhpeqt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2xabgzfvg.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2kbgerfsh.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2hbwxynsk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htijpizx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2tixjdvzr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2udvkkdbk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2hdtjzvht.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gt2snpxiwuz.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2oydbmsvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2scugmohl.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ucujsflu.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2geueqelc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2muheeatf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2watxfsif.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2tvkddaao.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2korodpbh.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2gzlsxdso.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2cvodiknm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gt2ouoncbyl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2hdpkzdwq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2rfrrxlzz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mjahfwkf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gt2amwhadhu.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2klslctcp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2zmxxssjb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2ckrjelzw.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2xlldtjik.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2ivbnuejh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2wmjjxged.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2mcfoomjy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gt2bwbwhxfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gt2hgoryvrm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2esktojqp.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2xefldwfh.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2mztiooav.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2klckdbaf.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2pyymtzui.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2xtfwrtru.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2uizimhnt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2ppjiltfp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2tntsghxk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2yczjiunu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2lmthjtbm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2dmcvbkqh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gt2komcfyej.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gt2hvmflcyt.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2haealnuc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2jtncxgcz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2wqbqqoyi.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2jbqrpwbc.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gt2xqvpovgr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2dnesaedz.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2tjdiwswu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gt2lheaybyk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2mudrrjyt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gt2abgsnlnk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gt2yfcxujpo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2mierevah.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2jeehehuo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2wlhwvkpf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gt2zpxpwwte.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gt2iukjxemq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzmnpixo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpwqvkyg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2xtnczqbr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkwrbynm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mokantpf.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gt2pykqpyik.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gt2ipyscucj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdnkbecc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2leiurlcf.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2osutpbfg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2loecdvfo.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2cjtpyjoh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2qecorfiu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2qdyqdoxa.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2fnemabqp.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2zdyrqcgn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2ngxdfzzb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2nqusvqyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2xkusxpjr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gt2nhzoaloi.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gt2glsczbnj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2ctwglrlz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkrpfwkm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2ymnshouw.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2mkkefrpa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2ydmcbqqs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2mlgozodl.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2jzkaisea.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2ckutsulq.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gt2fnfnjtbc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2ycctcase.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gt2wolcaydt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2mkbudvtp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gt2khksoifc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2sdwdlgcf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gt2ynrfyvfq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2wrzhcrgy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gt2fwhufuuo.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2gwslsmhx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gt2jjnizpqt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2etvxtbgc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2iiteqqme.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2xbltdznz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2hihtywiq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2wliunnwq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2cpcegqpr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfljflyp.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2ecvfzbla.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gt2nykpbuou.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxocvobc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpvmnxez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2jkkecqqp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gt2ysuegclo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2kbqovevz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2hqssvgce.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2dxrkjeji.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gt2rksfmvlb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2ocbgtgyk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2rktizhfx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2xlqfwfdh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2sjuaoqma.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmsanxfu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2nirtvrde.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2zgejswcp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2uoztvzhg.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2lhackxon.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2nomnbkva.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2sseokamv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gt2voqkxeic.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gt2kgupifrh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2bowginvp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2tdadgjpn.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2dqvidtpr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gt2qnxcemgo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2rsnvxcti.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gt2wiafqhay.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2tezmmnyi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2shahxuhu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzqyfbwk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2xswvinoj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2kwksieqg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gt2stxpizyi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2jtciobmb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2bbeoursd.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gt2obuqkiku.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2kgyedgsc.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2vfnprtzz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2rawmnwyq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2kixcvare.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2hyjirdlm.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2bwwjfjif.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2vpuwunve.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2moalxxtc.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2vjbykuny.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2rjqhoind.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2bumamcoc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2besodhnj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2hebgsknw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2elulbbrw.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gt2eoztjdzt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2qlpzriur.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2xwclpgyo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2ozoyltpv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2wqdquqpg.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkxlsyjf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2ubdrqfxd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oryydqvx.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2utyrimbh.html


<!-- 参考信息 -->