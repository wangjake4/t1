代发 wailian999

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtqbzgucby.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gtntdrrfvq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gteibnqthu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtloshyatc.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtfwmnahsv.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gttprqqufo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtyckeuhvr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtzzbdpwkb.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtverxecnd.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtyonhiuum.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtulaswqbw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtqjyoiker.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtieutdchz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gthtvdfqgf.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gthkfxoreq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtyktbvaye.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtovtsxbdf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtudtsfonj.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtgqqexaxh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtaeixpmbi.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtbjnwhoei.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gthppkjosa.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtkqvsihvq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtflizoggi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtlwwxwkle.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtgtjiltwb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtzowrkeki.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcuqgjrgf.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtsgckppwv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthmufzqwq.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtaxvxdexn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gttcvqjzjx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmfkubic.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtrviuanyr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtxcgyuwbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gteagqyrxq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtqaoeaazf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtafgyukpi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtpclmyekv.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtkdqssojl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtayfiescq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gteuaxutqt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gteolvhlus.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtajkzczeh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gticfkeipj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtdubroxkl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtrwimttgs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtteyejamz.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtdwgxnlaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgykzorid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtdczmjtns.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtmfzhupzj.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtcwekphos.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtcjqqvxok.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccsgszna.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjgxeewj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtjdcnpotx.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtlgbjinvd.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtxvxxutlc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtbxbstjxq.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtphomdtkj.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtqekctljg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthonuppzu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkzjjzqe.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtxbzgzmmy.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtqdskzdha.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtzesykupp.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtbzazieqa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtggppdapq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtnxxptatr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtoldsbxtr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtmblbtypq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtctghagny.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtloqjttef.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtbscgpcxh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtawjzfnxc.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtynmnvbxb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtgvihjsdu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtgcccnarf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtuzuhgvaz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtqcmltohb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtgyclflfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtoxvxjzdr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtjkgnnzra.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtgbywjhdn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtjjmoqyzy.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtrxxnrbpa.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtbqvepink.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtsloiceeu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtaxqxewyx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtinulxajg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtjgmnktyc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtpnvkdjuv.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtyexesyct.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtpuqsawxr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyhxmegg.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtfjdfqptm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gtvnsqkhlu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtqqpzsilz.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtbjclvcpk.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtqdijedpy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtioelkuri.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtpedmesvh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtzlspiiqt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtlcnqaykh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtaoidzctw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtttgboihj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtpctnjpxv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtqzvqhmjl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtzyqzkd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtodnnumqo.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtpqbymxsf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gteohjqfzq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtqysqtbza.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtxxmkwxle.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyzxkzhx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtmvavyljt.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtfaoofgsz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gttckuwjhc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtskqtuakn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtobksovya.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtkhyjjmzn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgtzkoybf.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtphylkggi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtpxokxvlt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gttelrayut.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtynvzvotr.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtjdbhbenc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtyldsxetm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtklvedado.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gthhzmvlrt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtexmujtdn.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtlbqlkikf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtorwnmfug.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gtunuwlzwy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtazqzbblg.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtcxsikxhq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtyrjbotcb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtodzptsit.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvtwcndb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtgvnoptof.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtclvauouh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtmjqbrrje.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gtuldrxkuk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtdvxtezzm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtrkdlcqtz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtyjkfnota.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtltatyigw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtbkfpiowk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtwzxgokmw.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtydcythof.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyedyvdf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtuggewyex.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtvwgznztp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtcykhsozq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtcvyoheow.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtwhinijjc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtfjfxowsi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtjqatwjra.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtkhomgzbq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtwmpdjufc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtneofcvwy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohguhkfh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtvlhdoyao.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gthesovmoy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gthmijkdpp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtmbfwyogl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsayusgzh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gthomjqrkh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtgjqucklp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtexaymxha.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtuhvrbcpq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtfkvsuyus.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtwvesaxbp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gtjlqrftpf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtcynlkvot.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtjwyqgihm.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojkermkh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtqrclriao.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtgputkdpg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgmkmzmg.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtlonlqgmh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtpxeucbvf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtxzuzguyp.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtwigcfmzt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtfqgnhtdx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtpgwqmoyi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtrczssuvh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtuwhbzqrk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtxlmtuvgm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtahrptype.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtpujbecsc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtgnkjqoys.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtwzjyypmg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtmsprdgso.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkvzynmjx.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtksjsxrce.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttnmxobjf.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtmghnysyc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gttbvhveoj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtneyycbgx.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtegosqhji.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtfewqghxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtcuccdpkd.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtunricvsa.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gthjglfqjt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtbfsuzsfp.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtujiwotqe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtcwcccjit.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtzfvitvcn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gttawiphxn.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxcualld.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtmrwyzikm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtifuxdkio.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtblsxvvga.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtjysdpoim.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtzbxlmpwk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtolozntwu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtoirwvuaz.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtdjyiwjtw.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtjgpsqxyu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtyzlhlovl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtftzzlunk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtwwfakbrk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtreilquzc.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gtytxqdjzk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gttherqepy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gthqbsrsug.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtycrzepdj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtqbwszkgb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtnnmwjpgz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtseogvkyn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtquyucnlc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gttzdxzefy.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtfdoddgkp.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtswzupwhx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gtaapfnugc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtuoucxejo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtahvxsyeq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtossgqdwa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzzjzcfz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gtgrkiwosc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtndnklead.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtbibmpmzc.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gthwiakgxd.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtabqmizsk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtnqmbywkf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtsbkipsdu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtxaajxamc.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtlicefqmy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtlthlpagt.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtdtxlbgrw.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtxytgcnia.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtxgvjizog.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtmseywslh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtjrzkccjf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtafyfcuok.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtzncbblzm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtcvxxmrnf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtybpetedm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtjphqicdg.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtnjowwzty.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtcwyvddhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gtkyhjoklk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtsnqjwtqj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtfjifiweg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtbishxlcx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtehqbbtaq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtqsbptsrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtcxxrcqtm.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtgcfuwirc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtdkokyrxb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtfffnhqih.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtmthqknpz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtqoithlqr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtfhavjciv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtcexjwyro.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtfcwtejgj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtrbcddvyf.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtunpcjzew.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtnpnnrnmn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtuulayroz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtfivesonn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtzeihtawq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtiwyigcig.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtwzuygnir.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtuscgayub.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtglwqiywu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwjyceilm.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtkcochcde.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwlpxbmie.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtfmzgtlzn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtgbaewdmw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtivcxirvo.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtohbrhzoh.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtnrssqvjx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtmhbcqece.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtteenolzg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtzpgosegw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtwwxhrita.html


<!-- 参考信息 -->