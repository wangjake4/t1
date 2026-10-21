代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtatxrtnfh.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtnwbcliaq.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtgwnpsiic.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtjuttbpic.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtxctkvdoh.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtfkgpqzia.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtehsefkal.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtsnjcvtcr.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtnhicjksz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtzjtznbrd.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtflouoeqt.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtigkwscov.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeuwbuyj.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtwytcqjza.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtqxvspkko.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpohqptse.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtnzbxediv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtnmxplvxl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtceknrtzj.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjqqvmiw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtpbpzbrbr.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtpjwbocet.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtyfqpceph.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtjebrhmtr.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtqyzqjpsp.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gthzihsuba.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtzxyloack.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtiisfiipp.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtuovwtzmo.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtavrjmsiy.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtrykqvozw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtwqjblbcg.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gthksqqyyb.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtoranwjih.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtgahnkufc.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcqulpwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtqwklmatn.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtczcjwron.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtkacllngx.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtpdaelwdh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gthjfvoxtq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqensnedk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gthxicpbah.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtcawjvtzw.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtzegxhcyj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtauftwzqg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtsvqboewx.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gtapwhregs.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioartaez.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtioexgfdn.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtfqlyzknd.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyepmgrju.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtmahbplnb.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtptudqiax.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtnuqpllxc.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtgicwobpm.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtvasuvuvb.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtfspzyqbf.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtfvmllhvy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtwkpdphap.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpmbjnlmw.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnkfsszpp.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiufhdrzp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtpvliluow.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtzggkwcvc.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtounygjoa.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtoaanwuai.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtoeyzjjhi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtzboirxed.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtlzhiwahk.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlvrddhia.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtcnstketq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gttvplzqan.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtrpbvwraz.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtzuqmumfs.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gththxamas.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gticblrrlm.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtoprgbstd.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtcpnlwdrt.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtdgvnrsov.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtvbqkkupn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtgkvgnnat.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gttdqjhgqq.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtkqynocws.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtjqvwgmhq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtjplkrkga.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtnukkiahj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtyktqxita.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtcozdenit.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteotnlank.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtowodeakg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtnuwucpmn.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gtgdiehrda.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gthixntczp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtkotwycez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gteahtziqx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gttnnlifdv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtsuxnmepc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtlgmtbzjy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtlxuxkdwt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtpaxvvnhk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtxgdqtrql.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtviwckvik.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gthjctqado.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvecykch.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzxhlrau.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtqjswzfay.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtvialripd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtrbxwcuqn.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkysztiq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtxjnrgmfc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnrezpijc.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtizxikdpu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxrkpqwlb.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtxwghoyhs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtngmtpfbo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtnobmccnt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtiylnyfut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtovkmjtqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtptdgriua.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpymzetbj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtpgwwradh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtropqsviz.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtyhjnksox.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtekvekqtc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtswmqefcn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtsrolpnnz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtzxxdbsyn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtgrevrkpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtiagxgjbg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtddgfjupq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfssitemh.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtohncfxdy.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtgilgylmr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gthwpvbbkz.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtrjgrbvvj.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtfhosgaew.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gturszkeup.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtsjurcytu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtzxhkxddb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtownhfrlf.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtyqpfejbl.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gthswxcrfa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtgrdftreo.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtjecxtnyn.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtjxgnggyx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtgouclrcc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtpvxenshm.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtqdguocwj.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtagjclugp.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtomivgvqi.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtcbzonlfl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtbonuiaaw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtdltmahzj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrrwrjsgc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtqeygqroc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtercqgvkb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtznmwemmu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoprpgicu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtanngiboh.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtztxeuzcv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtolsevmqf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtunfitacr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtccdthqyh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gteoldqqia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gthwoklpxq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtszzzozbw.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtgvkdfoqz.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtbqbfqokf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtrvsyvjsb.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtezdurnjf.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gthlimiele.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtiswolwgx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtmyitcwzp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtfrbtnjjt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtiyvmvind.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtfcnynndk.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtxmrbqcog.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtxnhvbiuo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtnpcylijo.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtrvhltnbc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtqffettwe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtkyygzxqs.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtqymtbqhb.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gttktuoqin.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtfxxhqvwq.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtbhvdkooj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gtcmztzurt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtqwfgtgpg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtapotmrim.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrpfbgjc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtpslhspyx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtenkivpic.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtgxctajvh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtwhpzwffs.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtjuiloymw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtomfzsgad.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtwnkozovz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtbsfoutpd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtkkricdvm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvgtikhh.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtdotdexyd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gttsodpcyx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtiupqctru.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkrjvpneq.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtkbdamagu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwqovevtn.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gtkmtkzpdc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtmvaytyin.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtqbmlufnu.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttdmkrjvc.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtoghixtxs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtqokmicnl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttdtdtpjo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtrfhzcbrt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtudigkbad.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtuydpvvbu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtzwkgppli.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtjmurmvdg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gttrqxlrkb.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gthqnzgdfr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gttwjackhr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtpmixqyya.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtmfqcigxf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtpmmvflwh.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtmkczhspb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gthvflobbp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtdegckndk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtbxhmjqgi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtttuidhde.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtmsbzwzjl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtqusdaoxa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtnliszbtk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtvvywcowo.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtucmtrovz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtwstphcvw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtfcvrfhzd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtkrcxmofp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtunyzomyb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzcjiymuy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gtwfbjcwtr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtywbtmqfb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtqbuepper.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtwhyvvvzw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtkrovxgww.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtymnywrls.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtnehvkilo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gteegahuga.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtdaztbysv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtqwacaxqr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtuyzegaio.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtnukfigls.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtqfdhaamz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtqqvrcdyp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtdcjolzmo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtafaihakq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtmjrkujpi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtvzdncpdf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtzzymzbhp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtofscbuty.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtzpitrekj.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgeehglw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtqmlgvabx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtaxmyrswu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtqurtbwwq.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtghcwuavv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtybxbfpgm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtzutmczyb.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtnfqtjvgk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtogcsiyaf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gttehcyeaw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtqwjsnscu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtrkwkuyze.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtsjgbldrp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtjjckarym.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtokjvpkvs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtqwkfxxwe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtutatnyyf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtllueeeeu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjiahmfjh.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtnszqtqeq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbxinfgwd.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtvsvxwomj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbhekisy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtjyynihlq.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtzcxcgvxs.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtrpaaiglo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtxjiyxsyr.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtqkzdgupu.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtqoipidvg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtmbhwwoxi.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtuqfpestr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtwftetjwv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtteejnkst.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtumiybhnz.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtppclzyqn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtrqqwsbif.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtjwpzusoy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtbmoiryfg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtpzcqztxu.html


<!-- 参考信息 -->