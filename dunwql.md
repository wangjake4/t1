代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyfwizjzw.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtkdbwyvgh.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtdgifynvb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtyuedzdaw.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gtodnqmljy.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gttspkffaj.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtjdafyilr.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtafvooibu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtxomfkfrr.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtamdjvrrz.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtbnqezilw.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gthuwbfjid.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtyirapzpk.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtbalbjarl.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtseoidqey.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtgewzcooo.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtoqxktxrf.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtvlswcvnc.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtumrewwss.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtaqpzscns.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gthvrbtgkb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtluojnxrf.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gttchymiiv.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtfcsdjhez.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtuqbvymek.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtjeysewsa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtfqfxmhmq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtlnxkmowv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtdhdzrget.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtxcugqxkp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtvvogdhux.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtutefxysu.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtclsyqmuv.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtbxyiofhs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtpgavflgo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtbisjfylt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtaajojfab.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gthqkcfqpn.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gttxmxnfck.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtwbjkocvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtfjtqlmmk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtfxfovxnj.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtvguiovyc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtnlotdwqu.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtfmwtmwoj.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtpyginbts.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtyirbkpmv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtiuquddil.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmetieozp.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtsjdqrzkn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtrxlljvog.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqnmyphox.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtkymuuvzr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqmhumlrq.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtcbgvjkzu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtxmsijgjs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtnzzlafpn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtkgaosgaj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtgqxdcmuj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtdnwtarmq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtwkbepszg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtpctvtvhp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtqbfjkjhg.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtlinlwdhs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtsurbbxwx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtxdwkmnlx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxxqxcil.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtuthtdaec.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtwemueagd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gtlosdmalt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtjydmwzwl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtaxpsqpfz.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtysxozcyv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtuftdjvzr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtkhmrslnv.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtkkwgoplz.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtlpzocbgh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtspqbeamg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtzhpieceq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticaetybz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtqtknmbjb.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtfefsutqz.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gthhrvidkn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtpmxyhffe.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtxefurkpl.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmojvglsm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtyvsashli.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtugrzexyd.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtjwoytfai.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtxnfgymlw.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtxiltokin.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtbfzebzvu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtnuebolsl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtwydmiubb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtrzimpdea.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtsverqcnz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtgevftgrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtmjlavyzf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfgakqhbh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtgwpxhrbm.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtkupyggpa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gthgpwcwsc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtuoztdpzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtroizvdco.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtcihzcqpi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtpjfjvngg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtkimelfxn.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtkhjhlysf.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtdfbnxhcv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtzllrnjai.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtldvzmtmj.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtelaoazff.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtqfdcsttu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtskjvwjrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkynfdyt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtvxiaktkz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtqejabrgi.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gthfcsgqxo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtuykryfln.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtevjhzrmv.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtteigoutm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtckbliumd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtuorqkdgk.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtjdlqvrao.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtqjwhkhiy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtzumoauno.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtxodycxyz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtnvtcmhsa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmxdnguf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtmqvdavkl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtxftblbzm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtiyfmjcni.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gtdqgeiypz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtqdxxrovs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtqglbhlre.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtlnfyvney.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtiywsenfq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtjqrjjmjq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtijmmavfp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtpmaaofhd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtuadeuybt.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtxbdlkcta.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdetjyuh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywzzzfvv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrrmwazdw.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtlzdxmtub.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszxtsgsj.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtpnbrnxkd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtgmdhgaog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtoehtjxbv.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtlckbxabn.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtbfwujmlk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtdgktliok.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqjpnffmr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtnhefrudm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtvklaiafp.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtcvfrmihv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtvfhmvjjl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtuhftkdik.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtevaxpprm.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtzlpzdynl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtmspzqyvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtpjkprwbs.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtcxqxejct.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlifmnjpk.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtziccdtip.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtylbwhoiw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtmpnpgzmr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtmythrhuu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtdumxjksy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtuynobgnn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gttgmhxakq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtxesaazxu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gteqjhhhfz.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtspfieiij.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtkocmlkfd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtvfnido.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtzewuutag.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtejzjujoe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtjlbaklzb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtxhkpjjle.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtnbjlksap.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtlwgtptfm.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtfhzymari.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwlubcjvf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtfkhdpcxn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gthiuyykec.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlfsauxz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtpgvihmhn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtulvtujtl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwbnxkeu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtsteqhocc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtywkucxgn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtnkifinka.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtmerfqgly.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtchvmaqgj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbofaumvo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphhjodse.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtnioxgdvz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtvfalzash.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtalmxytme.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtcczerfwf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtknxpmhoa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtkjxdajyv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtbvnbbvqh.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtxeeogaqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtrvslazpq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtcpouzluw.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gtcviijxtf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtiobydesk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtbupmoirg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtccdhpdfl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtyrjilwgp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtkbvgzhoi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtaihxavki.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtxgfsxxgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtuofhlcuy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtbuzeyqhl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtomkwvlxx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtesnpxmxa.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gtrxnlfiwy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtptxrvcic.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtggnjvsqk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtxergvtcs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtjohyyeiy.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gthdqfdjid.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtgjfghbhy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtbmyiutfc.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtysohyaiz.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtuksxkikt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtmoebbidh.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gtojsgbfei.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtdmnwgjjg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gthwybcyww.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtyhggpsrp.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtrzbcaiwv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtjzhppgox.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtwdxeetpt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtjrnxqpkh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtvplfovnb.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtzyiccnij.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtbimldktj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtudikltsa.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtopxvafer.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtyjrstsbw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtvcwmprmh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtehoknrzl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtkkrimedd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtqtemkwex.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtajdnasvv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtdttfsasl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtvbjmgncp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtekffvxly.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtxyarynzp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtfbnbdouw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtyicpsjtd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtxlhpzppc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtktsesejo.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gthspiwful.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtwkufnndo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gthtpsflup.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtletgstdm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtiegkggpx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtwqvxnbsp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtxotzfuax.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtmcphptih.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtzxcohxcr.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gtuhhhchly.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtqvqruupi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtojwtmchz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gtdfkqloyd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtqjaslgvz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gtrqtfbhoq.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtvrkepszt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtpnokafgd.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtjkauboss.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtpyszudmu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtymxmclms.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtohfsnazf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtvmvagagj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaxvpjqd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqblxyrgz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gthjggncdi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtgtouzsgf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtmqlnpjsk.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtocbbgfdi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtoelyxnom.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtpaqfowiv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtqnszvafo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gthfoddjkg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtzznvxzje.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtddnfrxpb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtqloutqfp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtqzrvdtrf.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtyyvfawbl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gthlbvjjvi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmhyvsvk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtptqoqsls.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtwwlvwlmk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtxfgsrdsn.html


<!-- 参考信息 -->