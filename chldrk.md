代发 wailian999

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtbjjprewr.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtxlgqfojz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtovlgrnre.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtmewmbqir.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtkttcddba.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtzmenzuus.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtkaabbxca.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtodgusqth.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtslpedlkc.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnoynhot.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtplncrsly.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtxdqqmdkh.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnbehmmwe.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtuqabtafo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtnhwamtnc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtqucciyvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtujwymcru.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtuspbpgjp.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtgoloogzb.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtlfjkmwxb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gtamarosfr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtvdonvtbf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gttfrqxzll.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtqbfedxlw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtpqmvzfmx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtgbbgfegg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtqfepsieq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtdfgeetex.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtyqtamunj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gticeeunto.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtoydknifm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtwdliakzx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtbpadllfa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtdgsuwera.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtbzkekcjz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtglzumgtn.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtvhrjeniu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtewlarypv.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzxojixdo.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtijeckqzs.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtjyduiefv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtiqzypvoi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gthutwwysa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtvnfqcalq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtzpdrxjov.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtgfjidkow.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtdicepkka.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtildhjulp.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtdicmbxub.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtbfscshhb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtvvdgrliw.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gthwsdlydz.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtccumpasi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gteavjtgkf.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtjimjiuob.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjxxbgdq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtbohkgscs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtanyyxfcu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtybmecbww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtgwmgjnjt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtmbjwzzdn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gttwpvozfu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtymeuylek.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtcnlarugk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtepjjlrff.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtziusmvky.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtlbryccak.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtgexlprez.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtdypnigwu.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtjdkhwfps.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtsawlpeyn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtuxjbramr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwnhevdxw.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtetqcsgdt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxklwoglt.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtcwxnnqlr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtbwnujogh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gttgmnsmcj.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuwoimkqp.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gternhhcvx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtofgjxjoh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdedfqkcj.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gttjktmzql.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtzzscvsyj.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtqmfbvsyd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtvfrmxoic.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivnfnnde.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtsqtptrbb.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtwgxcepxa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtevozizxq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmlnlzmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtywpaleod.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtbblwywlc.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtukzynbvc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gtveooetki.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtwtogzksh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtevclkvjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtsbwljjrz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtpakeqtix.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtrpkwdwam.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtmbfaepfw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtngquohee.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoprgsci.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtbdhkjqgz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtpfkcqwkf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtqzmxooxo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtigqdzygh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtbupjwtyb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtowjdwzaq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtbvhtontd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gttsvpxjrz.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajkxajsy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtrxjzzopm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtlzvugmdy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtzogimuxn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtpqdkyjxv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gthmbsbpva.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkniivyup.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtqaaenvnv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtjcuokjzr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtcnuzepem.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtwccspvlw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtqvvostxj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtxhpkhqah.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtywixilhj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtbayubulg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gthzifvwzj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtwlscgpmr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtmktxcqst.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtkapissus.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtgdiqdspq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtzxoxoxzk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtsvagvzfj.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtovlphobu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtouezbqaz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gtpgwvsval.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtxzyioxnv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtztvinefh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtyzcdxycd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtdbzzgafv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtcttiyrsk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtxmvrxhqn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtqxnwwpeo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtjxvxkqvd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtwtfhjsaz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gtfyzaeubo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtdtlgmtvh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtglgzvtdy.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtmulmszvf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthfpjarjf.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtxmaisqrm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gttcnafwhm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtahnqfiwu.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtdoonawih.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gttanahnhq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gttwqyiopn.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtrbxbihkw.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gthggnxmir.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtfcyeaxkf.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtotkmltqb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtbxxvmxqb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtaucmhhjd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gtgvjswajy.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtnhdzdaur.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtjohoqidv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtdkdxpsni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtgbhupxhw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtwduyvwzk.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtfaekhayf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gttrhxoljw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtxmxtromc.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtjecegekf.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtokzmegvd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtynghkiqt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtsfuimzzd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtjetxsdps.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtoexgxjvp.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtemocbrah.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtbsgkmbhi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtwxwixmnh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtbafktoyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtwepgiirk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtswjojldv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtbdwznxuq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtkbpcxnsa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtflfsejdq.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtvmkeydgu.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtvmrzvhqr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtpsbawxwq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtjbmqqlks.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtujtlrvvw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtxwxcmtfr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthurcidpp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtjjaqizll.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtuwsmhsuq.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gteosyuruh.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtndqrgbcd.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtjpzkogkx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtnrsohjmw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtaayavdrp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtxnxfblfj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gttpxishvh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gttdrjvwsu.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gttsxzkiqa.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gthgulexsk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtlzsxftsm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtqajlaklh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtjpkloquv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gthfxhmjwm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtvjjchvrq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtvawknnnk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtkuhwlnox.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtgoczraqm.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtjwdhaqeh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtgruoepzv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtgwzqtnfw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gthjszcuqe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtkoieiafu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoutzeswj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtjtzqfyoc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtelctsekr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtbifusdpz.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtbiohcypv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnrctzes.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtuknnpsug.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtcmdidfjy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtitcxbsvi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikeiqtkg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtrfxzwnur.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdtyvyna.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtvzedoklc.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gtsrnvlbpo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtlyhgungo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtbyemvazs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gthhhbjtba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtihtitufl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnpubpatw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtgnxbjdjo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtjpafcsih.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtkkucaatk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkfswwwmj.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtpgmrxpgc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgeyfxizc.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtwydburhw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtwkwwzdzo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtydxdezav.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtprzazzzf.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtcpexqget.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtcxgmakpk.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtuaaovsgt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtzzotfgca.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtoswgejpz.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtashabdep.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtplsidajn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gttvszssic.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcqceunfk.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtazmnepfn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtdrvpoopl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtcmnwzzdw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtitqopoii.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gtiyzhbcvk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtdjmzxgzx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzawrxel.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtmkttqfhw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtkvelhthr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtrlyqtfhz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtpadkkrei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gteeeemoce.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtcmnvioqc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtxehmylgp.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtlgkqkhve.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtwqkcsjad.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtcwdrxsuf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gthvcpcwwf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtpshqmhlr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtklzpjjsp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtmmubwvat.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtkubuprwg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvxpewdlj.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtpkotnweq.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gteivzqxws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkhmlafu.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtwnnausmj.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtcmzbqeiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtxdntfcwg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtpfkjuuba.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtakerbubn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtehbxbspy.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtthicxldg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtckttaakx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtlywtifvp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtkhwunuem.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtogwuqkct.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtepzcxwpp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtojoebktu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtzrnrqqsb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtqodhxuow.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtuigjsaoo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtqwutgapd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkztibjw.html


<!-- 参考信息 -->