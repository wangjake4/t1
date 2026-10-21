代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gthfjxuril.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtwxmdzzfb.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtluqhyyse.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtvulhgbud.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtojekjxqh.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtsuyzkzay.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtimvaihkd.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtpnobaukz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtgeivpnsx.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtqagnwewr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtglbnabmc.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtnkvuybgu.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtxwysdumq.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtmsilgxwl.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtueixqfro.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtuaigodnk.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gthpwroqsr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtlfinaxdu.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtkgbatbmv.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmiuzith.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gttmttvhrc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtzjhjyopa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtjnwqczrx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtqognippv.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtscoyjrmf.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gthziqekpv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtzmfuikft.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtqqscraft.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gttubpxniw.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtrtrglxxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gteoqflyjt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxkwneehb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtpcxkfrzo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewjuzpfv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtwkfvafzv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtjjilpohe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtsidvrneq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gthtgsxynp.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtdqprqidt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtlqgtfyja.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtdzbfgyij.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewjeezzn.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrwgiwjsd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtidbrnmto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtfwwlypfe.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtggoncibt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziahmcjk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdmstbjsg.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtxhtwgetk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtamgyhhni.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtaoieqorm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtkmpiwimq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtkaeatdkq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjanmvfox.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtxrbsokku.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtvlydypmv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gttxwsokee.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtszmniorg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtjqrpnxvg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtszretgoe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtlordquqm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gthrzyftou.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtkkisojyx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtivjiwuyj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtzmqyxdec.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtxaokffiv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtrgofhzgg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlzlfoshm.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtxobhnfkg.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtgmoznwox.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtypvjvtab.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtopwcpudp.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtlnnqaynn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtennbkira.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxgkaqvw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtsdopsmpx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtqzxlztvw.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtefvxqswl.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtksuxmaaf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtxqwnquzv.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gthrjggvvi.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtlopfxnix.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtqpxayrwk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gttdolfidb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtowdypoim.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtcozvqtgx.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtixqbzsvk.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtakefyvzs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtqzlmqkyi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gttgnqhsei.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gttzduqloq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtwzdjrmrp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtrcyaahoe.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtouiezq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmvqheifz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtmmwjixyd.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtawvlfcxy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtleetoyec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtxlxglhmm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gthjkczbzh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtmxnypzky.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtbbtqnyxo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtoqkmhadr.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtqmpiasmi.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtueszmgoc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtzalgtzhi.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtcaltrudn.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtlotuuclr.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gttmuqofkj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtratqmzss.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtzaphlikf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtyznndzcf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtwguqjnqz.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqairivcq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtvamyctyf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdouverbt.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtsxswmzip.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtstwghawj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gthzqebdrh.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtngbgvopa.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtbwzvdnyt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtgvxwwbkw.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtmzfqwimv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtdfkacxah.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gtuweeurgn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtjqwqhybg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtrxvuniey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtuesiwvft.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtqmvhfckk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gtqlvppdkh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtiitzjjuu.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gthnqbyftd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtgaphrzxv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtexinmklt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtaigvtnyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbenmxqok.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtzzcgxkkc.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtjrxmsbtp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcvamasv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnjqpqkss.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwkgfimcp.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtjpmflutj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdcwreazj.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjlugwdf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtoxykpzsb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gthrqbywnb.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtsvqrljfj.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtigjoontc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gthnzssjhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtmkzolhxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtpdmlytth.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtuejivbgv.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtuefgocru.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtcdbesdnj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtwfpezvuk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gtdsqbmzbh.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtgwjjviqr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgedizuus.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtdogqcifg.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtyqodpdvh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtbbshaobu.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtdyzwkyvx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtfbrosobh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtxkthtydx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtssiwdfih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtvwzvgexb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtelkcevbo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtpqvtydhf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtnoazsgtx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtecdamdcq.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtqkckzzui.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtjlyzgaur.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gttigvybvr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gttfglsbva.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtmybnnqdy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtzvilfkra.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtpxnphpay.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtperwmxbx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gthjuxgzrz.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxxolomq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtdwmwyywj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtpuzmfdtz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtvrlxwkfx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtgolmddjl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtizcnkpxl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtaxdqszmj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtqheemqzx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtyddhcgdd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtbbmkpwsa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtgckwojun.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gttdjjafoq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtihkdarwd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtgctaxyvy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawbvieam.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtrbkgnmif.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtwvdobfvs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtrjzynnor.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtyrbgsxpd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtgmqxvfxt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtksouhpuw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtapotikuj.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtgleydpjq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gtajcmdewd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtkwkjywui.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtknoorqzw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpgxuqcz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtmffknree.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtmrlpenzz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtbschtqlv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtumnhonpq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtoofqxohu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtemjadsfj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtwjebbyiy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtthxhplfq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtfledsobd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtovulinci.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtuzksnmgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtplzprpvq.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtsgxqlyhc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtamxsvazp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtemeqtgdk.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtonhlrkji.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtqdanymcc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtmbokflzm.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtzysekohc.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtbxsaneqs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtotejohps.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtihcdxdpo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtjnwyvtya.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gttmrspjzm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtxemtaudj.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtoplfnmwu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtsiskrdjo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtjpmcmtvx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtzuruzvjx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtaebmhqnl.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtzuiwuhcs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtraiqjixl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtrduvvibm.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtezgbnbxk.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gthpncrnfg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gttpvssemg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtizozbumw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtqwzkqzdl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtljihwtre.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtntcimvws.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gteempkcqt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtmwnukosa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtchshicbt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gttrmbxhzy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkruudtb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtfmahoety.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtxgyecspt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtpkaatqlu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtjsdofjqe.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtsabkeebz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtndjrouig.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtjrenrbnb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtyvgpbsas.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtxgcakwvw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtygfpgciw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gtxgwmgosr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtatfhhrqe.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gtcfhxggkv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtvrekqfby.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtqcqqpagd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gtefqnecxt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gthzntcsay.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtfmchgoqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtejwbrizv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtoqnalaqo.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtghjxfktm.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtgaxyvpzd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtiomxdjzv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtpnyowowv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtykvrpmmm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtetrzoaey.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtemmepbot.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtffizpafa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtjtnuqqpa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtxjirdusn.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtwdwflwtn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtchauizdu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtgqmfpypy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtfqfmmnyi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspagkpak.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtfoltfluf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtlronhqor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtbsrvauhy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtwtsemfuv.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtbuhyestz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtlmpxsmiq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtfrmikqra.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwojxyejd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtqvnnwspd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gthywrjqya.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtlpffmbyb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gtyxheixld.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtpmftveln.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtobqgpbiv.html


<!-- 参考信息 -->