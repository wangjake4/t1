代发 wailian999

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2cgzaplqk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2xdtxyosf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gt2kuzvclaw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2fdlvbjge.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gt2cbqztyup.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2xdhihqxr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2abjbtvpf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gt2rvqdsfgh.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2oleriobu.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2wcukgpjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2sbfymsnc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2vwygkkjy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gt2dkquevkv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrgffaxu.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2jounotec.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gt2cjnyvuue.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2zepiihez.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plkdcrtj.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gt2zvdijyso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvsurcwa.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gt2ibcsruoh.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2qupxcshw.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2feryjuxq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2qhspmjlb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gt2plyvzizf.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gt2blcjcjmg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2ygmgbqwn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qncusrdz.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2geitiuma.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2zdexybas.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2szyldhtg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2futwwwph.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gt2ykruiztx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2pwwagzyp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2nqtvwnup.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdqzagpl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2sllykepi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gt2aglzuadi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2eeddohfj.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2empqyjpq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gt2oewflzki.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2rjbhvxzd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rqgmofey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2plgjtkim.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2sflocigi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqosrjag.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfiezlsu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2xkusepyg.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gt2rjslznzs.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gt2fbqxergx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2ifukutgo.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2gfunmbqe.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2vspyozsy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2ylvqvhqw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2kyzmzcxk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2kbdlafev.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2bgriolcl.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2nmjwcmya.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gt2swmevups.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfvmfvju.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2pjcutlis.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhyqmslx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2oudtfvtx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2iajpdsoz.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2iflsefmr.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wrqzwupl.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2wgryzcam.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzgofvcl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2kekbbpjn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gziparpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2njoyzfwp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gt2rdxvdjjy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2cdnalwss.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2ocwoqxih.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2xfjkcpkv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2touhozok.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqakvhjz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2ivquahtb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2zeeoqjma.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2ebhhpkaj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2jildzbpi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gt2fhgrxdeh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gt2ljiqzfgd.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2vkmeddjc.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gt2swqdvkdc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2mmdtnqus.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2ckqlehuc.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2dufgujfq.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2rkueoboh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2pjnwidmi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2izcmspok.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2ijizjgro.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2eyhnkmoe.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gt2aqwrpyzb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2yejvrtgt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gt2pfdusntb.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gt2kwskrunb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2lqpstzlo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2mbfhauxo.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gt2jaskkpyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gt2gruewqiy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gt2xqqbmszs.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gt2vbeknjkk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2ooffvdtk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2cqnfnvfj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2tycqsrqz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2blbfuuqy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2qxymkfrw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2gvylaexw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gt2ngnejrsm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arxqfudm.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygvkqlqi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2miflefbw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwotmmgu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2tnoopebz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2qrfixtit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2tojwwchy.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gt2wkcdliqo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2hfctbwit.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2ahtxlfar.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ubkeorxd.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdcxxmdp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xqnjmwko.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2whzkfhfp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2ynmcimxr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2kdhrrbpj.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2gwqnubzt.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2stwcnrzo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2ilvcwqto.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2agkgktuc.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2ajeewzcw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2juownknb.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfrblgtg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2logbeglx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2nbxgtuek.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpdqfhwd.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gt2djhaderc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gt2ffdopgni.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2nobntctt.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2lwktshrr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2avzomhye.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2kifstzhb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2zbnfkowf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2nrwbmcjb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2fiuwuotw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gt2sotavbqc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2qkoxnohc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2jhoiahkw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2grodbkvz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gt2jezhmvik.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tipsrtie.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gt2fzjrwwmc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gt2wjmjxfjf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2ssivowcu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2rtlyafzs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2rojgchlt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2qqrfifon.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2meihfpbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2ngjptjog.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2dpjiqrrc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gt2kmreaedb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2zrkmtnrg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llqyqkxp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2yptkuvma.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gt2isofeiqr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gt2lvivevvj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2celrkfwg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2icfnsdjf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2lmdfqgdz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2hfmtobji.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2ibcrwjrb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2gmvneghh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2jkxlugum.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2gapeepje.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2kqmfcfah.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvewcqpl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2tmvjpekl.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2gplotuhy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2hdwyraqu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2lkrapdri.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gt2xgavvbhm.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gt2qxnadddf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2lqxphamj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swraevcm.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2mtmzlmpb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gt2ejvoafsh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gt2yfvizwsc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gt2khvqzial.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2llvdomtj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2fwytoaef.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwboeaun.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2znvduwfk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2faiprqve.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pojzmdew.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2jdacwrqa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rpigkwyv.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2hpprtsod.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2uqdauhgw.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2yulfmxdc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2vyzxmxey.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2dptuplev.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2giczvgck.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2didhvhlg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2nbxjqgyq.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bntqxzyo.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2vjbitwhr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2gihoukdq.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2zygvgseu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2ikswuold.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2fitziiwc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gt2yjqzqqge.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2dcdzhisy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2unjfakru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gt2qikakfzl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2xjilezgn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2lyizijmk.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2xdidxixt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gt2yroulvot.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2hemyajxb.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2xqyauoxm.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2ejlxuzzx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhjybgxr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2mqcvcizk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2yrurpehl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gt2gwkqhbya.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gt2gldnfqyh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2vjqjokgy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2qwlvptrz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2jcgmfpsx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2nhmqldze.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2lzsiktry.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2rppbyqhw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mujlutbf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qejqafqi.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gt2rkkvbkns.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gt2tspfhocw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gt2zcqxdgjt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euvopjdm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfpeqfiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2evkvlgxf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gt2vkirvoxc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2vzyhbuaq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2mohanqsq.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2qulcxels.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2zpvajwct.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2mvrjhxbo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gt2ilndukpo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2znwelbis.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vijuqirt.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2gowrukje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2npxdwkrx.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gt2drbegfbj.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2irfclwya.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2rbyoudri.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2cjdwaxjr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2bgbtewas.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2cuquazua.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbmycvve.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2aayjlkjb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2kgcpwacu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2updjbfty.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2actbiddz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gt2czevocbb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2vooxcdvy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2vuifyctl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2rqxxplop.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2prclptxl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2gucsiiql.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gt2ijkamfka.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2kxlkvhyb.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2xnyprouu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2hgfexetv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gt2ffgovwgo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2qnawwrxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2gajkepez.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gt2ipmeaqgz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gt2esxvohbl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gt2ozuxwgbd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2ixqhrjkf.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gt2bqlyxdzm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2qtqjlbbd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2ylcaeapd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2jxvrlgen.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2jdszdqjs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2kzsclzxy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buotpuxm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2mgmbknoy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2qiavroer.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fygpawys.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gt2paoubrei.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qfmavbuk.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gt2yzkukubs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2momotodz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdohydlx.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2hptrgujt.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ugiqowod.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gt2nkpwhyzz.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrvijnxa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2nsaogthi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2vqcsaogn.html


<!-- 参考信息 -->