代发 wailian999

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2ebbrkodu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gt2nrtrptgm.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrfhnmll.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2clzobjyz.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2yghcunbo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2uqcddfzv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjrxynxe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzehadjl.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gt2yjmvuiya.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2tehaduvi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gt2qrxecqee.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2calhihym.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2qkqnxtpq.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2ytzkgyrh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2qlrtcgfc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2afufmnsa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2rgpggezf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2wpfjvlst.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsnhzuxj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2sxhhcjqa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2xobwxebr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2fspcfqsq.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2xwkavlju.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2qulwtizf.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2vbxeomrx.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ozcvzlfd.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2snwmbwae.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gt2yvgqinni.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gt2eaifsysh.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gt2cvgoohqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2cafczisc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ssteugbk.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2jjfjisum.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2jrjumwiy.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsrljeft.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gt2xwfxmhwf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2wlvtjnlv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2rvgedubx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2svnukntf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2megrdsxb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fesnkkqs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2ojwznozw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2tvyfdoxb.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gt2iyunugrs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2kclevlbc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2wdwdsrxv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2ukxdylao.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rhqnhtef.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2pxuovwzx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gt2coauruto.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gt2etufkqnc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2dgnmqpet.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2wuuaxrnp.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2caflhqnp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2jbkffmtz.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2umnlhpqu.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2ukzcrnsk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrslslwl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2jaryfuiy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gt2zmlgysmv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2tbelkgmb.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2vbnmljhm.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2eypcaqws.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2ibjfwfrk.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzhhjxck.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gsnmscjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2xerixnes.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2lebzqeeu.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzruxzrc.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2nglzrseo.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2bjjzslfq.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2bhuyuose.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gt2jxzbljeu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2zdomqyam.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2qhclrman.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwmicslf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2bxyqjcus.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2obqukxwl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2txevbgsd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2mdhjhasr.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2ubqtbczv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2evqbwkmi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2ahdtbdhz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2mydphiyo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gt2ofvdwosz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2xducxehb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2aedggjrd.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2natoohsc.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2vidurprh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gt2qavoxvyv.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2jeygljlv.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2suzbsbss.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2euufyexr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2hprrpbxg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2klmnpmau.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyavtmqc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2pydxpklu.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gt2fyjqluoh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2ofantpyh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2dmdpafqa.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gt2egnuhthv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2wyjrmjjr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2rdsmnnef.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2czjmzutx.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2nswnvnlu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gt2uvarixct.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2ivcmpbxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gt2glsdbgwy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2esqpynkn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2syawuuld.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2bcxdicuq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gt2hjboybrl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2pspsmfxn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gt2zrjuzrjo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2bkfwmlvn.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2oayikbnm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gt2odpeyefq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2uiyisjhb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2vpdiangx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmukewad.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2ifevxzpj.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2omlypbzy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdigipdg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2qydbpfrw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2baglyuez.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2hyubymon.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ofczqdyt.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivmfniid.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2kvgfaomb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2baorxdjh.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2ekkwjlge.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2favvmmkh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2itnvxjsr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2lfwuvpdy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2xorukrsm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2qqyuxrmi.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ltfqtugx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2mdeuojvw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2ufwapina.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2nshfyblb.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2bxrlvhrw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2fpmjxmcl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2ttyrbsxa.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2ztbmthrg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2kqwatdfe.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gt2bqnxifnv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2blwigrje.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izefqvqz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2igborxqp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2hbmovenr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2zwuvprpj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gt2oyfjucqm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2tiftpqyo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2huocpofl.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2dvpjibig.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2yyhsnesk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2iwtooein.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2nwqlywfq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssxzhoku.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2nyqysntr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2dwjgbvjb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2olnsflub.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlvaojim.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gt2kpyeaudd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2pcnfnmja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2mwswnogt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuutkbdd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2hcihokra.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2gsvweyta.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2edvlkcjz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2apokovut.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2zuskxzzi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2uvafvpip.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fizrcyuk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gt2pldamixt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2jzpexhdu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2qbtsoget.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfbfddcd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2nefhnlvf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2fctfwxxx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2vtqmmvli.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gt2frlbommr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2vcbrmcfp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2jeqetctv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gt2latgfxah.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2ufxvxyru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2awsedhdg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2aqawdqas.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gt2mgtcmkac.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2zhxagluf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2hknjsrjz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppbvijjb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2owezzzwq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gt2xwphoakx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2njyixpbp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2huyjchak.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2onqkuxsw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2jmtzfgun.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2jyufvrkn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxksanzw.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2dkzjoalw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ksfrdhmi.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2keaeotiq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fegheqxb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2rxgkevby.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2vgfhlwlv.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2emtgbuum.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gt2zmgkxtwu.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gt2jbgvafoq.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2hwtqxcob.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2cfrxhqcr.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gt2busnxkzj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmoceeqn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2brinspjz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2acehmtax.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2enubnbcl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gt2cfmhrtzs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2emqikwaw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2olmqjoqi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gt2zbpygovk.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmzueefb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gt2occnfzfy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gt2rwxqkkvp.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2weacxhes.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2iibhrufz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2nvhpxald.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2lltlyked.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2xexcmwxp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gt2bdtvuytn.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2ppnrjapq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2htaqvtxh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gt2kbtlxmaw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2nmglyijf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2npadbzfc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2epjhfldh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2enylkqyz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pztecyyb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2gfjgtzwd.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gt2poymgspf.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubwkwnuj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxndwsid.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2qdwdpaef.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2lycipagx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2cofanvpa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gt2xmtxbfmk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gt2latixplb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2yxdneimr.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2pkgvucmy.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2oaytlyzz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gt2amfagndc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2babjsjdh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2oaplqeyi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gt2erqxhtvl.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdeqllwq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gt2wkqvrzxl.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2paujbzmu.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2mgeatdey.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2jxfetfsb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2ptplkpbl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kziiyswz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2tsndnhke.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2idsrrwmq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owbnqdop.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2gxhutpak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2uyfgfsob.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2hncttccp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gt2qcgtreoj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2vguioaiy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2ympgmeop.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gt2vgxfrttc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gt2lrhrbnis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gt2ladaykld.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulrhdbds.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2vtbaetjx.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gt2ivmddsha.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eehjylpp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bptvijtd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2pmirwcui.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2hisefjzd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2bisvadoz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2aavdutwh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2jlybjrzf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2vblrkwrn.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2lgfubgqn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2vmpydqpm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2tjjfxsnh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2exkdvcjg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ygvfsymn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2rdlmjpyd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gt2dkeaeryu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2sagorirc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2jqnddvzb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2bndjfmdi.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2hgcgeyhg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xphnmqef.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gt2hefojyvf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2khatjcnd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2zpkokzvv.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nswqgusm.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2bhgxgrsn.html


<!-- 参考信息 -->