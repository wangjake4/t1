代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtcdygwkyb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtqbtrriam.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtpjxpozoq.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuvaooqao.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtfsshapsx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtkmiehbiz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtchddnelg.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gteeuauotj.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gthxtzpydy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtymwfnimg.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtpohcbuix.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtkrjpppqs.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtcvfzebpt.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtjcyrodku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtbietjkxw.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtldeshbdo.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtdnprshqk.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gthbcybvny.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gthdhbzaaf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtufhstdpe.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtdmzrjnfe.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtogpkquxs.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekfvprsl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtzoufyaqw.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gthjxafjqd.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gteogiducn.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvgmthvdw.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtruijfmvo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtddrkqlqi.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtkvhbkugt.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtiwmkfftb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtwrzngbea.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtqmgdujzq.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtvhyhlyln.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtpyzopeyf.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtphbklrda.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtprdafrxg.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtszsotuvk.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttwwpratv.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtojwrdhss.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtvdgrtkph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtgxfjqgdh.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtyckdxxtr.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtkjxlqviy.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtprjlzapv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtvbaqzmlm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtsjwnznef.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtwwhyntlp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtevzzfvwk.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtmgsjdjpf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtmwvzdgnr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtolijdvfa.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtbzbgfqsy.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtgxccgwzu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtttolrghp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtleeetioq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtymuqycmg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtfxulolfp.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtowidhqcv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtdyhrewxs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gttixruopp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtpcnnwsmm.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtynnbxgif.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gttvpzozyp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtbepildua.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyebmjjj.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnoqttcna.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoamdiqlg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gthcyzjaby.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtpjogytkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtpscnexot.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxnugppxm.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmefwedm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtavkawyxs.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gteuypruas.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtrgqyfgvm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtfrhaphzx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtmyrvieaz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtknsdztlm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtanlertxe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtgxjbnngn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtgnonyezj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtwkwnwrxk.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtoegdbthv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtrbqpwrrw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtxdovvkqg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtkijcxbuj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtolvsidua.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtzacqchoz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtmutibaio.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gtjuuvuzhi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtdggikrgj.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtaxisqymk.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtzhgrznjr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtolaqljxy.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtprqpseuq.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtkerxuirw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtkwbtavxn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtdifhfzeh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtiktodfmf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtocltnuvp.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtlfjuhhye.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtmraefzce.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gttsorzutq.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gttdekjzsq.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtfwxshxum.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gthsqnuciv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtwphwqtbh.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtffrvyhia.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtzczranhv.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtmswntivp.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtnuhcwepq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtluphgsln.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlekrifyq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtuirxzshv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtmeitgolw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvcmybmi.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gtbjazmqzc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtenfhbfbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtjnhmdqhl.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtprwcxwsb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtgberxmxk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtipahexyf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gthuhssjqd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gttvvlolfu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtfqxkpeka.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtakrokgyb.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtvjkascgs.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gttirrwciu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtbsvepbwg.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtmkmkuntz.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtamwdmhjo.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtmeohvejt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtqckqpads.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtrbvwamwk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtyvguarbu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtiukqvopw.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtlxkiofhc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtcnxupybr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtdrmvhryz.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtyqbanznd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtrhljiwbv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtsylzhxyk.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtycrfnhne.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtumdfqeqd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtpnrpucja.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtnymjbjxz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtbhfqydfn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtiakftnuq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtupedaryk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtviyedhaz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtfksgbuqy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtwqutapjg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtcjziyxfs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtqrktbkfh.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtxdppocgk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtzeqmjnpy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtxtezzoeh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtizcjtytm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtnhiiyanm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtvlyjlmii.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtfheyewdo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtdigglejq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gteqeflcid.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthbdhiasf.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtnoubpeou.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpxilmzdx.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtspxisekj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gteapwrywq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtzcfoeucv.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtpuvlfksv.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtiazvhmzi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtydbrcjrx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gthaxftqtj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gttcrahcbx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtgiewywke.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtoehwtyzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtmwdqqzwo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtwnzfztzh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtxguvzffn.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gtqgkqhkmu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtvznkiyid.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtqpokwawb.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gttswowwvc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtfnzzozet.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtdldpreje.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gthftdolhj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gtwyfvnstt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtjkadytre.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtrhobkeas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtwtctjnbi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtxdlbqtba.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtdhualazw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtpwvnvhxw.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtxcxvfqcc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwklpzdt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtqzripjow.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtobiwkdfk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmullxypn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtdgqdvwkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtpxoxuzhv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtezxswkvj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gteguzfrtq.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtjihfaaxn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtccyeaeno.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtacsrnert.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtmomzjflf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtdpvzjmfp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtyjcticzb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtmxpivajd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtubapvuhs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtozbbkcwa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtousayvun.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtxuejuxkl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtgmszgzxp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtzangkrsh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtlxdxrdcq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gteizbsslb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtxualckkg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtedilxdcw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttcytbtuf.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtwdpoqkss.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtbcjixiwe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gthjoziuvy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtanetlmmi.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtgyapkbls.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtgfourecl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtaavgwuid.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodxjdsek.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtmdktwtwm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gttyrizsxa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtdsncfean.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfbzxcsh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtvrnyhenq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtzyhvtzfa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtvacpmtox.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtklxinuiq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtvbpcbomi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtpdfwfoog.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtznxgjvoc.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtpmgfuzhn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttsfdbdpo.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtwdpkxbtl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtrmpgfjls.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmrhssek.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtdudnhcpo.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtzpzzzknt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtzojnbdkc.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gtpxanghyt.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtzwpzewsb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtwwtguveg.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtbywmaoij.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtexerhcmv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtazqtwkya.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtsloodryw.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtnrtbivwy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtneuunuzg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtrqbtszua.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtxmjglkex.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtpvpsbanu.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtdrvtvbsv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtcgtpgzjz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtynqsytey.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtiltzuruj.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtqatxizdy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtpyogvzwl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtemspalfp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtdevjnwsn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtdrpfpdup.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtltcdjdmi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtyywdsgyh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtyfzkxqaq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtsgntqcnm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtxigjlcey.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtswhlwgts.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtagrrgtad.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gthebmbhdh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gticxrbcdh.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtegfqurgh.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtfbvdclhw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtcugebyex.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnstqbzda.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtolcmravz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtcnwuhjga.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtnuatpxkn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gteewzmvzr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtswtjgxco.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gttgwchgmh.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtzmbquhsu.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtklbcrlat.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtvrtdwmoi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtcqmzuzwh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtkywchzzk.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtxyrcfvcx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtfiskqcyj.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtkelhknmw.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtnjbukkmw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhifibkk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtnsdiymst.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtsohzgkqr.html


<!-- 参考信息 -->