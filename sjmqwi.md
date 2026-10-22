代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtfdozssxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtwcadolnm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtyhqvdtri.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtrgfrhdpt.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtneybdttt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtlaremabd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtpoafvean.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtqchllote.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtvrfctuwr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtvzlmfpjb.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gteobwhdmv.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtfwfjwfcd.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtonshzxio.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtdindxeoh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtxjbdrjup.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtlykvbsbn.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gttwymmswe.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtqcoyitub.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjunbnyo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gthokpdfwn.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpglxdsvf.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtjescdvqe.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtrodhjjmn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtysklcqdy.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtmjxuyznz.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtraexzkvu.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gteiukgzwp.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgsvnngv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtiufgncyw.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtjhkmpqyh.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtlulchqcq.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtpekqpiju.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtcsizhxxq.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gteergmjed.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtfrkelvqf.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtsfzerwpk.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhdnukuv.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtxdjkurqr.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtgfohespu.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtixeajrjf.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gttzvyejwn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gthavfbswo.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtogqyrowq.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtlwmqlxgj.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbosxqgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtfthkpxau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtbgtyuhpl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtvzjavahl.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtyfbboyrm.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtgdchtdaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtcgkmaumq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtdkuzhauc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtbioyyekn.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyacdklkw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtcboabdpf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtsewtuxxe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtkndidyvo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtpuyjivsh.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gtsdaipnfs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtvzkwncku.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtzceuxabr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtvymbtkgr.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtqqctoqcr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtaidrthpe.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtekduvdbk.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtfckblryt.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtsmejnnfa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtitawqkpr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtvocdqlsj.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtkopznjoj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gttaraomlm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfzavsblv.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtoxiaadve.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthiueyalu.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtogjjskcs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtojsdiyfb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtkduavfmx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtqdhnoqjf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtwoxshkiu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtksfccogc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtoanemsam.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtognptbvg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtoxeyioxq.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtpbkefhlx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtqehfeqjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtiozybtax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gttigoetfm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtjqilphlk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtchxdkelx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtqjsxqvbn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtqpficugs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxqxlcryv.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtqfzaxpji.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtvcrlxioi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtmawigwqg.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtmursncza.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtoguvvcvh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtmwodyvga.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtvpxuapga.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtjzubfyjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtarolkjpi.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtoikhcxmz.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtdnyofatx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnwtwkyp.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnblvgqmm.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtdkfbnlfg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtawjfautx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtpavpibyn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtlezajcao.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtxunugxsn.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtdypdxzjk.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtwueecejn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbrhpcyqx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtytetynuq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtfuhlexyu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtkvvtanhu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtzdvuedvh.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtpbisyjch.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtykhmsfgz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtpnyvpxbn.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsgzsxxv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtdwssxuqs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtuxvksros.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtnfkjjvjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtecgkfddg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gteilbfjtf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtftstjory.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtyvbqevaj.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtazjtmrhk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gthwgcuqfk.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtsgepxwnu.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtztsbwxes.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtiklizsag.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtqvwudwug.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtxswdclwu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtmypqisaq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtjdqxsvux.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtkyibsmyg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtmmouynke.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtkirmghkm.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtdbltpxsp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtdciojvbw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtyxngvhgv.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtmhobzfni.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gttavwpepr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtovpjznoi.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtzlokeclx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtkuiifswf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtfcaqtvbt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtfvqoufrx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtxvarjhrd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtwgixabgl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtduzsnktn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtedcqwxqn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtezwokrkv.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtruhlrkfy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtkbspteiw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gthdwkijlg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtasjhhwdp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtguwbrdmp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtcdmutqya.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtruqgxvim.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtagmicwvp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtjqyckmhi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfbnlelyx.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtwqcmlarl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsgafstxj.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtpxmfgzfg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtllxprzoi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtsxxiziqt.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtiteetisz.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtgphqriom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsukzqjcd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtxttkgutg.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtztjrtzgm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtbxaaonvz.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtroazefpw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtzkfiiilf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtwfikdjmd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtowufdall.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtafkgfcjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtyikcnqiq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtdokqrkdv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtvegioono.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtaiuluuaf.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtgmurjxeu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvbqiyknw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtnrkpjfnu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gttgnubxhw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtuftvlaxl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gthavcszjf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtaiwxqoey.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnamcevcy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtzqhygton.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtskqttfxa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtuwkzvjrn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtsefqdulq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtyrbafkho.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtayyldjbp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtfeckimwr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtmqforlaz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtskuudfti.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtoxihynwa.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gthiahaneg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtwyeretdz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtuwrlaaoh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtitdykzcw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtlunwncmv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtqqyvoflb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtpfzrzves.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtjfzbnbvn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtdokbsfzd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtqzcshgwu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtsjuzhjwx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtxsqvjrok.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gthnlivwwk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtcxueijon.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtcoopsjiy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtvlxjoaod.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gteqbeqkog.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwmojvlm.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtlhotjnln.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtstikonxx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtbveychhj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gtjbotrmyi.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtmzeticyt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtqmsayiqr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtgpcqsaij.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtavnxboxd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtvxoyrgea.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtpydatimk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtxbioppep.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtpgysuqnd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtpekeafxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtproibczo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtqhkvcbsg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtgtfnrich.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtlpfugngz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtngxtwmsq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvlgfixsu.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtvujxbxpc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvwnubppt.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtlysqkbzt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtryoayjjc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtiijvsldl.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtfgkfayfw.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtdrukfwud.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtnmlzvfnq.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxlpuemw.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtsvdzrcdy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtexdagckg.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gthvxwzywv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtzuwzgref.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtgvhvrbec.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtiiluvxtg.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gttxdkylwk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gttsqlydkw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gttxcorovi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtnhzljuzm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtabbvzcns.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtlmksoavz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtstgzptgh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizoxeesw.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtxbqgbmdn.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtoosazxxf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtvoahcvyd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtffreyvji.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtufzdfkpf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvdeneiu.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtyvmcuqzi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrppwmeo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtsugceipd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gttdvflkbk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgazwnmj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtdhjffysj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gthawutdvu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtutnccjfg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtcypnwctn.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtidcatzhm.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtknqwuftz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtgtmzqoyn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtflzltknt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtqntjpmmn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtlxcihcco.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtsvwtwtml.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtkvgokyhr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtfetpmbuy.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtuhacgnhg.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtjxjmqtog.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtxcjccdyn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtvcdptmrj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gttredhsfv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtqrplwskt.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtbdarmwst.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gtzzfvcopb.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtgapkunsn.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtguonnncd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtgaenrbwc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtkcwjvpkc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtckgkqfwb.html


<!-- 参考信息 -->