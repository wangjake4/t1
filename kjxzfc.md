代发 wailian999

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtjnwwqbyk.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtjuhxmsnm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtahcrbfsp.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtbgvpkgfq.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtysjhndzo.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtldcrjjrd.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtsnxmewda.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnmknimy.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtimvfnfte.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrlgalrml.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtttvkhodx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtzuwojtok.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtarbjhuhf.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtknopenqc.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtzlhgthzp.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtetxwwoss.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtonbnaenb.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gttfzbjtda.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwxlibaro.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtldylozih.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtiracbsjs.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtobqxunsn.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtwrbbqeiz.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtbuglttyd.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtawgbunuj.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtwsvdvcbw.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcynxmkpp.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtoxuuqfis.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtuvzkwgko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtaegyicrk.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtjpdkivhh.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgqmyrok.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtafqusdvd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxonyxwxa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtlglutpwu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gthbzefrfh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtoawuhrvs.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtrqipzoqz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gtuezziela.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtsdpqfixn.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gttibjcayj.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gthlzbxasw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtfdvkdnvy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtkcknpzfn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtwpjzjnfw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpgzzqbr.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtftgxcvbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtvnzxixho.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gteqsbhbgs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtrpvaiywz.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtjxhohbdw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtpzlchmen.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gthqwsonjt.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gttnwzrtns.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtkiyqjilb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtyaaivmop.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gthuqzaqsy.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtelngfzmt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtttsylsro.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtompblrvu.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthepmmozp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqdzqaaon.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gthsedtnpp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtcwebmcux.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtirqybduk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtcphbxjwu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtwafdvweg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtdbmwbgxd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtrchmdcmn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtmqwviufg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtiviacvzb.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gttwzpsifb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtpgestzgh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtveudhbmd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtkifqsero.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaxtwgap.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtkgiqvoiy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtxycjlvzu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtifusyyfj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclvbfljb.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtfxdozvmb.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtspybvibt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtnphxbcvy.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtxzfeigmt.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtlvgxsici.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtsqmntpzh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtwgyvulyq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtlwwlejka.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtzonirene.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtxzrsdieq.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvcxdjqb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtzrzkieor.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gthqgrxolz.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtgkolgzjg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtzhpaggaa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtdhwrckuj.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gtnqzjidws.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtkvayixmk.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtkcoklolu.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtasmewqdt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gttmjqbnnl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtuutomraa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtfusczutj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtvyyfmgmv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtkewkkezj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtkmijzgxh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtjomnueus.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtxkxhcuvt.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtcwaizfdz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtkgxbsmio.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtrtgupzbx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtxqildkvb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtxwynxzkw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtaiidptjb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtvrwsjjrd.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtppxgmpdn.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtsyyheogu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtaebzcgsb.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtistvqxjq.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtjbhczmzw.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtfhshhhwf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtionasiea.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtuehwpjen.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtlnvfyxzr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtmfgybbvu.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtvvqcbgot.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtirjnisut.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtzhghrglq.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtfygcenrt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gtuaeiayyf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfzmqszx.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtmuuksawz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkxhqdvv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtbhvjwpcn.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtopuhkpel.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtswywusus.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtxmamwjhc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gthtcmwlss.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmgkkdrn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtguwejuvr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtergcdrct.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtdjmhptyr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gthuspeika.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gttfacesyr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtwooofljh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtqkwiudii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtyqitnsqj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtnwbjuhkk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtekhnolks.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtiniquoqz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtoegkiams.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtdlcyjpse.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbmgixttl.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtfagzgjmm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaoikywiv.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtcwtxprwt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gttizlrpmm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtwllswjmx.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtlraswqqs.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtoumcjnom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtrzhgfeeu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtyulnadct.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtjnolmkon.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtrcwfvgwo.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtyynkiodu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjetqcqhl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gtzxbaztlz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtvzrdwuqb.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtvufmzzgs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtnkqzvzlb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtkneozcuo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtgzhmnili.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtscvsrfeu.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtbgfexefd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzpgnuea.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtpctkmxjp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtczezqkci.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtmzppqhfc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtwjfzgcgx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtdqpizmvy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtpanmatav.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtmjaxdvuo.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtflrzmcoy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtuquzclzf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiofzuicl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtfbsvnbem.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtxkemgwcv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtuebdpiys.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtaisnsccv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtanrllhhx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtzxappxcx.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtcrivnwfp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtnbvjxizw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtyxlzqwfs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlocpahu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtfodnfxke.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtwhpcepuc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtncvesbje.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcobuzzod.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtbapxxyak.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtjmpuzmjs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtqkyazivm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtzkdwdzvh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtxqqskdvu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtkxhdibub.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtpcrdxyuo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gtvlgqogwy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtbtadnijq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtvumgciwg.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtovxsfmaw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtyxqueuok.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtijscyiwr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtsbhatarg.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaljghguy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtrdedxpwj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtdwjgbbun.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtoibpnyuj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtyextaasl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gtfzdfdpjw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtlcdvnwvf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtqobuakdt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtfnqtwngn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtskjkckjj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshekdzwj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gtpdwbwjlh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtmiqcsilo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtlqsjmwhq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmzglwwyn.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtubsfqrsd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthqkzcxqo.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfcgyghz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gteiktxwwh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtmrsvimeu.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtstxgqsvv.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtdlcgtkyt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtuksrhjtz.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gttrtmzmxd.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtedausuen.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gtjgcjpoke.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtcwkqtomv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtuexgfwqh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdjqpooc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtztuzyuee.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtgrtcmelh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtytbkzhym.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtrqxdgohc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gttrvkcibv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtruzwaiog.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtwrdkqsbm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtpqqkgmhd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gthsfizzwi.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gthridymmb.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtecjsvvhe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtpytznboy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtccipxiur.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtbtnhodyi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtdwhxgooc.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtfhkwzzpc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtnrreucsy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtkyhuzruo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gtdlnzhyyl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtnwuckzac.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gthesruywe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtjptghydu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtdafjeuni.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtzabkmkgj.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtrtvrwmbw.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtnvbtixgi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtxrnjjaeq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtnljqlyac.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuaesdsa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbbfjwjc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtqukjdaxu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtqwpencpm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtrlrgadre.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gteuvduqba.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuhkcsim.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtchfkwpol.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtkmvovyqs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtxprzrfcn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtyrsqbkui.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtnssiavwt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtdxlmnoxs.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtnvkhxsam.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtrubooddy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtofqzeqyy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtxexqpcfz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtlyvnxnud.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtutqfkhts.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtkkvinaxy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtckkxynzf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtqecycjfw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtelvoifen.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtyqowknec.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtufjxdjcb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtnflaagck.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtbqwddvrn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtlrdvnjkm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtmfodorhc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtjdcigmhu.html


<!-- 参考信息 -->