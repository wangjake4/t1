代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtvkynklve.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtqvkdaqdb.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtzrvakswo.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtjsurmhri.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtwotwjiva.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtdwspqpys.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtskqyregz.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gttqdlcalc.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtaolrfesa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnuslwkh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtpzopgmfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtbbaxmksn.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtlbffhrjq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtsscnexgm.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gthgkgqvvs.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtumpfcwak.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtfuxguzpe.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtutwhslch.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtmcoiwvfr.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtxoeqntcn.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gttkdketdf.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtwhivpgps.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtzfqbmqac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisiornho.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtdodnidoq.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gttetdzdzt.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtqggeppit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtxbbqpjlb.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtgwzkclli.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtmjaedndt.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtefjjvfcb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtceiddslf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtpcjyoxru.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtgmcswrks.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtroadawbg.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtnqzqqnix.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtvdhgeuxj.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtnskmmgwf.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtflavkead.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtgvqatzly.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gtdyhoclbp.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtxwtxdyxl.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtysqfxhfq.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtxhshbmfz.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtupdducjs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtzcgiyvxx.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gtxycqbgdr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtdsadtpst.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gtbvvllrmm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gthezpvudh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtwauklvzp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtmbfpzejk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtopuupyau.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtejdxazhb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtypopyxrk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtjzwzseop.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtcutqpkih.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtrbquppsk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtqipfbydd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtxestxmtt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gtzvcylypi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtjepahwzc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzkeasof.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtvhpitqfi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtvfzimtcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtfaokwzvj.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtpltvgfoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtrxgohjyf.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtyavzawlr.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtdcyypwbn.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjzhtcgfu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtrqmsqhcb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtckifligg.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtpncjjxsj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtqfwccwxs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtprvwfmlt.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtlzzzclcb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtyidkjsbs.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtmnpsrayf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtqnvoimfa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtbldxtgov.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtefmjksfl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtdscdthyi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtiihsrfxu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtbhadgcbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtfigcvixf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtgptrvngi.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gthiztbbkk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtuhrbymtj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvsvkefby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtxbrbetkw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtntslwxql.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtdhnsipcr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gthfsushmo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtysvbaopx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtfjfnlaze.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtynpldxvt.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdutdelox.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gthvvvmapo.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtugvvygol.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtgrxsktia.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtmuxahsih.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtbzpirpwf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtgfmpyvgl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtnfprocdt.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtuhyqugdh.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtdueegpqm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtdjvetivk.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtmjvqiglv.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtomsdcgdv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtjqkvkbod.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtjeiqupzx.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtboqmttkh.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtpfrshmwp.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtvvbvlniu.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtvxhundfo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtqshuspft.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtenbaatus.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtmlftvrla.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtavwyplbp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtucakytsi.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtpgaxfido.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtxgdtfxly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtrqyfsnfr.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtmtaovyqo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsogthkh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtkzvauxhl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gturkuubgo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfovecpba.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtvmbkitxw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfwfoiub.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtamnhaoaf.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gtpbfjdoou.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gteqfegthd.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gtmncmizku.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtsmfktdsb.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtpeszpwcw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtuagvhgcf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtudxmxlkw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtsgtlqdtt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtucuatppk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtxraqjaoe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtcwoeqrbs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtqqsnhlaj.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtobtvzmgj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtywuohetp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtuchimxdd.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtydkwzzzy.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtgtzgpawz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtpmpttqxo.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtesghqotd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtwbuajbco.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtghtcijcr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gtzbputyat.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtpqegnsjx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtsxhchlrh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtifpkvdlr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhanetoe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtarlemexd.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtdlqmbxgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gtimdqhztr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtpuisjnpu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtbvcjijua.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtbxmgfynv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtzuvzchxz.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtegcwfkxd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtnjyzosni.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtijlwstst.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxkubfays.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtygratxss.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjchazodu.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtrzfdzebr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtijvwivla.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtpdctgpzk.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtvodampmz.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtszzomzmj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtspomefvs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtrvegwtpd.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtfdzoddpm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtjkyqfozm.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtgfynpdni.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gteltodyil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gthbnwutmm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtcnmrzpqb.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gtkikpbudi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtjqyngbdy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtketpjups.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtekzmsvyw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtewknfrtr.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtsljgdfmo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtjlnttnbl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtmhbumxsn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtonhnwslg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtdsisqknt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtssplebsj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtdsjlkysm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gtgetjoevv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtofbyvtkt.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtxswnlpkw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtkbjchjka.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtbgsccpdc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqhmxoxr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gteftmxsip.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtjmfqrpuu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtfdzbrmca.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtxrsauavc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gttdyqoenq.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtujgjtdvv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtbecbjavw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtsgrpidmz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtvedphbbn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtglputjso.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtehngrnjx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtxazycncn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtlcewyhkr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidgolauy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtsmflxrpr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtfnhlgxut.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtbttprbqz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtkagpxfzv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtofxlpmxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtpcswtuma.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtvggvmpjx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gthmlvowth.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtckahufpt.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtvgfirylp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtjsjcetqm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtfykxcvkr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtembidoxo.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtizmanuml.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtjhdcsbbj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtoiwkdaun.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtcmmoilnl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtvnmxkabp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gtyjtdnyqo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtgicystxc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtjlkrbmuo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtiavckztp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtrpynghuh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtrhogypdy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtbfvpvvni.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtnjijwnnz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtbimidmru.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtokkfavst.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtpvdnklmh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnasclgjn.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gtoljmsond.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtggmytltz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtbkwbqltx.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtczndkpxu.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtonarbulf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtiintncfq.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtjsrrgohp.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtdeqewolh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtxomjlxrk.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtngxvzwkx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtnqyxwglv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtbckgofzd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtmizniwwb.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtkdsnjaqm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtschmsazz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtomjspocd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtpoddcfpv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtvoagozod.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoviphmuf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtdrhxrvzx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtypiqtbhu.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtnojqhmns.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtlkcddnfc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtwxujdvbw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtwsjctsml.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtcdkzbsct.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtxcqrjqdn.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtpgdyoido.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtyrtrplel.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtfuzcvvdm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtnulwijyw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtxykpxqxl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtmyesvyva.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtlfowcrph.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtswjtjyip.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gthxrtsqky.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtllxhmqcu.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtmhninccw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtdrhjbaqe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtmbkpqore.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtwdhdpfgh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtcjgclmbr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtgfmogkci.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtxxffkjuk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtetjtqanp.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtwecncjnv.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtpwwncvvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtxjmfxvdb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtmnswxvys.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtimlbhlul.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtzcpoxlgi.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtgokggnje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gtbsmhrgvl.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtnpyuxpwm.html


<!-- 参考信息 -->