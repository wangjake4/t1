代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2jevfiyre.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2jkctyucq.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2hjusrknr.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2kpprmpqb.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlgzhzbr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gt2rjrzfwcc.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqnqzkpc.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2zltkceom.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2rpbyjebv.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2inzbdcwq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2zzljnocn.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2ssxuwsnr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hxoqhksp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2jghknpbt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2bswqyrev.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gt2iigmwlgs.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gt2tzcceqhy.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2mrcfmasc.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gt2uuzqavdj.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2fxqqksvt.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2okfvgcqr.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2cuieynvs.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2guguzyfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2bdarmdcl.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2bwhjjgik.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2sbflzisb.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2cufvqmda.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2qfjnntoh.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2abtxfuuo.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2uudotdyy.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2iqivwsrf.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2gyzaqzcm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2pbkssscx.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gt2ftchriip.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gt2ozokxlkf.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gt2toeymbrs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gt2jrkeoyuw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gt2dmvqmuyq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2ujdjnzkt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdjjilnq.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdhikreg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gt2qshxojzn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2mukjbaqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gt2rauusqqk.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2orfahzps.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gt2ppcdkbqi.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2ivnlpynf.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2nneurese.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2mnuuilap.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2xzmbxinb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2lfahjueo.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2azcjyfdh.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2eesfbuym.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gt2wgxelvfg.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2vgzepquy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgzquplx.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2nuajpimg.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2dftivest.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2dlixzdsq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2facjumzk.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gt2emwgmnpd.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2kikdiixc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2erzdhsan.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gt2iipeqdzd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2shuzelab.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2snvborki.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2gpemxfqh.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2mhpvlfyw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2grrkffte.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2tbftsely.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2vofppnci.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gt2lwupkjoj.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gt2khfuunzq.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjtwvyto.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2uesywjxy.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2jahpfhbc.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2gamirdxo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2fzxskxcj.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2sdvrhfyq.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gt2wrhggodh.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gt2asqctznc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gt2aimisxei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2zvhaxzhi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2otvgkuzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2ycttuxcc.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gt2vynmahuy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gt2ludlpyon.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gt2qjkmcjcm.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2fksixiap.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gt2mjsmlfnm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gt2ylvhrezw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2xmtxylze.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2yaefptgm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2pxunkkbg.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2glustuqe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gt2rxmcqbio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2ouizntpn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2yxvkjsmw.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2ykamtdme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gt2idrhzmmg.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2kahpfrnj.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2gflayffi.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2xbbpibpr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnmaxnss.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gt2uisyqsjw.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2mvmeazde.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2yoawwbbr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2cxwkrqtq.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2bemdkknd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2laoslmnh.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2tlfowowy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xceibtfp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2zbgdauno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcrfmwji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbvivtlr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2klykmxmg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkxsjtdh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2gbszetxo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2bblncyah.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2roxiffdx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2kyzllplh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2ayqsznwe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2gndauvbq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2adacprdl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dewubwha.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gt2hwwfyxci.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2dlxlxzzi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2xufowqes.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2fgibjnzf.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2exjfybpt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2vxepzyuf.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2arptivpc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2algamexh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2bveldctz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gt2ffomonhn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2qvvwhvze.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfghcoqd.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gt2ukimuxit.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2chudklan.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2jcttqmne.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikllozsa.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2ibrfpuyw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2bhvmhvbd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gt2axgrylug.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gt2ijufmylw.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2uzbxannl.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2myckpkav.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2hhqznesw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gt2yirrckrg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2bjgduwry.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2yqsuwrjk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2iwkbtbdt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2xyugxemw.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prtlboyy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2ekvwcdeb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2vihxbxbs.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhydahtz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2iqhkicux.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2rjgqmqhx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2loyxeajo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gt2triwmexf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnctnxal.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gt2estiahhd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2ogbdfspg.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2folovygu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gt2tdypoprr.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2ejyetxil.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2vxkfwmyt.html

TS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2ltzyrqps.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grbaphzc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gt2cexbozgu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2miinqzlq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2cirtrxcx.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2vlmblybs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2lzayzssu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2twkdkrwq.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2fpukfeoq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gt2yklxjebk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gt2gtbiypuk.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2xnksiino.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gt2fpjaqyho.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2rwstjdfg.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfgfhjyv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2iavdxhan.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2jpbrmjeb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gt2nbqxooka.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gt2nukkuygh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2bvxkexcj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2plqyudiu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gt2tmpyiaag.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2gzfxxlil.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2xifxhzwz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2elrwmfbd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gt2auqndlon.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2mfvppvrz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2xkmybpjn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sznfivuw.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2ndpcztle.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2zdfbtbkt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmnmyokb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zdlnfmoh.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2effsragy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fkndpgac.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqybfmth.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2mnjuzqia.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2ixofuwkv.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2ewpdsbtn.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2albbhksh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nylqbfek.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2vxvwvdad.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2jaocajqv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2lujjlnpi.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2rpseukzd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztkiakpy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2cfluzdmi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gt2lisrmaza.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gt2lnnhbtvb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2ihmlhtyy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2mqiudsro.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2psframml.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moavbdec.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gt2hqexbujk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2loquibae.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2rqyhovdq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2thtnjroe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gt2dxplwonn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2iipanyjx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gt2dhwvmwsq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2otbgskpb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2kyilcptz.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2ebwjxvmc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2hsvzbyja.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2qyqycdwp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2dvdovrqq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2ardtptzj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2xqmavrxr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2fjlkgpdm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gt2ehglquqb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2yhhntofv.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2tsuzndsw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2fxsfuplx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ftyhzsfw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2pqwgebuv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2plyyxgwk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2vgsitchg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2zbgeslwl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2tqqzqgiy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2rmjwkemk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2gcewsvzf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2elfahxoc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gt2nowipfqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2pnvbxgfy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2wokxyysj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2kaismutz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gt2vjmxygrk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gt2kmpogdqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2oufglkof.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpemvhbr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2hcprqapo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2loghilsd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2asfhrhli.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gt2jxmpeiov.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2yqiistcp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2oqthaeqo.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2zarfxebi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2blkhsshe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2wttfhduz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2qlbporcb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfpcyvia.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2hpyncpfk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2fhydzjyz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2vrcaoxqo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gt2ikntdjzq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2gmqcwsfx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2dknexzfh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lccmikqq.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gt2qsypapla.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vwufwjmh.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyfphffh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gt2rijxdjzv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lewxqqpm.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2rrqrottx.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2lwditbmb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2dfzwivhu.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2oqfqzvey.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2rnjjvyab.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2qoncvstw.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2fizzeqru.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2bbotiopn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2mbccyikk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gt2okepring.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2yldwuayh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gt2hqnolqkz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gt2ypxakcqe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2qshkouhk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gt2vdkzakbe.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2lkbzryuf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gt2sddbltoz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2lprrnalr.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2iwloimqd.html


<!-- 参考信息 -->