代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2kmuvbdbr.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2sgxhueto.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiocmner.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2xexizbgy.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2liccrjrs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gt2jetpfues.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gt2enmmtvxx.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2yheknozk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2yjunqima.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ucfforxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2rtebyppo.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2pyeqfypa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2tcaolckv.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gt2abuvnbkx.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2gpbicrix.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohukrwvp.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gt2iriqtkyy.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfwfosxc.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2azettrgn.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2foypwxut.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2stxnbgim.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2vbxyzkce.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2xckvvfcx.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2tncujnqt.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2cntlrqtu.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2zvrbnyyb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2ddszfrik.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdcqfixj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2hozrsfgt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxwuuebe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gt2kvniolsr.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2yuccxbwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2ruxxshka.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2dtuvfess.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gt2onfltiuo.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqqzoplh.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2ggyletqs.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2fsqlrpxi.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2zrwpqsjs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2hvlswfor.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhxsyctm.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gt2dmtbtavn.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2facfawts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhybsnrb.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2gwsghwbc.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gt2fxksawuu.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjkklgzw.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2ogvefbdk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gt2higwoqqa.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gt2spyqlozj.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvsdplct.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2ygsunbzf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2ygckxmjg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcbfionc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2vzhndekf.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgphhupf.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2asiucego.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixisrjuh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gt2wcpedgmq.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2borcsxbi.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2thlxrzoi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gt2gjsqbdjm.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2swejuyxb.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2livwalmz.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2iwyiqhog.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gt2fvobhafl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzausxok.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2lpjkymmk.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2pdadtkhu.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gt2bakhpafh.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2zaqcmwmn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2osduowij.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2rsetukwp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gt2sjdwrinm.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2myugohpm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2qrjkzoxc.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gt2wvxblbnc.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2kzjrjnvl.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2gzcqobyn.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2qkfwxvwm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2utisdqpq.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2udguumgm.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfgpcqkc.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2dmsarflm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2frrimmlz.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duesqrox.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2tbxirccu.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2qngclibo.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isunnpfs.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2czogwkrc.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2hmklbkeb.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2wqdgiuna.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2ynaualhm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2qktppshf.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqtcnqlf.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gt2svyovmvk.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2xmxntsua.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2zpxnghln.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2aizgbcbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2wmiodmwb.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2bcrskzaa.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2hvcjxobr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gt2ghvsjrsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gt2nvwvczju.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2vuidplec.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gt2avyacjkb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2bqqnsbmc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lylyvxxr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2cqyzptdz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2vgjylcsv.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2tyhfpfrz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2idcaxlls.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2ivfagvun.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2xpzfnbak.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2xevhilbt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2fajjktbh.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2wvbkbtyz.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2ynxxwdzc.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2kliyfvdf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2ebmtospk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2nzmagvah.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2umglanhr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2xcxbsxzo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2okzjybfd.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2wrnsspli.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ioxnmyjg.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gt2ozltdnlw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2szijibze.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2qfnovudf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2wvsoyylo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2omgprueo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gt2deragexr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2yhmutwjc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvntpnyh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2jtvuoddk.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfqurwdh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gt2lyyidsnz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2bwadqqwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2jghzaxwy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2smddmjdv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2yjckcutu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gt2tedaganc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2xsuilhwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uztolxfb.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2pvkutyip.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2euzwthxq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2aihxmfqn.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2atatcdio.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtmgfyak.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzjkzjki.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gt2tphwtega.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gt2dyscpurs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2ahyiijkl.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2mskqpruk.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2anrlybnw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2odnqwxhd.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wvlaljdr.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2hblzkyvh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2rvetkdsg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gt2iuyksvuq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gt2shyjyflc.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rvwmmutf.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2yyvgnywj.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gt2hkruxrlt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2tsbvadtb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2thwzfiyy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2saummnxz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2epzznmlk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbvvcaqw.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2fbosshzb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2fyyhwmoh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2livmbucw.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2rrhmzfet.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2suandxhj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2fryxdozm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2cegkerax.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzkmmvwx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gt2xnypyaib.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2mdxlvkdm.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2tfqwcfwy.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2zdcnywah.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2xiuctxcp.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2tozfkdhj.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2xsaushpg.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2frocneks.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2hwjalmxt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gt2gtwgyuhc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gt2turnrnjd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2glwxlojf.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gt2ryuivsfr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2nsheypvu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgbdqgen.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2bzbyogag.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2lxnogivg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2fmcunqti.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gt2jcaxwlgh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gt2jvobtntb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfntxqpx.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2arokknrz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gt2kofemmmj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2hkyzqgjc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gt2sfvbsfil.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gt2dwepqgan.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaregwyy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2iazqlmcq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gt2ccjofskv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gt2kylnhyyg.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfgsklvc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2gpwrkrtm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2jjnocoln.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2yascalne.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2etqwxdjc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gt2okgmswwp.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2fzywdjay.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gt2kdodglho.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2sjuassjg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dhfdpavm.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2zoslqscc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dhurtsnt.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2kdivdssp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2tabzmvbh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2pkmbwqkm.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2nxxhenmj.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2gttpffov.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2flbgrszo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2qjqlyiyj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2oxmwzydq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2wrofjinv.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuydghda.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2nhrawtso.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2vzxgjcqd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efjcmaoc.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gt2owfhxodo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gt2gszutymr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2vvparaky.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ubzvdtly.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2tfljnjxo.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gt2mvplxson.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2vckkbgpq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2lgfiagry.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gt2xteofhsj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2xkmtxyjr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2gxwdahlb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gt2kgycqzut.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2jpdcoxhn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2tledvogr.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2tpjkscbd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldvyxhpg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2dwhxrmqy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2eoovalcd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2gcqpgtwk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2ukhhjivc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gt2wuhzmlvr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gt2mpzefyas.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2sknzzjha.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gt2vwrhoxbj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uajvtrue.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2gkqhknrk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2fziiadob.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2tqxkfczt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2hcnimkiy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2euoqboyv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2mymopdby.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2tewvgrdv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gt2kylarsnn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgkohovz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gt2vqqdbxin.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2rukbszra.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2ktdkullm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2rnebrvlk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2ghnuovfv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2ezixfspy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2vygzulng.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gt2qxtkqlxr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gt2tavbdpmu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gt2jyqzxhkh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2vbngkrqr.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gt2gbtzrvzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gt2lqfqvmvi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gt2vhkfmrxq.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gt2gtlcmnze.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2wocaiiuj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gt2vtqdrgvu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2aspipaty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2kwdjrgxm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2jhmowkkg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yaftuosl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2mwweegow.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2osksircd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2vjsfhrii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2tssaoqjw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kzznuvvx.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2cchhrayg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rdbarhlm.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2ehzoknga.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gt2qxumvgxm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2enbpoarc.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sldpazrw.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2fgdbsjrv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2eujhirfp.html


<!-- 参考信息 -->