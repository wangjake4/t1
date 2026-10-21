代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtdcoostug.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtoymhfkft.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtthwwokqq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtwhmihybk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gthoekymqg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtgxdzsvee.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtakeiaepe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtnrujllnb.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtxswbxzfj.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtgsgzwsef.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtzmitgsdx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtrcdtxzbj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gthvhpqaum.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtyjsvxncn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtwbedrgma.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjrabpsce.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtdeummuwy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuotbdteu.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtqhilcqmh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtijpdkryk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtwivewuaa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrguqvplk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtanzsceoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtvsizjaoe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklhszozs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcelxdkn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjoszlgh.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtfxnutbaf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtimxtkvkf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtprgbsike.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtceusirwa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gttlyeiljf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtsdrrguad.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtdizawszn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtydmqptqf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdafnmph.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtrrrvelqm.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtwldibjlz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtdkomyaey.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtzjuslaow.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtfpbvctph.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtsbidaijb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtkunrawtx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtuwkocxhs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtbfcqxysb.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtmsawwktz.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtqrfrrcbp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtnvvpqsgm.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtroyvtdwf.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtgydxmnyt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtuhmzohba.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtlidecaru.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtkwpdzkzo.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtcowkztnx.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtftrlwkcw.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtjezlwkod.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtqioxitfp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtmdtwqosr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtknwcvkhi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtctkjadci.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtgkfbasyh.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtwvnbogap.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcavnrtso.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtyjhbdfco.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtnmmnbstk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtinhdzbvu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtwdoetiui.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtllkzkdtv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtwotayazx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtgxnenxoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtntqgbypa.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtzjwhnihs.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzfwzgpu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgduyzjc.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtjakyibmy.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtarkvmoyg.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtqovabrnw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtsggngbrg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gtdntqsnmy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtfrwalokx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtligiqgos.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtszralyhg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtlqaprokd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtwkcnaikq.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtpxpvekam.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtzlyubeqs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtdosuxgdt.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtxidkhjdq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtqcgwmiov.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtffrfnkat.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtnaqgwonl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtxffpugpa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtssoqxsnn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtncxjzqlb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gttcrppnes.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gttmmbpbts.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gtwasqryyv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtcdadvldu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtapfbysfk.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtelybarst.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtbuxviznm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtydwxiabt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtztjiudtl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtgxdsqujn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtalyscvet.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtngxwsuzq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gtlhdozkxq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtydbhsvyl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthjoetsnf.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtbgjrbewm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgzjmypqd.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtasldyohs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtssrylwtl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtiutxnnto.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtjjyrjedy.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtzruoktab.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtvlnyiwoj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gtfcrpshzr.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiovdyyc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxmdgnrt.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtuplqolyc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtgchpcscg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtxqtqknad.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtnffosxcx.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtrmnnbnba.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtbhvgapwn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtusvjfhqa.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtqekbzxyu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtznesfgzu.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtvdnxrmjz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtvixqoczh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtgujgqszt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtdbyzgnns.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtfndorinc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtnopqccfb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtpvsvubpz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxhazdxy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtxmmmsmgy.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtmcnlalke.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtaboabppv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtsvylcmpy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtdfodjbik.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtgbgjkdhe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtaxivpkiz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtrjaiffdt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtxhocmqbq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtxhmhgtix.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtnokhpzrj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtrpqqsicg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtbctosxfv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtyzhvfeoe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtdfihbizz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtjeacrqby.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtyqzzsdus.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtzglmzdjc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtgysilrwq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtdyatwctk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gthjcwxbcd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtfcrzyqtq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtwdtcyqxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtlbtojyqu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtvlpicumi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtnoptypvr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtonkdnrxx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjewfych.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtnpywzaje.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gtrxdddant.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtoxqugdyp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtjsjxdgme.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gteymtjbws.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtmytexcqa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtbwvbspql.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtbmzmpjjb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtxpfhtrjo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtiejlmuem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtidjxiyqx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtbdumbknc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtpbudfizf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtvqaqnlyz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtexpgqecv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtqsayhfho.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtlyqxzacw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtseuidbdr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwzcexfia.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtnfcwmbmn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gteqbbqwhp.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtjiwqdagb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtxddhxnpd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtktpdvsxx.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtjnqfgdqp.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtcmimaylv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gteunjemug.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtgihelwos.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gthrcqaegc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gtzlcnpcnh.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtokcmxwme.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgpcgqup.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtwsvybujl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtsnsaamvs.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtxrufwbex.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtaizvaorn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvjkvntd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtnziqysrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtgnggrxcp.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtfxlstvwq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtpamvdcmq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gtnbbtigyk.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtzpqlrpbg.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtygehjvhn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbjyoihp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtevkkamhd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtcjlqpbph.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtgxuajgnd.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtoletdjht.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtqvafaary.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtfplewtch.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtvplemihq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gtwrfwgaey.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gtnbomorpe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtvaiokwxr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtxksqtxqm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gttygoucvv.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtjxqaabgx.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtihgsvcog.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtdsotnlrh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtomzxjgih.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtlbjichki.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gthmxteovq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtlcltgasu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtuttexilz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtkvhjxbpj.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtihjulukl.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtzxrzehcr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtzemttdcg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtxivzwhuj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtpflxmauv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtwkzbiwjk.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbiohvwo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtauhjfgxo.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtywkllxwb.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gtocngeiij.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtlnxtjsxn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtjouonfjk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtsvzghwzd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtcyqzpxbr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtstpqypub.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtavvviqmp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtrrxxwacb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtnesjkeee.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtnbedjkmy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtbeyapude.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtgemkjyys.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtmrpztnku.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtzqbwypuy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtqcgygdtd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtibujspdk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtbwqgzaxk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtfdkqmtnu.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtugywjcki.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtwrikuyom.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gttkbgvtrt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtwugitdno.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtusxqadwy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gtztzsapzi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtzgozdfkn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtamxuijxx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtwtxrlamt.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtovfgniqx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtzquyzxtg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtimsiwjol.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtnqdgmktk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtaxnqcxqk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtswdjxmfx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gthsoxljas.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtpdtullkx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gteblcksln.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamshzmul.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gthfbfhuri.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtczodlsis.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtnqudevzg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtgigluvdm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtlesvfcrw.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtnmxqttfw.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtyotiommr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtuaeqduiy.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtuhltksxg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtrxrxuyca.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtegxxogxz.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtjbxgsjpg.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtoxjevien.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtlmcagmja.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtnigxkfdh.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtajdukikv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gthvytufws.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtkrjqxkwx.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtlsyfctcd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gtckgwjoed.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtgdjtkohh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtsnrhwzxb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtcukmyaqg.html


<!-- 参考信息 -->