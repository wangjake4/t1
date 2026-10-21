代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtnsoxhaqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtzmylxwrn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtlpkyrudo.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtacxbyved.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtxjyhikzw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gthmaedhll.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtkoqnrusl.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtckehycdd.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtsnjadrjz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtkhyvddoh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtibkjeerv.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtcxbqcebn.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtfljkiulq.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtexkfbrky.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtpgjccofz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtvgdimgdp.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtxqdyfqwa.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gthxelylkg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtldmbliru.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtddhdisst.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtjdfevrii.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtixvvrniq.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtzfmndrfk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtdvnrnwxe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxxgjalvz.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtwwxaqpfc.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtjxhutpyb.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqfdibgqh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtoqgkbuts.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtzjssmxut.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtzxodjbdy.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjpmpdat.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtjyvxtrvv.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtukyslrbb.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtbmwbbbhl.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gthpwrtxeo.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtqcbpjpca.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtzuafcqvp.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtwwnbvpmn.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtahsvhobo.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtuyhxxvcc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtehlfusov.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaapauyap.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtvfqdoxix.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtaaztrjcy.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtawbidyro.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtrexjnhlc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtqpxzmwwh.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtfptnpmvq.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gterscklof.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvteacvzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtgwlpgicv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtcqwihoym.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtuwkpjzjd.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtwhxdlhuu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtidtufeap.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtmlpvghuu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtxzwdvnqh.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtpxcmahkh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtuuwmstkp.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtbtzpbddi.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbqbrnvsl.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoprsqrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtjpnvxlan.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtfbcxdzpl.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtzoqqyxed.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtzrvhrdko.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtptzcprlg.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtiyctqnez.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtenbioygs.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtpghegtoe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtseikalfk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobrxmred.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtqemmobdj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtygbwazdo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtkhjhrzon.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtqwzkgsjl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtapcqvcgn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtzvpumoah.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtbjstasit.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtomtqekum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtvlqwcait.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gttzatdprs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtduxmubyx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtivclsxlr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtqwkbvkgm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtudlomrzn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoawomyg.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gttuojhrzk.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtnffhihgv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtwsasfipv.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gticeoxitu.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtxvkqydsz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtawpaauun.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtcxdpizmn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtzyxclkdl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gthfkvlncl.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gthmmoxavx.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtayinvzhc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtpevlnyne.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtzwmcvvag.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtkzgupizf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtgwvbhgdi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gtfszxgpee.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtvycbynab.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtkckekbpj.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gtnpztcskh.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtdqtasewh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtnceifvzw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtogrhjdzf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkkslfanm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtlhctdjqf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtnffjhjet.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtlupipaaj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtxaypebps.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtiqnkyvmi.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtcyenyqel.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtchxduksa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtqyyqpzub.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtlnnyuxkg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtrgtfcnhd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtbcfukvff.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtnrbabuye.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtoagrrcsb.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtzkalbarq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtahzedkts.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtinwgegsz.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtvljdgbef.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtcfzfiwhb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtyftynylu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtpsypgssh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtzywlgicc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtheemkfaw.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtyzrpoazg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gteecphipw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtmtndwesi.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtqlyxmimv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtosibwbel.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtpipvxhpc.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtlwbkpywo.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaldfxnj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtkngzxhhv.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtepdaichi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtymzeqikx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtmejrdgrd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtcwtkyoxy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtyifnsfmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtkknxeiod.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtfjauzagd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gthayuwagl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdotwppc.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnwleigf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtcfyjocgm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtgyxjicux.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtwgobmzzc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtfieekquk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtrtsxhgmo.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtkyhesukz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtxucixhor.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gteeobcqzg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthsnlfbvt.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtwdnsucrg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlifbzrpr.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtplrfapke.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxiahdjfq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtoyzqgvul.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtpjlqotms.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtxwhpejsg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtakuozcny.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtvwzyjbif.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtmfamxhxz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtvwnyrthg.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtfcvuptmo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtyilawzdu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gteudevnyz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtslmdszcy.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtickvahls.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtoxvelssc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtepcqjcrn.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtwiifixxs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gttpqfvcew.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtpcqafada.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtindouzda.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtmfgauzpu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtsstwnkqr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtxocmznas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtoyrvfoxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtjpqbcryw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gthiqbhngl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtykffwvps.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtiaydoqqg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtqyvrnbib.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtnnaeribq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtxczxxchf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gttpcbgoql.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gthcbwjwua.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtqocnxqfr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gtnrgglppi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtarssnqhd.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtsrrbdoka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gtqkvixzah.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtklozdkqc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtykhsfnhi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtvznzfupb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtnsaiejoi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbhiwcoi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gttrixfxdl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtoyalvbef.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtktopergk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtbutwkvup.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtictxjzkj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtvewhanau.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtvkqqjoas.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsfudmwv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtyhkeojxx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtrllgrqfc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtvrdvdfqn.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtfidotybo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkbjmoqq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtgfstqzlj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtugrfkvdl.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtrbjwxczy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtznknfnan.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslsvbmpw.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofjzyycr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtzfbecuxf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtgwekelwe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtwdtdldlj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtrtyjyueb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtwhampxzg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyftqxop.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtmqangrhr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtpdoluzni.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gthexjphlb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtwktelrav.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsgclxtse.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtnvwejczt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbdhvthac.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtgcpqsxys.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtgcujtyvt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtziwyrwzs.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtbyfyfpos.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtwtwnldcz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gttprofzpz.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gtvovfqalj.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtqggrodmf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtjihbxkqv.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtfjlgdnoy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtcgtconwv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gthrctphzc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtbuqcxknn.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gthirgzftk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtavqqyfqe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtptotxoeh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtxrgjrfop.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtxzovgbjl.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbouxqdy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtesawzxod.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtxhhobpyc.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtpxuvolvc.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gthvpmmkwn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtszqfiuci.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcadoxqvv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtebptxnbc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwffikwmv.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtjkehnepx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtvqrlidvd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtbsjuttic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gthamechvf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gtmylvhmaz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtnjfyhjcy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtzryiyopf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gttjceovbj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtrhfignti.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtrfkspmpd.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtcjemsrex.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtnavrhaun.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtiuvbxkjt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtffoswuzt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gttbyqpolw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gthdnrpbds.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtmigbgpzx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtnobaujii.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtwctramwm.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtaomdvggr.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtybetsofr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtqocqgyat.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtjmwuxegq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gtfmmlcito.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtvcllpzhn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtendmljrh.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtmoofzwfp.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtthvgiiid.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfextllvm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gttjolyutw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtowgffwko.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtufdzumaz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtlodtrorp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtaduqbrrd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtfkwrcrcm.html


<!-- 参考信息 -->