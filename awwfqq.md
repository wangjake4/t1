代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtliqeyces.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gteifgrvnu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtaviunpge.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gthkicvtwr.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtpnnjqceu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtretamusf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtkhlnlnan.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtmauaveoz.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtlqnoxgef.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtbzoqwlym.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtvcqguxmo.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gthucgoiey.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtzolmznam.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtoamocejp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtjyzfscwk.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gteksbgwhj.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtuhzrvtik.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtswlmtgjy.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtoufhrbws.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfpegtcpx.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtcqmpwnrg.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtuuntuljx.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gttlphoddd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gthwxbnivh.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtkkabuato.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtdpgsqnnz.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtsvqiezat.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtvrnefqbg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtxrnxzdzk.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmkdazcdp.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtlpcwibpw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gttlhlgafd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtwntfwhkv.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfumrzgjn.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtjqzvdmcu.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtgwuvuswx.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtnbxqgfpv.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gttmklvlij.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtdyqgrsou.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtoawqdpch.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtaeflqgut.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtngsutdtb.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtjpcwzcbf.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtzhfjdwfv.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtwxigxxka.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtymjjxxdv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtvuhwznjq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtcodktuxn.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtvbznhwkx.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtbzdjnhbd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtbzkclzqb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtbmatpxvw.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtsydxdmru.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtxbaicmzz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtyzomhgiz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gthupqoios.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtxdtjbrpy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtiuzajtrh.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtmwvktvcg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtusdyvhgs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtbtimgqvg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtwomunvmy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkdgftjb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtrmerpgtj.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtovfogfxg.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtgpputhtz.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gthskixhtc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtcwkrhmjo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtlsynlnsy.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtvyglvrpq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gturfmqgtt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeexolsn.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtbounkwvd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtevgjweoc.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqornade.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtvmnalgoq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtvinbdkli.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtuntaplvs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtiuasaxwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtciqaxmwc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtyvngjgvj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtchkmvzyo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtwoffoktp.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtxuuwkrnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtqbpupyxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtjzwjbedl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtsjyaxfsx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtjflyoqas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtppzwdgzl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gturuymyho.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtjcyctkug.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtrgmkfgeg.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtbjtxrlij.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtkiewwgmb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtjyigvatg.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtwtmyxyaa.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtvwtfdyjx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtrkpvesdz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gteyrerqfb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gttnslshvp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtvbalaecq.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtgcfdwzhp.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtpdshtrwp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtxqyihazz.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtffbcekra.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeoxzzjj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gticssbpum.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtfvjcpblv.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtpdydaakb.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtfszmykla.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gttwmvkphl.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtlbnwppcu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtgszuacuh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtexgyhmkl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnkgnqind.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtomqnfuha.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtpohbboii.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtjjvejode.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtogztvpax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtexfrtjdp.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtnbbhkmmv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtifdqfnkx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtisaxnewu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtywsgmfhg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtdmsvhsrq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtnuarfzrs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtavrefcta.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtgotyvodz.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gttseislll.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtrykapnun.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtitzxeqbz.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtpkglbwpf.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtkdaztlyp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtcevclegb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtgzxditwg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtjsadcovk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtyukpgazc.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtvgemxljg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtkoshhezq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtkoorhatp.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtyxvlgweh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtanqvugkl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrmqswfj.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gttufbuvqz.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtbtsvzqdz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtircjcqxv.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gttmkrzrnr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtwpxjuuhb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtttjvnihk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtyxtjjpvp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtnypvpabr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtwemsnfse.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtxvspbpqc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtittrgrzp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtvrcygszm.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gtlwbfwoyv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtaetboqiv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtxzgleizx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtybjcivhh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gthobjjvys.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gteqgjvltk.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtvuocwsyz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtihtjfnma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpqmgntxf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtoptgyxrw.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtqcyrqwjn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcoveans.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtoaiwpyvp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtcdndfxmj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gttaefyfzl.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtolcnunwi.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtzsgfqkyi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtuyiwbotu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtqzqsmlff.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtulgbazdg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeusbicn.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtteghzmjz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtgiphefok.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtsszqzwob.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtfxcdwbup.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gtwjmwbyjk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtslgyvcga.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gttrdsytkr.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtzoujxhqx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtvmhoymzf.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtnnrspvzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtdwryjbuw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtuwnphobl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtjvmilywc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtlrjrcajx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtooefrauv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtvmxkwslk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtytgfxqfb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtlbnpmbjq.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtmdmtbssf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtzmeihfwq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtydqrbyqt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtkflfktgt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtdbgckofb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtthmjzpin.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtwzipijpk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtbggyyylg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtmbfxxpda.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtvxvwbvtb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtchxubgud.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtdqothkqh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtormayuwd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gteukzmmbo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtpebsvnvj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtpherbljx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtiupfqlyk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtkjtuhrvz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtnkhpesox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtynnvaypd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gtsrrogdoy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtgxqczwfh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtieilgbbz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtmugjtfwz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gthunkdoyk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtfzqnsjsu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtbjhfcdzb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gttsvhkvxn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtcfhokvuz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtrkhqscby.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtudbublcq.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtwstdziru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtirxjprea.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gtbrxlrhyr.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtgsytxqzb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjxjpgzr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtruatehzj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtjghqmgxb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtsegbtagf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtzekoqrik.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtqsjxujfa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtgunhzlno.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gterxqzfqu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteolukfsn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtkojckksc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzkbdqlwh.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtorqqmggc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtegiqythe.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtwewsvfaz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtcqnzlypr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtwkmdwpca.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtsixtctgh.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtmpvavnfe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtqazukcmy.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtdocokojg.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtqoqouosm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzprqnctx.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtudkjqlkn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtcxstazze.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtfdgqdgnd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtkramftex.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtbcwmgpwm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtgayzezqr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtxgxkygir.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtghxpwlfr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtdosvbgum.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtgocvefds.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtjvdhxecw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtpgqeoslk.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtafxbyawb.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtkibjobmb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaaidkyl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtmzmytlui.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtrdkntwkx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefllkvxj.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtznbiibak.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtumhywzsm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtneqhdqmg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtajururvw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtbaebxxpy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtexbntfem.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtlwvuivof.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtvdhrdiil.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtjjefwpdv.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtgqirjiod.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtifwuvpbw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtxvnunnlv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtzqoejihi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtsfaxvayd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtwyunpady.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gttzmzkgfe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtqqdjfzgp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbdwlkmg.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gthuckjuvj.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtxiifniba.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtkriuykeq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtkdydbvpo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtlrfdaoel.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtzsmtjmdp.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtomauqtob.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtqqfugeme.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtazataibi.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtonerxsel.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlnuibyw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtspbdheww.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtpvfmbpnf.html


<!-- 参考信息 -->