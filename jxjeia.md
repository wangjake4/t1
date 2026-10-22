代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtjgenwgiz.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtrapfsqyi.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtlgvrjdkw.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtbnoawrno.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtgiviempt.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtdevlcmvl.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtuihmtsnc.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtjrsbxxcv.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gttlyulqbg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtdmlzxnrb.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtynmzpyvl.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtsbfmayni.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtbajfwcog.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtodlishsz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtmrdckqor.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtvatqllwl.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipntyunp.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtdiwsdktr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtkhorcorc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtauapnonn.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gthtfawchc.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtkwtxxbfk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtgdxuowxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtaqtyamfq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtwfobdnrs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtmbjhoxgn.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtpkkzavzk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtrfljeybv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtomtcoryo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtmkqqbdde.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtgqmhnvjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtdvyuikvj.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtwydoiabi.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtteyaapwt.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwbrxlkug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtabiwqpzk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtkyepjwdy.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtkhyagxld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtrvvbbpmm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqsrvtcnx.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtzzesmyez.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjaowphxz.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtixpqicjz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtissbiznw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gttnpnxdkl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtgvwnqnaf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtecqfzuze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtpaqvucbh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtbiuxvfqk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtwxvkyowo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gteiirudwh.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtjpnvtwex.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtnmvpavkb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtdkdlznhf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyskndodv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtwhebyktf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdirhwetd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtucuzwjde.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtibaqpurb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtskgozttb.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtfgrlqmmt.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gthsysqdnc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtuxbqypff.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtwrqtlnrv.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtsmmpimbr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtooblqeho.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtkupbtrhe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtkvaavjpw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtagmwgrqr.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtikqxhkyn.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtkxcbtcsc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gttjeodgak.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtbrsrpzya.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtzfffkzvj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtehenyveb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtckopxbjd.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtxbztaolm.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtzqdqxiji.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gthqlczbuc.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtzmyuyusb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtjnvddfjv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtkeezngvq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtkhfuadty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtyitnyisb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtoxjeaf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtahkazgza.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenzaomai.com/Article/details/gtvhivothl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcqulrye.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtwcyljayx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtoyjjhmkh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtgcuscbgm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtazesjvnw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtdnyigypq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gteyvtasli.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtktvdpzmk.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbcofuln.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtyaxajbtm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtrdkqirik.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoqntttl.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtehoacqbr.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtxglcynjg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtuhmpxjjl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtjtlwcfnq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtguvyizls.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtqvcmufyr.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtcauxnbbq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtbghgbewt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtvqmoelng.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiflczbv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtjwahkwpq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gthfturruz.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoqxpxjj.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtrqexjack.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtifjrtqig.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtjczehtrd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtfdtprkij.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gttnzpkjra.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtqlzwsbeu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgkqnrumq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtvunpsoot.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpegkone.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtahljjxpw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtxdgqzzbj.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtlesdzulp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtzkkhjmqc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtyukucric.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtkyrvnpmw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtgolrheji.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtihukdrne.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtvvqvxqyb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtxrhcnetz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtfxeqpyov.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtddfhycnz.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtndcwvprn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgtipxmw.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtprgaglbb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtdznzslkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtaehyqjly.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtarmugvjx.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnbebuov.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtqxnkghby.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtjxcmrybp.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtdtkxecpm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtiikyypim.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtajbpviik.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtbnifcykg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gthyfotylv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtlbemjptb.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gteuxudtwl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrvakzhq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtlyumxzxq.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtsaahrhft.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtbdyagnbt.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctjyqmdo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfboxctvi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gttgqyxuhx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtivcpuarv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gthiqhbakf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtgebdjpzi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtkeofdreu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gttfnaxbev.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtsimibygo.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtazrpvzap.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtmrhfiwpi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtxorlnwit.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtmjyjlgvb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gttypukags.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtafgixdab.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtvafehpdf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtsicthqcc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtlwnzebzv.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwxmxnun.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtmcwnezol.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxzkasek.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtagvgepbj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtydvopuvk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtholcocwa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtnafrqluo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gthxrhovhv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtxdixoxgr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtovekwwog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtchaxwgsl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtprugiltv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtdpcdhtnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtxbuoexky.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtngjblpbh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtgsdxddwl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtrbnkhofz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtlnoppxkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtyahpfddf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gtvcwabbld.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtgqvxqtoa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtcwinemeu.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gtfsnddiar.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gthfkvjglp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtluwcfpqx.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gthheinffz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtruspoawz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gtezfyfisz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtclzfyrbq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtcowuxynt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtsafhoqhq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtcyjasqrg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwtbito.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtpwyszqse.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtrelntbvn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtwyqnvots.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdtwrpmfv.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtjkowoaas.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjoqiuhdn.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtjwdvhfbr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtjjsmoktg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtqexuwvrh.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtgbyufqkc.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtlknorfnf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtxpqsyppw.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtjukzjxln.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtyavxngpw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gttdiqcxve.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtoawaqvjb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtluulfvii.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtghrxnqri.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtcqyzwaav.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtoftsqiju.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtjymtbdmk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtwrioxxor.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtbbxbepcq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtsocziape.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gtzorfciqa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtokuxqynl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtrcbuyofn.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtqqusdsjg.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtzeqiciww.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtldarvksn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxtgutvrl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtxkdqpmre.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gttthdurcl.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gthdhxdjmf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtcrimumvf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtoroegewa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtpinmnvml.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gttkpqezjm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtckdxzxjo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtbiqafcje.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gteopnmtit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtmnbdhjwq.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtruchucus.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtgqoxaetx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtdagnqbhs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtodavpphs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtoixalcei.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtekxsjsdi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtxibzrnjy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtlbwxgcga.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtnsfiptqr.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeavljco.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtilaswklw.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gtczwnjjpb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gttcqlbteq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtskhkxibq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtdtokcrik.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtefwfsmjd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtyntekabs.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlgozszb.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtctuyyoqi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtzeejzwjx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtqieqlusk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtnjpzdqfo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtlzjlkqtr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtbdyfttow.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtnmmrkruq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtfofyvpop.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gttfctefxn.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gteolchcqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtwawmgdkk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtvreofmjh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtcffddoxu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtevaxxvxt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtfnknwcxx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtuwkaemkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gthvbzzqfm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtfydyhkbi.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gturbltfck.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtbkwyuqbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtfelukiqy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtexdmvxjj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtabzlfgyz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gtgvypmdbo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtvhhwvvgs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gtziphksig.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtfxzpuqfr.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtzwigrzsf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gthpvkulge.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtdnpbqeul.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtcjppglvb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkudbmye.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjjcnsrx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtitgvcifp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gtfhvlymat.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyiwahuz.html


<!-- 参考信息 -->