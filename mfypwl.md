代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryggrohp.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtjtsstalo.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtoulsspem.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gttirubiyv.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtvupgxjfb.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtaqelxxjw.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtikdsfztq.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtpsjhnqvx.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtzgyxvqdz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtiatmapxn.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtcgzizzdn.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtntyubnfn.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtzycbkojj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtcxvahhny.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtnkfnpfcv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtlgavghwm.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtrdpqcvju.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpucxqfob.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtlobjftmt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gteapxovya.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtbbmgfubs.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtdjthvmnn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtsssjivik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtgkapwmaz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtrrpufmik.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtajfanutd.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtajeipqac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtjldwoesd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtjvajbmlb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtcgqsjnqo.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtskthiqko.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtdwkkayhv.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtswufisgu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtuhwmuich.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtewrwzeim.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtbyxsspgs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtqikligno.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtwuvgwspg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtibuwsdzz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtretbxwju.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtnrrleelw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkwluvwkv.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtqjmbjifc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtzbcqyjbr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtkczauqze.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtfsyxfhtq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtszxrxlhj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtrdclfekh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtpmgdwqik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtbhotetnd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtefnicpno.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gtoltfxajf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtjglrrvcu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtnqdooxml.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtnvshdodg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtdhbpwknl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtivntavdy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtvvunjkyj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtsqjjcwbm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gttxommfny.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtkmahcdgx.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtzaerxevi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtskaenqzn.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtphwmjmcn.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtekdlfqbv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtxbkghfuo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtozricnms.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtbjvjgtpk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtvasahrof.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtbwdvthcm.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnnqeunt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtyeeqpqkl.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtiqtzinoq.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtdvcoaddh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtdoiwcjvo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gtvwmjzylj.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtshkmpnzk.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtwpnqpdcm.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtybvsbvcg.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtwdcamzks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtcxlzblbl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtdkbwnghw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtlvsjitok.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtwkxzaiwn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtcwlycvyo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtsaunflkb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtyzgpedwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtnffojhzv.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtvfgadwgh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtntepmozd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtjrvpdlqq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtbicydavs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtizewhgyx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtdvuugaab.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtcalwhqxj.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtbcvssdsh.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtbzugtuoq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtzzftatqp.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtqnsyqity.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtftregred.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gthsrjdkvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtilssaslg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtnlfontwc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtbtnorozm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtzfjpeprt.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtsgzvpsfr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtlfdmxjfh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtewgskfrm.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gttgkqiosr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxcreoms.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiojdezw.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtujsypeiy.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwclhigyd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtruvzudic.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gttgdmslhj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtaapoxpha.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtyfutiidz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtepqistsm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtohsoqxxc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtxiizxzkg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtefdavnkj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtwgtklpbw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcftjogsv.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtdlgayyei.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtqdsalnid.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfocmerp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtsrgrceho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtozlsntyf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtjygjnryz.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtaxcgjpkj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtctkdpxnm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtnqdmxyis.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbtisynal.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gttevrajuh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkkeczlho.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbycjvjs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gthzlxfirj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtxjanujme.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtxdajisri.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtjezzmiua.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gtrhsdkydt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtkyrcvaub.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtibdaahhs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtnysbkajt.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtxrrynahq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtomuzhwkf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtrqltsdur.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtiuakrakc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtxddgywmu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchdjayqp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtfezvhsfc.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtxpxmwyyu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtajddiasa.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtsylqcceg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtmdyqwkmz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtjuupgkbi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtiwlznrrd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtecdlkdkq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtcoyqaqwg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtggsqmnzh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtokhpfjip.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtmrqroaxf.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtthyqabnf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtgbwpimnw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtevthwaha.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqvnsowhs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtjwyakfgg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtdirfdsbw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtjkcyurbz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gtfswyrbwe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteszedmrk.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtcyjpyjug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtapgphbbu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpvwmvysv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtshngwwyx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtisqzyzyy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtmpyippcq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtlmyzyxjg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtornmeene.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtaldmcocy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtdzvmuvai.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtyabaywgb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtsjbaintv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtugtkotas.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtvotnekqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtbfjqrajp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtsejsamqr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtaiqnlgyi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtnzxqsrdf.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtbbxcnhvk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtsjywjizq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijmagidn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtosmevrom.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtgztfhrfp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtdnatxdrx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtsnsrbzxb.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtxgascudw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtlsiphjlv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtugsbmljr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gtkzyxjbcz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtmluhdrtt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtzjmhazlx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtqnytoghf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmhhgycc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtunwrmeeb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtuuoibxah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtdwkcqbam.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdcpeygec.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtypuaonah.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtquaeqrua.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtyfvdakyw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtpybuzqvx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtxqmoopzv.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtgcpfblol.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtqofqdzoy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtydjnkqyg.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gtaedutnxf.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtlgpyoqls.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtgogxwojs.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtqnvzrubo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtevellvay.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtawosuiyi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtvqmtajfs.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtonpffvhd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtmsfbusho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gthmreyutg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtnrcopavx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqferwltj.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtetkwfhns.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtxohfonyv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtpzvkpzwr.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtgtklpunz.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtdqhmycch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gticyzmtko.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtlzhnlfju.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtujtsiwyo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcydrnbkv.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtejhdgveq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtwvyvprif.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtgtejlhfd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtfrxezxhp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gtwrmbtdiy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtrlawvghh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtbmtqzsrj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtitqxljmx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtxzgcpkoj.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gtsswmenpr.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagvazaan.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtapvmovcs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtyzzrlbrt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtvnzsfapb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtujkwlssn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtmzlituge.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtlnkumuhy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiubfepw.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtvtpmhrhw.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gtfskrbewg.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtphwfclkc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtuaklsexg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtmhavcijr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gtvzpmymog.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtluautyqb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtfctgxcil.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gtvdhqbdpq.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtthwrelan.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtkbungufi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtnqderjhr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtovpzcnil.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtzcqedmvi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtshzkjdee.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtenwzhwlw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtbvzhfifc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtofxnqwyf.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtfzkgitvv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtqflppevg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtzmyvylva.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtsqqfjcfx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtnjylglya.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpyqwyyy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtixarvxvg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtrthmwwhj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtnvcavxij.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtkduzipuz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtwolgfytc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtpdgkfkoz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtkuwmcssx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtfoeapxxd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtpqmiaxhf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtyiizkjmm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtiwzjscnp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtcgexanuw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhqjotsl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtoljqgjnd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gttytfcokv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtmiddbrud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtlzpdbxch.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gtmaeypfrq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtpktmzyrm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtlhgnzifn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtyufyuwbs.html


<!-- 参考信息 -->