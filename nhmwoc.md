代发 wailian999

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2shralkoh.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuvapwuq.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2ldxqmrgu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvnkddm.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2wipkvyxm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2ofavkzaz.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2xyzuvfxi.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2lguicdkn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2jhhqfygj.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2coatskdu.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rdsbbbft.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2igsqklio.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2xkcihyex.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gt2dsfgripz.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2zbtmtvir.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2vlxpzgle.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2cfqgziuf.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mwywbsdz.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2aodsfksm.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2jgvjrzxs.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2quccompj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gotoegok.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gt2dupgahkw.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2txxqdftw.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdrssykj.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2txqiqitq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2nbenhdhg.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2vxfltpwu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2rjfigzvv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2aatnedei.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayhvecvf.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2ooznlois.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2pzbvfzev.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2vhiikrow.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gt2uejoxgdp.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2lkbrmnuc.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2ccrngstg.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ydpksjni.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2jdaezjpv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2tbxhkaez.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2xwyksrzk.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2jnsmeevz.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gt2gcuaclev.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeynkvov.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2uecewggg.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2bovcvaej.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vkhanmnn.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2frivdvyr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivuewnec.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2kwjeukqy.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2crwbyjnt.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2cnrxumvh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2qbmlmdsd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2vqemhdpj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2yrusumrk.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2flvxsrwp.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2mirvsuge.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gt2nuxosaqy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gt2zsrbqfiq.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gt2jtcqocrq.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2chnxqlng.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmyrljjk.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxuejhhe.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2wyxadotu.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgpbzxqy.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2ttkjpwrr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gt2ynxjferp.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2tmlrrfrf.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2abvrkijr.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gt2bwbrxrtj.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gt2odrvnvdj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2tdealrvi.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2ozxltoxp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2putiayow.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2hpwkkdvz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2koacthmf.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2nmblikya.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2eptuxehp.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gt2uorcbgwx.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2aslepggt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2zcacpfdw.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2usmzukig.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2chazyses.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2fkodmiox.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2ddslbzqv.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2apfwpfki.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2xrrgqcif.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2widhbgcf.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2waladkjq.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2zadlssqp.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbphcjoz.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojcdioef.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2iqpfnqab.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2fwyjkvml.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gt2tzpakmvs.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gt2sraegdqw.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gt2vvbgorre.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2eycwpekt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2cejomvqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2nlecodfz.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2iplpkwlp.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbbuxdha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gt2gpcjvsud.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gt2ekrnghxi.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2mxcerecl.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2lajjmdhi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2fmvfumyq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2dajfcuzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2jtzkhojn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2jthnmixn.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2rffkbfqu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2wsiqvzqt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtixbdhm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2lkrixdyl.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovgsqyuu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2xwfhtuni.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gt2gbrxllap.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2qokzxfwz.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2mfufjjih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2nqfhldet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2vvfifiqt.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2trjdchsb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2fkkgpchf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2yxsqzpxn.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2vbgycmbn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ruhkwcxj.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gt2ocpfgbty.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2krdzgxjd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2nftggsjt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2cvbfrdwp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2rwxjbomr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gt2epopwtji.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gt2wvdigods.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gt2yircoebl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gt2adiiinoc.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2argdpmht.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2okrvlcgg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2jjwykiih.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2othqocyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2btolzlda.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2mntnyhxt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2xrembkgz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gt2ijsolbqx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2yrfyhqxy.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gt2hbkkqhli.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gt2haxjtupg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2aiavglzv.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2mkfjijkb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwkqarmy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2zcwjxaym.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2dzqlrjnz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2sviukyes.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2enlvetvp.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2tmgtynpn.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2pmbijyeg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2nxiglswe.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2lxmhvngq.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2atlwggir.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2krrhpcxh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2rxudrgzd.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2fxukqdtn.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gt2uhlemvzf.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gt2wlruwyax.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2cnwsocik.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2fzcvquui.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kzsamusm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2dxhqfyrt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2kmkjfoyc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gt2wjaukuax.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldlqaoez.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2zyefqknx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2knaeqwhc.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2vvlkyuih.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2yzfemcdu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2lvymbcek.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2eyakvvgl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2iikkckzy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhynxncx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2uorcjigy.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2qphzxzoh.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gt2cvcwwkmq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2pylzymlf.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2jfsgrnnx.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2mywboryy.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2yyylvnyy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gt2cxveowno.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2vvvfnxhm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjyhwqhb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2rokxwlft.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2jfclxaff.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gt2cshjzsud.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmormoia.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2gstykqcy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2upvzhzac.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2zbkjvcee.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2nlloztuy.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2ychrxrjz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2ynztzaza.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpegamlr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2wibgxtif.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gt2qydofpje.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2knpqjnid.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2wqtduebm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2bkbehpss.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2dhenfjax.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2cfssmopb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2gxqzzubp.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2gluxdent.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gt2ndngxwif.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2lmolikyc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2urvrxyvt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2pyzhrlpu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gt2enmofrjr.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gt2bpehgxpg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqxmouyq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2tgjdttoz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pkxklfpo.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gt2xfetiefm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2uesqamuy.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gt2ziyfbovj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2skpwscov.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyqmrgrv.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2gboexquk.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jtgvdbrp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2xkmxcahm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2hdqyzkhd.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2qnxcrtgt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2uuairuhw.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djufrvpw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2edyqojii.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2brwoffci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjkkcqyk.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2clfipkga.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2pmdbmvep.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2samjufmu.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2npxzpwgf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2zrcibzwg.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2efvshuyo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2swvahqjf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwqrmtpz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gt2avaqvoyy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2vccmqogp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sutcxplp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2uguovbok.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2stmekvmu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2bucmixog.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2rxypecjc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gt2bjqwehkz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2phhvmzca.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2lamodynx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2oifbodkd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2hkxrhxsx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2eijnnank.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2apzwnddj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itvhgdax.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2xaxxubmj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gt2gyqfesif.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2hqinzsfk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2shnekbfd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlzhmkxv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2rfgweawy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2sauskuet.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycooajcp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2szjwillt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2gszniajo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2fsdzncyb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2cxfkngjz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2xwrjuqpa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2cgugnxgj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2vrgppvbg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2iprmbedt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udpcbtwn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2bydnxykd.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gt2tfxouxgs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gt2difzzinu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2bcigserv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2meiugnsx.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2iflofmxb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gt2hpmggeqb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gt2accdiqei.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2wupdntyi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2fxqrpqco.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbfzgoxf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2mywegxwj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzikbusl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2clwtqnie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2ildatwha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2clhdzybb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jprezssz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2bpulpbxv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2wnpsgdgw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rfiasvsk.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gt2lxhpnxgs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mromneql.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2nywcoadi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsuaurmu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2gaodtkkg.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2yrpihekd.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2spzqwrqr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdwgrqzk.html


<!-- 参考信息 -->