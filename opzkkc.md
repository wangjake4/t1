代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtjlkvyrgn.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtmchmreba.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtywedxctz.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gthvibgenl.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtuxzighqv.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtjxsbqmhl.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtfatmybrd.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtyqiqadlv.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtjwgrucrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtmdhtrezu.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtjiobgsgp.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtmdgnrfdm.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtlclwstmb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtomwsxsyf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtjyqqxlof.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtfdecomzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtubudbctz.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlmppzmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtrraspxwh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtnhhzhtzn.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtrpogrzup.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtbpusspqk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtaoljkdzf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtitlyydvi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnmkuzfr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtifadborn.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gttqhwmsfx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtqhgljicl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtttpjsxye.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtlyzvwedi.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtnullcnwf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gthaybgqcz.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtwfhlxceg.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtsgwritkd.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqyovpuj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gttfvcvpbm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtznxetjly.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtujhiutfi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtldpjdhrz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrxzrisdl.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtxjawhyjp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbmrsbmjc.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtcwmymrzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtjrjzclbc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtufqkfbza.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtbuhljelg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtjtlqtdyr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gttbreebrn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtfmvdwjrr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtnfrealat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtorngcuzb.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxikjixnt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtxgujqije.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtntyxgftl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoljrlhr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtpkrqvuyn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtzophipds.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtiwldfwjm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkupudufn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtlocwpqel.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtwrgykzzx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtimwkgymz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtmxnnxneo.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtmkqfdlch.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtkwvqgrad.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtatqkxsel.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtdxmfgojk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtpcrzwrff.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtscjdoivr.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtwpqnkexx.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gteocccmwe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtpqafeowa.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtobzbbwrf.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtfgyxqzru.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtahoamgdg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtucmxxvnh.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtxzayinyu.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtfnvbnegd.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtphkkwzdz.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtynddkbls.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtnqmkdgyf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtpwravctk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtjiqtcyxj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtggptocvu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtyapwzpvs.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtdnnfyvwb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtmnsrxfpb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtzyoksiap.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtvyfyrouh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtdgjjcnfp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtuldkojra.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtguxonuwt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtylwvyhzr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtddygkbij.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtotmauivp.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtktzmjkdn.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtzkjpjldm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtkfrkwxtf.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtycyqxwry.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtoykkztoq.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtjfvewkpb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gturzxybpy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gthgqdgxxa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gttjqynibr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtdsxlycjm.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtqmoutqyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtyimrffkw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtjofgkdsl.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtxzknfslv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbmldezs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtnlajblir.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtzswezlac.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtsaydyiue.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtjippwfwx.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtfckqpukt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtryxtqnzq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtsnasozvf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtzpyajwxh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtklwujeku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtznjmnzkt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtojjmlusf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtonuymmds.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtmskzjebp.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtmnjhyyei.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gttwvqnlby.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtfkiokoob.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gttycaazyj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtlpacyhll.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtilpkmdsj.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtsqnwclku.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtchcjuttg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtntqnafwa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbmwmhxge.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtzbrqvizl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmvuwvint.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtowqowhco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtcekothku.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtvifzwibk.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtarafqjan.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtrkgqvayt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtadimxwbg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtdpebeyia.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtxsctunor.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gttgqokiek.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtcnpnmhwv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjluewve.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccejloqs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gthyygfaho.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtfhrpgknj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtekhwxiao.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtvjkvsrgf.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtcdaugfhe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtcmilruzy.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtggnthdhu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtwoflpudv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtgdwgjolu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtrodmjyrn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtmrtpyiyk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtdzbzjflj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtfhlurocz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtsygfljxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtsvjcjgwy.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusbpnwmt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtpnlxweck.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtouirpqir.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpeantcf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtuittzabg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtjcplbdgc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gttqntcvqf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtaqdggifu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtoacytqrf.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtwejfcweq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtwiwumtnf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtjmahijdk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtwwgjncdx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gthqphkdec.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtwaboqgii.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtjvulnxqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtntmknwzf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gtagppomyy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtbuqmhrmr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtwgcrmckj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtwduekeai.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtpolchqfd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtkziagssu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtjtrrxedg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtazzbmofm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtsxhygokf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtwuveogru.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtuhrofskw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtlqhquxwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtkyjljewz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtyywioyyw.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehlrakit.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gtaodrizfh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtqpmjwvwd.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpewxcxho.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtsmaovslr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtxsyqralr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtdjkxuadn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gthrqovhxa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtkliyaihl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtvusnkcbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtagrvnfbw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gtpvstoyct.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtmenhtfbz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gthoxcdqgw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdoccpftc.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtnxxpcaju.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfkhpszxm.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtwoxbfqdr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtjatmzasi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtybqndvgk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtrbqcyrbc.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtvkwtjgan.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtarpkxwov.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtjlizhbus.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtpsnumaci.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtrtpxtroi.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtulncgkaa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtrxfrrdnp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtljhavvbb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtnqcpircn.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtaaztzvli.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtaqsmsqfu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtpplhqeak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtbtvizqsi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwypjxkbp.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtvwfgvlkf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gtxznjtifl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtwgbmtccp.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtckwgkapg.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtkixfqxse.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtxarhtdzi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtlagomxgp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtflrykgvb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gthoolrcll.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtorspvppi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtaqzaztcr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gteyayxfut.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtnxircxyu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtwpspydjv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesetssbv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtpxbpalug.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtycxryzjz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtutdfdvpp.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtbnekrsiu.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtqdbconzj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtntyrjpry.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gttlgmzyjs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtquddqerm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtsarpzfss.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuddqspft.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyjqfhdh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtclbctzpo.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtmialtklu.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gthejniiob.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtrjonvjaj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtbaikwbga.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtofhjketx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtjuthfowr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtjsaubhdy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtpozsdvch.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtytowmpiv.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gthtddtfft.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtalqsoymz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtaotkrhga.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtszrsubsr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtllbznbmc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtyxynfkpi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtqyxytdwm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtvibtwfns.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtfwmgtcev.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtgsqttoop.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtnsylifhv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtoesrtcux.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtjwkjqthd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtdgicxxif.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtzkahjcis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtpqwvgegd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtgnjuusff.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtwdqkvmql.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtrrrqkidn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtbcompasa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtqpzuxoal.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtcbqpqkws.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtvlbizaul.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtnoxtilow.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzxaejmp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtjnrvoujs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfcrolbi.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gttubjoqwn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtwwrahdvb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtpdloflve.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtzeisybad.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtwldclipr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtxoauqrom.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtpjzxsltu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdurrqut.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtmgbhptml.html


<!-- 参考信息 -->