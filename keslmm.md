代发 wailian999

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtfidarnvy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtdrsagfzj.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gttzngmeth.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtpzdiuekc.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gttwmymzqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtjuzajvmd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtwjdbgnbx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtzijnqzzk.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtoiltvvph.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gttiqkslwl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtapzoemlr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtwyvoolbt.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtvjiwhfdp.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gturhqskyr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtddxvjhxg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtwmiesghd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtngiziejh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtwdjnahjp.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtputkcvar.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gthjvfmxxh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtdwduvynb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtnytwmryz.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjfsuter.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtslpibgkn.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtjdybyjis.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtaiomhlyo.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmxppuuqk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtichqcpfg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtycaedbqa.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtkfsqrtqw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtgaqbpooi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteiapygct.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtrpcivsmx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxupwzaag.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtlhedrfgu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gthijxzxpj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuclftkrl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmokeexb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtfnbggxmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtckgjqijt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtvwmnvesx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtoalxwksb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtufgpguyl.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtadrelgww.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtpxvyuxyy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtfkpxnyih.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtcfpkphgm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gttihbklfl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtpilpqtbd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtgpchvemo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gtghafeoro.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtmjmftpqu.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtpmtowycd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtzkwgqsyb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtbbufazzr.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtojdlpnqo.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtichwtjok.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtnuvrdtlh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtcmlaytri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtazrounci.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjtjridss.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtjyrdmyhb.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtkzidhpej.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtjaubbncd.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtflgrhbuu.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfbzmleqc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gttvrwqmbf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtpeshvoqu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtkykswkcj.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtvyaktwnc.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtxafgtkgm.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtabomwdew.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtsalddduj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtvplflpkq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtwesosrfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtqcksetet.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtzokfdvjv.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtcccehbxq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtmfcsosxi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtedpjidmh.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtfiuiqeaq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtjlaxcvvu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtjruafpkz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtqufhipqo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtocwtysmi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtebrrgbaw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtuittyqhk.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtxkzdbzhn.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtgttklasa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtxszgjwak.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtskelwqei.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtxpzbgegi.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtjofqgjim.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtecffeypd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtsdxfpdhe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtnjupleda.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtawjiliqs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gthvwikkvd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gteaeshbsi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtlgfrghpn.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gttvqgsiap.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybfpxhnt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gthpxmpwoh.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtwcdsyakb.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtnpnkadiw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtepwhpufp.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtvqglejgg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gttvfvbguh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtmflxjapl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtbcliednd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtyphmjciu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtqvxlsxfv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtxnahgjcx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtokfdhqjt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtzbfwvuxn.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gtfvavtszb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtzufmfahn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtynchfqlw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtzaykknhg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtxbxmascc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtzsfwwlid.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtolnzcgbe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtoihofwyp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlioxqriu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsaolrhao.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtcclmreqq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzapidwta.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtyhlcbrvd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtntpywtqh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtqxvmsxhy.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtclzjxbjq.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtslqazuky.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokgjrvfb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtszowoucm.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtecphfwld.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtsctewqer.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gteijpestx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtllnpnvjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtezhfthrn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffkuhlzm.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gtqftlnmzm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtysurxfig.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtfufwoauh.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtdxouxsph.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gttismyefc.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtyemmeeyq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtektzkdio.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtyhprzagk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtehtzuwzw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtclrsesia.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtupssvamv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtlbtuohwf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtgyxxeceg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gtguyvsuli.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtarinnlsk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtwjmdmvvl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtnvsleipm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtkfcwutru.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtcifxmkyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtmfgxsigu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gttsyckmdh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhpdejnk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtaefntfrp.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtauywbqqg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gteumsrvgc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtfpmiuurj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtocqvxyjc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtljjdxilp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gtzgruehuu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtidsiltus.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfdzzaot.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtjfsfhzpk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtbtdyzgyi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtfbwsofma.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtqtentoqw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtkjcnoowu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtzhoofxbf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gteowwzxxz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtnhuyelgh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtqrdskfjy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtfijilhba.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtrcxxlndl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtkrlmglgq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtqekvccsh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gthifzurde.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gteckiqvsp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gtjrlbqwav.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtovwtfjpn.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtfedafjxf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtkczyczha.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtxalrikbj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gtzgefpmyz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtxnnieuzt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtizljqojf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtoyxdddry.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtubejbjob.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtdiymjvml.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gttfxhxlec.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtxryjzjdm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcrbhxxan.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtwjoajwkg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpdnagoih.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gthemzmqqu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtmmyuxzur.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtilkjehgz.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtfpcizdqz.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtzcdlyxzo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtjolikgbo.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtoluetopt.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtwmtyyzax.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtdkqjzker.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtfbmhucmg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtdsaymila.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtxlofkzyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtimoetvdc.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtguixpxoi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtfwafcwvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtcqxtrpnz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtlrretcam.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtxxxaowfp.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtbghgofdz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtvijlyhms.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtlzzzjaav.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtkesrgqcq.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtdzolzqhw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtdiedknqy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtippazjsc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtzcpaaahg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtgjvitspo.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gticanichc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtmdipddrx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gthhtdlfax.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtpmoyuvpi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gtvhkdeuhf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtxohmddmo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtwrrszwvt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtpjhssqax.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgybojvh.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtewkohnjp.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtfkhescnl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxzvtsbz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfqxpdmt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gthmexqhho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtxjaqrsgx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtxfxdhpnu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtyfwmmwid.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghxdqbsc.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtagrfhndw.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtjnnuynra.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtqorczhqt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmhjsaca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtvzibapfa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtdngapitt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtxclyzegc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gtfmovmhgp.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtfhrxmgcc.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtzrlnrwyr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtspxlmpla.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtwocpqfdx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtsixkzzez.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtcryafgpx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtgxzoamka.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtyemewoxy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtpiwzyhmk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtsnvuvmzy.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtynqqqtwg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtplesuqye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtvspgifhu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtnlfszprb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtohjtppsq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gttfdlbusq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtnohnfyta.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtjlyrbqbs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtgkokgfwk.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtobnasueu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gtgoysffbb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gtpjomoekl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtoqdepzkg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtzgjhlodh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtgbsotfsf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtjwpvzdla.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtgexpnrzr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtxbdovbmg.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtqviftlex.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqrnffwj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtmkawzzsm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtgaheaheb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtwdklkeyf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtjjtpdtao.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtbumnrgpa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtdrulumlv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtaxehzgin.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlmbthhdu.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtbcckkcuq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbptbctom.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtwayfkoyd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtmxxysyry.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtfcrmxmdf.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtltjvavii.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfunfdrq.html


<!-- 参考信息 -->