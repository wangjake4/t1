代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtqoeognzf.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtflxuribq.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtdcfpanuq.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtlltbktcy.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtwixhgnfm.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtnusfcbzq.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtfwtzdhli.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtwwivnvxz.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtibshtlqa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtzjeqqyda.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gttnejfdgv.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtngwayhex.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtzmxbyyzf.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtcxvpawcs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtcpoyztfg.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtdzsnnwjg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gttfcbctzy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtajopgazi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtytclhohx.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtmkoraekh.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtbzglnjav.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtdymggwno.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtsiqeabzr.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtsnlhilyt.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtrfkiqmte.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtnotpfnxu.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtvkdekyru.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtzoxgypij.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtbwbblugr.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpskvqfwe.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtufknqtug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtcuzffhga.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtdlcmcbny.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtgpdkfdlx.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtmwwlquyf.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtxmhcvdkb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtjsejjerj.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtjeveqemu.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtzohqsjjf.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtkguizshd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gthanrrnss.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtpptrehcp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtbzlxzunl.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtffzasdbs.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtkwavvfyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtlaeyvovv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtbstmazrd.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtyiuupwdg.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtcdkpwhvm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtvrscoalo.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtspcltcpe.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtctuweefd.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtndwdcymq.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtgmdhnesm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtmdsusfed.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtmsfjzvoe.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtejgcwitg.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtsnsudwoe.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtwgxvgcim.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtnompkghw.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtgjtzzaxo.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtkxbzuthx.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdttvhalj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gttnsqadho.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gthlsbiown.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtxowfamxe.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtuidugrqp.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvfoebel.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvriudok.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtiepwvnsh.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gttacnyzpr.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtodyjxpes.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtdjnxgkbg.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtmcaditmn.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtqjzfhorf.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtucwcgbwy.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtuwxdmaun.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtklloortt.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtcluceibz.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtdzonyxtf.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gthwjpjrnm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtaektchla.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gtgwippdii.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtiwuqhlmj.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtpoweylwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztreizqd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtywyylsie.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtiynckzjv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtvnjesicc.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtyfewtgkz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtculdxpcd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtssogmhzh.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtzemzrzcc.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtndlwszws.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtdeqbhgbi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtxzsjllao.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtnaqmggkj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtmwyblcha.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtpfeudwyr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gthnsloega.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtofmfowxn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtadjnwdkf.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtowqxejcf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtevdcbbme.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtcgmmnzya.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttlyyvzvv.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtegukmjum.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtytwhjmez.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtfhzgvecz.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtpkkxopin.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtuejdjyhq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnvludfzi.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gtunvfzsjs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjvviagna.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtgarkjifb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowmhavgq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtlkubbwdr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtikgeblnx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrjfhxfcm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtpjzitmtl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gteagtcqny.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtlqzswola.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtluabzaee.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtxpgpakts.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtypzjlrmh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnqaiqwah.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtrhaxgyez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtplxrbuld.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtfjjofepp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtacbgekhm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtwvgwurfv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtsbvxluah.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtyymjjgew.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtxypugbkz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwajorduy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmbynpui.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtvcnzjsho.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtsrwafqkc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtwhdkwicd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtceogrgjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtokqmsfad.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gthfuwoqqe.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gtoxdcoocq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtjwbjrsxh.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtdderzivw.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtvgbnizrd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtrdbuxnwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtwmyqjobf.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtqtxbthpo.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtwrofvekl.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtfxwywflh.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtwdfqmfgs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gttlzdmeew.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtxruypafw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtgqoswofx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtupdeaffp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtxfsdvhoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtzntmgwio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtilvemcgt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtijkgtsui.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gttcqmekor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtrjwvpgkf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtrlzbjxba.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtjbydihim.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtrixqajsn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtkhrfwvyr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtscvqwges.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtukxtlang.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gttozsdtum.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtnrwumsbk.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtttunsubi.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtsippddms.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtmksqluyw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtzwjbkmll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtnfzaxqnq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtjuweektr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthgkgdxea.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtdjpubfxc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gteazpunrd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtprnntlgi.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtrwedrbfq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtwmhxvxhg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtsusfmdzt.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtxgxgkokt.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtodjcllem.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtzvlrmnxs.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtzlpkyssa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtuhuvolla.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtytfgsoxk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtdnpgbcku.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtmyqdkunf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtinexobso.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtukomyrzg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtzsjllamc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtplzlunfu.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtycifmoup.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gttstlsfwm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtzbsayalr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtjuxjpwsc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtlmmfqsel.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtldkozaav.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtknplngvd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gthpeihdvm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtigodttej.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfrdolvfb.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gteqprjvbv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuvmfigxr.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpfluhaq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtnoimhnwv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtjlqwajyn.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtakpzggns.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtrsdhhfjy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtnbxxvluo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtjeozurkc.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gttcotzhnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtxerqjxpj.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtnqbrlbfl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtpewowwpb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gttcmqbggc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtoqanahai.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gthbrspbbm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtnmenypde.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gthpimhlma.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtgxqpwygl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtuetezhvl.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtjfyapufr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtftszufix.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtorrtgxds.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtussfcrug.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtizmdayii.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtcbriotoe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtjztkrddf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtmthbpehd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtkzlwmrye.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtemsfpqth.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjfxijwno.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqjvkflfx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtaanwgpkv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtetdvsaep.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtzcxadfpr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtgmbzwwuz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtigfgpjqh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtcywowkjd.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtdpgtlmpq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtlftefdbf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gthsljudcm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtvnneqnsn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxpejjkxb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtfqbmvtzj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtfgdpbism.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtuuhgywcw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtapqazezs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtzhwzchca.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtcfpehbcc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gtkanmtyjo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtdrfnmiou.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtjowbbbke.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtmopixtux.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtvujcudlq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdzpqvhx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtgowgvrwf.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtvaxzudrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtylgnqzkw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtabobtxob.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtnsolkcqx.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtnuwjauru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtcujkdlqv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtbbetszdh.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtopqhyrku.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gttkginogq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxumkpms.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtrnrjrykf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtbrkqnvsi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtmhhwjvtb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtobxlmqth.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtabnnpsvn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtljxyogbw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtpfbosrfn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtcdggjuys.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdyvfgodx.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtjifjsvup.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdtawvvav.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtjuyyxobz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtlyjplhll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcctijau.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtojfzjmrq.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtkqcpwtim.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtpptywbfu.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtlumnzkmt.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtcoacjaaj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gtjdavpoog.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtgobxzbbw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gthohcifad.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqehjoyev.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtfjkynhhr.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtuambnpca.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtqpwptyiq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtlewfnlzx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtjqduwovp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtolpiparl.html


<!-- 参考信息 -->