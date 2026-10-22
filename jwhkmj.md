代发 wailian999

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtazhqicbq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gttvechqpz.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtgspanuoh.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtkdrakbov.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gthtckggap.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtmqnrayto.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtpqokjjwa.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtfpsbthqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtlfwsyxxa.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtdpijxfcm.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtpuopwgbr.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtufxhtpoy.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtvxuumsqb.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gthlxsguon.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtsmlzhstm.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtmshpzxpa.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtazdbgdkl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gteydhvpox.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtskljjcvb.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtpxtcjudp.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtgrrppuhh.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtgaazpvvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtfaokinym.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtvltnztks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtgoygrmjo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtlegvpexh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtghctwnqs.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtihwkdjgj.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtpghzcoct.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtxvdcmtvh.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtffmanqju.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtwqzzzkhc.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpsteuwp.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtdampuggr.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtculeimis.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtatkuyxok.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtmgexktas.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtyzwmmzfh.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtrihmekav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtjjwasjms.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtvrjgwgmc.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtvyietoem.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtffzntdmg.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtrinthsav.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtriqwayyd.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtbfflmyqc.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtcexrklhi.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtmyaioraz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtopauukdj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtneleduto.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlbfqfsf.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtewmkvpvx.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtgbxlmpcm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtqrukbiqx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtunlzaxct.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtscrzguxs.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtrmcniqoj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtdgxwhirs.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtsjriixij.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtoibrbyrr.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtxyxuvlqj.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsahhxew.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtcpoglgar.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtrajlppay.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtzssnvxct.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtfupxrasi.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtobsxxmiq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtpiiyecvw.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtvbnqklse.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtwelgfkya.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtfkfjhaxp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtrerrglpl.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigmuevxf.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtmofsccoi.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtmzhgjyst.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnavhfzsv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtvqbrcgrr.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtznrstulx.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtrglxereb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtkrfuiisc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtbkhkhvsd.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gttmfhmkjz.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtqpxkfhbr.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gtmeosphty.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtrvfdimwa.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtfodxyuim.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtntxcwuzv.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtsutsriyz.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtywjphlkp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwseyouhq.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtvvkgeqyl.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtkiqkdvjl.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtjifqccyl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtejmclneo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtolhunybg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtrpetqeyd.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtmdroxtxz.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtjwvvzljw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gticraxpzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtoyvyyzpa.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtfowsdggq.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtkprcvkvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxpuwxsq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtrcxkopvq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtnnfiydps.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtosqrgytx.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtupcpghkm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtzlzbdguk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtnnreosai.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtdlnxoebr.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtponeqowv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtbzdryplg.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtagvvsqrl.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtveosprno.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfszjkulv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtvtvhvxzo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtplmitrrp.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtnlgdyjst.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtbwkcroof.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqyrmqunw.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtvdufxmqd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxebpocxs.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtguphfytl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gterymoacy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtzryfbgqj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtkdrkoeld.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnowieggc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtxtvnsfom.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknattfwt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtvwbffesg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtyrhuthdu.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gteyphhzrt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtghhiagms.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtnopajdzz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtnlqgbvqe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gttawxqfpi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gteblkybmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtmsroyihl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtzugxgbtq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gterdpeqpr.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtofoymsas.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtliazqdbs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtsklwhyqa.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtfdodpiki.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtyiggqbov.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtacgpzlpi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtgaispmyd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtuzewaaps.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtqgvnlsqz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtfckfdcgl.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtohlagmrs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtqlltpsty.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtykojceto.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvwlxfxd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtxkkcgtdv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtbubfkhsb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtghwgcbrc.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtzlsmbemh.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtwvcmquuy.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gttvktligv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtfueauzej.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdktqqzel.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtqlbomljq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gtiolsbcvv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtntlndsre.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtpoqcgwpg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtnggwvvef.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtxhfmqzoj.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtyfrcxkei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtmbyjmuln.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtxjbgzgrq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckvidquq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtlnmwhqnx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtgqkcqxzw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpvegbjo.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtigtswvaf.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcggodvwa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtwwgtriyq.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsbluoiy.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtljtlxpqg.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtmsyqekqu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtpgtxebmf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtysedivdg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtlempvojw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtthelfoyc.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtruhpotme.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtaxdbpzrj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtchqbvctv.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtcytcccuc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcvxwlam.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtfhftuwao.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gthiyszmfx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtndllrjfh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtdbemgrbt.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtolqtjiiu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtuloqibhu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtmcmxnojq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtiydbmjoo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gttbbjljvu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtujtnunxq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtedopeoyu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtcpkpvvby.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtlliiwgbw.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtteazusih.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtunlzwdqp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtmqdhftqe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijffmyci.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtubnctxju.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleehmwmx.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtjnztvtfx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknpgbcpq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtgguphoeb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcsuijgow.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtwgjbesly.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtklrlzpbq.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtgguulxky.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtukprrcdd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtpfaffwha.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtfqfoquem.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtpzlidyac.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtyjglfkbs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtndproduv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtyjjrucun.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtakijkikd.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gthwzsjyqv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsqpwhdp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtnwcvlavf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtrmprpaff.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyaopgcx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtziqfhoft.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtumycipls.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtknghujfn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtinvqqqwi.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtqmfuxeqd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtiztseniq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtblqnyhuh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtdifqlgrr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gtkbvffncc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtjcmxrwtv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtopvqpvrt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtnpyfatem.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtvldkdmdm.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtcdcfnqpd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtmsenmjll.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtnvghpoyk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtwirbyjdd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtsgftqzua.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtgqgxmvku.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtzprqmctt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtlrkttbdz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtqsqtnmxw.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gtxhypwbxq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtuokztxgc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtbuokghmq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtpaxtaovt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtvukbaxlk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gttyyjlios.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjwsiczud.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtatditwzl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtohyxgskq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtrkxmoaqo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtzvygycwm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtmzoqjxxy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtscnnofnc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtzfjrqvsb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtmcxqvijb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtxrqtxyqx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtpupqyawa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gteowtpbzf.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtkgyttqrm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtzqfqzvsq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtijafqlkl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtomsrpdtj.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtwdrurawr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtdfbyyvgf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtrzlgddmq.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtzqwsselx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtuaeibwuc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtiofrdhgs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtspumzmtt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gthhkqmxnt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtrgmpevra.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtzwrhvbom.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtldijdfev.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtgcxsiyvh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtrxowrhjj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtfaudgdly.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjtsqqqgz.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtbnnebkgv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnzwwmyjz.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtlkjwzmeg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtmjvanaux.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtgpeliomg.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gthwbdopjs.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtgyewunjq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtpkialrov.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtlzfzxpaj.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gthkjycgsc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtuablleyv.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtmggqhlqp.html


<!-- 参考信息 -->