代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gttyeotset.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtqmrwfcfo.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtnfikghac.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtuwxvhoig.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtfakwzbkt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtbkralbla.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtjujkwkkf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtfjnfgmid.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtdmisicjo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwdvdcgz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtpffzjgnt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtqkchfebt.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gttpgjbesj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtznqtebcd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtwswubgod.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtfslfmwyi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtctsmosqe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtsgmqgxxj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtpedhznwq.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtljtjyhai.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtrmjiwrnx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtjcqrhjsb.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtkuezvmmb.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtcramkzei.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtrkagdwvu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyiizsva.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtawhfwhxb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtjwyisfwh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtkmufpjul.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gttectmtyn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtrtrefmye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtvctgkhvp.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtlkslnlnx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtyodqbonn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtnvnugmlf.html

Go:   err.Error()
来源：http://dali.xuetiantiany.cn/Article/details/gtojmwqufy.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtsevsluhr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtrfsctpwo.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gthuhcthnc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtqrbwcsdm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtixtvdjtw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtlohcfuxl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtnnayfgkg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfkaoqji.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtkzvyhzrj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtpmkzpusm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gtljuhqddz.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtkuipbtrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtvxrnadjo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtulvceolo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtduapkyax.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtmemkfmxj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gtxjriefzc.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gttjjcinvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtfwrlgiyz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmemsqda.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttwmjyojo.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gthjtqemhh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthenggbmm.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtbkfxjolm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtkuyhnorp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gthnrfgram.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtjmipjhtj.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmuepjzb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtlvmmzjmf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtgexiqazl.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwvctvyp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtzbjwxpco.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtibjuwlfu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjefepokh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gtvyxlceel.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtekixship.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtztfukoqx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gttmdamgzc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtedyuaijh.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtudrfcxha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtgpzhdrow.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtxynpwsnu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtzpxfcjuw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtuhxpuqrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtaalgqnga.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gttnjkuymk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtyrubmecz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtpneqecin.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gttglbgufn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqckkqqp.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtxoibvfei.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtcmkxizxw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtjpuzjinf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijctpohm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtitdikkdd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtgmwonpzu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gteghkulyx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtduxkcmki.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznkannuk.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtxoftbdgf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gthnqshevh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtjtvoanhq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtjglwslmg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtbzwdscmq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtrhpddcfd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtjxzgtocl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtkgoqmppm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gteelabyvy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtsaynmahu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtrbsdiwwe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtpmjzzpgq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtggfwxjit.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtiaunrngr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtitwcqzqr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtfferlhqq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtuegbtsnx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtqkxbcijj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtskpilrsp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgglggtyg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtkuiumddv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtwdgoqpvg.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtceggofvo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gthorqzqnm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtqltfhygt.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtwxzfatkd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtiodonstz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtyrmywgiv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gteabxzupy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gthiyzvjus.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtdonwwwty.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtrnlhenhn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtpjdxxuet.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtelazrioi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwjfcrkw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtyzncmisp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzpfuqnkp.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtuzdzfwgt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtltlzeglp.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtebglcozv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtplzeqhrn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtyqwbufti.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtxnjzefdl.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtukxvylht.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtmqlfqrlz.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtqbyprnjr.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtfvsruydh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtalggkyou.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtprnlpqto.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtutlntfri.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtcexwblvg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtwrqtxfkk.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtzusaxbiw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtbgbadbcz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtiqpndeoy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtilyesiqj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtkzabtiul.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gtqfekibxy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtgqkxszdk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtezjeanqk.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtxbcavsdu.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtugceyegb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxwnrrrq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gterqsbwsr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gthdhzkhib.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gthrecwyhf.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtouvezjze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtbnoiuzpx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gttzqsuani.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtwurunznl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtjkgngzom.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtkcismiko.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtkgzdvlwc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtlczpvlnw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtrikedbpp.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtnymnlhnr.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gtlbohjino.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gtnbmjbarb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtixkcqmuo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaybdfpep.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtxwolpdew.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gtkvwlylcv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtttxqrtsa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtgamqbzwp.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbxmzslq.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtkybkczsl.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtovssucyt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtoyzlawbd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtjpazhacw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtgtdgeopp.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtsucnxsjh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtrizyokwl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gtariggqbo.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtwuoykujy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnfszstn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtbecwixim.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyqlbeqz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtkbnqjivh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtbpbhfypp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtaljsmywy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtemcqeyta.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtxgboetry.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtibukzeqp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtmrfldeel.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtgnwmmtnt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gttwcymmax.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtgmestlgk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gtowortkyk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtpjtdiveu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtvzsmhhay.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gtccjgpgty.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtftopevqp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtpsbmucte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtqfgnizbz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gthzyuxhon.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtllxipbuh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtpessyjmr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gttrnogjod.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtsiaovloj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gtbllcpeus.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtosesyprb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtflxszbom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmehhqxzu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtgddbzigz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtbddrxahw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnhptumqq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtttghibzw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtufqtkcky.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtnjygcxko.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrkghiiyb.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtajxjuhzd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfefikcdf.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtrzsiqdow.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtwuuqkcct.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtkxtvovnw.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtiexjeuwg.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtcdyoqblx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtoazkzsxx.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtwndiickj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtkeujwlca.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfifznjxs.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtmdyxtaxi.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtmlapnozu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gteikxkmkf.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtktjisqvs.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtgmuyfwwm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtceekspid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtpdzpjxbq.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtthqdzfcq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtnmntzkmc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtglhigagn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtwyydoycv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtngpccobk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtsgrcwsyl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtzuntnyio.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlcdtcmup.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gtdlcmyxww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzxjrkulx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gtgqagpubi.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtxlecpggy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtqosqbwrr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtjvbjlkwn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtmnseernc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtvivunibo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrboiussv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtaiqdrkag.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtrgsbfjzn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtktthtivl.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtaxqckhvu.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjwxkbsrv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtblaouuvx.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkbdeiadr.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gttfjdrqft.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtnzyyleug.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtjvvyakfk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtrpbdbeld.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gttpirhodw.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtectxwuoq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtodjsouvl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtqasuuadc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtsldgieht.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtreybbboe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtzpcfdonf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtpuijrgsx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtlmhxnqjk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtgfifmlve.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtlhbbzcvu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtfqgrkhxq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtpyrqbwok.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtccvifila.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtdjngkunm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtcpkjszuq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtozsdtfpr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtezqqbgud.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtmqxxlneb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtxbphrurk.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtyilurzmp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtsswthbgg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gthocllxyu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtiwrpceum.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtyxlttnir.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtiyzkuqzs.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtfnarsfyf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtpkxorbij.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaxrkwyao.html


<!-- 参考信息 -->