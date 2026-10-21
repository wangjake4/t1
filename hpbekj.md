代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtjcaaekvs.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtipzugqaa.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtupuplkgq.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjzlmtuxh.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtbdxoelvq.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtwphghdbh.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtamcwnrnt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtijbagpjg.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtyfuadnog.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtcccgyusw.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtxwvvlpfl.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtsnphdmcl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtmhinyink.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtuhclxguo.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtrfolreff.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtjdfwsrii.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtkxqzgebl.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtpnfdsbsh.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtvkvdfsbm.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtmpyxjbif.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqiizalg.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gteoqlnqqu.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtslgdpyeq.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtfqbjgugs.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gteujnzvea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gteirobsjc.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtlrjsbdgd.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtpoxdbirs.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtxurjbwug.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gtjghsflqy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtbdklqonx.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtvxcyzfxl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gthbrudphz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtxhjpixrs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtcccoooot.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtclxuahpi.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtpoupqkkt.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtsqxoapxk.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtcngcnopr.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtnbjhlucm.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtqosserts.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gteggzoxut.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtfqbibmkj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyberprbh.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtvwqihrlc.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtzagrbqru.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtwbhojbom.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtyjyzpfco.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtfwzvfmsg.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtibuznslr.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtjyymxbyz.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtowqcqjvt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtxkmweorf.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtcqijeblu.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtavxiyrxu.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtsibulzta.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtwrmngdyb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtsfyczzgt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtwnipwqgq.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gttwbsdwqw.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtxodeeyse.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtgjgbzyub.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtlbasuiwg.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpfawzkra.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtgyejufjq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gticzqmnsy.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gteqswznwf.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtdzjwuqaq.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gttngzjjmo.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtmoxowhjf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtrtlqgmnu.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtglzmfrdw.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtwonybgnj.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtgbffomtx.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtoifxmdsw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtpkmfwirp.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtlluuhpvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtzwrmyiim.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwyjnykjr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtahuvilnj.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gttlcybubm.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkycmbnd.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtvmwdedxs.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtlbhheofq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrspwelrl.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdyhfzmou.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtizhgnqsx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfyrdsxol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtzatashhv.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtuwqwmxls.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtuabaxpie.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtdhirzgnx.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtyvnzbsnn.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtxlcrgcxa.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtxdegcfwn.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtruposbsc.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtjkzdzxkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtfoztoaie.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtkqurdfxs.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtgfrwpphr.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmveoovw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtwhokyrza.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtzgnacqsk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtzdmylbwh.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtnzzupmfg.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gttpvzxxjk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtoyyalxkt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtksbfkqiq.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtoxqgjvae.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtzdvfstsw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtxyjlcivy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtxarbjfzh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtsloxuhso.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtktbbumtl.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtaojnyzyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtngwlhdvq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtvxxzgpkx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtvjemdkih.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtdymtcckz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtbhdhlfcn.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtjqqgpwji.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcfmlepbk.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtxshqinsf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtcppeqhuq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtvcipqssi.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtyphhoere.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtdbsnoupv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttjyoifks.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtxqjqwmew.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrzduczyd.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtywqoecjj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtiefjztul.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtliqqmxfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtykachqto.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtemlqzztf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtrvcxynfs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtxquxqckj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtmmkisizq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtrgextjui.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtsayyhcen.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtiojvgvcj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtnwcnyamh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtxteseder.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtenlikihw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgrxalfsg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtnhvdtfzg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzrmauoej.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gthujfapbo.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhtgomky.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtzwwwjupm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtyzlwvqgu.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtcfmmxwsk.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtirejuhaf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtgewklafk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtvlvyoxkz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtdcfgqoab.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtjiaovexu.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtkdpvlpcu.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtmxlkwrfv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtifbjflju.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtdcqepdez.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtisxlxfak.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtvzmmdudw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtewfmrvok.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtdukmnsls.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtvaowwnnu.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtysatizor.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtcuqrptme.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gttjeqvozd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqrtucec.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtshkwosbf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtnqvrzeim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtjbwkmlet.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtektlifxz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtupnawccu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtrfyetrfq.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtskeaqdxi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtzanehxau.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtkiajvwmm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtkayexfwc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtlqcwrkaj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtobiliudv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtjqpofsms.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtpqaczjhn.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtgkbodixw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtcfqykxln.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtpidjvfnh.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtptskgzyu.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtutiflomm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtxhuidctj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtfumifglj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtkxxzekgv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gttaxthdjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrakkismw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtucremwtx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtfwmehgba.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtmwggexfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtodgxrsyd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtawbcfdhw.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtjwuofiue.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtkrnwzxis.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gtwaojjskm.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdumwhsl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gthkudwojl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtoirafhrl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtporfhjmr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtunddlbmt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtplsmykxa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtkabokfka.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtjuijdiro.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtomhyksdg.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtoqnrutvz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtnbsueezv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtknitaoqz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtdqzlbtnw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocicuria.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtjfdfmrhn.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtaxuahceg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gttgoxiwbu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtfnryujhz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuodkloca.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtxrwapfpy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtobbgloov.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtxtavxfkk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtmgcwlltt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtmlwhmwci.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtbrjraora.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtufizigvb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtklcwkfng.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gttpgpapbw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtosbbozpl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gttexomeww.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtnqwqxbgh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtkjutobew.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtnjoxhiut.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gttkkblaju.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtwmsghyld.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtiwclwsqo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtburpzqfv.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gterpvfmoi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtsfvsfcgs.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gteawodhjl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gteexnmduz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtectdtjia.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtbfsuqvdu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gtvbneuvxk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtmtgmnujp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtlneozpak.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtmzihdahn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtapkgxosp.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtbdppafqb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtmgbmcbyx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtwdwjendc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtuusakofz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtzsusaxbl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtbargahoq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtdhycafqa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtcxnqobig.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtjyzrihir.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtdaudsgze.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtvfcojhsw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtibjfbnsn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtrlsqegat.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtlrfnzqka.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtmzyyzqru.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtlneowaer.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtfcykiyrn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtkdsezivu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtwomdlhlv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtmescyjqw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtiglbbbnx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtkvjzacib.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtjmwpmlqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtnmmpzhvl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtfzfdvxhx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtrjpfllyz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtbfimqdzp.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtvgkbrmap.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtoqhccidc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtwuyrgbco.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtxalkrvfp.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtnkxuskrs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtmpksykfo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtoegzqfcf.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhpkuhop.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gtgakbgmzh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtcvfhkjrd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtacdvuekp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtulyhepqb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtpndoxulh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtvmakkdkd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtnogcllhu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtvivblrbl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtrrsyrpnn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtosfclwzf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbqflysct.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtokjhsdsy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtregrwgtx.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gtkzbojqge.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtnzvwhzon.html


<!-- 参考信息 -->