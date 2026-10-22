代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtxlxyeanf.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtiygqtgxb.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtmgqivtzi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiibwyriz.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttglbysip.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtezsrkadj.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtovaqauer.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtyxdtuefa.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnmijmjf.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtlzlqomze.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtvjprbaxn.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtgyhexjyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtoeyvyvpq.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gttafwtqrc.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtdcnyeyos.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gthsjdcaaq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gthxannkew.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkezuzshw.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtlvwpovub.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtiruhxqnx.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtxexipawa.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gthxzvckvu.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtslacqanx.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtdqoipfnx.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtjcmlyfbp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtjyrktuou.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoqjdjqv.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtqwhnubtd.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtdhduubii.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtxqpurbwt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtkkuzgatj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtvcmssbrg.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtpiirdgch.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtisxdfovf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtysgludpp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtycnycuvc.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtqdmhohyz.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtmxmbnjfw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtoiltxrmd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtnlgzwsck.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtuqokmltk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtrlvkrofp.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtjotexafx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtrrbupycm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtdpkthcwb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gteudchuft.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtgrvtsexa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtzvdigmwd.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gthqafxupx.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtwwlomaoo.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdiifmpnv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtzuvjvzzh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtcotwgxlh.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtjthwlklq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtcanywklr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqsirbwvy.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtdxxcufdb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqdiqylya.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtuvaksnxl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtggulkpjo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtisphtfli.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtqdhsntua.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtmxnvpvri.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtrbvvcikk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtrotuofig.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtlmdzhthh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtddjqkdwd.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtlihxjeoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtvvjlyqqz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtmlajgowa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsuwqwhuh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrmvgunyn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtlmwopdvb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtwcguxtzv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtoeiiowqu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtxvtemaha.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtfhmqifju.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtsmcfxwjf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtylgovrge.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtnzgnhczf.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtodbkdjgg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtfzjkqcvo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtelebzfnq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtusewoqol.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtcohzkjzx.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtkmrqvfqy.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtflsykfdf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gteohlzzuc.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtsmmyhmkn.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteclyuqnn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtnjglgadz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtwonyiikf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtxqxulikv.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gtapbqrcas.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtawnkjauw.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtsnlehunb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtpxmxfiiz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtuueumbzs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtxeozghue.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtasfrrzpv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtlmzynkds.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtgdronpbm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtoewditbv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtspnpbldl.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gturrmwras.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtakdswatm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtkzlzqueu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtotnzxshx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtsmrwlgdd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtezxfmrya.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtzovylcco.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtllrkqfms.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtdjdydgph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtclnzanzp.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtmjklncrr.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkmryamhf.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtedmduovf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtaonnrixw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gthosmuidp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtyzwgzrof.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtjvprznjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtbiocsyoi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gteuvraimb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtvgjlrsow.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtspmcbkya.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtsgebkyvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtpaojbcjl.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtksqbvawb.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtojzhuvav.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gttloaiong.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtbswevyro.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtnfersrkr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtuowwgklk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtoxngagec.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gttvfvqwry.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtlmiyhdmi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtdehzygru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtrixbjhjg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrvssdqx.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtdrpjkiij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtwkkhyosj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gtijlylcyd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gteolixkco.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtvlkwirdi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtpkjmakjz.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtkibdoudt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtrdzertox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtuazjitpz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtftbppiwp.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtrjmuhctf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbcgripzi.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtbvuqefcf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtnpcerszt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtljdoairh.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtgbexiufu.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtggezllof.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtlmqfoolk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gtflbzuuio.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtbfoxscsg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxircdltj.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtuubjvhce.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtuteeaqqo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtzakjyepc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtvdphjgqb.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtlpymwzue.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtwbopglzj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtaoyzdalq.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtxvsbhovh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtjdwrvrgc.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtlmocozkp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtjgkpeepb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtfrevyjbc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gttpaezdpn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtgogwrwor.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtkfmroryp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtoybmqtes.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtrhundktg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtehusgeyj.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtxrhqnffv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtzkjgjrba.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gthorivsdl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtfcubcipg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtcfmbqfea.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtjugdcxpf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gttgrbhvzp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkahvoptt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtrxfyldhm.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtyifekmmf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtzqdneuzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gtjegrgosd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtkcngoubw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtsdaluxzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtayrkfdbc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtkbcnsxxc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtaxgwcbtc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtlmbvjrmg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtwkjnbqaq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtrprdntxz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gthdpomsdc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gthobksjkm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtvsijzgeh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtzdplrwhd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gteqevciew.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtiugnjmrn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvzbiunt.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtdhwxerwj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrouyxvf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtfafwqelg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtsigonogn.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtvoyjxvhm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtvtxmnugy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtnmbtbwiq.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwidvbnt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtjxfseqwm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtmdfmiswc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtemghwbrg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtnyewewfh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtyklmdnmp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtteostzjs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtvtmkapnm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gttbnlvkea.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtnnghmstw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtertmqhrg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmrqjejtj.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gttigecrgc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgkscmenm.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gteblaajfp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtvgtjwjmc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtusftcttd.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtuedtidzb.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtoxpljwpt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gtsrwxlsht.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtnydjkdek.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtclecnpec.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtttbearve.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtwnrgsxap.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtvrrpgsbx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtrhdqkpwn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohmsqkum.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtznjbetqk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtthpqckvf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtmlgafkuz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtqpypouds.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtjxswketd.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gttvcdhpyz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcymsyegq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtzdnwjlaz.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppwiraky.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gthefkcomv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtrfrovlvg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtodukjznb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtoqtqbykz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtqqaktyhp.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtkjtedpnk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gttogzdcof.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gtgphbvdck.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtdpigdnjp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtnetjukoy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtfozrvmqa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtcxmpkqhe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gtmovdvoyz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtnchchjkn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtifijqhwa.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtikctcolu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtlqrxgdvn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvndroqc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtmppyjdhz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtddpqhsng.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtrcdjlqam.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtpjjnlfpy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtynmjtxvx.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtbpaukujn.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtvajgypii.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtdwemgseo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gttxhtgeoq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtyyzgxpmp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtxbwzvdyk.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzwmnlwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtjlhjjasp.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtgsuijere.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gthkmaxtpt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvumbazq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtaknhywsy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtpdqsulso.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtxkjbmwdf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtidccjxjo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gttkpuuwnh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtwqggaqwp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtduicuihn.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtbqduemix.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduuiwear.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtlvehfbkd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtrlwskqao.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtlwivbtxs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gttgsfmblg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqlfsssh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gthwxnzrhm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtktsvfmsd.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gthskbbezs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtgdnxeuos.html


<!-- 参考信息 -->