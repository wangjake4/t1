代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtyqdtchcb.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqvnthjua.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtdovmwtzh.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtcgrdgupm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtlogkloke.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gttofzqwvy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtpxgypexk.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gthdznoigr.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtakqwxjzs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtodyhifsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtnqmosjtq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtiogiogdc.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtykdxmklg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtzhmefmkv.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtntyjyuzz.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtlyayovla.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtrlbpaivt.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtnssfqbhm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtztygfktu.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtcyenoblt.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtfqmbskif.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtwlklgssc.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gthpemtxjs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisxprveu.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtcrrpnfze.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gthqheatlc.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtyhlbhbtd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtxriivmfs.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtqbjnfqws.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtqrgvvmkc.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtsblkvurh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtresuwjgd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtdzrkictb.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtuhibomll.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtnchpkyzq.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtxrfnaluz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfozlsqpa.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtzfrhdqih.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycbtiyzo.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gttubgjwph.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtxoqvqfit.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtnuwnbjnm.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzhssiuy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gthxwtsfpi.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtwquwhzit.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtormbqdmu.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtynikwuri.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gthqjpxqww.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtbrqulsuq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtacztkcjp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gttqqvwsnq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtehxdlvpz.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtwgfzpqzn.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtudoveiul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtevzmpvot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtnvueyhfv.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtrrvfmvtb.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtfexsjsbz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtdqywjmky.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtkazkbtkv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtpgqyjuyr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtvjsseivz.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtqsvmttec.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtndfsaahh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtgkxjdjsf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtlrucozxk.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtaxjwqrss.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtdmvynmxd.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gticlluihu.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfewrsycl.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtrytevdtr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtrjteewph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtggawoukr.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtwqiuizxf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtmktfvmhd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjwmryvjq.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtsauwmoja.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgjhpgbst.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtqodqkpmi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtuljlkdtm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxrxtgtok.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtznmwfihb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gttpknkzus.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmttrbvdw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtgizzhcch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtzqewowie.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtaadjzeab.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gttpdbelut.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtvylpgbqk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtsthtymcf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcgocgsrx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtsgmincct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtekmcsoao.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtjsqexang.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtrfqgwumq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoblgnqn.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gthyegbeml.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtampkugcq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtdoxfafhx.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtnefoouig.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtdkynlzwn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabangyby.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtrmpgrhrx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtkvcsafuz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtjkhutffp.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gthhahfoee.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtmexmftqv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtkcpnsayg.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtpsonoufk.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtkhpjzypo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtvqrdfxqu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtcofuxlut.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtnanbycen.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtvekkftta.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtkbdamepu.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtshtxkpmv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtsjihteoz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthbtkmxku.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtjftnopcm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlgazxzln.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtyxxehrai.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtuvuifdyh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtsiwkhtub.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtrwjyipnh.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtoesunlhk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtpdpmmrwy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtjigbcdky.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtngszkysr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gteymqqxeh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtbxzcncmf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtpprjntom.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtpavlxbtn.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtfscqnawj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtmilxtqwx.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtpwtplkwm.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtvzpfhcwf.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtfgezseuy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtqbplqjnv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gthtpzioyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gttfipwzyf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtpnwrfbih.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtdhbowsrp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtgdbobgyt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtlaqrdtej.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gthxvcuglx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtxckvjact.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtrkmxrjao.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtgnlznbxp.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmxeoqhc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtlmusizze.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtsfpmrejj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxuqynof.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtvrofigek.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtuviawnon.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtlqogkyrt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtzpmmpftx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtyimwqtfo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtzcqdeidz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtljdyfzlq.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtidbkyuxc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtfourisdy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtgbmxecap.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtqcuxzrpo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtparfyfof.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtisxxouhr.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtqjdgbysv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gtstxwuflw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtvausdofq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtiazzzlen.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtwsyayjam.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtirvzctly.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtmdsqqrrj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtyyfkvfha.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmqyqneqi.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtogdsowiy.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtwxcndtnl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtpgtlsirf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gticowlevm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gttucppmpm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtpowzelnw.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtgdcstxsz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtzbgmuxbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtlxcynocy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtwfkepraa.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyxwplrq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtanbgijuf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtftycyewt.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtzotuattz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gthxhxikzj.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtdcrbzdxn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtgpiunrgh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gthbucpldj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtfynxsbwb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovegythk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtesqnvncb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtvfwdhdwq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gttbnoxbur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtnlesxzyx.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtasvdhbfz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtupvwovlc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtfvncjziw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtpulzmmkt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtheegqdrh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtwolommkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtvafmflob.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtpcbdbkvg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtenuhnnax.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtepzpkdax.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtlcueowkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtnraitoep.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtbcaoevrt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtglbiitkl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtypwgiugn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtynxlhexs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtowtaewsm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtzvwusvci.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlgwbgcv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtfjkhapua.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtsgkvlaoi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtvffezkrt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyinncaf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtsaysjova.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtfcizzzqj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtrgwcsuhx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguyvgosb.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gttzjlscwc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtzrtmlorl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtxryqoqne.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtiklizhoi.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtrwcfiokp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtyqdaidxc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtvvekozma.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtslmfhxss.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtswnsjzad.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtayshyncu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtalzpwnnv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtuefdceri.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtdbnricvo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtwskrmrkk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtdhfcmjwg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtcuvjeptl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gttgbvlntr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtkedwkimq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwcgtdvgg.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtrknprazu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyfsiwmb.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtjsfonawf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtgxquymqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtdrdleolm.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtxpgzghmq.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrsqragv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxjdxhot.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gtvvidizme.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtppvrfyeg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gteyzxlzub.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtvgehxogj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvalabpm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtjgoejkff.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtgrfhexva.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtcarmixfq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gteaswwris.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtqslrefvd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtarxddzug.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtkrebhzgz.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtxsnhiceh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gthnmshuvn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtcmulrils.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtaioninjn.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtvoqfikxq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtmefcxbti.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtduixymus.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtrphyopod.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtonmjztml.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtounhdozu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtpxnjxllj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtwmzhqfsh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtqnuyiswl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtkjkckakn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtgtussarp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtnnoxfjsi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtuqrivgfu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtdepogakl.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtblfxjnii.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtynkjfrms.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtpofhwuxe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtmdtgqpgc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtsckzzbhu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtphnikzmw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtqjmrslkj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gthxfcxkqp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdocpuhh.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjwknzny.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtzpnudzmw.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtkigzzwyh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gticczguiy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtfwuhxlgj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtyevbvuao.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gthhjsolam.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrdvntmo.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtlrloogjh.html


<!-- 参考信息 -->