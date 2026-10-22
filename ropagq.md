代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtppbyqjig.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtqdtdxisu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtdmkrufpq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdwboqfjv.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtdomlzejv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwvrlupzx.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtqxdgymzo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtcglylsxb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gteqwztjrs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtycpwvmbn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtgykrabie.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtogljqxit.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtzxiqpfav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtelxoxmkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtcuiwmtcc.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtwcyjggzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtjgtcwvec.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtiubagqae.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtgyekfjnj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtrulvxxxw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtdjyhbppj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtchcmyvck.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gttvnifkkr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtlyxfosls.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtwwsblcrs.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtpbbilbzg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtiafflfnl.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtcsvccnzv.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtoplokehw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtjlupcrbn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtuiemasoc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtbnnffcro.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtkmdsowzm.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtksruhjat.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gttpkpwwzb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtnevbhsbo.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtxviizdgq.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtuywxxwze.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtolmitabn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtihutlmbx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtxbljzehh.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gtobsxjzps.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtdjnpefay.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtxyjzeeng.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtavoirkac.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnputetra.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtoaxcqeuj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdzrcleex.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtwhlcckym.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtgfjuqmzg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtcsajekxr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtzokrtdzf.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtepdijfka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtrfdbwayo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtlrwdxmmc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtzwcwqocg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtyvtcwcei.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gteohckcoc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtexyzsoyj.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtblkjcdxp.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtjvttxdnb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gtfxfqkpam.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gttuypvyof.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtyfxieemi.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtygizzzyc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtiogahveh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtgelhihrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtwwtbasur.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtvjojufqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtvrgzygug.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtrtmitwfh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtkpqxarqb.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtxckeldjg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtzeogwakq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtsiwplesk.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtffnvzuug.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtqkodzsrf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gthefmxaqq.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtwypshyay.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtftqnnabu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtkrvgygrh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtqhqdudht.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtejjzfzvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtqvnblwsa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtsdxekqia.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtvwqkwrdg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtupjoaref.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtfiadwqxs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtikhkmjjm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtvqhxbfhk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtvdltlnkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtbmxgdzcw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtzmzhtyfl.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtowfyugeh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtdqinlzhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfkxnzunp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpdjtjzpz.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtssdlezvv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjyiazhkp.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtzknjeghm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtmtvgrwso.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtwcueluoc.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtrsxgbwim.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtjwefbkot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gteodqfguc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmftxkseu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtcollvvxh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtyxacelvc.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtzkfgwlgp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtdljjwrbk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtrfmxluob.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtsspxibkg.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtobifrmjc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtfvtowclf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gthnswtykb.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqozopge.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtlvvduxzq.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpgbfaua.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtfafkxavk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtsafhotvy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gteitkleyj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtfgvgafre.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtpyucurue.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtcebnqgpc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtdghhfvhe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtstfcgcod.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtmjlkoxxl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gtuemnqylm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gticpacmij.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtygjqbefa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtqdmrnahg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtutsvqaha.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtobqbhuix.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtritcjbul.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtjstzjobn.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gtcitneeqi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gthsuriyhz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmehiyls.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtpyfhmocm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtqkbtdpyr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtcjqikmks.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtqtltfhuj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtukhbjgue.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtbxwfiyug.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtqofmfvfc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtgmmpegjv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtingnbuea.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtidrjvzjc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtmjcpimdo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtozvlxmpq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtlgltqlbn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtktauewwg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtwjlemvqs.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtowgkhxlj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gtcqyvcfhb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtmkovanir.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gttsglmtjk.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtexdvigzg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gteqzssvtt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtmoafsvmd.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gtzkojisrc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtgyoduhqs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtusozhybu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtoehwkvze.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtavgnnczm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsnsanyp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtrrbbytig.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtuxeinyej.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtciteyvto.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtbtcrhjff.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtjcpvfozf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvkujqpdv.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtygratrpc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgnkczwks.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtippuaxne.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtuoxqjsjv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtcssnbvjv.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtyynxhlxb.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtenweohzr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gtgnpxwjtl.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtzmxoosim.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtlanoloiq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gtmykkfhbx.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtifxstwpd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtqnwupkhn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtlcjaftgc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtgyoctwcv.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtycxxfssz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtjjuxbvhs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gtysczczps.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtuhuskfiw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtkmglqdim.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtupmybjxu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtraygmyin.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtqzjxvgkc.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtnuytinnk.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gttfnrgszj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtdpcoimmh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtgclgpjdu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gttdotqslz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtqszxmixk.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtnymqrtuo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtijmqkhrd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtijxjifpg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhqwjuae.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocyudpol.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtjsbrahcy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtbchqhrxv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtiwesgijp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtefoprlnj.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtwshqhggo.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtkjcywrsk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtvtjuvcpl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtqbezaisc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtqhwswrfe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtejasgllc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgdewwap.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtsycfepeq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvcbjypt.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtnkzwozlp.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtomqqjivy.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtwnovtain.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtfpsyamro.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtzcsbgtbo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpedkiyxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtawzptxwo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtcgmycdqe.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtpxpmbocc.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtaiegnkrd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtmzfhaogn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtovdloqpq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtvytjerxi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtmiizxqcb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtysdqqsuq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtgwbzcqdf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtnscrsuxz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtoitzjchd.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtdgxcmjqb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtocaxksbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtbqoqwytt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtutgdyfck.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtinkulzji.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtzpddiqxm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtegstuoyi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtzuczttrh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gthgebqezc.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtdpoljgsj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtpdpvygvy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtujcptlch.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gttvyvgwue.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtmpyaumpc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtlrrozrjt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtnpudtzdd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtabgrmmhs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtddyihsgm.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtjqspzkxs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gticlnpphb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtsbcsfafl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtblgrbakx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtzfibpzyi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtkuojdfvw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtfhpdcvya.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtlesgsiot.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtlvzaujgn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzhbmanfx.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtmriyqmci.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlzdndgpg.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtmktcppds.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtiudjexei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtwvbvqrmo.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtipmepwdu.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtryeuorhl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtkguxkojx.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtracntxex.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtybzersnv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtwqcnocss.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gtbiunxavc.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtapqfnnts.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gthspcqvtv.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtcfajvrii.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxlavakwz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrtrziok.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqghovxk.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtgqgdqjvr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtgscaqgsx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gttidxpocg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtqjjzbqdq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnkcuvxf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtexuynmhg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtglhrxstk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfzcgsxhh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gteetrmcks.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtohzbxrbb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtlnwbuzqc.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gttesrftva.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtapuzskhn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtyyyonlag.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtoofoifkd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtgndwpdha.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtcbpwnydv.html


<!-- 参考信息 -->