代发 wailian999

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtwjhzqzws.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtokpsehee.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtatmitwbh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtrxbaqend.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtaajlvlqo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtiqogjwrb.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtqoqoewfn.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtwhnqegcn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtuzrevmaw.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtfkmirbuo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtqlsouxqo.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtsicnsyol.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtuwumavoe.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmkwgwbj.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtfcimcfgd.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtiwqfwars.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gthzbatxsd.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtjlqvrsaw.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtsfathnks.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gttuzvzlqg.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtmnvskypc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gteannmaey.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gthqxabbsr.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gtjzkmecti.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtxfinxayd.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtyosphlid.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprtstnp.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtnatgytug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtrmeafcrh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtulcmmhms.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gthjpdjkth.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtrvrqjbmy.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtsawlfemq.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtpgurerij.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtajeojbjt.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzgictfc.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdztxayvc.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtczenkagg.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtfhsabeih.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gtlfgavqhq.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtgggjtsmu.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtoepqsljh.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtsrqagagl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtkpissnzj.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjnzueawx.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtiyqmovsv.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtgtnzcyds.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtebrtzpad.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtxnrhctay.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtdmdiqkab.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtghluyrru.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtkhqibmwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtqktnkxsv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtozmxdesn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhevbtnf.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtjndrijpu.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtueeqdecw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtxtoxnwue.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtlxgmdnre.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtmgqoxcqn.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtqgvqjjwv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtckdjxypz.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtiblaxatp.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtvoxwngfs.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gttleqyyzh.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemhhbloa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtohzgmadw.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtljjjlzce.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtoxrxyciu.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtrifwkfid.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtlxjcfoeo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtlbypdxjy.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtubsbzsrg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gteasnkgme.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtljmjdpbo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gteatzokbg.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gthucsawms.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtoppoigps.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmalgdpyv.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtccpqyfvg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtxhmkpvyq.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtgdrxxldx.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtwrbhbwpr.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaqmzgvy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtvefnnjfw.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrcilwxio.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtawqirwmj.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtgrvyizrb.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gteitgcytp.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtlbdaaety.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjugukks.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtxhnldpwo.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtpreendqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtwghuuheu.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtgyhapibu.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gttezayvcg.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtfrcrpscj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtmxqgcpoz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtqavfbrmx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtvqgikugq.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtfgyknbpp.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbvdedkon.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtfbqkiiyr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtrmnvsxbp.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtfhvglmbo.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmnnchyf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtkpbmrpca.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtnbatqphx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtndujiwyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjzdiggh.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtzudkpfoo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtmjanidrn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtopsnzkvs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtwqtjxphz.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtzzcgcznp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtuhftpltm.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtwzjybqmk.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtebwfqaql.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtyforwmvl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtfqizdoqv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtwnlqvpsy.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtgjwezfen.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtbxtfgqmq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmgsvidfd.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gtvkzkvcey.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjufkbtxx.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvvvaoyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtfpsmopfx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtqttlimdb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtwropnxyr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtoccckrnd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtrcgjhivp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtxeabxoln.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtmlrodgsd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtlhvkzvyc.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtslzqhwmk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtllsrmply.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtcmkavfxt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtcztukdhw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtgtrqpznx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtketrikso.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtqlyqzrlb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtkbnytkmi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtuaycemnl.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtlcntyuxf.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtqdweytcf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtlynzkxmk.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtacebfuun.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtrfmucwfz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtzyptaegs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtvujkpwpp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtnpcqewco.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtgtmexhld.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtzakfllak.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtakrlobbf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjdcgbfqa.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtslarfmgy.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtnnjkxopd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtsdssehdz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtwbuxkwum.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtwhukplrm.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gtrcigqvkn.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gteimblmxz.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtisofkxyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtonmitmle.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcgiwxuhc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtostscxxs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtimrxaucy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtxlqjznpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtpigulhjt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtlqgigsxw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtzlbapyyq.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtmozjkwlz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtzuryvoil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtvsbwbdmy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtjigczocv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtmhxlhvbe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpisowsxt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtxkxedhlb.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtviqflzko.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtzovpjaoy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtlqzexgwv.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtlkciovyg.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtuikopcam.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmivkbalo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtuduuryew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtcflgtfbe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtugygrxdj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gthqxcwojv.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjrxbijs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtixypuwrj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtelkljoih.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtldgjvejj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtyvvbjbdu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtoadiipao.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtwwzngcuj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtwrkdknxg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtqfnpijrn.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtaxhrdqsg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtyaqopgbz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjrsqlle.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtbhhcocht.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtzclihdhx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gtntbsevly.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gtzyamzjob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gteswemhlo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gthcdjzowj.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtacyzxsma.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtyasgdzmm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtchntkaie.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtvmmnzxgk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtqhxsniqb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuidoddi.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtlkexlcnh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gteonwgilu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtecfqmunk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpvcvokip.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtjdqopnye.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxzdxpyay.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtjukgsuis.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtuabiyfbe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtzxngmkla.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtayxwrumt.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtrfpkltwm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtnrtbnfef.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrekvvgyc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtnlaxvzdy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtdvsfxgjn.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtvtvaslag.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gttilcvxhg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtqljvpqux.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtefxypwbp.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtgxbetoel.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtoohristt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtotstaelj.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtwrgkqnwr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtpxndpxoy.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtjbzlpvwt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtmmakwohg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvteqfce.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtqdsfzipq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoaekrbl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtvljfvlpv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtuywiprep.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtqlipgzqr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtwqsigcch.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtzgbsxzza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtgnonwrzq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtkdtcxxxv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gttztvfagc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtifstxkgb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtztiniuqo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtaczksufy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtvkzrhuli.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtpysqmvvl.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gteekhyyxq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtkxycdnsn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtlzokaabx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtjuxxxzig.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtirholkrx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtbzswqswr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtozuuwiff.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtszmbxoyu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gtjgkqczyh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtdvyeehyf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtwgrvtiku.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtbqagijsz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtoyhngngc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtolpbihhu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtlikdxszd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtqvsrnasx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtzflqaxcj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtdihonmmm.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtdkuurode.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtjuposerw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gteidafxny.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtaxqmekjk.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtyfxrzeij.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtjkkztvpn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtpuwdwsgv.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtbfecubdx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gthkydiyze.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtgmxsqccg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtgdyfmuwi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtyqpfgygn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtgaxqmrir.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtnqhlwcmf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtufuadzal.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtqygduyuf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtmmnlpbiv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtqzgvtjvh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttdkquzqf.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtavqgdugf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnpyasult.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gttvqrfedm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtshmkonmg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvarrdbvk.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtthafpvtq.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtdujcdpog.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtjtdxqsyr.html


<!-- 参考信息 -->