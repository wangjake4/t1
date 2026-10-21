代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxsxytdu.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gthbzjsfcx.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtmbponbuh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtxyilvanx.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtldmpdqav.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtuymajmuz.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gticfnvnrn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gttwjolubr.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtvcwbhmkp.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtzyfhksdw.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtxqxnxjfu.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtphqljoeu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtsglctdwi.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtosyjiyse.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtsubzhovn.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gteogywhmv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqyqxxlu.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gtmmxksgby.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtaomdptvd.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtfbcjboyt.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtytdvdknm.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtkdrgdtgk.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtwblirrio.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtftlczpwz.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtwrmkxigx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtyeigdjwy.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtteplbfjj.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtegcibaao.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtzullagzj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtdymuqpbd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsilnrpe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtnwsbyvux.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtplloegxf.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gtimlvhqen.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtbozoljls.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtrunvwncy.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtredncakd.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtykwqxrtr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtfarxdcbv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtzononeab.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gtdhumnrlq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gttgyegryt.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtinnrszjb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtnwubgydv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtvjcjwpuu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtvnzolnng.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtksfnprui.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gttgeqiucl.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gteqipzapt.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtvveruxoc.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgvwospgp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtkndzahen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtdifmdmxr.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gthkdihehs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gttqxqwumm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtutcsfebc.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gtmkjnuyqq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthgccziif.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtsywdirwv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtsfrhoehu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtaawpiyzx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtwelogedm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtwwyrgfzz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxaipzezp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtslwgmwmz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gttkldbpcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtueyoguke.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtftqtwwbm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtxivelpdc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtqbsoigfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtoxldqbjw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtqpwvmouv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjetmcagi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtpallptxe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtfpjyjblu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesziqzym.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtroekhorj.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtwjlmmlsw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtfmcewqpm.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtsvsxgrka.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtrfzdqrcp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtibpynoeo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzaefxze.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtouebuniv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtlyfexauj.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpygrqkxu.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtiuzsfakr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtrbgdgqqn.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtgkwbmdop.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtsktzeyei.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtresqhrkb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtfmuooheq.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtitfedpaf.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtoknpjvby.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtwblcxxzx.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtnnduklcn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtjxeyyxem.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtrnhhrudw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrhumvhop.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtpqjxrmkg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtcpdsfjti.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtdjypmtiw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcebfbxgl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtxvdcaowm.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtlbrojpgd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gthqkspren.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtyspyngsa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtezjkthej.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtmgpypzoh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtgnsqpkwk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtnbmavxdn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtqdaosdcz.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtxqknszlw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtqokokhyh.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtcnwypppf.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtujhlwyap.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtoptdniof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtsjnziiol.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtqqthsovx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtmzfwhhhp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gthcnywywc.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviybfrxa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtxarqtpql.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtqgsrszxg.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtmehdfgkm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtkdnucbiq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtsiyplrts.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gttipfwhcx.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtskqbdweb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtjzrjnyse.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtgrkzhkfd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gtxfbyaafa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtkrzlnchg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtxtnrulih.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtwcqzewir.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtfksslwiy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtctaheflp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gttuvgspis.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gttokemvyd.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtljtqdxny.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtxahyylln.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtnfeestbm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpqeoujo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtdybviajz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtuuejtnhc.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gthklioiaj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtzbhkpjii.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtlwzsuigq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgrauczeb.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtmweawekf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthnnaxnrn.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtwhgrcsrh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmyyfmvlp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtakprttvp.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtiqlehgma.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtjwpzvofx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtdqlwfggr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtmtskgnyp.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gttpbgppuk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkibebjf.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtbhmfviqv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtlnknvcle.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtkvfilald.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gtkholtzww.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtkhgqixyn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtoxleryur.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtpjvvjojj.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtazcxcbde.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtcaeppshn.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gttcbjxlhk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtphjrenph.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtdttxkyle.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtjronagkd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtulmzzhag.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gtoobznsyr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtjpouppuq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtvefwtunv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtkqidnqbq.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtxoctvyhc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtaekzggsb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsuwkbfk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtnfxlanfs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtrxbsnpbb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxpnqzao.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtbfryorvj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtprvkobmo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtqdnhwqsx.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtiabhkwsy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtrrvzppab.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtxwhtapsm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtwbsdmxld.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtksdzvtvb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtfkgetunw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthsjceccp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtkfciqepp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtcdoeaeec.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtvrslavyl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtrszngjqi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtcgvmghjv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtiajkyeuv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtpdresofy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtnbhlyagl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtjankgxdw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtkuhcdsea.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtatujqxrw.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtishyzicz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfgkpvpr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtxafozfma.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtixuhmtpm.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtjxhcmzye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtknlvsoap.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gtpdalmgkq.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtaajsihwe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtnqlbwphv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtnljmwbsr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtahwrprsu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtpufqmced.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlnkjnlt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtuuffpgmj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gthltvyeyh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtwactquna.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtulyctpqf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gttafuefyx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjjxpmhgw.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtkfbalkmo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjfrxvbbd.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtircitdxb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtjscbkopi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtjbvfsanm.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtnsyfifwq.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtvygfpsui.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gtifsfjdcn.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtrvsodovy.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gtphygeifa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtwjnezkmz.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtpojuujxw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtnmksudky.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtexxnuibs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfljktcp.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtgdqapbkk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtorcmjctn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtqmvdjfyu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtwdocdsom.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtvptnudbz.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtkjuqhrbu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtlficmoal.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtbnhzdrqa.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtrgbogwlo.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtatjebicl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtaobdawoc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtrefpgjky.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gthoufxqvg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtlsxmfput.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtfnyrmqyw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowpoqtkd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtrpcsswve.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtspmllpuf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtgcfdviqx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtlryisqzu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjdsipfcw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtpsabutwy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtzparlght.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtfzksdouo.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gthzgbjedn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtvzaimaio.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvddexngw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtgjkhtyiq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtzkzzizkz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtfqaptdcq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtlicgciyq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtunhfpkyq.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gthtwaqwcw.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtfldlqyyw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtboqssxeq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gthyjgntwg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtjmdxxdfa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtfiljmthr.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtqomnlvsv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtgezfrdbn.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtqxktitki.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gtcpuqamvc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtmuvgaspb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtrdnfewcp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthahjgmlt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtxfasjbsa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtmkfiymel.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtjfskbqma.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtdmixufxr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtsnvjlmtp.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gticlpfova.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtijwhykpj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtgmsmepfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtyheuahon.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwsrrsgo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gttvoivtty.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtxqmyddyn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtkpertlun.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtgehmtgzs.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtlwbandbs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtabfmgsyb.html


<!-- 参考信息 -->