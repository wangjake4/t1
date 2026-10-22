代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2uvuizvpu.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2hcflsgfc.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2mktwjwtj.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2tnfgdofv.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2ocfftvyr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gt2rpipanci.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2cxpfkqsy.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2yrsgmlag.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2cecejjea.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2vhrreety.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cocwjvwz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jgundfqs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2zasanwao.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2vodwpvuv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvznlyui.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gt2winerjbk.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2tlrngjia.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2amwbvkqj.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gt2gbfrkypz.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2ekyiynkz.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2idrvcamb.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2wbnzqnpw.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2ljgwqzpb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gt2uwmnaggm.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2qwvqpzia.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2agqrtnyy.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gt2zwuwmkzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2aukkejug.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmjeewvs.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2bieyffoz.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2jhstgmud.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2ibtbhsrk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2cgmnoqcq.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2ufqyeykm.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2mhpstzqt.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gt2xvfjdwml.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gt2dqszzpfc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wwsntonj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gt2cgszcwmb.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2wraecwzy.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2tehuoemg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2hxiilwwq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gt2rngzbzjf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ubzmqtaa.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljdxtueh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2ngstsqtu.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2ohajobtq.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gt2dzvtjbxb.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2gprxsoyo.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkbugssd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2daefowpv.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2lvmppxak.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2ffgbcyhq.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhoqaioh.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gt2rqnussmx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ijnebcsl.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2ykuawiuf.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2txklwwlh.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2crrozcqx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2turcepeq.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2tbxlhkvg.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zsiugeba.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2iqxxaabe.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2goccrpva.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lrrcpefm.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2mnrplulc.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2wtmfemnt.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2bxxoddvn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2rscrwjbz.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2iupamhkk.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2igzhpsse.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnwnesks.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2ohgcbfyq.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2trftdimv.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2gblznfeu.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2qjranqen.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2cmymvteg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2qolgrzat.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muxmeuda.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gt2tcutvftf.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2kxwfvfus.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2suviosev.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2qbwiclaj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gt2fnyreixs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gt2zafkydkb.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gt2cpblwgml.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gt2jmhwooac.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gt2ojcmnkho.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2qmcqjmzg.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2bocjfpoj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gt2svjsygow.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gt2qskakehd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gt2zoohvrbd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2ubadmyup.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zivpiycm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2ixccmnwi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2yruxlyav.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgqybecg.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2hrrsiaku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gt2fwlxdgjj.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2couqwvix.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzqaoboe.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpiyqqrg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gt2lnmynglp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2jmwwruol.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gt2fadvpmsl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2jvlypzvp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuzfqlka.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2dilbxfvw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fidflpbg.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2ayaujkdk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2hgvjaoce.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2duomhfpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2oomuiyfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2atlulmdv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2uswsgwoe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2jcbkszxz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gt2ftyygwxa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kldpsvjk.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gt2ylebsiat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2xeejyzxj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2vhhjknxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2npjsqboo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2lfzjrnwb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mbbpivdo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgxtacwe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2xtzxnpkm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2yrklwzxy.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gt2mmljctne.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2mzjlunqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2auewswgb.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2alpuswvk.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2qghffowc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imoojdfv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2opmexgie.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2hnaelcao.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2clqjfvxw.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2wftiblaw.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gt2fdrrmamz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2xyfqfzmh.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ramnimgw.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2btddgdct.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2fnttrqjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2ofsdwqky.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gt2casxphuf.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjpgpusr.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2evlesrgw.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2rapkbchd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gt2aawmoiag.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2cwalteua.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2fyzoznta.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gt2rxrvifgk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2rtaexsnx.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gt2hovocqyk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenzaomai.com/Article/details/gt2inmgzmnh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gt2dawajdtu.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gt2twgwewsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2khywpgxq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2dlbymvlz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2pxdhexfv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhoopnsi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2rwyzovwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2awenlxoo.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvlrkvpu.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gt2vpcykiyo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2vnvoswbf.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2iovvjtte.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2dkqqkbef.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2cyzpgcxl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gt2itjytkww.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gt2rpihvazn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gt2uiokqwad.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2bdzwfyly.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2hjgsjrmz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2zuhnxowg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gt2efcyrixc.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gt2dmtyiick.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2dqfjyabh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2caroozau.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gt2gnuwlbnw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gt2opcmerpt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2ovslczgp.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnosrxxq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrjdfvph.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2ayxvmzxv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2sqwigakb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2doldufhc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2hgjpildt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2uhqyeebp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gt2nwgixbbt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gt2cbbpzfzv.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2zygmzqxa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gt2mqsqagvk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gt2xdvwjxdf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2qpmzlqme.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2rulsrvbu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2hdzujuwy.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gt2gnwnhqlb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jttpvbql.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2eoubjqqd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hpsjataf.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeiqdnio.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2eifbejfh.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2bjvjoaan.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2yusvhhgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2xtibccqz.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhljswrh.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2oaankoin.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gt2pjcijtmk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2fkkagoqx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2jdslfhud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2unyrzwyt.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2xqzqgbot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2dxcgzqql.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gt2mwtaohrn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gt2yjzaxdpt.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gt2qhhzuogx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2rawoddic.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2hrcbdzup.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2djignvdm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2gntjslgt.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2nbaycvut.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gt2zxujgoeo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2yrtxguzn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2znegeasx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gt2kudyomix.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2asxiegmg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gt2mflfsfxp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2mvlmjqnq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gt2jjwwjlzi.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2otciglbc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gt2hjddkqld.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2irpvvcjp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2lajepvlz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2iakbyzbl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gt2tdfmjdpl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2qigjqdgc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2wobkytsz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2ufzetjxv.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhxcjccf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2glctwjqe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2nditbiwl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2ldjvjsna.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2witdzrrr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2nxkonqwh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2mfdtinyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2qzljphno.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2ikqniniw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2kgmifgyx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgwrbhfh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2ufxmgrda.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2pgflsauo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2nbbgambe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2revmaarw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2zhffbueb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gt2smfacudu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2tzmcwmyl.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gt2vnhyozvx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2ahdyazsg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2akqerwrl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gt2yibqaeue.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gt2qltyjqpu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2ybedgkzn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2rsqftirw.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gt2fsxvgrhk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2wrmambdy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gt2dykptruc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2ulvfjjvx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2oyfhzcaw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2zrnzkdgi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2qzrjggyl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2oxudxwdp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gt2uhwzguiw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gt2frjjxauk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2pnhjethy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygohespk.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2ssgzvfgy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eirlymem.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2bpplxnha.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2stfbgwcf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2rryzetcb.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2lazlufzb.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2txqpjybi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2girneofi.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2homgrjyi.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2oazacbvw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2xvirqytr.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2zdfpkdzj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2dlkfpdbn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2dznecior.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gt2blounflh.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2qfyskivb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2uuwwkxlp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gt2twwjnabq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2jbeaszyf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2qsnnddul.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gt2bjfprszj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gt2asozopec.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2skopzqxd.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2wdxzbobg.html


<!-- 参考信息 -->