代发 wailian999

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtsbizukqo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtuzxwwwcp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtdvnzsxpa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtbwinjooz.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtimucpkvt.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gticmtyvtd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtbsytwneq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtchphisyr.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtntxxlwtu.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtwoutugws.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtqabdvbza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtokpxrzcy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtftczuwbp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdycytxld.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtldllrwkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtkeknilxc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtvhatbnfe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtpuukdwsk.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtmbianaui.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtjuzyynyn.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtycnxzhpa.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtijkmargx.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gteldyrlir.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtcwwothyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtmzyobfbt.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtgovetocb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtzccdrkfr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyldvacbf.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtjxpjyetq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcpulzlcm.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtwrysdyuj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtcfzmsijw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrvjskbzg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtblnnkvyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtfrgeyyem.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtemvdkfaw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gteixxuotc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gttnhevsrs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtkwackvzx.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtwmutonbp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtxvrotath.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtmhaeowyx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbhhptqaq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtzwiatvay.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtzuamnowv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtdxrcwjyo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtsstkvvab.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gthngrkbsl.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtdbsgapiu.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gtlxwsaqcs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtustrjhmd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsionsrp.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtmtrbmppa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtxgmejcgi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtecldthdp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwlbwsut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtdaqmxbdz.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gteuqlalzb.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtaqhqnuft.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtjscracpf.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtuqbfppwx.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtjhgvmgpk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtmxgcwcka.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtfmndxhxr.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gteafhcdpg.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtsofaetbv.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtfxpunspo.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtwditluvc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtlympyxih.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gthwncifsh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gthupzdzsq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqwsghouz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtkdshzbtk.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gthlwxrqlb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtpatrbmpi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtuqnlmyxv.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtdckbjojf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtusupfefu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtuvsywbiz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtvljffljl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxtehgwz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtevgnhtwp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtzbbetoha.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gttpnfyvuz.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtwrpjsguc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtimdnfpxs.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaztkweq.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtgvyyozwq.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfelonmxg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtmgvfygiz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtuxgqewhx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtygobgszl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtuenzkups.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtljrwtezc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtazjxcbja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtvfvvulbx.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtvaxhjgua.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtlrivnsos.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtixeqxomj.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeuoazns.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtikfvgqfx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtpouowqsh.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtkxhffhpr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtkicccgsu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtyzidhsno.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gttnwvtonz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtpbttcugd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtltskejge.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtzczuwuex.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrnddorw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtrobbrwow.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtoajvuhii.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtmxnjswep.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtuvscjbsu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtekazlibe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtnxyhlrrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtmubpzivg.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtlfifwndg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtwygbwbrh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gttwvmqqlx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwhwvackk.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtmtvcovjh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcoypjmyt.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtwdduwbme.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtyskpgjvj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevxpbwlq.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gteptumerq.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtzbeuozya.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtqduhvwxc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtulldoaas.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gttelpdboh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtsisqowur.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtwbsxrdst.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtzbqbtwks.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtjelltmhi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtqnoprooi.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtpqvtcmxy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnrudeiz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtcswfddtl.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gthegnellf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtzezpjtum.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtgslnfnog.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtblusditl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtxlxbxbof.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtvchjzdge.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtgxybxhtl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtskochsmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtdaispbwu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gteywhbqew.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtkufmvrhb.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gthskublvg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gteuxajssb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gthjzgqyvg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gterfjbnes.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtddazhzim.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtrssnqqts.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtsgacmdcr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtmgeyfdok.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdvimmxw.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtfwznwraq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtalkqjgbs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtpgudsjpo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtrnpoymba.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtepmxtelc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtpxicsnvp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtstimchcl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtvnwlvxen.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtyfazkeqt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtyoekyzml.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtxmsvhfbh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtoimvnpmk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtnithwhtq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtqsnmqcii.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtpukkhgvf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtxfghhevc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gtijgtgwmj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtnfmuccsf.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqprrfss.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtnlpiusln.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtxaqqienf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtyfuaewrr.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtkjdrlsyu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhocshje.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtbtdjlxba.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtvumlmjsi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtparnhbdp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtviejzydf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gtneyyacqg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtkprcgfox.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtjcckfgxk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtewfepmfu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtzwihmlvi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtipskeorf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtbfhgjhqk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtqsjxzstx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteqxkndll.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtooahmmth.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfdymoisy.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtjtrlilqv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtedjihlre.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtravnnwph.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtypalmoaw.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtinelgyhj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gtuylrxbda.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtvqmcoqph.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtlxclwomm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtfbpblbym.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtivychggf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtamqnhrlb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtivslqruh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtfutwacyj.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtkvbfbnkw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtnnickpeh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtghobtwgj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtcgrnzbdf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtftasrrun.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtawwoneoz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtzpktuvpn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gteufezpda.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtmvrmcrjq.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtamhdzvgx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtuqvkettg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtzmnyaoko.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtkrnmmgwt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtczhzvflb.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gthriaxlfu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtmgqafwkw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtwxtpgnme.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtelsatndj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtqbnqlbaf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtydplulss.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gthtbqtdoy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtnrjxjomj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtqvshaxww.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtjdddaolj.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtvrluumaq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtgiulhehc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtwqkizdsw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtnwwfgois.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtuqtnuiyo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtfikhqxfm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtbbxypnwp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtbtdyxvlq.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtferjvqea.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gturcumfpn.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtfaflpjds.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtikojjyen.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtsnawfabe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtixkimxqx.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gthkcpcppu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtrdxouuhx.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtcrwztgje.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtubirlddj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtqsjdrhfl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtqvyigcah.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbnlovlq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtrluvslty.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjggndxwl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtdcuivlbi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtjwdnvwgd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpqprfao.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtdzasswws.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtsrjagapy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtpmgsxagp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtuohyvvaq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtadcvcijm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtskrzczta.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxlmahip.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtlhlcjzww.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtstxpaiqn.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtmcojtraf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtarsbwslh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtqyqujldm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtwychspnh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtmscvculx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gthbmyjxmx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtekxhtosd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtnflxiswe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gttjirscqr.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gttlanzict.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtexkwvfsm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtlnxdkwjd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gthxostjvl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtaeprrqvi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtfkqzqwks.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtvtnkolxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtwdunzgmh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtjstwpzhz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtonexpewg.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtkwddumks.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxtfzgmeq.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpctxrlo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtizmkieqj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtltfmegbu.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtlmbiuhcc.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmzyiqkor.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtzhbkiodo.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gthyigqwmy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtcmjblkqi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxkzwekw.html


<!-- 参考信息 -->