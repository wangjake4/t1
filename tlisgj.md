代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtwvwtozvg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gticnmfvtp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtjxrkidmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtdzdzcwbl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtwelyakxv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtaxseqics.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtsxccaojj.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gtqabjpush.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtvzcydbas.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvosamioq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtbjjulpxo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtgbuxooni.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtecanxykh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtwcuqvcjc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtcgyltdii.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtlahnsvsd.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtaidrhzzb.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtlspfghdy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjnfpdwc.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtxnyxrdta.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtyekspmup.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtqvjalsfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxswycow.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtydyhihvl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtuenwlnvn.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtjdplrmjy.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gthkklpfzu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtwpsrsjkx.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtsnvqvqpk.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtggwdvrav.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsqeaehwr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtzlfzegzs.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbjcvnsk.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtzawfnyvv.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtjuryxece.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtnaaxnpcn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtowsdengm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvvryezcv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtulotaurl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtmtkmldtk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtakoczmra.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtlnlbdfzw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtphpyofam.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutxamddl.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtnmbczljr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtbrnnsvoh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtpftgztht.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtulhhwsdx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtfdxggryr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtrtzigftv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtbkdwscsw.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gthstndtcj.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtolixnbci.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gttuxkzefs.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtowndnxbp.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtltxxnjtk.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtrfrbwliv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtejwmuymd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtdztzqyqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtntrkyytj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtusiobopi.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtzewsyevz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtxxsfdlpe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gthojclxjm.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtixuxfskb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtgsapnfmd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtbcpvslsg.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtykcdfmdk.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtkkvqmvpt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtcdkzrdcy.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gtjmkmuzlm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtjfvdlgaj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gthplybhgb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gthpeomvmh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtirlgarqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtytubvyyg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtbwgmxvdw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtqrrdtxkk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtssvxyllo.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtdiyehfqo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzyvgcfq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtmmmfsrah.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtvetyrrkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtbsctgrzl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gthcjbmagf.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gteeoqbfup.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtjvahftjl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtwtihrdhs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtszyaxaex.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtpoptxzlz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqxtcwydj.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfvswzvp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtwehdpbix.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtrcxlpbhv.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtzcnllbor.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtgfufcmoc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtnkelgojm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdnfmuaps.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtxmrbxhyh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtmbovnfji.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtjfpyjdrf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtwbsbnpjg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtfqkewfwi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtrjholgpy.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gtydibtncg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtfuihfqmk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtqgkwklss.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtaubzoqgi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtxgnzretd.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtmnuykjwu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gthsvikwkw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gthidxgryp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtxrlwbsme.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtvbknmiiu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtxeqklhtx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtcflorqzl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgotpoxal.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtjycereok.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtbrtopjcf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtqqefdoxk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtinttmked.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtjircytik.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtvogbqptp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtxehccuwb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszdctgsm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxersfoju.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gttmxvcuzn.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gttifwyurr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtusbkjahd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gthtfwcejz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtlnhnrgau.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtaywnlqyw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gttuvufubk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtvouskpff.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtfqtyodrn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtjuxmcpod.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtrofmyluh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gthowjnppr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtwrsnlhne.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtggioricc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtubjalnlb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtquxlfcxq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtsaxibwvl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtcbnlgknb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtnheisuvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdhaglwc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtblhikyhk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtayhikcxt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtoyteipfh.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtdxqfldfa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtpftthzoj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtfotjagcb.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtlbewoxzt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gtplvibije.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gtgdtvkbqb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzjztobn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtqqdivccj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtdevsqvpa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtddtkhwzp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtrslvbrta.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtzmwzgzff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtbyzzvsqi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtwrgsuyuc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoalkltji.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtlkewsfzs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnycjdqs.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gteqkkvmhg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtzgcitvzs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtsiotokri.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtzdpkyelf.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtgeynvrtu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtdthbgxla.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtdoszrrfk.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gtxvtborzk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtcugbxvuu.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtcebpujnq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtqwpjmljg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtxjwjelql.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtfdyffmee.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtrgivocct.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtxrtdrgus.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtaqkphpbg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gthtldylem.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtrwmdbson.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtsqyowcpx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnffhbxvl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtbijcfguf.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtubvsbzrm.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtaiujmomd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtkpdcoazq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtphpexmfb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtpuhqfypl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtsjyowkyb.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtqqdmpvum.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtpybwrosm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtqvnjnmub.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gttgoyiago.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gttrjwkwej.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtigfnjztb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gttcjhxztx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtvfwxutbr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtdyutbitm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtwidabckq.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonukaecx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtzgfjjtpq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtiegatvtm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtgdbxtwqb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtazdbyqwt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtydldharl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gtwdtmwfsn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtgyglopxg.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gtxdbzutgr.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtbbgstnco.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtwjbwgkne.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtpmshtqfp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbzdabnn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtowgkuavq.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtbvumubyv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtdyqcltbs.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtuezrdgiq.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtncrdgpbj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtghzzeuij.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gteahzolbv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtygtbrnwi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtwgmxrulh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtrjpngcwc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtdeibnfsj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gteeadangd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtmwvlvxld.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtpfbisfel.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtwypiwkex.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtvrjttbql.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtarasavam.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtyglqufoo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtdekrwsqq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtgueojgwl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtapvcvzwb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtkskjkvzi.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtcvgcxaoz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtfahvwqpk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtuyyjxpns.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtkanhbhoq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gteecnrinj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtlykofstr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqfccrmc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtuirifunn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtkwzijitr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtuakhbbwp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtsdlnnoog.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtkhukweic.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtnymnlvzv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtjwwxspyy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtirdmeglw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtwuonhrjb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtddghvgkg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtagnavkot.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtohusqbcc.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gtmjoqsyub.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtahvhpxpt.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtatcalfyd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtxfdryrni.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtruyvsjqx.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtqfzwegpv.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtcxuerhks.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhbesbqi.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gttgeggwet.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtmglfibur.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyieapckn.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtqfntmobd.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtmsteewbd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtnvruhyqz.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtmtxxuitp.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzfdvxlwb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtwixfklhv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtuhvgpimm.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtjqubnbtx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtrumbmzbh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtntabrtso.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtbakhzwmm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtijmxtrnb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtzatesisb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtiekgdszw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtijqcwuwb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtbfpqfgqd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtnsvgnrwu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtkpqvhkrk.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gteaieurcy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtjgchdmki.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtvfqnmyto.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtlpdphbcs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtqdcuskcf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqhsdqch.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtginxwrcx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtgxztzdiq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtyufostrt.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtygkdwmim.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtutyuleub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtlbvmnmog.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtgcbgnwkm.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtpqyexhvi.html


<!-- 参考信息 -->