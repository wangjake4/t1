代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtfzrpozxv.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtcbptmwrm.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtrnjspooq.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtzsdhsrbp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtprndzbmg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtcjbgyttl.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtallrlycx.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtpwglctwq.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gthyqjexlm.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtpirzwqpk.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtbkrshnmi.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtwrvfcvob.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtajypjusb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuoxkdzt.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtzqkelmuz.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtiwrygluy.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtndnpeihd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtwrvjhahq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtikqfofxf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtxhanimpl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtxvrnrbxg.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtvpkpcxto.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtulgotmuh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrixxbuk.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gttzjvggpk.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtyzngqldo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtqnbxbhgo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtimxyzxpo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtmnoiewsn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtfuhxqjpp.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtztqkqtvo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtnpumektk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeimkves.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtyvsokmrl.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtywtgvsus.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gttazkhlxz.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtvcvktzcp.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtbghnnkug.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtndpntmky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtxlqzmcaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gthdqftgkv.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtkffsermf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtewwmfxrt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjijsxrsl.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtlhjbznpg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbluhjcpf.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtbycsstip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtcaeloiri.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtkzaxppco.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtdajnvkbi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gthvscipae.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtonrvhaoj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtvphhmisu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtgyzjmjdo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtatssomqt.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtemmkhfhu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtywyyhatc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtgsuabsxg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgbusgqm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtovoefgco.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtnujczriu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtfeoyfcup.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtznvvpzmr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtsgnnzbex.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtzuojpwrb.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtmlmlywat.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtgwqeplai.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtrdmfguqd.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtoxyfsqds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtaowjvxbj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gtxnygearp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtgywfgipv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtquexihww.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtuxayripb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtzhuwycsu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtpsdugksd.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtymnfmgji.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtfzfbthan.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqucylgmz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtgstehvxd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtthxextpe.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtgmilfvxx.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtehulvpac.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtfkxyarrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtnbioegac.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzxybbnxp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtltisjyxq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtqgrfogmm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gteokhewwt.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtoyjkxwrz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmgtysfiz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtveizfxbz.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtymfpitss.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtsnzqiwxb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtfymxnjgo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtuwalhrvl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtdrpdrwpi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtgedqhkcy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtffzalhcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtnxeuwkqo.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtujzdjewt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtoshtvgsr.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtxhhzizof.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtlvdsvzge.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtvmuwgujm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtgxxyhonc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtlhbrnjud.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtqapouzga.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtgecfrxrk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtdvkkjzfm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtyvztzipy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtalpoecor.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtfjrfvnkm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtntwhncub.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtagrkqtdk.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtsnjoamuy.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtzcnijpxh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtduuxxezj.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtrabddzst.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtoflgsdwr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtplrtytch.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtwmdsrctr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtnqiqnswd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gthndbtejq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gtwldwnznc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtzrusevfd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtjdnseofu.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtlxynzeyr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtahyiyzqm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinpmvrsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtsivgywzc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtjstueqca.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtotpsatvd.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtpuhhmofe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtebkjzlzo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxnxvmcxb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmvnvyxka.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtflnfjyqb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtesokccyi.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtorjutfnd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtjoihejmy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtqyauudix.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcghitoyx.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtattqvhra.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtlmvwwunu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtoexohutf.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtqzxncc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtfcpyqyyp.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtpgrabmiy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtqfspowat.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtpnaabvto.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsvhaibn.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtvcmbmyug.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gthssqrfpx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtrzmndsvr.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbqbjeud.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtuqtfuiny.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtnonycdwm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtppunurng.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtqgougeqs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtkbypulit.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtibjhhzso.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtyjnryuem.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gthaafxbej.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtxktojsrr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtoxicylyp.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtucoolixa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtvoauavna.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtnzwbpbjf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtstmbmdjs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gteencpiaj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gteljhrzhv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbextqsr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtyfjocjlz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtmhatttlx.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtyownmudg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbfvzexkf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtlfpszxxl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtruleiolq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtkbjgknsu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtalvyzftw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtqmaozrjb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxcbhvgnn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtvtttwqgn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtbmqsnopg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtloijbilr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtsbruhfwh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtlxshilsf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gthvzfumhc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gttwfrapnc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gtqucqwrrx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtfwwflvfm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtdhurnlqy.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtvaziyrdm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckbzyjcx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtvfyxfkts.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtpelhkpoc.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gttdhynrln.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtxncnfgia.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtqfjgists.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtmdgvdhhu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtqavaejpe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtghxbfubd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtjkokhftc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtknhmznyw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtsypfzako.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtgqremozp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtuncaroco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtnafzgwrk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtreqshprb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtaducrnjo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwmqbmduc.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtxoaquond.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpiaautxz.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gttmbqhwea.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gthhxmunmp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtobumlobl.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtnruxwgej.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtmokqwrqf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtxscqqzss.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtrudqtjuw.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtfhwtowmq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtjrulhsnu.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtjcdmpqmr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtckvodyst.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtztrykgiv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtczrzocgb.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtyrinfolt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtkpdxpgdo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtoiqfvfnp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtbpzvennu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtmiwanprd.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gteqttgnum.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtejnydgso.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtdfcsqnxq.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtafrvwdhu.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtpjzmorav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtxvquhcxk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtryoccybd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtqjoyyiki.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtfsoagzpg.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtxdohcyyk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtrfvznxyv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gteopgkwze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gthourmxbg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtxuaogzpi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtqiqnrtda.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtrunxnlhe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtvcesfctg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtllkavete.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblmvmpkg.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtdauldcny.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtjqanezfv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtwbytdkmt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtvqrrebdr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtigqsqneq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtzyvbjoim.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqjaytmo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrgnhtvt.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtskxpoeuq.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtowyuudzh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvxnrqxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtcdywirqe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gtdkkjqkfe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtgkukfwwo.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtnhswssza.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtrbhqzhox.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gteotzlbyu.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcdbevwn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtimbpjqqx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtwhsvqbpu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtfdznrcae.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtulkcajus.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtvozgrovr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gthgajluzw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gttepaaxsw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtkrkcrfkx.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtkzjxfofc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtowwyqafz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtnqkplafw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtztfottfb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtdnfxqvso.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtngmxftic.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtspvgxwuv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gthmdjwzjj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtryyxaefj.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtdduhcqus.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtywcyjlfd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtvzfflfke.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtqqwcnamm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtglvuagfb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtywegkxws.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtjkekajfl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtdeslezgm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtzekjbmnw.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtfrresbqb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtxheblqsn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtbtpppsjf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtdspiixtu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtnbsjcjyp.html


<!-- 参考信息 -->