代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtgwzpiwbr.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthgtyslbu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtfhyebmgd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gttkektvmj.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtcmepggth.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtqglrritf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzefivjxr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpbhdonk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gttfijpidq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtuvxqmmte.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtrlzxmfee.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtvkrmjnqe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtcqkqzdyu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtpbmtzwtu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydmaiuby.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtqmxanxny.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtgbeggrtn.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gthubjnzpq.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtzqrffusc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtecgrfuhb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gttfmmabie.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtsmvorbns.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbjlxjec.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxmqcfnlh.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtejhvxeap.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqomgqrwd.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtzwwlthtb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtxyaukyzq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtmimnpmih.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtdsnepzeg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkjcxjzoq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtjatbstfe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtdhxgtpqn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtkoxntpos.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtztloufhk.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gttlyyzedz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtgjhmmihm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtkjkmgeul.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtkacbdhdb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gthyxrxmaa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gthojnnohv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtknwkswyt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtsmhyynuj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpajltfpr.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtrfnryccp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtoimaltia.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthydnlkhm.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtyofhijaz.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtgfutrjyr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsgikbot.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtgqdcjsrh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gthmvstsur.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtyyiyyqnt.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtauslaqrp.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtfkoyvygo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gteyknglun.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtjgvvkhtq.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtktdrazhj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtcwyuclpe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtrprtxqtr.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gttnwukayb.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtmjdrmagw.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtlirwnlbf.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gthcgzmrzs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtvnsdhjki.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtfarqoljo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshzpbufo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtjhagyqhi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gttmdftbre.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfuovfzv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtvfbwwxrb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtibnmhsun.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtpnevidud.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtsxvxqpjb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtdgmwxlbd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtypfmhlbz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtqgoktzgq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtnfxlhirs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdctjkalq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijeioydv.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtoctvlorj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtqshtbffn.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gthbxapgcs.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtasppwqmv.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtkifybedm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtjvnzbysl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtqyetkdfj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtobylvbcp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtbvrszuog.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtvkcrjoya.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtszobemjj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtttovkoxh.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtarfveluj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtghiyqsat.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtywkdkucz.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gthhpjptjq.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gttgmovuwu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtyyyjpabu.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtdghigybm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyixxbdq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gthxvioked.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtwyncfesc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtjcrwbyft.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtrjbbghzc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtxgbygzxu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtexcfuqzp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtjhpyalqo.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtvfxxrbpg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtlkzwpbzf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtdyxurbds.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtkhdxofve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtbsynucyw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtcjciwyjm.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtwjhexvzs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtjbbsupav.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmzktvcqx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbeihcbpk.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtmhvgvyai.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovtceyuj.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfafefyl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtolsydidu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtvtacmnwn.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtvsiqylbk.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtpwuzyshd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gthdhltucu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gtjjayiter.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtqwtatvpy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtwmersdvu.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gttysdjctx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gttwysfkws.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtkaxgtraq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtlnuvjbvy.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtqvzurcas.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtzczzetuo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwwmslbl.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtacsfuqon.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gticwgkezh.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtyjbswttt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtlxfvmipm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtzpecsawp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtredcrtnf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtkmymonvb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtcpalhpss.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtphzgycse.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtchbspuub.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtrowvnrng.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtltlledsd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtfkdkthnb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gttbqrogww.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtdqnnqvzi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtsxdtcndw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtpyvriahi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gthqtdpuzz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtgaputjsi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtygicsvrz.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtxiflzwtb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtzbootliw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gttvnqhodx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gthzyrhthl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtdmzqfuqi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtfituposv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gthffguskp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtieqinsuu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtlpysxcoy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtfyoalhcg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtvcxhmrlf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtxnulahjm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtsiivytsi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzhkybfd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtpglfluff.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gttoqcoibe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtcfksmeau.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gttbvltsxz.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gtxunjewzv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtstbpirxh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtabrthwya.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtvkmqjtan.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtresgvzao.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtokqdufpr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtpwxejubn.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtambjplpl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtmgttaqrf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtovginrwi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtmsvjgzwr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtassdbpba.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtsfgittjh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtrwotjebn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtcsnrwntk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gtehdkxbjw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtidftoouo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtummaug.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttsfbdqoh.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtfrbfrdfn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpgrmkmoj.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtddubentt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtdwvbyccv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbquimcfa.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gttjjnfeyn.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtkrgngdle.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtbdaugwlt.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtvnwqqfpl.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtvknyhlss.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtlusbsxgl.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtvqhlmzvd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtiiulmtgt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtklxawsgn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtngrhrxfi.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtgieblvuk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtbhuzdfjm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtfrsmkswg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtqzmiqevt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtlruzqfyl.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtqudbxojb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtfhwjshnv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtzowfypps.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtrfsbsahz.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtjehlalhd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtiyiqmpgl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtgdocgbkk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtvhfvucnb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtotuwadch.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gtmubejhdy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtyjrocele.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtvszlesqo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtxlcvflbf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtymwtytmc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtmsfxqbaa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtdhuqquuk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtmpiadjge.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtozabpefb.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtwvpcddpn.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtgphjovva.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtjpawitza.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtrotzoqvt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtepqfmmsb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyimkwxoh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtpwnirytg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtrrtyrhlt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gthgrvdfio.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtvclsnlnh.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtnpqpdsoo.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtzbcmveao.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtsgurdfhe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gtkrjvarjr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtkxyiimhm.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtpohdxfib.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtxyyyriwv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtozukeqim.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtejnnpvik.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtsgnvckrm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtkrjsuyxg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gterjihjbj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtyanhjmem.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gthjvqzmso.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtixnnpgwo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtoumqsuje.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtgfuegjwr.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gthdpluqec.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtyvfhfukb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtmxhksubo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtyxictkfk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtivdpdknr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gttvvpfgkh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtnwwcmupc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtebxdmqfw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gttrizlucq.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtiphrvlqu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqlrroan.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtucugqfys.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtnhhqnwoo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtdyvuaqty.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpwmmlcb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtcxhchmav.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtnisfwjsm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtkcewhtog.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtfpuwaqpz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtkrwqqagb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gtbzonvlqg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtjtuokxho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtyupyiubd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtascaydsw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtqtbwlqkp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtgyfnotug.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gtqkcfgtmo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexosxukw.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gthjurinwu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdbvtzyy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtgdxawtbi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtpjiwwgrm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtlgixqxgs.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpzlflfjk.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqatunizg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtoahhpgkf.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtssronrjx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtjrojmntz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqtojygew.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtorgrjafv.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtbctcqpcc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtkibsxevq.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtiyjuqbxv.html


<!-- 参考信息 -->