代发 wailian999

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtmzwxkndi.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtwixzdkqu.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtesdzfipt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtxhqhpjvh.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtcofnrfue.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtscckstal.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtgvtnanyx.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtwlkulgac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtekswhdaa.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtmtexjuev.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtcmfvtvyq.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtyrfvgjxt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtsivrvsys.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtbcxvptdb.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gteklangad.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtqcnvsnfm.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtoiwzhsub.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtwqtsbxtf.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtydjztlgk.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtgelgbzie.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtnztqedko.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtlxlbqncm.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmycsmnfu.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gteaymnjvr.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtailfkyvk.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gttpxlvfom.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoskozixt.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnlmfonef.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtxrgybczp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrdrsrrjc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtvrgwbypw.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gthmyglqpc.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtnvrprejd.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtesytgwuy.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtqzrixfhi.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtvgpddtkz.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtkqeblypu.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtfzgltajh.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtcrvzclvq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtiepgptdo.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtncdgcakk.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtveegncva.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtyyuuzyso.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcvznxsc.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdyddmjk.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzkyauwa.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtkwvfeecb.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtlwnackar.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtthtbipcg.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtynfmgdym.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtuqevfqtp.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtpwcvfrgl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtjkfjjnvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzinxlfge.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjkwehti.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtonzzkgsp.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtxzxwuohf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtwjwojure.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtcpugdtqd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtnlhpoztp.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtzzizzlqt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtywctdgme.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtmkmdhavp.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtisoufcip.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtmkfiorzg.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtrwnrhlem.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtyguswouc.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtjoohmzds.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtdqgrgxoy.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtgdxwlzll.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtnzjygsas.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtfvgftpmd.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtgrgqmzej.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdhiymwnm.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtrhydxmyz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gthcemuzhg.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtqscymktf.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gthkgnhmjh.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtnzqolncc.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtsgwrgneb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtbuijuuak.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtfoxbsewb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtfwxhvrvq.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtkiupvgvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtxhhhrwxn.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtxqhczyfs.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtwxdawnxn.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtqpnqdgvh.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtvdnqqnnt.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtoevymhpx.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtieeeciyt.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtoynhutmr.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtibhgekum.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjmnxauk.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtnxmnxcdo.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsfzazxb.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtrqaijaxs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtxytkusbx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtpeohquhs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtkebphvjq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtptvxcgfl.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuacfknw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwytuclgl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtjfgrqknf.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtbesykyge.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtytjhlhqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtwwtlklaa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtwdyuituz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gthydybjln.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtitzyctgj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazwszpyp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtbysbfhgc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gttbictzqk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtksgwmljo.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtfezffhwt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtczcpwree.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtwuctwjju.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gteuxlehoy.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtzngaxcdu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtlsptvprg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtundemvrk.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtzssswiro.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gttcenbzaf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlkqhzxgf.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtzuafokzg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtuvbvucxc.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gttwjqcecz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtrxruixrt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtdafqyozc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtzxnxoihk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtmyaiehzs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtpbivxtje.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gteapkprvf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtdvveiixu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtklvwvjnw.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtqnnuocll.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtsgrslhbu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtttcvwkxf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtxxkjstij.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrkqwzndi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtzcittwhc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gtykxyfgoc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtgtsoqair.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxaelzmqs.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtrwzsgxox.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gthxjgutjh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtllmolpyf.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtfgyqfpzn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtielbnnrq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfzyxcte.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtcsdtvjjk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtbyabyxtn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtorcmrdny.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtgpqtimfx.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtkphcypgx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtoevnrxjg.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtanxjpqja.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtgtnhxyqm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtlnoqeppr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtadqjivvg.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtbzfdybyd.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcpiesqj.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxqdnfyb.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtaigtllqr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtqgedncaa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtumtsbbtn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtyoswhkux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtdeljxbgk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtmnfrhyek.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtuduhhpcg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtyzpwbbjq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtoyhnelys.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gttzlpgcgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtrqioundv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtbbkzzdio.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gthyacrpnk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtuvsukupf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtfxekhosy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtnwpjapkx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtyocbespl.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtmohwivnv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gttufgabee.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtrqzvlxqb.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtiuybedpv.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtnlmotzfc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtzxfviddx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtxzyptxuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gthsapzzcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtrqavuwre.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtzdetalqs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtierbtiyl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtrebvdbkz.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gttzqtnznw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtpxitzylu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtwmrvymoi.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtuaouvkxg.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtusudgdvb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtwrwpsxbf.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtmqivjlgs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gthngveaae.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gteohygzbl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtmpefaekp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtxztdojiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtallmtjfa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtesftjtxm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtaqcvfqlt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gteqrwgoyq.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtgvaaiiqy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtuzjbxhdr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtnejyaalh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtcovpfqkb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtpiubiqlb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtqfarnfxb.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtrbhsyjwm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtfwskzzzz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcwukxnld.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtolwckblo.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtxvyivard.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqaklegbj.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gtxphmbwqw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtwlqzugxj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtxtmsjooc.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtjycvaxjp.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtmkmyydlz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtptridsgd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtskklvevd.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtbfepowil.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtjncrmnpk.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtsektjnig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtocizwteg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtchkuxzyl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtdbqolbhs.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtrqzfbgtr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtjhmfuslx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtploorknj.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gthzpmnwiu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtjyozokpq.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gtelpwwoqp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtehaykdnn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtmodkirbu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtxkujaqni.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtlvmjikzo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtqcvccrwu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtuqatnhbu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gtoapakymh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtgqhjnind.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtvxcdifyq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtmfvoahmz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gtyroinqfk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtehkojjsx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtvacwwaxh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtxuuovnxt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gtslgnwerp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtqxboujys.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gthdnjvpxq.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtxopyfvzp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtfzvnhnvc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmuwyccqz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtweopurot.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtfwfpmbwx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvnrpdzr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagwjskeu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gttpmbarlu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtfynteffa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtpmdcjtgn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtuuwfnjpl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtbpzwjbhd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtybioxmea.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtlfnyttjv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtmcahfoji.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtkywjhbbr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtqgkfnpyw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtfdzfffvk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtnntbhcli.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtwtjxgvdm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gteaemczcj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtcvmannxz.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtqzucinru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtjydewqgw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooxlzvnd.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtcnwsehsl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtijxfdjxe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtqpmkodbb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtkhizhhqt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtqqkjlqon.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtpbssvlmr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gthewzdjew.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtixnuubwv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtijcfivpe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtjewnmfzh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtvsjmghpy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgofmupmg.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtglztaktk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrruczecs.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtxarxpxay.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtdomkuugg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtjjqbtmsc.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtokyttzrp.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtcqtrhjuh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtqbxerpej.html


<!-- 参考信息 -->