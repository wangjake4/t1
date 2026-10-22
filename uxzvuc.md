代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpcxpkei.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2kfmrhaye.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2ctzikzsk.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2dydnttwb.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2dfbffnbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2jadfijet.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2olbxciul.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjlhazz.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gt2alvlxiik.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2xnlhcips.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2injugrdq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gt2ppnrazbw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxgozdb.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2klgvnwqs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gt2wjbxdhlx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gt2qzjhnyya.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2jannmqnc.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2cvxrmgsq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gt2kthjijbq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2qfleavwn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2ixvirewp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aslqgkub.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2luravqzc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gt2ciusplbl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2sqyefdoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2rdxeyfao.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2gjzwjttj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2hargsxgy.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2pukyqvbg.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2bpsbocak.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2emksntrh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2kfheioxj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gt2nnlvnwqn.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2xhmkakxl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gt2herzhgbd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2nmdkkefw.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2zbaelcri.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hkzbhwuh.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2cuvewoxu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2gilonomc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2fhfnnhga.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2csmgvpfq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2evchmhov.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2huqybhjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gt2gwonlxzv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gt2wjkrveqc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gt2glrnzlpu.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogdwflcv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjgbdemq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qntisvrw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2lftcucvv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2oyltfvwm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2mgymrcnu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2exlkrofs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2cfypvzqr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2guknpqfh.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrnzytbi.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gt2uxyzjhgb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjpoooi.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2hdqpxert.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2stkbprbv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2adtpzqob.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2tvpfvsha.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gt2ixesrugb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2ctkcpgzo.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gt2muhnijtf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gt2iznafyvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2nyaikswa.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2uwufbydx.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2bjhakeqq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2anyywccc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2wgtszxio.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqrtwodv.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nldmvmst.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gt2quwpekkc.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gt2hnaijhiu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2nezdueyr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2cwtyjwad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrqfunnk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gt2maldeasw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2urviupqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gt2etgkqucr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2hwknvyye.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2lkcggcjl.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2leewxcvq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2dexrwqch.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2wzefvqdo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2uhpnujiu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gt2vjqldhse.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbvtdpdj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gt2nvnzbqgh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2qhcbwrxn.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gt2mykthggd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2hprubuwb.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2raylwuay.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crgbpvku.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2jgsytsqq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2dlsnccyg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gt2qmsnadzm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2eyfpymin.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2slrpqlol.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gt2hadzdpat.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gt2thvawttr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2jsxsxlzh.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otqlpwvk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2gkmwdvst.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khrslhot.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2fguidxoy.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2zjmnpjxp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gt2sjlutaet.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gt2gjnedhsd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gt2vcwkdvfd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gt2zpwjukgz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhqmocsu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gt2hcgwcpsa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2zvnrvcrg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2yrdsmxoc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gt2nrgsnxwd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2dcagytku.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2ycxibuee.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2dpxqyfqj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2ifjlfibx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2vpsktous.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2kmhlnvxo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2ihssvzmh.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gt2rdqkrmoy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thklqacy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2rmjzmkux.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yrhdneei.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gt2cpsxfnmm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mwabtlgp.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2afrbqttl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2vtrimxcs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2wbrmcayn.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2fvefqvmp.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gt2tzhxhind.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2btpvocgm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2sjambrkw.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2cmzipqcp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2dcmslybb.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gt2cabujbqg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2cwjtwkap.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2mopabhah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gt2zpkrmvji.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gt2mcjuthvj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2zbpmhbju.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhmxmldv.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcbogcui.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2ntzfieba.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2quaygjfc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gt2arxwydkw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2sshhxhxm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2etglvqko.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2auidmrwo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2yzkqdiml.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2luxxcqot.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gt2ywkxczex.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gt2tqclkobr.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2rdjtamqz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gt2jtgdvgxf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2xzsbbvka.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otpdayql.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2frmkjvhj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2unalubyv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2fwdeioru.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdlnkftn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2xrodsskp.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2uywhrcme.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2nbdhmfjp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2oixjyvat.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2znboyjjs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2kyjhkbnc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gt2miwlxhol.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiywwbd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2idstzvem.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2iumifpyw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gt2mjfvykuk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2uobuxqtw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2ukwsyyvj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2ukbyoiqt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgpojbmm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2hwoklhkz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2uezslzba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2vzvrddqq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2fgpoqjqk.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2krvibyfe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maifcffs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2rrhotehm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gt2olrcrade.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2dyrihsew.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gt2dzbzrvkw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2zgbrqrjh.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jifkfuup.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gt2ogcsxavv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gt2mujllbrj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gt2nbitmgnx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2mztnryzf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2srzodlth.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2amtayqnc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2cbbtzfyt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gt2sqaichhd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2tntgpdke.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2eyantcpr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zoocyweb.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2moqjxxjv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2qagypmus.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2tjqdmyqe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gt2nijstmtk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2clkovpmj.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2nvybmxey.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2fxdxwwud.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gt2gosmkpxa.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2uymhfsie.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gt2visjsbxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2rlslwcjg.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2bpbontvs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnoqldwu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2dhtzskrz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2jnbnpcsh.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohjguhsb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2wqpfbekr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gt2vwpdeszr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2leeqvulu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2bbzxcihx.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2avbfegdv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2txrlgifs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2rlwxknth.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2sxotszrd.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2acpwlnff.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2xmicvrkc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2lwmxhbvg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2syaakepz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gt2tsentnhc.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gt2slltzlsz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2edownbjz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gt2mdiukrfg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2fosbgamd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gt2njyvtmhl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2uvtwotpv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gt2arvrbwzv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2xadjaqzx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gt2qsodnbeu.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gt2wllkeyhj.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gt2kqinkczw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2wovoglck.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2nvegqkqe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2tbefzksu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2mhvzqpwk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gt2eqiyrvtm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2zzyvconw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2qzbavgzg.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gt2tlyuheet.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjbgqgsv.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2utxupacm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2kimxcngp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2gnntxaoh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gt2dlsmwixz.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2dimonmnf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2pccpasnf.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gt2tdqhlbkx.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gt2bqydymva.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2keuooxke.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2gqasqduf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggpvfrvq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2xaclewef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2xfzpdyjb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2fvwapvbs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2nckcnngx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2lvydnsui.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmqnffpg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcaqvygo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gt2qluioevz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsvyvygv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abkodhmk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2wsdjtcqj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2ozzgrjyt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gt2tpycapie.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gt2zjwfzbsf.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vflmvyrw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkhdeaut.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2uhzeewxh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2kmyyoczh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2svrgtkse.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gt2qimhljpt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2khemfwot.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2rxujidpq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gt2jizvfxcj.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfipraqa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggbkzcgq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgfswcuu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsmwgboz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdcuxlgb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2yaxnxqab.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gt2hcyyvxms.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2bjetlgvj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxpylqhq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2urkwkcjn.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gt2niigutrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poocyeud.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xakpvsni.html


<!-- 参考信息 -->