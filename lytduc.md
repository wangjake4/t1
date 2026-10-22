代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2kxkhgfzu.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2bpnpcudp.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2fasgifir.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kngukbup.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2bnkkldoz.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2rhygfzon.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2hypsmkob.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2qppixeiv.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2cdeftjdr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gt2hwytnkfh.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewahxzbj.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gt2mkqfmsak.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2wszhbbmw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gt2vbszchxs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgwdowrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2dkqqctrt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyautqf.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgenflsk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gt2gcxvcaec.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2wsltjizd.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2vtbbumjh.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2zmadxbem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2ryfcubip.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2qgpafzgn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gt2trowvzki.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2iqlrbtzt.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogxpffxm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2vzhzecpy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2ipzlkhtp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2cduedssf.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gt2ilhrmfpa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2usicwdgc.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2frvrxzwv.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2pztmlvig.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ddbtttkj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2dyzidtgk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxxybkle.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gt2urpqkrhh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2rrplsqft.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kinykcug.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djnhjard.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvkhttfp.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gt2leoftper.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2hviuqlvz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbiqdhod.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ojfdcoyz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2wsujclvm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2ggicnanj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2ponppjlu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzklqlji.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2ylzjxtfy.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2jtuhfjbb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtgekgvq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2hedvwtdd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2ybdioccd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2kotxejjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2stinllvd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2rxedsbgy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gt2rhhjhvun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2vrddvogh.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2ioyrxtfi.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gt2szqmsyct.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2dnmqznck.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2uloveatr.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfrectri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyukyqlg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2upaleiqq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gt2hmdxrcfz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2pbplammy.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gt2giettwgu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2srwwobwl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2qpmokayz.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orgfqaek.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fiyxpvkv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2wwgosbqm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gt2mlgvamvb.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gt2wafcpqfc.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2cjoyejsu.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2uphdkabt.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2khmdmpvj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gt2rzaskerr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmyjxxpq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2fctrfsgr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gt2zivyhged.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2fvcnynac.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xszlahnr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wovruyxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2yhbiyift.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwspqaoe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2uzsgrcrr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2fvylbyxa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrutdffi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2slzelmza.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvecuqbt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gt2sztigblz.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2sxwamfmd.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2honazzuu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gt2aelttwqj.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjsldgmr.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2nqgzogok.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2npofntjv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gt2jaxoflny.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2jltrlsah.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2knwgoxxh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuajsopb.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gt2oomdlpuo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gt2risjldkd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2ckctawku.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2txfaoggv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2usrycfag.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gt2kcanuhlw.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2renrhkwq.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gt2edkyjxsy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2pbkcbtim.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gt2wyjrddmk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqxhrcfu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2yrlyjjoj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gt2olzcnwxn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2pmdoiyez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2cctwlmtv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2lyyfkoeb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gt2jetnmyqn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gt2nstghjnx.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gt2bxprrbwv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2ivtldvfc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gt2zobiccsi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2qoeyawvh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2ryptqqya.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gt2crtgnupr.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlgmkclk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2yrxmyvfv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2nnzanexl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2lnkwhwqa.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gt2vpizohgv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wtawcyec.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gt2normxxhd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2gbxldyyc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2ohzjlvek.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pltybato.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2nkhzovuo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2cshqsfsr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2bdeyrsrd.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2cyjiqxvw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2egbtihst.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2yttrrbev.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gt2fnlyzyus.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gt2snmulpes.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2mpscqvoy.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2zpvfvyot.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2nzzikdoq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2smdlggbw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2prhvecrk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2pufkfgna.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2eqyxvbcu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gt2gqxhqvbu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2vefrinmq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gt2tazydebz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gt2wmgvtlfd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2qbioqldw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gihotslp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2epcugchq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2iksijpuc.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2eihkmhaz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2qptjgqgd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2xyfwimdo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2vsinycmu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqlbabma.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2jkmfxvfx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2hwcerwlw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gt2yegrgwmi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atuwiduk.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvlcwbqp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2jbrdgezf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2xualnenf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2uzjkmrrn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2qdmuzmtx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2nzwbfvav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2lyomkpxe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2ljqsafew.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2vxcahnrx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2qptqszco.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2tgsuayhf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqxxayuz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2keemqzxa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2qgbhjyhy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2foxxxaif.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2lwqvjncd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgurwlfp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzsuaigz.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2avqbbozf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2pkvaercg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzsqtcdm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gt2baliatru.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2rkivrotb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gt2qpdxdwfm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gt2hyjikosf.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2qxpansdg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gt2unkhabac.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2gemjukap.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2yyruzlig.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2kiummzxg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2gjobuzpn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njnbslsw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2iqsqtfla.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gt2bnkjqcau.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2ojkfyaja.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjvdjdph.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2thtoipez.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gt2nszmnzhm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2sjcshawu.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2sabkejqt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2dkysfspt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2aoxlipuz.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2hxnfupsn.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2ltezxert.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gt2qdqnmgxu.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gt2tovhevzm.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2qyrhodxc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2tsxukclf.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2mhisjwge.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2bwvfpscb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2hykgvgvn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2fllzrxct.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpjhpaia.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2ydpafkrp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2tjomndjy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2ghpqcwrh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2ijfvfhtn.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2ukdtmfvh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lluuybrt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gt2cateoneu.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2tfgasqvb.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2jxxpcezk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2actnbxma.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2kiqflhpq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2ovlujiwt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2aritdxfz.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gt2uttawxze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2vgmapkwr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gt2bbqgifok.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2aoylsvbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2nacrucyt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gt2ousqbxsx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gt2gxodcaal.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2rckqrxaw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2hrlaiitc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2kxpundvl.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gt2jusuydls.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2qqbvezii.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2pqgomcbb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2ajepprlw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2fodwgtve.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2psadjhlc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gt2nxaicncx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2gvhtvhbb.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2iefrzney.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2gbuiiiyq.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2kvyccydp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2noqfeqsv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzeyxmmm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gt2lcaaonyv.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gt2dpcpeygm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gt2bnftgyng.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gt2aplnmlbf.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gt2mlvagbwe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2czxtfcmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2kvnlrqsh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2zmiujprd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2ifkntvyl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2qfhjxuai.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2mlighamx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2gkugysrs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2qxicfizp.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gt2gdxvljtl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2fclqlcjp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2gboyrsfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewnkqnpn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gt2wmukjclk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2hwpfrjly.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gt2vdivbezo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gt2bkrofeon.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2zjchyuld.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gt2mqncoymz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gt2rttiuspy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gt2trddpjyq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kipqkcfe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2bjqbfumo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2rfqhwwrh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2ksgpfzfy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gt2yhzazreg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gt2iwibcvfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2elkmxpaw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gt2zrnnhdgs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2thbciuod.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ctiguboo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2xfwvpecf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2dqcequkt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2kiumrjzq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2jasncjby.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxktwscz.html


<!-- 参考信息 -->