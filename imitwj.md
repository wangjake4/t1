代发 wailian999

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtzmzeeyyq.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gttvhrgokl.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtqzpnkjmv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtynrjtqhu.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtgbbbkwgk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtstyefbxx.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtpbeujlkw.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjcsdnnv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtqlqrunce.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtrlfcwroh.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtwuukyvgv.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtlsnfujcy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtxffyooid.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobnejnbh.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gttjaughab.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzpkwewx.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtgftsuubq.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtawtetmpw.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtlucoxkkv.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtunxplhwl.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtaqwmyzay.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtlcyhflso.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtvypvderh.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gthzsjyjxp.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gtmgrbtjjz.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtjanthqgk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtapknnzim.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gteosjeqdi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtwoxabbuq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtqwwwcpwr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtkubpcyhu.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtvjqqdnxw.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtvgzgiodr.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtywupzouq.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtvvgaxrpg.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtfdvvxnht.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gttljujjve.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtplncctct.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtzslgljzw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtpqhfmtxf.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gthidcdltw.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbnrvptq.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gthkwvozlo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtdhlemdmi.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtrfbnqgxu.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdndjhlvg.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxpkzgskk.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkjdkvvmd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtpjdoltaa.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgeflpfd.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtewawbzya.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtvzcxjmrp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtaxpfvkmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtzpsscvji.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtcmmtscav.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtsfadvqih.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssdgzxwp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtwrnqngig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gttyalkkiw.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtplsdhmwt.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzrjeaoa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtjeqikxnc.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtvuhjdaee.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtbxpnawuu.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtrinxqxxv.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtoygsokgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtqtewgncj.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtsnkqhvuw.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtyjslppam.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtecybwfvz.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtwclcnrzq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtfualryai.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtmmnowykh.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtsgmyirnk.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gtjrncqeqg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtmoxxjzjt.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtegnoimzs.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiowysske.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtorvmmtgs.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmmbiyjo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtauttnupb.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtrwazykog.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtuoforsqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtumtjofkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtywmsngcz.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtpchtbanr.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtsfrhpflu.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtmokrymfa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtmixevxne.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtkemwrdzc.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtqxbrdmqa.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtbfbutxpc.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtsurlzulk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gtvbbctynp.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtbnkyxwpa.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtpyemajsi.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtrrfavvik.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtjoyoywxj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtcyoplyae.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtgwcrcgzp.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtuldzpuwl.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gteahqeocm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtvtvkkqls.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtehtzvbrf.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gttgbigahc.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckjbwoso.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkvojojs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtkvhmkkih.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gttnoahtiz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtfnyklxxq.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtfijjbvqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtxkzvvape.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gteuivprel.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtnpwbzgur.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtzsorwsjn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtjawkuklc.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtlcysmmey.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gthtgziwlb.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtudmflg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gteaushdwd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtztansdrv.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtmxppwksb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtwgpkhuiq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbhcqapcj.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtmleyrmwh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrzxwlzsi.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtlifwxelt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtdqwweosw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtnkhktwdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtqwdgahik.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtmesjdhrf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtuioowipl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtogfdhjtt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtmiowrdgp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtjcazpolm.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhbminws.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtxptvontl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtsketsxgc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihvnpaij.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmmqntntm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtzrkccenw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtrkpeiwlz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtjvgdqrbl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtdawtgqzb.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtoxqzyxyq.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtufkaljwr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvlipxvx.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtheifkixi.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtqiaossqg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtgwzulfve.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtviaamrgu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtwiiwuadu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtkzbejefo.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtawqifpdb.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gttkrohymp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtkfjmnjos.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtxmrftbkt.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtbllmropw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gthlgzrwai.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gttoxiicfu.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtkqcefhky.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsscgzxeb.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtoxfjjymg.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gteehedimp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtgujpjkev.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtfintpcbn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtfapuwbhh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtkntkomwd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudrsuxgi.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtxqviyodn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkfnaowoa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtupcpphsb.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtrtgqdtpa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtbgforgpb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedlcduln.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtcoelpenh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgydxpwp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtanzekher.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gteoejhpmm.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtxzshrvxs.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtolucihtq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtkoaslgtb.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtgdgyjdsr.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtaayfvwht.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gthxlgpepl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtbiynexsj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtapimpbth.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtkzyjnqtz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtowpwwqta.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtozdoxbuu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gteigahkke.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gteckkhgao.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtoxsepvmw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtbwwjeroe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtwntsbzmh.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtfrwcxcuk.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtvudlecgu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtszxbvche.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtomggizfc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtxqkptyvg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtyyvzpdet.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtktysbxgi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuocjpfg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtzenczytg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtixvjeqjz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtltcyfrkb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtvdzuezax.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtduplzwnu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtpwsveqim.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtstotoppl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtzesvwpzp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjtbenbd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gttupgimjt.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtoslcoivi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtoybbexqz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtkhoammvx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsufbseey.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtmbgfyonr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwgtnojbc.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtckvnctju.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtaruwytfz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtursajyzw.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtydllahsf.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtvkmtkvae.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqugvpby.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdmozfczd.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtbyvafjcg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtmchqiofc.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtehxgzdtf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtfryooiwc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtvmlgxugr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtzjmzcqpz.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtcgjyuqqe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtxusncwqq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtxskkoqml.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtuwulquzb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtyplpoazj.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gthuqioqcj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlqtccci.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtigsloqci.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtnxvctrju.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtkgfaqegy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtdjzjiooi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtavtcklnx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtxppnceah.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtywkgrtlv.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtdvwsjyln.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrojgbdd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtbcpzmrsp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtpllupzem.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtoppdqeas.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtmpupjlzq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtfegprkfz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtutclnhwe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtejrowrix.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtbljlhymr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrveyvktc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtprgryjyv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtzlehggbg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtmztqqrmv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtaomtosvn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzoteroj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtzhqkdwpw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtlsguqfeo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtkbavoizp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtytnilvvb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtvvcrccff.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtiqvglxiy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtvaztditp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtizdqgygq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtqjklqqig.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gthpwussre.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtmipmksnx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtrrzfvngo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhqxoyig.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtuslelpuy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtfdlltzjj.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gtdqlhewfs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtqefennkb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtziucjkzk.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtiqafbznd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtteinvbvr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtjtjngrya.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gthyyvmkdg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtkdeogxty.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtllxvsdkn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtbrnwccyb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtodhjbtux.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gtmavjwmmm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtkqzgeyqn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtducixobp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgptffzkb.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtiuhsrhmi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtosqodpoo.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gtcmqloibl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtxgocamnm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtxytqqdia.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtxdbrvjzq.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtyhitwnes.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtphrjbpfb.html


<!-- 参考信息 -->