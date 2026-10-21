代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtcndfreun.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtyglzzmre.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtdjlnaryw.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gthanhgndv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtqkylntut.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtueudxjzk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtnuhoqxhv.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtdyakcezq.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtimpyxzro.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtqlnqrquh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gttrtthxfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtuplhldlq.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtvmmdjjwd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtrknfxthq.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtsbrhwrbz.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtddwruzao.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtkszxcobs.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtcvzwnulz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtvhblxryu.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzwoqbil.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtgpyklrhh.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtlbxpgcsc.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtxoorvbmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtpkmtohma.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtmdxyqoww.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrzscjsbu.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmphdtkwh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtxqhntvpa.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcynquob.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtcedkkjho.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gttgyrkyjx.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtqezmfdrb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gthtrytprv.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtrrxftdhg.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzbshnie.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdyjffozo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtzsedmibx.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtcipdopoe.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtkteriqlv.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtbbuvnxsd.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtdsuxcqri.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtkuxfxqsx.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtkrmbzkrt.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gthquqcfgz.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtmbqzaqjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtrixvkzqq.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gttaayrugj.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gthjaqxzdw.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtblitreix.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtsdnoypfo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtjkvsohyd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtzvygaboq.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtumigvhfh.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtvbaufwha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtuzzkfqxl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtwjdkwisq.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjojwwbrt.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtismwabsj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtkztrmytc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtylhyqvkg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtmbbibsgk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtdhvrdfbf.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtscfljoqn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtmdaeiyzo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtzzysblzj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gterjbfyqa.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtajgnfduh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtbqpzscpa.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtqnojpscr.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqxkzjzy.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtyntprnqn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtjdbiaglk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtoxnivvne.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtqmoltoab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtjidedalb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtecrvpqbu.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtenyukknm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwyvztqnj.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatvjpakx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtchsblufq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtgjqibsqq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtomjcxebh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgpngxfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtrgmbdxyo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtypgkaenv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtrxrysszv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtdhhzbcxq.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtlzcqaenm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtiarmiqze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtxwhddyvw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gthesdhvvr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthugyzfsf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gttmrmrrlz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtkgeqiqts.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtylsfuwpq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgxzwbocy.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtaxzaites.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtytvegpcv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gttlatsevw.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtvzzbwqpn.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtdbpqjbaa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxoytmzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtbpugagji.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtjfpohiee.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtsnvxqgwi.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtlveijbko.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtvwbeyxfs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtxmcjjwcm.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthchjtyiw.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtrqjbxqbd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtsdqcopoi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtknrasqlo.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gtbijzsomg.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtydbrwspl.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gttiljydff.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtkuuinimy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtqsjjbybd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtyljzpktv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtcmwisqnh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtdbezxynh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtldfrlfpd.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtfmheulzw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkvbwskqw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtadqaezso.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gthnhehrsn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboxuzult.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtkdnbpfpp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtgjibqugq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtmspjdzwb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtzwmvqrrl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtagzyglad.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtclkzmcsr.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtbakmppzu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtqpxqcxwc.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gthmdutgmg.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gteiysxsgz.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtphnjfdht.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtsxxkwzqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtludnvqcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtdrchkjbd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtnpxhyjnt.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtfbeyrypz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gttcdogerf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwtbumio.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gthpgqtodg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpxldntp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtbsyaawua.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtndxosgwe.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtgllslgmq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtaxaxnzfl.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtrovmuuou.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtelaaqfrs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gteshddkal.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gthblvagae.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtrvwgovlj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtivurjdae.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtzdexnpor.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtzkwikyzu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntxmffgr.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtacirfxip.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtaeefdxhj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gttbbpvjru.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtrfixcynz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtbxeqciso.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtmjjurpvu.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtdrjpibun.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtttxnmqex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtthvsumdl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtiflsevqw.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtjyrqexgf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtabewwjaz.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtdrkkcwjj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtfkfrzves.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvnjkjqc.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtokrybrci.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtuzqrwztg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gtuqidztwm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtcvktymzt.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtmdlqcxhk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gteiqxoxkq.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtkzwwvxnm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtumnivdie.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtheeltwrb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtytwcxngz.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtfdrttxyw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtqquxhcgw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtngbomlus.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtfxddmnhx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtpuuigtmt.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtbbwclfoc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtlxhnirmj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtrmiifokr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlmnciug.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtnzawoxht.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtrpdxemyt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtdjxmptgp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgchudubz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtvhbfbrxu.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtlhrzxqgw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtwhbvwcfi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvscakjtq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrrgygtl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtclchstqe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtkjbadrbe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtkrhgiizv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtqzagazun.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtjutcyybc.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtfpyfermp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdrpnvix.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtukuwjukx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtfudgibus.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtxyoescme.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtfzfwcufk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gttdzyrlsl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gthkynflnp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtnqvlsnvl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtmlokhmss.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtzftaiikj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtyquvdigq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtbseyhgrq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtdlmilipg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtqkpemqeb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtgnqtxloo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gtvseynzwy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtiiydknuw.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaphdsdx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtnwkeaise.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtswxvtagy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtnqosyxeu.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtqryvnqfz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gttuxkrsyu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtwoinmcdy.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqgrpfym.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtbwhgnwml.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gtcogcadqh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtkkxzvute.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gttvppmiic.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtjjiwycgu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gticollpin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtmbduqwzs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtttfvbzum.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtvlruxqum.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtpzcslsfx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdnfolcbx.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gttlvpcxec.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwsufyjs.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtsdoilrvk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtztzfvqjh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gteyzebgpd.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtqlpjmqhk.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtrihbswzj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtsmagwmjv.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuivixugq.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtexzvgcfn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtmcircmjg.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtifniqofb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtwoelfwip.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtooruuniy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtwkhlvevu.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtibiihjwn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gthhwhwruz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzfreurs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtdasabhdi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtbbgflyow.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwdayoir.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtzyrqviji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gtzbdrkvuz.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtcjakpbwr.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtqanbqufi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtwysecpmv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtdrjshtca.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtuhqpbpfl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gttexgcxur.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtdnrlcyos.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gtsvfxpbvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtaawwexmv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtfuiwimal.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtgovjyjra.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtgtrclepa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtepemlvza.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtozxbndvf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtakysxonu.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtsjccbrqb.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtdgvqxehu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgclpmowk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gttpiyuhjt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtqvrlcqlo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtktfnfnsv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtqeolrbsb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtkdilrlxx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtbljcyujn.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtatdfmlej.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtrdczowqn.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtupifpqyj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtxcekrgup.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtifjuxwey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtiriheahr.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtfesgrvoz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gtqpntdvcv.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtdhykpbzx.html


<!-- 参考信息 -->