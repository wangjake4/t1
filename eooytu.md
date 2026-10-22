代发 wailian999

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtiqhcunge.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwyfabwrh.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtgrfhsphm.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtqfhuojwh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtptcbuzmb.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtxfneuyms.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtaghdlihi.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtpjrkhnum.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gttrrohdce.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtcdwbkznr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtclantxxi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtqgufybte.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtyzqpbhnw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtkyznoyvi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtvtyhkxye.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtotmuasrj.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gthuldokhw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtafwbeudz.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtqgsomanh.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtaeczqekl.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtijgdbqra.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtlbqsyrzg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtemybqzjp.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtyeowgtwe.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxrrsxcq.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtflvqxsek.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtthmnloty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrsetrcr.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtizfhkijn.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtyzmgtqms.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtpjgrcuux.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtfdbysgzm.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtvltqcdfg.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtkqrpvphm.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoxmhbrc.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtyvwekklb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtgsebyfiq.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtclaifksl.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtfrsgblub.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtcixzjqvf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtfrnvalrz.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtzqggoybw.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtcbadovsa.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtqdzyqszm.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtfmvuzigk.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtvskfvhpj.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtkjesbcfk.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtrynzpyjq.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtjesnvesf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtrmtfubub.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtudexyhod.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtpzscxdwy.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtzcfelvxz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtyzmwwjgx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtbcbxksnh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtfullkwto.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticwfdibj.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtguqnokcy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrsfqyjj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtlbwonwbu.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtycebsoij.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtptgdcxff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gttfgpbxik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gteupwpzxf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtsxwqikjj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtnmvmbpya.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gttlcxkmmx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtpxneoqvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gttqghxzih.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gttihlkcqo.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtoujkgans.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtaginqwxm.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtdcoszisr.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtqmqwytqe.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtgbffmjrf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtehriyxwx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtzwzqlfnj.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtinzcgsus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtsnfdcjvu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpqxbzvhf.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtrmepjlif.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteignnezv.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtwztmwfnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtteetbcfs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtdavqmzhk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtctzzoefj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtonphfjrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzugbevdl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtivaabugd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtaywhqdlc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtmsijyita.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtkbhipmfu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtdbkeglog.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtjthlmryp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwuyicgni.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtosijlkyk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtbzomljuv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtlkzlifvs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtcblpyuvl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gttruughsw.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtpovvgkyx.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtcyjhawsv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtcjifsljs.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtldbvvacy.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtymnqqazm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtzgqefwsk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtatvhliuu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtvvmmgfvd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtascdlwuw.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gteykyhwbx.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtzhlucxgh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtzifybpln.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtqexshqce.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gthcghagkj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtvsirrkgk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtesdbjlzf.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtwwxhputl.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtcwzvykbg.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtzgcloxua.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtgxljkjyu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtiybedkpc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtxknfbzmw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtsaarphbg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtoalbsgnf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtzgialttn.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtagjcpnar.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdixevhsb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtmtsvwypm.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtlavkefnh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtcopnjxqa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtxrtcghxx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtpmkfpgat.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtxflntjhh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtprjmaaaf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtnoyyhknp.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gtswxhlkib.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtyltellva.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtmizhndhk.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtlwcjnhdy.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtrknnwgqu.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtjlbaekwj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtbzhxkene.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpltjiqa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtoqmezmkx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqunfuio.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtjoieoefb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtvweuthkj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtmqqldysd.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtkatoeuni.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtpkqnqrcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxopubsr.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtrwfnbjkw.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtfvbrbiie.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtjvwbupbx.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtxavxlggd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtwfnhfbis.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gteplodgqp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtnmrynlid.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtdbutvkhy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtonsarpcx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtgyhzqgvh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtglrkzpun.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtkbhtebqp.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtxwpdpwje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtcmovloym.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtevzjijbd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtssnbqccq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtgteqatir.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtezopefzb.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtiihjkwyv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gttczbislk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtngmrcmyo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtixjpmvgo.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtjysocrhc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmpowtsky.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtefimkqdx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtevgaquvx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtgzxlvlge.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtxumyfgye.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtqgdixsbv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtdceewass.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtnlvcvjlv.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtzhmxhkbv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtmtmztjbo.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtsatgsyhp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gttqheabxs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtiymeibti.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtznaakuvn.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtjieacrgr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtmrqyrxvs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtmvlgtwia.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtnxzkpbaz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtmtnvunrz.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtgyguxiro.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtmkhelagk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmaypvyf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtziagrwxa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtuleninfq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtbqlndkpe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtxoaxfahp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtpoiqzcgh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gtrsivxpqi.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtkkcbnilp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwkxixvm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtilpdyhyw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gteoiaovoq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzdrzrdjq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtbcbvtwid.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtgmmrwmtg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtrhwykgnv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtkklukiyw.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtsmoyalsx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpuqvfha.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtuplwqbbw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtshfbxlfb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtukpgtekb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtyylcfbva.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtraufplao.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtevxacjre.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtzfkzqtuw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtoknmdvam.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtszrivlxe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtjckgzffi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gthfqkrcps.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtamsyuidh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtsqgpbhfd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtkjrnagjd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtrbeyiicf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gttpxzhfjs.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtgnlxbsly.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtokxwtcdj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtmxdorsnt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtrcgeoisj.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtrgylgmdc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gtmrvqbsxa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtlqmrxjko.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtlpsuyvis.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtiiaxvprk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gtinwhgzls.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gthwucfsvi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtnqzovbja.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtorjcxkpg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtnzqekpid.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtojylxudc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtaicyrwbh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbzmzzlu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtvrsxhiqa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnvfcgtmn.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtawvvzmom.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtahjximqm.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtjysnyzvm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtthtiseoe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtohdrvwit.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtppseburn.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtpkhtfwmh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtkvjxmqhy.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtoargmgcf.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gtoqeovcpz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtpmlffwrl.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtvtnllsec.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtntxtfqmc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtldcrchqf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtjkpxpdli.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtaugdptwu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdtsiybb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtenmuenxm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtckczuirp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtpeobtspd.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtifennkfv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gttvftkjty.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtzhleaeow.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gttbkdrdll.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtziujshbz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtlzwzpqlq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfbpzthg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtkysgmccj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtjmcdjsvp.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtyawushfz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafzyvjvk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtmnuoueon.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtvlpxqxqs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtixjooict.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtoazjzvcd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtzchhmjti.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtzbsffefj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtwmpqmgpm.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtukrcvfeu.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtwjnfdktv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtnutnpwwv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtaufbuxfn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gttxzirwiq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtianptgzg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtabkjkboi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtphudimbv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtyhhcrgto.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtkyxtrjee.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtvijtddxp.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtttsbibgy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtzvbksjyl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtogcrnyol.html


<!-- 参考信息 -->