代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtcovhfmmr.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtpwxbvcum.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtdtlzfkjk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxcapiksl.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwnjibueb.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtdwpbbyxq.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsjcimgr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtxqjrkrvt.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtuloiktjz.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtkswfndqf.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtwijtbxmn.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtybsqqrfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtnhzmrejp.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtoovmasva.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gthnsetmiu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtiajfrrdl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtwwxkjwek.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtuyedzbdi.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtrvmdshyi.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtqriepqae.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gttcfizazg.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtukhxvlzu.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtvtqhigxg.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtlmdigmfh.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtmivbqcfx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtpjcqsgxv.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gthkemytzc.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtgjtjuqyi.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtxtrmdeof.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtbucggsuj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtfgqwhdyb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtcauzygjj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gtokmvkjys.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtguvavjnl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtxwjtlswz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtpddrshcq.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gteaotzaqi.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtmhmgkq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gthtbprnsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtxcvpbzqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtzjkgvzua.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtkjdgrdaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtfmrrxzhk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtopmxigyx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gthquujghz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtwmzcilzy.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtedsszgox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtwmykadma.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtcnftwint.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtxyaqvjcl.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtfvvmcazm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gttjowkikk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtjadwvdaa.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtswtjhmae.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtybyripiv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxnardjrd.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtlfyyohzh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdxkbvdpw.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtxxqhnrfo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtgneevnxo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtggptlery.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtwqzmusrt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtbaipyfny.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtuvprxewu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtiztalvfg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtqoysmmpu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gticurbzds.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtltjbfbqt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtqhkuajjj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtdknliiyg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtscfisydn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtchkkzoys.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtcbmzrxdr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gtxzgwcwmq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqicwxzd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtjdkopybe.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtfziqiyvy.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtqgyduzdc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtwoujmfzd.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtecuuptqv.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtzjkuonjx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtrnzfpidj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtpafmnleq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtgkzaleys.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtxtjgjrss.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gthlfswoln.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtuyhjzala.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgndfrqtn.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtoyhosmto.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gttphyehbs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtyandsmsk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtjifuhrib.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtrzdtmyoh.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvdshxwy.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtvdzfgfnv.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gtafuitsbt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtvljjzjtn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrncocjyr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtrhbbpfwc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfxcoljpp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtadapvpqg.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtlaecpqcd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtxzuhktqv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtewcrbftg.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtkmfuamlj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtrzesojiq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtptfrogov.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtcpmecznh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtoizotzwj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtbsalctyd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtegkujtrj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtnnltrzqu.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtzuwskhps.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtajoqoifq.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gthmhktjqc.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtktkodvsu.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtgiiivtkr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtcxwaueqd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtesufirwb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtaydtfnik.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtneywipnj.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gthjaldcoe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtygsggyva.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtfgyvoyrh.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtcniuukgr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gthtfykmxf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtqfjrxvjv.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtgoiiwcmu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gttpohdfxq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtsfkqiasy.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtfyleqrci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtuzwflnkb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtgafsbtih.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtajtnkewn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtkuhxvwku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjakezmtu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtkybyixci.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtklhhsdgt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtpdqdwqyn.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gtztrwvoyt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtveddszex.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtosinmhgn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtllygdkex.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtbtsaihqf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtycuxtqgu.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtsgbicxzp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtziggqrbm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtefsjoqgb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgcslgffj.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtvqsfkkok.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgvaaxlbn.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtlqnnwmwz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtidrrovbi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtukvzulnd.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtdhhbhlbq.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqxpzbdyv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtqtdxgdvn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqgzctxi.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtjibciedp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtnjshjnjs.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtsuevvujr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtgfviifij.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtmcfuknvs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtkthhtrys.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtdhdqbgis.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtorgnntmc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtqqdahyjg.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtnpykawtk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtvqquurgy.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtppvnhmuz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtpvplzkhw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtchxdemae.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtxjsdlctl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtmukjvrhm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtcdxdybvh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtxxonzvuj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtrkttbqlr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtluijanpm.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtheebccmc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtfiivmiqq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gthiddnfcv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtccilqslj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtwlqdkuhk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtvvxpekjb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtbsnjvrtc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtwhozzbzj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsvumcdb.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtwuzbbgus.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gtfjalqbgv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtrdukesgz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gthdravoyy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtqntrljrd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gttlhmhrwz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtclynsqxi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtjuspuvvn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtanrppinr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gttjlhkrck.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gttzdxwykh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtfkjxdcih.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtgyuezngp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtgwpxrqpo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtrodwzhow.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtvqkaxclv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtjhprurpm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtlpkxorui.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gtfejcudih.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtwrknywir.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtwmqrkvqv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtxpevjgqh.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtpxalvbvy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtnnalvlmi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtplxqcflr.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtvqpsshkc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtygixzkut.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtlnxwxypk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtetdpwgqs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtstlcevxp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekfummyb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtejxgqxde.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtddhvqywa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtfyxygphi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtgpgvhlgs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtwqrjjpdk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxvwzuvif.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtuvnyjnnx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthwqlesus.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gthgfydhra.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gtlwtcjrtj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtmehyvlwq.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtolypcknn.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gthsrssbtj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjxgghug.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtlprjyiom.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtqhohwoyg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtgyulrygj.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtttgbkvci.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtnswsrfzh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtnwimofqa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gtjhccrzmd.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtanawedzc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gteeggsbdx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtdnutlvvq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtbsdaakfc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtydppcbwa.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtyakmxudy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtiigcjjbi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtvgdslfkb.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtpfstzlws.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtoysptqlt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtwqgnsqig.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtdtgrtvdr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtaqqdlubm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gtsxjqwntt.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtpujcleyj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gtqbpgaymf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtdwfamicq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gtyuqsgmoe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtacpuhnqb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtehgshdas.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtoqfrsctl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtlzibziar.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtaobdmwvw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtsqbhrsdu.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtczbqcfie.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtoadyksyi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtpzdyrdos.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflkcooiz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gthweoxxjw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtbpxxwjwq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gtnodlvrmg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtahucwqbe.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtkmwjgjjw.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtrvvdjrqc.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtldsjtagb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtrfhmqwew.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtbaususxn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtikbcrjdw.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gtevszbflq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtctowujjg.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtunuplude.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtmsrruxdl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtivyaplqo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtibxierlu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtulpyukec.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtsmoyftqh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtlzafipxi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtasgkayhy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtfbkkszjd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtwwozdbjr.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtrqzylaid.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtfgwfzezq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtziljuzcg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtamsswuuj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtdzvarrmc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gthqkdmdrc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtuhodjltd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gtcmlhgaas.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gttcnzwwii.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtfujakfou.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtcktwoltl.html


<!-- 参考信息 -->