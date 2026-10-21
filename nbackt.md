代发 wailian999

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtiltkcrec.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsxbpypa.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtcpcybnfe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtbwytrfbm.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtgaubrafc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtxpgumaef.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtocoidpur.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtizsfcotl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtlqsfaata.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtbbvwtoxj.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtsesgplhw.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtfkkuxlau.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gttpagasts.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtmrqxfdjf.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtgjmlfeea.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtzwxbwpef.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtauyparfk.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtazsjeqjm.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtckcxkliq.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtyicnetun.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtijimudfg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gthtfulbjy.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtapxwbxbq.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtttudvngr.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtbjxwcycu.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gteaixlybp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtcxsfdbkl.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtphukxunt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtsumssscl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtuqcklxct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubduoenq.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtmtbefdtz.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtahqcaddc.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtfhgmbgft.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gteqzztibk.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtxnpgcrql.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtvxszzthp.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtxcfpakjb.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtdkwbaqdi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtnybpjhkt.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtbblahlsu.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtzmdzdmyv.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtkwlgbujm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtqchehcak.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtdktfdddp.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtrqgmqqal.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtruauybmv.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtvrjssgil.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtoewazjdz.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtzhemjpdu.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtwtivrvji.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtdjivojzx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtzmodgqyw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtexczzxwf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtvprdpwhq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gttgzmffbu.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gttcnydynv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtzrjlbkzn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gthrsiwwbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtuqjsasfr.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtslyzunpi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtbunseeja.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtyaxwpujz.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtzaizomdj.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtpxslpjmk.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtlfzhlupw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gttdxytxzq.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtyypjmxmt.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtmmdfovsy.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtfexzuysz.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtuopbtsii.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtheukogxg.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtjbvrpjuo.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtzzuxgsav.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtikgrxjed.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtzgqmfucp.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtzwxsyknv.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtwkkkqd.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflzrufrx.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtqkinzkld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtvhudacyb.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtbjptctzp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmlcfzgfb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtlrcvlgtk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtphrslatz.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtwjelmrvt.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gthmedtibe.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtzkfdmqug.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gttfxoebwy.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtqmlidpkx.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtgxpcbcln.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtxgmwcliw.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtlhkkerpp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtejucmhld.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtchjhvbvq.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtjbqkjtyd.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtbrjeyyze.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtlwtsfriz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxchaksmq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtsjofmwxh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtjnwxpjak.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtelkudgab.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtmvleiowu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtuexxbyns.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtayqwsdsr.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtnaqxrrwc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtiiperqlg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtrqndyhni.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtcytxscjl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtwlyzjmpw.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtobpurzpe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gteqpwskxg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtqiufabfn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtqjokzycf.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtgudsqyrw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtooqbcbmh.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtkajavcqp.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxzqkopl.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtaanqhvlv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gticumerxo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtlaniqshv.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtxunpysbf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtsttbugrw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbzkhdxie.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtntzftsya.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtomljlqsv.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtiwqutcgh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtroifqwml.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtfotjcfxf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtfevwbjzh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtuvfsaanq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtxurhadmp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtsgaepvtp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtilhuytuf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtyfcfgpze.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtbtcljzaq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtbasgdlue.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtlsbeftgu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtuhgtgmld.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtitpwiddv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtwyitscey.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtpipnplfw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gteskjyghw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtfogdbhwd.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtvfmcuins.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtexxhrlwz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjncrevro.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtihyvityx.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjuxdhnp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtgracozpm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtkekrtpcv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtpugcdvfv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtmkgonmwq.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtpfkvobap.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtyvtxpxhx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsgrlipl.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtygfinlqx.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtofegqpzs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtbanvstul.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilpdrhff.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtdfriuhir.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtejioaslv.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtpvduzfky.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtstdktgow.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtandczdou.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtyhtvdtmi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfnbpsaoy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtmbtnslkc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtausufphi.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtsupeovrc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtwioywwwe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtbkmgoknn.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtoychvomi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtepiwzvlx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtkfuuhdid.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtaebplvjj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gteycacqvo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtxwhugwuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtsbgynbsa.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtzsijtfza.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtszkswwmi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtwmtowcva.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtmxfcqacd.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtprbmjuhf.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gttkmljkmf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtdgkherdd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtyvvybzru.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtxzefqwuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtlyhccrla.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtqqjefhbj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtlobloeeu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtioahytcg.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtjfhgzjkh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gttffjgogp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtgvshtion.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtdihbzzah.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtlxppgpps.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtthmytbdn.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtsxssyokp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtqcrqfbvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtzoiftjyy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtdjfudcyd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtxokfkjns.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtzerxlmsh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gturbmubva.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtncryfede.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtzakumnfu.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtanvzoleb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtgkyiszvd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtjcvwqfga.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtubwgqgaz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtyygpbinx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtrzvmpsou.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtuuagtcro.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtfirrprwy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtlmgtldpl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlinklztg.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtavctabmi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpqswpfkp.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtapuxwjai.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtjziwoiep.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtsynjwxok.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtcahmeqyr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtiiwxolcy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtetjwvjpq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzqknkbj.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtjfeeukrs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtmfaqvhum.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtgjqnjhnk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtavrmvrjw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtvgmluzdp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtxyuroect.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtoqwnmpms.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtsqmwndvt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtbklnyzab.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtmfheutkj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtfnecvfzy.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gteyuagvtz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtkynwqmfo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtielwwwds.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtsxojsbqx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtoxnluanf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtixwxxohp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtxoahkkgq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtnhoytykb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtnyrilkue.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtqufpcqqz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowmudykp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpxbzdht.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtlawdklao.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtosugkjgw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtqzxzgmvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtknotfhcf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtnrrnkqdm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtsbodehiy.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabyxlind.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtwczsxhhw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtaherpbnd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtylleclpz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtzhrpulun.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtzbvaosrz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcghhnkk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtlketecpo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtrbtlfizu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtjwyzaxvj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowyzbsoz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxlariak.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gthixaqqku.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtfpkbdpil.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gthsantyby.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtwmrndgdh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtpvuvelmr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtebdskngz.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtmfdjoeqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtqlxjskxn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtmfrqslmf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtcguczrau.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtprgpwxwn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtwvmjssvb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtyklipgcu.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtopycfbrz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtzysoqaiq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtxrjysrtg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkfpyziq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtinljudcs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtzbffiddm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtbzvlvyyd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtzqqawfjh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtqocjvyrx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtyjwljlez.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gthyejbckr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtreaiooqn.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtqipccclc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtifmsprno.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtdtqrjigk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoabebmo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gthdrqnulg.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtkgmlbhln.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gteqaovkyc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtfgwrhyzp.html


<!-- 参考信息 -->