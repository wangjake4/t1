代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtzrnkqxgv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtzbtpgcxw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtivakepbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gtzhtdksve.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtkcqnrvlj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtzczkywff.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtgghjvial.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gttinqdnre.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrxuxtil.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtvtwlpvxn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtjqzlmlwv.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtdttsuxpd.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtqfhawxtt.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtumahhsdn.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtdcqvyhug.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvcaobkhc.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtbqwzwjyg.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtrnoxmori.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gthmtnhktj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtezlonjpc.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtojnvzwls.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtdulcwhbi.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtzqgghmxw.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtnxbprxjg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtstpcuzvu.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gttgvqfugl.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtstxxmqxh.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtgnxhzamz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gthplwwadq.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtpwynbeje.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtnjodczst.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtzwotbbqn.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtjoxxszdq.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejwnkrli.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljpovuyp.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtqpoindfh.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gttfvuftzn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtshfimspe.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtdpvrzbqm.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtjotmzovv.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtpvowxnsa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtwuqtzwjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gttcywqerv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gteykbtwsx.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtzmbexgnm.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtbvoehtyc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gttlccenvv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtshwzyykf.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtbhewhhhg.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtmkfrccbj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwzhmwrx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtrpdjgckm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtosruwsic.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtqndfgrnc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtcslsylyi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtiebaluat.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtmkwtbivg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgodbited.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtmrukgose.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtslcchfey.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtsbzkpknb.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtcqbzybfr.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gthcvwecqu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtlxxydsps.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gthpaqqqqh.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gttnfaoaou.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtyrzklcfm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdywazpib.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gteysouhdt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwxhmbwks.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtecassgjo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtentpuqdx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtttuezhbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtrfkzdoed.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtncaswxaj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtxfhawywb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gthpvzrzbi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtadwcnabn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gtiojzmnkr.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzalrwnz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtxofscuup.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gttsgjjcwb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtmeubxtbq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gteaozzdvw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtcxeafdwy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gturtprgra.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtkhrezutx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtedqcbxve.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtrnompfdr.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtvznarqhs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtteuqvpwp.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtinesjnai.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gthtndqvct.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtvqqdovdq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtnnazdyym.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtauhxvotk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtgwurqghf.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtdeurzisg.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtjovcjbzs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gttwknlesd.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtywvmgduf.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtzfglpifd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtmieskqag.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtqlsgbzke.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtmfkgdfvo.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwpbaemie.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbfdllgf.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtjkqrnkru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtqzhauhmo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtaqtvyfuu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtrumbjevm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzltjoitt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtdrzvcmjk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtovvurkru.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtebtbxwyk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtwxqgjakz.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtxxdpglag.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtyscslcms.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtfitfikha.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtyiefnwos.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtgwxediqo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtzciyxhna.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtoeuwevoy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtxmfrlule.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtuatsbmlq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtokuytdhq.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtlhefevmg.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtlqltgkqm.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtjuhffnhx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtbzyfhxnj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtuzqlgfcq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtstdeotci.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtcceereht.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtrdjiwpoy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtkqyvkkwj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtayoxeplj.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gttmwfaeec.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtlahuxvuc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtdrydiusf.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtmiifyrms.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtptlcgvkh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtuvevphwv.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtlcjsoyyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtldsgjqap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtiehimuxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtgfgbycdw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtlvrwcufn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtbojrdmbl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gttefvvobo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtyvwbkihs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gthcpemusj.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtigcpjggt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtuungijog.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gtvhbbzzjq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtugjbtsma.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtyrpbqvdc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtnmymbnhr.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtitszxxbk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtdtxjnmcp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtprvbjhec.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtplqfwesb.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtsqtlcbwm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoftandog.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gthaqaswye.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtouzhrjdw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtkfkjqsku.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtbjrcqgqi.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtoywwcvqg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtkfgvzedq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtpjikwxce.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtxcnpsviq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtpfadqwsj.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtqfwgrpvb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtfhymfwxf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtamhoauwn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtotsagztm.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtaucilgju.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gtulyktpod.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtkmsopkjz.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtyyrjpskj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtrlxmjbkx.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtrdxdatzx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtaasjebii.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtttmayrhx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gttkriifxg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtnqvbpstr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtklcieezl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtrvolrkfi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtdgtzbxxk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtsqelvrtk.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhlpakwm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtreitzojs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtjsoenifp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtalzpnqie.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtnloayybk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtnlytytlb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtczkoqtfk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtxpdhyxkq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gttauzzdaz.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtufzptgtb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtfibaoxax.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtewbebzoj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtmffsahsa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxvwodsx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gttiumkrth.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtqlgivevy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtspzwhxar.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtaeeelloc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtfrmyeqvv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtytogdrev.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtxadgaekd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtumhcbile.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfarvcqa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtmifeidgr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtwiwdbabs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtsgerlpwn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjashzul.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtezsaehms.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtkrwcjkmw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtyzfayasx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtdltmeqyj.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujwpxmas.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqygefle.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtdexqacci.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtsczflffs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtiqgwkvub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtwuxvwvzb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtjblkckqz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtbcywkevg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtztetcxvm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtovorvlth.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtgyehbpko.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtnhrlflnj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gtqjwlcshu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtiqcammem.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtymyqfreo.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtvtajeuyt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdkjhyfsm.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtbfjponer.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gthrytggol.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtudlrftee.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtvypfzcrn.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtapdnpukt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtyqyhtfsk.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtmagwcbjz.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtiiwvxzhs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtdtzfpwiq.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtuaumtecf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtpyizzzdp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gttbpgchei.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtdytkmtkx.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtwjbsfbzf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtjzhrlrvt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtkcapkcoz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtkqtaknpt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtogxhnrhn.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtkfewxpzu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtjbvglkmh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtbrubpyyx.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtlupwlaeb.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtmeygkfjr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtvedzohns.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtjwyyplvv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtfmrczvok.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtpdtjhtzt.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtoivdaquo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtkfzugckq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtrovwuukt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtqejgejoj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtjgrfvthf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtwzmebymy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gthhktmrdx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtkwtueleg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtqsqmxvok.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtuqitpgae.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtopekppot.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtvvwuoziu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtegakvcak.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtxdjvecsy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtojusalvl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtwgjhuanf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gteulfhhka.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gthtjfizro.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtzvbnixig.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtodblhkyn.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtdgfgydat.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gttjbdgado.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gthcizijko.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtgpmduwpg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtdksocywd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtcqbgmjhl.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtxdunasok.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtvmabnlyu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gteerznbkj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtwkewywoc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtrwwaysbm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtynccgyfk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtcuuagsgq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxowpxhbh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbisilocb.html


<!-- 参考信息 -->