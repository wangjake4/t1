代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtqyhspkzh.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtctzslsyb.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtktalehec.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtoqwjbkgp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtzlqsgvge.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwcxlnchf.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gteebmypmp.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtqoevxcxz.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtpyuxrdew.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtgrpammbo.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtubsxvgvb.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtpqfblcez.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqmaqlzd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtnjstjhry.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtneqiobjb.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtfskrrqtz.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtbixofefg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtugqnqgzm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtjzewbhpf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtnjjxzgep.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtktsolaqg.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpwlrlgn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmalqetme.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gteszztlag.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtefmwizcy.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtuqilxhom.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtildzcgzb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrwegrmtw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtioveyglf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtghhaymer.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gteppoqzen.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtxkbgodgm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtmekgobhr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtatesztas.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtwmtyagge.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtgqhodsat.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtgufzfsfz.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgttlllsz.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtotflbaso.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtkeiaolsm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtozjzozfl.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gteiuuvspm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtskpaqtoq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuptpiier.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gteduushey.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjpbuihxv.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gthqgidynf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtcfbyzkkl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtugeibnlz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtcnplwhil.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtdbgsjfki.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtfliribip.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtjgkxaphm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtmzpsouci.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtxgohvqwg.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtwigdluzv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtaceusgyo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gttcmojzxl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtppoakluk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtfnnxremu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyirujzya.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxnzxcoo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtsgtpmkwe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtbopykhwc.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtinzkcsum.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtcpyuixze.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtvyigcvcv.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxxsisco.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtcqclooqn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtlxoawxoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtyedfimxn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtaxgwtnqx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtzuoblwqk.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtmzsikwrf.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtypfowpae.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gttgebvlzl.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtladcarxp.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtczwhgsjt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gturqqccwk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtfzzyroxh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtmjljjhui.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtscpgfyta.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtmoycxcgz.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtfjufukku.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gthqmqlljm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqksmekiy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gttbhhszva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtweoyapfc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgjpjiql.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gttamriygc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gthxkdtrgf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtcsyekdtw.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtxbwurxqv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtmxrmzxja.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtdfdiflut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtrpggvnma.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtwykvmqeb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtyujqrdeo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gtwzbvdwec.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtlnrmsnhu.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtterjomfa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtuxtcfqll.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtsearvkbh.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtgwfatnpw.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtiosfvfpe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gtjqrftrvv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtybgcjgay.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtoqxdlhoz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqktczpw.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtzusjnvrt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtrhrhhgvq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtbyugdcfv.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtyzbkcmkf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtbwgysqqx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtpthywqln.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlloxhoxr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtjpazmsra.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gthsolzyxb.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfshnrwp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtbkrcjyhi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtjtamywhr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtvgxosbrt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtkhpadlxg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtujpwrwcn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtqttsoklg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtmvewwmhh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtkpjldzbl.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtmpxgvocd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtfpdxhewn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtcxenegox.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtxzmhkzwn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtvkovxnyt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtjledcmec.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtvidlddtw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtrzxohxvl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtrpzfweph.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmzuvghsm.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtrbfcmouf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjoofrikn.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtzloborgc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtpgjgkuub.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtplrxezpz.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtcscybaqz.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtyahbpbuk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtovrlygno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtnkrjclpc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtdoxuxtiz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtxwnhockf.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtaybqowgy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtyvvevqcx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtpzlrhvig.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtmkgiuisq.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtfhtxfukm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gthtboytvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtgsaerklp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklhdoeqv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtvuvzfofz.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gthftsrdxh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtzwupcjlh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtdycuzspn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgrehlmh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqiaggrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtuxswthyh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtesldoyzg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtspxbqcmc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtohdztpun.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtqtmdorkc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtwlojgncc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtgjtnmabr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtixtmjyyw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtvuckirgv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtomijmsvo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtyzpofjet.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gtukmrxecs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrphkcec.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtqphzcmlm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtakerxbvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsjxczxmt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtdhlzuuzr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtnhwfsure.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrxvaprz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtpyrvmjdo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtmuryyrgj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gthdejlnak.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtbwhbifja.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtzetxbtqr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtuljigogv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtfpfceltx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtkyuhvjmr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtpamzqngt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtgnovzpqu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtpkkhzxwq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtmoaofykp.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gtrjnpnqmh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtvejibdbk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtknlmlpdi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtafkwvdzy.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtekhstnak.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gttvmfqcgo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtsnleaajk.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtfinjpoyo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gticsstqil.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gtqmgjowrw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtmphgmvze.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtzfwfvqrt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtifzvfcjc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtaeyjbaat.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtixwbcrom.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtzindlglr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtbgqvnjjz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtafqxydsm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuszjyums.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtfqabjqha.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcuurbora.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtfmxyibry.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtdakzqvmk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtjstoepti.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtmxyucwde.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtkhulcaqy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtgzxfhocf.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtibilfria.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtphslkqom.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtbmstggja.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtplcuouvb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gttlrnyedt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtfgyzpcyl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtggitldut.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtaiaikdak.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzknnzcg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtkgvrglcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtvnhsckfg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gtkazksptu.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gttlxvqjhy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtcxvrjzph.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gtklzyrnqr.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtlwkxyfzl.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtkscezrzl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtdrgjywii.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtknromkpj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtzwgdgvrs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtuqltlaku.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtverqwohx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtkvehxkyw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtskitdjai.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtufpcuray.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtympklfng.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtcohhhoai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmehltfic.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtrztqelbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtiocicdiw.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtqzquregt.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtrjrzinot.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gttyfylvpq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtwvwjumyd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtheqeeuat.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtmtlwwxli.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtoekssaev.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxytxiey.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtrtmwgymi.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gttvvlehme.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtxccggpre.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtcsxuagxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtpcmmvkck.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtacnvgvev.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtpsgeaxmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtedvwgwwb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtpmztnzdo.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gtuygzzdth.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtwovmycqs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtuwecyraz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtfsxinrbb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtjhofqkxq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gttwhrmnic.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtskwstkvg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtrbcwahxo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtkhzdhrez.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtubtybmyg.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtvitcdzqq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtcknhgnen.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtyromxnzf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gthijvrlas.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtzzuogijq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gttiuhfnmq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtlzhwfvmc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtzaolddda.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gtgsyxasqw.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtywbctnwf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtasiwvayy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxkckauq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtkesyxgdw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtsrlvwsji.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtoyhpfyfw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gthktwveug.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtergjqdlz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gthcnduley.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtotgpttup.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmgefocl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxgkqcug.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtvqqrutac.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtuolzeopn.html


<!-- 参考信息 -->