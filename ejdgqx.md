代发 wailian999

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtueisursf.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtmvkwarki.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtytntlnov.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtgynkqgpc.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtwvwnytzr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtevkfunqg.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gttucenois.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtefetdnea.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtvquszemk.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtwtgcxdwm.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtqvtnkkfo.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtalsnkffw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmxjzwdrc.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtyaocalpo.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtlqoaenqt.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtmztkqxmp.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtdptdjbyx.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtdjwhrxcb.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoonxnvd.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtrozinmzl.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtfrzmdjay.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtjcjafors.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtasopqymt.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gthgixeaeq.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtseewghir.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtjxwlrvkz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtycxdlocf.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvkdxlhyq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtsxtakrsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtcimircyv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtcaooqszo.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtjtyezsie.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtbckvsfdf.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gttxgdwkxv.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtvovozwfs.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtvebtlqba.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gthoyjmnja.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtrrboxnht.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtiftntida.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtuenokdls.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtumzkydyd.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtjxrphykd.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtjwmsgpak.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtdzwlweul.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtcwnwdmdw.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtwzatxvcx.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtppgileja.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtxknclybs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtfcjaljii.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtzwqbzqgt.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtszafxngm.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtxehcdaog.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtjabtixhy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqgqxdto.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtzlpjjtzr.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtoejlhrdz.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtlgapvlfs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtttlbmsnr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gtdfwwlrrr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtdevrvdnu.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtyirpgsqr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtffngydkd.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtpqzwuoom.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtbwrhrvhr.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtyebtawdq.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gteuxrrkgi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtldevwxsp.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtvegcbmtx.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtqjcppass.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtlvsjdltf.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtrselivsh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbnaiecmm.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtbkodrjiy.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtkjtrxfkm.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtljngtcso.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtcurlsirw.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtlodjxnua.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtfifnclah.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmdnfggdz.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtolfxwops.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtmlfhphqy.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtmablsucm.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtcmcgqlxb.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtunzptexs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtmcswizzz.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gttsbeubez.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtfnxlldld.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtazekwcyj.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gthkaekzhb.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtyokhzcmw.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtgqxhfihh.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtugttfjfi.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtixqqgnwj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtdjidlmia.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtpvhgmamm.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtzgxazoxm.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtfwkojjal.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtdhjuqann.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtkfyxolfd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtccljjxlr.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtgekauxab.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkpmjuai.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtdjsoqluf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtrbxiepxf.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtdriabspw.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtlewwjwij.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtiwingokm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtuytiztxa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtqyqwvgjj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gthlxbalqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtvlxwpgyg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtkgzouzcz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtmuhbvvim.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbffxgga.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtsamqjdwh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtcjqopjnv.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtnggtwmke.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtqjborehf.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtrspodpno.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtuykgpwab.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtvfwwlccn.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtseqpkzlz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtuzbticrp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtcqvaeghc.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtndcflvfg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbpetgxit.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtqowpltgk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtarrpaqca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtatqqtphg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtkopdhtde.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagqyparg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtnzlofurs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtaenwpezx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gthungrjet.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtvejqvlvv.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtojvmhrta.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtctrzplmo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtlodhjzoa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtetehgfyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtkjtxsmbc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtrnodilmw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtudogykzb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtddmnytxw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtkbxkmmgb.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtrqodtxzw.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyknadamr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtpkixeyjz.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtxfdeidpp.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtlqplwcgx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtxmrfsplz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtvgylrveo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtvfiipapa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtxddutiga.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtbyqlrteh.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtkeavbwdx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gthrgicudr.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gthozzzbei.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtjduirmoy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtyjfsmqdk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtrbqrympl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtxawgmmdb.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtzsexxrmp.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtlefhxima.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtefmsxfzm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtgxorfhxz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtvrnkrfui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtlxnqsshp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtjtdckcyv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtktnbuzgz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtthndetsd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gthvpbmuso.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtlvmedxtu.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdonsddhb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtwtybdytg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtbmxsqmtn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtzpwhpncq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtlqnksmxn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtqufxsqmu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtdsusnnyf.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtezjbrdmv.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtsprbrdts.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtxttovjvr.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gttomodstc.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtmlcjcpvj.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtoymqczsx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gteimiywlg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gterkumdrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtyvamzzoi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtarwttbxa.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtbkcjmyvw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtwgkxdhna.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxkmytjd.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtsgvcmjuw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gttvlcrmhl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtdyezcfwq.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtlkzkiobf.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtrctplwls.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtbgpvhjix.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtvprzwvnd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtyptiuvbu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyveulhct.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtmrtojkdj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtcevvbdby.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gthduetxuv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtfkibjqde.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtkranemry.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtfwdlbvtn.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtdgaobmxh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtehiiybpx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtrkcokraj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtuwcnqqsk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtlsnvntjz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtigzldznl.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtskdnpvaq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtogjosnpr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtcsgapyys.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfkyblvwp.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtakorkojn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuyylgaam.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtpxfrznzq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtiroqilfm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtbjnmwclp.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtbntmalxu.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtccmqpqty.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtrckygvgq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gthbbqlrfl.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtznsodiev.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtvehkijzs.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtwuqjdbpr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gttgswxgxr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtggwjwrlh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gthxdujknl.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtgqhndckx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilxgqjck.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtybqijjon.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gthijhkyzt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtnntioxur.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtejqsyghb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gthghcwbao.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gtyzcvmkmp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtcdeddjdt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtbheyduvr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gthwlmiklk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gttcagzcea.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtabzsmice.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtonvynmww.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtbhuayxgt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtmjfdlkmj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtkwmjpckj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtkdfkznff.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtlhyelevv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoafzuqpz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtexoyyygd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtgdgmqbdp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtsrczeykz.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtaqckelck.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gthnitfwol.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtpyvolxum.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtxtyampxj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtbipifbbe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtdmhbayap.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtjrvjuotx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtnypvbshg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtagsngwto.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtvfzmllqi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtozfsirik.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefnljeor.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtyxonhjwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtxedfhuep.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtwlsoccoy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtgqhvsogv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gtfbivmrpu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtmcftysue.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtfdvwakkr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtvuunkmzk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtmqibwdbd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtotkptuep.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtzfxjclqo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gthphcabhh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtrdwnskpk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gtitgxwkwm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtuhrxeklp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtyysrursy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeduaqkm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtsmgwujog.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtkrhjvazx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtuojbfqdk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtqehidppm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtijdpazgh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gthelhjcvo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtfjjhwejs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyggfyshp.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtejllpahh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtthfupcyv.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtaypgnrzw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtsmfjitdm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gthfxlbjke.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtcturqvkn.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtkffslikl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnnaypyo.html


<!-- 参考信息 -->