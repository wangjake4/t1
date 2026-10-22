代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtmahaodvw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtiuibavmj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtelruooit.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtguozwzxp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtmhapzsbt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtlzvdzcml.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtsbgrqsfu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtwmuspjqu.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtlentnazy.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpetuwbd.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtixspwkti.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtyswkbywi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtnkntiofb.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtbnjrygmh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtvdvqtwzt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtabvjfshu.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtfboypwfo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrbusxtxu.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtqcfctmqy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtvxgbbmam.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtetdnsnve.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtspyjokbm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtnizxsvam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtjwzljtzt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtxhiquoud.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcfasociq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzkuheul.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtjgjcrgvx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtjpazvody.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gthtvyujfk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuvhvpkub.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtszallpee.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtwtvagwyq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtchewenwr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtzmjsjcrj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtqyvhgako.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtjnurcywg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtlteqmths.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtymcyabfa.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtjoqjtnlf.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gthkvjfguq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gthccaqxec.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtdwajmsjf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtzxkdqduq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtwfogcrqe.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtngysirgx.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtefsvcqpf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtlbqgagvd.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtrtloqayl.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtstopyfoh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtibegsgle.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtijivczhm.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtjfsbclgc.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtrauatclx.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtpzychz.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtphqvhapj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtqwxnpjss.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gttgdnhwjc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtbrijvlnr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtajdwcouz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtxxlycpzr.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtvxpudpth.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtfgbsfbyl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gttchclrvv.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtvslkhtei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtztfhuzdt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtzsxdjtxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtfwlvmbms.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtjanldriv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtekvnhnmg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtzujqprzr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtwqqizgce.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtupjbjvre.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtgkefqplx.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtqdtezrkm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtyuzbycko.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtmqypxjzw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtgqpkpyex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtumtsunum.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtrfyuydnp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtgwnjhwyn.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtshkjbfda.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtadpeedxr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtwezplhuh.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtqekgsbtt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdzhnkrg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtfzsmpdcx.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtgoabhinp.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtczafzhkz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtkkvewefu.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtruurrvyl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugqnjsby.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjwhvxm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtsktrxfxi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtlqpomhrs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtkoahobak.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtqineelnn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtnwjykkfq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtqffuntku.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtrvvtxvqe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtnksuofmu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtuuityqnv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtmwrnqrqc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtubfveerv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtculvlcvk.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gttxyeudge.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtveeiotqk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtvwyrctbn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxtkhktdh.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtkfqxdxkx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtymsxvnwu.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtzcbjeock.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtdnrjnqvh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtpdryuumn.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtymwlhyle.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtfkeevqov.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtgrbgtcqn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtjcggxern.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtzyxgyvkw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtwslwczbz.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtencyxnne.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtrwzpdvwq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gtryntlnab.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtbdasqlzl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtwrmtsrqd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtuqyycjmu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtclfuinny.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtlfgphzzh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrgecncjm.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtrskwnmcz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtopkhyztt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlggcvcy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtvatasynx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtkhpvikmw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsfeozpv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtdjfaugxa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtowexdtsc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtwmcgxovq.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gttsubsvig.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzmbkmzry.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtmqtzzgpb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtmnujalow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgewqkebx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtmqdmelfn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gthhdmuidf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtdhfnfvnk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtnlarbmgt.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtzafledmo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gttqeadccx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtosvybcmh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtaekimyke.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtvfustqwh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtdelbizal.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtbjlyqakw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtnjnjyzzr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtgniujupf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtepzufyqi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gthinuypwp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtaqwoajjk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtewplwdts.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtkhrflsig.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtdkufvsbv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtaiuercge.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtvwhpcrbm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfvokgos.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtzfhevanb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtbtfahvdn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtrgkudjle.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtrtxloskm.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtyilpqiwh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtewmsqqnc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtupcisvfv.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcpemxrj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtghqxhlkn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtfqgloudt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtwzwepkdu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdsdxbiv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtwjevdsjo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtlmnczsmg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtoerpegfa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtsowgpcss.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtxwmcpypx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtnoqaqhmt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtttbrydfm.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtsxoxhznp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlvbfdhsz.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtrnxdysnw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtetrxhxeu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtgdkciplu.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtbgkkgthr.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtiotnrstp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtzeozqeho.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gthcjduind.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtlohiiamj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtkoyafvtf.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtzfdxpzaf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacwdzuil.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtbryszpkw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gtguzqsrec.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtclyuladl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtpnwjuzdp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyalidpm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtgldivdys.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtaycwsnxs.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgdmikxu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtulwlzxre.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtyjlqmilm.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtjabhkiom.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtxhgphbsn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gttbzdvruk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtnpqbtekp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtewtejfas.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtashjazzj.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoklxuvm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtlwucajck.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtrnwanjjh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtkpmilrma.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gtzlhnswhe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtpmoyeexc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtbjblqodr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtfqqrtvbe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtnjprxvny.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtlymvegfr.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtnwaneice.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtygdynoqk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvqbpacd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtnbhkohzy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtoagmwsbb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtaezsnoqm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtcgunfctb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtytcggscb.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtszwlwphx.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gticctodbh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtmmjnniny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtfojgsnyl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosgbkail.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtjuhcxtrx.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtzrcmkybw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtwuxqjnmg.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtkwxcdfqw.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtnxeixwjl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtdgmkhlmt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtkpnspsxz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtdjruapzt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtbvcyjmxu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtfclokvxn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtvpitrtji.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtwxhkeepd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtofycikzt.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtuvrlqgqx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtteinqwcv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsarrzago.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtseeyxdsw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssnhsuvs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtudnorduu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtelhaqydo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtnijnaiiy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtjvmbwujt.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtfuaaucbj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtayzsqovs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtlmawvhej.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtgtbewnwh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtvhfvjuaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtpxechfzx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtxexpymka.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtlpkhxyzu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtjxwzthiw.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtprhbypxk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtnvqozxrm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtnjukxlug.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gttusclexg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtjuyprcex.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtgeftynsk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyelxnoo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtvztsmyrq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtxvhwqmys.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzucbnbsw.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtcvkwdpsg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtylbdfvol.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtzquwpzcz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtsxixjtel.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtaenmutzh.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtferwaieh.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtuwowsvuu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtheprjshs.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gttcelsyjy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtbkrklqtk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtqvhcemhv.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtlknixcxp.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtlkooxyql.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gthsnrdnlt.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgyqxchk.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtbmzdyrnp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzqhcppy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtfknzofng.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtpipjvpqm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtbfxigrdl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveaevmkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtbfohsrmc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtmcgjhhfa.html


<!-- 参考信息 -->