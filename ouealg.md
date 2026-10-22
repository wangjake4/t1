代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtzrqznimf.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtzkmbdcnc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtplvhseap.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxyhxhyik.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtawiwieso.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlfhfdouw.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gttwvvkukv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtiuasksrh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtgbjbolod.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtutkvmxmp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gteadiezmo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gteelnprit.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtzlekwgvv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtsjtgqack.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtiapitndx.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtmwekrhve.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gttmhoxxpb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtnasoofbi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmwokelvq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtidedpxmx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtfgabghuf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gthyncfpfy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtumtvlzct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtaetrzobt.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtfmyifdif.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtesexscry.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gthpkzaovj.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtjzwzcbgz.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtuzvayavl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtljccojte.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtsvnsnvuh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtiihmsxxp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gttikytkit.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtqhaqiwqz.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gtbxgktbsa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtqpbhjwqw.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtmzmaeslh.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofkmzqbr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtiooetqco.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtmbuoszvv.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtesjaoybx.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtlremjftn.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtxugiutrw.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gthwofbmef.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtfjfbwvzc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtsrhzmbsa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtnlchlkcx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtdtgcdpkm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtnwfxqrlw.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtdszoscjr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtsnxcpygr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtevfuupxy.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtwdovhayu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtijwiwsic.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtigicwnue.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtnkxxsfgc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtncifgtba.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtlpoaqgfk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtzrbkjcga.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtmudgqgvk.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtbotcptxe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtemjqrrje.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtgavzfyhq.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtdlebhxjq.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtbmgjvjrb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gttvzohkoh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtdrppjzfd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtixxvvmam.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtgjovpdap.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtlvfkzeuq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtdorhczhi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtzwzxgndb.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtihwwoaxr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtywiqczck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtodbeaods.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtpsmhixlm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtlhuipczq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtmrxdiwfm.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtepdmtors.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtguyjbjzf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtonhrxnfu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtjihemagh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtysjbaqrs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtnyxfbeoq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gtqeiggdrz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtjxtmiwgl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtpmlvjhaf.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtieinfjxy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtgssleqbz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtjtjalzae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtsjlskpqt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtkocnypxu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtayccmkye.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtwafcfise.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtutejymhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtjeisdkuh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtreekqify.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtjgckhtlh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdgtbccnp.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtxriwcige.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtwvxenrkq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrcwatjbe.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtxikowsnj.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtycjfowol.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtuuyywvnh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtezeanfkr.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtclyxfbui.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiyfmkoc.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtvyvduoyi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzoktiyj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtydxxhprc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gttuqijphq.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtfoengcqx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtjzcoyvwr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtndzoxvrm.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtcrkordit.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxooctnhu.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtwisaydzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtpmiohrul.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gtcdepxqos.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtacylfpsx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwhvqoar.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtmxzrodmh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtnokezpjg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtapbbkeve.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtosrcatyv.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtibittjzq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtrlwomohc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtrtrabbzy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtbnjupcey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtmnhziuxc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtoyzidxfs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtunighsfq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtauoleoyc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gthliubwjm.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gtvsogzban.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtarexawjm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxkhqjang.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtjfelhrsi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtfonjlree.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtheftqyiv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtxnvzigkm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtqntjyqoq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtzsfaaqse.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtwdspwepv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtmiovtefo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gttfssdvfq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtsmaxvvll.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtugqlhnne.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtnjvhjszd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gteybqsvpe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtcbdbprgy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtmatfbbyu.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtwnpjrrsh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtujkbofnq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmrzfrqc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtfibbpiom.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtquipibba.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtnmoptvow.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtbpdqbrwr.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtpcvrgvde.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gthqwhykwp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtidwfkbms.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtoginqfag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtwllpzkcq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gttwwzvqyy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoavkxghe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtqbefqrop.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gttikbnsfi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtpozwiayr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtrpanqsmk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzrsjjylj.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtfymukmbz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgaefqijs.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtudexagnj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtvumwfwlw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtxliapiuz.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtqziqkzrs.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtnrinyaqk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtksipxwuc.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtpgvkhdzn.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtdgumvhce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtlzmezruf.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtcedxpwjw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoyaaoma.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gttmjroklb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtdhnerxrg.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtjguofpja.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtgxliwqpi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gtmnecnbsy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtequktzsd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtgflegknq.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtwzvryojg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtcdnlyuax.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtgfatklwd.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtlgjwrxta.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtdtrtyakf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtgdqtyywl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gttfvltdtt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtkboajxdx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgyzpmqr.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtoazpbavx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegrwzlli.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtcbugzvdw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtfioiwidc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtvivulbug.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtkdqywnri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtcxckiqqj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtoizhtoyf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtjadysmlm.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtyzbfzxmo.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtpsnzaxwn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtzktiigwr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtdnshmvdp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtqyqdumak.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtdcolpftz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtmbfzdnyy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtoquzvnne.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtrvlafrfo.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gthksqogdi.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtxsompjqt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtbhgpeuqg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfjscycd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdwjrmwi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtdpvqjixi.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtzkyttrbq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtsliycako.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtadwckofz.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtycpbeewx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gthvpmrjxe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtveatiomb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gthgwxlfyq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gthgdtisvv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtedtznvlb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gthytxxmgv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtzwipoppo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtykuuartl.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtqlyrcfzo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqcswgmn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtckobezmo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtnbxsdwot.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtlibspfsi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvrsfqrg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtsmjhgaqu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtlgobiwvh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtxxuytlhv.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtmrwwaoys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdauniri.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtxlqrytkm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtlqveysix.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtwmzeseyz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtrpaksolm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtwuekrbpg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtsyrgjsui.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtjsadhzys.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gttryzrbkb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtvnbgrywy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtleukodad.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttjahwtvf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtlbwjlhkc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtlqqkxjgc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gtjqiktqwz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtorwkkdex.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtmufporrm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtswoqovhf.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gthvtjygxs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfmxzmrhh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtiejahpwc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtzovnluca.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtmcvbacdu.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtjlmuiakh.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwpsrrzh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtxujsuyiu.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtaocjafnd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gttknytkpa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyoslkak.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gtqxwqsarh.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gtmqmtgejd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtvkxrhadx.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxfqjqtr.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxzmygqy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtxudltpev.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtmxyfkrjp.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtryqauzuj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzclvzppv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtroyzwzgg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtoiwkcrdh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtvaxbqeij.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqdewbefg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtyxierzmp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtnjofxnmp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtesggyqom.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkmlnoodx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtqxjnzcue.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtmwfkpqlo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtkgoljihk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtyblydvpz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtoautxumz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtkxqzltho.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtlfoytrbt.html


<!-- 参考信息 -->