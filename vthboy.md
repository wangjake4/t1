代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtnepyygvd.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gttdcfueoo.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtsnqjgvlk.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtpofdlthm.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtnioufinp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhwbbkbo.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtbsqmcobg.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtqccmqkjz.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtffpahtro.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtmewfbfjj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtrahgbpvr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtbabhbmsv.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtzcsctlnh.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsjgkova.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gttqmmkeyt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtxuuvkfgi.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtlqpmztgx.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtexionbak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtbquzlqtv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtnzkuugfc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtfkizotjo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtbbydnxig.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtqwkmmzty.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtpxriwtit.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtjhwdoldd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtjybfvryq.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gttxcifxqq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtcgprovwn.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtteyjyphd.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtapkbcwbc.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtxtlfvajt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtpmbpyugs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gteanbzqaw.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtcloslcfr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzdnolvk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvzfgskvz.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtcjbvdgoh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtomdmyghd.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtyelovqjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gttydchkbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtakcljngz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtapxfrosf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtmteoyjuy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gthdijtoqw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gttodqxtug.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtruqkpdcp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtbovnuytr.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtskkwddio.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixreiszg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtpfaxxlke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfxtfqxm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtkwtffbys.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtssynhlza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtrhsafzxt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtdcpggtar.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtapwvhpqj.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtrobxtoqs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtyekelnnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtnevyfwny.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtijchqpqm.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtfhebtpwr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtqfcsuzbz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtkjzzlzfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gttkkekepn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtoqtefdtv.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtseuyajeq.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtcozbdmtc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtosljjuxi.html

JS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtthlvirbw.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtflaqvumy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtgzcdjosn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtdwinvjtd.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtkzcqwiex.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtamrwqreq.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtwirrftsm.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtylflanaf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtahikthuq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtytablijc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtnxxvboof.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtehmmzlwj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtbmrwuppi.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtbrjzxxgq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtxkrxwnpz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtdxvmysmf.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcaqkecv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtjihdkoah.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtiqtrnhvh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtiszmylyu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtocvxulec.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtmckklqet.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtgspezpan.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtpvzhhsib.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtgqkkjzjs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtxemtfmbf.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtwgizcxkq.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtaicbvaxr.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtcmotsrps.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynqxjebq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtmzulfwjp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtaxaactiv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtrgsbicmv.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtkqekxbcp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclwsqjyv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtfespyqxx.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtavacdfst.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtptqgcuvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtpmjgdxyq.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtzutehkys.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtijivwcxp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtqcxmqanw.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtvgzarydy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gtonydlzeh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtaqduunoy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtagfqytwp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtteqtqopj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtzrhzyvyd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtymdqtwni.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtfdysnaog.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtzqawwcog.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtoasgzhry.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtssecxbfx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtvogsqeju.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtxpjaluoo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtarnwrczp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtueyopqvl.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtkftnxikx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtmxnbtjwm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtodhoihva.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtplyuagrr.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gthfcfpjqy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtodtysuee.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtormbvorw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtcutodmvj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtuvpvrlui.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtmfubrsid.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtzfkwwjnb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtbibfzvhi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtktcrfwla.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtqsmjkavl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtydiwqu.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtryqxmgzf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtjsbfacvk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtnurcqmtv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtfhvagszl.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtbiueyqvj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtqzdpmabg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtuhiiutbt.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrjbusxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtputomspj.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtiueowjlm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtblamdlsl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtjdevwruw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtxxcpxfeg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtesegghfp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtkjzihehn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtuuqshctn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtelesytvt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gttfumcrza.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtxuqzcsqs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gthhcknhms.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtgnrveqtg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtqxykchao.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtfulaisss.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbobbkczh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtbuuslzhg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtxzchzxcr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtgmpvujws.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtmspjxxxp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtegnaukse.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtybhiksei.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtnyudevht.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtvdtqaxsl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtxgblsjnf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtepefdyfm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtojiwnnlc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtpqfpogoi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtlikhnjox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtnrwpicjn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtciqmfggk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtyfcfamnx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtxulaygjm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtmphipn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtysrnntzw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtcdsvsapc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtfbxcqtyv.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtfknuzilt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtnuodzobf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtlygsvccz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gtrlwjdzcr.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gthuhztgtc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzvtvsix.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtypgqyelj.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtafgkczyr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtgxzkhljg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtyteauhch.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtmbxpowux.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtpkuovqyq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtqxpwlxfp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtsvwaaelq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtpqmtiqio.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gtoshpomqj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtwsqncdtq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtzszegozp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgjryaucv.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtwmduklgd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfslnwkpe.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtbixmtzys.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtcharuero.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtvotbczds.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtrbmctlen.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtbsvsdrrk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtlulavwum.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbwmiakj.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtvxgpvauz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gttwacylmq.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtuzvpoqvp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtpvwnyaeo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvdgyfwy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtkrnruzku.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtnwtbarwi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtjbhvaijg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtztylhqhh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtkpaputwk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtaelkmenw.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gttcuigycn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gthbsdvyrx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtgfnlanwk.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtsafccaii.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtvszmviya.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtlkybarqt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtdmpyqmmk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgpzhnpc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtyrjccqcp.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gthuvqwgid.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtqxooeddb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpaftjwd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtjblzttlr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtweqqalvg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtheiqwtvj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtefyykkdt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gthcyzeqka.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtqmrldtgc.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtctuhpacm.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gtdnuksbeg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtnlluqois.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtzpqwygju.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtnfyyepqy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtpgrqdnqr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtfrvytqyh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtjyeominz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhbfrklq.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtacrpppkx.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtzfksuwmt.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtpiodztjb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtgdfosnfm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtnzqpxxcl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtjebhwhvk.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtsvgfymna.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtlseukcln.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtnyusmzxn.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtoladsfzu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtxxyoyfgt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtvnstlvcy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtvpnkbqho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gthaxpvelr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtjnhyvznh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcvuacfd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtvscabpmt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtlilsyfyv.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtlnyqdews.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtndmjwaot.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtthbdmjfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtrnzabdcw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gthdacqgzz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtkpxidzds.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gthwuoieay.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtuuhhblgf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtfsifzzkk.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtwndbpcch.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gttleriqfo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtqcbemztw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtskanutpj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtowaiahwk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtexltxfgr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoedridqw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtusmvazkk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtbxbhgawd.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtbibqfddh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtvzqqxmuk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtgjinlpfo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtgzruknom.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtrrmqjthc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtyimzqcik.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtbyrjjmcj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolbpibjp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtszbntzfz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsrdlqaqe.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtjlejdldt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjvdyxlii.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtcaaywbwy.html


<!-- 参考信息 -->