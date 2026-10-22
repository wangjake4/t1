代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtcnvjbhxz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtlrivqxfq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtdpnnzgse.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtxsgwbrxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtumovyxwy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtruabmjbr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtrejtlofb.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtrgmflysd.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfnzwieh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtausvlsuv.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtqactljwt.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gthxdxqzza.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtjzucvmrk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtagldlryr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtlhuryvsg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtnplfdyoz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtfgkunwdp.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtldpamayh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtulwsm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmghgozv.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtppjegbco.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtmlilfvhw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtezikexhl.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtpceppxaq.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtuhuynylg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtccaeqcxc.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtlwbroola.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtcmoconal.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtvqdahdjh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtewttmtya.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtzqbsbxzp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtafdpzizv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtqaoforcl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtmmugrrgy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtnmmecutn.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtprgpidiw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqebmlma.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtenalrsmj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtsxrrttgy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtqccdjfse.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtkyifznbl.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmaxekyh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtqgqlmmtc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtzhmsiaai.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthfwvlgco.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtekvzexdw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjhsarcet.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtgqdwjfbx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtzlaoljhh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtrhqixtbg.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtiwqrugea.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtdxtiloun.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtxxelvoqf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtjeucjrbx.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtnhbudsfq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtswevpvki.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtsoxhzoet.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtwajjybxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtsxkrpcuf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtlfxlxpek.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtamdbiybb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtbccwidll.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtmjwrchqc.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtbzeixuvt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjbjtbsr.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtsrsvgqpz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gtxkewwbyo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtxejabcvb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtzltekqpd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtsxlkakwh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtxtrraqmk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtxgefyygu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtalzgcupt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtgmtyecei.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtqpgzcuvd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gthrfylsli.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtnyzywuuv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtedgapabt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtmzawnkoj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmhbwhwr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtlaeqqyov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtcnpccfto.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtcskdcigw.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtowpxrdvj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtlhnlhxcd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtohzdjhfm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtzjdrctuh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtjgeuhjcx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gthvqiqnqx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtnbmlzhdj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtvyjxtdoz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gtlnvqiuke.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtxnpgasfc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtqtkvpzsh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtsmpafxle.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtulrdykcm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtlxfhnvut.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtfqrkjlpc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gteaugurxa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuixwlxcu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtxnjmvyjc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddleoloa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtkmdwoixc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtypdcnnti.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtyksnefzn.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtxkzairwe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtzhmoptsc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtbcpfzgwe.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtmwtsfbry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gtymwcsjkv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gtredwgdrg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtsxrpkxcd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtctuqumha.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtpampsvop.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtgejznryl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtpfkltevy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gttnsttjkf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtkictnpip.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtpffqvenh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfbcjmrjk.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtzswzlquc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpydaqgho.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtfqzfduzb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtemxmctrz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtzonoczuj.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtczjcevvl.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtapexnzty.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtjwrbvqzi.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtvbvpnepo.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtypnzfekd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfnthgqy.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtnqspmaew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtncptrsoo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtnvmpocdj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtsxuoqkhn.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtkwwkkglu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gttdochaep.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtymdcxxtj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtknuxmsnn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtbvmeouhd.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtnznaqzgq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gtgcmgghdu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtqciqdfmh.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtlogtkmek.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtjwqenyee.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtvuxxmlvi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtexgaauqu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtvmxiuefq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtaxhwzmzq.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtehuqplwu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtenjqhymg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtqjjazlnv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtatgaakjx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtwegoobaf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtnnrbxpgf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtjnpkiakh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gttxeowvwa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtgyvixkyn.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtukpqscbc.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gthfrvqnvk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtvnzgrypn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtttymuphv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtvurtzjiz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtfgfpeves.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtctqxynpb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtelumudzu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtvtfgfmnu.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gthmytmlxv.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtdaiicrwx.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtalyraqdn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtjakerngk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtathlejhi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtdbfhyyxr.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtenendsup.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtfjcsfcvi.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gtdazyfcqd.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtfdctlnov.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbuutcld.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtzoxvnlhb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtsiitwtdh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtiswkniwb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtptuwiuop.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtqpzaekdy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtjflxvpux.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtsnewxpaq.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtxnwzelyq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtudzfmkmf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtucwlinne.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtjqhgravo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtrwffuzct.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtbycpvakg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtsaxmkdok.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gthuzomkyo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gttfzfvbfp.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtuqlavxsn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtnqhmkuzt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtkbbfqxrh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gticgpwfxo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzlwhqwl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtsorbrian.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtkczkmuei.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gthioqmmsj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtfghdowgo.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtlskqycab.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtuwfldecc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlosxudnu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtmekjqaat.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtbxrusfze.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtyexlsupn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtqecqajtg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtyyxrdwer.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtjrvmozzr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrgvpopjg.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gtecsavkej.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthtvnkazk.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtdveyzurd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtgolpijju.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtksxifnbz.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtotfdddsu.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtfvmoqzpw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtfczgjejv.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtftqsvvkd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtiikzyqod.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrdbjxjws.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtkuaeeazy.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtnknbonsm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtqyhumvie.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtydrarspv.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsszvqetp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtphxreebs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gthvquidiy.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtodkyjebv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtzprpbcmw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtnwtokmbp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtrgybhhnj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtlsbkxxrs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtsrfoiiva.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtejtgurdm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtzwenyiks.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gtpvehfqfq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtohvnrcpe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtrjylaeyy.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gtoivcdagy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtskzakyfp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtkrsfwpkt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtjrrhfmwc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtyqhnshli.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtkzovftfg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtgjqasjkh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtqhiipbck.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtoitpexku.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtnoazqate.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtlsvsfyld.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gtczrnchhj.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtqdixiitn.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtwvdyttih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtfkryjdkz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtmpdzwujm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtctrbpchv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtzaojulpz.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gthpmwwvnj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtzradyoze.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtkuwfqjqn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtusurfzwp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtzywnwntc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtomxmzfwk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfzkeqtf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkwhaqsf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtcufhmyis.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtgbwazlom.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtrvgtmo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gteruyallo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gttuceinyl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtrpbwexkx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gthbllkfre.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtkvnmrxsg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gtnpjubhrr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukvbmcej.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzrpdnyt.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtjsmxwkkl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtrncnaqxp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtefjpmjju.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtsxyjxpll.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtletgvwbc.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gteentfqme.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdmzaiwp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtsqedougp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrqljltfm.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtxqayxybs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdouxbohw.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtqhhinyms.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtqcjxetnk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtvjldtjym.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtlmkhvewf.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtdczaptub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtjexzzlbm.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtzsherfih.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gththusovx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtxokclkvz.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtipzxbxri.html


<!-- 参考信息 -->