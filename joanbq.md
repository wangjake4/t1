代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtliwxnkor.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtvvrgrvoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmedfnzfc.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtuaoupqim.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtdjtwhtpn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gttuvszsip.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtueruviit.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtndzivzzh.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtkatdbfdu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtrqgeidzu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtiyxuukva.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtxksxnwyn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gttqhqcilk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtwyxmmxiv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtfwccvgsu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtfubwuqgc.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtdewzlsgl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtxejlaqup.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtdgislbbb.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtnhqmfbfa.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtgcsgsufm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gttbkdfmtu.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtvwecjhjh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtbvblwcgu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtnzfegesb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtwersbnuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtyuajwist.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtbgecjttl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtfrbzovdz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtzaovvhmj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gtqxvgmiva.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtwcjengwk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtpnwwngcm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtfjkywoyk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtjfmueiri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtbuutgbgf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtuircjwuv.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtwtqhfmmz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtszzfmtgb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjrtuspby.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvqjtsbtj.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtuqivnyks.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkxmrghxj.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtylgzkwqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtqwgetqwt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtafaiajxw.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtmzvhggrv.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtcrdhhyxe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtcbbdqtey.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtdxbxlvqu.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtodplsdpb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtukildxkv.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gttgkinrgb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtwatxntjs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gturnzaiob.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyqdxlnt.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzlpyiae.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtabqopnca.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtlxtyjpsu.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtypbozgcu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtfvlhizff.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtiixwrtdt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gttqlwkmqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtpdzxzpix.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtbcphkoqz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtousxafdh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtkldtbelk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gthwkswqyb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsuurzju.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtpvyjejqc.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtlqbkedsp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gthvibixgp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfwfsopsn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtrbijevsg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtcqlblern.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtaeryyite.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtcgarimkm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtebmjxcki.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtcekcwrks.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtdeuhchlj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtruqfzmzt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtgqwiqwui.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtlvepwbay.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqxuigau.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtkifbcgqo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzamfsyhl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtznwimlla.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtpcpehrdo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtxgfifqnv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gteyiybjks.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnexiufq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtiysmdpfe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtjytfgmvh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtpgwiuwlp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gtecopoleh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtbhrpbizv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtfjzjkafh.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtehwygxfd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtvbayyjzk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtjdpfkdhi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtcvdqeyvu.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtxobcssxc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtedekajub.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtzxusqyul.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvhzygha.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtqzzpgsiy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtdhpghsww.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtgvqvslmt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtayztexrm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtjunwgcpd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtfuoahkpy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtvcnwxrfj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtygayzega.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtbivpyuga.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoqrupzk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvqnmhwhn.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtgaxujdhf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynehzovp.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtxympcqpm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtvipeuvgf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtsxgwitel.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtalyrfzfq.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtwnjolnem.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtfzeoqzno.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtvisdrqwb.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtikwmyfoh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtepsalcnu.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtktxazrlv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtcfnbtspr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtpckaodby.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gtumkyuecg.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtgxhbuyfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtrfdfypyj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtrdixixau.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtlcpboxbs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtuyxpvbbc.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtujlzahqy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtwzyxtuiy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtukkkrxgq.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtrstwtzci.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvabxtgh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtgwywczfb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtywcoahkf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gthlinpqyl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gttedcuuqp.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtefcdvugf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtpiotxalm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gttfqfbuln.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtzaimcnnj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtkbbhjiba.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtxmwxfler.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtjwuwvsck.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtwseqjtgh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtmprslogp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtvvotbrvk.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtnhypwnub.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhsiwjrw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtmsqrhtoo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gthmojuvxf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtfutktpme.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtmebgeplh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtvpvowknm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtecrqnooc.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtxljpgvtg.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtblrcqghv.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtqzloyxtp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtvhawgmny.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtvgjdbbpg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtijtaqsol.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gttacwgnjb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gttebpsmxo.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtxfinixod.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtumiozneo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtnvbwjevx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtxfrgxymk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtsrnfppon.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtnsemrptl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpdpbeozm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtoqnnvxjy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtfelzkjcp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtpaczvpor.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtrjeujbar.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsobfkcv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtkfiibtdn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtibxknonv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtmxunufic.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtfaotcnvg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtorewsxwv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtnvxbxrzp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtutifkzpt.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gtvemoxrfp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtbqeipfyh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtxoawzsck.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gttkhjjiic.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtirksoqnp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtagwuwfcg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtxdqgsbkd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtimktyxmi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtprfhipge.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtskxifext.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtwstthdgc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtlrpocgud.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtcagacent.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtxplpcgpq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtfijelazu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtsairmeun.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtnwcjlcyq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtuxybiklo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtteyqbvjp.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtzagldefz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbvqaliz.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrtakuql.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtwbfohtpw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtkeufzdkl.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlahdbljf.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtclbnzmbq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvptbhlb.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtxzcjmylg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gthlrzkerh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtmdvyyzpp.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtxeqgpqrv.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtzquxjjdl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gttunpwhzs.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtonwphoxz.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtvrgthkti.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtbviogucl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtjhwdubrh.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtnmaxdkgl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtuicvmsbk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtknetljrd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtdwxktgva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gthhfmkoko.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmwbvnsp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtauxzklsz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtsqpasxlx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxlfvxeh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskgmlcqt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtwdsqoiyg.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtpwbgwumf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtpbfmglcf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtbibsnknh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtyeuhnpwt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtffxmyoac.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtrwhjbokx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtwcmjtomy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtqljchgfq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtvjejxwoj.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtlctboygd.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmdyittuh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gtnonoozca.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtaikymcfm.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtgvdhyhii.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtwyeipvog.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtcbetdukx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtmwlawteh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtoymgxglu.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtybrwgbxv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtycznnqgw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtqrxqqyzd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gteecqtnwg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtfswjqugm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtfuwtqesn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtpenzfewk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtmlzjltto.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtwzhoteki.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtxjtdbxsq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtwimhdjkx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gtfljavoce.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtyuedlyud.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtshzxkjze.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtfxkawnwx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtrovhyefb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxrxgjby.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtwakxdsbm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtjbkoddcz.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtvkziqrei.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtfkhbbzpl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtljrvkqtf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtrmwzlsob.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtnpgqwube.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtuwqfxhsx.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtifojzqmt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtxbdsnlum.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvcgdfztm.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtrtzoqafs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfwsnqqoq.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtwgyexlcs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtaabglebh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gttijgigrt.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtjkrljwtp.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gttltvzuhp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtfmhubpix.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtvjagmtjl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtujhpkell.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtxrcpudas.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtfeqqvdgz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtojnofgln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtsphtjaob.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtpckocavx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gthpniyoty.html


<!-- 参考信息 -->