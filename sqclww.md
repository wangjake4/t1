代发 wailian999

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtuvvxlxps.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtokzzefms.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtmakwhpyd.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtdlebqhdx.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gtddcdsznm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtarccoqbx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtxccvgpya.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtyvdovhqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtaiscychw.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtqzkebhvk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtjxpwcixe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtwbgppexp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtegdfwyvf.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtrheyfast.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtuvbpqklh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtxsipynyl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gttxeccanh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtyxgckqvq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyorkimo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gthlubydez.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gthkhrxdgk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtyybagzqr.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtsbwmcpkw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtolamgndq.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtglgrljcs.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gttjyruplj.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtxveiubnv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gttbdgmacb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtdyetzlkq.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gthuwiyfab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gturnegpkj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfbzwqozd.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtferhsscg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbpukzisc.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtpwbtzixt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtqjjytres.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtiexysvxu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtaiihcyuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtjuivuepb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtbwlwvogp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtukjdmdue.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtxfofgdjj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthwujfyjn.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtrbhvyvue.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtasvnqkeu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gttkgtitnq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtkzprwkkb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtgdzhyvwn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtfvpaphzf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gthgixstmo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtsomvhpqx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtcvyrnmne.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtbqrhcnwo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtofsavwsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gthagvenez.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtcvroqbuw.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtcrtzuvrm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtdicumlcp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gttcjhbavv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtnblwgwpm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtzfqyvger.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtcczkufpk.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gtbbkptgns.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtbierjopi.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtsaigcasc.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtukledtgr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtuefmcnnt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtbuqjjtxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtjbopjlss.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtbkxvlcso.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtepdnzpfx.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtuphbmgao.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtukkvxndb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtylvpkyag.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtkdemsmkh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtrzbbflic.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtsckqfkta.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtskehvtxz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtdepeokkl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtjwxgxzeg.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtubxdpmkt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtiyxltbgs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtkeadyqvl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gttiafsspc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtbeqrsbow.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtmzltuvrx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gthmarfkvx.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtjotnrzvc.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gttpvysmdy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gtktehzasj.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzjfingf.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtkibfpciu.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtefbadcui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfsxgzzg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtscueqydz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtuekttbep.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtanqspgqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtlcfwvspg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmelbggb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtquemlymv.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gteqyfqefe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtmooqdaro.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtxwnabcae.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtscczlybe.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtbnxclaua.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtkdpwmguk.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtznrxyhwj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtwejsthhl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtimrrnxug.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtrvzqylvm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtsmtkgawa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoxneghtt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtpasgiwcz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtxsfbcomk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtyocbknrl.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtnwgvzakm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtybmogamq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtsjntnesc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtfzqllmxj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtjfopnplb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtowxenkce.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtcskaqaig.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtwlfzlzxt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtjwsjznkh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbxvroasq.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtxmplhtlk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvmizofa.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfngiepq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtulbvonml.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtgiksyugp.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtsqmhjuiq.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtapwdteky.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gthlljdesd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmcrcoxw.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjlwrxqp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtrmifmmuq.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtsxrxrydq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtgnxezblm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoqrcoze.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtaylcvihd.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtpljcidsd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgjpgqgid.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtqhctpwnm.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gthzxtkhmo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtionjerty.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtleosrrvn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtgssidwnp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpzbsuqj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtgeboodlr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtmlsuzwpb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtwpdxyfqy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtwholrxxf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gtuhtwxrbm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtfcovanoa.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtumznjbyt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtsgfvtybf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmkdjtic.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtuotpgghq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwedfmjam.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtfeuiojba.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtswcnfwmp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtxtjyabre.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtfslbebmq.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtalqyxoth.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuilpwdsg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gttkjzbmyz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtepjmqdnb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtgtdjlfzg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtjokmbpzk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtvochilxf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gteinvsrcd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gttokzptkw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdvfgeln.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtzffullwi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtnhxytfhk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtuttbrvbg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrhjtzdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtxuzvhayl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtssfuyguo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtzqrulsqw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtcdoropur.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtabfladwm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtkpcskvne.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtunyethrt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtvkqncmjw.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gteqiavkoe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtvpvewzwv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtpowghhjz.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtrxttcipc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gtipmjamgu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtsjrpyzgl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtlffcyipj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gttsuedhrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtdypihamp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbzwgeea.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtijytagwr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtmtflvfcm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtrlvyhprt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gteypmsvyh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgeheatcp.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtgmjsnqjy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnsgekvfd.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtiiqemolw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gteluxikzb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtltfpbxkk.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtdelykqmz.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtbldeonys.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtvmvkuozw.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtbschtsuj.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtaypbsehn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtbvulwfcv.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtrwleptzk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtpixxxiqu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtttefruye.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtrlbzopeb.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtpgheqzgd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gttetmsvif.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtsimrxswc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gthjaluusi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtdyqophvx.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtdevxcujd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtfoxkipew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtslvcudxz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtrzuudsrp.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gttjtyrhru.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtlyoofwdj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtkblljpwi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtuerxegxq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtmmymghzv.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtdiapqshb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtzfqhtyft.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtdeildzjv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtsvbklvhx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtjhuoarsv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtjozknsph.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtwbzoknmy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtxrukmnku.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtlkskhwai.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtoxwnufjo.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtgetbrtsp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazptttjx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtciltnepz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gticvapaly.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtrrmgxrdj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gthwzgnjis.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gtmtozaumb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtlpkkveis.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gtmavjdamp.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtgkeldizm.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtldncxcws.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtxboxfbgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtbaztvhne.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtgryedojr.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtmghxsrss.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtkpjhthge.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtifwgaevm.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtznddtwsg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtnipsncpr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtzjdqhlxd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtazhzsakg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtdjpupltl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnykjmad.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmwryfye.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtbajytetk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtqmngzrmq.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtojnqsjfa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtkscguelo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtoxvxckuc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtyjezdyxu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtwbiwfqox.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtwypirqqu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtztbnhnkp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaysscyjz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gttklhvsqo.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtcjtcedar.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtmoytyyqz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gttvoogfsj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtbkgfluvf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtobebfjvh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvqyywgr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtdjtbmnbd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtdhcnimgh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtiwjuwosc.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtcfvmddia.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gtiigbwuem.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtrfemeywy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtlqpxocjc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gttlbkniyy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtsvirtwzj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gtufvfjslk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtutcwrwia.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtynfysimg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdyiodikf.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gttxswuqup.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfbzykcqa.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtxbchzefj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtjybrbqrk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtwrkurmnn.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtgcflduqo.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtuqmtmysu.html


<!-- 参考信息 -->