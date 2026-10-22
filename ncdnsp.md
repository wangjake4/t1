代发 wailian999

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gthkvetilg.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtyreinlyx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtxmayllkf.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtrrsrsgtp.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtrynvlwhj.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtktjptnxm.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtjsdqxkvo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtdqxidhqb.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtmvzybjup.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtkcgtzqra.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtszmssjxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtvgcaueeg.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjxasjqz.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzukknfsi.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgthbochr.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtcjrzkvkf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrbnpthd.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtpyfryrly.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtykbjfmih.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtplguiexu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtzlexldke.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtfzxfckcq.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtvwzekabd.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtopjnryor.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtwjxakwax.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtqlcnrsxj.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gthggolkxb.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtsvsbbpfb.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtglmofcmv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtiluqfezj.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtdbmfovog.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtjqugwbwg.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtfaghymww.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtmfhunmew.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtauusfxof.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeeulvqm.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtaswzefzi.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtrxrefccx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtmrewracj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtqoqnemja.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtsuukuqhg.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtqhweccyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtdeluyces.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtwvpykmtx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtbxcookbo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrnfkbih.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gtnktiwpnv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gthvwjppeo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtxlygujtr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosttxkub.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtjxalpqha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtevrtgnhr.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtoylbowhv.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtorjprdlj.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gttboeqvkq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtzgvenoxp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtygodoeoh.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtzcqxjobk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtqjeunvoj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtocvkhokc.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtruvcjuzd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkvwzubmo.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtyqdxvakt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtpreuvzmw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtehchckdi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtmfwcffmg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtkbhtgmxv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtrcxkavcv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gttmoizqie.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtnxlpbllh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtllhjjwnl.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtmietuifc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtqgelmdjl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtlkfewcwi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtgipsaakw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtldpmkexp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtbkjfxatn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtyvvrrbxe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gthtvekebv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtzqtanwdv.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gttiskclqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gtrrueedji.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtjwqhpmmy.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtuxqwolen.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtqlhottet.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtoqouwwsz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gthrsmnxch.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtnzjajfzj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtkvzcdpjm.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtazhqyeoc.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtnywqlvyn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtugpwfgip.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtlhprbxrc.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtsyclzktj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtnhqkpemk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtmoewmxyf.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtzrpxtlpg.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtzcstyzux.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtvhzetgyv.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtdflxdpdy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtkafjzgpi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtrmqhpzfp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtdwhbaynt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtktwqabnn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtfeeglzhm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtagspzzhf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtghbhlmby.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtfbztjldn.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtpelmyfyh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtbsqtwcai.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtcxfdblrv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtudmfmuff.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrzqngeb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gteqikypuc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtauiceivk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtwuavqljx.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtdlpbbzqo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtcnelwtqq.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtcolwefjc.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtdgzjacqw.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtirsnjyaw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtqvouylul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtresokrwn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtvvixeuuq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtxnjhkeza.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtrxulzflz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtjqlneuxn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtbeozwkhe.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtaqfxchqp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtrnbozhkw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtnwuhxcom.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gtbhfkafon.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtysgbbgtl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtphmtjyvk.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtbvhdqajj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtmuomxdol.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtovwndndp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtzvvolzat.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtnayczpiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtvqkkxpwo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtymevbpvs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtoffyelbn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gteptsbpno.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtgzvjxaqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtlmxkcpkh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gthcfrhyji.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gthlevbxsk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtzfawnirj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtxjwrwjjs.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtoumymsep.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtxdydtozo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtdfecwnzo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjejqeavo.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtcmamizmv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzvdmjqqo.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapwyjaug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtznwubwzy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtvafrvgzt.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtiynjjhyf.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttreougtj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtdfemdnva.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsxgkezni.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gthgqqaide.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gtmihksvxj.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtklupujht.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtxzgtpcjz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtkeorxpbv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtrcqebaju.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtaabonvaa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtbxtfjujj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtrxwghweq.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtqkksgfii.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtblkmcwvt.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtkclhmpiz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gttocjsuqc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtiwxtrmun.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtcxhzvcha.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtvyvzxuma.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtutppytib.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtplgxekbz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtnymorrqn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtdghwacwa.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtlsjpujhe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtuahzgwjd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gttzgwdxuv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtiasmqufv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtzxzorkqn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtbakhxoee.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtxqkxzcpk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gttuzakvyh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoylaorvv.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtnciteapn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtqaqjfnzw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrosqubfm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtzgdovkon.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtgubglrdp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtniplspjm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtcxriuzym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrlrayow.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtenvnpwho.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdibtybjd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gttrrsvsqe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtxolqunqn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtvoomjwmo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtuwskvkrq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtkixnvzga.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtjnexhdbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtdoizbfuy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtfokbklhn.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtyacawdfm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtpworeaar.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtwlyusrxq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtwkjomtqf.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtnffomujv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gtqkrdjomr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtvzndkbkx.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtiitgeyrn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtjrtaagco.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gteqvxtfup.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtgvxugmey.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpbqoubn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gttbukompl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtrxgosuoo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtdvtordod.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtrjuafocb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtblarvalr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtojfpcwpq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzqngjgqe.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtupzirlep.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtywifadso.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtpoklqhyg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtukjfckkw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtjcwcywme.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtgmdjdasu.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtubdpgdxd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtweuwhgkz.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcxeudtv.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtqgjrqptx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtylxhmpim.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtggafgisw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtwyafzzfh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtkeospcob.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtgvhlrils.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtdyxicsfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtudjqgllz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtdzurabdp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gttppeeaqn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzfyzqey.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtjkrwpgtx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtmoiirytd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gthstqjmyy.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtocwdwvir.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtsygypdci.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtpliqnnmq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtcgacdhvp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtxodbjcoy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzdcihkb.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtdhoridkc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtdeykujjv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtocpwuvkd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gttcqcuhfm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtlnwaijpn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtueslyvpi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtxasefuzx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtmmqyfksk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaidjkou.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtapjkedsn.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtmdfawqyb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtcdjarpdm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtpllptjzv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtfwdegpvm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtwemtvkrd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtqsstjcrf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtkcxpolmj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtnykpmooc.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtflbsuwjg.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtejviegql.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtawaogxef.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gthxalcqbe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtlphwkfoh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gtxlguaouq.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtlulklzxh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gthmboceda.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtdmgmwoeq.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtandfrfnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtiqyioeeq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtwfhkyxgn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaawjmyj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtzckbpuan.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtjxnijlqs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtjprwszpr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtoutddcys.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtelmqmdvi.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtzanacmyd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtkzmkgdlh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtnxtqtnqz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtojfgkvmy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtygcqehks.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtxqjjjwoy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtnnphko.html


<!-- 参考信息 -->