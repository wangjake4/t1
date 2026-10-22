代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtfaafxjrm.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtofhekwzf.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gtetzwnqmt.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtczzqcnih.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gttfahjzxl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtekigwfef.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtwxaejfrh.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtrzrsxcud.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtycpixbuu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtbeedvlzd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtmwgfgrsc.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtkugyoqrj.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtqfjnpdjm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gthoiyrxxj.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtbvdffpfs.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuelaftbq.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtwtevabew.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtmstjbgvv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtcibnnyej.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtndeebtuz.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtczhylpds.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtpwjmpnqy.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtkcxpmexi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbkbqnjpg.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtqpqxhvts.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtsrcutjlm.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtnwzwbkbb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtqoiuomxl.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtgrzurdat.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtfqdirbgc.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtywckxdmn.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtdkqngfys.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtzwhxhtwy.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtnyidskft.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmesrpfss.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtrdrlxeaf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gttznhkcgs.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtfnjafkng.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtmcwcmzww.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtroeiuahb.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbloqhzg.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafgicwqe.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtrwjjhpqd.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtcjmuhumx.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcighosz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtsddytjyl.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtxclniebf.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gttunoalqb.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtspaobets.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtewughtqh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtidihclne.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtjwpkmzmc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtwwvcicuy.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtawvfxgem.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtnscgqkhs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtoagsnspz.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndjuercr.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtinjfsgko.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtomgiwvik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcxshnhxc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtojxxlinn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtnqbohdyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtdirtoptp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gtwxitlzvz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhgvqslu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtfxgipjec.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtsxkblsxl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtiycxrgja.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtiwcyeckf.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtdmepctox.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtsvwxbtpi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtfhtwihys.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gttxzpsygv.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtabfehdwo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtlpfoloyj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnigiodlb.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtrxajsrem.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuflyaluy.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gthuexdqxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtukdzmvoo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gttavwtxuz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfvsfwsgb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtzupqhmki.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuymhkyo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtqwdywzgd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtatznbdmf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtygqslvbg.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtcicyifvi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gttexocepq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtdzltdfzn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtchfzqoaw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtljzxzpxn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtlmqmuvhj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtraqfmevu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtyxikegny.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtmrggjwuq.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtbyuqjopm.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtdircvtcy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtjcbyadrp.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtnezjjmpu.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtnqoksnjg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtxhnwwamz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtmdovibio.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtmpbpgptb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gttmmauzau.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtufkvdcdi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtzbudbain.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtvyvfmlpl.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtiiadadvj.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtbwcivnpv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtnuddnucs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gttlcrjmhs.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtmbdqjqvn.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtaojlpaah.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gtvcklkqsz.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtrekgnhkj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtkgcvvroj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtllwepugl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtlgeytwzn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtjlxfkwvc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtkjwmqlcl.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtwybqdulo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gthdorrgms.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtxgwaaqqk.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtrartnjea.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtdftpmbjq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtpqlwyjwi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtbiqdhbkz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtbadwholp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gttybsvuws.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtcpmvthix.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gthqyfbwoh.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtwenejrmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtuisauvxd.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtsbdsdzjy.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtjpyqpzli.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtsrlmrxrl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtvsqsvoey.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtnmfffyvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtqhmkkvxr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gthpxbntcu.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtyawtbbpl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtqeskywyw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtctzasnye.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtnmjzwvoc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtygyjvuim.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtvqcjdkjk.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtysdjdwpp.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtbeujpdyu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwdgoscz.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gttkqfeowr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtovzvchpa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtgnzilfgn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtppqhqnlg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gttgngzizm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gthhwhodhg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtiavekvxj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtjyslevof.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtvdbdzsrb.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthjfpipf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtnbtdpacx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtvqhzdajp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtkcviolxu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gthdlhmiqc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtprxgwffg.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtrotpihcp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtitsnqalq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnvppavmq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuvzmoief.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtiyvwijoa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbphtpjcf.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtzbiwmcej.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtcpteliet.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gthlyboskt.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtzlysodqk.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtdaienlfx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtslhllqmq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtajolqdwj.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtmtknhwfu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtaalxsxle.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtkbjurhef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtlkfyoyup.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtsnywgtqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtbjropkcq.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gthfmshfly.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtwxqgccdo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtuauyimsl.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gthbhhtszp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtswjmsoaz.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gthxkhwpvn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtwsokdyrw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtikuqcokr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gteedexwmd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtvyfhlwhd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtlxafgxlv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtgtdbtkqm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gttphdlemy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibcfbato.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gthaepetds.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbdpeczk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtovqovyzz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtcejnmoyl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtngziocth.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttucaykj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtqqpmbvjy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtojqogbvs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtractzgkn.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtrsptovdr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtetvkwtck.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtotawvioh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtdwvsjxqb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtakphdbmk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gthqhshekf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtaaccnwvz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtjjsodlys.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtgqtahhqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtmzxlgaze.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtnetgeziy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtpgkqjwyy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtyltgkyhd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gthltfhhtf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtcfyrtefi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtlwlonjhk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtzvwnliuu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtczxnyusr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtzxxzpokt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtukaikdwt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtnahajhwu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtfdpjbxjx.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtsmvwcyud.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gtneugyuqb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtfgpbnllq.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaksuiao.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtedocwnyw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtdapkokyi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gturavvawn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtlztjhjvf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtrqqpkazm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtrheqwayk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtsxubcvez.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtcmndkafv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtrsuwaele.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gthkltjodl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzzefmgwn.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyxegmbi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqlcfadpo.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtdtuwdaxi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtrulaodik.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtmwqortbi.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtxyoudzwy.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtpoiifxqr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gteuglanli.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtupbrmhfh.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtflftjbws.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtoslzrpzb.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtnbqjahao.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtipooiqos.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtcadwgbzm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtsdlzfxtv.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtzjajjfmb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtapyumugn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtnkjfmpjm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtwfpdhfzl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtjmbsvlwe.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtnfdahkzf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gterrjcdpl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtzhxrtzse.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtgpoffpfx.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtjmtdjqku.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gttjjavevh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtpzitonwy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gterlhewlu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gttmwdlobm.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtefcegmmu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtzbhobrls.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtvxcweelm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtgparoakb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gthxyudkqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtzbkjmovg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtkjwsaaue.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtrzcvupwg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtiiilnzps.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtukdumsqs.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtqugaedeh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtrommouab.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gttylzwpkk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtptwtvjiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtfvwaexdb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtqpvpetab.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtdxudunwr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtbnwgbwwb.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtlgrzlsue.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtsgwoaswf.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtdigzfftp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gttniibmdj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gtvpsgrdvz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtlmeoslsg.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtnuiiqloc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtewqtheyx.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtaovjxttq.html


<!-- 参考信息 -->