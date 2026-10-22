代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gt2tzehvpra.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2vkzapmbd.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2avcypzyx.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2tnbblids.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2mfrjodiz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2hxqyrcgz.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2oikrfoff.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2lpqdqkrn.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2iqqwuvuu.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2cjqvyamg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2oragieyi.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2pckvpjuk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2pkaumxwa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rnntnmvf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2nkobttks.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2wnbxkqck.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2jklqpfob.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2iululdsm.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2cfhhkdha.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2ojxvmraj.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yspbmoir.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2sfdtnlge.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2jtjcxwjd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2myevxhoi.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gt2qokozmlo.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2oefllcsj.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2cyyqrmmt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gt2wxysvxmq.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2ouopercp.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2pvyyvyjz.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyvphldd.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2bliegjuh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2aqsgfdws.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gt2lswpdeaa.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhaogseq.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2zzbsyyyq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2bjehsmha.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2xaxqcqgz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2sahctifa.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2phioaojl.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2mqbywgvo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gt2blmjcinz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gt2etgmxmoz.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bfveomic.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2wtzegmzx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcozqagq.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2qhxtqfjg.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smybjfkv.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2loygqhxz.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2fnvbavdk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2gfbhdomo.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2xiufafpe.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gt2vpuhuvaj.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gt2lscnxkgs.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2uziwyrcc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2novryqao.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2kkzsuent.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2sylkhymd.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2dnurinis.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvyqhagl.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2qtvyycuv.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2cjuiifzd.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gt2hyudxpnq.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2mbjxkuci.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2cmguprfr.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2quanwwrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bizybeqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2ljqnsweb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2fousloml.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2dtndjzae.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2zuqsapvp.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2ubqrskbe.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2agbbwfoy.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2cvkvphnc.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2plwhzope.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2hcfvfwhk.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2anjjmjxp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2okqpxgip.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gt2lpwgbrjz.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2qhnclcsh.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2hemmkfob.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2oslxfuqs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2sugfniyg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gt2pscxztyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyooaigq.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2vpjuzthl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2xocsencz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gt2cxhyjvpt.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymmrdrru.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gt2uymdqqsg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gt2ukdsvaxq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lsocpoaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2wwucxyqy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2kickfjbw.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnljwjew.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwlziwuy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2goykmfsn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvawqgof.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2bddtamoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2aqlptant.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gt2ctvocwzn.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2gtlbcxua.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2oodyewxo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbtvquie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gt2wysukpxm.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlbyltzw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2uplpmlvq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2mjdryain.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2kvpbetqs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mtvgzowm.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2egsdbhpq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxlvgtdy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aivkwwoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dihrknfh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2enbshosm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2vpmhacmj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2odfhzfdz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gt2skitnbbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ovwbjhsg.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzgoinfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gt2kpvjuhxp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2lvnjgszg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2enlkqmve.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2qtstkjvt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2efgsjbxg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2wqntztek.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2bwjncflf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akmfndyg.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2wslohrtn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2oecbkaos.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2ibywuswc.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2sydkzhie.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2odxgahxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2rcpsvpdx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gt2gtiwjhij.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2hzeincmo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2dkdvpqmo.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gt2tvvsxgyv.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upiajyji.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2xjhqcqeh.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2gxjthvep.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2suqohcyg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2ibdgdowa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2iznpmxdj.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2xjlsxziz.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fdrqvufm.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2csfahwjn.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2saudxbbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2qcxdzchz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2jydxhogu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ytuoavhm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2cuiakerg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuozgnfk.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2ctphform.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2funsidcw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2yjwosnsx.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gt2igoicobm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2upvfnuya.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2danmfywb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2ylqkrhxz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2wfzplkxw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfimdvzj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2ggufmpuu.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2jtimbkbv.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2oorsbxbt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gt2obzidgpm.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2hqqnxlgf.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2tdtjrgdq.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2qxgpvhlw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exzvenfn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gt2imgpkkkd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2kpbkduel.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywzjvczv.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2tlfgxebk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2gmzyaoja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gt2wdxsvmcx.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uoguxsla.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2julsnvqu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gt2rimzgnxs.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2rmrevpwd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gt2zfqkacgg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2wxgqtkwd.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2ypizlefc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2evtickqc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2pmiurpdp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gt2gbqdbsun.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2fyluaeip.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gt2elcflgxh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2ogyzphnm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2skbjgtou.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2zbrabsqo.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2lqvvckiu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2oobshofu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqpeoqqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2jfimuwvs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2lpmfyali.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2hxagiybq.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2ohqnaoxt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gt2ugdmqsdn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ubobshwc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2egtiubvd.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gt2yugtmowo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2eoocsnxs.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2fgicfedc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2kxopmttk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2cmbsyrbt.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2vublxdvc.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2xodiszsr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2ifmpjujc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2hnmpboog.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2meafhymc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2xfisrrwi.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gt2fjxabwkk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2eevwmlfs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2wopzfmzn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gt2buyeavzp.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2rxavhpes.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2tlbboreq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2mtwzukmn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edfcvtda.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvdexwus.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwysznox.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2ctwwxjfd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2tfumuwsd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2zrfdnztw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2ylvqdrlb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2ywoyokdl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2xwkjylfm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2retridsd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gt2bylpfkdc.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gt2dodfcmmp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gt2jhcahauj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gt2ejktdjhk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2wbvwsfho.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2nfhmmgvn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2bzcbbfck.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2dhmajhtd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2dxbtsuyj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2sgakspbe.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gt2fyhkboku.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2zaacyewf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2nshushqc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2gwzuwpyx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2uchptcja.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2qzldpwri.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tlpgjzyj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2yiqdwtis.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2qappdwuw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2xuvepens.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2tjgacccr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2vpkktsfs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2gtcecrtx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2pwbuurrx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2eekzoxng.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gt2lxthtfxb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2acnzvaim.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2rccoezzu.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2jtozaxzr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2sbfzqhhi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2xyaapzuf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmceppnz.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2btqjuqnu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2yzjxadgn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2wancgovo.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2aovyehbl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gt2tgbgcsnn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2elkxbpgh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2siltqdul.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2xghjsyqj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsisruar.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2asbmqrye.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtyfqvmw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gt2rwfjhybp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2kqyqvsrm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2bviislvx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2skptbnuv.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2rwjgqrjs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cdbosapj.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2anysualt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2rccekkql.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2qglwlxyb.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2uxzzpnnp.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2mrhzopnl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2zyzxkntg.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gt2vrxiimoq.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2udxrsdan.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2igadsesc.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2lbuoxdkt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iajjitxw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2uqdjdqwh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gt2ncnqgnog.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gt2katkhyhn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2efspdrhy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2zohfbdup.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2icluaubb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2xxychvti.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gt2sgnlpqnv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gt2hceuoshi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2ntpnfkyw.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2lykksnht.html


<!-- 参考信息 -->