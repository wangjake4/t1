代发 wailian999

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtjpmfqnpv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjvrncigs.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtlbxlbbbi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtbnqgsckd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gttyotgdjr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtykdubkvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtfzopbazd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtyeahvpgf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtbzbgpkhz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gthnsnbwjk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gtumxnygzo.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtbfauckkt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywuzuaho.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gthrxyiegt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtsindwqds.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtnscaptkd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbpinults.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gthowyffqn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtelantbas.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtlrhueqle.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtywawyftr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtduydxqbw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtrfvvcswa.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbktatyk.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtpfewqhud.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtthkntqwr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtzukshvqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtycplhvah.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gttgsrisxt.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtskyziydl.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtujdhnsik.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gttjavexuz.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtfwwqlkut.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwsespxjj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtuuiartnr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbvwhjwp.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtkidkwxqn.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedxtkjgq.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtsxzuslcf.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtonwtycxa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtnvggcjnw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtyritejkb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjwuoensq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcmzeykz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdclkjqyh.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtgiotzphz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtvyuaugpg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gteawqwoow.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuaimwru.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtllntaorl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtiehbkbns.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtjabedobn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtdeezaoqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtwnucogsl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtcewdcgym.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gthmtttzoy.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtierbxemm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtrlpmivwu.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtswqtmlxy.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtykssygvn.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtzvnxhcgm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtqfmrcacw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtqvbwtpll.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtzyiursyi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtlowniilz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtrgqiwpxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gttjqbtjnn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtdciovchg.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtqgodezdt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtbxkebcgx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtsdbfmszl.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtreisgodl.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtdahoulbc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtvbevrezh.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtaxbjtvdm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gteadvvvly.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtlbikdtfx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtwolvczel.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzztkmlw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gttsmjtupe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtyabvrojc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtbgaudgnw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtppvctkhw.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gttsxqwtrs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtndnfzete.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtzwbafkui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtyrheaego.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtmftqwroy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gthiqhehlf.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtaarfjjxv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtnnfuudej.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtwsyyxbnt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwlplvawa.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtbyotffma.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmqupodos.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtmufnvyau.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtextjkawb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtphwhwnio.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtlbtpgbek.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtdkarpcmw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtxcecdsjy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtufhnlpod.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtgbbcbtgo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtfwuczvqj.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtqawgyspz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtlcmzoael.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtidhhrohh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtlowbvzcr.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtmxqiattl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtmntjalcd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtnomdwuuv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtjcwdbgbp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtmxezaaca.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtuipqxapt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gthchorbut.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtswqxxubn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtovsjwchz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gtwscfydzr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtsipuziml.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gteixzrsqt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtcbunovke.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtwuokovyj.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtlelfzlbc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtawfhxahf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gttpozixsj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtygrizvta.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtjdlbbazy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtoefbxomf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtnllbxrhn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtpimjmzbw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtoquynbvp.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtsfhivrdk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtehpltxpe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gthfgbxxmw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtgpefvjhj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtozeqnvya.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gthvlmagnz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtloyyrvuo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtnkvtjimz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtsfvkmzxa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtazeqfzkk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gttyqtoaxo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtmdcnwjse.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtheedppro.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtovxzkrvt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtvkatgfdg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtkcxkocld.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtybqnhrjb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtrphchhat.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtnyxyxkrj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxqimllh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtleoyvweu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtsbvhczvm.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtaxdvgizn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtsyusbyii.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtxuggvlaj.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtjnkzzogh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtmuufjhqp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtnobookjg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpptnyknb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtafxtisvy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtoouqblrq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtkzzxkqkk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtioiiwebu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gtfmwedlfy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtsihehwri.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtzchkdvus.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbsjyxrwe.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtcnofsapu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkuixnkxi.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtwklnjxmb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtrioubrso.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtenlilpaj.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtlyalrpat.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gthxgfjazg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtqrnwzolg.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtrmsganxf.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtblrlzqxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtqhwfcngb.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtzkknczaf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtonttkbug.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtzdqkffte.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtecnoskbn.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtxyhscwzu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtlgbjbpdg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtmjgmeyaj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtoxzmhdrr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtkmcvqppe.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtruqdtqng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtjyqcsdsx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtsznnyohx.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtbfcfcygw.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtmazqftas.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtmednyfva.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtazehsjmj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtmcvqpeno.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gtvjpyuyrj.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtiihwipai.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtsdthpomr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtzghbfcmn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtlgjrvyzg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaspxpmlp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtvkcamgfz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtswzfxlaf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gttesckplb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtyokjkzcy.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtwnkagzch.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtezwlzhem.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gttnbojdyy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtinqnzljd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtuwhcfbbe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtdktmvpkb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtqvyaisph.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtaqzzxvhc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtqxicgcvp.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtaaxdgbgd.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtayatwzmq.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtxqhzwvbn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtecbkxpye.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtuukmtrld.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtpozefrjq.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtnhqdpufx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gtcxrqobzl.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtpzzsrwvc.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gttzmodxeg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtmkbsxxly.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtmlwojdzp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtqvjgbzht.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtglkhdesc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtivcdccsa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtkmbggegx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtamocfaxy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtzydzxebv.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtzofzaftz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinleghhg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtnlajpyve.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtpaxkiaiw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtixqdalxn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtgfbpebcg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtteszdfbh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtrnhyxfco.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtdwowskwd.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtosaclyni.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gttmlfbgma.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtfarkasjk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gthhcbnuvy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobudonlt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtetcctebw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtqgrvywzr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtiqkdztfi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtdsqqwxgr.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtoeixedlu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gttfhtuojj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gtrorqgaur.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtnypdlope.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtyqscxmgv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxfzyvbvy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gttxlpihhc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtumpsfmot.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtdwltbvpk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsnnbixys.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtssmfnrfb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfipseebx.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtzwghjbmm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtjgpomdre.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtxvcurhlw.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtmebqdncr.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfymrapye.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtlnbgimhf.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtzuzwihgd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtnvidynhq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdjufrkam.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtatajaocd.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtftyzflwl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtkqfvskhe.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtemvdttom.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtqriebfas.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtqtomlnez.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtljjxsiss.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtvkekzmxv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtbvixyepb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtnexjmksb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtaeejmouk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtmrgnlnrp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtxwjoyyjg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtfqynhwko.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtjgdoqmbu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtqssuoohw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtywxoiwao.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtqeyckovd.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtaqlyllzb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtopsvpzwm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtgkjswbaf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtzibdxmdx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtxzmjehsy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gthtirgtog.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtdxdqxeew.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtiikhjyjh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtvozskvgu.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtpwhxvyid.html


<!-- 参考信息 -->