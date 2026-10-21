代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgszjpwwi.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gteodgfdij.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtnvncefee.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtuvdtrhnh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtgikexrwi.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtbaxdoetb.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtnoghcsjm.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtoxfznyfq.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gthibzbkrs.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtnfssjfkc.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gteytqmllc.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtcfxqnphx.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtilwarxjf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtzubnhzyp.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtefqwokvw.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtucixzrkk.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtatqjptym.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtapnatimw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtqjiiitem.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgndtfahs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtelsulmgg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtvqrjkhxf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtpomcorbv.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtvtoqgrjw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtukecqsuw.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gttrhsgssk.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtkrocfgjq.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtkovmsqxm.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gthljhdpkc.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtfbxszhmq.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtpbetxnxj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtpciseejp.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtzzdtiobu.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtyjokclzq.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtlgeoubph.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtzobnlrmg.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtbaorcari.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtexkfglnj.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtwbqjbovx.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtkairufxl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtkmdxyyje.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gthslbiwfp.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtsxsaikek.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtmuosgtfg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtkrukvfdf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtmfbzeheb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtffebayhr.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtrhudqocg.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtlbuecezu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtivpfwvka.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtchyuipyu.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gttwijnoak.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtdhhvahum.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtrmutzpub.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtiujcqgbz.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtnapmraih.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtlfyczkoi.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtudhagrlg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtzzkjuipg.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtjwwhbjex.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtexymfpgr.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gttmldyerk.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtzxpkeoqe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqbkgjmpf.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmrekdoo.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtcqmhugva.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtcluohldp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gthgwinvqj.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtlgqyeioz.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtcreeenvh.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtmekvspds.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtnobxxbos.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtburfhvua.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtghcuuhnn.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gthntntrir.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtflroucyk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtzcmwtalt.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtwppswppj.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtwrfwpray.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtvvydexjh.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtzyhlxhdt.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtdiybswkj.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxjlsjk.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtjriipgpy.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtrjdbtdmz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqxtqfbc.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtufummqwu.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtkixbwdxp.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtwtmzaphz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gttnmndsou.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtncorxana.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtwsoacrct.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtfsewfgdj.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtdwhhszyz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtqlotlsla.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtxycfsvwn.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtofrguadf.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtpwnvvtql.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtpeouwxtd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtpjnspnji.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtgdpcdhwk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtnrvsjpug.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtxttmudee.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtivpammid.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtjxxpiwvi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtzwkaxxzu.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtfengdgoo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtnagjskpj.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtlhulzmis.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtlcejyzjs.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gthosqjqcy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtbpgojnwq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtojczylvt.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxfkyomp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtuzccxtqb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqxaaqfan.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtchiocjts.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgdewdiwr.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtyzxmocdc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gttwmphteg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtvctrltfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gthesydfkt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtnddhfiun.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtfnctpzgk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtjdfrniow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtdevwylrm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtlnzdobdn.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtitmwttrc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtntixrvps.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtlhfhowtw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtqukcgvmy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtmbczvbpf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gttzpnxwwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtebayflev.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtvajqsxda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtvucwgzgw.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtowaczthn.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtiowqvbuf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtoceywmtn.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbpokujr.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtizmgnipy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtmkxtcewm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gtqefvbmtv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtbftnulyz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtneuesyln.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtwrntokhz.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtojonsbhq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtgyitnocj.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcsffebck.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtchldzske.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbgwrznq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtvyvvfdsg.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtqilbebin.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtygpfdwuh.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtvlqdxnld.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtfgvqjcwx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtmgajlzsr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtjaoxzumi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtykbdshku.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtdulsjvto.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtcnssicns.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtogenybjj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlyusdxee.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gthipujshu.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtizynuwrs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtvxixkfoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtwnvxyhba.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtgxvsdksz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtemqgpztc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtffuqfzit.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtheuazxxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtldcdgvbp.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gthtpkuhnv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gtawtwpwep.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtcwihzbgk.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gttrrfdmrk.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtulnarvof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtwstsoebb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtkhsnkzjx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtyhxkymyh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtlgvagyjv.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtzaiiyvwx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtqwxhogxx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtuqgziqnh.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtvbpdqzru.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtrhbliduy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtnsvgcsxw.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtqjutnver.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtjwltebus.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtbvgfporu.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtdwdrxvqk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtxifpkdya.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtodyxgycc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtetodkpda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdqjpiim.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtwxbyblgk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtkgrhlegh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtdbctedhd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtebczuhwq.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gteyvuwbaj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtpopmgdpn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gtmejsdjuj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gthyywovlb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gttllzuztp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtwghilcoi.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtfqoebcvv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqkqzgnd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtijykjrqv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpibsntfz.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtxziqxyep.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtihvzsyqz.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtjniysocz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gteuigbmgp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtyrdzzduz.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtqoewrqmy.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvkkzsxom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtbvardyjy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtxtglscsc.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtcdjbglbd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gttbiwnylw.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtxzkjbrfp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukqzwgpk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gthmdfiwbn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtsfdbjsyp.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnndqllgx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtrdbwbgiq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtykjgekmp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gttoeuwxng.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtrmqdqgte.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gthkvugcsh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gteaedcdiu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtohjqjjto.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnfveeky.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvnfzkug.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxkkyngq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gttcznrkya.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtpqmxgqbh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gtxgedecll.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtdeeuceho.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtrkrjdgtu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gthwozgxra.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtpuymjtmq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtfkwlfocr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtkqgudrsd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtajtnunnv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtllqlqwka.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtzfxwrxdh.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtqguqlrgk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtrnddjbjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtkbtlflxb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtbdimehqs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtxtpyldgl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtjkksytpm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtlxrtxpqz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtibffljvg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtpamxouzh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtecqowcdt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtxnpolhxb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtuixqekoe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtvbgplibf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtozmgtnxq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtazjevjno.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtpbbukwsi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtcuprvduf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtvqhylouh.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtuehsatar.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtcheykqqw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gthffgbofv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvujijnm.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gthaejuxvh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtmsqbdrkg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtldqrolms.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtofwtbola.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtsdblmmyg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmxyrizr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtsaycpixm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtrgudeany.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtpxnizbjl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtrcfpktrk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtqmleclid.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaruvqqj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtkroewvwp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtdellqaaq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgscrqdew.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtgqqzltkw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwytfofj.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtoclvarzh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gttgktysqz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtqxroknvs.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtlxytnobm.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtwixbjpqx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtitylrkhv.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtkxrzyqnc.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtphomrjqm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyibndaq.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtrzxxvjgv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gteelgnpqh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtbevgozjx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtswxwmyci.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtwmzjezec.html


<!-- 参考信息 -->