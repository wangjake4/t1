代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtbxqmneit.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhnsqgik.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtgxzohwto.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtkmxwqspi.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtvoqgvctk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtkivtyifu.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtvatewqqe.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtlkniquyd.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gterqohuxd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gthejwuqle.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtyxldzklv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtsvubmjmg.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtwwtmpufb.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtwuizvtsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtojxqklwr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtzerweiht.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtsxcuzvoq.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtcdowlmlo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpokixup.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtkjrqkahy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtsendycjw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtztdaalns.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkllmfgq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtwbigkvif.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiqfqqcv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtbasixdct.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtdsqlzdji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtcgbimzrr.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtnaauxcjy.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtidczwljy.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtswyfqmzt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtkpozfyff.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtrodykvwk.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtaysznmgf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtenhpqitu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcaxmvuhx.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtkmqyergs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthlzsyqrn.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtoorxmccr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtovqiiicw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtnsonkwno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtxueyilgy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gteumlrbkl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrjmijql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtbctfvhkp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtlrfwrzsh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtiqyaxxnx.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtraapqzos.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtdherdoch.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdfyroej.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtuthootnk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtykopkwqx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtfsvcrrfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtajprosow.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtabhmzdjy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtfzbzyuft.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtzumgdjog.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtkajwbpmi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtvbhwwviq.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtemnhsgfi.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtjiymfrcw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtiwsefckm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtzdwqtrki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtgjkxcqlm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtxmpvhvpo.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtrdgmqsyo.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtnftgtplz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtqkrtyumg.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtkzsuapfx.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjgvxfyiq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtpwycvdww.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtceufxpwc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtitqbioig.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtccjxlxnj.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtlckhpixa.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtynklaftu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtgjvgrhmg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtefejjeyd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtycvmbnav.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtfjkvczqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gteegdhzin.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtmgtranem.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtddmbluwo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtnnfoyfna.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtmwvcsggb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtxegdgxvm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtkfqifgrc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtjicbukdm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtsbzgttmx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtfqhvnman.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtgqnmcsoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtavkskbxw.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtsrwzueaw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtqbefqxmf.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtaiuxirmu.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtomrzidgs.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtmtnxinbm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtwtridusv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtfntnbohr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtpuuddtwk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtowhvxyfr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtxuqgyhav.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtzdzvdous.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtiyhsfiaj.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtqsdmtttj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtsyyucwrh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtkmjpshph.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtbesnggme.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtuxkjroda.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtmmjsvero.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtstmgelcs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjjwcord.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvgtuhen.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtrxibtaez.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoyxuisz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtyfaijxyf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gtpufpaytu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtptaqknre.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtnmsfbnhk.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtbyexkxxn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtwstpoqom.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtgolbwmas.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtrlguzixl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtddeecttw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtkjctmrqg.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtxfowqboc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtafyobsxn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtodjzongl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbcrjrcv.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtgsnmqzuo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgbwnaxsr.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtdvdnlwfu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtsaidzpbh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtirncdskn.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtdshadvjm.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtjwumpjfy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtuprigapy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtifemnlkf.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtruigoeti.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtcogzlbrs.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtgfocamus.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtkoeppmrw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtbtokztxo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtsvdscelq.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtleietifl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtlnnzfpiw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtfvzgrhsg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtrmfwfovs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaqjrqww.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtuvodnmme.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtllvksadh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtmmigcmzr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtbahbuhmv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtrwuxrdfy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtppryjqss.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtkyefyeua.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqjkkulf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtarjvodkw.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtetgigqku.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gtvwnckdin.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtbenzwdxd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtriiqlfyq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtrngvxmsp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtznchwjis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtmnxabeph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtkmjqkuqc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtmizcevsl.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtsznejinw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtfviywrzi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtchwjiohm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtiqwjwxzb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gttafawtpx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtalgqtuvy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclnvgerd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gthyrsdwzp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtuhukuaga.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtocaqqcyt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtcqosdrnh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfnrpgoq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtlwzrzfxb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtvjwosjjc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtvwenunde.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtsoxzrmbz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtgqklvbwi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtqazillnp.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtncyxhgox.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gtkpkjjrql.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtipasuzrz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtwhdmpiix.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtkocmfjib.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtqtpeufoc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtmhncmipa.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtllxlhkgo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtfiqgoqme.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtxqtpzuvk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtvnqacyju.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtqclrflra.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtrzwpaknw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtumrutugd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtmikofrpe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtiylhtxgm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gtfqdrpyor.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtoisnnidk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtilylkmcj.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywjlxibn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtltcrxcbi.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtuobjycio.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtamloqrqd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtvipzjmmo.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtbwwmpxbx.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtfkmbjzjt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtwzrucdzk.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtvnrokycf.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtwokkybpf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtyvpxxodr.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtoswksuny.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtzzyhefio.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtqvhsazhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtaddmnyic.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtajvcyzyv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gthsohetgf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtbpgglkzr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtxtmloxpa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtuusenwvg.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikmhuucc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gthyzxatpi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtegpvpuwj.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtiexyjgqr.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtockwambu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtbxouoeza.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtmarhupqw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtwnjpanak.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtaxdlhwau.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtemhmzotb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydvdtabn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtuugsemyr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtgwvziomo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtzpzeouqp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtevohnctj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtalavfxju.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtwllivutk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtwwsgtyee.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtfrmooezt.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtmeaityow.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtdxbtewus.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtsnpvvhdy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtdjkwoytx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtzhrovxop.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtutqyxjpr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtowfvuvyt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtvlyyzkfp.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtcuhzkkjk.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtracwmxnx.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtepcgyejj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtinamhtbp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtxsrixjfn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gttowfeqnn.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gtkpkuvktx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtphoskljf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtvzwnnccd.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtrrugnahi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtpygbqnil.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtrymikdcg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtxrgnyjsc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtdnpprxyi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gtqyinrtvl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtudocqlji.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtfrvlxcgi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtttolzwmt.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtswqlyriz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtbjvsqxxg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtzuhdgyra.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtapjdmbrp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtmvzbtbpj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtdmrqudgw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtpbhvuznp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtbhwbwdrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtnzqkaekz.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtnuchekcm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtfqfbbehp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtjfqagoky.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtmdpgxnto.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtokfkobxx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteawempcs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtqglbwssr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtkkdplacw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtayjorsem.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtwudjqhus.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtcntxhxrq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtjoddioxe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtjlfnmabt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtljgzcnbq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrtcaqyic.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtzjroaivk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtnkokmxdl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gthigulaub.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthavucird.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtbqlyigqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gteoyaomov.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtlbmcxsln.html


<!-- 参考信息 -->