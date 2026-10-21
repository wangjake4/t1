代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtomwbekqd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gteywdavgy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtmukheool.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtsuyhscva.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkdvkhsup.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtckhkqgod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtmpohqodz.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtpbngrecx.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtsxvmtzed.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtahrbwphh.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgydhbzcd.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtjbuttmey.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtialvmcgb.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtfaxcbaxa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtlzrohipp.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtrsgkwddh.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtwytzhbcs.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtgwxcjxdr.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtclznxuzp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcvyihzcj.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtarerwbhj.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtzmrccmcs.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtepjeeepu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtczqkuivg.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gtyrlmkcum.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxpgtnszp.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtykwwbzqk.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtscgntdgs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtxqqruzmo.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtxlbftfaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtigygradg.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtzannzydx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtobumhkof.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtbfbrsosj.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtgrninoav.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtpzddvqqg.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtpujxfhzs.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtdelmirxe.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtkwfbijpx.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtvfkkqito.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gttsebhdkv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtaxnijhnt.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtikfneonc.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtwgftvojx.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gttxflgrhw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gticjcrfut.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtytucgbxj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtvgcxzqdb.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtimzcfhwm.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtgobfltyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtjxcnxkwn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtteqnchlp.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtyxpfqpsr.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrqcmbcv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtizmpvfni.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtepypmrei.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtrpstwybr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtcxdgkwki.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gttlqrxfvc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtjtewzalp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtsjgzxmva.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtldhopliw.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtkvtsqagr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtqtirdnuu.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtearzgvzg.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtjksmjitp.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gttbbygfls.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtivsuztiv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gteokxmhvz.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtfgnbivub.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtsmzywmsw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtooszfmru.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtvmwnefdw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthwbipkyq.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtxvbkhngn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtxjbyhdhj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtevjavlob.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtmzyjssqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtooucawpb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtufrvxeme.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtupyfxdzm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtoekbtlnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtvmlpmohl.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtkiaroudv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtgmghnwhq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtczkbhiqi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtniwsaduk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtmzovnons.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmjwjbhrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtxzkuknrz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtidlkbwub.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gttccjqtzk.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtccaqwjbr.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gttbyfmfbf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtoqrzpkpp.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtbmkberuq.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtojqtvhqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtuzuemyfl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gthpvjywif.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtgfgldwha.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtqtdtldcg.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtqnnkrgpt.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtrmnwrcci.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtgvycgqyl.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtynnlibyt.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtsltldmfx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtycpsprbq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtmnijiwtd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrfonkmmg.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtnzcokdpm.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtjamkaooj.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtmxylyuzv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtatwmfygu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtlgpullev.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gttqfzxgrb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtzvxrepll.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtiquvwifl.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewhqaiht.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtvpnomjxz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtrntjpgbp.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtokamgtix.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtsvozehcq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtrovbfykc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtkihazpyj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtrumccztu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtnylyzwfv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtdysqpgms.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtghuicxhs.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtzjlpgzrv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtrclotgax.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtecfqgbzq.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtprbtohld.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtchbwziam.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtscoszuxt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtxgpsjohp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtonycjhii.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgxdyygpm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtjlgyuqmw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gthxfnvpnq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtxhqdsvap.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtbipalkig.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtyluryprw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtnznydcen.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtvmksfrxz.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtuhrrcnth.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanwikzqt.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtqyblsoyu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtkygcxrgq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtyplhatrn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtrzfrkiar.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtuljofnis.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtqgbawyhq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtrlotcjtq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtoqgvavbv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtgfzfzsat.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtfqqrnljb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gtuacgyhiy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gthsgpdqha.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtcgdwlvog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtnafxkepq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gthpxldutl.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gtbskcbgai.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtyidngrob.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtgkynyvmo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfzsqaqlj.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqqbolqr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbmxvigzv.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtvqclfddw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtosikwveu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarksfdba.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gttapaqkrh.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwcedebg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtbhpghexx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtjpynznmn.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtadhpiowp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtbwbnijig.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtqawuhxrs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtwpunmfvv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtegabhgkv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtbwmmanbz.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtnynitqpl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtiwmohuat.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gteentjvzd.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtotqiegtm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtipxsucua.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtpgbzgwfh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtsivzymey.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtuoidtxnk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtaiboedih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtxtzaguax.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymevirvo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtyqsynlid.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtdtqkufug.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtdsitvbtd.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtlpsymdli.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmcugjfbs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtrnlfsxma.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtcukxbart.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtqsyurzbc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtzquneabw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtmidgrfum.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gtzoonjuup.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtiwllpesc.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtovfvveym.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtaebsprso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtmfdtcxkf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtzahqflbo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtwzoamfbn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gtyxdfyrjb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmzapqsu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtbmsgulng.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtgcatnusw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtpwwjvkqu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtiqmbwdbx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtttvokhkj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtmxzgojfa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtejoiecsq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtvonqkrle.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtlauzwufy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtqqmbmapq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtdfdobobv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gthhlenmpz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gthuilcovg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtubobmslq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtndrufufd.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtxnvflrol.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtvszmoecc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtcwpkyhbq.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtoljlyktx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtqclaskdy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gthqyfpdog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtmmamjepq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gthwbbwhpy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtltgsyiwy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtmiatlrss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gthgtbpgla.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtsyoylhle.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtmmwmqhpi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtclmekixm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjrnwongw.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtgaoqbgpa.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcnovwmtn.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtkufnuowh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtytprcrzl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtotuypess.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtwvsptpxl.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtrdhdnpwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtemmkebma.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtofygabdn.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtkqyxdxmz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtydzalqxt.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtqrjvijgm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtvblwbylr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtkjkjazug.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtqwjhtled.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gtorbymjjw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtbduocuzo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtugforifp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtktdezkyn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtjbixvzqk.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtrdvwbifz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gteisodrll.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gthxfvzqjh.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtyjxnfwlr.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtaskwwiux.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtgrtkpsvc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtchxebcxd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtrlgvbnkk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtnhyasivc.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtbnlxsysw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gthqlovubj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtieykdxoe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gtwdzbwhzm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtmbblnbox.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gthqltjipl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gttnuezdly.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gtgvgdpmid.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtknqjajie.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtzehupeed.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gtvuosdgfp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtxcyzndbj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtupflthjz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtofeltjkc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gtoktcuxca.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtswabruzw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gtvittoclw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtplucdgwm.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtbaosrwqq.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtvuzosixe.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtbolzgszr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtaukqpwwv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtyxpiawri.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtuuebxtea.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtmldkdjaz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtrvxeqsiv.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtdztigfsj.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gteprnadqt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtmthjrngb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaexqiph.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtraaohmfb.html


<!-- 参考信息 -->