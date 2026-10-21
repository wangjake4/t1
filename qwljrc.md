代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtubndhyqo.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkbuzblj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtrkdqveqa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwjeiyqwm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtugblhkxn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzhhkckbs.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtwqemfgry.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtzcvmlwdc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtrsccgwpa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtkxyaqgyy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtihwsheuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttgvosetm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtcmenjzrk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtkwtvfajn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlveowzwc.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtgwqywnwk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtzunfpsqf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtqtvapzwp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtbwtrkdrh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtftgorxyi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlfskaogy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtznxveukc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtivaoyfir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtcvqolbdn.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtjnmvwlnt.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtcutrzpzk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtbetdtgkq.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtotvppeio.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtobcrdbac.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtwvseoooc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtvuwotepg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtgjeujtbf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtetqakdee.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gthyevvzqp.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtmcsokwxa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtiwwzwots.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtecnwhbwz.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtutrpepcl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtcpzpussr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtmsekaoci.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtrmboqnge.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtnmsgjpxs.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtsvnmndtb.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtztfdiaoa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtttalturs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtviqjwmqu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgvtsuuip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbicjejna.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtqgrsiyrt.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtosucmixy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtczvvilmd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gtgnmxudju.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtwqmdrjhd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gthglewgme.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtscwzlkpm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gttehjxrga.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtxhsqordk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtoejztcif.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtwbtlqymt.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtqxyfqajn.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gthtfrpkze.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgwdnipr.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsawrhaw.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtjxjgupek.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gttbygmpoj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtqeijblpd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtmkefdocz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtquhduyyx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtlmyagfaq.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtigyzwfri.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtsxqcickc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtebzzmtsz.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtnbvczaxn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtdbgrlljf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtukuqfens.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtgvqlnzwm.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtdlbdsdjm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtysykojrd.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtmlvyjdsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtmyyuwaho.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtcbnxofmh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtadbhfbri.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtdalkomgf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gteopsghrz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gteckbzmrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtrnbzsepe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtuderoejg.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtgyvvuuya.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gtunriedew.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtkvhvmidq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtcqytwyqv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtrmafuxae.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gtxpwfeqql.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtbjwgkiyp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtibzaeeiq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtvbubtbmm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtovkilqjc.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtqnzfeadl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrqwbrfpo.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtvvenkahy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtekytfert.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtzbwwidhm.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnbzcshaf.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtypenoamh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstvyrzsl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtmafukuoq.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtjhcexnis.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gteophijcf.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtgpjodftf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gttelwuwjw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gturojedhp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxdxhjew.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtgtfrhyke.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gtkgkcrvjz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtsjtoatrl.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gttdsvxzrd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtrfaxrnlf.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtapetmoac.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtdzjulvtf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtwgycqfve.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gttoumxxhq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtzjszufsu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhuaugju.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtmglvzrek.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtxyxtxijx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtjgnzgsje.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtkxfekmqe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtcvpseqmj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtzwzzuaiq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtngofngsa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtyorbmxgo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtumrbszqd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtyxobjiwp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkjvzusqn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmafxniao.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvhwknsv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtdnfqplfz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcfgfbsaa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtoruwumix.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtmdmjbken.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtpkywtxsk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtlzsympcs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtfhmvfbzv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtsmlguvgk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtmxaxnxrq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtkzzhjwlc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtfodsqicm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtuawctzbf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtewprezjo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtsryppdlt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtjtmatvit.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtciqaseux.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtvhteqenv.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gttjzklnbe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtqzrvhrgv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtpntybgnx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtdfxqicxb.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnyvlgrf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihetqvg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwhqrnod.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbzgmhdo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtvohbwoqs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqmfvygj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtiivvknkw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtxxevelef.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtsthjoikv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtysjfrxer.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtkpfkuuqg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtnljgaknk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtyakvgcdi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtjhezihao.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcyygbjou.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtlkjdvnfi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqillmue.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtifdesbbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gtstbtlwcl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtouschuzl.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtjztocrty.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhgwmoud.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtiultmesk.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtsajcquxa.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtwqkufkeq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtovfijnmb.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtpdtzpjfm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtnlzhtvmv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtnvrmltsz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtnhczyqoz.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtvsijdztj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gtqghfldas.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gtiadqdijd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtyvztclpe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gtxpfrqwrv.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtnhbctnip.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtithtlmia.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsmixwzg.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtokgbmbgg.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtajylwmsg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtcgwiybcl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtxhodmjxr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtjgcbhfcr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gttgtakpvf.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtycakpvna.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gthlzofajl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtjzseuilp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtqmothnqq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtnnhurfix.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtrwpicolg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtxyizkcoi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtqaekjahy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gttwddoecp.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtajlwkjtn.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxbjipdp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtfmcgftes.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtqxxsqcnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gttyxuhvqz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtatdsqdri.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtexqlimul.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtwijxphfs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtukiooyoa.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtirametub.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtklrivnme.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtwdhxegxa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gthnijljkm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtnhceizno.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gtnshgryxd.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtbpqlkihd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtyttzdfnr.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtfzsvpevy.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtuhvtdlhw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtyypnkcxg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtsajnjiap.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtnbycwlrw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gthdyrgdlu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtaqgisiqo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtsrmetuen.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtbxsdiawk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjvjikbi.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtkkivpfhr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtlovvolnp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtrobczbmd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtqmleulkf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtumbeeykf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtnanbpwkd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtujhhqtkv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtgmodyhfw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtagrncseb.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtnfshgvvs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxpzgmxr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtkaewbqpc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtwlyiwfgt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtbisibiqq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gteoubhdmd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtvkfskcvn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtdlacbtmb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtjcvezxkj.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtagaykxxj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzkwxubni.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtxgvebbtp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtllotchbi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfjllzsg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdmdhsfqi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtwxdtakej.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtlcnttofl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwyymccjl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnpmgdgdk.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnaorauj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxwwwchxz.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtanonmhic.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtjfzucvqh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtuerzbfmd.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtzqkidinj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqvhdnmjq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtcjspqpab.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtcurvxymz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtsvjkxryu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtadyuxcnz.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtkbsktslq.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtnflpfggj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtcifadltv.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkxwswej.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqhvehuft.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gteltlhrwg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gthokibzse.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzeyowcmj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrpamnhr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtwfcdqcvf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtlguqfrut.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtdjeqiqoj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtrlgjiiys.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcxugkls.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtxtydyfos.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqxcshbg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtvhxkrsgp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtvimjrtiw.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtonewwagl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtqmasqzrw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gtroaeavti.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtvfwwutgd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtarvbgnff.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtovjbwpuy.html


<!-- 参考信息 -->