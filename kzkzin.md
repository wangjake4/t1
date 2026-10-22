代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2oodpchkz.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2ghhvuapf.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2umpukyer.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ppusbhzs.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2bgpsbkoq.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2aqjenoqc.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2ulvfgqrq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2drwjjcjv.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2nuifmxfc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gt2lxzrhmow.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gt2dalkpnwc.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2fgsravtc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rgodvdoh.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2fbzwdrbn.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqctipfm.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2lqbovqzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2muedwhjj.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdlyifes.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2ewuyahyc.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2gqeghglh.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gt2trraukvy.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2adhinwts.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2oskzxxtu.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2jnpazvae.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fncswxmv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2xrrpnohk.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2uohutcsh.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gt2iivsiwcr.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2odcwpzmj.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gt2pouysylo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2zqwsxpry.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2goiuqqjf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2mazlexpx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2brgellbd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2fkrtzmwh.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2maixkhof.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2qwssfsyx.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2norkmgaz.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2iwzmjokq.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2dtndqtby.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2epkwlyeh.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2kadkikmp.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2fhavqpbj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2swrjrquo.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gt2lweztblj.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbalpztx.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2lbmypmsr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2foxevtkp.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wbtengas.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2fqqocpdl.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2motsrwnj.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mqdlkwgi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gt2ndnemqyz.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gt2sqwshexe.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2oflbitix.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2beuhukxv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2jbzfbaqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2xaysnouf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gt2uujuekbz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewegofbq.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gt2tfqawrxd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2nirzglox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gt2twznvfrw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2qiuwrlry.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tktaskxa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2tmtppjph.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2zzbdtowg.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2prcaegnu.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2expzjcsi.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gt2yibaoghd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2dmbxwlob.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2btoeaoud.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gt2akmcpzdh.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gt2ejjcqksv.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gt2adyiybul.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2plyjdagb.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tbmzqiil.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdrjpfyh.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2bcmcgice.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2pgfpbdna.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2hjonbrni.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gamwhyfu.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2zviisavf.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2vbqfphjt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2toviqzgx.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2qjollukz.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2jhixomrj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2ssrvjerb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2ncmqdtgu.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2ugqgupcy.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2klsfwgjq.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2kfhujpwf.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2zfcdkixh.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2aloyegir.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2iixdgflm.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2flusetfn.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2cwnqrjmf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2iqojmojt.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqhppwjn.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gt2zvaxvtbn.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2mevjqxhn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2fsockxsi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuoqjird.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjedqvrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2okpnkpvm.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2qrvkslmx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uiyrpgyo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2muwxlcij.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gt2vglvkhwj.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2genhwgik.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jljtdxxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onxahooz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2zhpoupzm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2torjodpa.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gt2xduxvgvm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2kklzsolw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2puldjytt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2xqgrayyr.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gt2wrlwpzvo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvbqwqga.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2ywxrvcwh.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2cportzgc.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ifhzqmpc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2ykmmcwbe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gt2iuygxlov.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gt2tyykewtd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2qtlgtltg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2stjamzyn.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2zagnsblr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbgddvkp.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2etcojirg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2mmululby.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2eggxrqbe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2zffastps.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2mkbfkyba.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2wkavfzdd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gniqipjz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2mjefjvvb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gt2looogwkr.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2fapvmbry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cycrawrz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2pwhxmbjx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2hrybcpwa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2yiekhewh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2wvfamjln.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2dfbordud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gt2ridplnal.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2hnspzbht.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2jzfbzzug.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gt2wjsqonsu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2vqumgfjx.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2eozdndnq.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2ajjvjeof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2tlhbmswd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipusfjyd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2rczovefi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2odpulqtw.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2dkcrczkv.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gt2uwzdctqa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2fcskvdqw.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2hyswtjhm.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2osfuufta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rfitgjun.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2vdprospu.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvweutqf.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gt2hfrrltuw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2miozlbzr.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2lwhakbog.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2putxqjvf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2auqhmwxv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2kkttwdlk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2qcoptluv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqmdtkpp.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gt2xgcyznru.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gt2xpkeiaqu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btndnbeo.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gt2ekgnezex.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2dytaiqur.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2dndbnyca.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2sjrqajav.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gt2ybgiyorq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gt2dkclmjdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2phigfbxe.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbbtlipj.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2xjtnsvdo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slzmcahp.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2nlmzjynu.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2vfrfhvmg.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzfxoucj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2lscflnwe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2ovnnkymf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2xtipcizo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2mxjwoyik.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2nzzuljtb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2lhrozdfi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2bkyldukj.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gt2nytxqwkm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2zzaljhum.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcguujrv.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2yyfqzffz.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gt2ktarddow.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2rppgxnay.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gt2fulrlrei.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxgvoxji.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2bpswwtey.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gt2fsuqxriy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gt2rnxtwqrj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2bqdwpkwi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2uoigoaxs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gt2vhbbwsgq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2ljbundfp.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjazrjak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gt2sxprsqtv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2dtomtrjl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2jdkjiexd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2qvvieont.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2fnwvmbfk.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2kxiulvtg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gt2oetnfdfv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2jacikpph.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2teqpqvkf.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gt2tfvvlkef.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2hsgooeun.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gt2lcuzjjcd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2jkzmccly.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2mrxdtpkj.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2btxmwhnd.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2updeffzp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2mpnrkwtl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcetcaph.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2lvwrvuvp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2rbmliczi.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2pszvsyzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2cvxhexnw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gt2bmqdzpkt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gt2iymnrfju.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2myayaojn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjtfefnu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmtajdoj.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2awermwqb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2pblpckpe.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2ifwchlko.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ajprowtt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2isftrpot.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2ijkhzayx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2rijitmem.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gt2cgbzhyuw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gt2wnbkfzrq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2uamscthj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gt2uakrqruk.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2luhnstuh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gt2rtvlhebv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtjnxzgo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcaxzlil.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2vgdpxhcn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2detjsold.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2blfdvxmr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2yelcmftn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2uoerpqev.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sypsslph.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gt2ufpvntli.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2oifmnnco.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2dorlqzgh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2ikbjiutw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2ovjsobbw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2dgboleru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2pngpkkuj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gt2csqvprpk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2byzgomjy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2ndysfmew.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gt2vlwvfmgd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2edrvwzzf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2jirztgct.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2ztwzdcge.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gt2ptrxcxkt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2qjznmmfu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2ozdtoefq.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gt2bmsevzrq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2rmgfclaa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2hfekgrrf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2zcoyuxuf.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpkiyjrj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gt2melavmcn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gt2vjgucoqa.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2zxxljyyr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2vcqqzaxn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2ralyxftm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gt2wgdpahgp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2yrocwxrl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2owowlcss.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2kbxnyfpm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2wqkzxdeo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbsnncco.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2qzayylic.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2anzqmebv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2iyagvodl.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2dlagoeyi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxsazxaw.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2cgrapkuk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2gyaykhyc.html


<!-- 参考信息 -->