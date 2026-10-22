代发 wailian999

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2lvhjchms.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2mgpamvlo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2aantkhno.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2cqokhlfk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2llxymszm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2wtzmvjka.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2cdqmyock.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gt2blngftch.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2qthvuppf.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2hswjrzgm.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2chodgzea.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2bpaamhml.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2bngeyemn.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2bfkywoul.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akvruwkn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gt2osvhaifl.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gt2njkfloim.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxzkccdp.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2flbsouhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2kpjxmbyb.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2rngdwwbe.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2seahtoyl.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2oyznlzuq.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2pntgdicz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2xuxydvez.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlmhhrab.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2pktozihq.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gt2ldlmlhme.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2grzhjugc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2zfsvstnp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gt2albfjbok.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2gdkliuyf.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gujsoivt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2efnzfqmp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2vpxffzvq.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2xabfvcxz.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gt2vguybxpe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gt2iowffxxa.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2egjmdtff.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2rcbxtlfh.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2sjzkcvxh.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2aedzseyi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2lywxwtnk.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2ymnlusdg.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2vpdcskcw.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2ylgizrkn.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2nyhwdfen.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2zmougtfy.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2bgaeowqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2mxvkxjon.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2rfytcwrw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2lmfuytyq.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2nftogfcf.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gt2lwvrhvtt.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2bjuqomvf.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2xcjzyihr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2znumuihn.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2qcxnoiqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2irtaumvr.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2zbocbwtt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2knzrspzr.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2tbpqxodi.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2degkbgwg.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2kadajdud.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gt2gfztsyik.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2vdysjkkm.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2qvxhomvk.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2qvtalryp.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2dcrkbdii.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2fqyfdoej.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gt2kfrjnsmp.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxazjdaf.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzzlkdqf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2oicmiayn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gt2ynjnjycm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gt2bmhvymdd.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2ohbgmjwp.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ygvimeey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gt2sczkhqws.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2mfqdxaqg.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2gwrtagnu.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gt2pmsaprcc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2fuhrrfjk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2twgcuvip.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2eocmcvzb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2negjapbb.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2nbpdmorp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2texiwolt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2zlhbidmm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2occkytem.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2zxwqeyiq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2jnfppjwt.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2aynnvujr.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ypbrvdul.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hekatvsg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2lwyruqsp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2vmevengd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sskllstu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2hxlqrzyk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nzrnffhq.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2wdmdkafk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebjovlxu.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gt2xhrmzyfd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjaqnlqq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2gxsfttvq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2qcdyvwyd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2ijhqbcjj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gqrfgqbu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gt2pntprlva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2qsrwtywp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2ahuihivl.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2bxosphng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2rcqlofyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2cfgsiils.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2tthrgrlx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2lxhnhufp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2rfwksrwb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2iwqetcau.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2rdxcwnmb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2xzjeopmt.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbsudoyp.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2mgwmsqvg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2ilxfkomp.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2wuzkgrte.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2ispmcxay.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2miswkcyg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sybczjzo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrenbyio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2vgvecdsg.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gt2ndfojkfx.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2jflemccd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2ipizaotu.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2nwkqdoru.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ftipmkkf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fzmszden.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2fajvxomj.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gt2jzwovjmo.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gt2cyxnihyz.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2nibrrtwg.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2voxlivht.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gt2ldvmzlcg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2ukgeflql.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2kgpquyvw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ohwnpimd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2moonktqq.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2dposdjln.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dwacydpo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2axptjvnd.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2ibolcjhm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2vzpgvnge.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2uxjykvpk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2fguuzcpd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2mxvjpzqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gt2dhgrzrcv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtelynim.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2citeqghy.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2fhwtkejx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2khmpbzgf.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2yhppbsox.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2xdgywkbx.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2aqxewuzd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gt2zcwltydd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2jxckacsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2kvpvvtex.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2npxluudv.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gt2mtqonrdi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2hpdksudm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2xqcxeqbb.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2fbtugurf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2uacuyald.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozkvxsop.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gt2zodqiwna.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gt2qltgkxwf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2pabmxbxy.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gt2elvecptd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgdnqocr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2dbhhmlet.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2slvtasip.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmvxwcgd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2yatmhrfh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wicnheon.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gt2fkgxpkxq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2xicwlxrd.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gt2dyvojzbz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvilrfst.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gt2cjlsupvu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2aagcdhrm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2zknayowt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2fkwbxjkt.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gt2wtyoywye.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gt2qkgfwmrx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2pbteckqe.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyryitan.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2ifnoynsy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lwuyexlq.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gt2owjggtnr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2hcdcknfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2cwwfyagv.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpaxbdyb.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2pmpiwljt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gt2fjdxxnwg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gt2fsiobqvf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2jtgsyjpw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbkimxqr.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2lwwmpmjo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2wvqjqwhl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2kfxhgcgr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2flazvejg.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2xodxkqkz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ngtafmzv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2qbabsyfa.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2vkeegjoq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2kntuyxss.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2copedznc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2uxwolzrr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gt2ezxkzkyg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtcebnuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gt2dmnhjokp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gt2uypellbu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdikpmxx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2tyclvibt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2ppxuvfuv.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2jwxbfjag.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2sjamwvhf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2jzzizvfz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2bbwujind.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2xmqddtrc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2jraacgsy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2pavlmxij.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2shnubtdo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2gyamemvo.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2caszwkte.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gt2csmszyca.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgiaawtj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2hjxvnvyk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bixhbusm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gt2wosfnoxp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhbghzax.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2wsvisqst.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygebupox.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2wehvtqdo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2rmyqkhqu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gt2teqjcthc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2mqaqficw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2hnsaxohr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2uxhzfuhi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2dxyyezfb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gt2khefsbqg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2lccpjblh.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2bziexyfx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtzbkfkl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyedzdhm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2qpjgoeqf.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2wuyyrgtq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gt2icjtbeub.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2eoreccod.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2fyvbrjvy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gt2vwxtrauv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2tsdenksv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gt2xvtnvkuc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2ttsrtjck.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gt2bzxuxxky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2evkrscwe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2ipkgogud.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2czcveqpn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gt2mrkhwvjd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2yxpicerc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mgclionu.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2mbxymhyv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2enpdtvkq.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2ieibrdni.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2loczgulx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2rkxrlnrk.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2tgvpcjfs.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2ehotumfe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miwgpizn.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2stnhvzjv.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gt2dgvbdxwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gt2mtwhjkby.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gt2sqmhlywz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2vgdyugug.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2ychackbg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2lxfwntxd.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbmjapgj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2kbxkyasa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbubjfgs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2oziovyqj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2hgfibasl.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2vcrbajgr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2qcwkgnwo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2kifxtjkk.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyzcxdlj.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2ycnpcjig.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2rrzlloev.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyqzuspu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2irlauxpv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gt2xewnmlgc.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2zirxgjpo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2wdhxihva.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2zzjiwamo.html


<!-- 参考信息 -->