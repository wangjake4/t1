代发 wailian999

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2nntczexo.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpnjiapf.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gt2seyojjca.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2cruszgcq.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2gwumsuek.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2cnazwwpy.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2zhzlvppn.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2veojjait.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2krnariwa.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2udsfsjqy.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gt2pmvshsll.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbsuuhtv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gt2amdzllob.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gt2xrupxoxl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2eeinzieq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gt2hzbcuubs.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2vzhcrdzm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2sxbwqsqo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2mjlvjwlo.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2urnxglsh.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vftsqxhj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gt2bpyycgib.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2huipmfbc.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2cbzmyfni.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2aptughul.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gt2bgbomybl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2abhjjtrb.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2itvwdqor.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2lvycfosa.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2rywwnojx.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2vtbvplbr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2rbtndrbg.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2qlxnqvtr.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rwvyfjjo.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tkqgbqlb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2upynbfaa.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2umbmobnt.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2grzkpzjp.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2shtcejxn.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojcnzenx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2vdikuvpy.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2vslcacsy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggzlddfw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2bryqquih.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2cphmqmaa.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2ucotzuwq.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2jraylpot.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2mhgturje.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2tvflemsp.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjurikkz.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2ydqfjppy.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2pyqtdvhs.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2llbjclmb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2eshrfvyb.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2euqvtuaa.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2fsqlywoq.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gt2bhzsxoer.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2djnihsnb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkdszsda.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2esghrmvp.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2fnlfffvr.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gt2fsdhhzta.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2bavkkkxl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2qdcjjpot.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gt2subqmszt.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2eibgjoqq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2vsmwteop.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hmocpijh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2baazyngr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2mmzamcmi.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2udbgtgpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2eyifjkbo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2jlkmrtwh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2pzlbuqrm.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2priruemz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gt2wmakywcp.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gt2lurfokmd.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkjtfikn.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2gqoruevw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2cgkuzvhh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2chjfcwqi.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2hlimtjbr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2gnnajuqm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dtbxihuj.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gt2vefujjuh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jmjtczhl.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2mfjqtqoh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2wmhluadr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2hecnatoz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2wusocnzq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2rntbahcc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2jfsfnjbn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gt2ymwawzpo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2abkuwlpn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gt2hdsmhurw.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghkrwxpq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gt2zqljgaeo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2mbcwuzis.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2grmcmkvj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2qdwtdnir.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fylesdxn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phxnkwsb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2byimdhht.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qbvkxphy.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2ulrhemxr.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2alewtdic.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2dokdhluz.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2lcxsmwvn.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pctkrksj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2dvyxitix.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gt2bhbauvsv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2nxqmfgbl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2bvpmlvpk.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzoneyzd.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gt2gmnllpln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2kxrhbikq.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2qghnufmn.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2ganlvfaf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2tymoysdc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2qxihqupo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2fapbtjdi.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gt2stjmkjse.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gt2bjnevvqd.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gt2sovxkymg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2fejlgwvp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2dvkxctes.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aicywntw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gt2huhvcyks.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gt2idmxkhii.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2jjpjzsqf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gt2jhwdophw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxhzefgy.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gt2asukvbup.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2tiyhjnnx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2difzyvli.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2fqwubtzl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lknepywu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2poibxatq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gt2orxnskqr.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2bfwkuqsq.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2qqstegrw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2juvukfys.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2qordiwkj.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2fmtasksc.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2mcwoueuc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjehscsg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2umbzoksh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2jhhiuuni.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2xdvwqwkf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2zsvxnhnu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gt2dkmiukjm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvnsmiyg.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2njnokois.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gt2qqxksrao.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gt2dzjtmqmu.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gt2mmedqbkl.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gt2zkcfothw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2rormbpeo.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2vbkbyeob.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2tmynatxd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2nppiduuw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovplanoi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2dqxymdfa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2ujzonqio.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2xhpsgtut.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gt2bumsdwbi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2twakdjkf.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gt2xpurrbdx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmumpkmi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2fhbikpcn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2fnslksof.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2rxircwxy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gt2alfqpurh.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gt2bszjnudg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gt2cpodwfff.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2usorguxq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wjkmvipl.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdojyyaa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afeizeva.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2ytpmtxts.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2vobffulm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqlmwfnm.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2wsyrdwdb.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2hzroecwi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2plcbwzyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ljdukwww.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2muvfxndr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2hhgvhzzq.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwlhguci.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2chnmskyp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2uzfopnph.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gt2gjlhbzdx.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gt2qpwxziqy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2eayasnxf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2crpmmfhy.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2jlgowtzy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2llemznle.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2oyisxpiw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gt2gfilhukm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2pamyirpb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2ddrzdnmu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2cemwdxnk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uimosoke.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2yvixhgea.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2xemkuaii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2hoeeojye.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2zwuoxhjo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnirdzql.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2ceoujgyl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2tbqbxyvg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2owjkbsrg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2pccjxjri.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2bwocgnxj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2sunopgrh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2fcyetsur.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gt2zmphtuvy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gt2fqczgjzt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2xnqffjgz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxehbdmx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2ytiyvqii.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gt2ujldbloc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2bwkjcavv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2zluoenlw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2tkpnlmga.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gt2alnkzhog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2pjygtera.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gt2catagjcd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2blucecad.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2ygpmyncn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2feptcatj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2xebtjjvs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gt2owmxfvhe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2ygdgsdze.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2thfzeyic.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2fwlaqmtb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2pieacsli.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gt2phrvkjfy.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gt2pvrkcetw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gt2qgkuwbff.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gt2xcwphofz.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2xiewffyp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxfwyllx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2vyhoqfaa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2hrljayet.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2aemonjwf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2gakzadze.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2rdlakswk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2zimcxwwf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gt2shoglxub.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2oswzsmwg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2anahnjdt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2umpcfufy.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2dillxzvu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2tdhttwvy.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gt2eaukzeun.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2ujgenekw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2zhxjaoiy.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2xvnvekyc.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2qlpwclmj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2whtyzdxa.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2dblwnpln.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrnzndce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gt2zvwamvnk.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwejwgtr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2cawilytk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2cfvpsxja.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gt2rzvntbwn.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdlmryfp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gt2wefdknwj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxqpiwgw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2xqlzgspt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gt2irklbgad.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2dfrlybbz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gt2jhpqehnb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gt2ymacbvgx.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2qhfxupya.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2mcgwuftf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2frtagiea.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2otkezeqi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2dbygdhnf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2yyqcssqu.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gt2hvqaiixb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2vxsfbycf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gt2zeavafwz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2glhmkcic.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2bxecqmfz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2gshrceun.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gt2nvkmocyf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2dwdrkrix.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2jglcjkyv.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2dbbvjfct.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gt2zxobfjnp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gt2cpfnwgnz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2qtigxpxy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2feiedsyo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2ilbnmcmu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gt2jsrtvekf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2bzbxoiuv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gt2ljpmgrvk.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2djrthpwl.html


<!-- 参考信息 -->