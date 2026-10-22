代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gt2eelkvcmi.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2nrxynctz.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhnrlqkh.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2momqarnm.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2ysvnecpa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2xwyvjvsv.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2hqpjckho.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2txcwsmoa.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2mbdgeajf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gt2gfmdqtqm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2vnpwxngw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2hebvhqdo.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2fsubxfmu.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2vnilippx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gt2oblxswbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gt2jkvtuvzp.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gt2ekxofsoi.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gt2oqxyrers.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2xxcotqdr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2dccwpuob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gt2erraqrta.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2qhfcvopw.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2trbucsrg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gt2abcavgls.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2xmljmgmc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2iorjdmoo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvcgpxd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2oibdgubh.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gt2fjctwaov.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2iwsqrhof.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2kbbtgvaa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2qwhemyqd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2bvmzyprq.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnkpyvvo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqxjtoli.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cesdgosb.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2xlibjjud.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2kutilvnj.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2gimcvdcd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gt2dxahpnyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2soucepju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2kwfumkkb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2rkfdyjyd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2owrptbgv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2tjfwxrii.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gt2glihrhfp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gt2ueeujjhe.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rugzblwf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gt2ubxgnqrr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2sngicxnf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2xrqgmdhd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2woebfbcp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ogbhiulx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2iqyqehde.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gt2riekznvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2oydhqujc.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2btrzlffx.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2sicllbxl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2dbkkeqfo.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2mvvmzjmv.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2wixmbtvp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2pnykmrut.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2xnrzixrz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rauwsded.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2rabbcgrd.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gt2swixjnef.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gt2ynvjtzkq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qkobylpr.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2viryqqzz.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2qsrqmdqq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftzgippr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2veclmzuk.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2tbbmzebf.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2qxuwnorm.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2mihfzkjn.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gt2fieqfddj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2maikavbs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2snmcglcv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2juvxfmwx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gt2itntaoad.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2sdamafda.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2fbmxvmpc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2gzjhqblv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gt2pelarizg.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2eluktqtv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2bngikzjo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nldrojqc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2xcpjaifc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gt2bigrpljq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2qibeqivo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iozqegjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubeooydn.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tokaftsz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2fwjukjmf.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2qwabzags.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2wsvjybez.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2fdvstfjl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gt2yhdywdxt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gt2gbnmxvgt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gt2dazideuc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2zrdqnxxl.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2elouyash.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2dulvazqj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2ielrmqnk.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2tfalnbgv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2cgsrwjth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2rpenfjry.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2zhvezovn.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gt2oepmjtrm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gt2rzknpzbq.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2almmtifs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hivaedsg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2oaljduov.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2zbqmitko.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2wtmyvscf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2yggmslcb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcjxyenn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gt2ajynluzw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2sdtwpihd.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2klruptha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gt2obdnvdah.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2osvbyhha.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2omjnkhky.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2ftbxgxsm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gt2exdapwnl.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gt2esozylce.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2zwiycqss.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2megappnx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2abwkpcxj.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2oqreixvb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2eshpsdfo.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2fvengvti.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2bcexfpce.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2lisldsij.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2dnkwbhsj.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2uaiwxjfv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2dqwnohky.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2sujlzdec.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2pweoemsf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2qwoydhiy.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gt2rvcfwudz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2dyjmbjev.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfwnbpbq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2wfrxjhcc.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2kkszesow.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2htkpqkvf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2guoyvelh.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2racahsdn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2iofzvngi.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2trsrmzmh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gt2osjczhve.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gt2oagyursg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2dnpgsifz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftrovnls.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2xztvdzno.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gt2cqoadzki.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocaifiqj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2wkmfdyvt.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2wsqutslr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrdxmkcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2uwngdfnk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2ltqghdhx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2vgmznjzf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2hfgkkxqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2cyasaslq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2mfushxjx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2gidbqzob.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gt2wtbglwii.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gt2aajudntn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2irloxdea.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2lwmfvipv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2fwfecyol.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2rrpofhcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2avkadujy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2pncwuaay.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gt2freilsen.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2llpyygsh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2ucaxikzb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gt2eezlymfi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2wsrlvtpc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2lagtdzci.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2bjxmnpva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbthvazd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gt2efiggurr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2ngsmrzpf.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2woyflajs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2zohdtjxt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2xessraod.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgpgaah.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2vdhavbin.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gt2kdfcgquy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2ousdjosl.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2hxtblpeq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2xykyoonf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gt2cdllkzqg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gt2tgwsioao.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2zpwrncly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2ybhibqvq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2lvzanivb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2mmhrvcvc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2wpgqdvdr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2geszrmbh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddyktevn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jlmsktpm.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2agipwjtc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ugixfjst.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2ptetceux.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2culozoip.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwztlloc.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2rdykjspb.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2ycgqfher.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gt2iqdqixxd.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gt2guialraq.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gt2dccfewnb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gt2kcqzdzli.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2xqbkdggl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2sgtzeqcw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2pwcnaaqt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gt2roikwgzd.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2andqauaw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2hgalfkdh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2iixvbywx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2btrnbaej.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqhsidph.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gt2bpvmxmrk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2xtuurxnh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2cftxxfqr.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2npyolsai.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2zasgksuc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2trffngzi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdfypvel.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2tsercorh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2gndgacpm.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2facbssxm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gt2xxytbwuq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsquutmj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2drbeiuuq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gt2wmabwswt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2iinsdhqg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2dmaqjvlr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2jqupsinp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2ynbzrikw.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bimcjjkd.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2jerrblge.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gt2pwufvzyx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2gbpnchmc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2gnbmufvn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2twsfpowi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2pcwynkrh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2unhmtqqi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2sqycqqgr.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2tinjdrpx.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gt2pogddkrm.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2sifmzskn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2ujrhizbn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbzoggtu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2fllyggdr.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2jtllpqnt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2swvbzvwr.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2qproazxu.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gt2vzbhcmdc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2jhybswqf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xihlrpib.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugvfckad.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2qvevgdef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2ldgrjydr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gt2prqcwhym.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2samejxyk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2jzzjcomt.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpgnrrem.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xiobfyuq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gt2ofrxaatp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2awkkymbo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eoysxibb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gt2zzfelcxh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2bhswuphy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2nrlynihk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gt2utogumka.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtuhrsem.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2phcsdlwx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2svijxabi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2akntcjjx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2nswtsxym.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gt2bdmgfovt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gt2zneosdce.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gt2ixasbobt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2mhtuakdn.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2aywlvxvp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gt2zjhjkanf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gt2baowwhob.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2srugmmwr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2xqqwoylh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2usiaqzbx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2sqreugyv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gt2klvbcnco.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2xtpshlnx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dtidpkjj.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2gwoycvfx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ntizzjfk.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gt2glthlhju.html


<!-- 参考信息 -->