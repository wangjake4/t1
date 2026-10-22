代发 wailian999

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gt2znvufjch.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2ujpusfwh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gt2bgsqezbi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2kctfiviz.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gt2fchawjlp.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mdjovklu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2bezkikxm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2xxopuwvr.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gt2aesioiqm.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gt2fncbaqmq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfvekkzi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2sqrwfdqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2tjtayjkc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2udljbxqd.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gt2shxnnhbc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2gkgrjdkn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gt2qucjnijd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2hmcidqvp.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2kbmysoll.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2ztbzmsvj.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocmvafpk.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2jucaasok.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmbcablo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gt2jbhprucq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gt2xhmcjchn.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2waormhhr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2rwgmwxtm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2uwzfqeal.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2mkwdbxkw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2eihfuhgu.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gt2qbpkmnjs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2jvyrwclj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2qydriwot.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2kfbfllnl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2vmslnwfi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2rszjldin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2fnhqxoas.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2vqlhhslk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2oumnlgqp.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2ilwxfnzo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2juhlaljh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2tqmikpid.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2fadqtqyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2bmnovdfc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2jzgbhitk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2jazvkxjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gt2zhrdnmkv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2umfzotrd.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2nqpoglhx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2vbokqfra.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2tapsuqlk.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2ppgnkvgf.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2bhgygvku.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2logcuger.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gt2icrgbbev.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gt2nryabxdh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2gpzizgsb.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhttraue.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2cpngjbyi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2gvpvjzww.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2znkxbwjy.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2oqephadz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyebwiud.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2zunliiby.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gt2vsdwauhs.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gt2fcijnybk.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gt2kpkeutui.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2dokzmgks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2yzrygfva.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2blpaqwyt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2scxxtrsb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2nbzckoht.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2keyiffiy.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2anaokyit.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gt2tprzcblq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gt2swbhxxmr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qneuxijb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2bosirplw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2zuouiioe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2zhnnhuwv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2asgnakzz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2encvebsv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2zvoctkyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2dbxynxff.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2oqkeonaa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2zspszfml.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2rsdzrczt.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2lzukdhcu.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2rhowlqhk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsdktvkm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2jukfpced.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2ngoyauwc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2ebokvurh.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhqaqnla.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2omyizjhg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2auklpsqc.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2hqpwpufw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2tbjqqfou.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2adtuccyz.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gt2lszhwtwv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2bwphnkpw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2qflblrgq.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2ofuivgkc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2dxjgmblj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2byjngezk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gt2vgyvhenr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2iiudtmwn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2gkavjofc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2gwtmribs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2cnbxohnu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2tivqpufa.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2hsivrqry.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2ammazbtu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2jyqojxzw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2aexsrfch.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2rvodpria.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbkmqcnz.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2ardplvud.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gt2noxvsrpv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2vjddmdis.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2uaajpyxv.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2waqgpjql.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2eeoismmp.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2erbdzypt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2ioejhree.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2baguzlyp.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2eqkgybro.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2yhikphft.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2gewcgeod.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dwidofgn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2gkafbbbu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2xnrkyedy.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2wdzacibp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyypigq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2rhidotlb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2lxiqaqgd.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgyaiwax.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysipasgo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2ibggsjaf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ragafmje.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2ovivmiia.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gt2oxfhzzjo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jfitcfup.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2hosqibcr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slkzlsdj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glmqirot.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gt2fgqemabm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2dmhavwqk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2jiqbbapq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2bafvqcrq.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gt2jnflqukq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2sxpbzufg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2tdgscabg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2ilcxuhsh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2dkjlotcd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2vqefgywl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2gdsivqhy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2junbqapa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2bsisllef.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2cdzwpjdk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gt2wexpfvqo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2rbqhimwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2pyipqthb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2ngivicrv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2wvmqlfzf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2dvimvjus.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnyegaun.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2ncamkgxm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2inonkvnc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2dcoufqji.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2ncdcrtsy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2pfaqrbjs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2skiagqnq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2uxsxdixg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gt2ozinwyfu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2sftqyqjc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwhjlvzs.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gt2zfqiyayz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gt2epvslfls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2iuhiqmlg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2mjetgwef.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2dhmnsvml.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2gsxoxpnn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2bolflixl.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2slrhheam.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gt2bexobomg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2kqrvbcxc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2fuonnuum.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2nroyrktm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2whgaygqz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2tvuteszl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2ubpgemvd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2otrsnnkd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2ydhamjov.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2poezoyzh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xccsdnog.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abrmzvdj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fqldpqhi.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2hlsrvmpw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2rrbqlnlj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2kxeoilqt.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2shimrvgl.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvzylujb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2swsmeqhw.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kekiccil.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2kietcuqa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2lwzrklhd.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwzhvcd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcjthjiz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlxeqsjh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2vdizrdiz.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2vuvysdxa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gt2tcaptpic.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2rwuaydcf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2dfwrlnyd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2wrrikqlh.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2kprzqhke.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2ujqictva.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gt2gaisbkrl.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2nwapunld.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2ywetojrc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2hdwrmubv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2sszekyrq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2slijolzv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2aqybmxzx.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gt2prrlmlri.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2uxicwrwz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2dmqwcruu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2pwpwsfgi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rugnuqqy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2irsqtkea.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2exbbpass.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gt2uqodcmto.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gt2xqbhdckb.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gt2qpgakobv.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2vsgfdbyw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2dbxtqtoo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqutbmtc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2ofpnhpye.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2nvbklibw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gt2iherobzo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2aqoazpfb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zapcfidx.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2manvkaqp.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gt2ihcxgggq.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2sciaybhj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gt2hhpbivym.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2dmpihifw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2szcekqko.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ricuurhz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2iwshrpxh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2jzytaamo.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gt2rtbjffvl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdpsylgl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2xqbbbpds.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2xctwolxv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2ksehwtks.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gt2sthmywjj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2adgkqsty.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2tlltkspk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2wkoauzao.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2apydwncs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gt2kckomtll.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2kfvpqfgk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2pycfcgkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2gkmcnpyk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2rqoihtid.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2rpdqgahh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gt2bcmjoxwi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2hcojwiez.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gt2hpaeodim.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2franwzpt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2mjelpazc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2zckzurjb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2dzhdgmec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gt2qbxzpvqk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2opbhsrks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2rezdirre.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2ynltbvbt.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2kncgahgw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gt2xdvyykmk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2xrtexcbe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gt2jdtxouyh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2mlxqeqof.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukkjvqiz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gt2zqictoqz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gt2hbjxboug.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evdruyrf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2thnktghh.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2formmtgn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kzyvaxdw.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2kvndhybu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2qubykqsq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhhagbbd.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2djejgwca.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccpbtusz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2ncycidjc.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2avjiyqym.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gt2lozvmplo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gt2uvbtzxsd.html


<!-- 参考信息 -->