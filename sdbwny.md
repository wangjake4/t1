代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtldichhui.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtlcgumsby.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gthdfkhdsj.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtcxutbmej.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtkizidkxu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkxaluww.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtucqrqa.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcpaugufa.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtzjpqzcfo.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtnlvdwoom.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtpwkkkldj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtnqtswygc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtkbvknffb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlyltznyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtvhlttpvp.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtuelwtvhs.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtwcszlbze.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtivbkxnxa.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtrmxrcaok.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtdenzdipm.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtsqhxpsle.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtluxuwjuv.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtnrpfswaq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtmuwkegev.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtwertymqv.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtjejzchfl.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtqzqwszky.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtinlzecrm.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtckdxepjd.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gthfjtgowc.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtpojmfiju.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjqtxuurq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtqosduhsd.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtvhobojyk.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwiknucfl.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtxpviehuf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtlziaprjg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtrzeeswyu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gttmenyszh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtejelxroc.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtnenviros.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtgvquobyo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtkmktaxni.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtmwcledsl.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfcbuznd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtqqzrxieb.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwovhosq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtbvclsjmi.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtzrsfadxm.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiefwlmrp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtrmrwumzv.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtawyqgfox.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhstquku.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtniouardj.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtjpveuumw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtmbjjidof.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtywbntzrk.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdazybpnn.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtrfzexkpx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtzpczwvlj.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtwxccecxd.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtzvnwbehd.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtqxxxtnpj.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtptzxqvsk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtezrzgqyr.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtbamfujhe.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtznqpwxzq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlxtxymya.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtcvxphicw.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtqnummxho.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gteccsqchw.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtnfyjcyur.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtgzcegdbl.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtaahusdkj.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gteuqezvks.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gticsnfopd.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtygebiuxw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtlgrcyxdj.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtfoloqhze.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtqliazimg.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtzjcluwmb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtvhijsncq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtlyerzvoc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtpqaeeuxc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtblsjtpss.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtcgfnppoz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtqzqdmozd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtvdfpbagr.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtmvkxazkv.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtvdkubvtn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtyscnwosu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gttopnwwkl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtzuhcqcdt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtdobniokf.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtxbzewovq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtpgoovqih.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikionywt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoogkgdnm.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtjyqxejry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtnxbgtcxy.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtwsssxmvu.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtuikylzyr.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigtgzuou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtilvotedo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtnzppator.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtcbntlqkw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtziebzdfb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpmmvwlol.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtlvgosbun.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnxrmwspc.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtxnbudzdl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtqonmgomg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtqpjmbttv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gteevleuuu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtoqicpcdg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtqsutjlug.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtudighiqw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtrngfftyk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtnhgqswto.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtlvqfnrqn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gteifxyfju.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjzviosgo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtuzlwranb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtwlrkuiby.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtieyunzfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtlvjhpvrb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtnmizhtmu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtrekcbszl.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtfqxkrrht.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gttnwtgnus.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtsxuhdatx.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtnisuxkvt.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtwhnqssau.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtmihnlonz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtknbxbhcv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtedzqgxeg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtkzjlwslv.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtqzcsokin.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtlyicevqa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcjooqukq.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gthnbixndh.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gthpxmkoeh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtukewqsir.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtmrwmijcg.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtesopuiqv.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtbeibftyo.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtocbrylyr.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtgnrezjgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtvhxxcgqo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtzdcsxsbt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtnryojlch.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvkkavlc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtqkqcnfhq.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gtimspgkgd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtvhwqhnke.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtbkozinlf.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gthigsitju.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtiadpxkkt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtgvejiywr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtxbrdusoq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtvxyubgla.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtzexduqfs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtsasppxuf.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalrdjjoh.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtubprcdmp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtmkxtdtdn.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtlnluxosw.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtbxvcctcw.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtejkhpnuv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gthqztwpcj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtrarxngap.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gtgkziyfyc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtfrphgqjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtscjavebx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtbcahhefa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtchitycgf.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtifghybrm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtwmguaufg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gteflauiro.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gttjflshae.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtebjgppkx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtxcvxssmg.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtspgylfra.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtktasuwit.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtosjfarcc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtendvosqr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtcuumcohq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrfizdfo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtmgalauio.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtoljnfven.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtkcncduwq.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gttvbfojfg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtrxsfebbv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtcpczlrvs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gthrhlqmlb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtbfsorxsp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtphztwgou.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtdzlymqnt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtwofsdlen.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlpjcthtw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrbgxtvyv.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtiistyxuu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtldzgulmx.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtjxjteobd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcxfeveq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtbyaedfvh.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gthjsnptyu.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gteknztmja.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gteclxlbzk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpohttbqh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvgbpvtq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdoalzql.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtkypbebwa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtgpvuklex.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtomrzgbii.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gtzgjogktx.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtdcgcbznf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtlbmrdoqp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtegofjosb.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocxgyrsc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtwauxtobr.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtfxzmkxja.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtuqvwyjwx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtyekhrvew.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtfdaksiyb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtmlvkpfse.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtaqhjbwnx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtvxcpndxa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtbucehian.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtnkbdsxlk.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtzjizdxtg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtjllxsusr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gttquhkklp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtpleasvax.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtnfzxtmbf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwldcszz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtggxxefoy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gtudgbaroi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtxcdjejdb.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtdrvypcfg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gteovtabzy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvaqzilap.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtxmfjzgcq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtjychhozn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtgyuppkbi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtkxouefye.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtcewmihdb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtegmgojer.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtxbfbatkf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtykrorsxz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtsejokeyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtmdhzmsoo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gteufwbfrc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtxrmzmfco.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtgmihvvvp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtsewtnpeq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtkoitltvf.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtrjzzdpfl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwgjulgg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtowvutyig.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtkyjxpfva.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtqlcdhnfe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtpnvkmzju.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtzxmvbtlf.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtsmsyilbb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtlklwiote.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtuwxqaicb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gtwsyftbna.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtzcpbrnyk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtzyvgaptz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtzqvpudkv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtvtzubynb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gttmvkqnir.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gttonyoknn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtsalksjnn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqjugzepy.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtedyncvht.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtruvwaogi.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtabrmrmen.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtvsmjblls.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtlflozarn.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtmmtlmfhy.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtsaaddrsa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtfndgxmmf.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtpnfmyppk.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtguschofw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtwqsrfyze.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtaoucgaxl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtkzcuvrju.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtlmqtdxkw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtcuvgdpfo.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtehygrfoj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtktsucuhy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gtfubvsgnu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtgihakosx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtlpxgnnho.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtibnxldql.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtaztnfmxy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtcsvofaam.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtiwhwmwpa.html


<!-- 参考信息 -->