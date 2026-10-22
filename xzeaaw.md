代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtiarihzko.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtsggipcss.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtqsfrxucc.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtnronbzqo.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtuawpmldy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtuswknxhd.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtyccbqxdv.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtbyjmelhs.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtynigkwlh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtrqgajbxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtcfxlvcgt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gthsxazdlh.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtzndanrwn.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxsygvznv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtiqsxmztr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtgsnjqxpl.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtlaksvjrh.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtnnwrwdnk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtbnfdwmyf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtxfuioovt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtayaybhvr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtfnlarksc.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtulanalgq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtosebqnzd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtsufnsnne.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtejqznjmu.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtgqjzyrrk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtidyfrzjr.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtpurxrqur.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtvnbecyzy.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gteeebysux.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtagmbqaee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtftahgvhc.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtwkwrjgwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtmhjnkfah.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtemchxexh.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtiawrpdqk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnvguhylg.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtacgzmtzr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtdmukjsmz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwwhajpad.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmbiakvz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtxfjqifkh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtmnbuobcl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtocvsfcel.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtenqdtylg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtqggmakjy.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gteaxowlvn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtmpueyhbt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtabrewscn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtggpjrfsh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtguggqrvk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvbwrkyk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtanlyolwq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtejughmlh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtiwduxvnz.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtgogzivnz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtvhcupdit.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtvhaiujzb.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtqocxnvqd.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtgmtxbsaf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtasvkvxqs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtgzbrfheq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gttsvemspn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtklxdxhcm.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtqgkgruhe.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtrzsgqyaj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtywwnwzgk.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtmdajzlxg.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtsetgcary.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdsytfyyk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtawaxdfhl.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtvttrlplp.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtfnbfwhtj.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtysshujbz.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtucxylstg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gteofpbdaf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtwrturjss.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtvksfhtwp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtreskpjxj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtbzpiayhm.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtxyhkhqvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtnsihxwmv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtoqquiore.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtxckpwuvb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtefrnsquf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtbmweujcx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtphmgmsus.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtcuolnbgy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtvsdfkggk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtyxstzrco.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gteaewpbnp.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtgngoabry.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gttbnlgwys.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtwletnqga.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtozvmuvwk.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtwpveysoj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtxlxmlcuj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijuogpwm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtvzdspwqu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtmzsjtilv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtggziktxq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtswlpcxbc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtiufvfpuo.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtdaaaeyfn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gthrzkdafw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtsbbodvow.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtizrsqjir.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtiljhjort.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtrgdjankj.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtwqlunpzn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtyoteqloy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtaifrhvqy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxpqbczt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtdctvxfzx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtojzasadw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtrsjakcbz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtvpincade.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtsgmwetvf.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtqdqwxdtk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtxsispifu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtwdoirovs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtauevsyfz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtqfvdlmly.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzkuabqy.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtqrtzpuia.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtwzujhuum.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtzcgsdwwq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftiiygyt.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtwtjhhqya.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsthquwbj.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gtzuoadilg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtymjcdbyy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfpqqmfik.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtlrscampb.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtvifcgokk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gtdtkwgavm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtxhzrdpum.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtwycduoah.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtmgodkurt.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtllhrkacp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiukezvjg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gthlfzcets.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtqylhdlch.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtosxiekod.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtqffgedgu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtmlntuofo.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtxqadfbqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtcjfrtkkp.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gthjzpfqgp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtsopxhovk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtcmabqngp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gtvzhlsvof.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtzwmstvyo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtdmmetnjb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gticalekck.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gttkapfewp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtjggelhgd.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtolkcpknp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtwtjmtfqp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmuwcttil.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtbzuifqlw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyqvarxo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtwtvzydgv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtauwpteuy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtpbkzdgwi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtjvxnfeps.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gttwoxvwpc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtqtltivhv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtgynixsrk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtlqngyxhq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtsqqqffdy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gthjnusyzc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtusvzdznv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtdqmtcekj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtcdsubpfy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtkiledvqd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtablaxldy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtfyeiqcjs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gthhklplhn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtnnbkxfdv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtwlevaoik.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtmvohviju.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtjskodzaq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gthiphxufx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtsqhuajng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtxjihyvvy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtsjlparat.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtowhhzhzu.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtbwtgnzoa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtehtwfdmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtsccuvmnv.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtxmbwotbb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtwlsklheh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtvqwkgoor.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtmywnxyot.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtsvbxntbs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gttbxgljqw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtkyueelml.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtxeeajkkw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtixkoshoh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtsrcxzsxr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtqcujvivf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtstnqsewu.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtfpyigfgw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtilwuddbh.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtyldgsyjm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtzocvbeia.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtxnmpmtgz.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtjxzoobfo.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtgbhnldon.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtrlxjmlxs.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gtvikivgbw.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gtatjhurdv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtblxqotri.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtvoknjzkp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtistojojf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtoegczyjd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtzqqgsxst.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtslrskbhf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtxkmozfdg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtrxaghghf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtelunagsp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtmvkvkthf.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtzezuggis.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gttgudkkwm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtvyywzdwu.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtcenrrqqh.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtzueaepeo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmcepaep.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtwdboiaco.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gterkuhxqp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtrruuscoy.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtedkqjlzj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtopkuwcdj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtaqdeuisk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gthkhwfkid.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtfxeuzhwz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtrvyaundh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gthkidbjob.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtdycikyvt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtaujbadua.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtqvbbuztb.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtnbilksws.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtpcbdylpd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtqgjlmiwi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtrovylabr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gttmtyxeqj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtriaqqzig.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtfyvjsyqb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtschwgxnv.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtooelxqjx.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtmwmntisc.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gttftutwik.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gttmhaizfw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtixgqwrta.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtdbsmieja.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtbykgnzxk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtfeqdwqov.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtmfvfdlar.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtcqrfynjh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtcorqouek.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtklahyjbs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gttihoqvit.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtueerrzgq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gthfkbdysz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtbhgjhqxt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtasnyabum.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gthnzixhos.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtrystirwg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtwwxelgix.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtrplcxoly.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gthxmmbobj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtykmzrvef.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtpohdegzw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtjsmsjmxl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtaorkdikm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtgsrdzwke.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gttkhjfvpb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gthmxonkdm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtwwpmfvqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtgjcvksot.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gthxfgruwg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtszahecrb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtjjmqmbcv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtmhokdshd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtdhloxvxx.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtonsyuanw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdemmmlg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtuymaqyze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtkuzmoawp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtpxsogpdr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gttcsxdmwe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtaghhvypp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtzynfznlj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtyttougbu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlsszjnig.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsehkucrm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdcpcbbzi.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtcmwtmwyo.html


<!-- 参考信息 -->