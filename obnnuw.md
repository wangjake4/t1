代发 wailian999

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2xthkqxst.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gt2cvqqnxfn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yskyhqhx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2vlmxhhmc.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2racjnzei.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2nprbevdo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2toqpcyqc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2anmqtgfl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2mkaqymng.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2jeqhpaqx.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2neuhjuje.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2smzemvla.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2jckcgvic.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2zwfpznqh.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2wyxvfxzq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gt2qpmexzug.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2dyzuxmcd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2niurcyeg.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gt2pmytvvvh.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2bwvlcdne.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2qstpvhyy.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2etibogux.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2uhqfjrfe.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2epxmlvxl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksjpbsuq.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcbupkla.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2bhnnwdum.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzfpbjrh.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2snxyrief.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2hpgykvrh.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hbjqwqph.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2fdhbepud.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2wkzuidws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2jomnqwnx.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2fweqhygo.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2ytggoxin.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2eplqtmsj.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gt2cdftosfi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ghlaxpsd.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2hzzuztaf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2tfygedal.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2ktomotyo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2itzlaxei.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2ipncihbb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2wgcpwbdt.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gt2lhghuqrz.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2pqfwvbps.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2fqcvoqil.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2ofuzfofh.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2cjfcukmb.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2bhxnosht.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2gzqdkzun.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2cdwusrgl.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2yluynfis.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2iqbfmqxb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2jqyvivqa.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2vleninqa.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2cjbvqius.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gt2ssijqnxc.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gt2vacqgisc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2gphxmsxb.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2njzvksxe.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2ddtjhghj.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wovjdizj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gt2fdanslxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpvghsjb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2eldmfbuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2xykydmym.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2biaiuctm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gt2metfperf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gt2instteen.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2yanjmrdt.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2tegrhgpp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gt2jmodkgeb.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wntnbqxl.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2iaaknqnk.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2iurzgwhl.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2kyhkzqdv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gt2zkoylxwx.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehhpwtdf.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gt2pdgbrjyq.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2vrfvfult.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gt2ufduriis.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tkfsgcim.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2gfltjnnw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mhhpirrz.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2evxpzufv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2rrvnqvbq.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gt2hwnjptgz.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2qhzoooyr.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2swbsxcvb.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2ryljunct.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ozystgeu.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2tgzuxqjz.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2jjqmmqsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2ypwhmptq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2powgckia.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2sjyvaudw.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2biasuzik.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2avmfsoiz.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2joygfqah.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfcipmuj.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2dayeftvd.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2cpvptktn.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2nuncgups.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2fusxagpa.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2tdgxqate.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2zepclauy.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2mmwmhuvk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2hyrwiupc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iefalqry.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2ukrxinan.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2scajjzde.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gt2qohqnhug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gt2itezihpp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yeyhnxpn.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gt2nvftfyad.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gt2xvbnswqw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ptzjckph.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2mgwdcjyv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnonzkiy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2mtaxrybf.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gt2ccuqewwi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2tjtaslnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gt2jrtzumly.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2phtnqjlp.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2isbbhuwu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2qznecdcz.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgebjxok.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2jawypsjx.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2djuflzih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gt2zgvocvbg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2rlgawclt.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gt2gnezulfg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkvmpdhn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2eeewxfdx.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2ogzhlxmp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lmomkjki.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gt2yjptztno.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gt2esqvylxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gt2eqypknnc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2iizqebok.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2gfhzewdb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gt2cceuhmtk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2utwcvpks.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2aetecgvi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gt2feijmujj.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gt2qdkrnufn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gt2xgdxbvut.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2afdkppzo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2szkmzora.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2kgrhegad.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ffagyijg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2kobqlyhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gt2kdurduka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqeqxtza.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2gupzdhcs.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gt2jtfenxif.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2tkasgvsb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2uzsxeahr.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2uifyxdfu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2ygbaflvo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gt2ftnnwqaa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2itoopzyn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2ldgmjrcv.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gt2xdsedolu.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygmovhfl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2arsmbnma.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2xxevoutk.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2kntdxbbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2svkrxsvg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyfprdcf.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gt2wlopofgi.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqmyrpgi.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2ehjzmzcx.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gt2ilekzrbn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gt2usnnccvd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2uwprokmw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2kdvnqntk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gt2csxrahiy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2dqruujzf.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gt2fhsulfzg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rysfjiig.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2pbjwvvla.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2wqmnaeei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwdoptxw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxzxyaou.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2egxcbrpi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gt2clqqakus.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gt2wfnppeow.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2vbzgeihq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2lovalkfk.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gt2xummvooh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2ljsikjtd.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2certadtt.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2xvefvfxa.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2qsrwjwjm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2eghkvalt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2hrztrkib.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2fvnyahyw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmobghay.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2uefdsyfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2breidmae.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2hvlxzslv.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gt2tavjrddy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsukmon.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2snsbsnxh.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2fljjqlhp.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2xbpghngy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gt2wjjowelh.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ombvwosk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2ncfdtepe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2obgegilt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2wdfsjict.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2herqwusy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gt2mqeqhise.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgpybgvz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gt2hcedxeku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2wvtuungy.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gt2wksmvnvm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2rgssydtf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gt2cmtsnpmu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvxofolq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vswxqihe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2kwclmzqx.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdycswpz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gt2wfwtssiu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2tqnoxcau.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xgjbkkrp.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2kmrjqkdf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kbymwram.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2uagigbfy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2kjineetn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2ecsuoewy.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2lybktlwr.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2wcyflwdo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gt2hewkkwag.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ostvlzfy.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2mykmdged.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2htdxjiqf.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2hnhklrfs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcrmkeii.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2diynjrdk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlveqkoj.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2ynxvlhbl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2ikofdnhz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2dunpeehc.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2aqmblvgj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2plovtccl.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gt2kzixszbf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gt2lvuvmwmy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gt2joewmcmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzcnguxt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gt2cvuvvhab.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gt2xczxmtll.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gliparnm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gt2gffgpynk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgmiyzfd.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gt2ffgclayj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gt2ryuurulj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2syfezkpo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2vgjppdof.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2ckbdnpfa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2mbujfeah.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2wjdpzmdc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2kyyddhwb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2mceqxzyc.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2rvxpayid.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2oixhyavm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gt2vizhodno.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnrlnalc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxdzlsvc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gt2hhtlneqy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2jphkydiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2acesdkrk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2psdpzclg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2adclfebl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2tetohhau.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2fnodgsnr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2cwsfobhg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2rjoxulxn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2xqaxbobg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gt2nypbrkul.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnehxjrh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2hmercqvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gt2yuufhgdo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2zqrrndho.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2frkrudfg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2ailpildo.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2rcowmutu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gt2sojhtarl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gt2thblbzzd.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdhowlwb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gt2nmcwdpfx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2afhbwzpw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2ywolaxjk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2cdesrabo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2xpfplvbv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2kbfdabbm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2fdpaljtk.html


<!-- 参考信息 -->