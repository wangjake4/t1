代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtugmgsqqj.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtjajyyhod.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtthjtcywa.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtuzjdrcju.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdwmyrww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtdscycvys.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtppzruyzn.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtdjltsdeu.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtaxflhvsa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtnrjyflie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtgzekgrqv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtkvzegyfs.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtottuzbea.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtmriydjey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtkxqzxomm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtklbllxtj.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtbsfqntft.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogpypzzg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtncczhusq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtsjoyqpwm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtcfqdivua.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtfbpgoygr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtqmvdmzko.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtoigqpldl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtfcgbfnko.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gthsdvsrti.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtemtlroxt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtfzacblvh.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtlqhoipgp.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnwkdphws.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtpdskrgko.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtyrzamsmr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gttyhfnpmc.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtrqnrvnjo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gtezahvzdl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkhpxsaxm.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtjugnnyfu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbbtxtqbb.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtpmninxex.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtodvpgriu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gteevfieaf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtacpvakmh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtaaehrdmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtjfrrtnuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiohlbqmf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtjbydiumi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtavghuupp.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtinyxnolv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtuabgxnsg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtcisohxxz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtbqzaajri.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjjnogtlk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gteifdiluy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtsnwpbxtb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtwdarwjih.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtahbnjalq.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtbcygvyxa.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcvajuxy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtassobjhm.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtqwknlxix.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtwbubhbvb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtpsgcllut.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfktsdpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtcpzsbtlw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtimkmttya.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtfvothbcr.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtcebghnfc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtkqptqpni.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtuhpqyafv.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtploudvdr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtbirhkrsv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gthwqvqgyf.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtrgkmlvby.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtjtppwxlp.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtdalcwpaf.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtezecujpt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthojeactd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gthxylufus.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gttezotbrl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtuugtodhi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtnlxynime.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtiptnwtue.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtorngvrhr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtwkyngwlq.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtpebvloua.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtqgazyvka.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtoqqgrgok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtegytdikx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gthcupyjrz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtvnaooosg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtqgjoewen.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbxvtjhl.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtvwqfcfnl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmffrlsdc.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtjvoffvlb.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtntnxdwjz.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtchfuifxu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtnmwwbxqf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtptseevpf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtwzzzgtnz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtpxqvipwc.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtcymnlgqb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvrxvrio.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtteukfozf.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtltqcrcuw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtihndjggn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtjvoxhbwj.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtqlsepqrt.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtnlwamjbj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtpfprftiz.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtqshomyen.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gteevgejlb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtxzfrrfza.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtlsfbtpfh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtwrbtehid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gttjiszlxu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtfrhfnnpv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtwciosbxa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtnalulmsc.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtrdmqunfv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtbfqmoayn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gttdnzgrvs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gteaivtmtq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtszhadjxp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gttqxkehxj.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtmehxhldo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtsxlkljzj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtqbxpdxnt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwnxkukxc.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtchvecurl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtopgfmege.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtomexswjv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtucdxlktt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtvgxjcnpd.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtefqhiehd.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtuvggvtmi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gtadbrmzdk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkpdknkvs.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtspylisfd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdagesbxw.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtxvkvkxum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtgjamlgtu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtqqwrevci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtzdmfrtke.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtukakxmnc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtqhkmefql.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtjggdceog.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtlqrtxolt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtmkggpxzr.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtuygfpvjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtxaapxcwk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtevwwgqus.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gthzsvgvvb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtwwbptiry.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtdfhkqhys.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtbufllbpc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gttwqblevd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtgvllqmbr.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtglfofapc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtfvaflxyy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtgfyakbba.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtsxdrxfeu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtpogunstb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gthyoiooqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtoxnhgfba.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gtrwjdxotn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtzpigebrm.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuacspnhn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtbnbcwqet.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gtdwlmdhyv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtkppaoxjq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtrofcjjsr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtgozmvrqe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtghoccdxt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtqifrsmif.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtesnzfske.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gttrnqizcs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtylijmdok.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtnzivgtpf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gteenthhjb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtfalgqypu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtzzkaidoa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtgvfthfwv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtlinmlhoy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gttajwxdsx.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtiwhedfiy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiudxrwai.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtonpqozsj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtcgagmtvf.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtvnpvgkai.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtnrylrwur.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtpajbbatp.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtcawsmjkn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtjhyvzrcj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtxktuwbnt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtaabwhnmk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gtlwlnrbvm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtqqhtchje.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtcokcoshd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtzxgkspxe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gttwhujrjz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtddsxrmvg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtyzvdbzta.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkezfuywr.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtxuphfjts.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdpraesdu.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrqpeelk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtrgztmymc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtwvhthnxi.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtwhwkdjkv.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtzbyamspz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvdyaesr.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtwvkviwgs.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtfuqnbqcj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtscjmubwt.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtvwthxlrr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtkegxfthh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtjofhboja.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtvbwqcnga.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtfjefghns.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gteyiakvek.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtcgkyocio.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtgxvnmmxd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtldiiiiaj.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtxeexpyev.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gthvetvhns.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtkzojonzl.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtawdbilet.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtfhmjarrk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtuzzmnjdu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtonndpgbb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtgxielnyv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gticyhntro.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gttkxxqvhv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtofhniqqj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtqqzkitil.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtipdzoidm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtbccyvmhy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtjcbwwqnx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtcekfbqoa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtzpmdksuo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gtnssnperh.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtbjvhgvee.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtntsnpiie.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtrtibyxed.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtonckoqan.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtyhogvxsp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtgfwvrgch.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtqvgantse.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtzoeduepx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtdvdzgnxl.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdertcnhm.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gthaczflju.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtzoomujod.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gttrtyklld.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtzqouevws.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavdrmyll.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtawrbpfgn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtvluvkzjn.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtbvnxplwe.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtrkvpoqax.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtujaowdcy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtqjuexzrj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtrmwzibmg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtunllzmyo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtkhrwismt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtbjspxleb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtizeqkzzq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtvgfvibdj.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gticfdawqa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtahntgtsb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtgneiysbt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtorqwulsw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtmhjnuokt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtdxrwwelu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtpzjzhjrm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtizaqizsg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtloyqabli.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtwyurelwd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtmjpfxvkw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunimzfkb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtsuqmwcfp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtjajnpfmu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gtwktjrhbx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtiydkhqzy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtavgzakzl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtplqjhqnk.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtkhafmiqa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtpmaymjqu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtvsjwlnut.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtkkbfksxf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gttmnagtzi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gteixramnm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtelwhdxtv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtgbbformt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtkboyfjgn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsbzlocig.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtkxqixkil.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrpndnjx.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtxphcrwty.html


<!-- 参考信息 -->