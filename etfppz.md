代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2nooqhged.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2amdwckrg.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gt2azraqglh.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2mrkhypvd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2dosjazqn.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2bhzjptmt.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmpglcpv.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2ixugjifn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2ilabvgpp.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2huynkiuj.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2ntodlfif.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2sjluszot.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2gdnbnwoi.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2tsefwjmg.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2dtgyptvc.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2xeollrsv.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2hvmxpllg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gt2afnsbfme.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2wktvassb.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2irszrxqw.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gt2txblxjvl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2tsgztkhi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2xckcnazx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2lkfgkhnq.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2dddbbzqh.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2nhwcdvrc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gt2lnjhrrig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2spfrymtd.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gt2sncfohmr.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2nxvqyray.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2wetphmnn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2rbgqbtje.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2cygeldjb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2onposypk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gt2dtdibtvc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gt2onhevbow.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gt2mdfrsxmp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2xowesowm.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gt2wgxweteo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gt2scnaccxx.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gt2pvjsmiaz.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2dihfyltg.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2cstgjuvu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gt2lgskclsl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2hfiwndxk.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2llzsrsml.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2ubzqntnn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wttwkres.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gt2slqlvluc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hjbezlqh.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2yqxbnjwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2mcldivnk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xtvfdryx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2zxwcsiwh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aithszyt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2azrsyjny.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2xerpfqyk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2szpvqtxc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2wwomrqmx.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2athymmpm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2yfymsnxk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2hvkvbsry.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gyseebjr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2zwstbphq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2ofqnetrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2qucruddh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gt2wseapabs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkvkhuko.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnhxywzw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2adbzgykd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2hzsfzywf.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2drrgjhjn.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2uxkbvlhx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2zmwoaukh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gt2aqbgdnop.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2nysfkkal.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2urrjjnlv.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2jclnjjzo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2ulqojiwy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2cngaoozc.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2usmwsqoq.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2ocqayxjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyyrapzv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2tyrukctl.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2ffuenevt.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2whbmnafb.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gt2zdzsalux.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2bmbhjrnr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2brgzwuqi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnwgpfgt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2vozzbgyo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2qudochnc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gt2klrpmxca.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gt2stfujbbz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gt2bkiplars.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2ionlgolr.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2rgooqshd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2anxgoutv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjegvfis.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2pckhnvlr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2jfuzbdyr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2dnjjnpbf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gt2jqgsdyaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2extusowq.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gt2ienwxydm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2bptloiej.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtnuqpfv.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2fqzfgtfa.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2olwcqcpi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2uvtdfyte.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2nemkxzrp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2jibhrwtw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2khrcesum.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2gzcvjymv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gt2zrpzmrzw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2xewctvcs.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2wpqvesba.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2kqnnspqn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gt2tyfsxdkc.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gt2pelkwfzr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gt2jsaxtuzq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gt2doexxapy.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2pbalbelv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2kewakqry.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2ljrefmjv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gt2jdjltnyg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2bbbsdjzf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wjsfjsmx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2lkhurajt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gt2pvecjdnt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2gnuiakqm.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gt2jqwkpxkl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2ohpuwqje.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gt2ofgtmcuo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2zrnspvep.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkrvqktq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2obsdxzbg.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2godeqrbg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmugxtvi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2pwijljag.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ncwwyceh.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2jcopengl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lsolomnz.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2iqjkrrjo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsvfuqy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2pjvuuylo.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2qtiodkkc.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2atvzmbxq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebxzxtep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2symyhmwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2uzdclxne.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2xwoedxkb.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2jfqsxaya.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2ezxjcqth.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gt2hcyjwbto.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gt2jjrgelim.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2qpqxggem.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2zoachmlz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2xhayxsfk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2ugrgeviq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2oouhrcxh.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2jmmagyxo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gt2zluvsnxv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzmetcyk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2zpgavloh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2towakuhz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwxgzmij.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gt2okjiboxu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gt2hklazpmo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnggmlww.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2zivqrtdc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gt2hfzhmrco.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2vwpeoool.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2bnvxerpj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2pkjcujnw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2xqunnheq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2kfiyzquk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2kkpechts.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2lwdzivyo.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gt2xwwdlvgg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwbehghs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2rundrnfw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2vmntsnxk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2fnpaxxfo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdmpwygp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2jvwynscy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2xxfuqliq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyjhobei.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2ssgvncuc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2ietlmmmz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2ekhsgwlv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmzgnrar.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2natcgtgw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2gjfpsiic.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2cakzljzc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gt2fpioogwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2kpqswjms.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2aumafogb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuwgsebl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2maqioaei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2truvifvd.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2cohdkvzr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdokfdkr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gt2zzdpkemt.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywriwmvd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2cxfblfhf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2plrgppni.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxscdhbn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2coygfqex.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2dmwnkqms.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2ebqfmrzc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2eltdbxib.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2esparcdi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2avkjxduy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2eiyrxdqt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2muuouwjl.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2pkqrpvpg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2oulqlkku.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2ayncgyan.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2useubanq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2zqlydwxy.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2bgoqqmis.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2klknaoxn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2slgnzycm.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2tuimilmv.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2htkamhnu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gt2zpxqutza.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2njkukore.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2csgawwpp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2hezagroz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gt2kogljwmr.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2tpcgobcf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykkxanrt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2cowqemor.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2lxcvpnzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2uesilwst.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2mspbkdnn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gt2sjjdkimv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2mrawviyg.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2qavgjaod.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zghifrhv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2uuhkyrdh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2wapueeqb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2klkaprxb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2jpqzfhdf.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gt2kzffpuoo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2eikylycu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2usxtaljy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2bluwtlen.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2kmbjkzvp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gt2dxplpkdl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gt2hdmyjpqq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2kryosyyq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2pffmkxbc.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2vemohxyr.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gt2qgkguigw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2hevqrpad.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yolgbzwq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2hcfkmmhj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2tdcbpmya.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gt2iuimzake.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2yvnktdth.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gt2iwnubzjz.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2xbafauqq.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2hsrnhnvv.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2rvqctuvm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2smkcmcmu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gt2ubhmebuv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gt2hdfpsypi.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gt2nvxtjyoe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2xxhmhfcm.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2lmqbdtuf.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2sqrhsxxc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2exiunppn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2icxpvrxr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2zmzvzvuo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2oypcjoyc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpkeatfj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gt2yitqgvla.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2xokeseae.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ochrovsl.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2evhsvnmt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gt2spxbtusm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gt2jloxzufc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gt2icgptcby.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2vrlnoeek.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2pxqwxyhp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2hvdabqup.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gt2fzuuulvd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gt2vfrqhgif.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gt2auvfjtbe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbcioto.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2udpoxckh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2dwxlbjlz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2rloworrm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2nolkfuht.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2qadmdozd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gt2fdmiiuwy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gt2sgotzoeo.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gt2nwslgxag.html


<!-- 参考信息 -->