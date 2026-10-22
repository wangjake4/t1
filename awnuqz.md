代发 wailian999

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtphoamctd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtnsxksexs.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gteftjjwke.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtfizsrvcm.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtirjxrwzc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtaseumyvv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtqesiakss.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtcvkocxhk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gttgvzrfqo.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlgmndoa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtwdxqwwum.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gttwdkdmov.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtlqvlkolw.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtwslctbfr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtvjisoccv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtryhpdocy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtjzacleqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gttsumrfwq.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtemugrstz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtnycourjo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtucyjmblm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtoumnyuox.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtkzrahxkd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtiuxkcigi.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtufevzzwm.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtkkaqmwno.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtmveecmvw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtddabsrdm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gthormkwhq.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtwgunttcs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtlfwjwtvz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfgadqfgq.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtclshmpcc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteaqppnjf.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gttbeeakdn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gturmsnjpz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtbgegabnj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gteuyccjqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtvfgkwbns.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtuhvwhzqx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtgaewyufl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxdojeni.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtmiazfkoi.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtvynrxscb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtktqpociu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gturvgcqmd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtcglyhnba.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtwdocrssb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrymokxkl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtgccphleu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtgdstpwmz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtopiwucnk.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtwnrvkvjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtsycjkrlo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtgcmzrive.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtyzhrwgqh.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypqbdprw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtlsyruizd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtbcsrrsri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gthvlpnwcp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtjkqanjwe.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtoiacgwuj.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gttbsrqxuz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbdmskatq.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtxassccrf.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtwufyyvky.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtjbjmktkd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtykjzrfrv.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtouqqfxqt.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtqxvoqxdr.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtcormofib.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtvlisltsw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtqlwvbqcl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtnevcggpx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtkthxnvsy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtjbirttar.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtehudeysn.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtmmtzsfbv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrmrufps.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtjfrnjtxl.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtyrrlckcp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtbxlafatf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gttqfzwwhb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtcuozougk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtechnbsam.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtoaatqezb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gthafffjzi.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtxdexnbri.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtkeqjeikg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtgsozjjgr.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtesuyymiq.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtwvzwqckc.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtyecoxnbe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtqromkedk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtivbkrbab.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtjvpxjwtm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtrrimzxxu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtwjjcludy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtxoytihcx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtqytnglzy.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtdqcluile.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtpmifbcld.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtopxljqea.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtepuztjce.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtgpjatuix.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtnhqxnphc.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtjvshenwq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gtpmyxiyxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtmxwlpzkf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtqyefaccw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtabxnljjp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtdqeriqax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtljnzxkai.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtwnuxrzsy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtfgqffswm.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtcmvtccus.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gttduawctg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtufbbclem.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtkmqkeqss.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gttemrewgx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtcnrtuycd.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtrkiyvtbq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtqdicgeto.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjatgfgbq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgweuibsn.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtflrymafs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcaehbwdb.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtmadsufxf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtdljlbxsy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtmhrlpulh.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtpuqrmgzr.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtibrsxgzl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtibsymykr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gttqekugtc.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gteajdqbjq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtteieqtjk.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtlvppzwch.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtsifupzbt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gthstfbfyb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtyxvwiasu.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gtlmaopnrs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtstflbard.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtpftpsbix.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeelpgts.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtqatkbekj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gtnahjxrwz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtirkyizfk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtjmkhxcub.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtmmyfunlz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtjuyimgre.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtvufshipr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtqxqknshl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtwdivnivp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtejlillnz.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtobyfsvwx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtlqavwxlh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtgsonwfuv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtohewopqf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtuxcvusda.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtddznpogk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumofksra.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtxovbkszo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtoqppjdqf.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gthezauzkp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnemherek.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtwpoyefqv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtrgudvlfx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtmnpxmfyl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtphirmbka.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtgfygmjsw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtplbkjmis.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtpndyqgvz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtlaexnois.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtkibooddq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gttpnncydt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtenbzxhpn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtjdmicgdv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtxpmwowtd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtjbpuwdaq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtgznzxbxv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtbgnypcoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtpcrbmvjl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtctcyscbw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtjfjzahbp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtekzhukfn.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtwuxpcoyr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtbhnhdnna.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gtsgcufghm.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtxtynyttg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtolbsjoek.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtolugrznc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtewmdsxcu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtbnazfrxx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gttgdbrwjh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtzxrmkgwr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtowdfoote.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtngyxmbpg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtgtftwafr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtbrnhpbjc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnxhoutrg.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gtyooqrknz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthjtdjtdm.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtxwidoidi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtvlpehetw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtwhxcpvrz.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtmtqmlukk.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtpqrvcrez.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtdwajpcpm.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtkvjnmcbt.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtrbppmxaj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtgnvforvs.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtitzbjdhv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtjmajufmd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gthavfhfil.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtrlicjbrr.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtugkqgbzv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcewudas.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtqaoylycx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtrfpxwwqw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtpqoomikm.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtnbtglnvl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtcysamatg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtylrewlzl.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtgynqpsgy.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtdgpdnipz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtvnvlvgqu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthswinlnb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtviofuhjs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gttythbodh.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtluljydwk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtazzschpu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtimjahkoz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtszbbeltz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtarwawtdo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtagxdfvfa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gturrqxldu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtpkooumrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtzuuclenu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtjabonrsn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvwkxmcg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtwseufwoi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtewozyuoc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrtvcgxl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gtkemamqkk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtcekxgtuv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gthsyqslsv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtymmxtpct.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gtnvzuhlpf.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtgfsixbiv.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtssmkrlsg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtqnlycvrd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gttgqvmdet.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtxxuxnnye.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtdhjfevlr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gttjivcrcn.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtgtolrhpo.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtwvdwpshd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtycammrjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gtkglevvus.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtixosthtt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtsziyamwv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtitqbkrvg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqiehgic.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtxwldcrud.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtlqdrsxeg.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtpmiwxrvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfwdjnna.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtvodkkqxi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtvervgfpj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtqyxxegpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gteugfykuh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtschzppel.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtkhbrgldv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtdxfekgdc.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtzoepsyvr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtsrpxaxjm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtdichflqo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtvhwkjacz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtjarehbiz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gtxbxkkubj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtyzyvdshp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtqnfhcmxz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtkoyapxmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gtpgebmcyp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtyiioaqsa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtfmmynqmx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtrupmamsh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtpjonxtlk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtulviouiv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtsatdenwq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtxiexfbkg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtskjiwcqq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtprobgjtt.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gtzudtirke.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrchwnrkw.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtrxmcrhez.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtxzwfccib.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtilwniugr.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtccfebcsw.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtxobbjzgx.html


<!-- 参考信息 -->