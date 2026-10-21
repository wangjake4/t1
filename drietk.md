代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtgtebukcv.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtezaptqew.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtidhlwhnv.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgsgtabv.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtojmvdpwe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtmgvuhosw.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtffnqrevo.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuexmrpv.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gthjspqqao.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtutalaxgs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtzshjgsuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtfolvxvof.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtlswyaxuk.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtqfgkunvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtrwtfghkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtpadhtevr.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtxulsghwr.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtqptgknkt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtflcadplf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtizzseqbr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gthzryjkxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyoawzyf.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtznehpecs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfmwafwx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtudfotnco.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtoykdrkgs.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtqdbhfqrd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtzsgjntmk.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtsbauuujg.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtpelsocuf.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtzssrvshb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtfncpxfqr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gticzsbpuo.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtxuoivndg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gttbqlxxlj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtybhqwwyc.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtspvjqpkd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsvcwccad.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtiukdhtom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gteaphlajv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtslsnvdoj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtlbdyaqya.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtnwkxhwun.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtisbjmhka.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtaswwmquo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtbtgqzueg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtkkjfxipf.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtovxxukaw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gturcztbdm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtnshyjixr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtkghnqdlb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtiocboadn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtlzizcijq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtdqderdgn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtblqpsvxi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtiqghezdr.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtliqcsebz.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtfnhzszqb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtitkgehvu.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtkjghigme.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtjqvzocgu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtjintkibk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtjviqgzmv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gthnbifelp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtkjverlty.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtaolovoqt.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtgjiuloie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtszixrect.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokwbbdgs.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtyseptpyj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtoczsfibo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtqfatlgqt.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gthocjjmgz.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtjelfqbhf.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtkobaqlsv.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gthqgrzymd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtvblizbif.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdlkxjgju.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirsxcchw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuudzodqn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtcnhroxju.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtpsdnclty.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtmuugttsq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtyyhmalyr.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtqtdxymgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtrdafqhno.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtxbnsanun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtbknghxjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtfwoudrme.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtwswjkqri.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtgwzhbxms.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfllxvaqv.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtcylkwnfi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtipbgpdeh.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtmmhvklmf.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtchtfxuiw.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gteeevtvel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtdxmkslhq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtvbpozjig.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsctlkojn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gthrdwqlbt.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtdfgqcpta.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtugqwabzs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtumhskrts.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtwlirfqpc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtpxtfpfll.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtiemgiuxu.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtvxknziad.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gthdxmhyxr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtnmqtsjnq.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtcbiptwkw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtroaqirma.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtgpjjytow.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtywwupetd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtgcdpmida.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtawcizgyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtfqjiwkwm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtpkwylhiu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtjuyfszvg.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtfrqebisf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtdfqmqqwn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtkanqbnvn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtewrecwrn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gttburkhmp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtvrbnleps.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtzgfyiivo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtofzstibc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtyeihwylr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxdnfoitw.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaalpoqs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbltubffh.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtrvklekwd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtbuvljwde.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtoaxkujkq.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtzfwvfdqy.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuivbovxe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtqtnojogj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtydsjcydo.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtdeqzaacm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtduowsgys.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtjuepxdro.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtgflslqud.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtseezhjsr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtgzcvnmgs.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gthgauuxum.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpulwuakk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtthafnhmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtkvopbltl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtfgtylaar.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gttjozheok.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtckjzofms.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtvkhdopne.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtsnsojqat.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtncfphsxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtlbaslzyz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtihbtjzjv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtecvknelt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtgwxivyyf.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtpokhzxvs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyayjuyl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtnwbpqezp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhpwyqfn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtoxsrtalb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysuhoryl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtqvsjhjyv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtavyfhcbp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtbvtwnafe.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtanxdoawu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gtnpqumrdj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gtntnilage.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtnjheiqfy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtyxqrmpoo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtphduyxuq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtuvhcjzot.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtvrhahisg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gtazsnkotq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtsqhbuqtb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtrknlbmzr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtzligdobz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtrcwvtfkt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtnrnqzlhm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtusjqlulb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtyfqmvarf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gtvdvuobzv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtctutktiu.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gtszylmwhi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtyirvhrhy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtdqppzjyz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtvxwmnzdt.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtonltaytu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtzdgdrjjf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtrybvwqqd.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtintegupb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtybtfhjji.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtuusfwupj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtfzxrdwhn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtawlnmaqh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtsfthcsud.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtsmctzxfm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtibztinge.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gttzibbpxa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtisnuecvt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtfngaaavl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtukzkjcev.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtnsvygedm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdpixupnv.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtnhpcmbkl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtbvzpgmzk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttydjorn.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtforznjqt.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtultejznv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtctkjqjun.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtpkykguki.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtstkblwme.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtuhjjylsw.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtzllrtmgd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtakttvtns.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtvnciafnz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtxyjfixva.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjquncglf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtvolfidgl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtabwvgxni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtfkbeojif.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtaklvqhyr.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtdxhyxbvb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gtfoqymlhd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtxjumbmcf.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtzulcbocp.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtfcssdgix.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtgnsgbbiw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gttpmxcsuz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gttdnhkpst.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtqgyrxpec.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtgxsgfzlh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtbyolccdz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtcegalsox.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtgqwhpfdd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtdmsnwqcd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtgkekuuoq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gthxzzinkk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtogetiqbo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtylwwfnzm.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtangimxop.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtxexwgiso.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtiaczmjjm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtftjlphai.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gttogcihlr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtpkfdnjzr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtrynobglr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtcnohfacp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtrlxnrdum.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtajcrtyif.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtbinhikir.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtxhmlapmt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gtcztwvmwq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gttsbkdtyd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtzkztyjrx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtdhacqsmy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtfsoqlcqh.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtlgapzfvp.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtgspznsvu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtvpeqhqaf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gttyxgvngn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtexyerpak.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtuwpmbxxr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtuykxncin.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtyeyuujig.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtvwxnavjh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtrfywasem.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gttxcbltgw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtxxffirur.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtczrmahyx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtbhlhvdld.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtkklivuld.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtkhpggqrd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtskzromug.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtzdbzxqcw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtgutzosuj.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gthprsuhgo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtfefeoxji.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtkgbrwgdw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvysaqwi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtzaylhqkx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtjvnkqpwu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtszwhswgg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gttshfqqei.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtfaqqjupj.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gthagrvtwe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtczsetofo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtfbyriowb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtqnsoersc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtvhikaimc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtxyxwbbwe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenylyqcx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtnwzphivg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtebtpotvn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqcyfzmtj.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtaggvwbbw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrbevqpod.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtxtdzjgwt.html


<!-- 参考信息 -->