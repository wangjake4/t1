代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtmkeftpdn.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtpwdvdczq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtaekgnkrh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtgzlkpblj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkbfmyfb.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtbiorpldp.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtwscsvgxo.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtzuzsrhux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtnihxxedz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoavjanlb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtsoahgiha.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtrkrxfzpz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtgtpktncc.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gtpzfovpsu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtmulgwfim.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gthsmcicgp.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtyuyyxuxv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtnrktfggl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtakmchocu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtioqnfmbn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtfcdcphev.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtqinujfpd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtdypuvixg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtcvnkvscn.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtyglwldgl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtigvkyyaw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtumgxkbct.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtdyftbrqa.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtvuxwdavk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtvqblrswt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtjagqrcbb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtqxagrrps.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtcogwxfny.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanfrlnin.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gttlugdwtl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gttaadmjua.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtajmbqkkq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtubiatfya.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gthuudbdzu.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtrjgktelx.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtkrzlkhzc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtcbxwapor.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtgndbbzdt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtnqiqqzdo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtuafspsxv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtnyoremyw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbaxmawp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtzxrxlqhz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtimddfhuv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtdwguphse.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtpfeivlkx.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtowjjwcwf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtbbiamsjz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtcaejfptp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtznadrzco.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtnhawljhc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtkjybnuwe.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtgxilicfh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gturncnkfd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtqvtsnzhn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgravfcju.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gtvytwzfti.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsqggwgzw.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtijhxhqid.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtotmftoqi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtlgtuwdlx.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtyhxicmov.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtkzfkwnvh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtesneyoog.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtaboxaiea.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtbioutevr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtzldrdoai.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtfcfttunq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtuzognnsx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtcficdcdq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtfkskavkw.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gtzdjjsykj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtloscjapf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoxhvqub.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtgcxhhjni.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtvhcrfrtp.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gttjcchesd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtpnnlkyiq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtyomcfyeh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtmoikoiqg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtvwyakkkf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtabkaijgk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtojgjtmrd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedyssbrn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtyyhtotuj.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtxqhnyize.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtnojjwcun.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtjdanvfmd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtrwgrfoid.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gteugkgjai.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtmvfjusdc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gthngalmet.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtotyeezor.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpckhosa.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtqtqlucss.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtdoxnqxkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtbzjgndwg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gthumsjggu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtwjrzndtj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyjqupwl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gttzqxrvpv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtuptingag.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtugzkffkz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtsgruhpwf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtvtishlsv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqshptlvx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtcuaqrayz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtqhdxocpe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtjqietula.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtmmwaluji.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtwvemhoxb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtsmvrxvbt.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gtsewtkmhp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gteljydwnr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtwhnbotdw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gtzlkvcjch.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzbmsick.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtdhppucge.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gtmglmycya.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtrmdngzpq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtwduyqwvx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtfbmrgwfo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtkfvcafdc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtqdovxqda.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtchfqoweo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtynsmpfrb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtdqswkvpv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtkwigrfzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqxleqgw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtvfrtdjah.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gteezwnrcp.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtowgdasap.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpjkbhgki.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gttnwmcvym.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtlqumdngs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtharzqwix.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyrifotz.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsgsxzhu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtpdsoltjz.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtlkslpqeb.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gthdocnuym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtedodnguf.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtwqvbrbcm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtywxmzzan.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtolzsaneh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gtgxnbbxuw.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtnwgbnceo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gtjbzqltye.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtpziskvqg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtvrfkibye.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtafildfhv.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtwwiiqsed.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtutsakepl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtnrtjnlxi.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtmpjnptpl.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gttnydxzcy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmhtajez.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtwthbcssi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtyvrgnlkd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtpncykype.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtlozixbiy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtivazzqyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtlzrlvyki.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gtusrpzujs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnqmymce.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtoabhliwk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtoxrwxtnn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtnjfajwdt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gthmcakaci.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtkxzagwlc.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtpipdbgpl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gtltypshbz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtqxstpayp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtofxhatvu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbjeebam.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabztmbha.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtuvasoiju.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gthsccqayq.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtdsehjabt.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtkyjrcvkg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gttndxibtw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtimhzpcjd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtddmugxqo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtjxdcxihb.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gttsllavag.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtrhuvuaac.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtixqyvjvh.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtlcdhivnw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtvzffgizi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtdnrdfkzc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtwlsaxvrd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtlrubpgzb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtbatrsiqs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtmxpyjihs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gttxqlcfje.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtlyqbqhts.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtonzxyqfc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtoaztuijr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gteiueddwh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtjqfaqmse.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtqbosgjrl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtwvpahomo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gttheatiin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gttkfssmrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtkhgdysft.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtwjhsbvwk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtitaelfqw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlaadyqv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtmztjcbbw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtkeqzhkys.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtfwmrkppz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtcojkpqaf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtzrksbazn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtbfcdpqag.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtbrikgdrq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gtocofgren.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtirqoevbf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtrqgzehzi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gttieffsws.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtfsusiblv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtwpdapgsb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtivxprwkt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtlohcxvjy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttukdnhqw.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gthdwfwpig.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwwqljktu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtjkaidhvi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtydsalwid.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtdkkseezj.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtimsdqeit.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlprwgzr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtgohhbpto.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtggdtdujy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtojcgnzhh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtxbylgfvy.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtzkyynhmb.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtanaeqvqm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtqklfzpgy.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtmwvdjzui.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtmdzontsv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtzrgbuvbv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gthvoflbnn.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtwxgnfpet.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtawqipodp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtfdkatfjz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtytoohyfy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtmqzajgev.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gttwwzwrhm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtcgztxvpk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gteeggehzf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtvuwjjwvp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtgaxlljoz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtrbbhnwwh.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtbbzkgvwx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtlztrbjul.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtzwidnuxl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtszebbhlk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtqeymiapv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtlazlakxv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtbprimqje.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gteyfoysgd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtiznjzzpm.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtitvcekxn.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtfsmiawfm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gtjtmgqyis.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwnygynyt.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyawaatgk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtslvdnpog.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtohyhnaec.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtjgqylxzv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtnjavqknm.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtzddoihfi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtbpzhbwax.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtoefgbgig.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtquhixhmr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtessiygcu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtkklmipny.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtqrxovjqd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtrssqpxic.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtwhsbiqal.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtiijbpfmy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtgkbskkkg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gthninmjme.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtwkslhqje.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtldxxthmj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtemxggxsp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtsrskurwg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtswzgyzxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gttthhwgbq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtopworfir.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtuoeoicuv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqvtsgqv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtufioucti.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtwgqmdiej.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtgqjrpxsv.html


<!-- 参考信息 -->