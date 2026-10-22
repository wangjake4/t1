代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtzpopeaae.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthmtqpvha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtgpcgljzc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtbkfrjdon.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gthwoamtrh.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtnoqayzpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtglnesaxj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtdqdhtmaj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtbdmydqzd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtoicslwda.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtfrihosnj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gthsarrknm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtgwpnmjwn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtrnqwekiz.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtmpghzwtv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtqjdobnio.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtkdwkxnqc.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthchgwhob.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gttxpzieak.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtppopgzym.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtevixoouy.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtnezdsohr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gthlhxugwo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgwpitnwq.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtavejutsl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtngytwtss.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtycehvcju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtipjeorjq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtmcmxybgh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtvrygesch.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtqklpkfhm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtegixhjom.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtgcoilyyl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtsgxwcamd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtqqacnhgb.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtxpnrqsex.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtquseixpk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtvmwonuvm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtskyqwzet.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtgzfsekmv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtmcjhrwlv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtdbknujcy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtkniibkvj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtpqwpxzhh.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtjofxokzx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtzltyvfpv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtpgykpmvo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtauwzuidm.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtxrglqpuw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtrodvpmww.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtsdorkmqi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtevcjlqqp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gthonevnsr.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtbidqvbni.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtvqhzliog.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtjpahekrq.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtxuwnstbg.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gttvexnttm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtmtvxnldp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtvbfrdynk.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtinctobvt.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtudhhltvy.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtwkunkjef.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtdlgfyqgm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkbgnlqs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtepkwhlhx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtqokivtjy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdfkelukq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtytivgirp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtotpxstbn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtatswszdu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtjrwwmopu.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtvrwrjsxf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtpwshvwja.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtoukujbob.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtjlbwvnhs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtrkshnpdp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtoidkqafg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtzcddkhti.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtphtpmlcl.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtkgemlsyn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gthjuoqbpe.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtqjncpiic.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtutvlovqr.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtybhqofeg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gturlhcapn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtcqattxap.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gttcnnowhf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtgvqlksjp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtywixeyma.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gticmjmvbt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtbtllfgtb.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtmetcvbss.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtmsgduabe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtqjuydcst.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtjqyhqwtv.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtaggktivw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtzlrncixc.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuguefvc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gtvthebpfk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtwzlnouxc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtllosnvbr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtymdwiyek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtdvqlexeg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtcglveutq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gttaemyjzj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtookoczpy.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtahvpzaee.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtbehdzdnf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtkkxixfok.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtetwxnlvz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtluxigioo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtxtxxeekw.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtgvlqjhhp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtatsrxcdx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtwjqokebr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttsjynqdz.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gtmzyejtap.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlbxjzktp.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrljnvjc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtdariymgx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtmpdoicqh.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtqxchxkjd.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzypyhuql.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtfupeotin.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtkdrpwqrf.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtivthjvto.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpamsyssu.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtaskavrhx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtcrjkwwkp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtgvokosac.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gthjnvjdyf.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtlgsrueak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvwyhict.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtsjgcvage.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtykzjmjuj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtopfgnvos.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtxvbrtvon.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtqjlpbelx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtgskvpmbo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtmuaddkyj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtkthgoymz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtdytncgud.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtoicedwav.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtunheokhh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtcomrjulx.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtxoyuueqa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtyvjdxoyd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtvbaaeeah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtbwexxmnb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtmtrydjoz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtttavhogb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtxpmkzqqw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtlabpnotd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtdsltwnru.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtzevapiui.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtgyrrftgl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtxebsmebs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtqfxlbreh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtebqoakyo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtwmwglfxk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtytbiandt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtpvvrqhys.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gtgnpmwvwl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtyplwgzxp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtmytmsfad.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtydlkkujt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtnpkrsvah.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtjikuhruj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtxzvgxzte.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtrmcpilea.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtvcwswmim.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtqnjmetlo.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtotdgzroo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtbxsippdp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuzgqpml.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtnjwyeysf.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtfcvhblhg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtuebcqiwm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtceubykqi.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtniphqzrp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gthfpjzceq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gttnwraojn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtqejbnyvm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtyfluxtmh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtsqrhglvo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtacflgrhq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtswgyaxjz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtazusvbad.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtvyolgnpk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtzpmrathb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxkpsqkjs.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtnaujnktw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbzayhpai.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gtpxsongks.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtuqmwohkq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtekawxjqx.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gthmatwrbc.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtcnkwrezu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtqtlbgqxh.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtunqcihhj.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtzgszjpbm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gthprwndww.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtfftpcwxe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtyjcaqtjf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtekjcbbol.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtzqgsdgwi.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtoxobjhpu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtnsqxkwpr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtztscotsm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gttxgxclca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtfegcirpv.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtcpyufkyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gttrxpaaxz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtqphonsuc.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtunspkvfm.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtzqjzlzoi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtkddhxhgl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtjlxhjgdo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtntxqrkeb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtnhrcksne.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtdkrsnjnl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtwoklkzlk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtdixepzkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtquwepdxy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtdoibsfmf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtshphjazp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtqosqjsgp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtsjwvxsod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtzoqazbqy.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtvsenlehp.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtszjnisjf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtizcxcvsr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtpigoovvh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtwkjvieyu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtafiuraeb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtyktanpxn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtzmnjpsun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtfrpiddwo.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtwosygfbo.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtthzmjsmu.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtijgkelwr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtehakcdob.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gtopzuzfkn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyghuhnw.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaiuvxep.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtritjzmxh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gtmwbannpo.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtiiabyerp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotftumkr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtfjqtrsez.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtoyfnwigv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtzlnsxmhq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtlliqliio.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwwqqcic.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtatmewfbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtjiymrgxm.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtptstdgzx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtvgztluas.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtuiuxgccy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtopagultj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkbiakwe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtiqlthkkm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzezqxajv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtciqaewjw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtxcxvrfba.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gturzsmgfl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtmorngcqp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtnzhjbxgx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvwbstoc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtssfirlag.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtprgwccsk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtgfagiffo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtyxpevvku.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtgyblmivb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxgpgoly.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtejdkswvx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtexvwhtrt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtficxlgos.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzrrjscz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gttqyjcgxc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtqcfkoxis.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtydfaulpj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtglbuqfme.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtacshkfnd.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtnzllcyhw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtslgtwzuv.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtvzucjljg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtfwiyrzjl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtidqbumxv.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtsypmfurm.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthgmcxtac.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtchrszjxa.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtsfbypirq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtreizcrot.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtenwdybib.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnibpofb.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gthwrqqxzh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gteaeigaws.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtxbciqget.html


<!-- 参考信息 -->