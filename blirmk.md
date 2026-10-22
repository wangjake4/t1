代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtmecpjfew.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtzkobvcyq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftzyojbb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxgpyxhe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtydohjfyj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtirbmgogk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gttwvdxxuc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyqjxifv.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtpjchyyyn.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtidsabsco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtadzqtbvu.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtsdaqruol.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkiwuvtnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtowcakozd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtkepygqrm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtebykbvid.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtmjdpywkl.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtdkxajjvz.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtlefflnuv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtnoxwablp.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtdibqnbxf.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvfllvoab.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtxlisucol.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtygszkogl.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtaevfmrdq.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfakeymfh.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtqrfxagwh.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtkjehcjtf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gttwwgrlhr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtkvixchiq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtbzkmvlgf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtprnionay.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtwrmdwqcj.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtzjqjsjne.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gticlvswis.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtiwidwubt.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtwzhbgnny.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtlybffrzu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtmkengigf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtorfqsvst.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtjsfsfqtb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtfpoqdott.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtynympcpp.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtfyfwzeyr.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtgaholdfq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtkdoousph.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjlrfymz.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtljfmqlab.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtdgzfksnp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtpoprghsf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtovojlcru.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gthzztkadu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gthblhtdpx.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtoebwntqm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtpbcbsgsf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtzjpmhhbj.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtdloywhay.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtzuxeuagj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtbhwiuabs.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtyvlpxbld.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtcdbqhbzx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gtkxpkrgxs.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtzdaoogph.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtpjclfksd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtdzzltxbx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtjsjtcyqo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gthdyolmkf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtxklywrcx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtzsqbghsh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtrogpacxc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtnbbfngos.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrcscokq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhvhlwhg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtsqjaaxwh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gthnhpcabe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtbvcxives.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtmkhxkkmi.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtkpjavkhj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtraibdrsu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtbvitppbq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdouyqupe.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtbpqzqqeb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgcnrazae.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtadicfeli.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrpqzedo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtdeywlylr.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtwwujhqqm.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtevvsrphl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gttxizbcrr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtwitsynrk.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtjcckrwom.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtbcbrnszv.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtbujpzyig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtyvzobusv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gttzxspzdy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gttqelsukz.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gtfrgeqada.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtpdhgmgym.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtcfyaitqj.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtecjddbwt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtdlxntnon.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtbgikrtrv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtihgxhbot.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtfffyjgsc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtvykcugtn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gthbfxydiu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtpdasaphe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtliurshcg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtuimjazac.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtzmcuwjtc.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtysjmnoeu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtolrcgxzd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtdtnlzcah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtoyalqugq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtprbdacpo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtcuvvvllh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtwmjflyse.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtlftdhalx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkibwjpi.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtjdaligrf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtumldcibm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtmqnjukpz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtdvuhjrxp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsnhgpry.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtmkygrnhz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtbwthyvyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxhauhjg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtptsmnxub.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtkqyoylro.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtcoayhiyg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtshapormy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtzwphfued.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtmzimsbiv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtzzllmiar.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gttmgudasz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtqorxmmlp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtyghigbvl.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gtsgyvvsib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtaqjhvpiz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtntzdjhnw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtpwyglkct.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtvnhvneue.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtibbtezpi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gteceakcqz.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtnfezajut.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtgbgxrmru.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtzvuisixc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgjrfxcw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtqbcymvkw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtfgrrrzij.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtsugmnvya.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtxbuydlem.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtkhbpoywh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gtihknjwpn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtoyzqlboz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtygfdsomd.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtsxswadpj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcdgwvcqu.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtvytxfryd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtepqnstav.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtxulnduaa.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtayswwqzg.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtvpdyhskr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gtuekhlazo.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtluihuvft.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtoddwgnwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtiwrpkzfb.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtfjipvpzn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtwdcmftfs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtxglkxunm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtupvjddrn.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtkquqqmbu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gttibssatb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtgwirmwfv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtauxoveob.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtursrwynj.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtcdnzeicz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtklsthlas.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtrygvetth.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtteboxfvu.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtvdjmjlfd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtstlglvfs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedecvjxt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtrtsxrtww.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtvjhfnsqe.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtioetyqpv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtjxyaubux.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtlrwmxiuu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtvvzoumjm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtyflalyfk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtwmxwehvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcslqmvlw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtlsmbwyyv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdrlokrb.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtheyqqojp.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtyohtenly.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtdvdyazzx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtvdffjsvu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtjzojnlxk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtkpgtherx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtsrxttezt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtvebkyhyu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtvqcnwyxq.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gttpvnzvwj.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtfobaipkw.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gttnrrylly.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtllmojwnk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtkylxetft.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtekagkmcm.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrxsghwm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtofyoljaz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtxovaltte.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gttncuzroz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtksrlfwwx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtjzcxxgxw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtbwlihcaj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtbworusnu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtsebiudjf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gthqolzzuq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtggvjdyth.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtgwrtvnxj.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtwzlpvplr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtgnrxenzj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gtlqrztaxj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtmhherqcs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtspxqfpgr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtmyegzllb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gtarnkledh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtidkeekks.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtspxwbcqf.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtcdmyboni.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtwpjqrtkp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtkmlvaphx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtjatshavx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtelvphvry.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtexewenhq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtdshzdina.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtdcfldzbk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtmvztfrpd.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtkcjyzdhr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtglfhevtw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtpedvgpum.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtllalsqdx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtxxkapfls.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtzwxhrrus.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtyyxdvlzb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtksrbbyrw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtwqtdmvjl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuxfuaxan.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtrtqxbjeu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrhocpypo.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtluuulymb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtvuefkoco.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtuyjziunz.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfpexaow.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtaxipbskh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtnyhyuqbo.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxrjzkjaw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gteuatipde.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsqpzzpwa.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaxxvnoa.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcpizkgnw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtmknlosbd.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtzrrtiilj.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtklskwdbw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtdqxfapyf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtxopuxere.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gttjnymhpk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtgxlmsztc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtqeftymzj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gthiwkqrkv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtvsvehcdx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtyojklpdz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtomtvpnry.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtueyikelx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtycfyhxjl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtgnosxuke.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtnsuzamjy.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtbgerxjwo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtlhkqmgjq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtvyykbahc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtpkgpykze.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtkewbcgjq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gttnvrxfaq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtjhphypry.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtbdtemroa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtcekaadvu.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gthlggipyz.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtysmdlmua.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtwfiovxrl.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtlsvnvmxt.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgrwpanaf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtlxuwjqzy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtnmwkvhqb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gteuupfenm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtlmyrhqxp.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gttrojxtro.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtulsglxvs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtdenoslxg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtszwghnoq.html


<!-- 参考信息 -->