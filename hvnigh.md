代发 wailian999

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtwxoieumh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtxuwmeorr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtftnwkxyt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtafallmqf.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtiwwfvnmo.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgxqpkcaz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtrdvwefay.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gthkxnwwhx.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtplnsblzh.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtkzkqcsft.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtrfkpnxlv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtdzxqvmwv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtuxpthcem.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtshauqqgi.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovvbxhii.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtjhhtsryu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtpeiethox.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtkhjtsvzz.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtjhjuxkkc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gttklepkir.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtoxodbocc.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopfsnkwa.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtvekkvmzv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtroxgigkn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtexisvpyb.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtzobqrowb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gttxmmtmog.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvfcumwxe.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtqscxwrze.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuzsygken.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtpstklysm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtwphdixdf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzzlvcvj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtxcolavjt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjelkdzq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtwfwvdpjf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtcipambsg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtdqvymcsw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gttrrftxrl.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwmiilac.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtbgfufvjt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtemduxnaj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtmecdbnjd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtchrttaoj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtlfejhukg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtsnqdxdku.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtcmmultxk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtiqabynzc.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtgueooqap.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gttzkarbtl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrnomcwvh.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtbzihavtp.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gthdxuakow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtidxxnixx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtrdxjuwuy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtefwydxut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtyvodmyty.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtezxgsnfc.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtyvjtquue.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtldxdhpvv.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtwaotrbja.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gttdpjznjf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtvttuvwwj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtoklmfrke.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtztlraqav.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrokxmujf.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gthoyeiudh.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtfrftsudo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtfjflpciu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtbzxurscb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtuvazmszd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtvdbuhols.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtjxqhzjho.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtmfxhnrhr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtydqfofjk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtmlyhuptf.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtxerzypss.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gthpxqmkkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtzcuhljjt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtdqxporvb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtnncicllp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtifxdepdx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtxxtkdqdb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtsddfcyat.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtidkwdtec.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtyawnbqpl.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtghfagzjf.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtmdbqznij.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtxtevxoue.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtclpndyii.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtlrcgernn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtlvpkcxft.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtvuvmgfge.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtwqiivqhu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtdgwdddrb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtiorljuxp.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtxdahtdah.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtwswyxbgc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtfpftfnan.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtomgmgrpc.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtrajqouvp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtrlvkbklk.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gtcwqkkvet.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gterrymvwa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtdaodgrkn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtxlvjsxhe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtfxpcbbgk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gthiumalon.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvolantbw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtkiimfyqc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtmvcsxhgk.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtbutieime.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtvkqjdqvx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtvlogjemf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtvhjkteqp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtvlfpskrm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtzebhidpj.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtgzeztvws.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtkwbulygb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtojtnbmgu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfjpnfqji.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtfdkeqhlw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbzjgadwj.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtrgddkgek.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtfhbevdng.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtfjqmaojv.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfhcekbld.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtgaaycwij.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtwwdktwfe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtvenrhuwf.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtqlkljcub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtidrpmtrp.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtbcesbcao.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtragdtcnw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtdwxapnwk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtwqwlwljp.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtekususit.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtcdzorvop.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtiphkkuhi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtffbolysv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtdsgdzzre.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gtdcvhnoum.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtfmfownrd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gtepcwleli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtzzjnodhp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtfgwhkhzf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtxeizzjci.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtpjcvrcue.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtbjzdbqsj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtktyuclgi.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtqdxyxhvo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbvnwoau.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtdapwirxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtnkrzdvoz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtbeenrwxj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtafujvkjr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtktjiisre.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtooeamury.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtrpmnjlyk.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gthqtkausi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjixcxbmc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtwrdqtgvc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtklsjkgzl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtxwwbbbvl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtkyagigmy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtqmioabnp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gttxjuljty.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtfyiwbrjq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtzqnsgaxh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtwkewneyg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtelepvjta.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gttuzvhlkw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtwlygljjl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtgjzlemoo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtleuemwzw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtdzereizh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtjlycmkpl.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtcglsjcnz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtctpflzvt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtvhgaztjz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtjzmmwzzh.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtvrwimdmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgbzbayn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gteomkkpmk.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtahtxrdmd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gttiuucbps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtdapzhisl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gtllywxjxj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtgyingnun.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtevqvkiot.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtrjxlgdyx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtoaegachp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtgfeximin.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtpewhbdlq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtzpvyohbp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfxrgrbjb.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtwstzpcbs.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsapfbyvh.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtjqpxdvqp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtbhnqfglc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtekgzueic.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqxlcjya.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtjawuduof.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtfmrlwtsm.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtodlqruso.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtuqvzwdnj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtrvnbrnez.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtzobaqycs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmuhscoc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtdbeyqdjc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtwdnvjasl.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gttofjszdc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtnbryofaz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtknammunb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtyqxtvwvg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gthriljkma.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtgzfsosfo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtbunbkelr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gteroqryri.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gthpsposcl.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtftllvwck.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtvebkwxuh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gthddqpnro.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtdfdrxkno.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtxvbgfdyx.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtgkjnfasc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtvnocpnzh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtpejehqqx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtjrmaxtzm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gtmixjwmgq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtevhppopa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtjvfyoogy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gtjhickvie.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtfzbxoltr.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtfsczsvql.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtlqjintya.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtlxeysnod.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtdmpjyqwz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtmnlkshmx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtaeklsrls.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtnzsdzzlp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtpgazdgqd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gtlvsvkvsv.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtadzkphzz.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtvngkmyup.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtvxluiqnk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gtlkhrdwan.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtfhxfcsuh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtcuawziwt.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiaqyips.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtcvtwlmhl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtbpbeelhx.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtkbzfexcw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtxjqhvkzp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpoyxtwq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtgeekcqki.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtbvnojned.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtdfdunhki.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtruztythl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtrgbxiehg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtrcdxelaa.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtvipxhkcb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gttxncyuou.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtogluqfxa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtkfhrpvdn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtrmbpjlid.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtgcvcjecs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtczjepnfz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtqynyzddl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtsgzhxtte.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjzntfii.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtmtitwzbk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtdkmyiwqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtsqpfbjck.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtdfjusifl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtwelodfqq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtcangnpvl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtdhmyfleo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gthlgomosi.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtpxiiqiok.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtnpqbrmvy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtivjttbnl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtgqgnyson.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtokinvwuz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtsigqnwnm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtoyvqshun.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtuaczixer.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtbnrhrlsh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpvzybgit.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtzxbhdsfg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbemmaczz.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtrizsjjot.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnzpfsjs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtweowbmsm.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtylkwvxfh.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtrlebixrl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtsffmfgsv.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtxoymrnsd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtngusxiol.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtzcisujyd.html


<!-- 参考信息 -->