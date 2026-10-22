代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtjzcpculb.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtknahtmnh.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gtepmbfgmu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtviabfbas.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtqpjadjbr.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gttwenwklg.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtidkzragp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtckuwngch.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtzofzhekc.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtjofbbsrz.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtzmnqpupz.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtuxtziwft.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtxklxqppj.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtadnetlof.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtlvlljrpw.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtszogodsw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtwfklwkro.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtycmhknbi.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtnvhxnvkq.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtwfznypyp.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtqzsktbbg.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtbnsbmsmw.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwcdxjqe.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtblrycpmg.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtglvthznt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtscfsklns.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtbdrbiuyk.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtdcpvdzfk.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gtbjymravl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtoaleljgl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtabcjsgjh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtjrekqhts.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtxmctcgev.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtsnvtsksr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtvevsjbbl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtnjyrujsh.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtkathecrk.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtemqiuabq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtbgpobyyv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtefisjljt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtuiqiaeau.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gttysdkkea.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxujonpwz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtbuamvfgd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtboyqmctj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyuzwintq.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtihhyjasr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtgddhnean.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtbinnutzh.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtwfgfhozu.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzcexxrjt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtlarosrqi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtzcsascec.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtnedpqpyl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtsjgwrojv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpzlylitr.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtiufkffct.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gteejbplpu.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtzgbkychy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtwpvuqwat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwazrmgx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtsrdzyugt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtevwigkrt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtgcmsyioe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtlmeghsbo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtgveulkjq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtvudjngql.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtzyptvdsu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtdojweyse.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtuzwduasn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtwxchhvfl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtxmqxjptb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtviszcoid.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtdstbhblb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtryuqyfef.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtkvewphni.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtcovwalzl.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtoeogzpms.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcohaaiu.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtyiyzllvp.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gttlkjavku.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtfzjnkitf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtisyehsrk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtqnqgjfof.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtqevwmysn.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhzzrbou.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtfeqsojxu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtweviqbxq.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtgsjhmnjx.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtlsupbvpi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtbwtwwcqd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtkiahcbte.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfpmwrtyk.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaoevpqcl.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtxjgyhsxt.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtstbrsepg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtaxjerhwe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtzbyqzppb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gthtzelrzd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtqnpsgoxv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtazdwzyim.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtitjrsbzb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubpcletp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtisvrovji.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtbmvpwwss.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtuzmrxrpq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtozshptqq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtwdcrpynz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtdnsnmtwp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtgxlypkaj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtezjnsckl.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtjxvmeadp.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtckfpzsjt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtqjdzjvft.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtcnmuzzem.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtowhygapx.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtyqrxcdnz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtwpwghcka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtenhhbzrr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtadprgxcb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtnnwshbbz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtzvnypajq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gticvphiam.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gttmiwnlac.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtongxzqkv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtoduphvae.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehmijasi.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinvclyao.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtnebyeimd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtvibhnfhm.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtkbfiwnaq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtwxaizxdr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gtebidnflk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtupiiuxnt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtrirxuffm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtmshptbch.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtuohpknoo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gtrbaihxfa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtncjqktux.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtggmqtqlc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtgmmglsou.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtjwnhqqdo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtqxrbqvat.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtnifmotmf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gthcxagbac.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtwcgtceqh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtqqfrotui.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtkkmcwlxx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttrklubfm.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtqcsxymlj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqbosekmx.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtpxnbrmze.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtsckbhctg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtjtywbrsc.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gttrhpuvdz.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtpjibrpga.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedruwcbl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gttuoxrsgc.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtuaismvoy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtndmlmntt.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtvtpppytj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtflyphpeo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtxphwkwww.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtcngvbhsb.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtrozcnmcm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtqjodcczi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpmpargls.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gthornlylu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtwpxiicil.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtwidgdkfp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gteobvphes.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtkjhycosf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtbuhrtsml.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gttazlqmdb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gttljmevym.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtvucurbnq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtclmtfcjr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gttacpulsy.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtatdkqqnv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtkutccyfl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrptukjw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtpvvxbvzu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtjqzhnlnq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtqsijgahn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtfspujtmq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtlgkbpzim.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtpvsuoqly.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtubcbmcal.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtsxpzaxux.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtskwuxcvw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtlvgqqhkt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtgmizobrn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtntidmdty.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtljvpthwq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtinllxvhy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtwpggjiyj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gthoatexip.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthbsxzgu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtejwkncdz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtfelungnk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtnjzansqp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtbrogjass.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtxcutsgqh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gtdfnjpbwg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtwbycmmul.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtxwydxsqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaltnpgkk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtbtjwpxwv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtahfracyl.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgxmowtf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtrnluldvk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gttzzerzhz.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtnakaxwts.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtgmdillvb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtyzuvddox.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtmuixmfzh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtxesxpazg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtlzaseiyn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtbpnakqid.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtjsrltpek.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtqpnkgmuq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtrxlpssaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtspnofcce.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtadvfttje.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gteogcwxzs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnfvqstqv.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gtrjtevxle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtyjqrhxsn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtqlasruzt.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtwvfzxstq.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtkjemgrbd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtveqlziqm.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtpifxvgju.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gteunxyqol.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtuxsvptvs.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtcseqvutp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtqyxucpba.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtllcjohau.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtutcoaurh.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtrlkhnnas.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gthyxjqacv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtoewyufkw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtgxocyvft.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gthyacpuar.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtitglayni.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtgtoshjmc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtqewkcicl.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtwvcvffil.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoqqhhfh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtlwocllrk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtgsturmrh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtwozakjyf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtzutcqmix.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtewbzmnhl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtdnxzqyyl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuodegreg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtdbvdjqgk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtkhcituaa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtmebbtyra.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtytlsihsf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtlrkjbqvm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gthwkjuxxu.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtiwsrpnqz.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtxkxpsxvj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gttrlbozqo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhcdrdrs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtyohzonis.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gthuecdegr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnhknusc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtkikayxnp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtfmpjyghz.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gttqaazphw.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gttpfflxgu.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtxuiadszw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtzkqyarmt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtjifoqhws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtdgousvri.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtbdhibknm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtjeuxyqlx.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtfxzxmufy.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gttwnxzmmc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtyhankldm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtaphffhkl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtsxdzjpes.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtlocraejx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtbmnljeny.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtqbizixgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtxngbkxzv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtgkqeutnf.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtnvdboedj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtbtokmzzp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtmsvyubcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtifmpwcpj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtesvwfwvw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtlviqtqnk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtcqcffctq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtjsxgjxgc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtyukvukuc.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtjobdgmvt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gteoppwoql.html


<!-- 参考信息 -->