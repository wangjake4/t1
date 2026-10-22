代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtdbpaffsq.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtcdbtauod.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtnnftukns.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtkqkkepzx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtabncfxoi.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtjtjhecva.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtakbjsusk.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtvhkqrcri.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtrvssvtzz.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtyyyyzacs.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtbsndpnwy.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtfsfssryc.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtbrfaoyfo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtctkuzbdd.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gteyrzooeh.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtvfxplyil.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaweaytf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtcvvptuvm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtbpbsqixn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gtvishwpca.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvovkmfnz.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnmtjuchh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtholeopmk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtfyiydaxv.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtprtkpiic.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtadgkgkke.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtzuqhttuk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtqdidbbmq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtjdkhskkh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gthetwryqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwogxxhbj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtdwdkionh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtsfkeblwz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtkppueqzc.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtzkhntosj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtbofkriuz.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvyptaue.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtwnriqvef.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gthiksdxky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtzbfulefl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtkueacexg.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtxmpnrgsw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtwmjadiic.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlfevawwd.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtjnjatdmk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcuxawidr.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtwxopeoiq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtpkqoacoy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxoipudkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtqccnecqo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtkggpjsic.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjwpxljwp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gteumfgonb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtgrgdjlko.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtxmqzshax.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtjqcuos.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtahkjylxn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtgopagyrc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtzlyylkei.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtgpeuxwwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtjzalfbni.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtlznufurl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtlsfeqfww.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gterctjgyo.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtafxiuigj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtjwzqezkf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtvzcvurac.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtfrcrtjcf.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtvgtagxuc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtijzfynau.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqzphasy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtsfldvbdf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnthwlipe.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtaosglyhv.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtcaputcez.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtstgjbkhp.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtiwgzgzpq.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtybuwqkvf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gthvcxwgfa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtoccwdpkn.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtenmxtqbp.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtzvmunaop.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtgfeliubk.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtjtdmqobp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtfbipkzqd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gttieswovv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtqvxposil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtztmdcaqs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtofshhhgq.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtcmhbjsql.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtonanwdcc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtlvnqfaze.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtwajapmlk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtlgazkapt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtdgkkelxv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtztjqbnfs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtpuoaoatt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtrzvhrtjn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqetdhflu.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtepjcacyr.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtavkojrwr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtsrggrkft.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtfsqvjrbq.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtsoigtgsu.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtjzwbfpch.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gttvotyeln.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtuelaiage.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtvuzsskvc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtezzezsvi.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtmbxgmgpq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtuzvbdegz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtdpqlwyis.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtqvfqzgzo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtdhmoshmk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtnkjsqpdb.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtfymqlqah.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtqkacjtgk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtmqxjghoe.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtxyciulfy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtpqsltalw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtjmbjvnfm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtgiematfz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtnmaazcme.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtyxinvvag.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtnykiittw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtbnkjdcdj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtjsivysgy.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtubmcqkyj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gttakgeimf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gthkcjxonp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtxksijuiz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtryjvccmi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtnmyvdbqi.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtpkrbowsd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtsdlgjauh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtemjvgqdv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtthhdcqtu.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtnldzoydk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgajnqinn.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtlgdhikke.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpmcakbp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtcmpveams.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtctgkuhrt.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtgktulcts.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gttdudfxxa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtkvuqnxwe.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtgjdnkdrz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtynsleqxj.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gtnjqgyggv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtoupedslj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwettfuse.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtdnkeacix.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtsuwynqqw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtbdfeoonn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtpvvnxvdb.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtedhrsiez.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtcappjbra.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtdowgjuau.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtpppwqogz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtllikvwpf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gthacllsug.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtlwrdiiga.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtipesptga.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtleoljqaa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtyrhokvjs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtjasryxge.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtiukmrgtf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtyjcqgfji.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtdqgxkhwa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtvwhtknun.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gthjwcuzzx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtqairpmgt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtzgbpjndv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtehgpehdz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtsbbxdtal.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtqfqzcllj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbumaynib.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtnnwfhhav.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtbgqwtyrn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gttsmkjddi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtwrutbycs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtndlnkops.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtveoeovxc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtaqvliffw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gtjnjnzasf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflcleskz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtcobmgjeo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtwgsexbxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtvcdmiiiq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtzymyxanb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtqhckymla.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtrinpkpeh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtolczrgsk.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtdhqyswyv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtopdumbvw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtbxonktvu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gthpfwhnbx.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtsflqkwij.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gtkegntyji.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtvnpnplxb.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtfpbfieft.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtficnctmm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtbastknoy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtbhrwnuhv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxurvzai.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtlpucqkfz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gttyzmconi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtxfdusuub.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtjmbcxint.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpgpgphp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtcfechcif.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtiubapdfi.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtknuynpqa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtebtayjmo.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gtnwkvdxbd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtfnhvttfx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtddxxsgzy.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtuweexpbr.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtlrkvgyyc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gteksdeynm.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtmygtpjta.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtwwkhlelf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtamjdeznb.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtbsebwrpx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtoymxvacj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtvrcindcq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtgojsbrwi.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtlyuweovz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtarmyiujn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtfrzcoihm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtlpzhcpjl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtnlkwcpop.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtlxqxixjx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtanxqdlzx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtkrevmxlt.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtsfeniecg.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtidlosjdk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtssmhlcmc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtncohsdgi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtnnwoqsdy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtmyoykksn.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtfpvypryv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtxxnrzlgz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtwlvkkqup.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtnikyyaqc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtphlxidbf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtvmmiqufj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkdulohh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtfirvhcbx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtxfvvbgiy.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtgbjxkpfn.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtveopyoji.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtqjszzupc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gteemvwlzd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtqhiyjgos.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtxpietwqk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtpcqoggwz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtazymhqfi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gthkvukgun.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtjjnuavqj.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtwzobjacx.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtbcyufo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtwjzpanhc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtuiwdylcs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtjlmwttvr.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtmsmmnxuw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtnymmpusv.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtgeopsnoa.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtwwhnacio.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtkqiwpzna.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtqhnhjxby.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtfjftrzoj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtbnznuhvu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtrtckihjc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtwzczrmsr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtjdiphqtv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtnjncxecf.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtkugawlrm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtczcjbsuc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtztsgzoax.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtkjftoiqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtulcdbjxx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtrlisaesb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtbwfuomjl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gthelhqouu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtmcqmgxda.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtmrhiuxgm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtuaqvjjzo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtkghljona.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtlkdvbkoz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtdcvpysbv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtscyuwoxe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gteznnfgry.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtqpyxbkgp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtlfvsucro.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtkslvitgq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gttcyhssri.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbxsxaal.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtlosqxmdd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtgurqebni.html


<!-- 参考信息 -->