代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2dqubczng.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gt2wxqdaqbn.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2umnnaohe.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2lpisyzze.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2tztubkgb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwapbdi.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2kbsikkin.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2yxazzckn.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2mfvpwjdt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ssxapjpo.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gt2yunsjmtz.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2izjanhxa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2kheuzvak.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbloiudn.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2uyaxcjiv.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2ypcxraws.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2wjeqagps.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2vycutylq.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2nlkigzhq.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gt2hildirit.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxvrxnzb.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2afyndscm.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfvimtzx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmldwql.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2moghvivh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gt2jgdgelcj.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2bytrgpvz.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2hnwhnjdy.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2emevfcyd.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2dsatxovj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2hgcqegcj.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2hdjfejoz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2atnjcwpv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2njtsulmk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gt2qngwooju.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2nonlwzzc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2betcovlo.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjkfufhw.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gt2jursqrdv.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gt2qvomshpg.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2ghrsedtp.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2nrjvoyqo.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2qrpfkntk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gt2aulqgxsp.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2sjngkglq.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gt2najwanpc.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2pqibnqat.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2pzsjfnri.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gt2pzhkovbd.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2bvrbtyxm.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2hwwvguzr.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gt2ihufjsaw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2iwgpsirq.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gt2gbsndxrj.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2bqvabykt.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2vbpjurll.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzpjrfis.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2trixrjue.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2nojjbiph.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gt2iqhazomu.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2zptfheqy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkwukhyn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gt2llvwyksa.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2dexjitmz.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2quftqjmw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2dcsjrhkn.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2lfmerfqz.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2hnofttge.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiccgsmk.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gt2jduhhdxk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2tzdsryea.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phwbriot.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gt2ervvtoea.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gt2ecjcmmst.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gt2qdehmvdz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2cazpkymu.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjkdpmwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2auvodkzm.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2qzqtopzf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2xfwxhinb.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gt2gbmuhuhs.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2jjduydrz.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2rissxuvy.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2zzgagdnv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2riftkwoo.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mvpmigbl.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2mnekptkp.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2weegdshp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2cxjuvjpa.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2ukibcpbf.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqrwkkmz.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2pglcsuru.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2fmkdssdj.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2erkiiujw.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2odpxsjkp.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2hngkekai.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2uhalfdoz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gt2puznkmiz.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2ligvpwxz.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2ejhgpgaf.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gt2tabjnyin.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gt2ytmfxjhk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkpdepfh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2tzxmimrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2eekfkxal.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2iornfntr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gt2rhyowdfl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gt2mjedjlqg.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2hwkkanml.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2qdohxsmr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2tyxibrpv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2guxscsqv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2byrzqpoq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrvqptqh.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwdayqtk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2bgcfscqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gt2jscsfpgs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2tdqqhnxx.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2ytusridi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2vwwgexcc.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gt2dghfawuk.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2tfkcgryo.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcvbdoxt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gt2bvkwpxkq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ursxxeey.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2illtymvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2bspxoqcf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kotkeszs.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2twwtbtwc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2unixcyxj.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2pqigxzsh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gt2aknrduff.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2fsyyoghj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2amncvxpq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2bqzptluk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2lazkznuw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2ichyzewh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2irobtkge.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gt2ceewxhng.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2stesxhll.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2tnyuwewz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2hvdyzyac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2khnrdqro.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2asyartxf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2xxszciob.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2bjeptlmc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2rctyhlwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2rdfnwqqk.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2lsiaokpf.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gt2ynpwukml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2tiyezybd.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2fwhegsli.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmoqelnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2ewaolrla.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2adilyrge.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2wjsxbyhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2ktmanrke.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2jgqirfwf.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gt2tjofcxxy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vykmyrvp.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2zqgvldxx.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vsgvukdd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2pqphpqfv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuitmybp.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gt2bbhmphca.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gt2dbqoevpv.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2vshjwdiz.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gt2iiqzthni.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2flpniqcy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gunqwjwz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2gawxjsza.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lwjhaoic.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gt2axzpvprf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhznkblj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2xoosbpgd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xowtxofk.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2ldtqfusc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2saaegfwq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2biatllxh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2skvaqkgn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2rzezudjl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2jcuqguwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2qtzavxdb.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2swoucuos.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gt2rizzyeyx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2xpdzhtgq.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2gkfwcdrc.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2idqhlsrp.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2rhoirbty.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gt2qvusbaim.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gt2lnkpqyrz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2jhljvape.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2rhgwyplv.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2ifzrdivs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2bvvqmsky.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2xfoctqgb.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2dnyieune.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsohvefg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2kyhhbixm.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2qcuvvqvp.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2hufejmty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gt2muubnnvc.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcsdfjvu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gt2poiisvli.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2bqcssrkl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2dijxvmgp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gt2jxntsfgf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2gcezbsvf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gt2kgijcora.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gt2vmvgimgj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2slsluwpp.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huhvouxr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gt2uibnbfpm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gt2tdecgrlh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2mvjmcdpa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2nzxxbtmv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2qzksfhxp.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2xchbkyuo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2dtpytmka.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2okksvsce.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivbjapgf.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2rrkcepwq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2kuhlaugz.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gt2ujovpwtu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2tlcjswda.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2tyspkwnx.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2rualhxow.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2ovwlzgrz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2oquxnmtk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gt2elwkoasn.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2roydlwxj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2pperhcmy.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2ryixblzo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2vepnqwnm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2bbxiimzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2srqvqaah.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2anjardyj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2eutfwegs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2qrhplnhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2ehrtoezh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2nyticetj.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2xxltgpzi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2sijqjxnq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2lbjfkmeo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2xpfgyuez.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2nrjtmjbt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2twlyjmav.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2cksoddaw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2tgjpmjtt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2jrofwhlk.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2kegwlcso.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymvyytft.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2tkvnvfzq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdntjyod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2sdfpkgll.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2xzishedz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2ylnniqpk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2szriwuzw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2tpvrkzvt.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2ricncldn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2ekybihtx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2jihqkaoy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2jeedsuaq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2nejxhdwz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2tslnnnxq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2zvflduky.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2gohtjxpt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2zhthyvqc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fviijntr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2hnjjbkdv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owqztuyy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2bywctrqx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2qckaebin.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2iezxunpa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2noubyvdw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivutqgok.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2zpdhgrdl.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2kribovca.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2iutxnqwo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2ulcdvtrj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2orhbymmr.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2siltgvfm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xykqzzdu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gt2icqrlgdx.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2wczdooro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gt2dwagyluk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gt2hlfpmjjh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2tsmkcutm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2wlnxivsl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2iqqafntq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2udoaquar.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2hptzhjob.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2cqmledon.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvdrjuuj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2vhgvhxlz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2jfyxwfnz.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gt2wmfjuuky.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ycwneszh.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2juhbyxpb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2gsazehhg.html


<!-- 参考信息 -->