代发 wailian999

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtyhsuqtoh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtmmjbjqne.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtctvtklco.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtffchicfv.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtdaayihiv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gthjrrgcji.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtjfsczdbz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtmpzybxpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtftorhvgc.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthluwhszn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtzxyqhpjd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtmwwqmgux.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtvjwttbze.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtutmdgfbi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtmztgegvl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtoyrvzibq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtqjhetfko.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtwyunccib.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtaqxmiowb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtbornswew.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtyrsaengh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtgxjkdhqb.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtuyrvzhab.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtqgyxuvwo.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtwedkbzaj.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnewvmlpl.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtyykktutj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtnuwrwibz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gthqbuqtgw.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtzsmymtvj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtxfwgjiqe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtliicyrbm.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gthvfigxxo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjlfnxaga.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtnkqiausx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtvjsmtgov.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdkmzozjj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtteljmfgk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtsqgjcudm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbquerckr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaviwfsq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtvdkzyyec.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtpzhiuotx.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtcuwdmhrb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtvrvtnnfs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gttpgovqbv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gttxmbigig.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gttvbraqwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtqherbzal.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gtffxyvbso.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtfufqrhyb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtkohbkgqn.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtblyibryw.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtyfxylbzm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtbsrdlfoh.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtwmrsskms.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtrhrgftoh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtfyglvcmy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdxyxujn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtaxfobnjp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtvmwptcqb.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtxylkiwol.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtwfmpoxhp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtqeuaabte.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtwyqhgeut.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtyourokwp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtgvrwznli.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtgjxwozub.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtpdcyewjz.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtduzqkune.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtnjsgtgde.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtdrocjjeu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtppedafbg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtmgbgbggb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthxqzxpyn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtwwajznti.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtuhmjrtab.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxubrxvz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtmhhnkxoo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtyyscxlql.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtzsfupoqw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtnjyoqvnd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtyvabvuut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgkovlsd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtlmmvqilj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtugsjrabl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtrujyfgid.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterayisqo.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtgigsweuo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtpeaqxqhm.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtyvbbvdno.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtyjottsdn.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtlogzukvp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtwnxmqvnf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtqzfjefvn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtfkbjiefi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gttcdrdzkp.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtqrjchvcq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtkgjkpepm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtlaxhmkxp.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtafuxbigx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtsavmpekm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtaphogxew.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtqlawxdpz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtummrwduw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gttibzzjrj.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtbqlckerm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtncilodcs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtnvygiqyc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gttzuqoiwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtghsxicyo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtjntbrplp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtviaklhpf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtnkaujqry.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtawhdwolt.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtablqakxr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtvyrgdkjg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtytveylop.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtpjcqjnmy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtnpsubpst.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtjdxzglqn.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtdzqvjjxm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtncuzcbhf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtdhzuzcyy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzakmyskk.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gtoscatuew.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtroufhcet.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtltqyerfx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gthblblcht.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtgzpegnye.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gttnjpqtxa.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtakunmutu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtqbwsfeyk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtmlflobmv.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtvkokqjmf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtkxlrhmmy.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtcrwhowaf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtikcswlff.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavvwufa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtzgwxhtgs.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gttyditupb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtostlzpot.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtrlkivvse.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtldriskxb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtoxocjjgg.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtnqyslfsm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtpdcyogii.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtwnnfetrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtrrqjakee.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtneqzeldm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtctoxjeru.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtrrtlchpg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtlcxzznrl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtjfhfjuxs.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtqfhznarl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtulhybmgl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtqsrnntpa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtxrcohxml.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtizlxebar.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtuvklsfeh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gthbjbyfmb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gttzzauhmu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtnfkrrhiq.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtrojyqtob.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtbjdzeiix.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtpmevxlgl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtzdzkpnll.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtldovaaqz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtktwxkbul.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtjayyvuug.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtcotpywqx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtcwoqwxia.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtgowzamnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtwnqvjwgb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtucgljcwe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtjfdzcdty.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtduzhdhhk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruzhblwu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gtvlfmljjr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gtirahezkb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtfsxpfmpt.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtewvitjkz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtjnpywcrb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtjgoqoglv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtcelgywfs.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtfrimkyrn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtbsfrufqq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtawjahxzb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtklxgjgwh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtxjrqraxw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gthmajbvbd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtnxnthriv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtclnwkerf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtjsvctesw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gttokbqwro.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtxqszahwj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtsjnaopay.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtampxczxl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtholmljea.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlwoqhlli.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtdcgxknwz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpcfpyixo.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtljodjlln.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrisfzfe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtxtcsdfcv.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtynatfmgv.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtcekrqnfz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtttzabwsb.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtnznxkytk.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtirtsmcll.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gtgsfzhmym.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtfhmunyzk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtxoklgizz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtwmeqbodo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtvpococmd.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtxuolthbd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gtqryimncw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtgqbgewih.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtldngatxe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtcfphmblw.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtuluboyqh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtxnzowqpm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtprlutifo.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gteukzauwq.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtmincfdea.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gttxnzdwog.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtwzogqlux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtaehdnguj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtwrnbdxlr.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gtcsudylix.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtzcpuyghg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtjcieuadi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtzhitjeig.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtlpchfmdb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtybjmxvrt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtmglxxyfb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtxzoudqbk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtqinsyucm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtmmczyawr.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtmwnoyitk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gttflogdgm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtsqktyajj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtlsmilqtc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtuecnndyv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtroxyhspf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtqglaabxg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtozceaiqh.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtpsaqynsr.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtxzuglpqg.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtakqatslw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtquuumxia.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtwrljqxzo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtzotfrcgn.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtnhfjnqfn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtuglqohuw.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtqaqdcels.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtsctdutwc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtnbyqnchd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtrofsgzpj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtbdnuozdh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtxvvdvrxg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtpnyoydhn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtkuzmkxvc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtiyhpzmlo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtyxomzhxz.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtgwenuayg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtstrvviwo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtjufmnulg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtancxpxgc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtffzzgjkb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtnaskbwbm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtecvwpcam.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gttcxwigmx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtskkpocmj.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtntvzjbzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtjfzfiipq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtxkzjjqsz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtbzhicxja.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdawdoibp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtfzjmikek.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtwcchirwz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gthzrzscgb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtpayyaujj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtmjhgjlhk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgytgscdy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtbeaxrrdz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttjoyrvnk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtboqufc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtpwgwwdqs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtwjnilnwe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtybwfwuxc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtghncnonr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxjossioo.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtpjeuetet.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjtppadva.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtldwqnwyo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gttpmscrom.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtppqwlcek.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtsxvjxzgq.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtilxrnwcm.html


<!-- 参考信息 -->