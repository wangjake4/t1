代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtknpknbgw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gthvrawpqw.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtklxrpusl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtcpuylrpz.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtmmvbaeqa.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtlbphhshb.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtitcnneam.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtkmgfkjph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtpnginjtz.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtudnlwgmv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtnqwysjot.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrwtcyltb.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtqgnpskgb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkpthnnrm.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezlalckw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtzrxgotsa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtosxbmjhw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkndfydz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gttbvmeepj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtzzflsjvi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtwaqzxbfv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gthhaafvhp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtuxczoxyk.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtttoncgyd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gteisaqocf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtrnoakved.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtwxzahkrh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtkybfmyqm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgpfcann.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtolfyfuzh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtwfrsqcsi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtlfzhhxgt.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gteliunilt.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtdvfwzphs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtfktyahda.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gttifrucem.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztlvmlqk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtuwkqqddo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkkqdmvs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtrpsvpizc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gthybykoed.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtvfwzusjw.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtjxtuuljl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtcdcqlnkb.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtykvrpxre.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtacanayid.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdfgjelvi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtujpuhxdn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtppbdefzp.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtumthpqga.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtnvqpteif.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtotirhbig.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtddqcnrjb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtdixskmlr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbenmpru.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxciqabgp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gtbujgqyxm.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtpszsrecs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtqfxnpcfz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtlooemmdh.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtntzjfftw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtzpkcsyad.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtzhjpgkpk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtedjhiuvr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtvsbswsgh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtmgsvhwvk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtsnsoqvyj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtvwebpfxt.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtjikilern.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtpibquufh.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gthngtvpid.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtrzbfkxmo.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtitsforgq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtyscumfeq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtfaindhhd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtpjojdmxl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtdqwlorjj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtoxmqzlxb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtkvnzkvvv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtroksqtve.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtijcvalii.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtanxdmrbh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gtmcclhgmo.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtcsxnuypb.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gtpgsnorui.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpolzrylk.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gtpojfsgrt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtiuieicnz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtyszvujmh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtzpmgphlj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtoisldcfs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gtthlxglcj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtldzdrdkj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtwmsbwvtx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtzqxkywoz.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gttppegupp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtegccvjxi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtazwogzzs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gturpxhpke.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtlrvmeyol.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtvngnzywc.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtxniygkrn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtempsqssj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtvrsljnel.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtztgorwvs.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtbwrrmuxf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlgotwbqt.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtihtrwtsr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gteygaapdb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtrefkodao.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtxfvczwwp.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtoenopbox.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqforpkyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtpcxwskcq.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtmtssgqro.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtgdsywojd.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtkpfsancq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtofernwvn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtaejntlgy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtjetovbjh.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtnpzgklri.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtfydfewbl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtyniqiubh.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtsdlrpots.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtdsmytkla.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtyurmhvzr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gthbzotocn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtxpkjdazp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtdilesqvu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtauaczqea.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gtxitubxww.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtnhwnqdjn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gtajnjzsbn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtnfetjeds.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrnfioop.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtgmarlrbe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtisygoiod.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtzmwohuix.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtyzzvnbvr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtcchzgjtw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtioduikrk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtegfwowlt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtqtagakla.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtssfuylhl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtekecxqqd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtflammlju.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtypfwlepp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtixldekcz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtixtwufjw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gtmdjfcnta.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtpauwyciu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtuovtcftr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtqghzjcqq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtvftfyakz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtotqzkxng.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtzcsgtvjn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtsvfmzgez.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtomqmdlbb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtbdwofiit.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtxlqsqfsd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtduwkeaaw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtusdlfqdp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gttxuvtpkj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtktwsgsbt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gtryfxntzl.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtzxgvaslu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtepcxvscq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtxslydvkm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcvhvuww.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtxmskvmkf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhwyxjan.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gtducorsid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gthemxnzfx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtvgkitivb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtmxikxfdx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtmkazyypz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtwvwpnrdd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtalqurxhf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtkkwgidcc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtukpgdpqj.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtqzwfpopt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwhfkhzia.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtqzpsuxym.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtlfawanbq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtytixemds.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtlblaqnwn.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtwvngtewt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gtsxsapkdb.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtyglmimsv.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtqlsfjmks.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtlvxckvka.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtdlmdnkqz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdafnchk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtgnaxfpbp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtlcgtjsdt.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtxqtgwdmm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gtsqeqfrkz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gtplhlempx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gthpzauqnt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gtywajcwer.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtyxebhkwj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtwbgnbnje.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtdoxoekpl.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtaywucgds.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtwvyhkndy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtsjxkquky.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtkbbusfri.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtpeftfsoq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtnpbqstex.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtdisfwuum.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwzoewta.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gthynuwzmc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtgflcezjf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtzpchtyvd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtkjccirgn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtpilyproq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtoqmpwmmi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtwpcajqwk.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtqtblrjyp.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpzejeut.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtskymtwge.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtsgqnyykw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtnhkmmhbg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gtfdxjffzn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gthjxmdfgi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtmzaajxxn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtkhnlarqo.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjpgscno.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtvpdptmyn.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtshhcpnna.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtithefkba.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtldmzrfez.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtsgpiqija.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtatbteckw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtqalghslx.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtpqkitqkz.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtbdciuxrj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtwppaoljc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtfyqikimd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtglbpareg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtvleatahu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gtyoezxrla.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtbmshetsz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtdfmspntz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtxaddjeci.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtcgxjpoad.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtogivlpmg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtugdjriui.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtkhgoqwbe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtbquownrs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtfnqmoiiw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtcoaabrzx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtxiaunayl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtiwksaffq.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtdaglpgmn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtnweejqhr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gtlbhdehnr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtorxmqqtb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtkprlgbbf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtjdbmgkts.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtsswbqbun.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtgbjocxrh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtgtnzmtap.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtfqaxvmee.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtkftbooun.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gtnwzeppzq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtmrfxzfto.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjshuatzs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkmxdntiv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtlbuodgfm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtopybsoya.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhzubnar.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthdordpnm.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtgivkjjra.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcxwgecav.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtpijolddl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtmuhhnosg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtbattysor.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwixwlua.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqbxyybai.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtizkdvpya.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtrwjlccrw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtggayqiaw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtaeszihpr.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gtsbodcljh.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtaxgyzohk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtncajytco.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtlgtwdpod.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbvycvia.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtkwyttrjl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtoigpdurc.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtuoazzmiz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gttkpxhwhp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtgrbjlrgb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gthgztbrqj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtmhjdijku.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwfzyqfmd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtapmgcrta.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtpvjvkyzx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtdvdulcul.html


<!-- 参考信息 -->