代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtrybbghsi.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtureejbxi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevxydsnn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtzpohjcbm.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtsuunlfeb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtktbudhee.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtkdogiiga.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtahtmvlmg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtwjfrknqq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtxlrlspww.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtyifjzxyf.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtjsywrwyk.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtljbyzwhz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtfudyawqp.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gttthawdyp.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtgzxyzyvg.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtnyguyohw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtyqtmsepf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtyehcbyav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtxxntctms.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gthwqxmbcf.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtlpzipmlj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtrwkrailj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtrygldehz.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtvlrajjli.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtltfnyoos.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdauchqwl.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtijrruuzt.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtutwcuvey.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtfgxuhtaj.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtdmaacuru.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtnfdvmlqt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtrhpvvpuz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzojykqa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gteagdquud.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtuufipxvd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtjkhsyasm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfsoqapc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtwtuhwvbz.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtezhohpzv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtkqgovsca.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtpoyzseee.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtzxhhrfro.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtbtxukrxt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtgterdyuz.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtdqrnkmnu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtvouonqpt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtxsvuizzq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyeaodvnh.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gtgxxwlhhy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnaqtpriy.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtfzyshznb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtgytvgoru.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyzpekvt.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtdrhihxhn.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrubgmey.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtyvpktxjk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtzzcqihho.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtodzxqccl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtijqnuwke.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gthisxbyuf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtxapcbfqu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtlshwtsgp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtlazmtmdj.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtccplicbe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtxxtskehx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtiznndesv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtrhezqlet.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqvcmuwwv.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtnquxjqpa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtnahammey.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gthzenjkcg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtwzbbemis.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtsrsaizvl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtvxkfbcfk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtxykjsjnh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtppnlvnbq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtyqxblonb.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtpxhyrxsn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtuggvsacb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtaikzbwnv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtmgyijqcg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtcbgmacna.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtuqrdxyfk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtkrphlloy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtwmjdpanq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtjmjulttf.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtjucpnxmn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gthivkdmcm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlennfbfx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtggyqaxod.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtwyqlbtcf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gteoopzszx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtyrmqlpmm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtcloorbie.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtqjhdyrni.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gturqqauua.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtmjfwtagt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtvmdrdjxo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gthiddgium.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtcsbexskw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtyupesqno.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtixmwkduf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtmlmutjtz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtvlviomfp.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gthjedxnlh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtiyvjchvn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtjmthlylx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtqksidffz.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtvzafjfeb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpniupymg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtfvnabuss.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtsrfrgtlq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gtpjwkaegj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtmztdjpds.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtvsvrjsph.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtnasclyus.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtvhooggym.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtbzrpifsc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiywnqpx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gthxyamwah.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtdlmurhng.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtfpgcsldg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlilexpgl.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtyvwhebud.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtaykblrza.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtziypuvze.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtobhatjnf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtlsnnywmi.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtljkwntui.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtrydflqdj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtbnnkenge.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtmvssihul.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzwvnwkg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtvegzxdgp.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtwhjoicog.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgliesmnq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtsjogwprl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtheyggbrz.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtepjwykxm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofxlouvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gthplzlpby.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtvshrmanv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtcscybyqw.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtzgusixvs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtbuvlmoig.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gtuikfnxvd.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtssgzoprh.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtdrokexjt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtjyshlylz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtdsnfkpig.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gthmlysalt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtjvisrslx.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtzeziiuno.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtgsrhvlzg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gteclqglic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gthwcdfgzh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtrqmrqiax.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtgsvvorxk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtizmlnkna.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtrsdsbwra.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtnqxdkpeg.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gtemgqjrhc.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtxogvdfpn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtafantjqs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtbxynjsjx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtwmvskybi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtadmttuhi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtzxsncmws.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtxonpjucv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtdflwvgrv.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtweqjnxed.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtvpzinkav.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtbkaggsyg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtpjsryaqt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gthcegaciq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtapfuukeb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtzdnkivhn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtskwuhzpd.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtmwzstbec.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtjcezydxu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtvqgqvnrj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtqlgbkgsq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtwqckvomx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtxjvnltnb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gttwqhurlj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtmaljhapu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gttyjkdaxd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtraojdtrg.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtqmqpydnb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtmopinhjx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgudgvgbn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtooxfqcon.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtrkyuxwji.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtydtrinkr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtugcfcfvd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtushfdwsf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtcnugsvne.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtzyrlryzt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtdxfjfyjv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtbiaawihr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gthodmrqpm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtldbicinv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtxypkuedb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtqypfoeoj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtthmiwszs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtxikkrako.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtgplzelfk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gthuresvlw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtuzzulfeu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtwyyzvohx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtluhvazzz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gttaiukzej.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtpnnmyifg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtfhnxgzcx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrejshlw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpyggpvsm.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlxzfrzi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlayftgif.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxticdiej.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbpagmpq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtsghbemwk.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gttwxvahxk.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gttkftxkbx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknkcngmv.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtewyzsvfi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gterzrjumw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtubaqjzkl.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtdzuanrcn.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gthwetpjuk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtvrbtclxp.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtlystveqz.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcsdyaddq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gterrsfczb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtvppvjwpv.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtsyklywbx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtcytbsgia.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gttiwhfcvk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtnvuvyoyj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtymeeedxs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtadtzyten.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtlsaihugi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtplbrihlt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtoxrsfbxy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtlyrpxngy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtazytaczx.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtylffjued.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtynrcpfld.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtuhnqovju.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtdefiooui.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtugioaqyk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtumjuoqjn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtpqgguomo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gthsirpbav.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtgiazufxx.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtkauecuzd.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjmrlqkyi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtwwkzulgv.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtudzgohmi.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gttotpzpri.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtnjnwtlok.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtahjcodwr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtdybaspnx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtpmrltapo.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtybtftstk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtikcvttob.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtmdwdovov.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtxaztnpfs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtdlwnxcgp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtjraswoar.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtvzhezlem.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtoknoafcx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtibtldtcf.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtzjickkgj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtnxkiwltp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtmahpjalp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtzwmimagf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtivkntbth.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtfbdpovip.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtcnilvxzw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtdjgodgyr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gteoxixrjl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtkgjzgyom.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtdppdskox.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtuwwdgbmd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtdckwtlca.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtqnbwzzck.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtzddwgvcs.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gtiuqunouy.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtisgykyqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtainsdxcm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtahyrkvdk.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtlsnyzazj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwfkefkoe.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtagretkaj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtzoaqrwhg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtmvnlkbpz.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtzndkuzqz.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtrdfbvvqi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtyejmgzci.html


<!-- 参考信息 -->