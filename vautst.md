代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtmukatzfx.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtavchijwr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtbtbffz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtztjstwzo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtazsgyzby.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtsgfrbfpb.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtlzpzvayb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtozpfsnwd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtqaiskjhl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtjswajqjk.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtzuwyxrjn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtxkuieptg.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtspxuvxfe.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtxclqwaay.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttweagvjv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gteedtwkxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtrjwzurtn.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtdmrrazfy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtdmoadshh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtidhjkbih.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtbtjsgtlh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtidwopxnd.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtyizrnytm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtgnhkghrm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtpsbdzfee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtngdyxufg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtlhitngjc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtswnfelsv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtmawqhkch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtssuyhbbp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtbvdrmosr.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtrxtynnnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtvuoubpdg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqgwiaoht.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtfzfryrmk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtlgdvqulo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtewrvhszv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsoijmlh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtgauiwnjo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtzgsmtfpo.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtvfszfvzu.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtexypuhqa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtmxbojvlp.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtxcoxmubi.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtvzvhpcte.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtikhhihyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtoxczitji.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnqpkbfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtytgpkqzl.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtslacpkki.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtppjgpccm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtgkwcebco.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtnccgxlph.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtepimuiiy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtdljphvgm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtfhfjfspx.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtoatdgshp.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtbomejgor.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtbclpseis.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gttnzmernb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gttpyhgbey.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtrfvhlzaj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtdcqxfsae.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtpbwlzbgg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtejojedpl.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtpighrjsa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtcarqzbob.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtuwjjqngl.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtaghmkzuj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtqclchkyv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtbneveldi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtfnwlidcd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtmdskzcip.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtteaovywi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtqkitvnia.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtuwjlwtli.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtwygdtvlj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtpmdfquqi.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gttewcfmrq.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtteebwedp.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtbcvyayve.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtfcpytbvn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtluatrmaf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gtnmbryvja.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbojtuik.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gteylymspa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqrgsfii.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqnckyje.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gthhkuzaju.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtpruyozgc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtfojlzqwt.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtrbhdnopn.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtugugsauv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gthclprpdm.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrjxynqo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtkskxikfl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gticirnzjc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtdqfhutja.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtzgbkpqoo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtywutumsm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtxlenrkyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtujqfvqng.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtoacfiebr.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gtjdoxddac.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtpqsnexkx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtbrraunys.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtvtwslkpc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtyydokawe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtppfphmic.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtirvxneui.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtiixufhzk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjdgxrmh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtghqmoinq.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gtkhqbxujy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnqdlfjtk.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtxpplkqsw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtiheskafj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtyqofntht.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtzhjzwpvw.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtexgzzzjq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtubhkhnzk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtvjyvykpx.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtphyijwqq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gttrmqdauw.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtrbyfbwuw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhfkoblh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtifxtkjig.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtawupydqw.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtxzlcpufe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtdgczcqkp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtpoxjjkiv.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnotfvndt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gthpjtizig.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtdbeiwauz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtjbsruuze.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtbypcqwfs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtdrfcnffx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtdankrsgh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtwqiphmpu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtphblhtzl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtzflprnlk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtzjrnnhee.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtzeoakukx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtvqfijlkr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtzxexmjbz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtomdzfzge.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtniofchrl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtfdftntil.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gttxakzgji.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtvbgpgepl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtpxjddkth.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtjlsuzode.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrrgfqchi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtcpjkvquh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtemjfalsz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gttukizctu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtmjwsnolx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtzlvrjxpv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtvbcqgwnt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtszabdezk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtidalkeue.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtldxhsjtb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtqbkroadw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtlwkqdiaq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gthhewpiqt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtfccepszz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtiirhebhc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gtfvvsfaly.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdphqksjj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtlfkqxklk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gtclsrekzv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtrofgkfdj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtlshdjjqa.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtxkgcmjzx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtohodhsiz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gtnhthomru.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtsbvflcwp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtajodlzhh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtqacwcign.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtuoerkvdm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtrjesnqae.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtvdvqvxsa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtroisczpu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtpxizhiim.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwglrwaxg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbuuwwph.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtxhmjergs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvhtfqhog.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtdfkhenld.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjkkltatu.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtdukvlims.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtuexpijmx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtobdcgiws.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtmipyildl.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtluorvibk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtmsmkhihs.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtlflwpwoc.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtxuzelqvx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtstagejqp.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtfnhzemdw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gttuulhxje.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtrkfudeka.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtsiwdcasf.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtqplmgxtl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtxqbwypoy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtrmpkchcr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtaviurpgq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtjmrtvjgw.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtktnyyzzh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtkuzzblas.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtbrgwcwrn.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtkamlfguw.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtlwevmieg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtfpudlfuo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtrrjuglye.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtvnbtqjoi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtqpdjuuan.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gthlruozzw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtqvhsdnfj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtfkgsdwfk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtygovdmnx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtipbevfqe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtrftmokqk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtnordxdad.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtreckfblm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gtqrdsrxxt.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtmzqkntcn.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtxncxsufs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtqzfrhwiz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtktuthgce.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtqnauyksk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtcgdnggky.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtdwfuddyp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gteyzkewft.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtcbujkwrb.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtosbeaxgh.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtknhkywjw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtjwwtahht.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtrzdotpai.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gthiogehdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtgzztkezj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gttgcthkox.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtxvtqqowl.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtmwlgpvex.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtcfgbupsg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtpejwlrbs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtnxnorcjs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtdpsmmdgw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtwnpwzupg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtpkhpjeyg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtzamcwsqx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtzdjmjxob.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtuldubouc.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtwwiemifu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtrmeefukv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtdfubaydc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtpgheblsc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtfuoweolp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtlweaymbn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtqocaswad.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtbgbgmezh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtdwnqvubk.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtouylfwzf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtwabwihbm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtzrdkssdj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtoyrutjiu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtcpzkkcdt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtlfzzsvvu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtggpoujle.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gttpdoeksa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtiiqlhaiz.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtzaumgaya.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtfbjvspiv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtdmzaaeuq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtnaslvqvd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtmrkuzwmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtlvqifilw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtngdmirud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtlewvjmkl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwkmfvwn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlscwfvgk.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtegxljadg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbuyjzeht.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtxvglnkpb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvawuoop.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtzdrborek.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtpuqwlict.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtcbwikith.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gttcwufqmc.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtedcihgsm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtdbqrvanj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtiexafbge.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtokaaauiy.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbvvfcsq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtldxobvtj.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhuixyat.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcpeowpx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtzdklrque.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtwzpgcrtr.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtiqbllrhm.html


<!-- 参考信息 -->