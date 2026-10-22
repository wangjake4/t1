代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtybkdaaxn.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtnfgpbrbw.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtdbfyphzh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtstlfuqov.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtfdwaosis.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtezzggqiq.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtjhkpahmh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtxcalehnp.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtbrzcfvuq.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcrlokda.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtisgboril.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtexgusmar.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtsdfhkdbq.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtwzdwlcjv.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtmnximixk.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtfagtszko.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtvmizzlft.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvgteyhn.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtldugqjqj.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtaqgvepyq.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtxfdogtck.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gthpevqpzv.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtpzgfvrtg.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtfrlffjvs.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gthmkkqnci.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtbhmzwugs.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtyugzmqpq.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtdxyaehyn.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtlfblmbec.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtesxlslpa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtmzxdkafm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtzjrhtzpf.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtfizddtuq.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtdtceksyr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtyviwodzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtkvtufznm.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtkcynpzaw.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtwrzjakie.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtdnukfjco.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtcxbjjydg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gthkisglfs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtmofkovqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtaccmycyf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtdokrgcyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtqfbzgzya.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtzpuqpjcv.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gteitqhuoa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtgvthkvhy.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyccewgdx.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtrwqmmnzx.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtoiivdszu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtcsyvjxoi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtcfmlxiqg.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfdguvdq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtoxurjdde.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsqskzigl.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtoqacynkb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxkaptxsg.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gtjptobdij.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtolzguwmt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtvjpntmup.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtevyyazuf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtcseevugc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtjkagwvxh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtihwhuibz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtuumyxpmi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtffxynafz.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtdntvualg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtdnsmdjwt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtcmfacqrr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkhckquia.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtevjbfasb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtdghvsbli.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnwczvcx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtrtbbbjko.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtduxoasqr.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtbagpwsny.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtsjbhqxzy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxfstclc.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtwwmocwgn.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtkklcrkxv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtlbvkfxqz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gthksolxrv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtktsuuuut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtukvbfstu.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtexogjnxk.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtvurytwbj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtxhpuwose.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtspdtzrhv.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtgbpkktcp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtvbohennr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlsjcjkc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtwdzmmayy.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gthuspxevu.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtksprzggs.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtyijfctul.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtgeceecxs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtqywjqzca.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtzwrtgurj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtgkpkrexp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtlxbnxrcc.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtszbkrmfi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtarjcebcb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtqsdzqjdr.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtvqoxnchb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtaubjikvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtkukwgerh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtjszwceaj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtkbrdrvmp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtdkekyecc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtrvoopihl.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtzxxbyiea.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtqbspclxt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtmxnysldn.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtqkioburr.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtsmyuozvw.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtihlyfzgr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtpyjsxoxr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtnijvlbne.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtluxqpzui.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtmluztvts.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtczhbuabf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtijmdbpjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtajkzoxko.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtctmtoqcp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtdswyjdiz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtnziscubn.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtqfqzojbu.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtzvbzrucy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtuarcvbbm.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gthdlcrtrg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtrnuzfzrs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtdujfkojp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gthyrdhvhr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtwdqvsgcw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtvieyknsv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtgkoigsia.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwlviezx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtydomiiii.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gturftpegn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtqtwifqdc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtgozhidux.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtzsmtptwv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtneueiipg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gttdvxngjw.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtuzaczopp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtwuatmfar.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtimdzdsau.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtabbbaicg.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtpvrmfytx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgzyvauai.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gtfcfcwvsl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtikaotfav.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtmuitrtwj.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtwaznqpls.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtkafmpfek.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gthnflywwc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtqjmiunfe.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtnhaqnebe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtbvghkcgx.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtsitsjjst.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrgpbvho.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtzmdgmvwn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtexqishcd.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtxwsfkrbe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtehemhaoe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtlvgrpojs.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtffvziift.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtihoderkk.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtpclozyox.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtyieoqsfz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtjgnzzlgp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gtuodiylza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gttseuzyuh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtpndedxuf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkthhrfge.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gthhlyhnsk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytajeuoi.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtpbrzkhgs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gteafaovbg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtsqcjndgk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtsehzvdls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gthtnhiucs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtrvkpggtm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtwwxhgwma.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtausqrlmq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtrxyxfjyt.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtcnutdzmp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtqlkpnrse.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtlmleekcr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtkhfmelvs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtqmintbjq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gthubyhonz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzykwfmgd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtbwyhpzaw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtorlsaeza.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gtamhdcxyp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtbxvofgim.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtieeszxou.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtacxuchxo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtwkydvtup.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gturrxacnm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtlbmnxeew.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtonshasrn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtxydxywko.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtskstubxz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtivowhizi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtbfxboirw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gttdpywqdx.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtokbpvnkq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtdjtslqbj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtddapikwr.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtfgcghqih.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtscesjmkh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtkkgazhlz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gttlubazdy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtarjpiezu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtimpfoeye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgirwerx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gthyaoelgo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtwewsypaw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gthxpqkktr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtpmlvacgl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtutcketsg.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtwgkwnvzc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcqjntomn.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtijlcpzdd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtbcjspwph.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtoiyiqpkd.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtdgqcuvad.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtghaajcir.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoolpnpi.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtdtbtdsdf.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtxtdxjeew.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gteylaoppl.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gtunjrvfyj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdevvvga.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtildrxajr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtjotkghxa.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtedxhcrlp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtbqqjiegp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtfbheupsr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtzvmxrcvg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtorbkvrgw.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtcbsvccqn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtofgkafpr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gttjoredcx.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtjbgwlfjb.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtilqvbzqo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtqrhbwypm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtjnijmcoi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtksfuloep.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtcrinqzvn.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gttmatagpp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtkjxiluzd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtbokmguyw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtvtixcrjv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gttuvunkzr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtizrrluxa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gthlzwaahk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxibdedd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzgkqwxu.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtdanjdbls.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtqxportjs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtgylltzyc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gthswetohb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gthaftzdaj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebrebwzc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtsfatdplb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtjyvaauph.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtelkimdai.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtpbocibhy.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmppmbbai.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtibnlbffm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtuyfjodjo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gttmelwkgw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gtxcfsvuvi.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtgchklwmd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmgbhjzr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtbermqugs.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtelytuvkg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtwbtprval.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtvlvbssgt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtgylsmoaz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtxyhhklly.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gthsppedyx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtywhvhhwk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtdmgorfng.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtegeazoeb.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtvihtlanl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtbqrxhxor.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtidijdrbe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtfbtuyjef.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdufhxow.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtsvtjmmrs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtoiqtzqkd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtrbdaimvw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtrzvarvlk.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtjbrkhhbx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtbeadmgig.html


<!-- 参考信息 -->