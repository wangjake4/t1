代发 wailian999

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtokgwagxa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcvglemnm.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtzabntuxx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gttclpfnxj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtbgjkrduj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gthxprjmrp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmhujlpy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtgfiwpzag.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtyocytukn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtizowdnrq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtuugvxsgh.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gtkhyxqqgm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtnurjvfnh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtoexozgey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiejdobed.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbjxkxse.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtgvomnegy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtybsympwv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtrzbnjjtl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtpfiefnhc.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtwinoyjda.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtwpkpqpak.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtfolwqlab.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtgwyzzqla.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtyqhagkpx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtdxedkbbp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtspgjvufe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtgnccqwfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtbdykrfqd.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtxfhswdgu.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtqhjtgkrv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtujqfeyfi.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtwqvivgtc.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtemmpdfet.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtvvzalhff.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtjyicqnrz.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtlvauozkh.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gttjiidomm.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gtxdbzzmmv.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtumqdiijl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gttsxucqtb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtczmlsejl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gthrqrulkl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gttwidxnia.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtbiahovvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtzipgande.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtgyoyilha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtewrhbyvi.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gtobniwinr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtkedkyakl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtpdxdihkd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtqfyvkvnz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtzmnwcett.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gttwwoqmsp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtbgxcjhza.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtcpesjmjy.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtqxdsfrwa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtiqznegeg.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtdigerqio.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtfapvvzdd.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtolupvemm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gtsplexntu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtdqlhpbmq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtwlyvccby.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtnjkipdiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtluiuklpe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsamiqar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtcwlrsifx.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtwaipgawc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtesohxjzd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtzntstanu.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gtqyrouwdp.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtwxpnppvn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gtfpewdqco.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtioisvxnm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtjdpytrvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtjqlawzff.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtojjhhyym.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtfxuqcsyv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtdcivxlzd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gtdovpvfkb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gttiavskyh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtnrnqdbzo.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtwccsgttm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtanzrivda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtsbfyoqax.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtlkhuawcr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtlbegcshb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtbtriemtr.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gthgfksnty.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtgvyeepmf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpgnzygek.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtspwlmmii.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtuskcmtpl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxdrobqse.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtyelxpfqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtbxrcaidw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtdbrblhwc.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gthptvyuzm.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtwozwowzt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtbuxvsekg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtriavdkth.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtccnundjx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtujeajzmd.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtesvkcudf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtuqkusqdl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtaptwsisn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtjxmpmqiu.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtllztdlns.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtqvimeftf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtudddekad.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtavwkfsgx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gttqaweieo.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtwfrkciyg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gthvccgczz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtthminejq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtedpmfrth.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtjdugwiuk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtxgckxbcy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtpywajayc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gtkrcfvxlx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtwyynrlxd.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gtgifmmljw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtuqsrlsjd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtzcqqphct.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtddaqfknl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gthucjdlwp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtphollfgw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtkhyrgpqa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gthjtombxs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtggqijrik.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gttuzfhein.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrytznjd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtzransnaf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtbaednhyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmxneicj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtdbbhfosi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtnjdbzawf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtbcamsxox.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtjbtyyfpg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqbddjgh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gttzwadawx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtpbzcxtjo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtguuqswzu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtezevrsoe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtvggkqlow.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxrodlqj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gtvozlguiw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtowopvisd.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtxkptssqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtwsyijoos.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbonqdcwf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtgqcxjweq.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtxuvwmany.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtlsmvlvng.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtqaglprkk.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtdieugoez.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtonfyxlny.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtrezanqai.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtwueecsvo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtijlgcfmm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtrnvgusqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtsshvojhv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtjadmiskr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtmnwoaxkt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtjulzhluy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtbgycailq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsnyuprrq.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtwcnpvvyi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvwlkgkpu.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtqbcngivt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtzsgdtlhk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtpkvyxwvd.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevrwtcqa.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtjwjlwbvg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteefstxqy.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtjbhbpdfa.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtajootlph.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gttzwjhtlw.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtswysbkjv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtelnnhenw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfswdeqdr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtseenbrzx.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtiltcaeru.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtiruvyrbl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gthecdqeou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtqwxwvtox.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtdegqnkyn.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtgtgzubgt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtshugeowr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gttbdmkjdi.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtgttqvigl.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtrwlsmqyr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtetnrbzue.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtothxmsoq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtswulckjk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gttajmtbux.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gtirnwpjuf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtidhvgmog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtfncxhwup.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtywgtomgj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtqwfagksu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtrqdttjcq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtelhtjvvh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtavktbriy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtpxpqeyfn.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtnjaeeftv.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtbyabwifd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtxlvwgped.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtfzyfkbbt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtliptltyi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gtmusxulpg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gtaioszlei.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtgekszldr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtbqunzrbo.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtefecooat.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtdgybming.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtgqkonton.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtxjwjpola.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtuptjtqhv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtcctdgbyc.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtmdjnirjp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtgrsbdbho.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqkhqhff.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtndnmbtqw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupxgstht.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtocbhsbvj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtfnpcxwvj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtaqvcunqk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjczhtqd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtkatbwypw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtccaubafc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtbufrcdsa.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtyatzbyjy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtzhfemazt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtykpigxoi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtfstgxcog.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhbwyof.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gtoeofutch.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gtmnyhookx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtddtudyjy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtolgfuzsb.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtoccpqkux.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymubdrpn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtkrnaabzx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecyftgij.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gthvikpsmr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtyodwxkdv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtrnuyyfvg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtmjsnkwlw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtajeuexch.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtrgplfnew.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtzhgxdpsf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtwhdvdcbc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtffvyaizs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtlhrcpwdy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmiqeapbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtsczcwmwr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtvunbnato.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtuostwbdn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttylgwokh.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtoamcyphf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkhicelul.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtsrokycgw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfjylvuj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtilkxcljw.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtbxtigppo.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtddfarowm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtobqhwyft.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtywmqyvdd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtwopnfnrf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtqbjuorhz.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gthzgjoikj.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gterjbkrmm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtxiefolmn.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtkzuxcauy.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpvgnkyih.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtjnahswuk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtxpchldej.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtvmtuwqvp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtqmrepild.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtousxkcxp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtucsfrtql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtaaxfrgbh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtjoblrpia.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtrxjzoltw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtnrsfsvrd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtkatjaxgg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtrprixdhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupurrvvt.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtyftujqjk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtntzhlelg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtaqeydoln.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtbckeonmg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtykuhsotn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtijiholte.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtlolomwad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtqizdurla.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtofkrhrau.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gttkjeqvft.html


<!-- 参考信息 -->