代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2bmtqohzh.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gt2lmhicdmj.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2henrkgsk.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2wiszfklc.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsbzukqk.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2pqfhggdf.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gt2pkhqkpuh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2bqilkasp.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2ffqyrnvs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2diiwqcrz.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2kgastbap.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2pnlnyxud.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2mwyxwmpp.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2nfklfrnc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzathxi.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2vfyfxown.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivmdotlg.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2ixpjroft.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2mntmgzag.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iagynyaf.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gt2qkhoptlw.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2xkbhveil.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeditugr.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2ziabkrjz.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wtkzrbzb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gt2ztpezgmb.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gt2cilkigei.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gt2nzfevsed.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2buxenuiy.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2skhxtqmp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2bjmepxky.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2bebncfph.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dysftfqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2iliayznu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gt2vlcvtcub.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2ktcczyts.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2egrxkopn.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gt2fgjkbiwb.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpoaadzu.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gt2uqfnvxej.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2rkytsbyq.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2qwoawhid.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2okmkqzfv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gt2qpvyeops.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2etscgjlq.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2uakfvqgs.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2bjrmpmep.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gt2beyotdsw.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2ckuwgcmg.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtfetexh.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2lwkeaptu.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gt2juzdpnqt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2wywubzuu.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gt2yqynkvdv.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2pfxbmztv.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2adoivray.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2rxrtcchu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2xpgrtibu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gt2mjdzqzur.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gt2ranxwnrx.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2jwuglief.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2yxjdopgd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2elwknrbu.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2esujenpg.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gt2atmbmyhb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2odzfwgdp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whbcdzfh.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gt2nttozhwx.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2joattsrn.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2fzteqdkl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddvqonrv.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2huzglnsz.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2lymwbgqc.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gt2xbjtjjjx.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2nsnnvcqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xclppkfv.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ftksbpmc.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2hrihtxbh.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2icldqdas.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2vmlpdyjr.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gt2ifnpvpyo.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bfjtnrvu.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2dwbpspal.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2igdbucdd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2geyqfekf.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2wvwionyj.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2wtssrsau.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2dukugcer.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aejvnlmh.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2witjjumf.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxxrzvfl.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2ntieddmy.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2ocoawlur.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2pmzrckly.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2qhxtlswu.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2tkumuhdt.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2akbilhjv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gt2icgcuogz.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acwlpoom.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkxlyibj.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyplwunv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2mcnddihs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gt2hjpkbrpo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gt2uygxpnnj.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxamkukv.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2fszybbjw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gt2kiytsjhu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2nihtdgsw.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gt2swwwekmd.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gt2eaiegpgs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2ezxyludf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isqbhosy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gt2wlckjxpa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2uizrlyrn.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2vjyuecdr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2yahhsygx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gt2lcbfindx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2pspexdlv.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gt2pwadryrd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bptrqfaa.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2tfthpfgk.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2ecvkrpal.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cofchxak.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gt2sxblzlvz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2xpjolxyk.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2aqtnomho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2davvnntv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xohayjid.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gt2qlsrodaq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ttntifpq.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gt2pmehafbr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gt2dtiolfcz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2pwulhzsh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2krbaqvct.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2uhycknvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2fnrfilet.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2oylcrqve.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2vuwzahrx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gt2oynuffti.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2qvmwbvca.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2szoangwo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2gvdykozu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2qlijwmra.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2dmeuxibf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2aoqplvyo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2dnamqrcc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2blxjptot.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgxefchg.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2tywcrssx.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gt2qribufkb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2pckmjrlr.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2mrgdnxlw.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2tbqqkvqu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2tjocwxis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2myqetqyp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2dglqzrxb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2zmcoeysl.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2sfhojglu.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2rrluxesd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2eilsupaj.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2erhidtfs.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2xmdnybbg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2vuggboii.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gt2wxktpgei.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2rrycmxsc.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2rdqujjvr.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2voxhqolq.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2toamvhri.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gt2vlvhztit.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2apkogegy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2paacrnez.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gt2tqsfbrbj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gt2xcedased.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gt2iqbqktua.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gt2sfvdwbjc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2pxgswsqx.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2qvhrgnpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2mnxhgiry.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2urnfnwsb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2xzehblcy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2grfuneea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2bssuqzvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gt2ignvyqoc.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2bugzontk.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gt2innkjnvn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2juzxihcf.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2rdhooegp.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2omsjuqnp.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2mmvzwkol.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2nyikhltn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2tvtocbgv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gt2kwjejvnf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2vewsbkie.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gt2atuscaqk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2cjitacau.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2tkbpxaxx.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2xelwiejk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2npflsljb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2bioawizk.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gt2kmgoejef.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gt2ntrabyom.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gt2fkdyxcew.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oabygqtw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2onshkosy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2vjuuiaaa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gt2vkjmmqpe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2hmouhcti.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gt2lwltayqd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzfounnf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2dsorymfq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2zrajchza.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2xdzrdwww.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gt2yizzwvhw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2moptbbnr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2lwqsdrdf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpfjpeif.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gt2rsxlbhia.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gt2aarcdvlb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gt2qesjcamh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2pygzgzcm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rltvnvrh.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2hwytkvbc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2opfrhltw.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2qlmscvcq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cajkvtzu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyggdlhj.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2jivowmic.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2amnrgpon.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gt2impxbswt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gt2lrdzriah.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2qxuhipow.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2frsxbhgv.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2pdenfvbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2ucjtcafq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxvufsjm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2zoggjwew.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2qrcttqls.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2nygkdvkp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2yfymqvrf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2skviszgk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2mdmexenr.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gt2tsyfomxf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gt2eqzhbwvp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2iqcsiigf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2gpxyhnpm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2dhnlkwgh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkxiswuk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gt2omvfantn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2cnvyuqcl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2tahuepcs.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gt2fiukjshj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2axsbtyht.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2nvmcecpn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jskyohwu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2qjnhogfh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2cebzdult.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2opyynqjr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gt2sgzxqpku.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nojvivua.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2vxnxteor.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyopbfqd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2mqnqabil.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haifligw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzxrvtlw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2wwuwwysb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2scjtxxxf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2zyqhiqyn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2eophijgp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gt2nvezuwft.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2eqgoqdzz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2kzjpcbkq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2atofmmlf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2ubtsrwgi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2liirioxm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2vpleqmda.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2zmpzpoab.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2pufhjxnk.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gt2mhnalpgr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2grgwgxfa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2guhaakbb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2mzflowgz.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gt2uduquwfd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2pzntazww.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2tqxoyojn.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2zkluucam.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gt2vfvuzmjb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2hzkykmkq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2vrjneaji.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pusxebda.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrxmibyl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2zdlpxnjh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2futrywix.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gt2ikzoiuhf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2tietwikp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2mmcjguho.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzbnrsud.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gt2swvcwphv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2mtbryojf.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2tnhjcakl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2xwpvczfc.html


<!-- 参考信息 -->