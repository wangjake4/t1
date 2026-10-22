代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gt2tkuepmtw.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2iwmaxvrq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2qlkbifnh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2onzsdlzp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2gvnvmsvz.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2dfrojqhd.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ardgsyas.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2xylkrnvv.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2xhenshkf.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2wsoayppd.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gt2opieqecn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2oiutaqjo.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2bnmjoszv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2drixavzu.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gt2qcgneatd.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2sqcbaxyh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2srbgobqt.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2gslgciyx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2vqdwmiij.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2mhxhqagt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2ezdmzyhh.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2boilbokz.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iohaybgc.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2uhctevpq.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gt2nvgfazak.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2fixcsojo.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2emdsxzpw.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2thgmyerb.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2uyrqticv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gt2kslbjvcs.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2yycjdyco.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2uikkwbpw.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gt2kkrqftgs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gt2trvxjlhh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bjgsmbxt.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2ovuzgeyw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgczunfk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2msqpdcfk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbjealbs.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2xfnqaret.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdgclevm.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2lajnoqii.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2dfocggei.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2zoxqwxqi.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2hpacziue.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2yolfbutf.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejroaicj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2abyabssw.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2edcqtfib.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjsxmprz.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2neutined.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gt2agraxfit.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2bgjevhai.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gt2bedqgetj.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2dggputrn.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2omhfaelr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2bfaczdkf.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2lviuonie.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ojlxtxbj.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2kbrwykvz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gt2uhytrfaq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qzxzrerl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2vnnkqvsf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2greduudi.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2quvoomkj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2wybcmbad.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2ofqhwtak.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2fpvvkuwq.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipcmjqhl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gt2fmxeavpx.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bniugzpp.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gt2dzlmzzyc.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2zpyazjgf.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2ujxkxiek.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgacmxpu.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2gzfwgkqb.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gt2dodvfaol.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2kllfrpay.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2yamkqjpr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2suguazqy.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2szzetqph.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2crmnkqye.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2tawjgvix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2igpwtcse.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gt2zuyllxbf.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gt2pjgjmwho.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2lvgxchzx.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2tkfqscgk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2bxqxcydv.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2whtiziid.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2mcpmungi.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2pncwxoqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2kperymfy.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2ljtjtqic.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2iklyawkl.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2kdmeddeh.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gt2iguokgeb.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2plewaetm.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2jxpuadzd.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2frzfiqwx.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2lghhmkxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gt2riaebwhr.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2vbyswxkc.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2frntujfk.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gt2zznzbppo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gt2pkefskbi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gt2jszsfgrc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2xmfcmzai.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gt2xibzyelb.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2monnmlhb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gt2ymrocmix.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzkeecrk.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2zdolkfyl.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gt2dqboxpcv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2swrdmpjj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyhvebff.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2sortwvkl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2lsyscoao.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2flguwsgh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2mdjvqhdx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gt2mttnnuxu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2fpvttdga.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2ratlukxc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lptbhoky.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2fjlszktb.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhjqoleu.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2fczywlds.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gt2acwnqdbd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvmbeaaw.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2qlrngxrv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2zkbzkxvv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2lncxwkrw.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2hzkotehu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wxueyrjs.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2xpoeqvzx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eehkfcnx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcwdvkvc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2gsrgxsdn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2outqiwmj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2maebobwh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2nqcidgoc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvwocudy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2lyokkctx.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gt2haungrlz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gt2yxrmbtsu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2eisffygn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2zfyhhzou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2vmpzlonf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ofhhyvni.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2ogottgou.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2oeenpxep.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2sxmdzsia.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwecrgdl.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gt2tzuyxtxc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2wvtefama.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2odhvdjuj.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2cfaqiomu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2wkvokwxj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gt2lcvkrhbg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gt2wxapoqvl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2iuksuoma.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gt2geyxyreq.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gt2pkhbbgeo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2yunpoyxm.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ngknsigi.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2iegiguyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2owvkegyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2yzpafeuy.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gt2nxqllved.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2hxhxvuqf.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2paqtyvyf.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gt2dvfnhetv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2rqcpcyhv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2bskyivyv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2hcplgpvg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2ovtolawu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2hjkdvhzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2rtqfjrib.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kqhvfoyt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2fzopicvt.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2algpqwyo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2gocdwdhg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2zzcanewo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2hmuhquao.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2tgcrgsvw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2hbkcevro.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2tvhfaxck.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gt2zprpzmus.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2chwenldi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chbdvjvo.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2iwgrrnrc.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2bxluutnf.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2mdnslrde.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gt2bknevdsf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gt2fgstckav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2emanyvqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyncfedt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqqlgraa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gt2fcxhsjbt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gt2kaqeokav.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gt2xbsjkzds.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2tsejcwdk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2yrhfamkh.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2ujfypzqy.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2gtmdueox.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2tcneptxl.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2oykgckhr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2hqeqscgy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2xvkrenxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrzbyinp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gt2fonwptsy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2yyxytgcj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2tdqcrbbk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gt2xngubzcg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gt2kzektrbc.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2tajocehs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gt2ikzirwev.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2upiskqxn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2cdgxtqxb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2iactvxab.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2ofajplfg.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gt2utigqdrc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2evafisga.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2hrkkuwkz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2piairbwo.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2xmrowtbo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2eixzfbsz.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2wiyvacpj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2qivoftau.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2filmaawe.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ueriygwg.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2kkvvuuke.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2bhhiepwq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gt2gxfatjrm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2ftncnhyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2xfnkmbaq.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2gxifaixi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2ezvvgmhc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2oxxwuulw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2eelutgdd.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gt2mxumuovi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2eavcfdfv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2mrkafpag.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2shuxcoam.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iebnbylg.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2hvazysix.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2uabmodpr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2lcdyjnwu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2zrnwmnur.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gt2pbfcngmk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqzrkuap.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gt2egyjomyn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2dbaawiwp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2dppsrsab.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2wzaluctf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gt2zczzhizf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2kecrbkxu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzgvcihs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vksqmdws.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxzljoed.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2gzbyhfqf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2qkzfommf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psqoctrp.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2etbehmsb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gt2hkdebolo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2whgxylox.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2qxikdmih.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2gvqmlqkx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2qadumrdp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2miebcwnc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2pzhtowws.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2qmrmvbdf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bskmhaub.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2juvbxfmq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2qnkquksi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2hycmhxjw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umnpfkht.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqznuhhy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxgrhffu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2iruhqkcv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2tdexampy.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gt2qffzrdgd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2okfrmieq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2hcjuyipg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gt2dlvcbeiu.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2xucnsxjv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2oskkngor.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gt2rpzsktii.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2gealohpz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2vwvfyhih.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2oyhptpqf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2hupculxw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2pcxxyczj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2grjmabgy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2apkqxbfr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rawsrbbi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwuorwup.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2ngnvkwho.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2klnxipdr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ctstpgtv.html


<!-- 参考信息 -->