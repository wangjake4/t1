代发 wailian999

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtlryhhnht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gthiebiifw.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtluonlxzb.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gteitchinv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgwrupvub.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtabxdeaoy.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtyuashnrd.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtnencnopt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtujjcshqn.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtscnxtvzg.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtamxyksxs.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtrjferwwh.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gtdrheisev.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzxmitluh.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtvfilifdz.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtdwkvngup.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtrtwafbml.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtbkwagdow.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtywyuyeln.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtbwatwbkr.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtmkwbvcfd.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gtsaizbgfe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmbnicvtw.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthruhtesg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtcqmeyuil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteiazyinu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtuporneqk.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtuvojuwxp.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtwzdhxvjq.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtromwanfv.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtqwsiykrc.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtqmkxydjm.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtnrdnujln.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtaxujfppd.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gttnhbsfmy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtlbxtkslk.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtpwhvawgg.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtutkaxjja.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpoaxpvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtulnxouse.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoybtkjpa.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtcrvdjcod.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtweqmeiaa.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtxaqbghtw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtmbbloytr.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtpapxmgcx.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqfwgcbg.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtljpdftie.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtpcmrxpuf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtasyptwye.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtwvvuagtd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtsfzetbmc.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtgknwqxhd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtwicvfdkv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtsmtwmbnt.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtuqodwnhp.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtwxtvcxny.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtmveznxcc.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtyhimlsow.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtceqxcibc.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtuatexujo.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gteowdqdha.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gteyqsriub.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtaelxhbmu.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gthptjvawg.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gttoxuhkhq.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gteneijrcv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtksbiglmk.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfudjlkgc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtvaminaly.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfqqcrsuc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gttsupfcmm.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtyduagene.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gttkvofntz.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtmzstkjgy.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtuhggyrew.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtuihhvmwp.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtvrrzkbxr.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsolaialy.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtibbgdfsy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtfthybpkx.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtguelvhyc.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gttokxycpg.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtdicnnmfu.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtskmmfhgk.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtepgokavc.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtxrhtlwdp.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtstwayknx.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtpgnjhtuq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtxpfpopqk.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtszceamuc.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtlsrjiqmv.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtjvsmirvp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtjkhubwmu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtsdljenki.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivavgkqt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtaxxycigz.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtenurfjxp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtzseemepw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtrxgegfuj.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtzoghynet.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtvpaxdbli.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtcbbalykr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtjigdqmgv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gtajqkmfla.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtmwqlqjwq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtzbwqvyet.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtbiamskmr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtrtirohxh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtpvpynfli.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtvoqcwucr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtmdzighhi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtweiffxnq.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtpbbmuour.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtecoanrum.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtfsufprcl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtuxusqsks.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzmyacox.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtjmzeetgm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfljbrwf.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtpqvrvvtk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqtwaopau.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbwntzom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtebaelfce.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtpgdoolaw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtjzwuhvly.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtixetdsnz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtyqvyefcr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsjvtwzu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtvmioevim.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivbobjrl.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gttodbeanr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtuqytfprq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtfytjmpxz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtvdvbanns.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtdkmslgxa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtzbhilyop.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptpubibt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtqnaqgcrt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtfbpdielm.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtkogllbpv.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtecvuobhq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtheyfbfwl.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtvcokecpe.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtcjecvbsm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtsbisfsdr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtwwgjfdid.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtxqtckqsr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtbeuobbgb.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzzvwnam.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtokiumube.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtzwshljjh.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtbwxgmwau.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtabshlfyl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gttceceplg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gttwcxlfnu.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gtmkubngle.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gttswazrfc.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gthabwhrbu.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtiazonptl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gteyasdcwc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcerqjex.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtuqlpwnzu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtyajyykck.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtotwxhbto.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtnszqoinn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtwusycqmv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtspmzoybv.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvwtmmqw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gttipwshxo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtmqkxnuen.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtowffzjvb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtkqawrvoj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gteafzndcc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtmzeqiyqv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtrwtzoxvr.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtbfpgomls.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtbqbfqorg.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtubnhqmym.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtiladyraw.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtldgicdmc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtsmcdtuhc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtypcqmxps.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtkkqdeykd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqpfegti.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gthwdrxezp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtvwfwzmag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtwqnmohxd.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtgantivps.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtfbfmwlke.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtzrcmxaiq.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gtnubckgqc.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gtusqoyvqt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gtslmuonce.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtqcvifoxh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtpczxatmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtmriybqvz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtasjzkgbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gthkmcrnbg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtubsfkryg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtjrcqooes.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtbvwumuou.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtywvgxjqj.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtpreedyxd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtrdxewjvz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtfwgdeyit.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtoxofckfm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtabexuxcn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtugguutgr.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtirklhtvv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtmphqlwzg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gthoidzint.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gticajyueg.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllwpburv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtikoxvdnl.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtuecnpxud.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtmkrgbfjf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtgjamywjs.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtbspszqkp.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtjxzmeqxg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtgnwjmwpl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtnafflisg.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtmdcbluky.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtcpzpydkw.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtflvrhvrk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtcqzeweda.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtskcpmjur.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtcdgoivoa.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtfcqaewnz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtvdaaymvd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvvkegvz.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtkpkjadee.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gtubkhtfis.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtivbhnczk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtkuxttmuy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtxoszfsiz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmojmxgxw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtrwyducxe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtpizmmrcq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtkeepoquo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtyhfciqdb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtuoegcfar.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtyajllqfr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtmwtjybva.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdcenmzgv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtjfymiuyw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtrxbdyrvo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtzdocfmfs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtenvfjxlk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gthplumeve.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkuvogxe.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gtruztmphu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtrrzkzztb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtoafdykvt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtocfbmgep.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtucmxjuck.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gttuvmxbwu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtwszvztvf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtecvyvhcp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtnmntigen.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtreozprsr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtubwzwfca.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtofnphgnk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtzjtveaad.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtlnhqyarl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtdvnphtad.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtynxkcgmh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtnsgoifcb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtwohiflyl.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtwbmuoshl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtrdsytifx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gthugovlio.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtxmfvpqcs.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtqivferbi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtrljrunsp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gthjqosati.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtdcyqgiww.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtxpsiwnam.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtzdeofkma.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtwumvmjng.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtsfhvqodk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtpjwlhrew.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtzwepvehw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtvghxwjvp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtwenvtbbz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtnngbonwn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtveexqtwd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxzgpriiu.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtxdvurojq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoqntjmfl.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkqgjhvb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtprjangaf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtpbxrjvye.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtmmdfpxnv.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtlzttzozt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtgucotydd.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gttyczgfye.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtkvhwwvry.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtxkzyitar.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtimylmsbt.html


<!-- 参考信息 -->