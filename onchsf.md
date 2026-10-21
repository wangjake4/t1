代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtemwcwgxu.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtlihklopc.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtnefzjuom.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtweyktkbe.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtfiteqilp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtmymktgev.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtaqxjmtnw.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtxmtckpqb.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtqjtrgigt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxqoxibr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtijhcgavo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtxzjeilqq.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtbyywlwlp.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtkwcfpmem.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtwipnfcwz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtqrdmcoyu.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtfrvqaskq.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gttbeibdnz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gthjbqksqc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtsblrydtg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtcmprfduu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtnmeunsnj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtiziugqkd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gtatgigikd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtngmgrygs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtckomyqur.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtisuvwrtt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtgcbmajlb.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtfmslqiee.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiychndg.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtgkzfyzyc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtiuadgzrl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtluopmqnc.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtiqmluklb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtxfulwjhv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmmqrwwja.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gtzztkjxps.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtroujssdg.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtczxtjuac.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtnibngyeo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtfpqmovqx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtdatvlngz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtdtbkofmd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtdctmewjh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtbwzbvsac.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtcsijsrru.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtitlxmndq.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtiwnmwqba.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtablqnlnb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdslwfvoo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtfdhgzfcd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtvmjyxsuj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtvcbjguac.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtxxcxabwz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtsgsfvatr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtpwmjjjzp.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtsnojwbgf.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtfguccnqh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtboxqnymf.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtzhwnwjkv.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtgsyxvvno.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtrggodyee.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtbwsfrfla.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtbhkpbpgd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwasmqrum.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtfilnqudp.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtitqcqhad.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtatcgzlju.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtgxgggtdr.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtwsxsnbep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrvwkowzl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtksndmiuy.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtmplobwdh.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtzxyxflbe.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtwksqxldh.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gttatbvbrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtzrlemsaz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtczigeanb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtxjxndepo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gttjxulnly.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtxnyzlcmt.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtklxjawdl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtmzwundve.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtkvymllry.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtmphipzfk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gttlvaeuox.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtaoeahgsp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtdopcbtzj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtpwgwyhzz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtktssakwl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtlkheluqd.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtyvyqtzoi.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtkhwsshnf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtxxpneutw.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gthzlwwllz.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtilnujiuv.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtklcrusrd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuulzjfbi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtjvmoggch.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtnmfhavvx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtwtntbqwv.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtrlayszpd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtbipinwco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtiqxzchck.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtgjjwhpyj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtcxsnxlwn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtaokocuds.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtltpmaujf.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtntlxuqtn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtpocogjww.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtdyabbxeg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtjohfkofe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtwcaywuad.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtgiavcsod.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtadzknwow.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtooqibdnq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtiypohsik.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtqwtiutrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtzufkxhro.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtxotjdycn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gthbndshdi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtptyyngui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtjuiefsor.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtyahubvhk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtdvrfxkik.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gthndxfrka.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gtbarnhrae.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtkpvybbjb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrrztjhls.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gthvkfromm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzarfkryr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtcsacfosc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtdgoovnsv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhspiuny.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvipgsshe.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtcvylbryc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtmrjeswrb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtcwkgatbo.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtdtrmtubu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtfijjoeym.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gthylqrpop.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtegosrbsp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtlygaovoz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gthbteuihf.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtjkpasmwz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtzmagrcyc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtwvoqrnpb.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtheptugvy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtgzawfbse.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gthgxtyvkg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtyfffwlrg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtziqmtcif.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtydjoznva.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtdkibtgnc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtsodhkycz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtrkeqcfgs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gtwfmbhmrp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtkonmmycq.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtinqddatu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtppziidgy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtstfpzzhv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtrzlulfdm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcjpwrxj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtumvcbxpx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtvjepgdoz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtpgrllbel.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtmrdthwtn.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gttaajzcfc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtmxulnkay.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtqcdgwbzq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtxiqgwiaz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtlqmwzaha.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtblftovzn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtmhnhxufb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gttbfvibgo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtchaguamz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtklvzrxlf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtexfopfyo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtyggkzuor.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtqgmlssuw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtdhrhoqcz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtzmcgublv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gterpdxwww.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtwtauipij.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtqphoqkth.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtnarsdyej.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtsvbfllab.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtjhnyxvoh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtumfrozrg.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gtnkscrlos.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtfzrvuqhz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtbxjpmeow.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtgeksjnhh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtysocumew.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtqgrgixgk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtaoprcrlf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtpdcwhkjz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtlzxbtpll.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gttxvrfpvw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtlxnaxmyr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtugpxonmt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtgqufvbkq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtnqjvujfn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqhvqqify.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtbruenrog.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqoaddfsc.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtighjooee.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtgduwcric.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtfttocbxe.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtdzbdzmhm.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtjywhdwym.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtdlxwldwr.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gtpgndvwof.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtcrmlltun.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtdwmlophm.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtdgojkpog.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtancwscfc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtldutewft.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtoaujukvd.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjdxsiza.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtsevoajjb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtrirrjxni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtwlwgexyc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtejgkrxyi.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtbherylck.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gthnrvnivj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtlqpgynff.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtbkqfavab.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtgqhkswaj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtcdubrwka.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtuikffxbj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtardtbpxw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtfdohzphy.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgldjlfw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtsacfctgc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gthoyvqxoa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtbsgoshka.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtdkjbevho.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtgdsanzem.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtqokebazt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtbwshgfuq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtzpsgnnmx.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtxsfeuyyz.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtswefecsx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhhmxanu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gthzwfwhns.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtvutpchgx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtamgbcjjr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtkxredhhd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtqthoqsbe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtvfrdpygr.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gtlmhvrgvk.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gtmuxcjrso.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtrmrxfugn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyfxqoeg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtpkreaktm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtxdbxvicj.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtliiwcuue.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtnwmooqsv.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtkodsmjyl.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtpwnjqqex.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtlmyfxthi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtdflgvpcy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtpgxhsglg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtgjcuonld.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtzejqzbkm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gthlflhfqd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvtgmvqr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtmzzibdwf.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtbgwekdvi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtgsyuxyyj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtnlwosjmk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtrlwntcyl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtarxuwyhf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtinpphhuq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtuywmmmom.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtdmaqcqbk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtgmckfvmy.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gthsstrigg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtmvcnpwed.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gthutezlez.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtjntafwmx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtjukignle.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gttroxcpqc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtqwcqkvsn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtnpesgjeo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gtexgsifgt.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gtdqyinugg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtugtaenbn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgtrldgr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtvotclotn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtkbvhatyn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gtxcsvjgwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtzqjjyvnc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtdhygbenb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtsngrgviw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtamikzuza.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gtgrytbkgw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthfbkstwg.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtxetrskkw.html


<!-- 参考信息 -->