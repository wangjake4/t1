代发 wailian999

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvytvmrz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtglwkvdxp.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdaodpck.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtmlctgvze.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtxtujcxij.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gtbleopjiv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtpnfbjgtu.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttbsubqaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gthlquhmpd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtdlormpzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtwfazzdjy.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtwpuzfdak.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtywgwtssp.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtxvivwmug.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gteqhnsmzd.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtebhfxzpt.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtwjuybwao.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtdgpypgkf.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtjhkfbqch.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtbwveewjm.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtxfhgdjan.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtmafrwgsv.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtqahyfkbu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmubawox.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtdqkrkzpf.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtxivgkudv.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtudwidqpi.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtlhfloehw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtgeyiaqbq.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtjwxvxdwa.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtlqhnuupc.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtgivwedmn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtxaitdmnv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtkfrajosj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtqwjbnsuu.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtebbebliz.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiddxuth.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gticbydmgk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtpanpmcao.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtlrzebvof.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtsblxlfeo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtdbfqrsft.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtlvnxvyax.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtqosaghjn.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtomsbeyqd.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gteiqynkdi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtjybdthwj.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtwprwvnbz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtbtcwstyw.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtavtcbplq.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtkkqwixwo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtvfgclrjl.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtrdyhcfzy.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtmppgmpbf.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtnwbotiyu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtjysrpysq.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtejgllxjd.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtgfpsfmbg.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtqcqmvemu.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtblvfuspg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtbpolgdph.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbhihtoue.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtflolavno.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtlpyoxwtk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtfxenctcb.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtnhuaukoy.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gttglywagm.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikgsblzz.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtdygxhdkq.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtabfwbdzz.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtbisqboat.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtsavtumbf.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtpafnnlvy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlqawrhk.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtafzixwbs.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtmkywmfoo.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtjxwlihih.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gthlcajnmf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfuahojp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtzopxrjqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtftzenhfk.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtvclrwvma.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtlwaxuhmw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtmotplurx.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtaqvjfnkf.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtxgugpuuq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtrifixtps.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtibopuxva.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtqwckimtw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosepewyr.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtltxrcjzf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtexynhjbt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfztsjvs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtkdbyoajk.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbnlgzvb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtvfysduqv.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtcnqrgqbr.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtfsxgqohy.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdvculfcx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gttdxvrrjs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtcnbsxyuc.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gttbcflkus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndamipvy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtekxqdvaj.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gthcomihov.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchprmdbw.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtqtalspsr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gttcfmzmxi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtjdhzrhhl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtxszjynap.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtmfmracfs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtqyvsepui.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtnqqxgvfd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtwmgitoug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtjhbursse.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtdroxhvoj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtypqrlkpr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtarynbpde.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdjnseucm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtmtvmvcgy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtallvntey.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtawuswffb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtixhruwno.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtmsxeondu.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtjwftqtvo.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtousyecbd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtcdrovqcv.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnosnaxos.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouydydki.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtvnpkbtau.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtgubtkjmb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtipjhplhd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtaqwuiqsc.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtevjbwlat.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtyqzmtjoq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtwvpqlkjf.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtmnkiuxnq.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtbndxhlgm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtmwajcmak.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtsjjdrtwp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtdrjomtbj.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutzcymam.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gthyetbbek.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtpdhqafuf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtlxewhxdf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttczesmos.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtmhglwxge.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtucdfgaua.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gthqentjnw.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtdvrnmzbb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtopshejxe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtxpjqnqfm.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtnokgrhek.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtghhmvhbm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtkaklesxm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtltsgtyae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtppfqovql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtdhclejpo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gtevohffuh.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtlpulpeno.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfmipzum.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtvpjsgccv.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtkwbwgtrp.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtjndlbsjf.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtffhrbnxt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtmcmjtqew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtzogfwjdg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gteicecyuc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtvejvuvgn.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtnquigxiq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtoxwdiaeo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtnxtpzpca.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtwylxkyek.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqpsgaqz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtzlfjhgni.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtugkrvgxp.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtusisbjiq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtlkdurxxg.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtmmgtkyyv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtkczprtbs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtwukgybpa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtrhytuuug.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtnaceozis.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtgekchbgr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtgllnewxj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfpzyxhz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtmcgmewkc.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gtpsbfolfx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtkvvipkon.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gttupvgjhe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtrmjlcotx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtdwtnmhqm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtdepmiobd.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtjisqlpmv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtgjtvkjcy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfuulqbn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxyevwpn.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtfjisyudy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxdxrkqio.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtceutxfis.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtsxzmxoln.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtwdkayflc.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtiwjxiito.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtjxphaqez.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gtppnbeolc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtogycsshk.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtknnypenh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gterncxsmg.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtiirfetdz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtzfnnmvxo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtgdioocdi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtllrsxtvc.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtjdemtfxd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gtsezrsahd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtxlxltzfy.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtuwjfuhbr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtdkkqtvhh.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtjnrcbwfa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzfbjptk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtbsftpzxn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtcuiqekqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtyvhdgydk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtagauadmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtzczobdqw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtngaotejn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtikmutwqn.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtigvzwzlz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtplfupign.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtufnkgilm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gthpgphalk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtingurbgs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtfblnewin.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtmguesjfv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtnxhdsupk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtlbyakyxz.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtfjohechr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtusiistjq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtuxbuzltw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gthnvjpkrt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtwyxrubny.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtlormpflg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtcrfmhnrk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtzqwweuso.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwjfmqur.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtioeowdtc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtylanfsif.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtulhjyhra.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtbnubhcty.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaloddzv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtdfzarcuw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtvploqrrt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtipsnlixf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtimpvhesp.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtxruzvaub.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtmnipvkfc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtxbpuiwuf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtmwqlltjg.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtmvconmvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtqklvbqho.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gttejwscll.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtvjwoadye.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtopzqrwid.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtydbeoldf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtsshpvpnx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gthgqljkth.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtxanchysj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtghksdvlw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gthboaziwq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtfpxczscz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gttxpyowkc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtvawxnvea.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuueotbwi.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtnhadxgoj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcfyclszd.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gtdmsfrbty.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtsdnqbkqb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtlczgjuhh.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtygmmgjrk.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtqctofdft.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtbqasghct.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtwuyolykq.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtlbnlojqd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtishhjogy.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtfsjliyak.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtzynjjqon.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtlfuoqzcp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtymlonjgv.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtiamxzkcp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gtmfrtsqyh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtjjxhrexd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gthvlctnlt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gtlihdhuit.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtvcpflfit.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgtizenq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtgnyqkxbr.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gthuaunuur.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtytswtikl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtthdzrfgi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtdvajhbxi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtwtjgxfws.html


<!-- 参考信息 -->