代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtmwjoioxw.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtumwqfpyr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtagqufbek.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtdfjqmaet.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtoxseoorb.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtpzvgahmf.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtyckfavhu.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtvojedxip.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtyjazzzbi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtoyaeuyxw.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtlwozuhoq.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtzysqyriy.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtudijbhif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtjzvzxyfc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtnahmdxez.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbftcnibo.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtyvexutvd.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtjvfuizlq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtqkyvxmah.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtqptzvuks.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtkjcjozub.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtkcjrlvjg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtyaxjkhbc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtcaafedml.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtymnihfrx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtgrvyeozv.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtmzxmcxhb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtefeknkrn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtzsgqjtrd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtlmxqwzgd.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtlqxmszci.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtswqmqjxm.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtatytmhxj.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtnmobrgaz.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtuldypfsv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtqothftxe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtlxwuhmml.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtlysmqzwm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtunbkukhc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcoglwgyr.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtprsqxcyy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtggkktqxb.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtvalmnnrv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtaushryvx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjfypxrt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gthwdajhcf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtviezchan.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtioqronfp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtlaclcbqw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtknphchwy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gttooqwvqt.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtknaeeoat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtbvaespvd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gthnyyuroy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtwgfpozwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgszmmypf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkywznvs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtkdyldvxm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtmfvbvfhl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtbniaklzg.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtcbfllucc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtwnskngqv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtaetnzmub.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtnzogzhgv.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtewywyrmd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtekisdjad.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtfpxlcqhk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtilguyyec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtkyoflvkn.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtwbayjghe.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtxpucyfop.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtabpdykwt.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtoznmwhfm.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtsmuxusdu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtaxzhqidd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtgnrivsiz.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtlextqybi.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtmwriadye.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtxxumiphs.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtedjrcvcx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtvdlrjrwr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gteigrazoq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtdcktbkow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtjtcqlyon.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gtvqgawgbs.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtvzotupls.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtgombngmn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtwqtyclci.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtezebwggt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtndkmpzqe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtipbngadd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtbihwnsqr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtbvtalyer.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gttxmssfld.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtnyajvopk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtvsellzgt.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtemobkdgv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgykkgvnu.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtrxtcyplu.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtmijiznff.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtuovqyugq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtpnjhridd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtmeiycedj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtrfdxdxag.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gthjhfpwvn.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtearwgcfv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtyxjzkzba.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtwjzcoedn.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtkzjoxpsv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtoaknbrck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtzmlzlfjj.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmizgshbx.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtcuxmcbra.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtyjdfkbgn.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtjuxhxnzj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtqqmtgowj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtbknpqore.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtolcpvxcp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gthjiegadw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtobojscmp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtigrljgal.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtnuywezxf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtuitybrkt.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gttjljihst.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gtjphsaeda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtiqwruoaf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtwgdopylz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtfjcmgzsi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtbvvghztp.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gttrzxktsv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtdpllmzfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtosbsoohp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkcpwhwzu.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gttddubzto.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxiojfktu.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtmtnfzcyb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtkajaqtov.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtjgwomuuu.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtvyxkirns.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtpnvmibxf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtheubkqtv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtkrxtoeku.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtqvhmxrqu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtzrqsvety.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtcmfidamn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtgsjazvjr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtpnjmxqnp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtpnuogvny.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtxkcdjzjv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gtfnjpbvpe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtnvtjrsnq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtmofwbohg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtdquperkd.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtiylsxvzi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gttpmkadjc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtuxahqpyz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtooxzobpg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtkhnzvjtx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtzienpyog.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtowkhuefh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtkuzpaxsn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtnkpldirm.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtpduzmxdf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtutsjzeiw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtsmyatsvp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gttzniqtwl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtxdeswyyp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtocmsizdb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtcmcybykm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtgdnztlrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gttvdgyjrx.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtadtblpbm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtosbozprp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtxgrynrwt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtowyzslnj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtaytbxojj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtnnibfghy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtuzzbluyr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtuyhrdcqh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtqyfamvls.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtskjjtljs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtazxyjdfa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtuzujagix.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gttujiqflw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtxbtbhgug.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtprndxzck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtkwmaafsa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtuvlxpevs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtkfmnzvfb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gthiighvqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtkpwkwklz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtycxfmlea.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtdythqqbg.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtmdqbolju.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgbbkbcc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gthdwefrwa.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtcmwfncny.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtalpkpekz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtfbgbkajh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtjmjsecgp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtrntviypj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtkorxigjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtclmzlnau.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtjwkrgpiq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtajopwulk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gthmdgsgdc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdslhjmcw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjaqdfunh.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtzlauiqly.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnrkzgblq.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtktgzbbfh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtbjqpmkwb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtvqnvqcqn.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtpkokneqo.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtmhgeqokc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtzgzwqevi.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaweqrupr.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtplvskryh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtjamtrajb.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtlebuqmqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtipcoeetj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtlrviqilz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtufrvvywk.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtsgwfrcay.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtibwnsmqe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtpwhpwwef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gttsfxnmjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtwkdpaton.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcgydoru.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtkgnhjuau.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtnjgqvwpd.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvyccifz.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxuobdwl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtalhwbpjl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gttfhonxoe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtzanpmrqj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtdrbgyxty.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gteyuhyerf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gthfuufmcq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gttapfdrhb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gtfolyscns.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtnjhbqkpn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtjtkgcujh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmypggopj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtmcayflqo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gtxnyeownq.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtarlkadwz.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlfvnljv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtyrjfqpmk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtqolchksf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gttcibaxzp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtpzegebrn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaabuuxzn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtezyburoh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtzcfzorbu.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtdylvdksn.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtpdsyijak.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtcdhoykxn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtngrhimfp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gtnqjcbgri.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtcbcrigju.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtmkhyufjs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtenmbsgla.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtsyanupem.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtzvawcizf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gteufbmgzg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtatfklohk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtwecvpdgn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtleazboxj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsowxlnyt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gtumcvrope.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtxmnsjeno.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtxgjfrlbc.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtywtdphuu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtciirtjho.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtqgfinxgq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtxstlkszu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtrseegrrh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtizvckeca.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtmkufompw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtbdgarzgp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtetznsgdx.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtwhzmofca.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtpampkdtc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gtybrnxmsx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtzubfisft.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtbhfcmoel.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxghdpla.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtmyykqszt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmsizvuy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtinyuqeko.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtxtbhloip.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtxnsrrgtt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtszfcbtsz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtstrbrfsd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtbsitmtgj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtnykomboo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtwogdwhia.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtxmzvwoej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtioehsgnj.html


<!-- 参考信息 -->