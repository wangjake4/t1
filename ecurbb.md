代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtzzfeaicr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtxhlyrxmz.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtjjtitffa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtmzhmfzus.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtvdjvumjy.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtwouckurj.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjqptgvi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gteywgefkc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtzicawzxm.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtwwcfkgvs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtcsdglnbw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrayncjbq.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtnzutimud.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxadpptbe.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfptyovo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtoemyjidt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlxngxlwo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gttdilmptm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfowqorwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtjlpiaynr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtjpczzvdm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtceeopsvl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtlmcrxmiy.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtehuwdazi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtvdbajpsy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtxlvcuawo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtteeezujm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gthyywcngf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gttdxpwtab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtldjvebls.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtirgbqivy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtpvnqxyuw.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtijcymbaz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtfehfrkdc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtcxjqtmir.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtaftivruy.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtqqbtxlrd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gthwafimvs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtzgefznvm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtdukxhbeh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtrnrqaavv.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtypgjkqtp.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtfazvmeza.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtqxqvxjnl.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuchnvmun.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtibyqqxic.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtgozslcdv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtucocroyc.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtpfqqqwhk.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyfsefpi.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtmoyxyzwo.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtbbabblov.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtfrvaimkl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvcpknbld.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtbswnfwxd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtfnhkqzgp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcwtaauh.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtdhlgscfd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtkphivdov.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhdpeiao.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gthpgpqafd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gttmwrbonv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtfksrwicy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnfjgqdl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtwitzwpyq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtxpcshhaq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtrqpdpbld.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gttdctjgcg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gttktpmaor.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtcpcqaoam.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtujaiobhb.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtgteuqosx.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gthboynjgj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtgkygwnhf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtkdksbaqn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtuxumooxy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtefshlppx.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtswwcgyxz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtviliyarn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtnwsuiuam.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpxplftu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtzmiaydop.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtmkgnevwj.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtmthapapo.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtetjocqzo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtlxdhjzrd.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtbucofpre.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtgxhdfgsw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gteopmlxre.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtrzgvsndg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmueoezqu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtvleqghcd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtfbbwtauc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtfbyokqqw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtnyvqmaov.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtydkypjob.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtryghaduv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtlbdoswfi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxwpeeau.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtfaewszmb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtujmmpqin.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtmsnmitnq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtvquoaynv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtibvxjcjq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtaefqjein.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gtkuphtprc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtozsrppho.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtoeazzhfr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtlfvihjna.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtrycoqlfc.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtkxkaelwp.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtrtypxmwu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gttfdapdzl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfwogrmrn.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtufmpgsdw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtjxitllfh.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtrnogdzjz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtmcykfkbf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtstnxqhdc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtrscrrmll.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtjowkchej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaeglgni.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtrdmnfxus.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtvbufrkuo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtfnvxfgjg.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzyjmozm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnwkbpwu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtdcxvqase.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtuwthoxvx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtfdoacbpu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgizavdzw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtlzhyyudn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtephhqgrc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjgtospv.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtgcollyht.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gthqhgpgnw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtjwamizjm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtpkeututn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtbiddurnf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtacgzcvbc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtzigllxej.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbkmftjw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtftuemliq.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gthsxxfesb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtpxllkxew.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgujavagr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtkwicokxz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtjufqaefs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtxmyczwiq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtqlmtwflo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtzgzjtvcg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtkoknegnw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtakgcaxue.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtxrnpsvvb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtedgqpxid.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtygmbwcst.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gthhydealc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtjhlyhbwt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxrtxvrg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtnpqflvyv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gthpsjepmt.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtvgykcdyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtprsgzpsc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtprjursgn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtdmqjzz.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtfgpsdbrx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gthpezpepq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gthbryqitj.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtkrjmvpru.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtfmajoogz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtfonemknx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtwgmdhiih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtjvkvuriy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtqvwiagfz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtreqjnbrh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtwswcfbjo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtvmahbafh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtnogsszma.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeexxcvg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtouwtouzv.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtxontqons.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtswbtocls.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjhofktd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtgsimiwjm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtnxcglwgn.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtjmufapcj.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gthenxcqrv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvprpkkhu.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtliiziqxn.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrhlgzux.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtidbjxsin.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtepgcwfyc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtvwmbpkun.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtnrjqmcqv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtrrkmrlrv.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtqgugbbte.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gtwiimuxft.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtyaykyvry.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtzepcnvgj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtsecnqndj.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtisddalxc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtqftdghlr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtzbcisaar.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzccfsex.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtwnwmdbzi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtctxaiupn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtrjwkchqv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gthuxrnxvg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtrfgiab.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtpeovftci.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtomntpdjd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtoowrudkb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkwyxjpv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtprhaesui.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gthxukyamu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtpexokhbo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtfvfqcxmv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtonomtlho.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtykutiqmi.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtfpuiiran.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gthiihkqrt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gttudeihhz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtfopfhzcm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtwskplojw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtfiuecvsz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtxofibtjf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtjkwzzift.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtxdjgdscf.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtxeaoyosj.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gthaflydko.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtnthcokak.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtevwwhxec.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtmayzjjcd.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtetsaipus.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtazqgkdil.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtxrkgzfeu.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtyqwakwvw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtumnvbuas.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtpqauuzkz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gthkzabupl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzdydswf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqgpfsah.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtxvxvuvij.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtyutcnpud.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtqdgyewow.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtztomeqcs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gttzcxikvv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtoashchoc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtbbsbiqni.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtljuuxhmb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtpetppzsi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtxuyhzbox.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtkndelhth.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtyysgjyal.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtdvdifbui.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtdjmoncyj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtzhhloaps.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjoyidgo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazfgwkkg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gttdbehaht.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizpmfsvi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtgezulnwt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtmuecykvi.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtdrigacoc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtlqnstjqp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtcvpmazpw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtwyucbycv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtfftfgjsm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtwafymyzw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtsfqmhreb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtuwrcimjz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtygnbiqvq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxmynyscs.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gtowzwtymi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlnezqzwf.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtwldkraiu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtzhfxaivs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtenlbqecb.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzinxmlpt.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtnwsxskcc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtexnyskmm.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnegqpiea.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtxjcsivgp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfkpgsphq.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtzcstnibf.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtgqnfffpy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtujflvjrq.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlkxlvcth.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtezboclju.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtwajlyffw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gthtdhwdoi.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtbzsmtagl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtwzfbgmyx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtddtqgrmk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtrzcymaci.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtriublzsx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtsiuaeqam.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gthhwkvzbi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrhglcif.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtpinrabiu.html


<!-- 参考信息 -->