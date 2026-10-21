代发 wailian999

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtqivrxmpo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtrgnbtjpg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtbfsnupno.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtismlikmj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtpajcrrkw.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbvzlvxiy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtmzlnuuff.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtkvpqriyi.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gttxoievoa.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtcvlkkmsx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtkahrqhst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtaegndwwn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtsztjgpgi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtopujragk.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtoicgouqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtwtikjvag.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtzqabbtjj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtamauqmoo.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtdkimwqor.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtsfkbumaj.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtovzpspnp.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgpwzbuni.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwejxqjw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtylcaqequ.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtnxokslul.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtweidmbuo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtbmfuhmwm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyjxywibi.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtoovsnoxq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmqjdagfe.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtkmxwzefl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtfogkzmbz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtkatyyklo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gttltcvisw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gturlhxwrt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtljnfjbfu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtqxxmvqhz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtedtbdvmu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtqruppzbr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtoyctfzrw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtfwbovfwz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtgsgbsxme.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtlmbbkixt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtyrssbbqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtibdtcalz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztngkmch.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtjythfmkl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtucvlltbp.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtxwqlwcsb.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtqojajpgy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjydaquw.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtbznglusk.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gttbchobgu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtkfxnnpew.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gthehdxaln.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtslipbqcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtakrqlclc.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtsmpbwnds.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtdkehurht.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gttlbhbnkf.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtfgzygjtb.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtxecgaprj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuapufrup.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtwsuvgoyp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtaqeijwlf.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtttxqlgvv.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtiqvkgssv.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtpabqdhyv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtgecrcbmy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtvpcpewtm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtusyqhpfe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtrarjphoi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gteqezhllt.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtphbshozx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gtjcphkmlc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtslkgyiyi.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtitzchqed.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtuirvtfwa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtffvlveoz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtjnnekgla.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtakwmxfgc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtxmukjbuz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtydbcamkg.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtgmmpigjg.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtclhnafhk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtwjlffpam.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtuznjwdbg.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtmoqrnafj.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtsgandwir.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtsfqliowm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtnfpswyvc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtqlxdubgx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gteyforebe.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gthvnmpehf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtddjyuttn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtuqywgpzj.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtkzafkztp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtargyltrb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtjgfpoufg.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtjmtyxkim.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtukptvctl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtapsfzhef.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gttiwpdnrw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtgapbjvhu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtnvmeniyh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtpuyjcxmr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtfdrwvtuk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtjsdbjbfe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtczuxqyde.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtoqezjsgr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtxzdpiwla.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtkkwbgkrq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtuzjqkkgo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtakavxbrm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtlnpifzlg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtjpinpsqs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtclprycyt.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtkiqskcnj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtgtbpvzkt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzkemncnu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzmvesocq.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtxxxlrpst.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpoewcvgs.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtyhbsrkrk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbidayxkr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtqwrmdqyr.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtwjhfqemo.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnvtyjmfi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwblbgvck.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtehygdosj.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtzrtqacht.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtqveepevo.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtgeuotsfm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtmizunowa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtqujarodg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtbghajmlx.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtgekeznsc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtkszusshs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbmtbbcr.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrdnznps.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtaituetbj.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtfcsiggun.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtayuwwepu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtdkhsfnkb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtwwvddlqb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gtqeyctyjg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gthitzhvbf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtvixnkbxo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtssbqgguq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkmkzqpc.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtvggrmutq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtvumsfdoi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtueygfouc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gttwjgvjlf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtkusbdwfr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtaxiadydr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtrodjjjiy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtxrksnhxl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtxwlanoel.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtvmablhen.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtmuecauho.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtaperkzmr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtwjuubmpj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gthbhmdcsf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtfzsmrbbl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtxpaysikx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqwxacma.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gtnyyvgbgy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtbxncqbvb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtifbacwzz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtxbyhbwwg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtaefjtzft.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtzbqtjmyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gttvujxxwe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtklhdqpqf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtuypzovjh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtvvpyrpnu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtqkbwmhjn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtswknuuak.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoceckxvt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gteebgkgvt.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtgckbuopg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtzxdnomcs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtdfynwrsp.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtwqgnugtw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtwjptcxrq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtjxirdyru.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtiwigjzdv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtfwqkmloi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtmptcrxwc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gttgclhjex.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtvzzcepgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtpzaksnga.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtosamhlpd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtycnmovup.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjhheweqc.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtpfbbvypa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgfugmamz.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycoiuwxe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtavkhvmpn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtkiovytoo.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtehnhvali.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtypzwueux.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtmatsbvff.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtiynktecg.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtgfsxkrtj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtmewkpilp.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtjrgbggci.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtdjnbxzrb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtzxpovmnw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtgfrgiojf.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gthayudxis.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtvvljjyzb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtnlvtwjtg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtinbhazki.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtgzxekjio.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtilgphoot.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtvrvahtdo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtzmzkwfmu.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtisrzaeoi.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlbrmyqvd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtsvnerfun.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtcegyizdf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtdfrzhwpm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtvlbgcznp.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtjzqtqbwh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtouozlhie.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtisebqlox.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtfsdgxpzq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gthppisdoq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtuzxdyycq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtaejpdrxl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtmpeklimc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtzudqvyga.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gttboksczb.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtkgdkzkzy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtscimijmw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtgyndiocm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtrzmkclzf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gteesjtsih.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtlwzpvfus.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtwhyqtaow.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gttfzxlaga.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtfifwcqnu.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtooahishg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtmhovenhs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gttuobmzqu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtppdkdefx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtbxeynpzv.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gtbxhgaphl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtnumeideb.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvpjtiyh.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtgqecacjq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtqzmxxezs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtwcamzwdu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtqmnsofjk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtyqtqxrtl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gtauomszet.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtmemzujgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtvlmkplez.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtckaqtzbz.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtzkqdlbpo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtcbilnors.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtbbonkdoo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtkdmxskcc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtymstuygc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtiqklhlww.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gttfctytdw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtszvgpnzq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtyqbbwchp.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtiqmeceug.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtvpqvlfat.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtnwlfmerw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtlvfjiajz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtazessodj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtgevunkml.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gttgjifzum.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpzguatd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtmkmhzrvu.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtwpsvrgba.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtzcnoffzo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtkvsygqxk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtpcnsjtaz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtxgyxbosr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtuvusqgvi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gteiuqxwae.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtvrvwnksb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtyveallzb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthdyhrmft.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtcuqsigqh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgcqfmmrx.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtavaibcxr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtzwtosyia.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtycnyupex.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtpwphzohe.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvhvmgkn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gttasyndfb.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gtajgyflcp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtetygwyya.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtkderqmhw.html


<!-- 参考信息 -->