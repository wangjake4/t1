代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2cebrldca.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2looziqiz.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2bsbqgghl.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2vevsffld.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gt2vdyiriti.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2zsxwdubp.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2weyfnqpd.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2azmxfjyv.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2gwpbbjpx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xruxuwaw.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gt2qfngzkcs.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gt2yrryfnsz.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2lmivajmd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2xlzibrks.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2sancbfzu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gt2unipjkxe.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2myufrrsf.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgewvdms.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxwaxdrc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2phtldsux.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxsywplv.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2yuhhwfmf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gt2csfxmqbt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2xweidvil.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2jnmielwh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2yiblhbax.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2ivjaervr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2zassejjd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2meggfdux.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2fliiyrxz.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gt2lswmtapb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gt2thlzehcv.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtyqefun.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2qfbjtcdc.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ekylcjag.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2xjsezmph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2yqbbtwbx.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2vdddvorf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcexczow.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ksbbeblw.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gt2jpkqsttv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jjooqwmn.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2qvoeztrp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2srswejnv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2kvdogjfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2lzaltzkp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2buaisbze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2ccknnwrq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2ewavzxgi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gt2fmdxhgsf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2dikhfsvg.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2waqjoiuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gt2tudamenl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2ednugiwi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2syqwwxya.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2rvqqnsnu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2ctvyejly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgcgfdko.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gt2rdreapgp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2ztshkjfl.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2veznfyyv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qedvlfcq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2drmvoxhw.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2mgkclamn.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2sjoxiscy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2qvzlazvi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2lavioqta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2uubanxvu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2zinestlq.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gt2mvbunmgd.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gt2acgfbbys.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2twffucnx.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2pnmdoypl.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2dqfuwatu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2yevryuds.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2flvzfyyl.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysspcdvd.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2rsccaatn.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2kgzvazvx.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2yapzjtso.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2coydhdrq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2cbujpphn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tczprphk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gt2bvmybrsu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pibrdyvn.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gt2xjxxverz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2nmvgvkpn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gt2ypmgowse.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2mdfldbtp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2rumrtofe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2syyflnmc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2epdtdevn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gt2zgriueld.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2yaefhbup.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2ctkwttwr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2iptehrud.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gt2ewbdjqxi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gt2hsxgutkh.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ukswyzaw.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2usgfqvdv.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2enefmsjv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gt2aqqwddvx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gt2mdspfugs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2yebcwtgo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2chobhoiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gt2rpqgmdod.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gt2aykrbert.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2mmbhbcdf.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2dkokoujc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2vnzkeqgd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gt2orndizux.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcunifoo.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2irsbphhx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gt2xiqogqun.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihwdbpue.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2capqikij.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gt2hbtlxqms.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2gdggvwxe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2bnibjcud.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wkiajfwg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2vgattpee.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gt2gaoxdboz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2hjtzsbif.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gt2mlhpvcgw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngqvcdmr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2dopjkazt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2afbkskao.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnqrxdbn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2igtltczh.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwbyuzka.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gt2zclviyzz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2rwhiirbh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2nfggtfhi.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2qymwbzwu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2jvzmneud.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2fpudhxss.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2tmalonei.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2vhphfomv.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2yytgdhwh.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2efvsqlul.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2kwbrpybh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuzrvggi.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2krkzvlya.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2ltzcrkml.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqvmzweu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2dlddmfgd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gt2gbgbsnft.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2hkaxiyfb.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2cinxlcfv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gt2agaflonm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2najjbszs.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2qxykzjbm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2gprrhsbw.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gt2wblakmri.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2owvcnuzh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2aqmbabiv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2pyagctay.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erhvcued.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2ztwlbxgz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2lnqzldli.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2lhvunlqc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2jlxpmaef.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2ldzhehzu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gt2mziknfvo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2udncqihi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2knsjdluy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2qhjhwfvw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2pcisptho.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2zjazockq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gt2twkippyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2ufezbsmc.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujgqnuxg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gt2bqzyjmsj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2wsreaiae.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2pctsqnir.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2torxyduz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2tpcunvky.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2tetsggzj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2dlxmsvgr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2hzuoymrj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2dmfhsgvd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlbmtanu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2wgsuulvm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2xpysktoo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2lrrflxhn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2txtgcohj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqlxifzx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gt2uapauicc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2fpheczel.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2afblnsij.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gt2zubockkl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2lzcbxckk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2jyzifepq.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gt2huyskitx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2wskfcmph.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2kytslgjo.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2syaijuwc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gt2npswmvzv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2hwszrirm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujxkdyud.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2pzldqroj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2zyolwhsl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2xpnosomv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2acvjgexy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2ipuekxro.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhrqcuwo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2flktvxvc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vfunmlxb.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gt2yuybhosu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2buysnxio.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2pyhbmsvs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2ycjqzokz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2hwlagwla.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2eudxnkgf.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2bspovdpj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gt2vnrzzpuy.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2mmxvyman.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2tbbxgfdp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpwwbhes.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gt2hjbwnvqz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2bfxctwzo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2smwflnuo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2cpymyaqs.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gt2krlolkwi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2uigqqehh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2buntpzvx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2tbhpgwsk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2apoxurbt.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gt2ltuxylcf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2rdavgqtv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2bepfwpcl.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2lhekruoe.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2wokpfdze.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjbkmrxk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2bebesyvn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2lbkxwoti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2wqpebvmf.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2jguddwwp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gt2mhlvidqd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2pldnyqwv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2zujkamxc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2fhzzqsdl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2atitugzw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2wcwrbgpj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2jfjjlmkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2uhhynifd.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2svlbmuha.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2rihmrjmj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gt2wlqhujei.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2vglqqmtm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2gdldljbw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2aotjykkj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oljepael.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnjwlwnu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2ydytgpxr.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2xhrlniav.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2jcdagpzq.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gt2byebnwzn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gt2nexxqbms.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbrzbdfd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2ibrvbkyv.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2sktqteam.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2ufafnpug.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2efnwtwgn.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2xxxsiffs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2zdsowlat.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2zkdcmkhr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2aygczfpa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2zlgyfgpa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2tmkwzepo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gt2fuyeneux.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2dukutkft.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2xvanziay.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gt2applfhib.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2ntabqerg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gt2roimioao.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2xnhxunvv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gt2prhducpp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gt2kqmxoivq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gt2gunhwcmm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2eqefstet.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2ukmgesub.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycinlxsq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2fqggwocp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbnzytee.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2hspcnqxw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2ruxcxzos.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sylouwjp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2hhcvfbbj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2uwlzzwjv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2yvimbusv.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2fiucnfmr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2ltzrqpia.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpcqbaqu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2kyjzsfty.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2imvctlnx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gt2qedotnyd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2vedljgpk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2jnzuqotk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2fspfaknx.html


<!-- 参考信息 -->