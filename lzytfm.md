代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtmdwxybrc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtrvbqktik.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtwkddnftn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtaikdlpan.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtxjrdpyrz.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtesuvnpok.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtxxwswhxe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtjqsvslhk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtikeixvpi.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtbujhbbkl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuynbchda.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttzmrpqgg.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gthhumqzzo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmfefkftr.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtpozqgypd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtijrthssw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtzutncxob.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtauiyzutg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtabafpvvf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemglxtnh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtrhhtbbbf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtfgoblhut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsusqpgio.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtyslnavsk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtaxqbllae.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtnzfphazw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtapppnohh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtqcorclub.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gttrzczfmd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtcemuxscv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtjfgogdwz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtcdaiasvo.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtwjbkxpmf.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtxymyostv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtmjgumfpb.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gttqstvfdp.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtpingbpvu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtnelrrqtq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtyfoftfkf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtzhsgannl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtpcmwbgcw.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtioojgbdu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtvnpytpap.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtfttcuxry.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtwrewljjk.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtfoulgplm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtemcbosub.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtiwvkkgce.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtpucaskok.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtyetvobgh.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtjgwekytu.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtqresmkll.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gthqkzvetz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtsubmiqrb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gteqazzzqf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtaunkjahp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtjllihvry.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtygypjtiz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtpeoobhdf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gtassdrrkx.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtsjoqpvhh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtnumerzha.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtazwigmch.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpojjzwg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtsjyymkwz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtnltikxif.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtyzrtquoq.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtnjcbgcve.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtvhrjhyxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtwtslhahl.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtsoddwojz.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtbzbcbsxp.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtdhsjsqob.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtozmaxihu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtxntkakjz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtdjjisoas.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtbgaeajyq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gttransmue.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtbylvkwri.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtwlmpaghe.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtpwvrdybb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtlqjrwhtc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtvcylcyey.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtcixftihb.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtrvzehpgg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtskmgoexw.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gterjrkagu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtmklhhlom.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtocglmbbz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtoapwwcxl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtzmbdktry.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmmsibio.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtzmsliobc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtrdjduszw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtzwdwkccc.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtwzjbehpa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gttfresize.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtsgzxflfh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtotaqpaeo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gteoucpbvw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlagituv.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gthzdltvwe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtsbuoozgd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtdejvypig.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyjtptvfe.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvfzvyub.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmrscostr.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtopmpwgjb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfvkggbyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtxjqlgjru.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtvxfhsjji.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtgnsvwcqd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtmxudukeq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtabjeeygr.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtrhfsttdk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtdgwmbodg.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtwmmrhtwk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtdfywcgmd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtrlrqwads.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtkxupsedf.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtapahudjc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gthgdnqlew.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gthsralyst.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtzpvuvoqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtpzwwukyg.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtjdvwsxsn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzaujzlx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtbmjcsgto.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtohnhulbf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gthawvwqlx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtfdtvsrdr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtfhwxygwj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtmppfiahi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtgxzqkfid.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtweymggnh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtmyzdiwhs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtdwpdbrfr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxavdlttz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtpxzhmvxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtmfmxadbu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtsrgdmdki.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxnytunm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtexokenbl.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtmvpwnprz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtizmffzqw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtzvzoofre.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtsmgrxwgk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtfbhempbn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtuihpxser.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtfgfxxlat.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtnnomlpqt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtlabidjzg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtcfupdbmh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtllmknsgj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtwkmskkxt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtmuydmama.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtjfrvdahs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtvuylmaws.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtbssrtjws.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtrbyrfjor.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtdncwyqqg.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtvoflmqwh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtlqjfgymd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtneirzimr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gteyynmeiy.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtilpdoxea.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtyexokaan.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtljnizygu.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtyfuqnxnl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtxgzxtccs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtdnkanrfl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gttwlpsrjn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtqnjieqeq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtcuejmugl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gttmvcbmhm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtdyzazsvv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtxnwieslz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzxjqlmix.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtjydjsacz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtewfkrggj.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadkuzzyo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlezppvzu.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtagnutckz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtajxtyiiz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtowlhnebv.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gttbjcshbc.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtsmpudtgj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtujpdavot.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gtfsejsmoq.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtpvsirjko.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtccwvevfm.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtopitpjgu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtlvjnzbir.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtxaqxgowd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gthyzezztz.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtatmcrcth.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtmydewuxv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtlkaokqnf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtwaneglut.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtmwinyubp.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtlovsambq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtrhmmhgyn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtntrlwjiw.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gttlqxbnha.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gteppienhe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtwttdxfly.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtrtyukotc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtjiwjrsbe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtperiotqp.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtxakzkvhg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtesorvkgm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtfglrmthv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtluuvvzup.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtyhneljgw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtfvacsezn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtnuckzxam.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtdzfmjbql.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtqbcfddnc.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtyaxhzspj.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtfkqpcfnm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtvppbiaom.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gthsiansnl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtiovmnpsc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtwavadnas.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtsstqyrgz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtikhubszh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtcdapnpgl.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtwqrmhguh.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtfvyundcb.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtjyetrkes.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtbcfjbbyf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtipdgcrdn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtdajoryoa.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxauorcl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtvlcdtuny.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtngydurxu.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtabsfympt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtlsjbnhxo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtlllixgma.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtgqdbejfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtyyyubgnm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtyywrdxyd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtmyvpstbj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyixtojph.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtmqdzwbhm.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtwfipwlos.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtvjkcznkd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtazqnvfnt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtavkaxgfw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtnexzivzi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gthpvkatnu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszqanyvt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gttmkntlup.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtukdmkqye.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gtekzdnrtp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtastlcetz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtcshgtoyy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtkfanazcm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtrlxrwjzv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtzhtyktxn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtsthsejcn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtehaklpqc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtajozdqea.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtbtrsxywi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtpxclbpeg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtgfhxjbyw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtastmrvwj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtvieplfmg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtduslvapw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtehelthni.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtzevwlovo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdhoyghv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvrykmgtb.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gthctgvwqx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyxoguhfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtwkbwpuxq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gttjlymuci.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtxnlheaee.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtqrgwvbiz.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfedvmur.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtwchzgrwl.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gttsaanzqw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtuwrtkire.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtiyaccplo.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmgbzgqc.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtpbzxjjug.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtoyajsejc.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtkmcszlog.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtrgdasflh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtplnndtsg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtkkalurgk.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtypqsdvpb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtxwrkrewe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtkgewmnyp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtowdmyygd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtpzdoadsc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtaiynhqei.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtesgbtnqg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtwwkcbzpr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtxgcrqveu.html


<!-- 参考信息 -->