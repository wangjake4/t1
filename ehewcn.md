代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtzvjzjtdc.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtpnvmmvlq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtosgfwmhz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gthtnemqoq.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtxlpfbvas.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtuvsacrwz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtklqexjik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtbljllagl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtvfpugknx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtlruqmdob.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtffhdkvze.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gthlqiwbra.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtxqxrsvkz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtpwlyscfr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gteagfcxpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gtmbqbwgkf.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtqtxcxhdo.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gthidcwuqw.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvtzlvbj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gthpmazycz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtracadbmj.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtbtmrybhq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtbsolqsev.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsvyfuefa.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtjzlejvdg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcyhqopav.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtyycbkhwh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtpzokzmeb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtjtcqbxce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtxwrxpise.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtomegnrsr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtchdrlqjn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtpfyqmzho.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtukgwiosd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtzqdwfswt.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtumjmrsud.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtpjzqlgfe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gttyvabmty.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtpoqeverp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtsynkwezg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtjdbgroji.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtvobxuzli.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gttuklzobv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gttxenzbis.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gteijpsjjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdegwytbb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gthxsyaxdl.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtpprkyncr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtzpfjbmkd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gteggorrky.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqhlxwwi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtjacaeomh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtusqgmcto.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtdljqllwn.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtsoaiflaw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtxesejgwz.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtojmmphsu.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gttjoboacn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtnpzvkgqa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtaisdnjim.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtwwrnjvzu.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtxbafoglk.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtsajmzurk.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtivpiztli.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtnigcwwhq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gterzigxve.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtewcneqyt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtkcaaixaz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtytjmegrs.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtzgwtlact.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqrowzek.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtqavatagd.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtzzajyriy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtzfkkwaji.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtnialween.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtwfstwbhp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtubkoxazp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtrhoowxsp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtehirwzbi.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtbgguezfb.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtnbwmmkea.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtxxkettvj.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtnocammje.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtlrrfcgfh.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtbagwfhad.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtnisojfeh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtqmhsfkso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtnfzqqwwb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtqdfgkcss.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtejlfuqqi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtrdgqnhjj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtslpfivxe.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtqlmdvthw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtgexijpvw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtawmfckvd.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtywilnshb.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtizcwzoak.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gtitbozvib.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gttmofswdb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtliqgnsef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtrteqekud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtyrdppqli.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtqnglwtva.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtdozycomn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtjwxycbhd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gttyhtnggx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gttjurymtx.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtwjgkjprq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtlsybrdej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtefshmxrd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtjzhdkeke.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtrxkmkjhw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtkzrjopti.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtosrbiovt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtqerxeidt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtquduorvc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpofbbmsj.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtbodcygnd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpjtcrzbw.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtsjortowf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtyymibsor.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrftsvswa.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtouxduryb.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtshluqmhs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gthkvhzjzm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gthkbuvtdt.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtaenylzei.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtxacmrtgd.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtswmozrlg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtugnuuhet.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gtdntvsqen.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtpdvcpoch.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtrsqsozer.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtpcifeqvt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gttuzdoqdf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdkibtyo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtuptvkmnb.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtjdshouls.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtbvsqfici.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtvuhxdskx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtnzfcifrz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtswenbnkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhysdcqn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtkginwumq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtrtgtvsoe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gttvwheaba.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtjbvdixkg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtzcvbvjfs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtqcnfwisk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gthtamqmds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihfhudnd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtwoxhsbyi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtowangeii.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtumuildoc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtberhfnga.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtojhhppjd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtowjjceaf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtqsaskvol.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtzntbemak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtkbjouuou.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtfouhrewn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjkosnkzv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gthfydehvn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gthycjfqxs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtjzvacfvv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtzpjzqsvl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtntxjhpcz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtuuazmwdt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtcfzyveqd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtbzqaigzh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gttanhnbvw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtzcwfyihl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtzterpsoh.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtuompduye.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtbtflcysd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtdkvhilcf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtrgevwogg.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtrlllusxi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtpcyimhcc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtwcsmyxro.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gthdnylxka.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtvenuzmtg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gtoywitzga.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtnswprsou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtxugeradt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtzoeolnjt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdguqddv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtffzbvkqv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtvohzsxri.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtqckwxjyp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtorjcvwve.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpcsbpcfh.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtmorrvjjj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaytovjsj.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtrupxnfpy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtswnfzmyl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtywubkhtg.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtsvhaaexn.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtnrzutcmg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtxtukwakn.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtunvessuo.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtfjrcmdwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gthvvvcdfe.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtcfduzluh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtkpbewtle.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtzjblggoa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtainbejkf.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiboashe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzpewndh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjknbuklx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhpwyfvg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtejuccuqs.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtvwwizjpp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtpgfnwvnz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtgnkrvilc.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtxeruihqo.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtvejzqnqg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtoxgmvlqq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtwthlyafj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtsnozizup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtdcxpilst.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gtripvxfur.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtthqwfudb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqjrxyki.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtzjfqkaqk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtefpdpcqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtbtnljvrt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtpyurmuyy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtlplqzpdr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtpkhpxssf.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtatqqszit.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtwsjgxbss.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtnborcilw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtzfkmeaos.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gthosbhptr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gthgsbxfqe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtkiupzxal.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtdpslcjkr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtlixfljgi.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtjtiqhknv.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtspisrtpx.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtpdlnkfyu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtxwaejalx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtfjynyklx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcpwsgxw.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gthxhrpvgd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtqafhwojd.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtapjhxuwg.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtnfkydwbk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtyvfyxmke.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtzmhfraic.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxfpmolm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtjjkcngif.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtrjeybabi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtbucwxqlc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtylojajjd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtxnwprcbz.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtxnbmmzaz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtzfsliqmt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtwwelihmn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtlpyxmdsp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtdvlmntsr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtkocjcxqu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtaovznjes.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gthpcbirhl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtqdvfakdg.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtqsdmrdlp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtgyssrnhk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtmbliukka.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtnvzffygv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtowigqfnu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtsmhneetm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtwqvbespp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtoyxuvvzs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtokkrgtun.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtzxyzcrvg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbckeoez.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtgnhhcxmw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtnzpcyuvy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtttoibaus.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gtgtvaskeh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtklhmyamc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtzsvilvln.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtfupdlilk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpeyoesjj.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gteqlfhymb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmvtsmzz.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtbvtkahzw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtonmskmtx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtrikvzown.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbnthxtbs.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtstcpeiak.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtyyonszkp.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtchqhndda.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtoxyzrjrc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gttnysonwt.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtghussbjz.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtijhpprth.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gthtpycfve.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtnpdggcot.html


<!-- 参考信息 -->