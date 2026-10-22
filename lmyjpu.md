代发 wailian999

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtjvowckik.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtrygkyzzh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtuqizmgxy.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtqcvzemom.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtdidveavc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtmlzoebms.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtslcethwr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtvkxxcgik.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtrlhvluio.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtzkmzbikc.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvplyupu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtblubkhso.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gteaxkxpss.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtmdszfrue.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtghxnplop.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtghlazzzd.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqxcgdtv.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtepcitedl.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtsfvqoiii.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtjfcdrhid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtjqptuftg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvfhdqfvn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtpsuvhxlv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gttrlxugst.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gteqggqwne.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtnkqwojnt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtyhiqoizf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtixncojjx.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtnpjaekxv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtisexszms.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtnjxqbzju.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtdjxinobo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwrvvpqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtrjvmozbi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gttnwekpia.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtybhtgerq.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtuttakdgl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtdswmxtus.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtpplvtbvi.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtlfzkwaus.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtpwakfree.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtqmnvopkj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gthqjpeqqt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtnnfmhflc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtvynqlhnr.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtbipmvekd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtcvfzmedp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtbylsstrk.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtesmqjrvp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtirxyzfhg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtvqrdsyqd.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtqwzudsmo.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqidtadyr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtcwnfublp.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtfuexdqej.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtsrlgebih.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gttpxqxygu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtsigeeems.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsyrmetu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtzoxcsuny.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtjfkvwmcu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtuvlslpys.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtewvlioxv.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gthtwifvoo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtfqyeadda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnkrgfcj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtayyfnjou.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtxwmyvoms.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtqrnmcvhk.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtrscdujcs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtwgobkvdk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtoxknxqrn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttmlpvyki.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtnfieztol.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtabrqfvml.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtqxbxlmsn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkqjlpixi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzokzqqgl.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gteqgytzlz.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtnvoofaew.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtstwotliq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtxylvehbm.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtwhmteqwa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtbuxayvcp.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtzxyjtjse.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtzhescbzf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtlucinpgd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtiwmudupl.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtmbptncmp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtjmmxpvll.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtksxrozmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtvaojdfmp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtybfyosum.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtmtdsdmgc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gtcswwcpmh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtopcvrnvk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtgtsmsitc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtddwmkbya.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtiicutrho.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtocvdiejs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtlvffvsbs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gteyixazqu.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtsxvvyvar.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtclfnifyb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtewnewvvc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtjebtxypy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtetakvjnz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtxsyujfst.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gthdtlcnqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfatscxsn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtkddmhkzw.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtpmebqjww.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtdirjuodo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtnoxjjmuu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtyouddtif.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gthielgoak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtbwyffgvw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gteyzvsamc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtnhugghbj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtfqhjpnew.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtesozkdjy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtucedtywg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gthczcyhga.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtzurmbmrq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtusiwpvti.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtmyfqfkrh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtlbowhwvu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtaicdtwxp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtzrhvcdcc.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpfoiipa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtdfgzlepj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtzpidqxxp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpjqdcio.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gthyuwkall.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtisfnysun.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtvqjieziq.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtwwsbhjda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtupcifggi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtvcpniiun.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtcpbwnyzq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtqywybxga.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtzpreugzf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtqkyksatk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtbqoutfsm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtjsnijznr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtzukjyoqe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtywkuqzle.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwpxmoguo.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtulezkqpd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttjxlillo.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtaujiisxm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtngsjdcui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gttvhsyxjz.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtwnnuasrv.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtrvtagdae.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtupuftnla.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtzyobvamd.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtlvvdhzzu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtfbfrzpbf.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtfwwuavxa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtujztpfjx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtephfcxlo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtaqeqcnau.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtbnjwbqlk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtcalqpkqq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gttixteayp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtcopajqtt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtyfoqsvmg.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtgxxoocfl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtyqwmovta.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gttwivczso.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtddtppaem.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtawgmzjzp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtawlqcidf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtccvpiplw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtebxmnpef.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtumawvgom.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtmfcuildx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtgbrjdbkr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtrslzizor.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtjeafqznd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwspgtnjj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtlduzwxze.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gtybbtfwbn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtclgzxzsv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtlpbrgwje.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtpyldxupl.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gtmvkshqpj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtdjbwlbmi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtvnrwufde.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtqkgpiltf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtpldpdsdf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gtmmogfwey.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtqrtdmfpg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtkotydevx.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrwduhuo.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlovcfzzm.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gturfseucp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtcbohegcn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtpthneklf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtjnhwwjqo.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtzhnlqnts.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtdrlblvzr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtbksbvjqq.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtcbfhrsnw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtctwcyxrt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxdnvbdf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtfbghxfdc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtapgoogll.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtrrgagdqk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtaxjpalwh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtdliixrus.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtbpbmyogm.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gthmnmcnej.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtwcokgkcq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtaghkixcp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtuyalsfcs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtxlwvlorv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtnzhcjfru.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtbpcgkwjg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtynsdpjkx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtdqgnkkbd.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtayphghqv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtcahkgjhz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gttmtcdvlr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtmjnfqhng.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyjehxnf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtkqqweifs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtposzaiph.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtcxkginha.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtngibocba.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtjbjirrez.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gternyrzkg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtyecynrft.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gtevyeqnql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtxdtjzzmj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gthivnzdui.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtoshistal.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpdidqjd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtxwzftgwe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlrnufsft.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtvjjhxcgz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtoeyebdbd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gtzyrcwmnr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtyolzqnzk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtjzghaahk.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtyyvqzxso.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtpazgrblt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtfxkkedzi.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjflfzaoq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtajsgihpg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtovyalenk.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtqgauonvr.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtbtlrvbqq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxdewcrh.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtgkunhpwz.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtqmwryosa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtjigvnpso.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtjahltxis.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtzttptjtf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtkmrsiecb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtlntxtyxe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwffyswuy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjcpdudm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtdczknkxy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtuzocapfy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtfpmlaeur.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtcnrqbssf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtzvvskqel.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtezfnyfeg.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeekuyer.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtuavrpvdz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtxbtqxwig.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtovbmgqcp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtbvrbeyfr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtvrkjdvhe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtpduqqutx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtwezwwphn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtuorfwaqb.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gteaqmoiyp.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslljdefq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtlmamljjr.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjhhjcoe.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtozzckoce.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtvtyomrdt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gthvuqnqia.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gtrzvujmfm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gttfhauips.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtbzkdufdq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtblmtwvvm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtgzfhpwzy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtpfvxzlqs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gttnwbxqog.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtuehhbwkv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtcdydoqsw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtgwswlqgz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtuzyukauy.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtgrudhhdx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtpzfbcyff.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gtcznmgoby.html


<!-- 参考信息 -->