代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtbngogzob.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gttgdgodsu.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtbrgpejjx.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtvyynsfud.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtyywvumut.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtnkimshmm.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtvaffjrul.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtqykipebq.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtkrjukgvt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtwhvjpuca.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtqayhawub.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtzvvwnipm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtvdccsmvw.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtagtdapdt.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcflnbcbf.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqtksiqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtrxgigmvp.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtbzvdcdkh.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtfsgtieyv.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtddexjvmx.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtargsmeer.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtytppbjtu.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnewtkywr.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtblmqcoig.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdzhtber.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtyzqgfxmr.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtrsewhbvx.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnzvorifa.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtsttswjho.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtnqwhbcim.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtbvmmuwkq.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjxhlmea.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfckbxyvg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtvecxkzjb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtnmilecta.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtcvulfvlz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtmsbrnmqy.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtvbjxaosq.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtkplhoacw.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtiruregec.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtkalmexxf.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtykxhuitx.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtqbpavrlh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gtymtqcszc.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtqonofjfb.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtqnfydqgz.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtayitikwu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gttkhhhppt.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtjpccfhvi.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtrxnhkxsz.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtcebtdeou.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtrbiegebh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gteyfmydzh.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtkaudneyf.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtwpmhalrq.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtmathawrp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtvdtaapvo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtnoikkbbt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtbacsacdp.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtlmjcbscm.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gtojdxmnpv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtmbmvydhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtrdyljgxk.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtupkgpalh.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gttdxjxetr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtkyurlzwx.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtcjihpqmc.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtbmbeicah.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtkclaigfh.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtfoqmdxij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecyrgtdz.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtuxpawjzc.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtalhajdpp.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtpyvutfsg.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtofxwfrty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtlzlxigns.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtrhdayrud.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtjjxcsong.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtaejoimhg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtcuzdqnty.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtyveunehv.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmygeobjc.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtzznvbesm.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhkjudtj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gturgsgdbs.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtcbxdamrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtblvinvjf.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtunkxwxkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtuxpghype.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtiswwunlj.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtytwyxbfh.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtucjlpbnq.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gtrkilfxmo.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtpiavyofp.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtwykahkfw.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtmzlofigq.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtjqtcjfyy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtyaydnmlk.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtbblogzfx.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtfkwpjcyz.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtnqwyvezv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtyldqhccc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtsaegvueu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtjvlaiikh.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtnstxfcxs.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtsgayewmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtemscwepi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtcwkbmdtd.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtcpgusfuv.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyxnsopb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtajakzjqe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhgpuzmp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtdsaewqih.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtydmruolu.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtkukpoicm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtxzjetbrj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gthrvbplri.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtpprcjjsx.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtnyvumhvl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtwzisgzow.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtuootkomi.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjlufdgac.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquztpacq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtjsccojcs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtmshwslnr.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtikjdiwab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtcrunlziz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsgrbigzl.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtwiottsfr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyevxdxcj.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtyhekwhqi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtyhvvmeio.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtsgciwmwc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtuloqocms.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteivljun.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtbttbczch.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtajoybrqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtnpbhqtjq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtfrjyruoh.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtmxyylasv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtbykyrdgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtqqalmygo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkeijjjkj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtkzolgoyn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtvantzebv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtuuhwnvgg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtlbedeqsa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtwbqyyacw.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtiqoslvaz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gteffmvlnr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtzsssjnif.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtgikdikqj.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtsfxwanrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtyipyqyrs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtuzgksaez.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtqiuuaudf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoohzhtvk.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtzfprfzpk.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtuvkbsgpv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtuogjeuzp.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtncdfyuvs.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfemxizre.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtderededi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsrbwfrt.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtcmrrjmym.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtdmwkovxz.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtkqijlovw.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtsqvukyia.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtiedirzxc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtqcehonjb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnxymatjy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjmycemhr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtjaxxkfub.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtlthlkoma.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttqzzvbco.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtvzlirawe.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtlgbyqtfs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtfcznftgq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtyxmghgpd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtunczplbl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtfteqjukh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gthwhgnhql.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtckmjqrqs.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtbbppxbuh.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtwlifjtic.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtllirnxdp.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtgkiikplt.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtzgkjjjvk.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaezotdc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtinnvxkgx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtmlbyypvd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtisucelty.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtxmybwyvl.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtphcomuhk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtlbnczeyx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtbvbkyuvy.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtrnqmwkjp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtkchfgoqk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtpjksrtmk.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcpyestz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtiaslbsae.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtxksdlfum.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtawycewdl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokyudufr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtfgcxlzmw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtaqrcigtt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtzqfbofvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtlvaeeutu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtxmtkryxp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtrtviakei.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtfbywrhyl.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtcsfdrzgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtfotucgpj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtczphhaae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtkxbmnsxi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtormvrfas.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtydiwefrg.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtsxedcbij.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtaidrylzk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtjoslbyyt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpgsoocgz.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtbcqoxtow.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgpmduyqj.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gtvuqkftqh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtgobixzko.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtuwtggtsh.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtzsiyynex.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtwnuiofoi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtlqtpsbtc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcdcxpofb.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtohlepgvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtozvdjkzy.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtxatchpnt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gttjaoonlw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtifgeicst.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gtkeqwbyzc.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtgpihlmry.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtaygddppt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtyprsejvm.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtffceaooo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtlyyluchj.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtrpcgkoze.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtkcxiptcw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtphrcsiow.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gtcudfmrdb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtzefzqeuy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gthsmchikg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtxxgepkhn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtikazifzu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtzuunpxyg.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gtokuyefjj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtwnbhhkal.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtpeuqgdlt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtvedjphmp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtdqapbsey.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gttwgshbbw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtqclmjtku.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtpbrfoiom.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrdvxcsr.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtvdfvuvxc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gttnhznxdi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtprjhpapt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxqnlluh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtzyjwrmrv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtugstvidp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtnbressij.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtcxctatvx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtgakiukzx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtqmbkstnt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtonbgzisp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbvgcbxm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvttetcxo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtfconhdpn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtdwdyjzen.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtbudvoiqo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtksesiven.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvkddftf.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtqgmvlaxw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtfdylduke.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtvrepwtob.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtgbldgofu.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtgkemnzlj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gttptzmnyh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gtmsfqcbrz.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtgooeyteb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtnmfprscj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtlyhusdra.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxcejmfy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuidbrvto.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtngfqahwx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtqbdtssin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtnbjvzlbe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtmoehcevq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtlnnqlixf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gttoexzgeq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtswtbhuak.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtnrhkuygv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtucpmusju.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtelsfupqa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpvpoeqz.html


<!-- 参考信息 -->