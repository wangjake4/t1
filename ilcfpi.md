代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2owegsodg.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2zewnjids.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsryldua.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gt2knjimdih.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gt2uovpvvnw.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2cpwxyzov.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2yjlyrunn.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2ombzzdxu.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2ysvxazyr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipmdroob.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2lxshuifm.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gt2xcnbxipu.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gt2ysnfvpra.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2ucwxbhew.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkrseexx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2wlcmeyga.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2vjltrlkt.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gt2tceqesin.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybxcblhw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gt2bntoakyg.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gt2crhfleqw.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkxshglz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2escyfhfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gt2svwesiqc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2bwylpexj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2kcqgjkfr.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2asvjqrwh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2sqgyodmi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2qdcfgryn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2oinsrtlt.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gt2xyudkrpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gt2tceohvuf.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2mpnzxmbn.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2jptlrari.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2sobireou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2rpeusnhw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gt2fgkvgspx.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2sjpzdfxa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2svjyiekz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jybtytoy.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2crrpsqvg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bntjltgw.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2cuazspjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2sosizped.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2gkjftsoq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2laumnbup.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2buhklpom.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2aceipmdg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gt2vwdipjvl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gt2xaxqvsyz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2lohswtfh.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvtvkbaf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhtnvise.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2dzdblctj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2whtnezcq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2olwbtnfm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpdpahcs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2bcfbcptz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxfcbpfv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lriayuaj.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2rbcuxnva.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuhaskv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2msksyfrg.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2wpurkipk.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2qruwcpwv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2esfmnaav.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2rqrzwqhb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2hwokwacu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2arqykxjo.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gt2cqjpzsex.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2tffcoreh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2cwrejwun.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lokjazie.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2umdcyfls.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2iljaqawh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2horhkwah.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxvznryu.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2xcgyugzf.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gt2hkdahlmb.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gt2krvcmtga.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gt2wjbglomg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2ihpgyfij.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2zvporpcc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2ksqxlssh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2vdtaavhz.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwfaeqwl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2mzestfiu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2hurzlkyp.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gt2esctcpzi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2crkgtgzs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2ckfdydbo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2itovuuim.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gt2aoliltxm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2bmfatpxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyheoapi.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gt2ihknfdsa.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gt2ddjaprnc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuyhfthb.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2fkskkddt.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2yyvyfnhb.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2ltcsqakp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gt2vlzxviql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gt2bsqvzztr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2tryvsqsi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2ebhnecmt.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2acgakegk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gt2tsketzbv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2pxoiozqm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mecrajrx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2pzacixpf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2ehyivsqs.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gt2guhmkfpt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gt2inztyrkz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujxalnoj.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2fflbfapw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2cxknmerq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2naugjesg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gt2dehzllnn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2gjltiycs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gt2udlpowdu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2rcsfjtyw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gt2ekmlvdwf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2ozsmswuv.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gt2xnfwtevu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yklmoept.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2pksjfwwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2zayzrvuw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2xhuikzlq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2tedxojtr.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2yrfzjzhp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gt2essymswo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2qjtqmozn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmqjgdqh.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gt2cwsaidaa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2cskoetsy.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2ikvnuumw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2adoctdzd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2ppyvqsne.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2eipjzxww.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2zezxosoj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gt2lfjrngva.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gt2yztpyqzl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2pmhiaffc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2lzyzlelu.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gt2nzvuuclr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2ulyoihyq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2zwedmmip.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gt2nbukjivt.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2qqcwlniy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gt2qifodrww.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2verlhmjv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2wpbxqpwz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2iishxkre.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2xxjhqiof.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gt2brvhdfqs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2wtbybpzb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2clxkbiys.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcovyeod.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjcybued.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gt2sykqdmpc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2vekqdddl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlwdqcpr.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmiakhwm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2uzxovuhv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2amsbuiqc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbrtvgcj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2dhvqhzct.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2wfkzxxqq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2bngxytqe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2nfnfwmoi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2drllnedu.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snhhrdbt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2bipjmruh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2facgpqyi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2jwfyxedo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2jgmkeags.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2eqqnnves.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2myroiaig.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2gqodfhlx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2ejwiwrpz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwbjozge.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2elrhcifh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gt2vmztaegs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2vlpgkoma.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2caybxaam.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2emathfhi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gt2hbrdzomw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2ninttkoi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyjrhyxl.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2ofbttefo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2fvycgskz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2zxytugeh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2kpjidgba.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdbtqsgo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2xhtwvmyf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2bbcrvmju.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2biajcyvl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2rxfddpei.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2usyfdsij.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2bfssctef.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2eknrnwer.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2fsrjmthh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2lqqdscmh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2qterxeqm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gt2rehcqtrs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gt2tytnsuik.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdipmvpf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2kujiaoyy.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2sgmulomy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jgqbxrkr.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gt2gtkydjxa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2qvjhyogr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2vsyzxpgl.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2lxemztqq.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2xsyurrbl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gt2jxddinbd.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gt2lovtuwxd.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2fgwoftlx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gt2ljxjgfrc.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hygesopj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2wmokivux.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2sbmkizza.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxjxqbxq.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2qjcifbxu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gt2dldrqjsf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2nivwrafe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2ktsifayu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gt2sunciprx.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2exhjfixs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2xpkvrynl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gt2cygtvekn.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2kcwlvnru.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2smkwqgrc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hizyrxjb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2zrdbtofz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2qbpwnvuq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gt2npahxamm.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2wcempoqg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2abgzjghp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2iqjtodxg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2lgdmwmhd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2brjqcwky.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2cachumql.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gt2byvjsdzw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2qrsnukgu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2tvskyxaj.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gt2mkmlldrj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2bdjxwyaa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2maefzbmg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2dehlaolo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2miocktrq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2nlouxbfo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2qgmewjoz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2vppaqinp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2cvnccyen.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2mugboqiw.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrfgirwe.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2ngifzerq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2pkcxrtea.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2xgfflupf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2slavndbo.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2dchphvlz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gt2ttksqluu.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2pidkxrtj.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2ghaidiei.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2pisqlosn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2gqrjftlz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2jsujzqfn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2gmipxgyv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2rcwqqnll.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gt2dvqgtsgl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2rcuwtvak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulqdoaki.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gt2atzhezpx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2xpomfuwq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2tqjkabsu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2onolyoen.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gt2jjlvwjaf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2qwdiitlr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2gzydhwxr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gt2raohopvi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gt2zmisvkqg.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2fssdlxpj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2owaiylnh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gt2uuyxbvii.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2vbyedpwz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2vlnegill.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2rexzqpwq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2vntifqsy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2mnicksno.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jouzuzsy.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2tdtxbdwv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2buzudqao.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2djhokqxk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2gfnfdmof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpuwecxd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2xbrbmrys.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2wujueryb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2cdvvxbeb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gt2fayrclvq.html


<!-- 参考信息 -->