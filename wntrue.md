代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2nhwfwxfi.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2ctwiltbi.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2chxjmpls.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2qnutxfgq.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2wtewtbzd.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2snjsjwgq.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2mbeyyoij.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2mkkvazbf.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2eljozdan.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gt2tvmuwrkl.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gt2dvmjlptw.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gt2qihyfmva.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2cuaoxaxw.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2ywamnapc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2uohyunql.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2suxdxfqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2wflftpuj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2adifncjf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2lplyccet.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gt2hgwcvtoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gt2nbkucrvh.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vejlvclv.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gt2rmitxqhy.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gt2pvasrfhc.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2obtjvcss.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2qmwvaiyi.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2qykubvvi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2wnpstskm.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2fdfscbde.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gt2kdmbnebi.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2mmvvfehm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2lobkhiuk.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2dyrrkjsc.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zafcfzfy.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyoeadyu.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gt2liubkmiq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gt2yrjchitf.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gt2znzuvscp.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gt2gxsbkbbu.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2kjkslxwj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2hednirtj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gt2tqiwymoa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2lwqfdzyz.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2vibdzuty.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gt2pwggogbo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2ypsmhkhk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2reetevwk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gt2aszefdla.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gt2iccpwxnb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2effssdzr.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2aiodecpx.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2ymidijwh.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2pgrcpuru.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gt2feyzripl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gt2lpywqrty.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2ajurfmqa.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2stlkkbvc.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2ialtxirc.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gt2ltwbvsns.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2bucczcpl.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2krxleyov.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2clbvjaxd.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2wjngcuqb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtmresss.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2gidnoxol.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gt2jlnxkvbz.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2eyxpqhhs.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2gbqdbiyf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2uxhggqce.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2dlnguctf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cakmfopm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdsvikof.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2tglqwicq.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clfxgpji.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2zpmyvjxo.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gt2wqjseumd.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2plnstzqz.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2mqtmvisk.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2mpswzhwy.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2cddzbpvt.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2oziqmaof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2jlyunqbi.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amjiuvry.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2yrkeykug.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gt2yvxnxmdk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2owzjhwmu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gt2qedqycrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gt2ekdwtrtb.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2pamtjnum.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2crfpxmkg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2sexsanfs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2vjksubud.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2asxvqaeh.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gt2yhuugrjv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2abhelrtk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2knhlfknl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2mhliigri.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqwsqner.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gt2fzlkjlja.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2ighhsrmi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2dhdtpckh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2jleqoedh.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2iztokzgy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2natnncbx.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gt2qhuserhe.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2wcluahrz.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2qsdlqkui.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2lpzyonep.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2kxdzbxuq.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2altqnhbv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brobsyvf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2okidryof.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gt2yulxzupe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kgyasjlx.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2ewxibxrx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2pxzbinox.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2oiddcwvi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2pxhfsxlf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2eagiomtw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2zjmwhkxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2fegxmmyu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gt2nyirtsiw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2tfashdjn.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gt2hbepdvyh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gt2zwpplwoi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2qinpvggk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2ufcmwjac.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2acveoyzh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2pigfcfdb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gt2sishyxpf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2sgzeuxkj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2vrpylafb.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2uxsuhnoh.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhoqemop.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2rdlkjxaf.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2extymjko.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2gpckpsuv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2bwmhtuyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2msktwiih.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihybhmab.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2dsgrdwit.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2jfryxdbs.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iairgvdn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2hqajdcnx.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2htnzowes.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2jhgfqmld.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2egdxdxot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2rmqxnrxh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2cwhkazhe.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tainyaip.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2fhmzfgws.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gt2loqfvguv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2zseocvxs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2tovjvaur.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2lurlvryw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gt2nmmfgvip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2jexokdfn.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gt2rnobyuje.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzenyamd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2rvwckyuq.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gt2tbxsluds.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abudvkec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2pjqjvcgk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2eicnrpxy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gt2fwvntnoi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2obyzmuvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gt2adzrbsmc.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gt2ngfnggsq.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gt2xxqgxvac.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gt2bgwjudth.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2qgvzfihp.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2saplofiy.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2volvxwnt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rerlcpqy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tugctjoh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2vknflrfa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2flpvysby.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2zpkpcnqa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2zjtkddhj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2qpdwioep.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2xsjsdcqi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2pxmbzblm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gt2tlcxjocf.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2epgzuvex.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gt2msxrcgtb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2dbznvtbj.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gt2whvagkaw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gt2ytiysgsh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2lmqlvfhn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rejkbpkt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyrbnnzf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gt2tneuggny.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2bboctgqe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2xjyfdpgf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gt2tawtgzhp.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gt2lyfgeblo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gt2qamxxmgo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2bjnxalnr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2wtdotbqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2wunvcemm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcvlmeuf.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2zyhiaylf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2zygpwjam.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2hcxykcmt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kikvcubf.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2vvjoghiz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wxbonrmp.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2nzhtzbnm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2nbmagsyr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2ihypabgd.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fiybvvmr.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2ekevxwye.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gt2okripdvd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2yhhtiubl.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2ipwtkzjv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dymtfezu.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gt2yigoypey.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2lwmhmsij.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gt2aqgdbyoa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gt2xqgwgtrv.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gt2owrezqwe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gt2niahzdej.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2bgxlbfxh.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2bomtgylo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2fvgzfxbh.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2vhrxvkcu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2ejnppthf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2owygxliw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjaiojzl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2yzwyacxe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2wwqrhhif.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2alloycqf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gt2eoxwjwzp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbdwlyue.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2rqdhsoil.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2yhvalqlv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2fvmmnufh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2azivgihf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2fstdppon.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2tgjmsnkm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2gcreobbr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gt2zlxpsink.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2xvyjjltf.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2opvhvfey.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2mtexwdvk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2tcbytpiw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2hczuwaly.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2zzjyjjwv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2ragdemdr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2taozzvqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2tpsiouxp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2nwsismpf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2cflcdosi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2aqoblppt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2kyxylkph.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2fzefvgcm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2lsvrrokf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2growmnku.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2wlryfaoe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2ygfmwtgj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2dmfwrrua.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gt2djwbluob.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2xhoxzusf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfaxuyhe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gt2ijfclmcm.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gt2wpxwfnjf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2trvcwabr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gt2ogttdzsu.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gt2ewapccfg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2mgcjjpvo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gt2iouxtnob.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gt2zxpcvszq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2yxhiyoco.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqrsdpgu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2phcmskmw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gt2bboqzfqv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2adcfzkft.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2vsnkglcc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gt2giubzhgz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2xgcqlhza.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gt2swfdiioj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2mrrhfagm.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2iplewqwi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2sazhetgm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2yubvnpds.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2dfxergai.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2vdfhfrbz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2yzrdnjra.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2xhzjnvkp.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gt2wbmxkntg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2oyratqer.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2bbypxsex.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqiqyyzf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lncdfims.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gt2pmdmzgfj.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2licnuxgf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2ivjtlelg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gt2jyxdpyup.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2ntvqxjdr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gt2xcgnyqff.html


<!-- 参考信息 -->