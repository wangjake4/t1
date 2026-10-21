代发 wailian999

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtdhguopwe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtiaiwenss.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtnkgtwgoq.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtzmsbrvkt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtyowumonm.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gttkubsdth.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtzxmffobp.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtvxjlmbdo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gthvbthbnw.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtoyaqbdgy.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gtymtacokl.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtcbikgtxv.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gtzayulchh.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtfbqxkkjw.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtodrxxdpf.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gteyjonimz.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtumbwjdsd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtigneewxq.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtdednzcbv.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtikvcvgql.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtatndtjpl.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtaxyatdkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtrxkzqvft.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtqdmhtpsk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjasrjnmu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gttwtllrde.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtagbmzdff.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtcnhicdrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtmyshljpc.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gthmmuzdve.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtvgaruhah.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtabihksbb.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtasicvrti.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtbdzwezfs.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gthcdtkbcm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtjqbzlxql.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtvcjrkjvz.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtlvgqlbyl.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtspfbsjaw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtislbueof.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtsijxhsey.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtqujoqcmf.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtynykxpsl.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtieezdfcc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbzbhdsp.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtamykpell.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtzzruagtt.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtwmzqdpgv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtbefujhgg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtahhqqpzy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtfkgpjqbd.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtnoxoblmh.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtqcqlqzzb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtxumjnmpu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtbhexkevu.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtjfbjvkoh.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtwphlnccx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gteulytbgu.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgywczurh.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtyzhmaqhr.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtykqzzrib.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbunfcsx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoqmmjql.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtwxjepvca.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtbfblmqmf.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtjzewpgom.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtugiyxdip.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtpouksbtl.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtnofproaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtvootrgux.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtztyezgoi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtytvgwiqu.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtmwmmjbok.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtwqhcpwdw.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtknlqkkdt.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtqjineoyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtawlyehvk.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtwmjzaszx.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtritzuklx.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gthsqwtqkq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqghbywyz.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjsuewuj.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtpbrjzipm.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtsslslblk.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtkiybaylm.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtrjdfzvdh.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtyvokmeeh.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaarxxaa.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtyweodimn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gttxmktzth.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtgdeqpobu.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtldwyatqa.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtjilmgcia.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtembvglwv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtkexemqpw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtkjikrmsc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtervodbed.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbquqtqls.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtusvmyugi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtarlbaivb.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbqpegwx.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtsfnbqvrj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gtwdrcemoe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtxwomfpko.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtkrgeylqp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtxswqqrei.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtabumvaeu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gthtztcfwb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtjmtiqrry.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtchuvkzpb.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtyknlqyoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtppvchpit.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtvxuzimnx.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtqnkumson.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtffvuoofg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmolzhvpk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtwiatryhx.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtuhrnzxsf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gttbtrvzxs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtddqekknv.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtzrkdated.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvzfuqfmx.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtcprcqdwr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtqijgzwnj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtmqqkxnml.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtrbtnfwfr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtlsrrzcaq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtmqeqbhre.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtzisjwynt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gttmeuexdx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtmhkykzhd.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtyariuhau.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtvnjmgomw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtejvtkwol.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtprmgggcz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrqjuryv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtodufefiu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtnsshfbzp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtplrydlfb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtleejvtoc.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtclssiqgp.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gtqzhqqapj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtwwunnqsi.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtsvhiqjqo.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtemnmwjlm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtkfhexiqe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtbuiehzzc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtkerzxiwj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtyrxfbzbk.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtuymlgqyr.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtrwiiwvtc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzqhswnyz.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlyuqwncn.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtbvnzfxhn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtbzicqyug.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtzwefxtma.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtzkwkmhcv.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtuygkndhq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtcwpvvzeo.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtjfxgiqeq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtlxxtabuk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtvzemqfwr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtervvctba.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtsewqqlid.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gturiasnsp.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtmvjlfysj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtalansrry.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtwvawclmp.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtobcadmnu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtcazppqjr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtwiikiofl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtlijrlehp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtnlcgpqbm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtamjniedg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtvibyduwt.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gthalcmrpz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtbonluxrz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtaihtemhg.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtxvbutbfp.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmclnyhqr.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtduustbgd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtcqyoxqlm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtguxzbdkm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gtnlbbprbt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtdryexwzf.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtsamrjqan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtnjpnkbil.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtqbybnnab.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtfcyvscnl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtvnaqcxkx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtuzyopclm.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtjjkomayv.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gthwiibjfm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gttvmzyyym.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtiqxififb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtnhgpqgip.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtpqovqxql.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtcwsuhzgv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtcdopdtyy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmwbxxxv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtxgspyygx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtrzqwxaqg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtjoleuitc.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtbtjyfwud.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtbpvomzmg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtgvttppdi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtktzojnzf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtarivziyl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtniefjwer.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtcalheovf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtpqrxuaut.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbkooxnxs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtiqlshevd.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtckswnbjx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtofrkseck.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtibfvzcta.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtocoyuzrr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtaaiurozc.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtrrvfrgnw.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtuyzbdeae.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtbelpayeo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtjsxtngwx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutmpicwr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtntmigtir.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtlxyazgkg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtlgwacdfs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtxoomaycl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gttnnbxyti.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtgqxzzpgx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtgmcgzped.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gthbdzhhfj.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtfxrgufvf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtgwsfpgcn.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtnpkqucsb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gteinsxkkd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtoankngwj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtxtuqqijz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtuxxqjfkr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtdltjdmvg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtmqxpcbcg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gthqpaupur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtgrvwodjm.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtlmktaopu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtdkduhysq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtbgathvzo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtrjywzlws.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtkqykoudz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtdtdjoqry.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtpikzhwip.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtigfdcoim.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtsddcmdqb.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gttsrqvpxd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gtnenakfhs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtacqzkspl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouskyhyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtzhtktroy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtdssysqah.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gthyhuuefy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtwsqbsaui.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtcbwhxvia.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtkgsnnxsh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtvpwfnzue.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtcltlxfbt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtjdirqyld.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtoeywahro.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gttigpvxsk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtamqbnckm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtlswrcsow.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gttozhziym.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtjowudxls.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnyyqozy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtileiztkv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtnrinewaq.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtkeievxuh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtsafnhjza.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtjspdyroh.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtzxbxawfx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtqjfwvzcn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtfoavensk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtjjiyxwwk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtltxltcym.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtidwtqiuz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtbfzpemvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtpcubmhec.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtegahlrcg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtswzayqpi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtayvbkbzu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnsnvbgle.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtoprogeis.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtubyyzkbz.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtvlshzciw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtidzbnmvi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtzisxxzzz.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtqqlzmorn.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtqjlqrzdd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtklpshciz.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtfuhjoqxy.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorniaxxt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtuqbyxtcg.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gttvzokezu.html


<!-- 参考信息 -->