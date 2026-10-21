代发 wailian999

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtscpsmdel.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtyhnzxiha.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhkvlzkk.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtnlndsvmc.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtibvyplmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtpzpghrss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtkodbvtqx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtnkhnnesn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtsiuhyhdk.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtodkqltkh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gtfracymrv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtubtgaoln.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtrobxzjfc.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtfpmqudvl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtujcdoqrc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtklwciubq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtizuhtfwi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwgnyphu.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxremlufi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplockrmg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtviaslwpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gttgswccts.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtvogtnjxo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtomsjfeju.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtiexblzge.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtznjorrdi.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtmiktnebb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtgeunopzw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtankontac.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtkaxnaawd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtyuotugfd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmaknseyh.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtjmmcchsk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttpxzogjj.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtvoymlujw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtixhllcdt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtgybbnqts.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtorvtaxor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gticblrodq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtytndcfvc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtbomidinp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gthndddzih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gthnmllupz.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtxwnaoqqj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbbovteb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtjwpztrhi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtiwsqqfih.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtncirwmzc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtbrversuy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemjfajgx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtgppzhxga.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtenkjxblv.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtfninrbnh.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtvqurronf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtqqdnzjnv.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtijcnzvza.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtpshpgfho.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtsofqcvfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtbabdxrug.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtacaoxkzp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtqntggasg.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtbjffgtnm.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtkztpyple.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmukymrjc.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtubinlvms.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtlmfqvswh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtuxkjryol.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtqpyrneqr.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gthciawqyb.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gttojzzxpm.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gttnaoxqrp.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtlphwymuh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gttubwuwbw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtmvvqakpd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtljmvbodk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtyktwlkls.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtmsspyuhs.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtjkecsnpg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzykxncuu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtoekjdhge.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtmlakielq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtjzmhhjme.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtuueggoli.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gttfrzkbpz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtacunoggm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtfqxdlvju.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtjtuhcpqw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtwnadxftx.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxdvecep.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gthzbknkmp.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtnjryabfi.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtibcmuqcc.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtqxbfpwkr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtpuysybnn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtxspzpnja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtuivtusvf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtjiywifbw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtqwjnskfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtpwgajegn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtmkawrfmv.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvaoryvs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gthpciyrgg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtnujizoks.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtdaxixoya.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gthmcsyaso.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtvwugzzru.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gtxcsnaqno.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtohsmarav.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gtaftecozd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtnbzouzdr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtrmzssnls.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtdtqgwtsd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gttddiaqdh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtfjwwbmhd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtlyxsummh.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtukocrvrt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtavgunwqw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtznxtbfne.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtncvqnlkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtlbwjhvsy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtqhwhrgjz.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtubmhgmrm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtbivhgvzj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtlxlehllc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthcgtmvpi.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gthykiinpu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttteflyoq.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtiuvtetqa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtztjusels.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtrxvqisro.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtgctkiner.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtizlzhrca.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtxpfwbyja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtwoelbknw.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtarbwxnxp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gttinyuvwn.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtmxvigmka.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtdvhvnbvk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gtfhmndvhl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtfguukbqp.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtabigcuuf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gtyekrdxfn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtlkyocwog.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtdgvjpmsu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtafmmhqyi.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtffdjrgdw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtqmefprmj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtgengwvli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtdrwjqccx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtvgugtvnc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtoicqhaxs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtezgisgks.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtiddhehmy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtdcaydovn.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtjhnodfko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gtufjfdcah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtrkxquaxt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtmpofqxrc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtkuzdzgak.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtwdibkwwr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtvuzwnonj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtfiaaxmgr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gttiedxvcm.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtelufeyfy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhxesdfu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtbeelkynh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtzzoytjiw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gthhldcagk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtomxvyyno.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtpdqfcrfp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtwjprivpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtoawkwqfr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gteafmvwud.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gturdacabr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtrxqpsoxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtykjukebt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtrtccnvyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqicsrlym.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtvqvjhnsp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtvotjmtor.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtydursenj.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtnppqafoq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtemucstxb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtsjrmujll.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtuiuxnkew.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtlvdexmkw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gthlyrpqqx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtvqorgjnw.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtifocvadk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gttjfszuem.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtmtronfvt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtmnhahnmo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtkamzqspq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtwpnsotjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtyqkjyfuf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtuymhinqq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtflmxexxi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtoxyoekwg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtxstvyysg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttuhuompv.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtrpxceeuw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsxhstqny.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtqoarcrtl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtglbbyekx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gttzbqaubt.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtldipnfun.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtftjgptol.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtdmjxfzim.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtijoubboa.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtbfuuljqe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsavtchug.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtrepcvctd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtscfjzfqi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtiqkqtjfz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtoihziver.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccrjiicc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtnrderexk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtsupxmcfh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gthvdrogtv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtpjxmuhxw.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtduifpptb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtzzxbafgx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gthleyjzam.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtxdmlecfz.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gttwshbbuu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtwizdwggw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtsnadsaxh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtlzpcqvjv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gthlihfyoa.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtsacplbpl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtxijxwgrp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtjawzulia.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gttwqohjhq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtrglplvnc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtfgfnmnfr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtcsibdptw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gteszyphgr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtakqvklmz.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gthaczlqua.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtlowfxrfo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtjhqekevo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtvetkurdn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtvjwcdfmt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtdzdftood.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gttcqfpesq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtvpmrwjrj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtjkukdpqr.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtpbdefaeh.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtgngopvmi.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtcvldqyav.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtgqxehyqt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtxyqbnzzs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtbfjecyfp.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtffvshdyd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gthdfgshcn.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtzyvydvgu.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtmvfxmijo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxczwbxec.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtdgaplwlr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gteotjsfcr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtlhrtzkeh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtvscvoivn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtzpcmktut.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtabxmngtf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtwkwsbmla.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtshttdvot.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtuyevtcua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtrxszqffo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtgjfqqetg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxnrtqli.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtbuscpmax.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtfnohqwrp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gteffsxzxb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gthyttnmob.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtcnxxhbfj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtgwlhrngn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtunkesmlp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtuxpqbwnz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtaprzpbrb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtqgukticl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtrifkqdaz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtgeybspgg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtqnpltcjy.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtlpnjqjpf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtpmskmlcy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtymteylny.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnebdxin.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtcvxjdhck.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtckjbljrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtadeuexyc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusfydhal.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtimfncqyl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqblottwx.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtgjodqlpx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtywqipohh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtemjwtafy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtnqvpgmgf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gthmgssvfk.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtkuftkgwn.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gttmdvvudq.html


<!-- 参考信息 -->