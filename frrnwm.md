代发 wailian999

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2cshmoeyi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2oshhaiyg.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2xbnyjoik.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gt2nmoqxsre.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2xjnbinfb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2hduqvvyr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2fcwoxxhw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2pruymhpx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2aluzpjrk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2skoojxxm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndnjqfpq.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2ctusgtkt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbakashp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2elltmkjw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2vmylnvno.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2wjszlrgc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2faztacfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2nogsumgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2hnxuqulm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2vdvwgnku.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2kshykahi.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkjkrcuf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2fjvdpcbv.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2qrqjutim.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2xhgcnhzi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2eggnpiko.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2tesvyqfw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2negteaxf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2nmhfmypx.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2xuetesvv.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2wzlouoll.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2qwniaigv.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xdyzbxfa.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2sctuzhuv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2idtotgnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugrgmcbi.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2zcnggira.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gt2halkfqyv.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2vwpmeugv.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gt2nvuryquk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2detmvtez.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2cdjvawnk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2xdatcoiq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2inhkbcoz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2zmvbvird.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gt2photwcex.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gt2zhbypedh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gt2usjbmnbw.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzwapeip.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2fimfnapg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2uewmvivt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2ovtucvew.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gt2afiazapq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gt2onbxgxdm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2gnkppumn.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gt2ilevhdad.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gt2wyzfubbo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2qsapnime.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2raipurmv.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2shycdfiz.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2wgktccaa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2ctryxxvd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwfswdpi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjrtwoqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rblbebrx.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2knqgnxab.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gt2boymjrqb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2cgtuateh.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gt2lorycvnp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpvudqmb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2cpilmpgt.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2wszvwqdx.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gt2imtvwcka.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gt2cvgkyhrf.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2vknzpnje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqxppzqy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gt2wmbmltks.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gt2fqhitmzs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gt2ncpjsorf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2zslzcebj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gt2fajykvfr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gt2izsukohj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2vyhurwlf.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2xyelcpjl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gt2ypkjfzdh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cupnwjhk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2bohrzuxl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2knftiskb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2rpijuhjr.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2pyhlcbcr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2pxppseox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2odrawwkw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2iquiwxde.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2xoqsqigx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayepiprs.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gt2rrfupgau.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2ccjmlnyu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2vzhwnbry.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2mttvvheb.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2uynsafdj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2gkbagfpf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rihtfgkf.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elnaoxbz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2sxptjtuf.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gt2kszuixkd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2edepvypv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2cwnfatwp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujtuvtue.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2opqabomh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2hvzdywym.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkqlmdwm.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2mnnuhiwk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajtrizyz.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hatasejm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gt2sppmkgft.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2xbcfgvtj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2ftbfohpo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gt2rajbyyff.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2ojqgfaxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixtaifsr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gt2qfzfpfsq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2pjbgqhjh.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrteuzlh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2imungrie.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2wajpnrrb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2khwxbpue.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubygommy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkvqgthi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2rseezufg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2rzgxqykz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2lywunose.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2ryxsdgbi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gt2yfnapbdk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2pdlchyyf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2kvftjvda.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2ylpwdyyu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwrjzgsc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2difztqkd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2iausmmej.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxdbgxmo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gt2jmsujzkd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2mfflnlii.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2jrjmmcxg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2xzwxllkh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2uqdpxuhw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2cunkzxyn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gt2icdajmkp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gt2dpglltax.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2zxzdvngz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gt2wknwxdrf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2blgdflbr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2lmalztxn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2lygvrayj.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmkktpbr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2hpwojcdc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gt2lpcwvcfh.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2fymbqqkl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gt2mfqfyfrx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyxbuezp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gt2atrfpcsp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2nbgtzjpd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2cragagez.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2idcjnqyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2sgbnekgi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2dteinfgr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2jsypgnuy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2rcyhfful.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2meorzdls.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2bllpmvde.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2opnqyssi.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2enqvlcsk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2hdjfeejk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2ufoclafc.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2gxvntkgp.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2ywogotre.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gt2wkbnxgul.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2drjrhith.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gt2zamoybxw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmpvgvdp.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2dqqfknle.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2qsllwjtz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2wdcgjotm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2yzjoqhkr.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gt2eslnxlnn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2rndmratf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2jzjnbxno.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2owmvkjnz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfuztcfj.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gt2imolapxm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gt2ryqpojgk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2ifjarlwi.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2ritpxgzr.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2kqbxxywh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2hltliblw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2jarjmutr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2psowpylo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gt2ztfyiypj.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2rlknphlj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2ayyxecia.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gt2xcpveqqw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2jzddcsle.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2soocltjo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2pxawkbbm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gt2evburrah.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgjpiadl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2oxxhzovf.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2vdniptao.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2ahbqdbme.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2unkhjsfr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2zkqcyuhx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2agspvbjp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kasqrmsm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2mzntmqlu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gt2ptsnovqx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2aewimnee.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gt2qefixuul.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2tfjgioyv.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2nkvkimsw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gt2bsolfszm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gt2tceksczm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2awcgcnkm.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gt2iaosmljs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gt2zgzeziwk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2bmvavtxs.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gt2yjryuvva.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2mohuducf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhplhbie.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpxpfost.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2eaynustk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgdcboak.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2qmgzrlqt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2ywrcnwjb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2drjtxqjx.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2yrncgkkd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2lcuwtfhd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2dlxqpccz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gt2uwktgrxw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caacnbhg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgqxkrny.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuebfgjf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2adxolxdu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftfwosty.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2ctbetbnn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2nmmpkqmn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvzrlvvn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2rqbnmhba.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2dabjhvun.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2ybmskxis.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2btjorxlo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2vvzygxwb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2vwqgicng.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2wthhvcvs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2ptwkgjgp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2ausfijcb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gt2oktkvxmt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2rupjcleo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gt2kvegdzlr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2abxiphwa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2ugqnrinp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2mlimqxbq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lypzngfw.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2sacptwph.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ehcnccjn.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2oapqaann.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2pcdzzjge.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2wjxcwkpc.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhnqhfxv.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2dbtyjlrf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2kjvuhfxi.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2khzuyypi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2uttpibov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2qlqfftyb.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gt2qxfylpfm.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2zryuslnl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2ysmdqjua.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2tctgvicu.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2fzmhjicw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gt2qhwixruy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2aruoskwl.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2onrqkqib.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gt2qeolmyxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2ldzhdylw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2ubfxpnll.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2hbtywkkx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2icweytec.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2mcvldajz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gt2doocjwhb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2pqzelubx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ogmpbxtv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2rvpmqasq.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ehuuvegt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2rfqmfvge.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eguifamj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2ohcrkgnz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2oqfgnnpy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2okgabdgf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bngikufa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2hxrcmtyc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2ivjgztuz.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gt2kjbhuuqc.html


<!-- 参考信息 -->