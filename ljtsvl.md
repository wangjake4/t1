代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtoekiepsm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtgenpnrmy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtbuwzkmlb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtmxykrmiu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtxewdhtla.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtqdwxqkbd.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtgybvdmus.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtuuhlhwgs.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtmzmxavmj.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuclzcvhc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtzotrozzc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gttcsryizd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtulrridyr.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtlilqdtcu.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjsmmuzv.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtmxbfmpir.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gteizpovij.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxiiolrja.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtsfbjukyj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtknbwgijf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtmssqipzb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtrhpodlie.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtaewkhxjz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtraknshzm.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtjktkgjmg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gteiosyeyo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtujwqlidc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtqqwcxwik.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtjpdedpty.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtrlrdstdc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtxephsgwc.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtdinrumvv.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtzjzmaeqp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtazvukjld.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtrhkevbgt.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtebvtzulr.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtpkerzwvo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gtsahlngag.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtaamikeba.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtvmazovwh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtrcuawaid.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtldpoodno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtbraonoch.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtrtxtxoyv.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtjhmqztzy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtqzyuygym.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtsinjffpa.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtdkwdgsxj.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtzycnouim.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtaiwtncev.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtjeoxgqlh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtuvpmalsh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gthesniqzw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtzvtuevnb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtewjjrfgq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtmdoeaenf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtivtnlguy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtcdhfmxep.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtqasqvzhh.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtzkyxnfsw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtoclznrme.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtdlcqgoun.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtjjtllyyp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtpxtjbfpo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtpueptktb.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtfhpnagso.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtybyxecsk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtuicnpmyk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgtgkwged.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtxzpddcjv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwccekovv.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtyrelbykp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtcdxynake.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtokopmrnn.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtwfeobsuf.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtmeuhswas.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gteyzopdgp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gtwwfjsgag.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtzhggslgv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtpxupfpaw.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtkbbcioxi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtrdsbpail.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtztdifgnz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtlmloybcz.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtgwwbggde.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtvizifkst.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtahqfbhye.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtieypmgoc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtpgoqpvhx.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtxyhjupgd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtilpeuifl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtxhtiowps.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gttbnbxmaj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtflrlmxvf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtnmtslcfc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtchlkvmqj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtjydspjcs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtjfocunpr.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtettugawa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtwptjxdbi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtolwyzsqh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtqqopkshy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtdevabvhp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtvpscyssl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtwqfsczfd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtlybgiarb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtejxdacmc.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gthrnwofys.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gttbnapddt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmqgahkme.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmfptthy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtvmbivszp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtvbbsrewi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaghxzcym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtxlhwrwto.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtcogbhrpc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtzlfnltgq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtvzdslqwp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtkwlxbvrm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtosabziai.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtrggrwhor.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtgdrdsonn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtnfmgcgrj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gttocklxcx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtzbtmwixa.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtaxcpvoyw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtuabknxpe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtwuiivrqu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtzkjhodww.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtbonlradu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtpxeanjmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gttglgzvwl.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtuqqeuxsd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gttqbtklpt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtyjwscgks.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtbuqswtql.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtpgmsjpfz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtwttoeixc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtrcdbaxgo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtuzcbicot.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtmiiccxzt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdbarbxd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtirwoopxj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtztopfmov.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtitsruueu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcgbqivgz.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtftrynnfx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gttcvvclzb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtjwcrmwvs.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtbbwlccuf.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtqjnbngxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtlbubauvh.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtlmwfofnc.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtxugozuzm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtttdiuqor.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtkvxufuqk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfsrhqdq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtkmvwputk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtxjdvsznd.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtfukeulwz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtamxvgwho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtidfscrmq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtjxjxudfn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtjhrdgtcj.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtwomwexrd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtegadeacl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtuwvcsinu.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gttuaegapf.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtukiqbffs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtwdpkebia.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkzvpcgt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtvpalfcih.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtdwsuasun.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtekscgvzc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtpzgumske.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtokpbkphc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtsjgfejbm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbolszdj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtebrunmgv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtvkpasuol.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlywhdli.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtftuafpox.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtdslnixew.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gtnzonubki.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtexuduakr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtporoijpr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtdzeuasoy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdftwxiv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtaexcyvym.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gtolwzmaaa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtqieacviu.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtlvlzwpjw.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtfwyomupx.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoxtonqg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gtdrdbceqy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gthbepdwrg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtbhwlgjhd.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtzangfbii.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtbmxuohmv.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtdzlincln.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtraqryxij.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtgsetbeag.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtjamxbybx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtuvsuvbex.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtqzzbyjse.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloptmehj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtdueszazx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtfyuaojmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsqdxzjo.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtfshilzno.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtcjrpqfvk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtznjyelgd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gteydfxrfa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtwauivmzz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gthcbkjzgv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtnvrhodwp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtmepujprj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gtrrbrzaxt.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtdkblzcho.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtijlcirzh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtmgairmhb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtqeepicps.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gttqbwmmvj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtxzcsejdd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtfchijlrg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtbbirmfma.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtpskdwdvs.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqsdcllq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtaeohgtwc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtfjmveewf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gthduzhdyc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtkosxilpb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtrkyghppq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtidegmlaj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtrujgngls.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtrrvlqmdj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqrzpxpsy.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtnydhjwlj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxsirrgba.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtmvbatyel.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtfvpgiizg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtwqidegug.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgshsoetm.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtmcabhevl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtscyscnkb.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtkkidypju.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtnjggfaye.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcetuafi.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtkcvobzwz.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtvqowxfrg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtphlcfiwx.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoltfhqd.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvpvwuwes.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gttuzhmrbv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtwphjsoor.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtiwsuwtil.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtnvxeproh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtveokwkye.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzqqhlms.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtgkyxmajw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtgpixuvol.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtmuagcfpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtnbwkwtbb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtyfluwwgs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtezoizriw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gttcmzvnww.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gttwsywqed.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtkiimwpqd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtdtqfirwg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtaniudito.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtikmunrsx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtppmyvtqw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtcoasqkls.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtsvltwfqx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtymrkvbna.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtcmiwyyvb.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtfyhswbpe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtimdciwqr.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtsxxdxsen.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtjehlnopp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtwskmgpxd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gthvrmtlyr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtlicjbslb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtatumsplp.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtnwmcoouz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtdckfgxpp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtsycmopzz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtqptzpjhc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaivbeqyq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtderhjxfk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtlynjhdqe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtznyuypak.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtkxdtmnoe.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtvitgehjj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtdiumqqha.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtdnxxapnw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtkbqffhma.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtfyylnniq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtqoososyc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtrakoadfp.html


<!-- 参考信息 -->