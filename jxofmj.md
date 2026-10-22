代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2jjwrqyjg.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2dthganaf.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2gpdomjcu.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2ycmcpfou.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2ohzdfzmd.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxzcsvgz.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2hfdrlrgr.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2ivvwbqqw.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2fmavzplj.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2lxddqgfb.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iolpmvib.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2mhybzhaa.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2keecklek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gt2sbzgtake.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrnpmiij.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gt2kdqtnitc.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gt2gwmwxlrx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xofwsocg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hoaigzpo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gt2sdnkbsxs.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gt2eaaoezht.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rsrqcsfn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gt2soasrztw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2rxnmmkev.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gt2ekqjvctr.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gt2hcnshpyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2oesksdnp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2bepljywg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2nwmnkpnz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkvhgbxx.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyluowef.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2ynguswmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpdacpfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2zthukmau.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gt2cdxraalu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2rebhedug.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2mvykcnnw.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2oitjaftt.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2kpmiczuz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2dpmiiide.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2ifqikfjo.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gt2fmjnnopv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2xvidnnzp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2auhjvzbn.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2pphyxpyl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kklvhmii.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gt2bgltgtpz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2jseiakjq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gt2pkxtdsaf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2struxwjo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2jquixtbk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2ctgyvize.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2fuwifrrv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gt2qllkfmyw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2fblnjqyg.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2myxfamil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gt2alvasrdc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2bzzpmboq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2jbwrhavg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2cedfhuvw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2tduvpzqw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gt2ymzmacca.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gt2gizwurhp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2mxkwecoc.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2glpeqgjl.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2adykbpfq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfokrejl.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2egeyffvf.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2ejqtzpzg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2ejotblyp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gt2cweozxdy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2hhkxbwaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2azdybgqt.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2cxxkqzqh.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2nndhhlvf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhajhmdb.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xexvzyvy.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2hntottmn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2mhlydraj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gt2zgkpcozt.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2lsafcmjp.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gt2apwaiibf.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2lickeehn.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2pnqgvmnz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2bkvkdttg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2ddabmead.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2hlfuniks.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vunbjiqd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2cjemnzsj.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gt2jjbtgajk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2qcttgrax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2isuwedtc.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gt2duvbrzls.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2dvpshfzm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2xepogbir.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2hzcbxrjy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2rfnkwtmb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2xdfiajee.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gt2mucoamon.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2dmwmqojp.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2liobfkub.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2ovcotutc.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2nsnwoufu.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2azpnuixq.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2lngffmvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2zbdpfoug.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2ktjfmtnx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2cgjaxjuy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2wpbivxua.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgwbkwuy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2dfejwbot.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrvuiquq.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2xdbamlvu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2bwfioliu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2nxwqmczv.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gt2hxelogep.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2rjaykpiz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gt2qowgvosw.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2ghitjszp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2nvssowch.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gt2qlajkgkk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2jjnjxlhy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2cttnkhbp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jwwshqyw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhvghjpe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2qcipjxwt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2pvsxwnad.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2cfelybjc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2tcewcdco.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gt2vvqpkpaa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2htittwke.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2cinimtmk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gt2fqujqhcb.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2zqrynmjb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eaggzejk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgtmdmmm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2keneivkg.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2ikgdcjka.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2svuehmoq.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2osoltytx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2wgrwttnq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2qdvhqwlk.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2jiooixfr.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2sxnkktdo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvgtggeq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2ovnkvihu.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2vzuniibt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2mbbofkxx.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gt2djwkievx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2zhorjyrx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpslvygb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gt2hjqtrifu.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2ndoggtlt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gt2fszqkzhh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnigmlaf.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2ejmubhec.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqeghejd.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2tgcufciu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebwvxlbh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2ppjssjsf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gt2kvdftyhq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2xmnuqanl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2uqwdhuik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2vmjlymqx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gt2dmwktrzc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2mngrsbpy.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkhybqjz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2julfpegw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2fyutlcda.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmrcpvys.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2lluhavgv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2mtsklsvw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooeovfxm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2tbeeeyji.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2cyjktlky.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gt2qhfcnpjr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gt2etpskbha.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khisygij.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2zopxldmk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2xwszvset.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gt2tzxcnjdb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2skyoasqn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2hjdqdgeq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2sfircgax.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2dkmxxjyn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2ogamsqic.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gt2vadorirv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2zmqmqyao.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhgbnmpb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2cvkysyii.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2osjtsqpc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmzidxkq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2yzuccydu.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2tbedbzje.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmsnbbfh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2mpjvfklm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2ehecixpz.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2brktyyxc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2qjbdwoux.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gt2mishljsy.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2vtxwtfjb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2kamaxaqt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2ztlrqzwz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gt2dlegqcnc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2aprbnrbh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2epsmqgkv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2dsqajdeb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2nizxdjtv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gt2rjkqeafx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2edcqklxi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2witqimsu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxrqrpcn.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2eyqmajai.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2cchxldmb.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2wlzfhetv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2mzpmksmm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2cwdbufav.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hztamygl.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2papmwenz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2zjfwcudy.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rghgycve.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2lgpjvgyf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2ikuckzli.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nallqgrn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2izoyegze.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2egbjugns.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2ddrpannx.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2rfkaqahc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2jkoefhvf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2bwlxfxgi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2vkkofjgs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gt2clzyfgyz.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyqmmqcg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gt2azdkypup.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gt2htdcsewi.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2ctivztuh.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2elofncbt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2oszidcai.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2igvhjyvd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2vxurquil.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2qlkjtdbd.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2ykzhvpqs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2jnlsithx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2renvvyms.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2mkdasuko.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2lugykxha.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2nisytaao.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2yhgvbftd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2sxwlocyv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2gxxtvadx.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeajmnhl.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gt2mpqfoztc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2jpkmltqe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2mwfjwtco.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2ullblzgv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gt2wdgaulhr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2wdfxpuyj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2ucdvbjhv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2svkkuhwq.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2kntrnosg.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbvndqwb.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2pnxuwcms.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2yguaoovd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2qfixxohj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gt2wkvofnbs.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gt2xjncsegj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpcmkdfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2klregmfj.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdziakyq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2waubvfnt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2uvucxbtr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2wyfuxdtf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gt2edsmhwdb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2hoyzudyp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2idbrpbgt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2zcoohfzp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2sknojehy.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2kempyjee.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gt2mbpdmcuu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2rwsnzdcl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gt2wgxjcnik.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2czfynebt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2cgwhsaun.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gt2srtwyzrb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssnrsxhz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytakgnlx.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gt2hkoqabro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2exmmrgmi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyjecngw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2xwtxremp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2efttjwdj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2bxlnitty.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gt2fdxitwse.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gt2sjvnfhkv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2ragaxgif.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gt2jrqegyfz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2ntmonitz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2rzqpoqya.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2rerkrbko.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tahqeauy.html


<!-- 参考信息 -->