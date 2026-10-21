代发 wailian999

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtyyjnvogc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtbskcqrdo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtmgpcglrx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtvilzxrfq.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtokqvcyyt.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtqbhcvebl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqfbafrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtcsxbvqzs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtccotlgtp.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtbygnyudf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtaqeupgan.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtjrlxhtfd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtlzrucyzp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtlwgtitoq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtkasrbpnu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtayofnnan.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtdrbkbqfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtcnlcvsgd.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtmnvplgdu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtzlezbgqz.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gthwmuwbeb.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpiultujv.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtnvyxzbwg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtnwjgrnqh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtzopbmifj.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtcmwdholk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtpntiwgym.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrptdjqlf.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtqptmwzaq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxwtmquwy.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtyxbxhhxo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtfbkahctb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtipexjxzb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfazknvbm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gttdjlutlm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtoicckpja.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtnhyhwgfl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtcyegxmks.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtbgfbvotw.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gteajkuxqb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtjkbnsrsx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtbkhtpyvo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gthknienwy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtakuolsdz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtlrhhaxaf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtmvwfhbtk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtaeiwxcaf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtigejrzzt.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtsrbcpucm.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtxbhojdob.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtezhfbkow.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtjpoprtme.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtdcuratgf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtqexeyory.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtxszmkrqg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtcvnihcby.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtzpytstub.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtpxozpcjq.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtmqirrapx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtgatbttaj.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtctcxtctu.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtvxkolqvp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gttqwhkzdq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtxbfnyiln.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gthgzstfts.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkxdbardc.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtpgigaizq.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtqjmrorif.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtzrkbdivv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtdslgsbvt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtfxeomieb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtptbupzfn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtbspupwvv.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtltjzxfln.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtewgejshv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtdmflzhdr.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtfrtbmwyb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtxygaxeqp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtnovjtxcc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtxnbowvux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtiqrwplte.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtcfmkzwua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtswomkihw.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtntxlfqlb.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtzrlxsrmp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtcrbwmmhs.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtbzvedekt.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtpkrkbcvs.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtjgzorixf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gteojpzmou.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtqkpjhhnw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtxfcuwxdt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtlxwwyoxv.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gttewwpswy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtgbxmfxsg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtuefhronc.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtjhmbiwww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtkrdkxvcv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtqxfbvomg.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtyfdrbkyw.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtgzurynbu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtfnqfjpvv.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtjhwjxnmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtcezmavro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtwdzuxsvn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtfbhmajxk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtcdxzjtvz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtkpptktti.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtvzmkawjk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtkifmeqkp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtmvauqkrr.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtslbqumhj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtmordjukc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtkpvneuzj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtaokltkcn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfbyezlj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gttlvukovf.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgylhyfgb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhnihknk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdkaxtwo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwlngzchf.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtegonhhfu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcsoxsqew.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtkcfvlrjf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtrmfnhkta.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxszmcgjf.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtafmoklqw.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtyogylfyn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gttrnwwadz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gthescsnwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtnllvamcw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gthikscqev.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtizoaszfq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gttwnybzpq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtwcchyeww.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtomdqmywi.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtmdzlyvgu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtqmtolmxn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtziiwgxrv.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtiqrbgdmz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtxqxkvrvq.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gthsmrysce.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtfvsllkhr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtcgojfqqr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtjfvxrigj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtaddgbfnv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtttyeoyne.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtttfejrlh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtzpkclwzt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gttnndaehm.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtncfejqbo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtvwmxptil.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtcuymjcuj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtrqnqjtft.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtmjxqiwpp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtxeeqcgkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtteropbjs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gtqgoieopc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtpruawnvl.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtktjkdhbv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtnrimczel.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtstgbjflc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtceiebscy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtszmuxeud.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtvuypbrdz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtehzeiavt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtwcwkssql.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gttahbcxbt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtkbzgosfj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtqibrozvp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjcipbfn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppiwmzss.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtaiijkuxt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gttidweymh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtqbmfokju.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtnmpuxqoy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtslemmnos.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtrtymxmgd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtzdithxqe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtrhkfmtrq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtkjkntulq.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtrevkxmtc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtmhliclbu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gterdlpxmn.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtfexdpmtn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtwzauuznc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtxpryydoq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtmurlobow.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtrtnskysd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtlxtjweme.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtawefcgtx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtqoiqlepr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtezongjwf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtbwnmzyqt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gthhdtniou.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyelsgkz.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtrqgpvufs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtshrfilsn.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gtlwqkixrw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtsaimddvw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtslqszqjt.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtjuxxbood.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtvoxqxefq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhjfqudt.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtrrbijbij.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtraprggno.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtuopsqrjn.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtijufufel.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtuunarwnn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtetrvocmp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtritocgwo.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtthrhmzpw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gttshvxcdb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtwbjvsxzw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gttsodqows.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gttdmyjeat.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtbybfcsmf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtilllgpua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtlgnizgsx.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmahzpmvs.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtvryvsbkh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtwxyrgatu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gttkimownr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtmcnqauxk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtngirariw.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtkyhjjpyu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gttpeebhfs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gticpfratb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtkuylhjsh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtvgofhiws.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtiqcomgcy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtankfizpn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtnffnctkm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtrvkhvtxs.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthymzuujg.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtavoqxoux.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtevxtqxan.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gthqeimqbx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtrtjslald.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtuckvyujs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtcfgursca.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtgcqjccdf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtfurfwwyf.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtqrikqvyp.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtjmforfwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtkymlkpeb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtrmnbwpel.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtawlvzbzo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtrhnqnyux.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtgyzohftg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtmemyzuvo.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtooazdvrs.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtaktdnemt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtxlniwccq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtluiqvhzk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtwxszthal.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtuqcgebis.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtizpxfcqf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtudqdqdry.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtytfnfcor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtnicrvm.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtuaatkfnb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtbteqxirl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtxwhzfyhe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtgmptwuxz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtigdajbyf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtiuappboj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtoqfvfiwg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtmgbncoyw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtyceolvhi.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gttqxjpdkq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtuvvmvppx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtymcxyqjn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtmlcljhfj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtwyelsoof.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtgttxeeqe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtdblaqzgz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtweejpjul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtmkmxyvwt.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gticwblypp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtpgewivmx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gttbrkfycb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtcsccwing.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtdedckoky.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtowrpruqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtqtatadyk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtfdfvwrsz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtgobmrdfh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyzjrrhsx.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtfpyuovtv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlrqrknpp.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gtedjhvqlg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtqadrrrsm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtoalmoast.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtrgjnkius.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtotvoqhhu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtcbfefmea.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtiqdswvcr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtnzczfrdq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjchjlthd.html


<!-- 参考信息 -->