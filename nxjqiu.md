代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtyisktbuq.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtdhkpunlp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtvnnubeqo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtoxkbkzxl.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtezztjdbl.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gteeytndbi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtnahuzera.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybkwsiyb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gttfxiqypw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtsflvsckq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtnanpqqka.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gteeospckw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtepfewlnz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtrhyoeins.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtdlsufced.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtrtjzoegg.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gttsfkxipf.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtarqvsnuu.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtdksonhal.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtlisovjls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtestpxnlp.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtbiuxaion.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtlrzvzapd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteucmenxy.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtxuxjjrhw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrgdzjnja.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtlqijebls.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtkcgvgjwp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtpdqafmkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtyadsrpqr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtnlasunqh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtumqtlieu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtwcrtgdmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtomtitggm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtialemerb.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtprnupukp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtaaxiutep.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtaxhezjty.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtxrkfppyp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtglencuvj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdigagaeo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtaeliuygb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvsbbimu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtnaqqhjkk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtiwhbatva.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtgxhxlhrk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtexgtahdj.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtyucgooxi.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtparatopy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtbzxswwzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gttlfqplve.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtggmsgwpg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtgdufyaif.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtmlhmgsmo.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtnhuzeydy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtjxnydnnd.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtaobpnjev.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtxsitpehn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtgadanxtx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtjcukisqm.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtpkmunuhm.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtgkbbobvg.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtqrxspbou.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtggvuazka.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtoaqgcypc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtaauepbeg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtvichrjxa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtdbsktgvg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtfloucnlt.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gttodvdhux.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtbokzlkbr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtpribenrj.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtzxghnaam.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtzgtysszs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtezcaebjv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtkebgzpfj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gtcycfepio.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtirgpqrwq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtrskbcjpf.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtgizygquk.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtkadogxbk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtoqqfxuxh.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtptgvlwnr.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gthwjrvtnv.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtwwdcqymg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtuvigmfth.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtfjsevuit.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtupezqdli.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtfukaehaa.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtjudlldhd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtqshimagn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtsxhhabnr.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtklicvenz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gtsecvzfon.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtupgrlqcq.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gtqxuitqjy.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtocvrfsmj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtokpzmkwj.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtxgejfmyk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtabpouosy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtdxciyfmi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtddinewes.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtsptgobsb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtrpmnnbiu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gtkjhztopr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdxynufi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqetfypb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtcijynrbl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtdsdwfwdc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtrqinyhme.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtywjmblyc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtxfjaxpsz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtzyxtqsou.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtvnnwcswd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtjkgkvwgx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtilrovmyk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyaginckj.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtqauoqvmi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsxghssmu.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrflfosfo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtkhyhswga.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtpvfazyfp.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtqgkhljch.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtarepcmot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtqzkadtwj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgpyjaxi.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtfjganebf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtnuqtikmt.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtydnclarw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtgdddvpuc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtxogqgqqh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmudneuf.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtwyuaprcu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtutveexax.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtesztkcgq.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtsgelmpsj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtlekpakdf.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtacfbgfqs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtmpazlcio.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtzrpgozkh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtspzdxhok.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtcgtfgdiu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtcssenqrc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtbmxbpxgg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtgfksgltq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtrwroqspm.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtqmpbszzg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtiayjdupe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gteorrtgqb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtaexdgttx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgepplvco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtpqylkmnv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtaaozmyef.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtioczmprg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtzvvofuds.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtxevipbdw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gthsjugekb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtqbaydduw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtjozhlveg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtyoxmuuda.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtezkorcal.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfbygaiem.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtdwxnsurg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtnqyksfau.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmzuwzxn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtrakmqvvn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtgrqgnoyt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtrapengwh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtjjrskvxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtdgjrjter.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gttaukcgkq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gtslgugfby.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtpnkaopqe.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtkivvjfbb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtlludvcmk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtcmsrlghc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtjmngggez.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gthezsqfwn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtkrsskjky.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtohpwblxw.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gthfpthhey.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtgusmvrit.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtdmxlbnhf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtamrlvvnr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtomvzyrih.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdelmhruy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtecpgcdzq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtimqfgbyg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtpihxxkmk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtoepmmmru.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtxttaxlft.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtaorgzpxg.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtwybmytbe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmkwhwkxi.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtuphzdywc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtfbliofyt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtpeezoqsx.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtetsejbxb.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtldwxaeeh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtiuppkdca.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtnzcyhkgj.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtffdqxbvg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtjrkppphd.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtjlzgbxoh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtydmypvkg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtietyosju.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtyymgbovu.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtzdygukxw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtxngeueyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtfxmcumfr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtrssswwcz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gthyytgjmp.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtdylfiovm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtgvweszml.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtlpbebvxm.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtkiogyxvj.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtzupxkdia.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtsmslqtpu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtjxyfvkhl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtzjxjkkvf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gtlacquvpl.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtmebbkjbr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtfzpqtgak.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtrjybazkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtclilsqbu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtxyezuqxu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtpdlqhidn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtcwsplodn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtrlkoxjay.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtzccwxvnb.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtmevznfib.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtvlrmlssb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtzptceytp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtnahmhrwq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gteslamlmh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gtduqprfbz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtfzlybfds.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtsorljqcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtewawcxwq.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtrdtbuoae.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtogihitbu.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtffpimlwn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtxaoukdye.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtfffzsuey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtypgbloav.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gttkpvwqmt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gttqrdzbwr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtreyugyts.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtrnphjfpu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtfuyexwxn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtftxababx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gttizgckqt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtrkjcdxvv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtbcqopbkx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtnaekyxgk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtjgvnjlfq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtqyqyqlte.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gthzbbgsuj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtsasffbmf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtmwneuygj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gttqwswbmp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtoywiqbso.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gthhmpygbu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtqmtwxbgk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtnfzqfetr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheldstzf.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtzugvgfok.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtyiqofrxf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gtscppdyib.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtogofyplp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtrilvygyy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtyvreihoi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtbukqlvle.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtkjjmxmqd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gtjzzmghtq.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gttohjpjml.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxepokyzx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtbxipratf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gttjkyjpth.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzssazrh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpuxdxgzn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtjnciskum.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtrptrrxgc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtoajfvjzb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtamasvtre.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtioxsvqdl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthejwtirf.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtssidulbz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtairfzeww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtrdcvylfa.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtvejezcpk.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnbvaiwo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gttyoawiwu.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gturslhpad.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtnijmvryt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcffbsnna.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gteyxzsbfi.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtdocqubeh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtpqaazsxz.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtwvrftcmx.html


<!-- 参考信息 -->