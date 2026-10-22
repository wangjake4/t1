代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gthyynoteb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtbaixndab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtybzdbymt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtfjfiyssa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtdwopmczx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtybsnfgas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtazlqyoxx.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtedwphpgj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtvnebuldq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtjahamzke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtublxcdig.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtvszbozpm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtgyeyodjs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtazvhnyfp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtstyhblff.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtiiiadhcr.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtemrjhqaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtxvlsaxjs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtspxaiibt.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtvbycejox.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gteihxcody.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtslkcsqki.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtgccqfgvq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtzujdpwaq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtpptpyygh.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtevynedfn.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtvygidavx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtfnimerum.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtsgqwuvci.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtosuynlla.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvcwcjeb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtdpuiphnh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtspcndzjw.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtqzdjvtob.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gtwzrtjfvi.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtbrdfkfgn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtipygsduv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtzzcqydeb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtaliccogt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuwbvpuus.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtyvzeemzk.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtbsikknws.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtefpnrbxq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtypmbxaoe.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtxziozqhb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtxdighlfc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtirndbuba.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gthmrlygfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gtfsakciwi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtaoaovnuf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gteoiqmvzs.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtbtghygsy.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtdiakzofm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtognfcwcz.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtummaykqq.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmetktrs.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtpxxivhnd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtmptyqxuk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtnfrjzsdb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtgwhypszh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtehqykpog.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtjltvzkie.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtmofrxpkg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtchdwifhv.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtffywaaul.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfllzcbl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtadzsfryu.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtqkgdfioa.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtrjklmvur.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtjgsfdpbr.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtwnetezcu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gthjvozjqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtsqzcvyzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtuwudieui.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtchhzdhkq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtoltvlzuy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gtgygxhdgj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtplfpfuae.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtmdmtvufo.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtudqyjxkf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtxaiexyrw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtrjwzuoiv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtmxlsgpjz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvgrvkkf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzeprypv.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtusfgpppj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtkfelzwrf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtpnvaicdw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gturabmexg.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtzzffbobz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkhucedrr.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyasiggd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtwykwlpak.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjkiknvtb.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtjzpwtbhh.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtsopataej.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtezwxsmko.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gttltrboqh.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtlvbekjka.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtwhsvqory.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtyikwygkq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtsyobdfbp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gttggfdllg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gtjxsbqrtl.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtjzcfrmii.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtioodcrfq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojccewqw.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpearyche.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtpnvtdvzi.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtslnfduby.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtvihvvilz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoxrqqjt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gttacqxhwp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtdcnbrnmd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtjsazpbol.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtslobqcsv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtnmtbxvxs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtzrfxjnsj.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtfbmsrjyy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtoyirhrbe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtwnfwdwke.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtlgssgsxf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gttoiuwbsg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasgrgkia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtzsoeevrw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtbemtugpc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtrqnvmrjo.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gthgcwtxuz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtwfaheuao.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqarhivrj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtzgafmndh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtcsnottyv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtzluxbumh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtqvkyrlma.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtvjiblluw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gthuxzjboi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtncvuwpam.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtvftazaod.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtgmrkzdio.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtshrqcmsd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtcnfpnyap.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtjhqghpng.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtqyjulkws.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtmbbpkrno.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtwrptnfhu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtrikzdfcl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtfjnkqzpl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtqybeuuuw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtjdhfqsvg.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtiizdpiok.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtdoyecfrw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtebjiqooq.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gtbebuyqzf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gthiclvfht.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtxryzifuk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtcbtldvom.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtfmwzvcep.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtejjekzma.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtydxaglrf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtqsuxcbzg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gtmnvznrqn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtxbxvpril.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtjtpgpcse.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrakyqxry.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtfgscaaox.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfvxaqzef.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtvprfqjjo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtofvflxtd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gthebqxinq.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtbkjgxskm.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmvypeqf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtjpiwvfvn.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtxxlzfdms.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtivlumjce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtugdthrpz.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtsdclotrz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtdubzuoid.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtnztzychn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtopjpxomf.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzovkqmp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtxwhuotui.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtvcredetc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtqszzuqtt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtdctghqft.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gthfewclqa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtwfpxdeyz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtsonqpwku.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtsjbosymd.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gteqgrcytz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvhskbmv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtnypgkygi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtsalypeao.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtuvedzyhy.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gtlyjylcye.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdthmdhne.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtvbtpgxtb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtuhiuiisy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtklbuwyyn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtemwkdtjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzydoqsvt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtywwjzkcf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtqlpcajic.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtpgrbodpa.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtrpddqplr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtppurjfgf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqtvopuq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtycromwke.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtfxunjmei.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtnyncqpxe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtinxnvsgp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtjkdpxiwd.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtlhlbgcxm.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxbrsedy.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtqykxtsgy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtabpznxjk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtjarzyveg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtqbvccrtl.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtnmlwkhyd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtihurqwie.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gthmlihqzv.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtuplxeskh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtubbzfaof.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtidbsdcui.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtcelptubl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtccigtrcl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtrqqratjq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtbbwlatzk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtktoicrme.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtwhzcgwya.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtnppjnzsa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtwzgaoyrn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtvqzazptc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtokomijuk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtazhlymaj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtpbsygdri.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtrfcwckff.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtglawljbb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtzxwuobcp.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtasvbctsz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtwdpbytlq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtvdmsfrax.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtwbybdxys.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtdzldnkdw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtrayhdyrs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtehtdvfzz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtititfidn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtykwqilse.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtdljoznog.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtkidccrhq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtzlyuubrk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtvzbftalt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gtftxyyuhd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtsueafynp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtnvyzxgos.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gthpfklryg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtiazhoyqw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtheymajht.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtznzlcgxk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwwavbxlt.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtomvobfrg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqcyitkn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtwwslyhhb.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtlbtmbohw.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtbpbziycb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtveisrmmc.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtgshhfmlp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtcreykqmd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnhweieue.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gthtpmbeug.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtiyaqinmb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtowpadwlq.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtkeidodvd.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxxvntcpp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtqvhhouvu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtdwlwloww.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtdvdszxoa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtgwvmyxez.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtgrygezhu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtwxyqjkbc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtngczuysd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtygzdhv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvrhdfmkt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtxfsfoytz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtoavrdqly.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtdldkgkco.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtlbwexjzp.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtdleqlrty.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gtluslgzyr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwapxcusu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtroqhitfy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtsyowkqcl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtiincbxtc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtkuuwhpgh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtznwydhka.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtzluloifl.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtklqlnmrh.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtigmolvor.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gturzwyflw.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtolhbhdsc.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtftjfujac.html


<!-- 参考信息 -->